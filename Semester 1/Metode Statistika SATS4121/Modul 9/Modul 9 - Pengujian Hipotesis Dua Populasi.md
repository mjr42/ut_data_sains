---
tags:
  - metode_statistika
  - materi_9_MS
---
Pengujian Hipotesis sendiri memiliki arti sebagai suatu usaha menguji parameter populasi melalui pengambilan sampel. Pengujian hipotesis dapat dilakukan untuk gugus data satu populasi, dua populasi atau lebih. Pada pembahasan sebelumnya dijelaskan untuk satu populasi, pada pembahasan kali ini akan dijelaskan uji hipotesis untuk dua populasi, baik untuk rata-rata, proporsi, maupun varians/ragam, beserta selang kepercayaan bagi selisih dua populasi. Pada Modul 7 Anda telah mempelajari selang kepercayaan satu populasi, bukan?

Nah, sekarang bersama dengan materi pengujian hipotesisnya, materi selang kepercayaan dua populasi juga dibahas sekaligus.

Pengujian hipotesis dua populasi bertujuan untuk membandingkan dua macam populasi. Misalnya pengusaha daging ayam sedang berusaha meningkatkan berat badan ayam dengan memberikan jenis makanan A.

Untuk mengetahui apakah jenis makanan tersebut mampu meningkatkan berat badan atau tidak, perusahaan membentuk dua kelompok ayam. Data ayam tersebut dapat menggunakan pengambilan data sampel dari populasi atau keseluruhan data di populasi. Kelompok pertama adalah ayam dengan tanpa diberi makanan A. Sementara itu, kelompok kedua diberi makanan A.

Selanjutnya dilakukan uji rata-rata berat badan, apakah rata-rata berat badan kelompok ayam kedua lebih besar dari kelompok pertama.

Langkah-langkah pengujiannya juga mengikuti pembahasan sebelumnya, yaitu: (1) menentukan hipotesis; (2) menentukan taraf signifikansi; (3) menentukan statistik uji; (4) menentukan daerah kritis; dan (5) mengambil kesimpulan.

# [[Kegiatan Belajar 1 - Pengujian Hipotesis Rata Rata]]

Pengujian hipotesis rata-rata dua populasi bertujuan untuk membandingkan rata-rata dua macam populasi dan mengetahui perbedaan atau selisih rata-rata dua populasi. Misalnya pada kasus nilai ujian siswa, ingin menguji apakah rata-rata ujian akhir Matematika tahun 2010 dan 2011 adalah sama atau mengalami peningkatan.

Jenis populasi yang ada dapat berupa populasi independen dan dependen. Dua populasi dikatakan independen jika populasi pertama tidak berhubungan atau tidak berpasangan dengan populasi kedua. Sebaliknya, dikatakan dependen jika populasi pertama dan kedua adalah sama, berhubungan, atau berpasangan. Sebagai contoh pada perusahaan daging ayam yang dijelaskan sebelumnya. Jenis populasi tersebut adalah independen, karena kedua kelompok berbeda dan tidak berpasangan. Ayam kelompok pertama tidak diberi makanan dan kelompok kedua diberi makanan. Apabila dilakukan pengambilan sekelompok ayam, selanjutnya dicatat berat badan ayam ketika normal dan beberapa hari kemudian diberi makanan jenis A dan dicatat perubahan berat badannya, maka dikatakan jenis populasi yang dependen. Hal tersebut dikarenakan ayam di kedua populasi adalah sama yaitu populasi ayam ketika masih normal dan setelah diberi makanan jenis A.


## 01. Dua Populasi Independen

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





## 02. Dua Populasi Dependent

![[Pasted image 20241123181421.png]]
![[Pasted image 20241123181431.png]]

#### Contoh 9.6

Untuk mengetahui apakah keanggotaan dalam suatu organisasi mahasiswa berpengaruh terhadap IPK mahasiswa dilakukan pencatatan nilai IPK 5 mahasiswa. Pencatatan pertama adalah ketika mahasiswa tersebut masih menjadi anggota organisasi. Pencatatan kedua adalah ketika mahasiswa sudah tidak menjadi anggota organisasi. Ujilah apakah keanggotaan organisasi akan membuat nilai IPK menurun dengan taraf signifikansi 5%!

![[Pasted image 20241123181455.png]]

![[Pasted image 20241123181503.png]]
![[Pasted image 20241123181512.png]]



---


# [[Kegiatan Belajar 2 - Pengujian Hipotesis - Proporsi]]

Sebagai contoh, terdapat televisi jenis A dan jenis B. Selama satu hari, perusahaan mengetahui terdapat kerusakan mesin produksi kedua televisi yang menyebabkan banyak produk televisi yang mengalami cacat. Kemudian perusahaan ingin mengetahui jenis televisi mana yang lebih banyak terjadi cacat. Untuk mengetahuinya dapat dilakukan dengan melakukan uji hipotesis proporsi dua populasi. Populasi pertama adalah televisi jenis A dan populasi kedua adalah televisi jenis B. Kejadian sukses yang dimaksud dalam proporsi ini adalah jumlah produk yang cacat pada hari tersebut.

![[Pasted image 20241123181651.png]]

![[Pasted image 20241123181702.png]]

Pengujian hipotesis proporsi dua populasi dapat dilakukan untuk menguji hipotesis nol apakah proporsi populasi pertama dan kedua sama serta apakah proporsi populasi pertama lebih kecil dari populasi kedua. Selain itu juga untuk menguji apakah proporsi populasi pertama lebih besar dari pada populasi kedua.

![[Pasted image 20241123181718.png]]
![[Pasted image 20241123181730.png]]

#### Contoh 9.8

Suatu pemungutan suara hendak dilakukan di antara penduduk kota A dan kota B untuk mengetahui pendapat mereka mengenai pembangunan mall baru. Lokasi mall berada di perbatasan kota A dan B. Sebagian besar penduduk merasa bahwa pembangunan tersebut akan lolos, karena letak mall yang strategis dan besarnya proporsi penduduk yang menyetujuinya. Untuk mengetahui apakah ada selisih yang nyata antara proporsi penduduk kota A dan kota B yang setuju dengan pembangunan mall, dilakukan pengambilan sampel. Di kota A, terdapat 120 penduduk dari total 200 penduduk menyetujui. Sedangkan di kota B, terdapat 240 penduduk dari total 500 penduduk menyetujui. Lakukan pengujian hipotesis untuk membuktikan bahwa proporsi penduduk yang setuju di kota A lebih tinggi dibandingkan kota B. Gunakan a = 5%.

##### Penyelesaian:
![[Pasted image 20241123181810.png]]


#### Contoh 9.9

Dari Contoh 9.8 juga dapat dihitung selang kepercayaan 95% untuk selisih proporsi penduduk di kota A dan kota B yang menyatakan setuju.

##### Penyelesaian
![[Pasted image 20241123181830.png]]

Selang kepercayaan tersebut menunjukkan bahwa selisih proporsi penduduk di kota A dan kota B yang menyatakan setuju adalah antara 0,059 hingga 0,181. Dengan kata lain, selish persentase penduduk di kota A dan kota B yang menyatakan setuju adalah antara 5,9% hingga 18,1%. Angka yang positif menunjukkan bahwa proporsi (atau persentase) penduduk yang menyatakan setuju di kota A lebih tinggi dibandingkan di kota B.

#### Contoh 9.10

Sebuah studi menemukan bahwa pada tahun 2005 terdapat 50 dari 300 pekerja US adalah milik serikat. Selanjutnya pada tahun 2006, dari sejumlah 400 sampel terdapat 80 pekerja adalah milik serikat. Buktikan apakah keanggotaan serikat pada tahun 2006 tidak lebih besar 1% bila dibandingkan pada tahun 2005 (a = 2%)?

##### Penyelesaian:
![[Pasted image 20241123181919.png]]


---


# [[Kegiatan Belajar 3 - Pengujian Hipotesis - Varians]]


![[Pasted image 20241123182132.png]]
![[Pasted image 20241123182206.png]]

![[Pasted image 20241123182218.png]]

#### Contoh 9.11

Untuk menguji kesevariansan diameter kikir yang dihasilkan dari dua mesin A dan B dilakukan pengambilan beberapa sampel dari masing-masing mesin. Sejumlah 10 buah kikir diambil dari mesin A. Dihasilkan rata-rata 3,5 mm dan simpangan baku 0,05 mm. Sedangkan sejumlah 15 buah kikir diambil dari mesin B. Dihasilkan rata-rata 3,5 mm dan simpangan baku 0,07 mm. Ujilah apakah varians diameter kedua mesin adalah sama. Gunakan taraf signifikansi 10%.

##### Penyelesaian

![[Pasted image 20241123182259.png]]![[Pasted image 20241123182314.png]]

#### Contoh 9.12

Dari Contoh 9.11 dapat dihitung nilai selang kepercayaan 90% bagi perbandingan varians kedua populasi.

##### Penyelesaian

![[Pasted image 20241123182337.png]]

#### Contoh 9.13
![[Pasted image 20241123182349.png]]