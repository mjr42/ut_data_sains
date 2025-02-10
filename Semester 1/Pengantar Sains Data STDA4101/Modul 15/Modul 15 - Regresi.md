---
tags:
  - sains_data
  - materi_15_PSD
---
Salah satu algoritme eksplanatori adalah analisis regresi, di mana peneliti harus memiliki sebuah variabel bebas dan terikat. Variabel bebas kemudian digunakan sebagai prediktor atas variabel terikat. Konsep regresi amat mudah dan dapat digunakan untuk penelitian yang bersifat sederhana. Misal, bagaimana hubungan antara jumlah data latih dengan akurasi hasil klasifikasi.

Algoritme eksplanatoriberusaha menjelaskan suatu modelberdasarkan pada variabel yang memiliki hubungan linear. Kemudian dievaluasi tingkat signifikansinya secara statistik.

## [[01. Regresi Linear Sederhana]]

#### a. Bersifat Positif (Linear)

Hubungan antara variabel bebas dan terikat dapat bersifat positif atau linear, artinya semakin besar nilai prediktor, maka akan semakin besar pula nilai variabel terikatnya begitu pun sebaliknya.

#### b. Bersifat Negatif (non-linear)

Sementara bersifat negatif atau non-linear jika hubungan antara prediktor dan variabel terikatnya berbanding terbalik.

Atau dengan kata lain, semakin besar nilai prediktor, maka akan semakin kecil nilai variabel terikatnya, begitu pun sebaliknya.

Perlu dipahami bahwa berhubungan belum tentu kemudian memiliki hubungan sebab akibat. Peneliti perlu memastikan hal ini lebih dalam dengan melakukan kajian literatur yang berkualitas.



## [[02. Multiple Regresi Linear]]

Seperti halnya regresi linear, multiple regresi juga bertujuan untuk mene-mukan hubungan antara variabel. Hanya saja variabelnya lebih dari dua atau dikenal juga dengan istilah multiple. Variabel bebas atau prediktor dapat berjumlah dua, tiga, atau lebih, sementara variabel terikatnya dapat berjumlah satu.

Pada multiple regresi peneliti akan melakukan analisis kekuatan hu-bungan atas semua prediktor terhadap sebuah variabel terikat. Misal, ba-gaimana hubungan antara ukuran data, jumlah data latih, dan algoritme klasifikasi yang dipilih dengan hasil akurasi klasifikasi.



## [[03. Decision Tree (Pohon Keputusan)]]

Asumsi yang digunakan pada analisis regresi linear dan multiple regresi adalah terdapat hubungan yang linear antara variabel bebas dengan variabel terikatnya. Namun bagaimana jika hubungan tidak linear? Namun variabel bebas tetap bisa digunakan untuk memprediksi variabel terikatnya. Maka kita dapat menggunakan algoritme pohon keputusan.

Algoritme pohon keputusan bekerja dengan cara membagi dataset ke dalam bagian-bagian yang lebih kecil. Tujuan dari algoritme ini adalah untuk membuat model yang memprediksi nilai variabel terikat, pohon keputusan menggunakan representasi pohon untuk memecahkan masalah di mana simpul daun (leaf node) adalah label kelas dan atribut direpresentasikan pada simpul internal (internal node) dari pohon.

#### a. Asumsi Pohon Keputusan

Asumsi yang digunakan dalam algoritme pohon keputusan adalah sebagai berikut.

1. ﻿﻿﻿Seluruh data latih dianggap sebagai akar (root).
2. ﻿﻿﻿Skala dari fitur yang digunakan sebaiknya adalah kategoris jika bersifat kontinu sebaiknya diubah terlebih dahulu ke dalam bentuk diskret.
3. ﻿﻿﻿Hasil prediksi terdistribusi secara rekursif (perulangan) berdasarkan nilai atributnya.
4. ﻿﻿﻿Urutan penentuan atribut sebagai akar (root) atau simpul internal (internal node) dihitung menggunakan pendekatan statistik.

#### b. Terminologi Pohon Keputusan

Terdapat beberapa terminologi penting terkait dengan pohon kepu-tusan, yaitu :

1) root note,
2) splitting, 
3) decision node, 
4) leaf/terminal node,
5) pruning, 
6) branch/sub tree, dan 
7) parent and child node.

![[Screenshot 2024-10-27 at 11.19.15.png]]

#### c. Kriteria Pohon Keputusan

Dalam menentukan atribut dengan akurasi yang baik peneliti meng-gunakan beberapa kriteria seperti :

1) entropy, 
2) information gain, 
3) Gini indeks, 
4) gain ratio, 
5) reduction in varance, dan 
6) Chi-square. 

Ber-bagai kriteria ini akan menghitung nilai untuk setiap atribut. Nilai akan diurutkan, dan atribut ditempatkan pada pohon sesuai dengan urutan, yaitu atribut dengan nilai yang tinggi akan ditaruh sebagai akar (root).

Information gain digunakan sebagai kriteria jika atribut memiliki sifat kategoris/ordinal, sementara Gini indeks digunakan jika atribut memiliki sifat kontinu.




## [[04. Random Forest (RF)]]

Random forest adalah algoritme yang menggunakan banyak pohon kepu-tusan atau gabungan dari banyak pohon keputusan untuk kemudian menghitung rata-rata dari nilai prediksi guna memperoleh hasil yang lebih baik.

Algoritme RF merupakan bagian dari algoritmee ensemble learning, yaitu algoritme yang memanfaatkan multiple atau banyak model dalam prosedur aplikasinya.

Banyak peneliti memilih menggunakan algoritme RF daripada pohon keputusan saja karena dengan memanfaatkan algoritme RF ini seperti menggunakan algoritme pohon keputusan berulang kali untuk mendapatkan hasil prediksi yang lebih akurat.

Algoritme RF dikenal juga sebagai salah satu proses pembelajaran ensemble, dimana penggabungan beberapa algoritme pembelajaran diguna-kan untuk memperoleh hasil yang lebih baik.

#### Konsep Random Forest

Terdapat dua konsep utama kenapa kemudian diberikan nama "Random", yaitu :

1) pengambilan sampel dilakukan secara acak dari kumpulan data latih saat proses membangun pohon, 
2) subset atau potongan dari fitur selalu dipertimbangkan saat memisahkan simpul (node),

Namun sebenarnya di belakang algoritme RF terdapat banyak hal kompleks yang berlaku. Ini seperti kotak hitam yang kita tidak pernah tahu apa yang terjadi di dalamnya, walaupun kita masih dapat melakukan penggalian melalui pendekatan matematis.




## [[Semester 1/Pengantar Sains Data STDA4101/Modul 15/05. Menentukan Metode yang Tepat]]

Bagaimana menentukan metode yang tepat? Apakah menggunakan algo-ritme regresi atau pohon keputusan? Semuanya akan kembali kepada jenis masalah yang akan dijawab. Peneliti perlu banyak melakukan kajian lite-ratur yang dalam dengan melihat penelitian-penelitian sebelumnya yang telah dilakukan.

> Jika menurut literatur terdapat hubungan linear antara variabel bebas dan terikatnya, maka lebih baik menggunakan algoritme regresi.

> jika di dalam literatur dinyatakan bahwa terdapat hubungan non-linear be-serta kompleksitas yang tinggi antara variabel bebas dan terikatnya, maka lebih baik menggunakan algoritme pohon keputusan.

> jika model prediksi yang dibangun perlu dijelaskan kepada pemangku kepentingan guna mendukung proses pengambilan keputusan, maka penggunaan algoritme pohon keputusan akan lebih baik daripada algoritme regresi. Karena pohon keputusan yang merupakan luaran dari proses pengolahan data akan lebih mudah divisualisasikan dan ditafsirkan daripada grafis linear dengan sumbu X dan Y pada diagram kartesius.



## [[Semester 1/Pengantar Sains Data STDA4101/Modul 15/06. Kelebihan dan Kekurangan]]
#### a. Algoritme Pohon Keputusan

Algoritme pohon keputusan relatif mudah diimplementasikan, bahkan dengan komputer yang memiliki spesifikasi rendah sekalipun. Terdapat banyak sekali library yang tersedia untuk menerapkan algoritme pohon keputusan, baik menggunakan Python maupun R.

Masalah paling umum yang sering ditemui dalam algoritme pohon keputusan adalah mudah terjebak ke dalam kondisi overfitting.

##### 1. Overfitting

Overfitting adalah suatu kondisi di mana data latih yang digunakan pada proses pela-tihan selalu memberikan hasil yang terbaik, namun memberikan hasil yang buruk pada proses pengujian. Dengan kata lain, model mengenali data latih dengan sangat baik, sehingga hasil prediksinya sangat tinggi dalam proses pelatihan. Namun jika menggunakan data uji yang berbeda, akan mem-berikan hasil prediksi yang buruk.

##### 2. Pruning

Upaya yang dapat dilakukan untuk mengurangi atau, bahkan meng-hilangkan overfitting adalah dengan melakukan pruning, yaitu proses pe-mangkasan pohon keputusan atau dengan menggunakan algoritme Random Forest.


Namun, algoritme Random Forest juga tidak lepas dari kelemahan, terdapat banyak hal kompleks berjalan di balik layar yang tidak diketahui.

Hal ini dikenal juga dengan istilah black box, yaitu semacam kotak hitam di mana ada input dan ada hasilnya, namun kita tidak tahu persis apa yang sebenarnya terjadi di dalam kotak hitam tersebut.