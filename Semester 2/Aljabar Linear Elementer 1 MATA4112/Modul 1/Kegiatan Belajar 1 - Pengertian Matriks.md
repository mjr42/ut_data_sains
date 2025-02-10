---
tags:
  - aljabar_linear_elementer
  - materi_1_ALE
---
# Kegiatan Belajar 1 - Pengertian Matriks

Pengertian susunan bilangan real yang teratur dalam baris dan kolom inilah yang nantinya akan mendasari konsep matriks. Oleh karena itu, sebelum sampai pengertian matriks, kita akan mulai mengingat kembali bilangan real dan sifat sifatnya

Bilangan real dan sifat-sifatnya
![[Screenshot 2025-02-03 at 16.40.07.png]]

Catatan:
![[Screenshot 2025-02-03 at 16.40.37.png]]


## [[01. Pengertian Matriks]]

Sekarang perhatikan daftar jumlah kemeja merek tertentu yang laku terjual selama sebulan pada suatu toko pakaian menurut ukuran dan warnanya didepan sebagai ilustrasi/contoh lebih lengkap berikut ini.

#### Contoh 1.1.1
##### Daftar banyaknya kemeja polos merek "A" yang terjual dalam bulan Juni 1996

Daftar banyaknya kemeja polos merek "A" yang terjual dalam bulan Juni 1996 digambarkan pada Tabel 1.1.1.
![[Screenshot 2025-02-03 at 16.42.55.png]]

Tabel 1.1.1 di samping kanan meng-gambarkan jumlah hasil penjualan kemeja yang dikelompokkan menurut dua karakteristik, yaitu warna dan ukuran. Angka dalam daftar adalah jumlah anggota masing-masing

kelompok tersusun dalam empat baris dan empat kelompok.


##### Daftar kadar gizi dan harga bahan makanan per kg (kilo gram).

![[Screenshot 2025-02-03 at 16.43.07.png]]

Pada Tabel 1.1.2 termuat daftar kadar gizi dan nilai rupiah dari beberapa bahan makanan. Kadar gizi dalam gram per kg dan harga dalam rupiah per kg. Daftar pada contoh kedua ini berisi bilangan yang tersusun dalam 5 (lima) baris dan 4 (empat) kolom.

Susunan bilangan seperti yang terdapat pada kedua contoh di atas disebut matriks, yang definisi formalnya akan kita tuliskan sebagai berikut.

#### Definisi 1.1.1 (Pengertian Matriks)

>1) Matriks adalah jajaran bilangan real berbentuk persegi panjang.
>2) Bilangan real yang terdapat dalam jajaran yang membentuk matriks disebut unsur matriks.
>3) Matriks (berukuran) m X n adalah matriks yang terdiri dari m baris dan n kolom, setiap baris memuat n bilangan, dan tiap kolom memuat m bilangan.

##### Cara menuliskan matriks (umum) berukuran m x n:

![[Screenshot 2025-02-03 at 16.44.52.png]]

- Angka pertama (kiri) pada indeks suatu unsur menyatakan nomor atau urutan tempat baris yang ditempati unsur itu (dari atas ke bawah).

- Angka kedua (kanan) pada indeks suatu unsur menyatakan nomor atau urutan tempat kolom yang ditempati unsur itu (dari kiri ke kanan).

- Jadi a, adalah unsur matriks A yang terdapat pada baris ke-i (dari atas), pada kolom ke-j (dari kiri), i dan j bilangan asli dengan 1 ≤ i ≤ m dan 1 ≤ j ≤ n. Misalnya, a,, adalah unsur matriks 4 pada baris ke-3 dan kolom ke-7.


#### Contoh 1.1.2

##### Daftar banyaknya kemeja polos merek "A" yang terjual dalam bulan Juni 1996
Matriks yang terbentuk dari Tabel 1.1.1 pada Contoh 1.1.1a adalah

![[Screenshot 2025-02-03 at 16.46.28.png]]
##### Daftar kadar gizi dan harga bahan makanan per kg (kilo gram).
dan matriks yang terbentuk dari Tabel 1.1.2 pada Contoh 1.1.1b adalah

![[Screenshot 2025-02-03 at 16.46.58.png]]

Matriks K berukuran 4 x 4 dan matriks G berukuran 5 x 4.

##### Pandang matriks

![[Screenshot 2025-02-03 at 16.47.44.png]]

Matriks A berukuran 3 x 5. Unsur pada baris ke-2 kolom ke-4 adalah a4 = 12. Untuk lebih memahaminya, diberikan ilustrasi sebagai berikut.

![[Screenshot 2025-02-03 at 16.48.01.png]]

##### Contoh bukan matriks

![[Screenshot 2025-02-03 at 16.48.18.png]]

Menurut pengertian (definisi) A, B, dan C bukan matriks, karena: 

1) A mempunyai unsur yang bukan bilangan real, yakni @ dan 0.

2) B tidak terdapat unsur yang bertempat pada baris ke-2, kolom ke-3. Baris kedua dan kolom ketiga hanya mempunyai dua unsur.

3) C terdapat unsur yang berupa bilangan kompleks yakni V-5 (bukan bilangan real). Walaupun demikian, adakalanya kita memerlukan matriks dengan unsur bilangan kompleks, tetapi bukan pada Aljabar Linear Elementer 1 ini. Pada pendahuluan sudah dijelaskan bahwa pada pembahasan aljabar linear elementer ini dibatasi hanya untuk bilangan real.




## [[02. Jenis Matriks Berdasarkan Ukurannya]]


#### Definisi 1.1.3 (Jenis Matriks)

>1) Matriks baris adalah matriks 1 x n
>   
>2) Matriks kolom adalah matriks m x 1


#### Contoh 1.1.3 (Jenis Matriks)

1) Matriks baris A = [0 1 3 -1] adalah matriks 1 x 4

2) Matriks Kolom:

![[Screenshot 2025-02-03 at 16.51.07.png]]

#### Definisi 1.1.3 (Matriks Bujur Sangkar)

> Matriks Bujur sangkar orde n adalah Matriks berukuran n x n


#### Contoh 1.1.4 (Matriks Bujur Sangkar)

Contoh-contoh berikut adalah matriks bujur sangkar dan ordenya.

![[Screenshot 2025-02-03 at 16.52.04.png]]

#### Definisi 1.1.4 (Unsur Matriks Bujur Sangkar)

![[Screenshot 2025-02-03 at 16.52.24.png]]

Untuk jelasnya lihatlah ilustrasi berikut ini:

![[Screenshot 2025-02-03 at 16.53.24.png]]

Perhatikan!
Yang dimaksud dengan diagonal suatu matriks adalah diagonal "kiri atas - kanan bawah" (yang bergaris penuh),bukan yang "kiri bawah-kanan atas" (garis terputus).


#### Definisi 1.1.5 (Matriks segitiga bawah)

> Matriks segitiga bawah adalah matriks bujur sangkar yang semua unsur di atas diagonalnya adalah 0.

#### Contoh 1.1.5 (Matriks segitiga bawah)

1. Matriks-matriks berikut adalah matriks segitiga bawah
![[Screenshot 2025-02-04 at 14.52.09.png]]

karena semua unsur atas diagonal adalah 0. Unsur-unsur diagonal dan bawah diagonal boleh nol atau tidak nol, karena pada definisi matriks segitiga tidak ada pembatasan nol atau tidak nol untuk unsur-unsur diagonal ini.

2. Matriks berikut bukan matriks segitiga bawah, karena ada unsur atas diagonal yang tidak 0 (yang dilingkari).

![[Screenshot 2025-02-04 at 14.52.41.png]]

#### Definisi 1.1.6 (Matriks segitiga atas)

> Matriks segi tiga atas adalah matriks bujur sangkar yang semua unsur bawah diagonalnya adalah 0.


#### Contoh 1.1.6 (Matriks segitiga atas)

1. Matriks-matriks berikut adalah matriks segitiga atas, karena semua unsur-unsur bawah diagonal adalah 0.

![[Screenshot 2025-02-04 at 14.54.01.png]]

2. Matriks-matriks bujur sangkar berikut bukan matriks segitiga atas, karena ada unsur bawah diagonalnya yang tidak nol.

![[Screenshot 2025-02-04 at 14.54.15.png]]


#### Definisi 1.1.7 (Matriks Diagonal)

>1. Matriks diagonal adalah matriks bujur sangkar yang semua unsur luar diagonal yakni unsur atas diagonal atau bawah diagonalnya adalah 0.
>   
>2. Matriks diagonal yang semua unsur diagonalnya adalah 1 disebut matriks satuan diberi notasi I,, (n banyak baris atau kolom).

Dapat juga dikatakan bahwa matriks diagonal adalah matriks bujur sangkar

![[Screenshot 2025-02-04 at 14.55.24.png]]

Matriks diagonal adalah sekaligus matriks segitiga atas dan segitiga bawah. Perhatikan ilustrasi di bawah ini.

![[Screenshot 2025-02-04 at 14.55.55.png]]

Tak ada pembatasan pada unsur-unsur diagonal apakah 0 atau tidak 0. Unsur-unsur diagonal a, b, c, dan d boleh 0 atau tidak 0.


#### Contoh 1.1.7 (Matriks Diagonal)

1. Matriks-matriks berikut adalah matriks diagonal
![[Screenshot 2025-02-04 at 14.56.34.png]]

2. Matriks-matriks berikut bukan matriks diagonal
![[Screenshot 2025-02-04 at 14.56.41.png]]

karena untuk tiap matriks ada unsur luar diagonal yang nilainya tak nol. Silahkan tunjukkanlah sendiri!

1. Matriks-matriks berikut adalah matriks satuan.

![[Screenshot 2025-02-04 at 14.57.23.png]]





## [[03. Kesamaan Dua Matriks]]

#### Definisi 1.1.8 (Jenis Matriks)

> ![[Screenshot 2025-02-04 at 14.58.15.png]]


Jadi dua matriks sama, apabila ukurannya sama dan unsur-unsur pada posisi (baris dan kolom) yang sama juga sama.

#### Contoh 1.1.8 (Jenis Matriks)

1. Jika diketahui:
![[Pasted image 20250204145849.png]]

maka A = B karena ukuran kedua matriks sama yakni 2 x 3 dan setiap unsur pada posisi yang sama juga sama.


2. Jika diketahui:

![[Pasted image 20250204145927.png]]

sika diketahui bahwa P = Q maka haruslah p = 3.





## [[04. Penjumlahan pada Matriks]]


#### Contoh 1.1.9 (Penjumlahan Matriks)

Di sebuah toko pakaian setelah tutup pada akhir bulan terdapat persediaan kemeja polos merek "A" warna putih dan biru ukuran S, M, dan L seperti dalam daftar berikut.

![[Pasted image 20250204150055.png]]

Pada keesokan harinya, jadi pada tanggal satu bulan berikutnya, sebelum buka toko, datang persediaan baru yang dipesan sebelumnya yang jumlahnya seperti dalam daftar berikut.

![[Pasted image 20250204150115.png]]

Bagaimanakah caranya mendapatkan daftar persediaan pada tanggal satu sebelum buka toko? Untuk itu kita buat dulu catatan persediaan berikut.

![[Pasted image 20250204150128.png]]

Dengan demikian, diperoleh persediaan sekarang sebagai berikut.

Untuk mendapatkan bilangan pada posisi tertentu pada daftar terakhir, bilangan-bilangan pada posisi yang sama pada daftar pertama (saat tutup toko kemarin) dan kedua (saat buka toko hari ini) dijumlahkan.

Kita lihat, ukuran matriks yang pada daftar pertama dan pada daftar kedua, sama. Unsur pada posisi tertentu pada matriks terakhir adalah jumlah unsur matriks yang pertama dan matriks yang kedua pada posisi itu.

Sesungguhnya begitulah cara menjumlahkan matriks, menurut definisi yang akan kita tuliskan, matriks terakhir adalah jumlah matriks pertama dengan matriks kedua.


#### Definisi 1.1.9 (Penjumlahan Matriks)

> ![[Pasted image 20250204150218.png]]


Dari Definisi 1.1.9 jelas bahwa yang dapat dijumlahkan adalah matriks yang berukuran sama. Matriks yang ukurannya berlainan, tidak dapat dijumlahkan.

#### Contoh 1.1.10 (Penjumlahan Matriks)

Pandang matriks-matriks berikut ini.

![[Pasted image 20250204150310.png]]

Apabila dijumlahkan, maka:

- ![[Pasted image 20250204150324.png]]

- ![[Pasted image 20250204150336.png]]


Lihat kembali Contoh 1.1.9, Tabel 1.1.3 dan Tabel 1.1.4 dalam bentuk matriks masing-masing adalah,

![[Pasted image 20250204150400.png]]

Kalau kedua matriks tersebut dijumlahkan, maka menghasilkan

![[Pasted image 20250204150410.png]]

Mudah dilihat bahwa sifat penjumlahan pada bilangan real berlaku juga untuk penjumlahan pada matriks.

Arti pengurangan matriks dapat kita lihat pada contoh berikut.


#### Contoh 1.1.10 (Pengurangan Matriks)

Andaikan persediaan kemeja polos merek tertentu pada sebuah toko pada awal adalah sebagai berikut

![[Pasted image 20250204150507.png]]

Jumlah kemeja yang laku terjual pada bulan tersebut dapat dilihat pada daftar berikut.

![[Pasted image 20250204150518.png]]

Susunan bilangan daftar persediaan pada akhir bulan adalah matriks dari bilangan pada Tabel 1.1.6 (persediaan awal bulan) dikurangi dengan matriks dari bilangan pada Tabel 1.1.7 (yang laku pada bulan tersebut), yaitu:

![[Pasted image 20250204150529.png]]







## [[05. Perkalian Matriks]]

Bahasan perkalian matriks terdiri dari perkalian matriks dengan skalar (bilangan real) dan perkalian dua buah matriks. Perkalian matriks baris dan matriks kolom akan mendahului perkalian dua matriks secara umum, karena setiap unsur pada perkalian dua matriks ditentukan oleh perkalian matriks baris dan matriks kolom.

### 5.1 Perkalian Matriks dengan Bilangan Real/Skalar

Perkalian matriks dengan bilangan real adalah matriks dengan ukuran sama dan setiap unsurnya merupakan hasil kali unsur-unsur matriks yang dikalikan dengan skalar tersebut. Definisi formal sebagai berikut.

#### Definisi 1.1.10

> ![[Pasted image 20250204150710.png]]

#### Contoh 1.1.12

Jika matriks

![[Pasted image 20250204150744.png]]
maka :

![[Pasted image 20250204150755.png]]


Jika matriks

![[Pasted image 20250204150808.png]]
maka:

![[Pasted image 20250204151015.png]]

### 5.2 Perkalian matriks baris dan matriks kolom

Kita mulai dengan perkalian matriks baris dengan matriks kolom.

#### Definisi 1.1.11

![[Pasted image 20250204151113.png]]

#### Contoh 1.1.14

1. Jika 
![[Screenshot 2025-02-08 at 13.51.26.png]]
![[Screenshot 2025-02-08 at 13.51.41.png]]

2. Jika
![[Pasted image 20250208135205.png]]
![[Pasted image 20250208135224.png]]







## [[06. Perkalian Dua Matriks]]

Baris dari matriks A yang berukuran m x k dapat dipandang sebagai matriks baris berukuran 1 x k. Kolom dari matriks B yang berukuran k X n dapat dipandang sebagai matriks kolom berukuran k x 1. Dengan demikian, matriks A terdiri dari m buah baris, matriks B terdiri dari n buah kolom.

Jadi banyaknya kolom matriks A sama dengan banyaknya baris matriks B. Matriks A dan B yang seperti ini yang dapat dikalikan. Definisi tepatnya dituangkan sebagai berikut.

#### Definisi 1.1.12 (Perkalian Dua Matriks)

> ![[Pasted image 20250208135348.png]]



Jadi matriks A dapat dikalikan dengan matriks B apabila banyaknya kolom matriks A sama dengan banyaknya baris matriks B. Jika matriks baris ke-i dari matriks A adalah

![[Pasted image 20250208135431.png]]

dan matriks kolom ke-j dari B adalah

![[Pasted image 20250208135441.png]]

maka unsur matriks AB pada baris ke-i kolom ke-j adalah

![[Pasted image 20250208135453.png]]

Hasil kali matriks AB dapat digambarkan sebagai berikut.

![[Pasted image 20250208135559.png]]

Unsur pada baris ke-i kolom ke-j matriks AB adalah hasil kali matriks baris ke-i dari matriks A dengan matriks kolom ke-j matriks B.


#### Contoh 1.1.15 (Perkalian Dua Matriks)

Jika
![[Pasted image 20250208135717.png]]
dengan
![[Pasted image 20250208135759.png]]

dan 

![[Pasted image 20250208135807.png]]

sehingga,

![[Pasted image 20250208135819.png]]

Sedangkan 

![[Pasted image 20250208135853.png]]

Lak depat ditalikan, karena banyakya kolom Q (yaitu 1) tidak sama dengan banyaknya baris P (yaitu 2).


Jika

![[Pasted image 20250208140024.png]]

![[Pasted image 20250208140035.png]]

dan 

![[Pasted image 20250208140103.png]]

Terlihat bahwa AB # BA tidak komutatif.


Jika, 
![[Pasted image 20250208140849.png]]

Maka, 

![[Pasted image 20250208140906.png]]

sedangkan

![[Pasted image 20250208140922.png]]


Jika, 

![[Pasted image 20250208140937.png]]
maka, 

![[Pasted image 20250208140948.png]]

sedangkan, 

![[Pasted image 20250208141017.png]]


Bila,

![[Pasted image 20250208141045.png]]

maka, 

![[Pasted image 20250208141056.png]]

sedangkan, 

![[Pasted image 20250208141113.png]]

Dari Contoh 1.1.12 jelas terlihat bahwa pada umumnya perkalian matriks tidak komutatif. Kesesuaian ukuran matriks yang dapat dikalikan mirip dengan aturan penyambungan domino seperti berikut ini.

![[Pasted image 20250208141157.png]]

Dalam permainan domino kita dapat menyusun kartu domino seperti di atas.

Kartu domino P[5|3] dapat disambungkan dengan kartu Q[3|4]. Kartu @ ini selanjutnya dapat pula disambungkan dengan kartu R[42]. Posisi yang terbuka sekarang adalah sama dengan posisi satu kartu [5|2] yang berarti kita dapat menyambung di kiri dengan kartu [m|5] di kanan dengan kartu [2,n]. Hal ini serupa dengan mengalikan matriks A berukuran 5 x 3, di kanan dengan matriks B berukuran 3 x 4, dilanjutkan dengan mengalikan di kanan dengan matriks C berukuran 4 x 2.





