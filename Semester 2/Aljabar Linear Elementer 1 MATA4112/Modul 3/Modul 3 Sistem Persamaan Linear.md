---
tags:
  - aljabar_linear_elementer
  - materi_3_ALE
---
# [[Kegiatan Belajar 1 - Jawab Sistem Persamaan Linear]]

Pada contoh tersebut jawabnya ada dan tunggal. Apakah sifat ini berlaku (artinya, jawaban selalu ada dan tunggal) untuk setiap sistem persamaan linear? Kalau sekiranya jawabnya ya, pembicaraan kita mengenai sistem persamaan linear sudah selesai. Akan tetapi nyatanya jawabnya tidak, artinya jawab tidak selalu ada dan kalaupun ada tidak selalu tunggal.


## 01. Tipe Jawaban Sistem Persamaan

Sekarang kita bahas masalah SPL pada Contoh 3.1.1, Contoh 3.1.2, dan Contoh 3.1.3 yang memperlihatkan 3 tipe jawaban sistem persamaan linear, yaitu:

1. tidak ada jawab, 
2. ada banyak jawab (jawab tak tunggal), dan 
3. ada jawab tunggal.

#### Contoh 3.1.1 (tidak ada jawaban)

Pandang sistem persamaan linear:

![[Pasted image 20250209161422.png]]

Secara ilmu ukur, masing-masing persamaan menyatakan garis di $R^2$ sehingga kita peroleh dua garis seperti pada Gambar 3.1.1.

![[Pasted image 20250209161451.png]]

Jawab sistem persamaan itu menyatakan perpotongan antara kedua garis itu. Oleh karena kedua garis itu sejajar, perpotongannya hampa, jadi jawab sistem persamaan itu tidak ada. 

Hal ini juga dapat dijelaskan dengan eliminasi Gauss seperti berikut:

![[Pasted image 20250209161537.png]]

Baris ke-2 matriks lengkap bentuk terakhir menyatakan persamaan $0.x + 0.y = 2$ atau $0 = 2$, suatu kemustahilan yang menyimpulkan bahwa sistem persamaan linear tersebut tak punya jawab.



#### Contoh 3.1.2 (ada banyak jawab (jawab tak tunggal))

Pandang sistem persamaan linear:

![[Pasted image 20250209161642.png]]

Garis $x - y = -1$ dan $2x - 2y = -2$ adalah dua garis yang berimpit, sehingga perpotongannya merupakan semua titik pada garis itu. Lihat Gambar 3.1.2.

![[Pasted image 20250209161701.png]]

Pengerjaan eliminasi Gauss pada sistem persamaan itu adalah sebagai berikut.

![[Pasted image 20250209161711.png]]

Baris ke-2 pada matriks lengkap terakhir menyatakan persamaan $0.x + 0.y = 0$ yang tak memberikan pembatasan apapun pada x dan y , sehingga sistem persamaan itu ekivalen dengan satu persamaan saja, yakni $x - y = -1$. Jadi salah satu dari x dan y dapat dibuat bebas. Untuk keteraturan, yang bebas kita pilih y, maka kita tuliskan $y =t$, t real sebarang, dan $x = -1 + y = -1 +t$. Maka untuk suatu

![[Pasted image 20250209161819.png]]

Jawab sistem persamaan itu ialah:

![[Pasted image 20250209161840.png]]

Sehingga keseluruhan jawab sistem persamaan linear tersebut adalah,

![[Pasted image 20250209161852.png]]

yang merupakan garis di $R^2$ , sehingga lebih dari satu jawab atau banyak jawab atau **jawab tak tunggal**, Gambar 3.1.2.


#### Contoh 3.1.3 (ada jawab tunggal)

Pandang sistem persamaan linear:

![[Pasted image 20250209161959.png]]

Secara ilmu ukur, garis $x - y = 0$ dan $x + 2y = 3$ berpotongan di (1,1), Gambar 3.1.3. Jadi perpotongan kedua garis merupakan himpunan yang terdiri dari satu titik saja, jadi sistem persamaan tersebut mempunyai tepat satu jawab.

![[Pasted image 20250209162031.png]]

Pengerjaan eliminasi Gauss-Jordan pada sistem persamaan linear ini:

![[Pasted image 20250209162041.png]]

Pada matriks lengkap terakhir: persamaan ke-1 memberikan $1.x + 0.y = 1$ atau $x = 1$ dan persamaan ke-2 memberikan $0.x + 1.y = 1$ atau $y = 1$. Jadi jawab tunggal, yaitu :

$x = 1$ dan $y = 1$ .


Dari 3 contoh tersebut terlihat bahwa jawab sistem persamaan linear dapat dikategorikan 3 macam, yaitu:

![[Pasted image 20250209162133.png]]


Dalam hal banyak jawab atau lebih dari satu jawab atau jawab tak tunggal terdapat tak berhingga banyaknya jawab.

Apabila sistem persamaan linear yang terdiri dari 2 peubah x dan y , maka secara geometris kita masih dapat menggambar grafiknya sehingga diperoleh kesimpulan tak ada jawab (grafik sejajar), ada jawab tak tunggal (grafik berimpit), dan ada jawab tunggal (grafik berpotongan). 

Tetapi, apabila sistem persamaan linear tersebut terdiri lebih dari 2 peubah maka secara geometris kesimpulan tak ada jawab, ada jawab tak tunggal, dan ada jawab tunggal sukar diperoleh. 

Oleh sebab itu, kesimpulan tak ada jawab, ada jawab tak tunggal, dan ada jawab tunggal harus menggunakan eliminasi Gauss atau eliminasi Gauss-Jordan.

Secara umum, untuk setiap sistem persamaan linear dapat dipastikan bahwa hanya tepat satu dari 3 kemungkinan berikut yang berlaku, yaitu:

4. tak ada jawab;
5. ﻿﻿﻿banyak jawab (tak berhingga jawab atau jawab tak tunggal); atau
6. ﻿﻿﻿jawab tunggal (tepat satu jawab).


>Sistem persamaan linear yang mempunyai jawab (baik jawab tunggal maupun banyak jawab) juga disebut konsisten, 

>yang tidak mempunyai jawab disebut tidak konsisten.

Sebelum membahas contoh-contoh lain, kita bahas matriks koefisien dan matriks lengkap, yaitu matriks yang akan dioperasikan eliminasi Gauss dan eliminasi Gauss-Jordan.





## 02. Matriks Koefisien dan Matriks Lengkap

Sistem persamaan linear (SPL) yang terdiri dari m persamaan dengan n peubah (variabel) bebas, secara umum dapat dinyatakan sebagai:

![[Pasted image 20250209162322.png]]

dapat dituliskan dalam matriks A yang berukuran $m x n$ , matriks kolom & dan matriks B sebagai $AX = B$ dengan:

![[Pasted image 20250209162339.png]]

Matriks: A

![[Pasted image 20250209162418.png]]

disebut matriks koefisien; dan

![[Pasted image 20250209162430.png]]

disebut matriks lengkap sistem persamaan linear (3.1.1).

Misanya, apabila diketahui sistem persamaan linear:

![[Pasted image 20250209162454.png]]

maka matriks koefisien dan matriks lengkap masing-masing adalah:

![[Pasted image 20250209162505.png]]

Barisan bilangan
![[Pasted image 20250209162529.png]]

Adalah jawaban sistem persamaan linera (3.1.1) apabila
![[Pasted image 20250209162551.png]]

memenuhi persamaan linear yaitu
![[Pasted image 20250209162609.png]]

Jawab, 
![[Pasted image 20250209162621.png]]
ini dapat dituliskan sebagai matriks kolom $n x 1$

![[Pasted image 20250209162643.png]]

Dalam hal jawab tak tunggal, himpunan jawab sistem persamaan itu adalah himpunan semua R yang memenuhi AR = B.





## 03. Penyelesaian Sistem Persamaan Linear Dengan Eliminasi Gauss dan Eliminasi Gauss-Jordan

Sekarang kita bahas beberapa contoh sistem persamaan linear yang tak punya jawab, punya jawab tak tunggal, dan punya jawab tunggal dengan menggunakan eliminasi Gauss dan eliminasi Gauss-Jordan yang telah dibahas pada Modul 2 Kegiatan Belajar 1.

#### Contoh 3.1.4

Diketahui sistem persamaan linear

![[Pasted image 20250209162759.png]]

Selesaikan (tentukan x, y dan z ) dengan cara: 

1. eliminasi Gauss; dan 
2. eliminasi Gauss-Jordan.

##### Penyelesaian

###### Eliminasi Gauss

Matriks lengkap sistem persamaan linear adalah

![[Pasted image 20250209162841.png]]

![[Pasted image 20250209162850.png]]

Substitusi mundur adalah sebagai berikut:

![[Pasted image 20250209162928.png]]

Jadi, jawab sistem persamaan linear adalah x = 1, y = -1, dan z = 2.


###### Eliminasi Gauss-Jordan (melanjutkan operasi baris butir a.)

![[Pasted image 20250209162956.png]]


#### Contoh 3.1.5

Periksa, apakah sistem persamaan linear

![[Pasted image 20250209163013.png]]
punya jawab atau tak punya jawab?

##### Penyelesaian

Lakukan eliminasi Gauss pada matriks lengkap sistem persamaan tersebut.

![[Pasted image 20250209163038.png]]

Persamaan ke-3 matriks lengkap terakhir adalah: $0.x + O.y + 0.z = 1$ atau $0 = 1$, yang tak mungkin dipenuhi oleh x,y, dan z real. Jadi sistem persamaan linear tersebut tak konsisten atau tak punya jawab.


#### Contoh 3.1.6

Periksalah jawaban sistem persamaan linear

![[Pasted image 20250209163129.png]]

##### Penyelesaian

Kita kerjakan dengan eliminasi Gauss-Jordan seperti berikut ini.

![[Pasted image 20250209163147.png]]

menghasilkan jawab tunggal, yaitu:

![[Pasted image 20250209163158.png]]

Jadi, sistem persamaan linear ini konsisten dan jawabnya tunggal.


#### Contoh 3.1.7

Periksalah jawaban sistem persamaan linear

![[Pasted image 20250209163228.png]]

##### Penyelesaian

Mari kita kerjakan dengan eliminasi Gauss-Jordan untuk matriks lengkap sistem persamaan linear berikut ini.

![[Pasted image 20250209163243.png]]
![[Pasted image 20250209163257.png]]

Contoh 3.1.7 ini juga menghasilkan matriks eselon tereduksi sama dengan matriks eselon tereduksi untuk Contoh 3.1.6 [lihat matriks (3.1.2)] ditambahi baris 0 di bawahnya. Jadi sistem persamaan linear mampunyai jawab tunggal, yaitu:

![[Pasted image 20250209163309.png]]



#### Contoh 3.1.8

Selesaikan sistem persamaan linear (SPL):

![[Pasted image 20250209163337.png]]

##### Penyelesaian

Gunakan eliminasi Gauss-Jordan:

![[Pasted image 20250209163354.png]]

Kalau kita perhatikan matriks lengkap yang terakhir, maka dari baris:

![[Pasted image 20250209163404.png]]

![[Pasted image 20250209163433.png]]


Jadi, himpunan jawab SPL dalam bentuk matriks kolom adalah:

![[Pasted image 20250209163445.png]]

Ini berarti, sistem persamaan linear punya jawab tak tunggal (nilai t yang memberikan bermacam-macam jawab).

Untuk keteraturan, bilangan yang dicari yang dibuat sebarang, yaitu yang kolom koefisiennya pada matriks koefisien tak memuat unsur satu utama suatu baris. Pada contoh ini kolom itu adalah kolom ke-4 sehingga yang kita buat bebas adalah x4. Cara pemilihan seperti ini akan kita patuhi secara konsekuen.



#### Contoh 3.1.9

Periksalah jawab sistem persamaan linear berikut ini.

![[Pasted image 20250209163524.png]]

##### Penyelesaian

Gunakan eliminasi Gauss untuk matriks lengkapnya:

![[Pasted image 20250209163540.png]]

Baris paling bawah pada matriks terakhir menyatakan persamaan
![[Pasted image 20250209163559.png]]

yang tak mungkin dipenuhi. Jadi sistem persamaan tak konsisten atau tak punya jawab.


#### Contoh 3.1.10

Selesalkan sistem persamaan linear:

![[Pasted image 20250209170650.png]]

##### Penyelesaian

Matriks lengkapnya:

![[Pasted image 20250209170709.png]]

Selanjutnya, langkah-langkah eliminasi Gauss-Jordan untuk soal ini sama dengan yang dilakukan pada Contoh 3.1.8, perbedaan hanya pada matriks yang terlibat yaitu pada kolom terakhir. Untuk Contoh 3.1.10, semua unsur pada kolom terakhir adalah 0, sehingga kita peroleh matriks eselon tereduksi:

![[Pasted image 20250209170720.png]]

Sehingga,
![[Pasted image 20250209170733.png]]

dapat diambil sebarang misalkan t. Jadi himpunan jawab sistem persamaan in1 adalah:

![[Pasted image 20250209170749.png]]

Jika di tulis dalam matriks kolom

![[Pasted image 20250209170806.png]]

Jadi, ada tak berhingga banyaknya jawab, karena 

![[Pasted image 20250209170824.png]]

![[Pasted image 20250209170837.png]]

Sistem persamaan linear Contoh 3.1.10 adalah persamaan homogen karena unsur-unsur markis B adalah 0. Pada Kegiatan Belajar 2 akan kita bahas sistem persamaan linear homogen yang selalu punya jawab, sekurangnya ialah

![[Pasted image 20250209170859.png]] ![[Pasted image 20250209170905.png]]




---




# [[Kegiatan Belajar 2 - Analisis Jawab Sistem Persamaan Linear]]

ada Kegiatan Belaiar 1 modul ini sudah disimpulkan bahwa dengan eliminas Gauss atau eliminasi Gauss-Jordan, kita dapat:

![[Pasted image 20250209171122.png]]

Pada kesempatan ini akan dibahas keujudan dan ketunggalan. Keujudan terkait dengan ada jawab atau tidak adanya jawab sistem persamaan linear, sedangkan ketunggalan terkait dengan jawab tunggal atau jawab tidak tunggal.


## 04. Keujudan Jawab

Keujudan jawab di sini berkaitan dengan ada jawab atau tidak ada jawab suatu sistem persamaan linear dengan cara operasi baris elementer matriks lengkapnya.

Diketahui sistem persamaan linear dan matriks lengkapnya:

![[Pasted image 20250209171228.png]]

Kemudian kita akan melakukan serangkaian operasi baris elementer pada matriks lengkap untuk menentukan sistem persamaan linear mempunyai jawab atau tidak mempunyai jawab (ada jawab atau tidak ada jawab).

#### 3.4.1 Tidak Ada Jawab

Bila dilakukan operasi baris elementer pada matriks lengkap menghasilkan matriks eselon tereduksi memuat baris yang unsur 1 utamanya pada kolom terakhir (yang berarti memberikan 0 = 1), maka sistem persamaan tidak konsisten atau tidak ada jawab. Jelasnya, kita lihat Contoh 3.2.1 berikut ini.

##### Contoh 3.2.1

Pandang sistem persamaan linear yang matriks lengkapnya
![[Pasted image 20250209180757.png]]

Proses mencari matriks eselonnya adalah sebagai berikut.

![[Pasted image 20250209180812.png]]

Matriks terakhir pada baris ke-3 mempunyai unsur tak nol, yaitu 1, terkiri pada kolom terakhir. Ini berarti sistem persamaan tak konsisten atau tak ada jawab. Dalil yang mendasari bahwa sistem persamaan linear tak ada jawab dinyatakan ke dalam Dalil 3.2.1 berikut ini.

##### Dalil 3.2.1 (Tidak Ada Jawab)

> Jika serangkaian operasi baris elementer dikerjakan pada matriks lengkap suatu sistem persamaan linear menghasilkan matriks yang memuat baris yang mempunyai unsur tak nol terkiri pada kolom terakhir, maka sistem persamaan linear tak ada jawab.

Pada matriks eselon setiap baris tak nol mempunyai tepat satu unsur satu utama.

Jadi banyaknya baris tak nol sama dengan banyaknya unsur satu utama. Susunan unsur satu utama menyebabkan pada tiap kolom ada paling banyak satu unsur satu utama. Jadi banyaknya unsur satu utama tak dapat melebihi banyaknya kolom, karena pada satu kolom ada paling banyak satu unsur satu utama. Karena banyaknya baris tak nol sama dengan banyaknya unsur satu utama, maka banyaknya baris tak nol juga tak melebihi banyaknya kolom.



#### 3.4.2 Ada Jawab (Punya Jawab)

Jika matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak memuat baris yang unsur 1 terkirinya pada kolom terakhir, kita dapat melakukan substitusi mundur untuk memperoleh jawab. Agar lebih jelas, kita perhatikan Contoh 3.2.2 berikut ini.

##### Contoh 3.2.2

Andaikan matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak mempunyai baris yang unsur satu utamanya terletak pada kolom terakhir, jadi unsur 1 utama tiap baris tidak pada kolom terakhir misalnya seperti berikut,

![[Pasted image 20250209180927.png]]

![[Pasted image 20250209180942.png]]

Kemudian dibuat dalam bentuk matriks kolom:

![[Pasted image 20250209180952.png]]

Dengan demikian, jika matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak memuat baris yang unsur 1 terkirinya pada kolom terakhir, sistem persamaan linear tersebut mempunyai jawab. Secara umum dinyatakan ke dalam Dalil 3.2.2 berikut ini.

##### Dalil 3.2.2 (Ada/Punya Jawab)

> Jika matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak memuat baris yang unsur satu utamanya pada kolom terakhir (unsur satu utama tiap baris tidak terletak pada kolom terakhir), maka sistem persamaan linear itu punya jawab.

Dalil 3.2.2 ini merupakan syarat perlu dan cukup untuk ada jawab, begitu pula Dalil 3.2.1 sebelumnya untuk tak ada jawab.

Kadang-kadang kita tidak harus menggunakan dalil di atas secara penuh untuk menetapkan bahwa suatu sistem persamaan linear punya jawab, dalam arti kita tidak harus betul-betul menentukan matriks eselon untuk matriks lengkap sistem persamaan itu. Hal itu kita perlihatkan pada Contoh 3.2.3 dan Contoh 3.2.4 berikut ini.

##### Contoh 3.2.3

Tunjukkan bahwa sistem persamaan linear yang matriks lengkapnya seperti berikut punya jawab tanpa lebih dulu mencari jawab itu.

![[Pasted image 20250209181124.png]]

###### Penyelesaian:
Me-nol-kan unsur pada kolom pertama di bawah baris pertama.

![[Pasted image 20250209181145.png]]

Matriks eselon untuk matriks lengkap ini jelas tak mempunyai baris yang unsur satu utamanya pada kolom terakhir, jadi sistem kita punya jawab.


##### Contoh 3.2.4 (Sistem Persamaan Linear Homogen)

Pandang sistem persamaan linear yang kolom terakhir matriks lengkapnya adalah kolom nol (kolom yang semua unsurnya adalah 0). Sistem persamaan linear yang begini disebut Sistem Persamaan Linear Homogen. Matriks koefisien dan matriks lengkapnya masing-masing adalah sebagai berikut,

![[Pasted image 20250209181224.png]]

Matriks eselon untuk matriks lengkap ini diperoleh dengan pengerjaan rangkaian operasi baris elementer pada matriks lengkap itu. Pengerjaan tiap operasi baris elementer pada matriks tak akan mengubah kolom nol matriks itu. Dengan demikian kolom terakhir matriks eselon untuk matriks lengkap di atas akan merupakan kolom nol, dengan demikian matriks eselon itu tak memuat baris yang unsur satu utamanya pada kolom terakhir. Jadi sistem persamaan linear homogen punya jawab.

Sesungguhnya untuk sistem persamaan linear homogen langsung terlihat bahwa

![[Pasted image 20250209181245.png]]

adalah jawab, karena jelaslah

![[Pasted image 20250209181257.png]]

jawab ini disebut jawab trivial (remeh, sepele).








## 05. Ketunggalan Jawaban

Kalau suatu sistem persamaan linear punya (ada) jawab, pertanyaan selanjutnya: apakah jawab tersebut tunggal atau tak tunggal?

Pada pembahasan ketunggalan jawab berikut ini, kita akan memeriksa sistem persamaan yang punya jawab selanjutnya untuk menentukan: apakah jawab tersebut tunggal atau tak tunggal (banyak jawab). 

Mari kita melihat Contoh 3.2.5 dan Contoh 3.2.6, yang masing-masing dengan operasi baris elementer matriks lengkap sudah menghasilkan matriks eselon.

#### Contoh 3.2.5

Pandang sistem persamaan linear pada Contoh 3.2.3. Matriks eselon untuk matriks lengkapnya telah ditemukan, yaitu:

![[Pasted image 20250209181422.png]]

Banyaknya bilangan yang dicari adalah banyaknya kolom matriks koefisien sistem persamaan itu, yaitu matriks yang dilingkupi oleh persegi panjang terputus. Pada contoh ini ada 3 bilangan yang dicari, yaitu x, y, dan z.

Baris-baris tak nol pada matriks eselon itu menyatakan persamaan-persamaan yang saling bebas dalam sistem persamaan itu. Banyaknya baris tak nol pada matriks eselon ada 2 buah, sedangkan banyaknya bilangan yang dicari ada 3 , maka jawab tak tunggal karena kita dapat membuat salah satu y atau z bebas .


#### Contoh 3.2.6

Pandang sistem persamaan linear yang matriks eselon untuk matriks lengkapnya sudah diberikan berikut ini.

![[Pasted image 20250209181452.png]]

Jelas matriks ini tak mempunyai baris yang unsur satu utamanya pada kolom terakhir, jadi sistem persamaannya punya jawab. Banyaknya baris tak nol sama dengan banyaknya kolom matriks koefisien, setiap kolom pada matriks koefisien memuat unsur satu utama suatu baris. Tak ada bilangan yang dicari yang dibuat bebas, jawab sistem persamaan ini tunggal.

Pada umumnya banyaknya baris tak nol pada matriks eselon paling banyak sama banyaknya dengan banyaknya kolom matriks itu. Jadi banyaknya baris tak nol pada matriks eselon untuk matriks lengkap suatu sistem persamaan linear, paling banyak sama dengan banyaknya kolom matriks lengkap itu. Tetapi bila matriks eselon untuk matriks lengkap itu tak memuat baris yang unsur satu utamanya pada kolom terakhir, maka banyaknya baris tak nol itu paling banyak sama dengan banyaknya kolom dikurangi satu, jadi paling banyak sama banyaknya dengan banyaknya kolom matriks koefisien sistem persamaan itu.

Dari penjelasan pada Contoh 3.2.6, dalil berikut (yang bukti lengkapnya tidak dibahas di sini) dapat kita tuliskan

#### Dalil 3.2.3 (Ketunggalan)

> Jika pada matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak terdapat baris yang unsur satu utamanya pada kolom terakhir dan banyaknya baris tak nol sama dengan banyaknya kolom matriks koefisien, maka sistem persamaan linear itu punya tepat satu jawab.

Kembali pada Contoh 3.2.2. Matriks eselon untuk matriks lengkap sistem persamaan linear di situ adalah

![[Pasted image 20250209181541.png]]

banyaknya baris tak nol adalah 3, sedangkan banyaknya kolom matriks koefisien adalah 5. Kolom ke-2 dan kolom ke-5 tak memuat unsur 1 utama suatu baris. Hal ini mengakibatkan tak tunggalnya jawab.

Dapat dibuktikan bahwa hal itu berlaku umum, akan kita rumuskan berupa dalil berikut.

#### Dalil 3.2.4

> Jika matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak memuat baris yang unsur satu utamanya terletak pada kolom terakhir, dan banyak baris tak nolnya kurang dari banyaknya kolom, maka sistem persamaan linear itu mempunyai lebih dari satu jawab.

Selanjutnya, dalil-dalil yang sudah kita bahas akan kita manfaatkan untuk memeriksa jawab contoh-contoh soal berikut ini.

##### Contoh 3.2.7

Periksa, apakah sistem persamaan linear yang matriks lengkapnya diberikan berikut ini, mempunyai jawab atau tidak mempunyai jawab, kalau mempunyai jawab apakah jawab tersebut tunggal atau tidak tunggal.

![[Pasted image 20250209181642.png]]

a. dan c. sistem persamaan linear homogen, b.,d., dan e. tidak homogen

###### Penyelesaian

Di sini akan diberikan matriks eselon dari masing-masing matriks lengkap. Sedangkan proses memperoleh masing-masing matriks eselon diserahkan kepada Anda sebagai latihan!.

a. Matriks Eselon

![[Pasted image 20250209181719.png]]

b. Matriks eselon:

![[Pasted image 20250209181739.png]]

c. Matriks Eselon

![[Pasted image 20250209181801.png]]

Matriks eselon untuk matriks lengkapnya tak mempunyai unsur satu utama pada kolom terakhir, jadi punya jawab. Banyaknya baris tak nol adalah 2, kurang dari banyaknya kolom matriks koefisien, yaitu 4. Jawab tak tunggal, jadi ada jawab yang bukan jawab trivial, yang disebut jawab tak trivial.

Pada sistem persamaan linear homogen masalah keujudan jawab jadi tidak penting, karena sistem persamaan linear homogen itu selalu punya jawab. Yang relevan adalah masalah ketunggalan.

Untuk sistem persamaan linear homogen jawab tunggal berarti satu satunya jawab adalah jawab trivial, ketaktunggalan jawab berarti adanya jawab tak trivial.

Anda akan menemukan penerapan masalah ini nanti pada masalah nilai eigen yang akan dibahas dalam Aljabar Linear Elementer II.


d. Matriks Eselon

![[Pasted image 20250209181838.png]]

tak terdapat baris yang unsur satu utamanya pada kolom terakhir, ada jawab.

Karena banyaknya baris tak nol (yakni 2) kurang dari banyaknya kolom matriks koefisien (yaitu 4) jawab sistem itu tak tunggal. Sebelum memperoleh matriks eselon kita sudah dapat menyimpulkan banyaknya baris(3) jelas kurang dari banyaknya kolom matriks koefisien, jadi baris tak nol pun begitu.


e. Dalam rangka mencari matriks eselonnya kita sampai ke pada matriks

![[Pasted image 20250209181904.png]]

yang memuat baris yang menyatakan persamaan yang tak mungkin dapat dipenuhi, sistem persamaannya tak punya jawab.

Pada Contoh 3.2.4 dibahas bahwa sistem persamaan linear homogen selalu punya jawab. Kalau jawab itu tunggal, yang ada hanya jawab trivial. Bila jawab tak tunggal, ada jawab yang disebut jawab tak trivial. Persoalan pada sistem persamaan homogen adalah masalah ada atau tak adanya jawab tak trivial. Pemeriksaan cukup dilakukan pada matriks koefisien saja seperti berikut.


##### Contoh 3.2.8

Diketahui 2 sistem persamaan linear homogen dengan matriks eselon untuk masing-masing matriks koefisiennya:


![[Pasted image 20250209181941.png]]

Tentukan, apakah sistem persamaan linear homogen yang berkaitan mempunyai jawab tak trivial atau jawab trivial.

###### Penyelesaian

a. Matriks koefisien mempunyai jawab tunggal karena banyaknya baris tak nol pada matriks eselon matriks koefisien sama dengan banyaknya kolom. Kemudian
dengan substitusi mundur menghasilkan jawab tunggal x = 0, y = 0, dan z = 0, yang berarti sistem persamaan linear homogen yang berkaitan mempunyai jawab trivial.

b. Sedangkan pada persamaan b. banyaknya baris tak nol pada matriks eselon kurang dari banyaknya kolom sehingga jawabnya tak tunggal, jadi sistem persamaan linear homogen yang berkaitan mempunyai jawab yang tak trivial.




## 06. Analisis Sistem Persamaan Linear yang Matriks Lengkapnya Mengandung Unsur Parameter

Keujudan dan Ketunggalan Jawab yang telah dibahas di depan akan kita manfaatkan untuk menganalisis sistem persamaan linear yang beberapa unsur matriks lengkapnya masih berupa parameter.

Akan kita bahas syarat-syarat untuk parameter yang menyebabkan jawab sistem tak ada, ada tepat satu (tunggal), atau ada lebih dari satu (tak tunggal). Pembahasan dengan cara memberikan contoh-contoh soal.

#### Contoh 3.2.9

Tentukan hubungan antara p, q, dan r agar sistem persamaan linear (SPL):

![[Pasted image 20250209182128.png]]

![[Pasted image 20250209182134.png]]

##### Penyelesaian

Pengerjaan eliminasi Gauss pada matriks lengkap

![[Pasted image 20250209182200.png]]

Perhatikan baris terakhir, kemudian kita lihat 2 kasus berikut ini.

![[Pasted image 20250209182210.png]]
![[Pasted image 20250209182222.png]]

##### Kesimpulan

![[Pasted image 20250209182234.png]]


#### Contoh 3.2.10

Tentukan nilai-nilai p supaya sistem persamaan linear (SPL):

![[Pasted image 20250209182258.png]]

##### Penyelesaian

Karena SPL hanya mempunyai 2 persamaan, maka banyaknya baris tak nol pada matriks eselon untuk matriks koefisiennya paling banyak 2, jadi pasti kurang dari banyaknya kolom (yaitu 3). Dengan demikian, kita sudah dapat menyimpulkan bahwa kasus (ii) ada tepat satu jawab tak akan terjadi untuk nilai p berapapun (tak pernah ada tepat satu jawab).

Pengerjaan eliminasi Gauss untuk matriks lengkap

![[Pasted image 20250209182322.png]]

![[Pasted image 20250209182331.png]]

##### Kesimpulan

![[Pasted image 20250209182347.png]]


#### Contoh 3.2.11

Kerjakan seperti pada Contoh 3.2.10 untuk sistem persamaan linear (SPL) berikut tanpa mencari jawab

![[Pasted image 20250209182413.png]]

##### Penyelesaian

Karena banyaknya baris kurang dari banyaknya kolom matriks koefisien, maka banyaknya baris tak nol matriks eselon untuk matriks koefisien kurang dari banyaknya kolom. Jadi untuk nilai p berapapun kasus sistem persamaan linear tersebut punya tepat satu jawab tidak pernah terjadi.

Yang mungkin terjadi adalah tak punya jawab atau punya lebih dari satu jawab, yang akan kita periksa dengan mencoba mengerjakan langkah pertama eliminasi Gauss, sebagai berikut.

![[Pasted image 20250209182435.png]]

Perhatikan matriks terakhir:

![[Pasted image 20250209182447.png]]

##### Kesimpulan

![[Pasted image 20250209182457.png]]


#### Contoh 3.2.12

Tentukan nilai-nilai p supaya sistem persamaan linear homogen yang berkaitan dengan matriks koefisien berikut,

![[Pasted image 20250209182516.png]]

##### Penyelesaian

Pada sistem persamaan linear homogen: jawab selalu ada, sekurangnya jawab trivial. Bila jawabnya tunggal, jawab satu satunya itu adalah jawab trivial. Jawab tak tunggal ekivalen dengan adanya jawab tak trivial.

Langkah permulaan eliminasi Gauss mencari matriks eselon untuk matriks koefisien,

![[Pasted image 20250209182537.png]]
Perhatikan baris terakhir matriks (3.2.2):

![[Pasted image 20250209182552.png]]

##### Kesimpulan

![[Pasted image 20250209182603.png]]


#### Contoh 3.2.13

Tentukan nilai-nilai p supaya sistem persamaan linear (SPL) yang matriks lengkapnya:

![[Pasted image 20250209182619.png]]

##### Penyelesaian

Dengan pengerjaan eliminasi Gauss matriks lengkap menghasilkan,

![[Pasted image 20250209182641.png]]

![[Pasted image 20250209182650.png]]

##### Kesimpulan

![[Pasted image 20250209182702.png]]



