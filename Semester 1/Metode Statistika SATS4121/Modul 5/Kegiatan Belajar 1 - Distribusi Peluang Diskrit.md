---
tags:
  - metode_statistika
  - materi_5_MS
---
# Kegiatan Belajar 1 - Distribusi Peluang Diskrit

> **Distribusi peluang diskrit** adalah sebuah tabel atau rumus yang mencantumkan semua kemungkinan nilai suatu variabel acak diskrit berikut peluangnya.

Pada variabel acak diskrit, setiap nilainya dikaitkan dengan peluang tertentu. Misalnya dalam pelemparan uang logam sebanyak 3 kali, variabel acak X, yaitu banyaknya sisi gambar, mengaitkan peluang sebesar 3/8 pada nilai variabel acak 2, karena 3 di antara 8 titik sampel mempunyai kemungkinan yang sama untuk menghasilkan 2 sisi gambar dan 1 sisi angka.

Dengan mengasumsikan peluang yang sama untuk setiap kejadian sederhana, maka peluang M bernilai 0 adalah 1/3. Semua kemungkinan nilai m berikut peluangnya dicantumkan dalam tabel berikut.

![[Screenshot 2024-10-19 at 12.22.03.png]]

Perhatikan bahwa nilai-nilai m mencakup semua kemungkinan sehingga total peluangnya sama dengan 1.

Seringkali, lebih memudahkan bila semua peluang suatu variabel acak dinyatakan dalam sebuah rumus. Rumus demikian ini tentulah merupakan fungsi nilai-nilai x, oleh karena itu kita akan melambangkan dengan $f(x),g(x),r(x),$ dan sebagainya. Jadi $f(x)=P(X=x)$; misalnya

$f(3) = P(X = 3)$. Himpunan semua pasangan berurutan $(x, f(x))$ disebut

fungsi peluang atau sebaran peluang bagi variabel acak X.


## [[01. Distribusi Bernoulli]]

Distribusi Bernoulli dibentuk berdasarkan satu kali percobaan yang memberikan hasil dua kemungkinan, yaitu sukses atau gagal, dengan peluang sukses p dan peluang gagal $$q=1-p.$$
> **Variabel acak Bernoulli** didefinisikan sebagai kejadian sukses dalam percobaan tersebut.

Misalnya, percobaan pelemparan sekeping mata uang logam. Jika sukses didefinisikan sebagai munculnya sisi gambar, maka variabel acak X adalah munculnya sisi gambar, dengan peluang sukses adalah $p=\frac{1}{2}$ dan peluan gagal adalah $q = \frac{1}{2}$ .

Secara umum, distribusi peluang Bernoulli diformulasikan sebagai berikut.

#### Distribusi Bernoulli

Fungsi distribusi peluang variabel acak X Bernoulli dengan peluang
sukses p dan peluang gagal $q = 1- p$ adalah:

$$b(x,p)=p^xq^{1-x}, untuk | x=0.1$$

#### Expektasi dan Varians Distribusi Bernoulli

Nilai espektasi variabel acak X Bernoulli adalah: $$E(X)= p$$ dan varians $$Var(X) = pq$$

Karena variabel acak Bernoulli hanya terdiri dari satu kali percobaan, maka hal yang menarik adalah menggunakan kejadian Bernoulli untuk beberapa kali percobaan. Nah, percobaan yang melibatkan kejadian Bernoulli yang dilakukan sebanyak $n$ kali dinamakan kejadian Binomial.




## [[02. Distribusi Binominal]]

Percobaan Bernoulli yang dilakukan berulang-ulang dinamakan percobaan Binomial.

>Variabel acak Binomial $X$ didefinisikan sebagai jumlah kejadian sukses dalam $n$ kali percobaan.

distribusi peluang Binomial juga merupakan pengembangan dari distribusi Bernoulli.

Secara umum, percobaan Binomial adalah percobaan yang memiliki ciri-ciri berikut:

1. ﻿﻿﻿Percobaannya terdiri atas $n$ ulangan.
2. ﻿﻿﻿Dalam setiap ulangan, hasilnya dapat digolongkan sukses atau gagal.
3. ﻿﻿﻿Peluang sukses, yang dilambangkan dengan $p$, untuk setiap ulangan
4. adalah sama, tidak berubah-ubah.
5. ﻿﻿﻿Ulangan-ulangan itu bersifat bebas satu sama lain.

##### Contohnya

Misalnya, percobaan pelemparan sekeping mata uang dilakukan sebanyak 3 kali. Variabel acak X adalah banyaknya muncul sisi gambar.

Hasil percobaan yang mungkin adalah sebagai berikut.
![[Screenshot 2024-10-19 at 12.31.20.png]]

Berdasarkan tabel di atas maka:

1. ﻿﻿﻿Peluang $X = 3$ atau semua hasil percobaan muncul gambar adalah $p^3$.
2. ﻿﻿﻿Peluang $X = 2$ atau dari tiga percobaan hanya dua kali muncul gambar adalah $3p^2 (1-p)$.
3. ﻿﻿﻿Peluang $X =1$ atau hanya satu kali muncul gambar dari tiga kali pelemparan adalah $3p(1- p)^2$ .
4. Peluang X =0 atau semua hasil percobaan muncul sisi angka adalah $(1-p)^3$.

Dari ilustrasi tersebut dapat dirumuskan model matematika dari distribusi peluang Binomial sebagai berikut.

#### [[02. Distribusi Binominal]]

> Suatu kejadian Bernoulli dapat menghasilkan sukses dengan peluang p dan gagal dengan peluang q =1- p, maka distribusi peluang peubah acak binomial X yaitu banyaknya sukses dalam n usaha bebas, adalah:
> ![[Screenshot 2024-10-19 at 12.36.45.png]]


##### Contoh 5.1

Di sebuah kota, keperluan uang untuk membeli ganja atau sejenisnya ternyata melatarbelakangi 75% peristiwa pencurian yang terjadi. Berapa peluang bahwa tepat 2 di antara 4 kasus pencurian yang berikutnya dilatarbelakangi oleh keperluan uang untuk membeli ganja? Asumsinya kejadian pencurian bersifat saling bebas.

###### Penyelesaian

1. Variabel acak X adalah banyaknya kejadian pencurian yang dilatarbelakangi oleh keperluan uang untuk membeli ganja. X merupakan variabel acak Binomial. Kejadian sukses (1) dari percobaan Binomial ini adalah jika pencurian yang terjadi dilatarbelakangi oleh keperluan uang untuk membeli ganja, dan kejadian gagal (O) adalah jika pencurian yang terjadi tidak dilatarbelakangi oleh keperluan uang untuk membeli ganja, mungkin ada motif yang lainnya.
   
2. Keperluan uang untuk membeli ganja atau sejenisnya ternyata melatarbelakangi 75% peristiwa pencurian yang terjadi, berarti :
   $$p=75﹪ =\frac{3}{4}$$
3. Tepat 2 di antara 4 kasus pencurian yang berikutnya dilatarbelakangi oleh keperluan uang untuk membeli ganja. Hal ini berarti:
   
   $$n=4$$ $$x=2$$
   Berdasarkan informasi tersebut, menggunakan fungsi distribusi peluang Binomial diperoleh:
   
   ![[Screenshot 2024-10-19 at 12.40.24.png]]

##### Contoh 5.2

Peluang seseorang sembuh dari suatu penyakit darah adalah 0,4. Bila 15 orang diketahui menderita penyakit ini, berapa peluang bahwa: 

a) sekurang-kurangnya 10 orang dapat sembuh; 
b) ada 3 sampai 8 orang yang sembuh; dan 
c) tepat 5 orang yang sembuh?

###### Penyelesaiannya

Misalkan X adalah banyaknya orang yang sembuh, maka:

![[Screenshot 2024-10-19 at 16.46.27.png]]

#### Ekspektasi dan Varians dari Variabel Acak Binomial

Nilai ekspektasi dan varians bagi distribusi binomial $b(x;n,p)$ adalah:
$$µ = np$$
dan 
$$𝛔^2=npq$$

##### Contoh 5.3

Tentukan rata-rata (ekspektasi) dan varians dari soal pada contoh 5.2.

###### Penyelesaian

![[Screenshot 2024-10-19 at 16.49.49.png]]

setiap variabel acak pasti memiliki nilai rata-rata atau ekspektasi dan varians. Lalu, apa kegunaan mengetahui rataan dan varians dari peubah acak? Salah satunya adalah untuk menentukan batas-batas interval nilai yang memiliki peluang tertentu. Seperti pada dalil Chebyshev

#### Teorema Chebyshev

Peluang setiap variabel acak X mendapat nilai dalam k simpangan baku dari nilai rataan adalah paling sedikit $$(1-\frac{1}{k^2})$$
yaitu :
![[Screenshot 2024-10-19 at 16.51.47.png]]

##### Contoh 5.4

Dari Contoh 5.2 dan Contoh 5.3, tentukanlah batas-batas selang $$\mu±2\sigma$$dan berikan interpretasinya.

###### Penyelesaian

![[Screenshot 2024-10-19 at 16.53.28.png]]


## [[03. Distribusi Seragam (Uniform) Diskrit]]

Di antara semua distribusi peluang diskrit, yang paling sederhana adalah distribusi seragam (uniform) diskrit. Dalam distribusi ini, setiap nilai variabel acak mempunyai peluang terjadi yang sama.

#### Distribusi Seragam (Uniform) Diskrit

> Bila variabel acak X mempunyai nilai-nilai $x_1, x_2, ..., x_k$ dengan peluang yang sama, maka distribusi seragam diskritnya adalah $f (x;k) = \frac{1}{k}$ untuk $x = x_1,x_2,x_3... x_n$

##### Contoh 5.5

Bila sebuah dadu dilemparkan, setiap ruang sampel $S = (1, 2, 3, 4, 5, 6)$
mempunyai peluang yang sama untuk muncul, yaitu $\frac{1}{6}$. Oleh karena itu, kita mempunyai distribusi seragam dengan $f (x; 6) =\frac{1}{6}$ untuk $x= 1,2,3,4,5,6$

###### Penyelesaian:

Sajian grafik histogram bagi distribusi seragam ini selalu berupa beberapa empat persegi panjang dengan tinggi yang sama.

![[Screenshot 2024-10-19 at 16.57.55.png]]

##### Contoh 5.6

Tentukan distribusi seragam bagi himpunan bagian nama bulan berukuran 3 yang diambil secara acak.

###### Penyelesaian

![[Screenshot 2024-10-19 at 17.03.05.png]]






