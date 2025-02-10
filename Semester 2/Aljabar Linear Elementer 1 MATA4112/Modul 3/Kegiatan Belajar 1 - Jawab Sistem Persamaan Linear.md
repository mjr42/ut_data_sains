---
tags:
  - aljabar_linear_elementer
  - materi_3_ALE
---
# Kegiatan Belajar 1 - Jawab Sistem Persamaan Linear

Pada contoh tersebut jawabnya ada dan tunggal. Apakah sifat ini berlaku (artinya, jawaban selalu ada dan tunggal) untuk setiap sistem persamaan linear? Kalau sekiranya jawabnya ya, pembicaraan kita mengenai sistem persamaan linear sudah selesai. Akan tetapi nyatanya jawabnya tidak, artinya jawab tidak selalu ada dan kalaupun ada tidak selalu tunggal.


## [[01. Tipe Jawaban Sistem Persamaan]]

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





## [[02. Matriks Koefisien dan Matriks Lengkap]]

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





## [[03. Penyelesaian Sistem Persamaan Linear Dengan Eliminasi Gauss dan Eliminasi Gauss-Jordan]]

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







