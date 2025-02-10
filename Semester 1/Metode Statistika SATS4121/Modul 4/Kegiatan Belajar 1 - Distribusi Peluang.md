---
tags:
  - metode_statistika
  - materi_4_MS
---
# Kegiatan Belajar 1 - Distribusi Peluang

## [[01. Variabel Acak]]

Variabel acak adalah suatu fungsi berupa bilangan rill pada setiap unsur dalam ruang sampel. Sebuah variabel acak X pada ruang sampel S dinotasikan dengan $X : S → ℝ$ untuk sebuah bilangan rill X(s) dengan setiap titik sampel s ∈ S. Variabel acak dinyatakan dengan huruf kapital, biasanya hurufnya dalah X, Y, Z,.. sedangkan nilainya dinyatakan dengan huruf kecil x,y,z,...

Variabel acak pada ruang probabilitas (𝛀, S, P) yang dinotasikan dengan X dapat diartikan sebagai fungsi dengan domain 𝛀 dan kodomain himpunan bagian dari bilangan rill sedemikian sehingga untuk setiap bilangan rill r dipenuhi $A_r = {𝛚/X(𝛚)≤r} ∈ S$. Sehingga dengan variabel acak, ruang sampel telah ditransfiormasikan menjadi ruang sampel variabel acak yang merupakan himpunan bagian dari bilangan rill

> Variabel Acak : Suatu fungsi yang mengaitkan suatu bilangan real pada setiap unsur dalam ruang sampel

Variabel acak terbagi menjadi dua jenis yaitu:

#### 1. Variabel Acak Diskrit

Suatu variabel acak X dikatakan diskrit jika himpunan semua nilai yang mungkin dari X adalah himpunan bilangan yang dapat dihitung. 

>Lind et al menyatakan bahwa variabel acak diskrit adalah sebuah variabel acak yang hanya berisi nilai nilai yang terpisah dengan jelas

Biasanya nilai nilai variabel acak diskrit ini diperoleh dari hasil menghitung

#### 2. Variabel Acak Kontinu

Sedangkan suatu variabel acak dikatakan kontinu jika nilai nilai dari X merupakan bilangan bilangan pada suatu interval. 

> Menurut Lind et al, variabel acak kontinue dapat berisi satu dari sekian banyak nilai yang jumlahnya tak hingga dalam batasan batasan tertentu.

![[Screenshot 2024-10-03 at 19.15.32.png]]




## [[02. Distribusi Peluang variabel Acak Diskrit]]

Setiap variabel diskrit memiliki nilai yang menyatakan peluang dari variabel tersebut. Semua nilai peluang dari variabel acal X dinyatakan dengan sebuah rumus atau fungsi seperti f(x) ,g(x), r(x), dan seterusnya

Dalam hal ini misalnya f(x) - P(X=x), dengan kumpulan pasangan teruru (x, f(x)) sebagai fungsi peluang atau distribusi peluang dari variabel acak diskrit X dan massa peluang dimana untuk setiap kejadian X dipenuhi :

##### Syarat 1:  $f(x) \geq 0$ 
Ini berarti bahwa peluang setiap nilai yang diambil oleh variabel acak X harus selalu non-negatif. Secara logika, peluang tidak mungkin bernilai negatif. Fungsi peluang f(x) harus bernilai nol atau lebih besar dari nol untuk setiap x, artinya P(X=x) \geq 0.

##### Syarat 2:  $\sum_{x} f(x) = 1$ 
Ini adalah syarat bahwa jumlah total dari semua peluang harus sama dengan 1. Dalam konteks variabel acak diskrit, peluang semua kemungkinan nilai X yang mungkin diambil (dalam kumpulan nilai diskrit) harus berjumlah 1. Artinya, jika kita menambahkan semua P(X=x) untuk setiap nilai x, hasilnya harus selalu 1.

##### Syarat 3:  $P(X = x) = f(x)$ 
Ini menjelaskan bahwa peluang variabel acak diskrit X mengambil nilai x tertentu adalah sama dengan nilai dari fungsi peluang f(x) pada x. Dengan kata lain, f(x) adalah fungsi yang memberikan nilai peluang bahwa X akan memiliki nilai tertentu x.

Sementara itu, dalam banyak kasus diperlukan juga menghitung peluang  bahwa  untuk  nilai  variabel  acak  disrit  X  akan  lebih  kecil  atau  sama  dengan suatu  bilangan  riill x.  Bila $F(x) = P(X≤x)$ untuk  setiap  bilangan  riil x,  maka  F(x) disebut  sebagai  fungsi  distribusi  kumulatif.  

Adapun  distribusi  kumulatif  F(x) dari variabel acak diskrit X dengan distribusi peluang  f(x)  sebagai berikut:


$F(x) = P(X \leq x) = \sum_{x} f(x) \quad \text{untuk} \quad -\infty < x < \infty$


Dimana:

- $f(x)$  adalah fungsi massa peluang yang memberikan peluang untuk nilai spesifik  X = x .
- $\sum_{x} f(x)$  adalah penjumlahan dari semua peluang untuk nilai  X  yang kurang dari atau sama dengan  x .

Secara umum, fungsi distribusi kumulatif menggambarkan akumulasi peluang untuk setiap nilai  X , yang meningkat dari 0 hingga 1.


#### Contoh 4.2

Suatu pengiriman 8 komputer PC yang sama ke suatu toko mengandung 3 komputer yang cacat. Nila suatu sekolah membeli 2 komputer ini secara acak, tentukan distribusi peluang banyaknya komputer PC yang cacat

##### Penyelesaian:

Soal menyebutkan bahwa ada 8 komputer, 3 di antaranya cacat. Sekolah membeli 2 komputer secara acak. Kita diminta menentukan **distribusi peluang banyaknya komputer cacat** yang dibeli oleh sekolah.
###### 1.	Identifikasi variabel acak dan parameter masalah:

- Total komputer:  N = 8 
- Komputer cacat:  k = 3 
- Komputer yang dibeli:  n = 2 
- Variabel acak:  X  adalah jumlah komputer cacat yang dibeli.

###### 2.	Tentukan distribusi peluang:

Karena pengambilan dilakukan secara acak tanpa pengembalian, distribusi yang digunakan adalah hipergeometrik, dengan rumus sebagai berikut:

$P(X = x) = \frac{\binom{k}{x} \binom{N-k}{n-x}}{\binom{N}{n}}$

Dimana:
- $\binom{k}{x}$  adalah kombinasi memilih  x  komputer cacat dari  k  komputer cacat.
- $\binom{N-k}{n-x}$  adalah kombinasi memilih  n - x  komputer tidak cacat dari  N-k  komputer yang tidak cacat.
- $\binom{N}{n}$  adalah total kombinasi memilih  n  komputer dari  N  komputer.

###### 3.	Hitung peluang untuk setiap kemungkinan  x :

Karena hanya 2 komputer yang dibeli, nilai  X  yang mungkin adalah  x = 0, 1, 2 :

perlu diingat : 

$\binom{n}{r} = \frac{n!}{r!(n-r)!}$

**a) Untuk  X = 0  (tidak ada komputer cacat):**

$P(X = 0) = \frac{\binom{3}{0} \binom{5}{2}}{\binom{8}{2}} = \frac{1 \times 10}{28} = \frac{10}{28} = 0.3571$

b) Untuk  X = 1  (satu komputer cacat):

$P(X = 1) = \frac{\binom{3}{1} \binom{5}{1}}{\binom{8}{2}} = \frac{3 \times 5}{28} = \frac{15}{28} = 0.5357$

c) Untuk  X = 2  (dua komputer cacat):

$P(X = 2) = \frac{\binom{3}{2} \binom{5}{0}}{\binom{8}{2}} = \frac{3 \times 1}{28} = \frac{3}{28} = 0.1071$

###### 4.	Tulis distribusi peluangnya:

$P(X = 0) = 0.3571, \quad P(X = 1) = 0.5357, \quad P(X = 2) = 0.1071$

![[Screenshot 2024-10-03 at 19.32.25.png]]



## [[03. Distribusi Peluang Variabel Acak Kontinu]]

Suatu variabel acak kontinu selalu memiliki peluang nol pada setiap titik x sehingga nilai distribusi peluangnya tidak mungkin disajikan dalam bentuk tabel. Dengan demikian, nilai dalam variabel acak kontinu dapat dinyatakan sebagai nilai suatu selang bukan titik.

Meskipun peluang variabel acak kontinu tidak dapat dinyatakan dalam bentuk tabel, namum dapat disajikan dalam bentuk rumus sebagai berikut:

 $P(a < X \leq b) = P(a < X < b) + P(X = b)$

ini menunjukkan cara menghitung peluang bahwa variabel acak  X  berada di antara dua nilai  a  dan  b , termasuk batas atas  b . Karena  X  adalah variabel acak kontinu, peluang bahwa  X  tepat sama dengan nilai tertentu (misalnya  P(X = b) ) adalah nol. Maka:

$P(a < X \leq b) = P(a < X < b)$

Sehingga dihitung:

$P(a < X < b) = \int_a^b f(x) dx$

Peluang  X  berada di antara dua nilai  a  dan  b  dihitung dengan integrasi fungsi densitas peluang  f(x)  dari  a  hingga  b. 

Integrasi ini menggambarkan luas area di bawah kurva fungsi densitas peluang  f(x)  antara  x = a  dan  x = b . Luas ini mewakili peluang bahwa  X  berada dalam rentang tersebut.


Fungsi f(x) sebagai fungsi densitas peluang untuk variabel acak kontinu X yang didefinisikan pada bilangan rill ℝ jika:

#### 1.	Fungsi non-negatif:

$f(x) \geq 0 \quad \text{untuk semua} \quad x \in \mathbb{R}$  atau $∀ x \in \mathbb{R}$

Ini berarti bahwa fungsi densitas peluang tidak pernah negatif. Peluang selalu bernilai nol atau positif.

#### 2.	Total peluang sama dengan 1:

$\int_{-\infty}^{\infty} f(x) dx = 1$

Ini menyatakan bahwa total peluang untuk semua kemungkinan nilai  X  (dari  $-\infty$  hingga  $\infty$ ) harus sama dengan 1. Ini mencerminkan fakta bahwa peluang bahwa suatu peristiwa terjadi adalah pasti (peluang total dalam distribusi peluang selalu 1).

#### 3.	Peluang pada rentang tertentu:

$P(a < X < b) = \int_a^b f(x) dx$

Ini adalah cara menghitung peluang bahwa variabel acak kontinu  X  berada di antara nilai  a  dan  b . Peluang ini diukur sebagai luas di bawah kurva  f(x)  antara batas  a  dan  b .


![[Screenshot 2024-10-03 at 19.49.11.png]]

Adapun distribusi kumulatif F(x) dari variabel acak kontinu X dengan fungsi densitas peluang f(x) adalah :

![[Screenshot 2024-10-03 at 19.58.02.png]]

Fungsi distribusi peluang dari variabel acak kontinu X, yang disimbolkan sebagai $F(x)=P(X≤x)$, memberikan probabilitas bahwa nilai variabel acak X akan kurang dari atau sama dengan xxx. Secara matematis, fungsi distribusi kumulatif  F(x) dinyatakan sebagai integral dari fungsi kepadatan peluang f(x)

f(x) menggambarkan seberapa padat atau sering suatu nilai X terjadi dalam rentang tertentu. Nilai dari f(x) bisa diinterpretasikan sebagai probabilitas dari kejadian X pada suatu interval kecil. Hubungan antara PDF dan CDF adalah sebagai berikut:

- CDF F(x) adalah integral dari f(x) dari $−∞$ hingga x.
- PDF f(x) dapat diperoleh dari turunan CDF F(x):

$f(x)=dF(x)dxf(x) = \frac{dF(x)}{dx}f(x)=dxdF(x)$​

Dengan demikian, peluang bahwa X berada di antara dua nilai, misalnya a dan b, dihitung dengan selisih CDF pada b dan a:

$P(a<X<b)=F(b)−F(a)$ dan $f(x) = \frac{dF(x)}{dx}$


#### Contoh 4.3

Misalkan bahwa error suhu reaksi dalam Celcius percobaan laboratorium yang dikontrol merupakan variabel acak X yang mempunyai fungsi padat peluang:
![[Screenshot 2024-10-03 at 20.04.30.png]]


hitunglah peluang  $P(0 < X \leq 1)$

##### Penyelesaian:

Langkah-langkah penyelesaian:

###### 1. **Identifikasi fungsi kepadatan peluang (PDF):**

$f(x) = \frac{x^2}{3}, \text{ untuk } -1 < x < 2$

Untuk nilai di luar interval tersebut, $f(x)=0$


###### 2. **Hitung peluang yang diminta:** 

Peluang $P(0 < X \leq 1)$ dapat dihitung sebagai integral dari f(x) pada interval $[0,1]$:

$P(0 < X \leq 1) = \int_{0}^{1} \frac{x^2}{3} \, dx$

###### 3. **Hitung integral:** 

Integral dari $\frac{x^2}{3}$​ adalah:

![[Screenshot 2024-10-03 at 20.12.27.png]]
$\int \frac{x^2}{3} \, dx = \frac{x^3}{9}$


###### 4. **Evaluasi integral di batas-batas:** 

Evaluasi hasil integral pada batas 0 dan 1:

$\left[ \frac{x^3}{9} \right]_{0}^{1} = \frac{1^3}{9} - \frac{0^3}{9} = \frac{1}{9}$

![[Screenshot 2024-10-03 at 20.14.50.png]]

Jadi, nilai peluang $P(0 < X \leq 1)$ adalah $\frac{1}{9}$​.






