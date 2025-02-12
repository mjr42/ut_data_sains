---
tags:
  - metode_statistika
  - materi_9_MS
---
# Kegiatan Belajar 1 - Pengujian Hipotesis Rata Rata

Pengujian hipotesis rata-rata dua populasi bertujuan untuk membandingkan rata-rata dua macam populasi dan mengetahui perbedaan atau selisih rata-rata dua populasi. Misalnya pada kasus nilai ujian siswa, ingin menguji apakah rata-rata ujian akhir Matematika tahun 2010 dan 2011 adalah sama atau mengalami peningkatan.

Jenis populasi yang ada dapat berupa populasi independen dan dependen. Dua populasi dikatakan independen jika populasi pertama tidak berhubungan atau tidak berpasangan dengan populasi kedua. Sebaliknya, dikatakan dependen jika populasi pertama dan kedua adalah sama, berhubungan, atau berpasangan. Sebagai contoh pada perusahaan daging ayam yang dijelaskan sebelumnya. Jenis populasi tersebut adalah independen, karena kedua kelompok berbeda dan tidak berpasangan. Ayam kelompok pertama tidak diberi makanan dan kelompok kedua diberi makanan. Apabila dilakukan pengambilan sekelompok ayam, selanjutnya dicatat berat badan ayam ketika normal dan beberapa hari kemudian diberi makanan jenis A dan dicatat perubahan berat badannya, maka dikatakan jenis populasi yang dependen. Hal tersebut dikarenakan ayam di kedua populasi adalah sama yaitu populasi ayam ketika masih normal dan setelah diberi makanan jenis A.


## [[01. Dua Populasi Independen]]

#### 1. Varians Diketahui

Dua sampel acak independen dengan jumlah $n_1$, dan $n_2$, masing-masing diperoleh dari dua populasi dengan rata-rata $\mu_1$ dan $\mu_2$ serta ragam $\sigma^2_1$ , dan $\sigma^2_2$ akan memiliki penduga titik untuk perbedaan rata-rata adalah $x_1 - x_2$ yaitu memiliki rata-rata

![[Pasted image 20241123180547.png]]

![[Pasted image 20241123180603.png]]

#### Contoh 9.1

Seorang importir telah mengimpor sejumlah lampu pijar yang mereknya berbeda, yaitu merek everbright dan merek everlight. Importir tersebut ingin sekali mengetahui ada atau tidaknya perbedaan rata-rata usia pakai kedua merek tersebut. Secara acak dipilih 50 buah lampu pijar merek everbright dan 50 buah merek everlight. Setelah diadakan pengukuran, ternyata rata-rata usia pakai lampu everlight sebesar 1282 jam dan merek everbright sebesar 1.208 jam. Menurut catatan perusahaan, simpangan baku populasi usia pakai lampu pijar merek everlight adalah 80 jam dan merek everbright adalah 94 jam. Yakinkan pedagang import tersebut terhadap dugaannya bahwa rata-rata usia kedua merek nyata berbeda?. Gunakan taraf signifikansi 5%.

##### Penyelesaian
Untuk menjawab pertanyaan ini dilakukan pengujian hipotesis dengan langkah-langkah sebagai berikut:

![[Pasted image 20241123180637.png]]
![[Pasted image 20241123180646.png]]

#### Contoh 9.2

Dari Contoh 9.1, dapatkan 95% selang kepercayaan selisih rata-rata usia pakai lampu merek everbright (populasi pertama) dan merek everlight (populasi kedua)!

##### Penyelesaian:

![[Pasted image 20241123180751.png]]
Perhitungan tersebut menghasilkan kesimpulan bahwa selisih rata-rata usia pakai adalah antara 39,79 jam hingga 108,21 jam. Nilai selisih yang positif menunjukkan juga bahwa usia pakai merek everbright lebih tinggi dari merek everlight. Hal ini akan dibuktikan melalui uji hipotesis pada Contoh 9.3.

#### Contoh 9.3

Dari Contoh 9.1, misalnya importir juga menduga bahwa rata-rata usia pakai merek everlight lebih lama dibandingkan merek everbright. Ujilah anggapan tersebut dengan menggunakan taraf signifikansi 5%.

##### Penyelesaian

![[Pasted image 20241123180836.png]]

#### 2. Varians Tidak Diketahui

Pembahasan sebelumnya adalah uji hipotesis rata-rata ketika varians diketahui. Apabila varians  $\sigma^2_1$ , dan $\sigma^2_2$  tidak diketahui maka menggunakan pendekatan distribusi t-student. Pengujian ini mengasumsikan simpangan baku kedua populasi sama $\sigma_1 = \sigma_2 = \sigma_3$ atau $\sigma_1 ≠ \sigma_2$,. Ketika diasumsikan $\sigma_1 = \sigma_2 = \sigma_3$ digunakan uji pooled t-test. Statistik uji yang digunakan adalah:

![[Pasted image 20241123181055.png]]

![[Pasted image 20241123181104.png]]

#### Contoh 9.4

Dilakukan pengamatan terhadap Sungai Mas dan Wonokromo untuk membandingkan konsentrasi DO harian. Pengamatan sampel dilakukan selama sepuluh hari dan dicatat konsentrasi DO setiap sehari sekali di masing-masing sungai. Dari hasil pengamatan tersebut, diperoleh bahwa rata- rata konsentrasi DO di Sungai Mas adalah 2,5 mg/l dan simpangan baku 2,05 mg/l. Sedangkan untuk Sungai Wonokromo rata-ratanya 3,20 mg/l dan simpangan baku 2,75 mg/l. Apakah ada cukup bukti untuk menyatakan bahwa kedua sungai memiliki rata-rata konsentrasi DO harian yang berbeda. Gunakan taraf signifikansi 5% dan di asumsikan $\sigma_1 = \sigma_2 = \sigma_3$

##### Penyelesaian

![[Pasted image 20241123181146.png]]
![[Pasted image 20241123181157.png]]

#### Contoh 9.5

Dari Contoh 9.4 juga dapat dihitung 95% selang kepercayaan selisih rata-rata konsentrasi DO di Sungai Mas dan di Sungai Wonokromo.

Karena kedua populasi independen dan standar deviasi populasi tidak diketahui, maka selang kepercayaannya adalah sebagai berikut:

![[Pasted image 20241123181227.png]]

Sehingga didapatkan selang kepercayaan selisih rata-rata konsentrasi DO di Sungai Mas dan di Sungai Wonokromo adalah antara -2,98 mg/l hingga 1,58 mg/1.

![[Pasted image 20241123181246.png]]

![[Pasted image 20241123181254.png]]





## [[02. Dua Populasi Dependent]]

![[Pasted image 20241123181421.png]]
![[Pasted image 20241123181431.png]]

#### Contoh 9.6

Untuk mengetahui apakah keanggotaan dalam suatu organisasi mahasiswa berpengaruh terhadap IPK mahasiswa dilakukan pencatatan nilai IPK 5 mahasiswa. Pencatatan pertama adalah ketika mahasiswa tersebut masih menjadi anggota organisasi. Pencatatan kedua adalah ketika mahasiswa sudah tidak menjadi anggota organisasi. Ujilah apakah keanggotaan organisasi akan membuat nilai IPK menurun dengan taraf signifikansi 5%!

![[Pasted image 20241123181455.png]]

![[Pasted image 20241123181503.png]]
![[Pasted image 20241123181512.png]]



