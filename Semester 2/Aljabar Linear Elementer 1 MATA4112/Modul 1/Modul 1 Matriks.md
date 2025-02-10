---
tags:
  - aljabar_linear_elementer
  - materi_1_ALE
---
Sistem persamaan linear (SPL) yang muncul hampir dalam semua penerapan aljabar linear, juga sangat dipcrlukan sebagai landasan dalam pembahasan bagian lain aljabar linear elementer. Mencari dan menganalisis selesaian SPL sangat dimudahkan dengan menggunakan matriks. Oleh sebab itu, modul pertama perkuliahan Aljabar Linear Elementer I ini kita isi dengan pembahasan matriks dan pengenalan operasinya seperti penjumlahan, perkalian dua matriks, dan perkalian matriks dengan skalar.

Pada materi aljabar linear elementer, pengertian bilangan akan kita batasi dengan bilangan real. Oleh karena itu, untuk mengerti sifat-sifat operasi pada matriks dan juga untuk memahami materi penting lain aljabar linear elementer ini, diperlukan pemahaman sifat-sifat bilangan real yang sudah Anda kenal sejak di sekolah dasar.



# [[Kegiatan Belajar 1 - Pengertian Matriks]]

Pengertian susunan bilangan real yang teratur dalam baris dan kolom inilah yang nantinya akan mendasari konsep matriks. Oleh karena itu, sebelum sampai pengertian matriks, kita akan mulai mengingat kembali bilangan real dan sifat sifatnya

Bilangan real dan sifat-sifatnya
![[Screenshot 2025-02-03 at 16.40.07.png]]

Catatan:
![[Screenshot 2025-02-03 at 16.40.37.png]]


## 01. Pengertian Matriks

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




## 02. Jenis Matriks Berdasarkan Ukurannya


#### Definisi 1.1.3 (Jenis Matriks)

>1) Matriks baris adalah matriks 1 x n
>   
>2) Matriks kolom adalah matriks m x 1


#### Contoh 1.1.3 (Jenis Matriks)

4) Matriks baris A = [0 1 3 -1] adalah matriks 1 x 4

5) Matriks Kolom:

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

6. Matriks-matriks berikut adalah matriks segitiga bawah
![[Screenshot 2025-02-04 at 14.52.09.png]]

karena semua unsur atas diagonal adalah 0. Unsur-unsur diagonal dan bawah diagonal boleh nol atau tidak nol, karena pada definisi matriks segitiga tidak ada pembatasan nol atau tidak nol untuk unsur-unsur diagonal ini.

7. Matriks berikut bukan matriks segitiga bawah, karena ada unsur atas diagonal yang tidak 0 (yang dilingkari).

![[Screenshot 2025-02-04 at 14.52.41.png]]

#### Definisi 1.1.6 (Matriks segitiga atas)

> Matriks segi tiga atas adalah matriks bujur sangkar yang semua unsur bawah diagonalnya adalah 0.


#### Contoh 1.1.6 (Matriks segitiga atas)

8. Matriks-matriks berikut adalah matriks segitiga atas, karena semua unsur-unsur bawah diagonal adalah 0.

![[Screenshot 2025-02-04 at 14.54.01.png]]

9. Matriks-matriks bujur sangkar berikut bukan matriks segitiga atas, karena ada unsur bawah diagonalnya yang tidak nol.

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

10. Matriks-matriks berikut adalah matriks diagonal
![[Screenshot 2025-02-04 at 14.56.34.png]]

11. Matriks-matriks berikut bukan matriks diagonal
![[Screenshot 2025-02-04 at 14.56.41.png]]

karena untuk tiap matriks ada unsur luar diagonal yang nilainya tak nol. Silahkan tunjukkanlah sendiri!

12. Matriks-matriks berikut adalah matriks satuan.

![[Screenshot 2025-02-04 at 14.57.23.png]]





## 03. Kesamaan Dua Matriks

#### Definisi 1.1.8 (Jenis Matriks)

> ![[Screenshot 2025-02-04 at 14.58.15.png]]


Jadi dua matriks sama, apabila ukurannya sama dan unsur-unsur pada posisi (baris dan kolom) yang sama juga sama.

#### Contoh 1.1.8 (Jenis Matriks)

13. Jika diketahui:
![[Pasted image 20250204145849.png]]

maka A = B karena ukuran kedua matriks sama yakni 2 x 3 dan setiap unsur pada posisi yang sama juga sama.


14. Jika diketahui:

![[Pasted image 20250204145927.png]]

sika diketahui bahwa P = Q maka haruslah p = 3.





## 04. Penjumlahan pada Matriks


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







## 05. Perkalian Matriks

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

15. Jika 
![[Screenshot 2025-02-08 at 13.51.26.png]]
![[Screenshot 2025-02-08 at 13.51.41.png]]

16. Jika
![[Pasted image 20250208135205.png]]
![[Pasted image 20250208135224.png]]







## 06. Perkalian Dua Matriks

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




--- 



# [[Kegiatan Belajar 2 - Sifat Operasi Matriks]]

Pada BMP Pengantar Matematika/MATA4101 dan Kalkulus I/MATA4110, kita membahas sifat-sifat bilangan real. Hal ini mendorong kita untuk meninjau lebih lanjut sifat-sifat operasi matriks. Sudah kita ketahui penjumlahan matriks adalah komutatif, sedangkan perkalian matriks tak komutatif.

Keasosiatifan berlaku untuk penjumlahan matriks. Akan kita perlihatkan kelak bahwa perkalian matriks juga asosiatif. Perkalian matriks dengan skalar ternyata ekivalen dengan mengalikan matriks itu dengan suatu matriks diagonal yang setiap unsur diagonalnya adalah skalar itu. Beberapa sifat perkalian bilangan real yang diturunkan dari sifat grup bilangan real, seperti hukum kanselasi ternyata tak berlaku untuk perkalian matriks.




## 07. Sifat Asosiatif Perkalian Matriks

Untuk membahas keasosiatifan perkalian matriks, perhatikan Contoh 1.2.1 berikut ini.

#### Contoh 1.2.1

Diketahui matriks

![[Pasted image 20250208141632.png]]

maka :

![[Pasted image 20250208141645.png]]

Kemudian,

![[Pasted image 20250208141701.png]]


Contoh 1.2.1 menunjukkan keberlakuan sifat asosiatif untuk perkalian, yaitu (AB)C = A(BC). Sifat asosiatif ini juga berlaku umum untuk perkalian matriks yang dinyatakan dalam Dalil 1.2.1 berikut ini.


#### Definisi 1.2.1 (Sifat Asosiatif)

> Jika A matriks berukuran m X n, B matriks berukuran n x k, dan C matriks berukuran k X q, maka (AB)C = A (BC).

bukti

> ![[Pasted image 20250208142149.png]]

> ![[Pasted image 20250208142200.png]]



Dengan berlakunya sifat asosiatif pada perkalian matriks, baik (AB)C maupun A(BC) dapat dinyatakan dengan ABC saja.







## 08. Sifat Distributif Perkalian Matriks

Untuk membahas sifat distributif, perhatikan Contoh 1.2.2a dan Contoh 1.2.2b berikut ini.

#### Contoh 1.2.2a

Diketahui matriks,

![[Pasted image 20250208142419.png]]

Maka:

![[Pasted image 20250208142431.png]]

![[Pasted image 20250208142500.png]]


jadi, A(B+C) = AB+ AC .



#### Contoh 1.2.2b

Diketahui matriks,

![[Pasted image 20250208142554.png]]

maka:

![[Pasted image 20250208142610.png]]

jadi, (P+Q)R = PR+QR.


Contoh 1.2.2a dan Contoh 1.2.2b menunjukkan keberlakuan sifat distributif. Sifat distributif secara umum dinyatakan sebagai Dalil 1.2.2 berikut ini.


#### Definisi 1.2.2 (Sifat Distributif)

> ![[Pasted image 20250208142652.png]]


Bukti:

Unsur pada baris ke i kolom ke j matriks A (B + C) adalah

![[Pasted image 20250208142825.png]]

Ruas kanan adalala unsur pada baris ke i kolom ke j matriks AB + AC.


Unsur pada baris ke i kolom ke j matriks (P+Q)R adalah

![[Pasted image 20250208142903.png]]

Ruas kanan adalah unsur pada baris ke i kolom ke j matriks PR + QR.






## 09. Sifat Perkalian Matriks dengan Bilangan Real dan Matriks Diagonal

Perkalian matriks dengan bilangan real (di kiri atau di kanan) adalah mengalikan setiap unsur matriks dengan bilangan real tersebut. Dapat dilihat nanti bahwa hal ini ekivalen dengan mengalikan matriks tersebut dengan suatu matriks diagonal di kiri atau di kanan. Untuk memperoleh gambarannya, perhatikan Contoh 1.2.3a dan Contoh 1.2.3b berikut ini.

#### Contoh 1.2.3a

Diketahui matriks A

![[Pasted image 20250208143250.png]]

matriks diagonal C

![[Pasted image 20250208143308.png]]

matriks diagonal D

![[Pasted image 20250208143325.png]]

dan bilangan real c = 3.

maka dapat diperoleh

![[Pasted image 20250208143344.png]]

Pada Contoh 1.2.3a, matriks A berukuran 3 x 2, matriks diagonal C berukuran 3 x 3 dengan unsur diagonal 3, dan matriks diagonal D berukuran 2 x 2 dengan unsur diagonal 3 memenuhi CA = AD = cA = Ac dengan c = 3.



#### Contoh 1.2.3a

Diketahui matriks B

![[Pasted image 20250208144137.png]]

matriks diagonal E

![[Pasted image 20250208144152.png]]

Matriks diagonal F

![[Pasted image 20250208144210.png]]

dan bilangan real

![[Pasted image 20250208144239.png]]

Maka dapat diperoleh:

![[Pasted image 20250208144255.png]]

Pada Contoh 1.2.3b, matriks B berukuran 2 x 3, matriks diagonal E berukuran 3 x 3 dengan unsur diagonal 2/3, matriks diagonal F berukuran 2 x 2 dengan unsur diagonal 2V3 memenuhi FB = BE = cB = Bc dengan c = 2v3 .

Sesungguhnya, dari Contoh 1.2.3a dan Contoh 1.2.3b berlaku secara umum yang dinyatakan oleh Dalil 1.2.3 berikut ini.

#### Definisi 1.2.3 (Perkalian Matriks dengan Bilangan Real dan matriks Diagonal)

> ![[Pasted image 20250208144408.png]]


Bukti:

Ukuran matriks CA, AD, dan cA sama yaitu m X n, Tuliskan:

![[Pasted image 20250208144445.png]]
maka :

![[Pasted image 20250208144458.png]]

Jadi, CA = AD = cA [terbukti].



#### Contoh 1.2.4

Diketahui A

![[Pasted image 20250208144800.png]]

Maka menurut Dalil 1.2.3, bila matriks

![[Pasted image 20250208144823.png]]

![[Pasted image 20250208144851.png]]

![[Pasted image 20250208144905.png]]

Dari sifat-sifat bilangan real, dengan mudah dapat dibuktikan Dalil 1.2.4 berikut ini.

#### Definisi 1.2.4

> ![[Pasted image 20250208144929.png]]

Bukti:

![[Pasted image 20250208144944.png]]

#### Contoh 1.2.5

Contoh ini menunjukkan keberlakuan Dalil 1.2.4.

![[Pasted image 20250208145005.png]]

![[Pasted image 20250208145012.png]]

![[Pasted image 20250208145027.png]]


Seperti halnya Dalil 1.2.4, sifat-sifat distributif lain yang dinyatakan Dalil 1.2.5 berikut juga dapat dibuktikan menggunakan sifat-sifat bilangan real.

#### Definisi 1.2.5

> ![[Pasted image 20250208145103.png]]


Bukti:

![[Pasted image 20250208145118.png]]


Beberapa dari sifat di atas akan diperlukan nanti dalam pembahasan ruang vektor.







## 10. Matriks Bujur Sangkar dan Sifat Sifatnya

Karena matriks bujur sangkar adalah juga matriks, maka semua sifat operasi matriks juga berlaku untuk matriks bujur sangkar. Pandang himpunan matriks bujur sangkar orde m. Pada himpunan matriks ini perkalian matriks adalah suatu operasi biner. Unsur satuan adalah matriks satuan orde

![[Pasted image 20250208145337.png]]

unsur invers mungkin ada.

#### Definisi 1.2.1

> ![[Pasted image 20250208145435.png]]


Dari Definisi 1.2.1, jelas bahwa invers dari $A^{-1}$ adalah A sendiri, jadi

![[Pasted image 20250208145545.png]]

![[Pasted image 20250208145552.png]]


#### Contoh 1.2.6

Tentukan invers matriks A

![[Pasted image 20250208145613.png]]

Penyelesaian:

![[Pasted image 20250208145628.png]]

Tidak semua matriks bujur sangkar mempunyai invers. Hal ini akan diperlihatkan pada contoh berikut ini.


#### Contoh 1.2.7

Tentukan invers matriks B, jika ada

![[Pasted image 20250208145657.png]]

![[Pasted image 20250208145711.png]]

yang menghasilkan 4 persamaan, yaitu:

yaitu: $(1) p+r =1$; $(2)-p-r=0$; $(3)q+s=0$ ; dan $(4) -q -5 = 1$.

Jika persamaan (1) dan (2) dijumlahkan, maka diperoleh:

![[Pasted image 20250208150039.png]]

berarti menghasilkan pertentangan 0=1. Pertentangan ini diakibatkan karena pengandaian bahwa B mempunyai invers. Jadi, penandaian bahwa B mempunyai invers adalah salah, yang benar adalah B tidak mempunyai invers. Matriks yang tidak memiliki invers disebut matriks singular, yang definisi lengkapnya sebagai berikut.


#### Definisi 1.2.2

> ![[Pasted image 20250208150130.png]]


Jadi, matriks A pada Contoh 1.2.6 adalah matriks tak singular, dan matriks B pada Contoh 1.2.7 adalah matriks singular.

![[Pasted image 20250208150153.png]]

Untuk Contoh 1.2.6, det A =(-1x2) -(0)×(0) =-2#0. Sedangkan Contoh 1.2.7, det B = ((1)x(-1)) -(I)x(-1))=0. Tampaknya ada kaitan antara kenolan determinan matriks dengan kesingularannya. Keterkaitan antara kenolan determinan matriks dengan kesingularan dinyatakan pada Dalil 1.2.6 berikut ini.


#### Definisi 1.2.6

> Matriks A tak singular jika dan hanya jika det A # 0 .

Bukti: (untuk matriks 2 x 2)


diketahui A tak sngular maka harus dibuktikan det A # 0 

Andaikan A punya invers. Akan kita nyatakan matriks invers dalam unsur-unsur dari A , yaitu a,b,c, dan d. Misalkan

![[Pasted image 20250208150321.png]]

![[Pasted image 20250208150328.png]]

![[Pasted image 20250208150349.png]]



diketahui det A # 0 maka harus dibuktikan A tak singular

Andaikan ad -bc # 0 atau det A # 0, maka matriks

![[Pasted image 20250208150416.png]]

![[Pasted image 20250208150428.png]]

![[Pasted image 20250208150435.png]]



#### Contoh 1.2.8

![[Pasted image 20250208150538.png]]


Kita periksa determinannya: det P =(2) (1) - (-2) (-1) = 0.

Jadi, karena det P = 0 maka P tidak punya invers. Matriks apa sajakah yang inversnya dirinya sendiri? Matriks yang inversnya dirinya sendiri adalah matriks yang memenuhi

![[Pasted image 20250208150522.png]]



#### Contoh 1.2.9

Carilah matriks A yang berukuran 2 x 2 yang memenuhi AA = I (yakni A merupakan invers dari dirinya sendiri).

![[Pasted image 20250208150606.png]]

![[Pasted image 20250208150623.png]]


Opsi 1

![[Pasted image 20250208150634.png]]

Opsi 2

![[Pasted image 20250208150646.png]]

Sebagai contoh untuk persamaan $(**)$:

![[Pasted image 20250208150709.png]]






## 11. Sifat Sifat Inverse

Sudah dibahas bahwa invers suatu matriks bujur sangkar adalah tunggal, begitu pula invers dari suatu matriks yang inversnya matriks itu sendiri. Sekarang akan dibahas sifat-sifat invers lainnya. Sebelumnya kita bahas Contoh 1.2.10 terlebih dahulu yang akan mengantarkan kepada sifat-sifat invers tersebut.

#### Contoh 1.2.10

Diketahui matriks

![[Pasted image 20250208150829.png]]

Tentukan

![[Pasted image 20250208150840.png]]

Penyelesaian

![[Pasted image 20250208150914.png]]

![[Pasted image 20250208150928.png]]

#### Definisi 1.2.7 

> ![[Pasted image 20250208150949.png]]


Bukti

![[Pasted image 20250208150958.png]]

Kalau pada bilangan real setiap bilangan yang tak nol punya invers, tetapi kalau pada himpunan matriks bujur sangkar maka ada matriks tak nol yang tak punya invers (singular), seperti terlihat pada Contoh 1.2.11 berikut.

#### Contoh 1.2.11

Buktikan bahwa matriks tak nol A tidak mempunyai Inverse
![[Pasted image 20250208151037.png]]

Bukti

![[Pasted image 20250208151057.png]]

Pada bilangan real berlaku sifat: ab = 0 dan a # 0 berakibat b=0. Sifat ini tidak berlaku untuk matriks: jika AB = O dan A # O tidak menjamin B = O . Ini diperlihatkan pada Contoh 1.2.12 berikut.


#### Contoh 1.2.12

![[Pasted image 20250208151934.png]]

Menghasilkan dua persamaan

![[Pasted image 20250208151956.png]]




## 12. Transpose Matriks

#### Definisi 1.2.3

> ![[Pasted image 20250208152037.png]]


![[Pasted image 20250208152044.png]]

![[Pasted image 20250208152057.png]]


#### Contoh 1.2.13

![[Pasted image 20250208152133.png]]

Perhatikan, transpos matriks D dan E masing-masing adalah dirinya sendiri. Matriks seperti ini disebut matriks simetri, yang definisi formalnya sebagai berikut.



#### Definisi 1.2.4 (Matriks Simetri)

> Matriks yang sama dengan transposnya disebut matriks simetri.


![[Pasted image 20250208152218.png]]


#### Contoh 1.2.14

Periksa, matriks-matriks berikut matriks simetri atau bukan!

![[Pasted image 20250208152253.png]]

Jawab


![[Pasted image 20250208152306.png]]
![[Pasted image 20250208152330.png]]



