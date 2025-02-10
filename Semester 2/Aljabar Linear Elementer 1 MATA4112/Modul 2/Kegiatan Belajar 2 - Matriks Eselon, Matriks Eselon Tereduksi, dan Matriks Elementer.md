---
tags:
  - aljabar_linear_elementer
  - materi_2_ALE
---

## Kegiatan Belajar 2 - Matriks Eselon, Matriks Eselon Tereduksi, dan Matriks Elementer

## [[04. Matriks Eselon dan Matriks Eselon Tereduksi]]

Dengan eliminasi Gauss, matriks A berikut ini dapat diubah menjadi matriks P atau Q, sedangkan matriks B dapat diubah menjadi R.

![[Pasted image 20250208161003.png]]

(Untuk memperoleh matriks P,Q, dan R dengan eliminasi Gauss silahkan dikerjakan sendiri! ).


Sekarang perhatikanlah ketiga matriks P,Q, dan R :

1. pada setiap baris, unsur tak nol yang terletak paling kiri, adalah 1;

2. juga, untuk semua baris, unsur-unsur 1 terkiri itu tertata dengan aturan susunan berikut: unsur 1 terkiri baris yang di bawah selalu berada lebih ke kanan dari pada unsur satu terkiri baris yang di atasnya;

3. kalau matriks itu mempunyai baris yang semua unsurnya adalah 0, yang disebut baris nol (seperti baris ketiga pada matriks R), maka di bawah baris ini tak ada baris yang mempunyai unsur tak nol.

Matriks-matriks seperti P, @, dan R ini dinamai matriks eselon, adapun definisi tepatnya dituangkan sebagai berikut.


#### Definisi 2.2.1 (Matriks Eselon)

> ![[Pasted image 20250208161134.png]]


##### Sifat 1) 
mengakibatkan bahwa untuk matriks eselon, pada kolom yang memuat unsur 1 utama dari suatu baris (misalnya baris ke-k), tak ada unsur tak nol di bawah unsur 1 utama itu.

Kalau di bawah unsur 1 utama itu terdapat unsur tak nol, maka unsur 1 utama baris yang memuat unsur tak nol ini (yang tentunya terletak lebih ke bawah dari baris ke-k), tak bisa terletak lebih ke kanan dari unsur 1 utama baris ke-k itu. Ini bertentangan dengan sifat 2).

##### Sifat 2) 
dapat pula disimpulkan bahwa banyaknya baris tak nol matriks eselon tidak bisa lebih banyak dari jumlah kolom.


Untuk lebih jelasnya marilah kita telaah Contoh 2.2.1 dan Contoh 2.2.2 berikut ini.


#### Contoh 2.2.1 (Matriks Eselon)

Diketahui matriks

![[Pasted image 20250208161225.png]]

Untuk menunjukkan bahwa matriks P dan @ adalah matriks eselon, maka harus kita periksa dipenuhinya 3 sifat matriks tersebut.

##### Matriks P
Pada setiap baris, unsur tak nol paling kiri adalah 1, jadi sifat 1 dipenuhi. Tempat unsur 1 utama setiap baris:

![[Pasted image 20250208161249.png]]

Dengan demikian sifat 2) dipenuhi.

Matriks P tak mempunyai baris yang semua unsurnya adalah 0, jadi sifat 3) dipenuhi secara otomatis.


##### Matriks Q
Pada baris 1 sampai dengan 3, unsur tak nol paling kiri adalah 1, sifat 1) dipenuhi. Pada baris keempat, tak ada unsur tak nol, sifat 1) dipenuhi.

![[Pasted image 20250208161341.png]]


Dengan demikian posisi unsur 1 utama tiap baris memenuhi sifat 2). Baris keempat tak punya unsur tak nol. Jadi sifat 3) dipenuhi.


#### Contoh 2.2.2 (Bukan matriks Eselon)

Diketahui matriks:

![[Pasted image 20250208161420.png]]

Untuk menunjukkan bahwa suatu matriks bukan matriks eselon, cukup ditunjukkan bahwa salah satu dari 3 sifat tidak dipenuhi.

##### Matriks P
Unsur 1 utama baris ketiga tidak lebih ke kanan dari unsur 1 utama baris kedua, sehingga sifat 2) tidak dipenuhi. Jadi P bukan matriks eselon.

##### Matriks Q
Di bawah baris yang semua unsurnya 0 (baris kedua), terdapat baris yang memuat unsur tak nol (baris ketiga), sehingga sifat 3) tidak dipenuhi. Jadi @ bukan matriks eselon.

##### Matriks R
Unsur tak nol terkiri baris kedua tidak 1, sehingga sifat 1) tidak dipenuhi. Jadi R bukan matriks eselon.


#### Contoh 2.2.3
Periksa berlakunya sifat-sifat 1), 2), dan 3) pada matriks-matriks berikut, kemudian tentukan apakah matriks eselon atau bukan matriks eselon.

![[Pasted image 20250208161530.png]]


##### Matriks P

![[Pasted image 20250208161713.png]]

##### Matriks Q

![[Pasted image 20250208161727.png]]

##### Matriks R

![[Pasted image 20250208161740.png]]

##### Matriks S

![[Pasted image 20250208161757.png]]

##### Matriks T

![[Pasted image 20250208161810.png]]

##### Matriks U

![[Pasted image 20250208161824.png]]

Hasil pembahasan di atas dapat disimpulkan dalam tabel berikut ini.

![[Pasted image 20250208161841.png]]

Pada permulaan bagian ini sudah dijelaskan bahwa dengan eliminasi Gauss, matriks

![[Pasted image 20250208161859.png]]

dapat diubah menjadi matriks P

![[Pasted image 20250208161912.png]]

yang merupakan matriks eselon. Meneruskan eliminasi Gauss-Jordan satu langkah lagi, Kita peroleh matriks Q

![[Pasted image 20250208161941.png]]

Yang juga merupakan matriks eselon


Matriks-matriks P dan Q adalah matriks-matriks eselon yang diperoleh dengan serangkaian operasi baris elementer pada matriks A dan disebut bentuk eselon untuk matriks A . Terlihat bahwa bentuk eselon untuk suatu matriks tidak tunggal.

Untuk mendapatkan bentuk eselon yang tunggal kita harus memilih satu dari di antara bentuk-bentuk eselon. Untuk itu diperlukan pengertian matriks eselon tereduksi, yang definisinya seperti berikut ini


#### Definisi 2.2.2 (Matriks Eselon Tereduksi)

> ![[Pasted image 20250208162012.png]]


Untuk matriks eselon, pada kolom yang memuat unsur 1 utama suatu baris, tak ada unsur di bawah unsur 1 utama itu yang tak nol. Dengan demikian untuk matriks eselon tereduksi satu satunya unsur tak nol pada kolom itu adalah unsur 1 utama itu sendiri. Jelas dari definisi bahwa matriks eselon tereduksi adalah matriks eselon, dan matriks yang bukan matriks eselon, pastilah bukan matriks eselon tereduksi. Bahwa matriks eselon tereduksi tunggal, tidak dibuktikan di sini.



#### Contoh 2.2.4

Sekarang akan kita periksa yang manakah dari matriks-matriks P,Q,R,s,T , dan U pada Contoh 2.2.3 yang termasuk matriks eselon tereduksi. Karena matriks eselon tereduksi adalah matriks eselon, maka kita hanya memeriksa matriks eselon P,S,T , dan U saja ( Q dan R bukan matriks eselon).

##### Matriks P

![[Pasted image 20250208185623.png]]

jelaslah kolom ketiga memuat unsur 1 utama (pada baris kedua) dan pada kolom ketiga tersebut ada unsur 2 (tak nol) yang terletak di atas unsur 1 utama. Dengan demikian matriks P bukan matriks eselon tereduksi. Hal ini juga dapat ditunjukkan dengan melihat kolom keempat.

##### Matriks S

![[Pasted image 20250208185642.png]]

karena semua unsur adalah nol, maka tak ada kolom yang memuat unsur 1 utama.Jadi S matriks eselon tereduksi.

##### Matriks T

![[Pasted image 20250208185723.png]]

jelas setiap kolom memuat unsur 1 utama, dan pada tiap kolom itu tiap unsur di atas unsur 1 utama adalah nol. Maka T matriks eselon tereduksi.

##### Matriks U

![[Pasted image 20250208185757.png]]

Kolom yang memuat unsur 1 utama adalah kolom pertama dan kolom kedua. Pada tiap kolom itu tak ada unsur tak nol di atas unsur 1 utama. Jadi U matriks eselon tereduksi.


Hasil pembahasan di atas dan pembahasan pada Contoh 2.2.3 dapat pula di
simpulkan dalam tabel berikut ini.

![[Pasted image 20250208185850.png]]

Untuk lebih memantapkan pemahaman Anda, kita pandang Contoh 2.2.5 berikut.


#### Contoh 2.2.5

Periksa, apakah matriks berikut matriks eselon tereduksi atau bukan.

![[Pasted image 20250208185925.png]]

##### Penyelesaian

###### Matriks D

Matriks D: tak memenuhi sifat 1) karena unsur tak nol paling kiri untuk baris kedua, adalah 2 1. Matriks D bukan matriks eselon, jadi matriks D bukan matriks eselon tereduksi.

###### Matriks E
Matriks E: memenuhi sifat 1) sebab unsur tak nol terkiri untuk setiap baris adalah 1. Memenuhi sifat 2) karena letak unsur 1 terkiri, makin ke bawah, makin ke kanan.

Memenuhi sifat 3) karena baris nol terletak paling bawah. Memenuhi sifat 4), karena setiap kolom yang memuat unsur satu terkiri, tak memuat unsur tak nol selain unsur 1 terkiri itu sendiri. Matriks E matriks eselon tereduksi.

###### Matriks F
Matriks F: memenuhi sifat 1) karena unsur tak nol terkiri untuk tiap baris, adalah 1. Memenuhi sifat 2) karena unsur 1 terkiri tiap baris tersusun dari atas ke bawah, makin ke bawah, makin ke kanan. Memenuhi sifat 3) karena baris nol tidak ada. Tak memenuhi sifat 4) karena terdapat kolom yang memuat unsur 1 utama yang juga memuat unsur tak nol lainnya, yakni kolom ketiga (juga kolom kelima). Dengan demikian F adalah matriks eselon, akan tetapi matriks F bukan matriks eselon tereduksi.


Untuk lebih memantapkan pemahaman Anda, buatlah tabel seperti pada Contoh 2.2.4 untuk soal pada Contoh 2.2.5 ini.

Penampilan matriks eselon dapat disimpulkan sebagai berikut.

> - Baris yang mempunyai unsur tak nol tersusun semuanya pada bagian atas matriks, tanpa disisipi oleh baris nol. Unsur tak nol terkiri tiap baris itu 1, tersusun dari atas ke bawah, makin ke bawah makin ke kanan.
>   
> - Baris nol tersusun pada bagian bawah tanpa disisipi oleh baris yang mempunyai unsur tak nol. Lihat lagi matriks P,S,T, dan U pada Contoh 2.2.3 dan Contoh 2.2.4!





## [[05. Menentukan MAtriks Eselon dan Matriks Eselon Tereduksi Menggunakan Eliminasi Gauss dan Eliminasi Gauss-Jordan]]

> - Eliminasi Gauss adalah proses mengubah suatu matriks menjadi matriks eselon.
>   
> - Eliminasi Gauss-Jordan adalah proses mengubah suatu matriks menjadi matriks eselon tereduksi.

Pada akhir Kegiatan Belajar 1 sudah dibahas cara menyederhanakan matriks lengkap yang tak singular dari suatu sistem persamaan linear menjadi berbentuk matriks eselon dan matriks eselon tereduksi menggunakan rangkaian operasi baris elementer: Algoritma (langkah-langkah pelaksanaan beserta urutannya) untuk proses penyederhanaan itu pada kesempatan ini akan dituliskan secara terinci, perhatikan Contoh 2.2.6 berikut.


#### Contoh 2.2.6 (Eliminasi Gauss dan Eliminasi Gauss-Jordan)

Untuk mendapatkan gambaran yang jelas mengenai prosedur ini, setiap langkah akan disajikan bersama dengan pengerjaannya dalam rangka mengubah matriks,

![[Pasted image 20250208190257.png]]

menjadi matriks eselon dan eselon tereduksi.

##### Tahap IG 
Membereskan baris pertama

###### Langkah I/IG

![[Pasted image 20250208190344.png]]


###### Langkah 2/IG

![[Pasted image 20250208190427.png]]

###### Langkah 3/IG

![[Pasted image 20250208190450.png]]

###### Langkah 4/IG

![[Pasted image 20250208190506.png]]

###### Langkah 5/IG

![[Pasted image 20250208190522.png]]

Kita sekarang dapat melanjutkan dengan tahap II yakni membereskan baris ke-2. (kalau tahap II ini selesai kita dapat melanjutkan ke tahap III dan seterusnya sampai semua baris sudah dibereskan). Untuk selanjutnya dalam pikiran kita, kita menghapuskan baris pertama, sehingga sesungguhnya yang kita pandang adalah

matriks yang berada di dalam persegi panjang dengan garis terputus-putus seperti pada gambar di bawah ini. Sekarang kita akan mengerjakan langkah-langkah pada tahap II.

##### Tahap IIG
Membereskan baris ke dua

###### Langkah 1/IIG

![[Pasted image 20250208190619.png]]

###### Langkah 2/IIG

![[Pasted image 20250208190636.png]]

###### Langkah 3/IIG

![[Pasted image 20250208190655.png]]

###### Langkah 4/IIG

![[Pasted image 20250208190714.png]]

###### Langkah 5/IIG

![[Pasted image 20250208190729.png]]


##### Tahap IIIG
Membereskan baris ke tiga

###### Langkah 1/IIIG

![[Pasted image 20250208190933.png]]

###### Langkah 2/IIIG

![[Pasted image 20250208190959.png]]

###### Langkah 3/IIIG

![[Pasted image 20250208191014.png]]

###### Langkah 4/IIIG

![[Pasted image 20250208191029.png]]

###### Langkah 5/IIIG

![[Pasted image 20250208191047.png]]

##### Tahap IVG
Membereskan baris ke 4

###### Langkah 1/IVG

![[Pasted image 20250208191213.png]]

###### Langkah 2/IVG

![[Pasted image 20250208191228.png]]

###### Langkah 3/IVG

![[Pasted image 20250208191243.png]]

###### Langkah 4/IVG

![[Pasted image 20250208191259.png]]

###### Langkah 5/IVG

![[Pasted image 20250208191322.png]]

Apabila yang diinginkan matriks eselon tereduksi, maka proses kita lanjutkan dengan langkah-langkah berikut sehingga keseluruhan proses menjadi proses eliminasi Gauss-Jordan.

#### Tahapan IGJ
Membereskan baris paling bawah (baris ke-4)

###### Langkah 1/IGJ

![[Pasted image 20250208191434.png]]

###### Langkah 2/IGJ

![[Pasted image 20250208191456.png]]

###### Langkah 3/IGJ

![[Pasted image 20250208191513.png]]

##### Tahap IIGJ
Membereskan baris ke-3

###### Langkah 1/IIGJ

![[Pasted image 20250208191602.png]]

###### Langkah 2/IIGJ

![[Pasted image 20250208191620.png]]

###### Langkah 3/IIGJ

![[Pasted image 20250208191801.png]]

##### Tahap IIIGJ
Membereskan baris ke-2

###### Langkah 1/IIIGJ

![[Pasted image 20250208191840.png]]

###### Langkah 2/IIGJ

![[Pasted image 20250208191855.png]]

###### Langkah 3/IIIGJ

![[Pasted image 20250208191909.png]]


Untuk lebih memantapkan pemahaman Anda kita bahas satu contoh soal lagi.


#### Contoh 2.2.7

Lakukan eliminasi Gauss untuk mengubah matriks ini menjadi matriks eselon, kemudian lanjutkan dengan eliminasi Gauss-Jordan untuk memperoleh matriks eselon tereduksi.

![[Pasted image 20250208191936.png]]

###### Penyelesaian

###### Langkah 1/IG, 2/IG, 3/IG

![[Pasted image 20250208192006.png]]

###### Langkah 4/IG

![[Pasted image 20250208192027.png]]

###### Langkah 5/IG

![[Pasted image 20250208192043.png]]

###### Langkah 1/IIG, 2/IIG, 3/IIKG

![[Pasted image 20250208192110.png]]

###### Langkah 4/IIG

![[Pasted image 20250208192131.png]]

###### Langkah 5/IIG

![[Pasted image 20250208192145.png]]

###### Langkah 1/IIIG, 2/IIIG, 3/IIIG

![[Pasted image 20250208192204.png]]
![[Pasted image 20250208192238.png]]

###### Langkah 4/IIIG

![[Pasted image 20250208192251.png]]

###### Langkah 5/IIIG

![[Pasted image 20250208192311.png]]

Meneruskan dengan eliminasi Gauss-Jordan adalah menolkan unsur-unsur di atas unsur 1 utama pada kolom yang memuat unsur 1 utama itu.

###### Langkah 1/IGJ

![[Pasted image 20250208192335.png]]

###### Langkah 2/IGJ

![[Pasted image 20250208192351.png]]

###### Langkah 3/IGJ

![[Pasted image 20250208192409.png]]

###### Langkah 1/IIGJ

![[Pasted image 20250208192425.png]]

###### Langkah 2/IIGJ

![[Pasted image 20250208192447.png]]





## [[06. Matriks Elementer dan Keekivalenan Baris]]

Pada Kegiatan Belajar 1 telah dibicarakan pengertian operasi baris elementer dan pemanfaatannya dalam proses menyederhanakan suatu matriks menjadi matriks eselon atau matriks eselon tereduksi. Matriks eselon dan matriks eselon tereduksi itu ternyata ekivalen baris dengan matriks semula.

Pengerjaan operasi baris elementer pada suatu matriks berarti mengalikan matriks itu di kiri dengan suatu matriks bujursangkar tak singular yang disebut matriks elementer. Dengan demikian matriks ini merepresentasikan suatu keekivalenan baris.

Telah disinggung bahwa matriks eselon dan matriks eselon tereduksi adalah suatu matriks yang ekivalen baris dengan matriks tersebut. Rumusan definisi keekivalenan baris itu dituliskan sebagai berikut.

#### Definisi 2.2.3

> Matriks A disebut ekivalen baris dengan matriks B, apabila matriks B merupakan hasil serangkaian operasi baris elementer (OBE) yang dikerjakan pada matriks A.


Jelaslah bahwa matriks eselon dan matriks eselon tereduksi adalah hasil serangkaian operasi baris elementer yang dikerjakan pada matriks yang berkaitan.

Dengan demikian jelas bahwa suatu matriks ekivalen baris dengan matriks eselon dan matriks eselon tereduksinya.


Pada pembahasan sistem persamaan linear nanti di Modul 3, ternyata jawabnya dapat ditentukan langsung dari matriks eselon tereduksi untuk matriks lengkap sistem persamaan itu. Dari sifat keekivalenan baris ini, nanti dapat diturunkan bahwa dua sistem persamaan linear yang matriks lengkapnya ekivalen baris maka jawabnya sama (bila jawab ada). Jika jawab sistem persamaan yang satu tidak ada, jawab sistem persamaan yang lainnya juga tidak ada.

Untuk memudahkan kita membahas sifat sifat operasi baris elementer diperlukan pengertian matriks elementer yang dapat mewakili operasi baris itu. Definisi matriks elementer adalah sebagai berikut.

#### Definisi 2.2.4

> Matriks elementer adalah matriks bujur sangkar yang diperoleh jika operasi baris elementer (OBE) dikerjakan pada matriks satuan (yang berukuran sama dengan matriks bujursangkar tersebut).

Untuk lebih jelasnya, akan kita bahas beberapa berikut ini.

#### Contoh 2.2.8

Akan ditentukan 3 macam matriks elementer berukuran 3x3 yang diperoleh dari OBE matriks satuan $I_3$ sebagai berikut: 

1. baris ke-2 dikalikan dengan P;
2. baris ke-1 dipertukarkan dengan baris ke-2; dan 
3. baris ke-3 ditambahi dengan 9 kali baris ke-1.

##### Penyelesaian

![[Pasted image 20250208192745.png]]

Kita peroleh 3 matriks elementer $E_1$, $E_2$, dan $Е_3$ .

Apabila matriks elementer  $E_1$, $E_2$, dan $Е_3$ dari Contoh 2.2.8 masing-masing dikalikan dengan matriks sebarang berukuran 3xk, maka hasilnya sama dengan pengerjaan operasi baris elementer yang berkaitan pada matriks sebarang berukuran 3xk tersebut. Hal ini akan diperlihatkan pada Contoh 2.2.9 (pada contoh ini matriks sebarang A berukuran 3x5 dan pengerjaan operasi baris elementer dilakukan dari kanan ke kiri).


#### Contoh 2.2.9a

![[Pasted image 20250208192910.png]]

##### Penyelesaian

![[Pasted image 20250208192921.png]]
![[Pasted image 20250208192929.png]]

Pembahasan matriks elementer dan keekivalenan baris dapat diperluas untuk matriks berukuran mxm dan matriks satuan Im untuk m bilangan asli. Untuk operasi perkalian baris ke -k, pertukaran baris ke-k dengan baris ke-l , dan menambahi baris ke-k adalah sebagai berikut.

![[Pasted image 20250208192954.png]]

Pada Contoh 2.2.9a sudah kita lihat bahwa bila matriks elementer E adalah hasil pengerjaan suatu operasi baris elementer pada matriks satuan /z dan A suatu matriks 3x5, maka hasil pengerjaan operasi baris elementer itu pada A adalah EA . Sifat atau hasil pada Contoh 2.2.9a secara umum juga berlaku untuk A matriks berukuran mx m dan matriks satuan $I_m$

![[Pasted image 20250208193025.png]]

#### Contoh 2.2.9b

![[Pasted image 20250208193040.png]]

###### Penyelesaian

![[Pasted image 20250208193052.png]]


#### Contoh 2.2.10

Rangkaian operasi baris elementer berikut dikerjakan pada matriks A yang berukuran 4xn dan matriks satuan I secara berturutan:

![[Pasted image 20250208193121.png]]
![[Pasted image 20250208193143.png]]

##### Penyelesaian

![[Pasted image 20250208193155.png]]
![[Pasted image 20250208193206.png]]


#### Contoh 2.2.11

![[Pasted image 20250208193232.png]]

yang merupakan hasil pengerjaan dua langkah OBE pada matriks A :

4. baris ke-3 dikurangi baris ke-2 dilanjutkan dengan;
5. mempertukarkan baris ke-1 dengan baris ke-2.

![[Pasted image 20250208193252.png]]

##### Penyelesaian

![[Pasted image 20250208193303.png]]

#### Dalil 2.3.1

> ![[Pasted image 20250208193324.png]]







