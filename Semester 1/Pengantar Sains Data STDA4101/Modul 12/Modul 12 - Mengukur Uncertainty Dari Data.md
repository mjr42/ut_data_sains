---
tags:
  - sains_data
  - materi_12_PSD
---
Mengukur ketidakpastian artinya meminimalkan kesalahan atau kegagalan dan memaksimalkan kebenaran atau kesuksesan yang mungkin diperoleh dari suatu keputusan yang diambil.

Beberapa metode yang dapat digunakan untuk mengukur ketidakpas-tian adalah menggunakan a) Confusion matrix, b) Area under receiver ope-rator curve (AUROC), dan c) menghitung Root mean square error (RMSE).


## [[01. Confusion Matrix]]

Confusion matrix biasanya digunakan untuk mengukur ketidakpastian dari hasil klasifikasi, baik klasifikasi terbimbing (supervised) maupun tidak terbimbing (unsupervised). Jumlah hasil klasifikasi yang benar dan salah kemudian dihitung untuk setiap kelas klasifikasi yang digunakan dalam analisis.

![[Screenshot 2024-10-26 at 20.55.52.png]]

Gambar 12.1 menunjukkan contoh tabel yang digunakan untuk meng-ukur hasil akhir ketidakpastian dari suatu proses klasifikasi. 

>Jika hasil uji dari data sebenarnya benar (aktual) dan hasil model klasifikasi (prediksi) juga benar, maka akan masuk ke kelas True Positive (TP), 

>sebaliknya jika hasil uji dari data sebenarnya benar, namun hasil model klasifikasi salah, maka akan masuk ke kelas False Negative (FN).

>Selanjutnya, jika hasil uji dari data aktual salah, namun pada hasil model prediksi dinyatakan benar, maka akan masuk ke kelas False Positive (FP).

Jika hasil uji dari data aktual salah, dan pada hasil model prediksi juga dinyatakan salah, maka akan masuk ke kelas True Negative (TN), 

dengan memiliki jumlah total TP, FN, FP, dan TN, kini kita dapat menghitung Sensitivity (Recall), Specificity, Precision, Negative Predictive Value (Error), dan Accuracy

#### 1. Presisi

Presisi adalah proporsi kelas yang diidentifikasi dengan benar, terhadap semua titik uji. Presisi akan menjawab pertanyaan "berapa banyak titik uji hutan yang berhasil diidentifikasi sebagai hutan secara presisi".

#### 2. Negative Predictive Value (Error)

Negative Predictive Value (Error) adalah proporsi kesalahan dalam klasifikasi, yang akan menjawab pertanyaan "berapa tingkat kesalahan klasifikasi".

#### 3. Akurasi

Akurasi adalah proporsi hasil yang benar secara umum dari sebuah kelas klasifikasi. Akurasi akan menjawab pertanyaan "berapa banyak titik uji hutan yang secara akurat diidentifikasi sebagai hutan dari seluruh titik uji".

#### 4. F1 Score

Lebih jauh kita juga dapat menghitung F1 skor, yaitu sebuah metode untuk mengukur performa klasifikasi yang lebih baik untuk distribusi kelas yang tidak merata dalam data uji. 

Sebagai contoh distribusi kelas yang tidak merata terkadang muncul dalam prediksi klasifikasi penggunaan lahan menggunakan data citra satelit, di mana sebagian besar hasil Klasifikasi adalah benar dan sebagian kecil yang salah.

- Fl skor dapat dihitung dengan persamaan
- ﻿﻿F1 skor = 2*(Sensitivity*Precision)/Sensitivity+Precision)

#### 5. Sensitivity

sensitivity (recall), yaitu tingkat positif yang sebenarnya, apa artinya? Jika menggunakan rumus TP/(TP+FN) sebagai contoh sensitivity pada kasus klasifikasi citra satelit, akan menjadi 30/(30+25) = 30/55 = 6/11. Dengan kata lain, 6 dari 11 titik klasifikasi hutan berhasil diidentifikasi dengan benar sebagai "hutan". 

Sensitivity (Recall) akan menjawab pertanyaan "dari semua titik uji hutan, berapa banyak yang benar diidentifikasi sebagai hutan". Sensitivity (Recall) disebut juga True Positive Rate (TPR).

#### 6. Specificity

Sementara itu apa arti dari specificity? Dengan menggunakan rumus TN/(TN+FP), akan memberikan informasi tingkat negatif yang sebenarnya.

Masih dengan contoh kasus kelas hutan dari klasifikasi citra satelit, 50/(50+5) = 50/55 = 10/11, artinya 10 dari 11 titik observasi yang bukan hutan berhasil diklasifikasi sebagai "bukan hutan". 

Specificity akan menjawab pertanyaan "dari semua titik uji bukan hutan, berapa banyak yang benar diidentifikasi sebagai bukan hutan". 1 - Specificity disebut juga False Positive Rate (FPR).

#### Perbedaannya

Cara paling mudah untuk mengingat perbedaan antara sensitivity (recall) dan specificity adalah dengan mengingat lampu taman. Jika lampu taman sangat sensitif, maka lampu akan menyala terlalu mudah, misal hanya jika ada daun jatuh dari pohon, maka lampu akan menyala. Jika ter-lalu spesifik, maka lampu taman tersebut hanya akan menyala jika ada orang berlalu tepat di depannya saja, atau mungkin tidak menyala jika malam tiba.

Sulit menemukan keseimbangan antara sensitivity (recall) dan speci-ficity hanya dengan menggunakan Confusion matrix, maka kita dapat menggunakan metode selanjutnya, yaitu Area under receiver operator curve (AUROC).



## [[02. Area under receiver operator curve (AUROC)]]

Area under receiver operator curve adalah sebuah grafis yang menunjukkan seberapa luas area di bawah atau di atas garis melengkung (curve), semakin luas area di bawah garis melengkung dan di atas garis linear menunjukkan bahwa hasil prediksi atau klasifikasi semakin baik. Semakin luas area di atas garis melengkung dan di bawah garis linear menunjukkan bahwa hasil prediksi atau klasifikasi semakin buruk

![[Screenshot 2024-10-26 at 21.07.13.png]]

Grafis AUROC terdiri atas sumbu X yang merupakan nilai dari False Positive Rate (FPR atau 1 - Specificity) dan sumbu Y yang merupakan nilai dari True Positive Rate (TPR atau Sensitivity (Recall)).

![[Screenshot 2024-10-26 at 21.07.43.png]]

Gambar 12.3 menun-jukkan sebuah grafis AUROC atau yang lebih sederhana disebut grafis ROC saja dari hasil analisis perbandingan antara model kesesuaian lahan kawasan perkotaan dengan data hasil survei di lapangan.

Terdapat sebuah garis linear berwarna hitam dan sebuah garis yang berwarna biru yang merupakan garis yang menghubungkan antara nilai FPR dan TPR dari lima kelas kesesuaian (TS - Tidak Sesuai, KS - Kurang Sesuai, CS - Cukup Sesuai, S - Sesuai, dan SS - Sangat Sesuai).


Kita sudah mengetahui bagaimana cara mengukur TPR dan FPR, maka hanya dengan memplot semua nilai tersebut dari semua kelas klasi-fikasi lahan ke dalam sebuah grafis kita akan mendapatkan grafis ROC.

![[Screenshot 2024-10-26 at 21.09.05.png]]

Grafis ROC pada Gambar 12.3 menunjukkan bahwa hasil pemodelan kurang optimal dengan area di bawah sumbu garis linear. Namun, cukup baik karena area tersebut tidak cukup luas.

Untuk kelas TS, KS, CS, dan SS semua berada di atas sumbu garis linear, hanya kelas S yang berada di bawah sumbu garis linear. Hal ini menunjukkan bahwa tingkat akurasi cukup baik untuk keempat kelas tersebut. Hanya kelas S yang memiliki tingkat akurasi yang kurang baik. Dengan kata lain kelas S berada di area FPR sementara keempat kelas lainnya berada di area TPR.



## [[03. Root Mean Square Error (RMSE)]]

Perlu dipahami sebelum menggunakan RMSE dalam menghitung ketidak-pastian bahwa RMSE digunakan untuk data tanpa nilai pencilan (outliers). Jika data yang dievaluasi memiliki nilai pencilan, maka sebaiknya menggunakan Mean Absolute Error (MAE),

#### a. Mean Absolute Error (MAE)

MAE merepresentasikan rata-rata perbedaan secara absolut antara nilai aktual (data uji) dan nilai hasil pemodelan (prediksi) persamaan yang digunakan adalah:

![[Screenshot 2024-10-26 at 21.11.24.png]]

Di mana, y adalah nilai prediksi dan ý adalah nilai aktual 

#### b. RMSE - Root Mean Square Error

Sementara persamaan untuk menghitung RMSE adalah: 
![[Screenshot 2024-10-26 at 21.12.56.png]]

Sehingga kita mengetahui bahwa RMSE sebenarnya adalah akar kuad-rat dari Mean Square Error (MSE), yaitu perhitungan standar deviasi residu, atau perbedaan antara nilai aktual dengan nilai prediksi. Nilai RMSE yang rendah menunjukkan akurasi model yang tinggi, sebaliknya nilai RMSE yang tinggi menunjukkan akurasi model yang rendah. Rentang nilai RMSE adalah antara 0 hingga 1.


