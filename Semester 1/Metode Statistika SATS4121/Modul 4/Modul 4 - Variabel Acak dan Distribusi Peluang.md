---
tags:
  - metode_statistika
  - materi_4_MS
---
# [[Kegiatan Belajar 1 - Distribusi Peluang]]

## 01. Variabel Acak

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




## 02. Distribusi Peluang variabel Acak Diskrit

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



## Distribusi Peluang Variabel Acak Kontinu

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



---

# [[Kegiatan Belajar 2 - Ekspektasi dan Varians Distribusi Peluang]]

## Nilai Ekspektasi (Nilai Harapan)

Expektasi atau yang bisa disebut juga sebagai Mean. Misal X adalah variabel acak dengan distribusi peluang f(x), maka ekspektasi atau mean dari X didefinisikan sebagai berikut

#### Ekspektasi untuk variabel acak diskrit

![[Screenshot 2024-10-04 at 07.58.47.png]]

JIka x adalah variabel acak diskrit, nilai ekspektasi yang diperoleh dengan menjumlahkan semua nilai x, dikalikan dengan peluang atau fungsi massa peluang f(x) pada setiap nilai x,

- f(x): Ini adalah **fungsi massa peluang** (Probability Mass Function, PMF) untuk variabel acak diskrit X. PMF f(x) menyatakan peluang bahwa X mengambil nilai tertentu x, sehingga $f(x) = P(X = x)$.

- $\sum_{x}$ : Simbol ini menunjukkan penjumlahan untuk semua kemungkinan nilai x yang mungkin diambil oleh variabel acak X.

- $x \cdot f(x)$: Ini adalah kontribusi masing-masing nilai x terhadap ekspektasi, yaitu nilai x dikalikan dengan peluangnya f(x).

Secara intuitif, $E(X)$ adalah rata-rata nilai yang diharapkan dari variabel acak X, yang dihitung dengan mempertimbangkan seberapa sering setiap nilai x terjadi.

##### Contoh

![[Screenshot 2024-10-04 at 08.02.10.png]]

#### Ekspektasi untuk variabel acak kontinu

![[Screenshot 2024-10-04 at 08.02.32.png]]

Jika X adalah variabel acak **kontinu**, nilai ekspektasi diperoleh dengan mengintegralkan x dikalikan dengan **fungsi kepadatan peluang** (Probability Density Function, PDF) f(x), yang menggambarkan distribusi peluang dari variabel acak X.

- $f(x)$: Ini adalah **fungsi kepadatan peluang** untuk variabel acak kontinu X. Fungsi ini tidak menyatakan peluang langsung dari X, tetapi menggambarkan seberapa padat peluang pada suatu interval kecil di sekitar x. Jumlah integral f(x) di seluruh ruang harus sama dengan 1, yang menandakan bahwa total peluang dari semua kemungkinan nilai x adalah 100%.

- $\int_{-\infty}^{\infty}$​: Simbol integral ini menandakan bahwa kita menjumlahkan kontribusi dari semua nilai x yang mungkin, mulai dari nilai terendah (dalam teori, dari $-\infty$) hingga nilai tertinggi (hingga $+\infty$).

- $x \cdot f(x)$: Seperti dalam kasus diskrit, ini adalah kontribusi setiap nilai x terhadap ekspektasi, dikalikan dengan kepadatannya f(x).


Secara intuitif, ekspektasi dalam konteks kontinu adalah rata-rata tertimbang dari semua nilai x, di mana bobotnya diberikan oleh f(x).

##### Contoh:
![[Screenshot 2024-10-04 at 08.06.54.png]]

![[Screenshot 2024-10-04 at 08.09.26.png]]
![[Screenshot 2024-10-04 at 08.09.43.png]]
![[Screenshot 2024-10-04 at 08.09.54.png]]
![[Screenshot 2024-10-04 at 08.10.54.png]]

![[Screenshot 2024-10-04 at 08.11.44.png]]

#### Contoh 4.4

Carilah nilai harapan banyaknya kimiawan dalam panitia yang terdiri dari 3 orang yang dipilih secara acak dari 4 kimiawan dan 3 biolog.

##### Penyelesaian
Langkah pertama adalah memahami bahwa soal ini meminta nilai **harapan** atau **ekspektasi** dari banyaknya kimiawan dalam panitia yang beranggotakan 3 orang, dipilih dari total 4 kimiawan dan 3 biolog.

###### 1. Tentukan variabel acak

Misalkan X adalah variabel acak yang menyatakan banyaknya kimiawan dalam panitia 3 orang. Karena pemilihan ini acak, maka X bisa bernilai 0, 1, 2, atau 3 (artinya, bisa ada 0, 1, 2, atau 3 kimiawan dalam panitia tersebut).

![[Screenshot 2024-10-04 at 08.22.23.png]]

###### 2. Distribusi hipergeometrik 

Pemilihan ini dapat dimodelkan dengan distribusi **hipergeometrik**. Distribusi ini digunakan ketika kita mengambil sampel tanpa pengembalian dari populasi yang terbagi menjadi dua kelompok (dalam kasus ini, kimiawan dan biolog). Rumus distribusi hipergeometrik untuk peluang P(X = k) memilih k kimiawan dalam panitia 3 orang adalah:

![[Screenshot 2024-10-04 at 08.24.02.png]]

![[Screenshot 2024-10-04 at 08.24.56.png]]

![[Screenshot 2024-10-04 at 08.25.53.png]]
> perlu di ingat:
> $\binom{n}{r} = \frac{n!}{r!(n-r)!}$


![[Screenshot 2024-10-04 at 08.28.38.png]]


#### Contoh 4.5

Misalkan X variabel acak yang menyatakan umur dalam jam sejenis bola lampu. Fungsi padat peluangnya (PDF) diberikan oleh:

![[Screenshot 2024-10-04 at 08.30.06.png]]

Hitunglah harapan umur jenis bola lampu tersebut.

##### Penyelesaian:

![[Screenshot 2024-10-04 at 08.30.37.png]]


![[Screenshot 2024-10-04 at 08.31.02.png]]

![[Screenshot 2024-10-04 at 08.32.01.png]]

![[Screenshot 2024-10-04 at 08.33.33.png]]

![[Screenshot 2024-10-04 at 08.33.55.png]]
![[Screenshot 2024-10-04 at 08.34.05.png]]

![[Screenshot 2024-10-04 at 08.34.18.png]]
![[Screenshot 2024-10-04 at 08.34.37.png]]

![[Screenshot 2024-10-04 at 08.35.08.png]]

![[Screenshot 2024-10-04 at 08.35.40.png]]

![[Screenshot 2024-10-04 at 08.35.58.png]]

![[Screenshot 2024-10-04 at 08.36.12.png]]

![[Screenshot 2024-10-04 at 08.36.46.png]]


## Nilai Harapan Fungsi Transformasi Acak

Misalnya sebuah variabel acak baru g(x) nimainya bergantung pada X atau merupakan fungsi dari X, yaitu setiap nilai g(X) dapat ditentukan bila diketahui nilai X. Misal g(X) sama dengan $X^2$ atau 3X-1. Jadi bila X bernilai 2 maka g(X) bernilai g(2). Khususnya bila X variabel acak diskrit dengan distribusi peluang dan $g(x)=X^2$

$$P[g(x)=0] = P(X=0) f(0)$$
$$p[g(x)=1] = p(x=-1) + p(x=1) = f(-1)+f(1)$$
$$p[g(x)=4] = P(X=2) = f(2)$$


![[Screenshot 2024-10-04 at 09.09.42.png]]

Menurut definisi nilai harapan variabel acak, diperoleh
![[Screenshot 2024-10-04 at 09.13.25.png]]


#### Nilai Harapan Fungsi Transformasi Acak Diskrit

Untuk peubah acak diskrit, nilai harapan μg(x)\mu_{g(x)}μg(x)​ dihitung sebagai:

$$\mu_{g(x)} = \mathbb{E}[g(X)] = \sum g(x) f(X)$$

 **Penjelasan**:

- $X$ adalah peubah acak yang mengambil nilai-nilai diskrit.
- $g(X)$ adalah suatu fungsi dari peubah acak X.
- $f(X)$ adalah fungsi probabilitas atau peluang (probability mass function) yang memberikan peluang dari setiap nilai X.
- Nilai harapan dari $g(X)$ dihitung dengan menjumlahkan hasil perkalian antara nilai $g(X)$ dan peluang $f(X)$ untuk setiap kemungkinan nilai X.


##### Contoh

Misalkan X adalah peubah acak yang merepresentasikan jumlah lemparan koin dengan distribusi sebagai berikut:

![[Screenshot 2024-10-04 at 09.16.30.png]]

![[Screenshot 2024-10-04 at 09.17.09.png]]




#### Nilai Harapan Fungsi Transformasi Acak Kontinu

Untuk peubah acak kontinu, nilai harapan $\mu_{g(x)}$​ dihitung sebagai:

$$\mu_{g(x)} = \mathbb{E}[g(X)] = \int_{-\infty}^{\infty} g(X) f(X) dx$$

- **Penjelasan**:
    - $X$ adalah peubah acak kontinu yang mengambil nilai dalam suatu interval.
      
    - $f(X)$ adalah fungsi kepadatan peluang (probability density function) yang memberikan kepadatan probabilitas di sekitar nilai X.
      
    - Nilai harapan $\mu_{g(x)}$​ dihitung dengan mengintegrasikan produk dari g(X) dan f(X) di sepanjang semua kemungkinan nilai X, yang dinotasikan dengan $\int_{-\infty}^{\infty}$​.

Intisari:
	- Nilai harapan $\mathbb{E}[g(X)]$ merupakan rata-rata tertimbang dari g(X), di mana bobotnya adalah peluang f(X). Perbedaannya terletak pada apakah X bersifat diskrit (menggunakan penjumlahan) atau kontinu (menggunakan integrasi).

##### Contoh

Misalkan X adalah peubah acak kontinu yang terdistribusi secara seragam antara 0 dan 2, dengan fungsi kepadatan peluang $f(X) = \frac{1}{2}$​ untuk $0 \leq X \leq 2$ dan f(X) = 0 di luar interval tersebut.

Fungsi $g(X) = X^2$, maka kita ingin menghitung nilai harapan $\mathbb{E}[g(X)]$.

![[Screenshot 2024-10-04 at 09.25.45.png]]

#### Kesimpulan:

- **Kasus diskrit**: Menggunakan penjumlahan dengan probabilitas diskrit.
- **Kasus kontinu**: Menggunakan integrasi dengan fungsi kepadatan peluang.



#### Contoh 4.6

Banyaknya mobil X, yang masuk ke suatu pencucian mobil setiap hari antara jam 12.00-14.00 mempunyai distribusi peluang

![[Screenshot 2024-10-04 at 10.03.25.png]]

Hitunglah angka harapan penerimaan para karyawan jika $E[g(x)]=E(2x-1)$

##### Penyelesaian:

![[Screenshot 2024-10-04 at 10.05.51.png]]

#### Contoh 4.7

JIka X adalah suatu variabel aca dengan fungsi densitas probabilitas sebagai berikut
![[Screenshot 2024-10-04 at 10.07.03.png]]

Tentukan nilai harapan g(X)=4x+3


![[Screenshot 2024-10-04 at 10.07.28.png]]


## Nilai Harapan dari Variabel Acak Diskrit

Misalkan X dan Y adalah variabel ransom diskrit maka:

#### 1. Untuk sembarang konstanta $a$, berlaku:

$$E(a) = a \quad \text{dan} \quad E(aX) = aE(X)$$

Penjelasan:

- $E(a) = a$: Ekspektasi dari suatu konstanta aaa adalah aaa itu sendiri, karena nilai konstanta tidak berubah sehingga harapannya sama dengan nilai konstanta tersebut.
  
- $E(aX) = aE(X)$: Ekspektasi dari hasil perkalian konstanta aaa dengan variabel random X adalah sama dengan konstanta tersebut dikalikan dengan ekspektasi dari variabel random X. Hal ini menunjukkan bahwa konstanta dapat "dikeluarkan" dari ekspektasi.


##### Contoh

- $E(a)=a$:
    
    - Misalkan $a=5$. Karena aaa adalah konstanta, maka ekspektasinya sama dengan nilainya sendiri: 
    $$E(5)=5$$ 

- $E(aX)=aE(X)$:
    
    - Misalkan X adalah variabel acak yang menunjukkan hasil lemparan sebuah dadu, sehingga $X \in \{1, 2, 3, 4, 5, 6\}$ dan ekspektasi X dihitung sebagai: 
      $$E(X) = \frac{1 + 2 + 3 + 4 + 5 + 6}{6} = 3.5$$
      Misalkan a=2. Maka ekspektasi dari aX adalah: 
      $$E(2X) = 2E(X) = 2 \times 3.5 = 7$$
       Ini menunjukkan bahwa kita bisa mengalikan konstanta dengan ekspektasi variabel acak.



#### 2. Jika terdapat dua konstanta X dan Y berlaku:
 $$E(X+Y)=E(X)+E(Y)$$
Penjelasan

- Ini adalah sifat **linearitas ekspektasi**. Ekspektasi dari jumlah dua variabel random X dan Y adalah sama dengan jumlah ekspektasi dari masing-masing variabel tersebut. Ini berlaku terlepas dari apakah X dan Y bersifat independen atau tidak.

##### Contoh

Misalkan X adalah hasil lemparan dadu dan Y adalah hasil lemparan koin di mana Y=1 untuk sisi kepala dan Y=0 untuk sisi ekor. Ekspektasi dari X adalah:

$$E(X) = 3.5 \quad \text{(seperti dihitung sebelumnya)}$$

Ekspektasi dari Y (dengan peluang masing-masing 1/2) adalah: 
$$E(Y) = \frac{1 \times 0.5 + 0 \times 0.5}{1} = 0.5$$

Maka ekspektasi dari $X+Y$ adalah: 
$$E(X + Y) = E(X) + E(Y) = 3.5 + 0.5 = 4$$

 Ini menunjukkan bahwa ekspektasi dari jumlah dua variabel acak adalah jumlah ekspektasi masing-masing.


#### 3. Jika terdapat tiga konstanta a, b, c berlaku:

$$E(aX+bY+c)=aE(X)+bE(Y)+c$$

Penjelasan:

- Ini adalah bentuk umum dari **linearitas ekspektasi**. Jika ada dua variabel random X dan Y serta konstanta a, b, c, maka ekspektasi dari kombinasi linear $aX + bY + c$ dapat dihitung sebagai:
    - $aE(X)$ untuk komponen $aX$,
    - $bE(Y)$ untuk komponen $bY$,
    - dan c, karena c adalah konstanta, ekspektasinya adalah c itu sendiri.

##### Contoh

Misalkan kita kembali menggunakan X sebagai hasil lemparan dadu dan Y sebagai hasil lemparan koin seperti pada contoh sebelumnya, dengan: 
$$E(X) = 3.5 \quad \text{dan} \quad E(Y) = 0.5$$

 Misalkan a=2, b=3, dan c=5. Maka: 
 $$E(2X+3Y+5)=2E(X)+3E(Y)+5$$
  
 Substitusi nilai ekspektasi X dan Y: 
 $$E(2X+3Y+5)=2(3.5)+3(0.5)+5=7+1.5+5=13.5$$
  
  Jadi ekspektasi dari $2X+3Y+5$ adalah 13.5.


#### Contoh 4.8

Sebuah produsen kosemtik baru baru ini membuat dua macam krim pelembab yang ditunjukan untuk wanita dewasa dan remaja. Karena banyak produk produk kecantikan sejenis yang beredar di pasaran maka penjualan untuk produk krim pelembab ini tidak bisa diprediksi secara pasti, Berdasarkan hasil penjualan yang telah dilakukan, dugaan penjualan krim pelembab untuk wanita dewasa adalah sebagai berikut

![[Screenshot 2024-10-04 at 10.39.01.png]]

Sedangkan untuk dugaan krim pelembab untuk remaja adalah sebagai berikut

![[Screenshot 2024-10-04 at 10.39.37.png]]

1. Berapa ekspektasi atau nilai harapan jumlah penjualan krim untuk remaja dan jumlah penjualan krim untuk wanita dewasa?
2. Produsen kosmetik itu menetapkan keuntungan $2.000 untuk setiap botol krim dewasa dan $3.500 untuk krim remaja. Berapa ekspektasi keuntungan untuk krim dewasa dan krim remaja?
3. Berapa ekspektasi total keuntungan untuk kedua krim?

##### Penyelesaian

##### Pertanyaan 1:
Berapa ekspektasi atau nilai harapan jumlah penjualan krim untuk remaja dan jumlah penjualan krim untuk wanita dewasa?

###### Langkah 1
![[Screenshot 2024-10-04 at 10.41.29.png]]

###### Langkah 2 
**Hitung nilai harapan untuk krim wanita dewasa**

![[Screenshot 2024-10-04 at 10.42.11.png]]



###### Langkah 3 
Hitung nilai harapan untuk krim remaja

![[Screenshot 2024-10-04 at 10.42.39.png]]




##### Pertanyaan 2:

**Produsen kosmetik itu menetapkan keuntungan $2.000 untuk setiap botol krim dewasa dan $3.500 untuk krim remaja. Berapa ekspektasi keuntungan untuk krim dewasa dan krim remaja?**

Untuk menghitung ekspektasi keuntungan, kita bisa mengalikan nilai ekspektasi jumlah penjualan dengan keuntungan per botol.

###### Langkah 1
![[Screenshot 2024-10-04 at 10.47.41.png]]


###### Langkah 2
![[Screenshot 2024-10-04 at 10.47.58.png]]


##### Pertanyaan 3:

**Berapa ekspektasi total keuntungan untuk kedua krim?**

Untuk menghitung ekspektasi total keuntungan dari kedua krim, kita cukup menjumlahkan ekspektasi keuntungan untuk krim dewasa dan krim remaja.

$$\text{Ekspektasi Total Keuntungan} = 10.000.000 + 1.557.500 = 11.557.500 \text{ dolar}$$


##### Kesimpulan:

1. Ekspektasi penjualan untuk krim dewasa adalah 5.000 botol, dan untuk krim remaja adalah 445 botol.
   
2. Ekspektasi keuntungan untuk krim dewasa adalah $10.000.000 dan untuk krim remaja adalah $1.557.500.
   
3. Ekspektasi total keuntungan untuk kedua krim adalah $11.557.500.


## Variansi

Nilai harapan dari variabel acak X merupakan suatu nilai dalam statistik yang menggambarkan letak distribusi probabilitas berpusat. Meskipun demikian, nilai harapah tersebut tidak cukup untuk memberikan gambaran tentang benruk suatu distribusi. Menurut Walpole, untuk mengetahui suatu distribusi, perlu diketahui variabilitas distribusi tersebut.

Salah satu ukuran variabilitas dalam statistik adalah Variansi. Variansi dari variabel acak X atau variansi dari distribusi probabilitas X dinyataan dengan 

$Var(X)$ atau dinotasikan dengan $𝛔^2_x$ atau $𝛔^2$

#### 1. Variansi jika $X$ Diskrit

Persamaan variansi untuk variabel acak diskrit adalah:

$$\sigma^2 = \mathbb{E} \left[ (X - \mu)^2 \right] = \sum_x (x - \mu)^2 \cdot f(x)$$

Penjelasan:

- $\mathbb{E} \left[ (X - \mu)^2 \right]$menyatakan ekspektasi atau rata-rata dari kuadrat deviasi X dari nilai harapannya μ.
  
- $\sum_x (x - \mu)^2 \cdot f(x)$ adalah penjumlahan semua nilai x yang mungkin dari variabel acak X, di mana masing-masing dikalikan dengan probabilitasnya f(x) dan deviasi kuadratnya $(x - \mu)^2$

##### Contoh

Misalkan kita memiliki sebuah variabel acak X yang menyatakan jumlah mata dadu dari sebuah lemparan dadu biasa (dadu berjumlah 6 sisi). Distribusi probabilitas f(x) untuk X adalah seragam, artinya:

![[Screenshot 2024-10-04 at 11.32.06.png]]

Nilai harapan $\mu$ untuk X adalah:

![[Screenshot 2024-10-04 at 11.32.24.png]]

Untuk menghitung variansi $\sigma^2$ gunakan rumus

![[Screenshot 2024-10-04 at 11.33.26.png]]

 Langlah Langkah:

###### Langkah 1

![[Screenshot 2024-10-04 at 11.33.48.png]]

###### Langkah 2

![[Screenshot 2024-10-04 at 11.34.37.png]]

###### Langkah 3

![[Screenshot 2024-10-04 at 11.34.59.png]]

###### Simpulan
Jadi, variansi X adalah sekitar 2.92


#### 2. Variansi jika $X$ Kontinu

Persamaan variansi untuk variabel acak kontinu adalah:

$$\sigma^2 = \mathbb{E} \left[ (X - \mu)^2 \right] = \int_{-\infty}^{\infty} (x - \mu)^2 \cdot f(x) \, dx$$

Penjelasan:

- Persamaan ini adalah analogi dari kasus diskrit, tetapi menggunakan integral karena X kontinu.
  
- f(x) adalah fungsi kepadatan probabilitas dari X, dan $\int_{-\infty}^{\infty} (x - \mu)^2 \cdot f(x) \, dx$ menghitung rata-rata tertimbang dari kuadrat deviasi $(x - \mu)^2$ di seluruh domain x.

##### Contoh

Misalkan X adalah variabel acak kontinu yang mengikuti distribusi normal standar, $X \sim N(0, 1)$, dengan fungsi kepadatan probabilitas:
![[Screenshot 2024-10-04 at 11.36.08.png]]

Nilai harapan $\mu = 0$ karena ini adalah distribusi normal standar. Variansi $\sigma^2$ dapat dihitung dengan

![[Screenshot 2024-10-04 at 11.36.46.png]]

Penyelesaian integral ini merupakan standar dalam distribusi normal, dan hasilnya diketahui sebagai:

![[Screenshot 2024-10-04 at 11.37.01.png]]

Ini menunjukkan bahwa variansi dari distribusi normal standar $N(0,1)$ adalah 1.


#### Contoh 4.9

Misalkan peubah acak X menyatakan banyaknya mobil yang digunakan untuk keperluan dinas kantor pada setiap hari kerja. Distribusi peluang untuk kaktor A adalah
![[Screenshot 2024-10-04 at 11.40.21.png]]

Dan untuk kantor B adalah
![[Screenshot 2024-10-04 at 11.40.30.png]]

Tunjukan bahwa variansi distribusi peluang kantor B lebih besar dari pada variansi kantor A

##### Penyelesaian

Untuk membuktikan bahwa variansi distribusi peluang kantor B lebih besar daripada variansi kantor A, kita perlu menghitung variansi untuk kedua distribusi.

###### Langkah 1: Hitung Nilai Harapan (Mean) untuk Kantor A

![[Screenshot 2024-10-04 at 11.41.20.png]]


###### Langkah 2: Hitung Variansi untuk Kantor A

![[Screenshot 2024-10-04 at 11.42.37.png]]

###### Langkah 3: Hitung Nilai Harapan (Mean) untuk Kantor B

![[Screenshot 2024-10-04 at 11.43.03.png]]


###### Langkah 4: Hitung Variansi untuk Kantor B

![[Screenshot 2024-10-04 at 11.43.34.png]]

###### Langkah 5: Bandingkan Variansi

Dari hasil perhitungan:

- Variansi kantor A = 0.6
- Variansi kantor B = 1.6

###### **Kesimpulan:** 

Variansi distribusi peluang kantor B (1.6) lebih besar daripada variansi kantor A (0.6), seperti yang diminta.



## Variansi Variabel Acak X

Variansi variabel random X adalah 
$$𝛔^2=E(x^2)-\mu^2$$

#### A. Variansi dari Suatu Variabel Acak Deskrit

##### 1. Definisi Variansi

Variansi $\sigma^2$ didefinisikan sebagai:

$$\sigma^2 = \sum_x (x - \mu)^2 \cdot f(x)$$

Di sini:

- x adalah nilai-nilai variabel acak.
  
- $\mu$ adalah rata-rata (mean) dari distribusi probabilitas variabel acak X, didefinisikan sebagai $\mu = \sum_x x \cdot f(x)$
  
- f(x) adalah fungsi probabilitas dari X, yang memberikan probabilitas bahwa variabel acak X mengambil nilai x.

##### 2. Penguraian Persamaan

Langkah pertama dalam penyederhanaan adalah menguraikan kuadrat dalam ekspresi $(x - \mu)^2$:

$$(x - \mu)^2 = x^2 - 2\mu x + \mu^2$$

Menggantikannya ke dalam persamaan variansi, diperoleh:

$$\sigma^2 = \sum_x (x^2 - 2\mu x + \mu^2) \cdot f(x)$$
##### 3. Memisahkan Penjumlahan

Selanjutnya, ekspresi di atas dipisah menjadi tiga penjumlahan:

$$\sigma^2 = \sum_x x^2 \cdot f(x) - 2\mu \sum_x x \cdot f(x) + \mu^2 \sum_x f(x)$$

Setiap bagian ini dijelaskan sebagai berikut:

- $\sum_x x^2 \cdot f(x)$ adalah nilai ekspektasi dari $X^2$, atau $E(X^2)$.
  
- $2\mu \sum_x x \cdot f(x)$ dapat disederhanakan menjadi $2\mu^2$, karena $\mu = \sum_x x \cdot f(x)$.
  
- $\sum_x f(x) = 1$, karena jumlah semua probabilitas dalam distribusi adalah 1.


##### 4. Hasil Akhir Variansi

Setelah menyederhanakan, kita mendapatkan:

$$\sigma^2 = E(X^2) - 2\mu^2 + \mu^2$$

Yang pada akhirnya memberikan:

$$\sigma^2 = E(X^2) - \mu^2$$


##### 5. Contoh

Misalkan kita memiliki sebuah variabel acak diskrit $X$ yang merepresentasikan hasil pelemparan dadu biasa (1 hingga 6). Probabilitas setiap nilai $x$ dari variabel acak ini adalah:
![[Screenshot 2024-10-04 at 13.08.14.png]]

###### a. Menghitung Ekspektasi $\mu$:

![[Screenshot 2024-10-04 at 13.12.56.png]]

###### b. Menghitung Ekspektasi $X^2$

![[Screenshot 2024-10-04 at 13.13.56.png]]

###### c. Menghitung Variansi $\sigma^2$:

![[Screenshot 2024-10-04 at 13.14.35.png]]


#### B. Variansi dari Suatu Variabel Acak Kontinu

Variabel acak kontinu adalah variabel acak yang dapat mengambil nilai dari suatu interval yang tak terhingga atau sangat banyak dalam suatu rentang, misalnya $X \in [a, b]$. Alih-alih memiliki fungsi probabilitas diskrit f(x), variabel acak kontinu memiliki **fungsi densitas probabilitas (pdf)** f(x), yang mendefinisikan probabilitas relatif bahwa X mengambil nilai dalam suatu rentang kecil.

##### 1. Definisi Variansi untuk Variabel Acak Kontinu

Variansi untuk variabel acak kontinu didefinisikan sebagai:

$$\sigma^2 = E(X^2) - \mu^2$$

Di mana:

- $E(X^2)$ adalah **ekspektasi (rata-rata)** dari $X^2$.
  
- $\mu = E(X)$ adalah rata-rata (mean) dari X, dan dapat dihitung sebagai:

$$\mu = \int_{-\infty}^{\infty} x \cdot f(x) \, dx$$

##### 2. Ekspektasi dari $X^2$

Ekspektasi $E(X^2)$, atau rata-rata dari $X^2$, dapat dihitung dengan cara yang sama seperti menghitung E(X), hanya saja menggunakan $x^2$ sebagai pengganti x:

$$E(X^2) = \int_{-\infty}^{\infty} x^2 \cdot f(x) \, dx$$

##### 3. Persamaan Variansi untuk Variabel Acak Kontinu

Untuk menghitung variansi $\sigma^2$, kita gunakan hubungan berikut:

$$\sigma^2 = E(X^2) - \mu^2$$

Dari langkah sebelumnya:

- $E(X^2) = \int_{-\infty}^{\infty} x^2 \cdot f(x) \, dx$
- $\mu = \int_{-\infty}^{\infty} x \cdot f(x) \, dx$ maka $\mu^2$ adalah kuadrat dari hasil ekspektasi tersebut.

Jadi, persamaan variansi untuk variabel acak kontinu adalah:

$$\sigma^2 = \int_{-\infty}^{\infty} x^2 \cdot f(x) \, dx - \left( \int_{-\infty}^{\infty} x \cdot f(x) \, dx \right)^2$$

##### 4. Contoh

Misalkan variabel acak kontinu X memiliki fungsi densitas probabilitas (pdf):

![[Screenshot 2024-10-04 at 13.15.20.png]]
###### a. Menghitung Ekspektasi $\mu$:

![[Screenshot 2024-10-04 at 13.16.06.png]]

###### b. Menghitung Ekspektasi $X^2$:

![[Screenshot 2024-10-04 at 13.16.47.png]]

###### c. Menghitung Variansi $\sigma^2$:

![[Screenshot 2024-10-04 at 13.19.09.png]]

#### C. Contoh  4.10

Misalkan peubah acak X menyatakan banyaknya bagian yang cacat dari suatu mesin bila 3 suku cadang disamping dari rantai produksi akan diuji. Berikut adalah distribusi peluang X

![[Screenshot 2024-10-04 at 13.24.44.png]]

Hitunglah $𝛔^2$

##### Penyelesaian:

Soal ini meminta kita menghitung _varian_ (σ²) dari variabel acak **X** yang menyatakan banyaknya bagian cacat dari mesin. Berikut adalah distribusi peluang dari **X**:

![[Screenshot 2024-10-04 at 13.25.42.png]]

###### Tahap 1: Menghitung Ekspektasi ($E[X]$)

![[Screenshot 2024-10-04 at 13.28.52.png]]

###### Tahap 2: Menghitung Ekspektasi Kuadrat ($E[X²]$)

![[Screenshot 2024-10-04 at 13.29.08.png]]

###### Tahap 3: Menghitung Varian $(σ²)$

![[Screenshot 2024-10-04 at 13.29.20.png]]

#### D. Contoh  4.11

Jika X adalah suatu variabel acak dengan fungsi densitas probabilitas sebagai berikut:

![[Screenshot 2024-10-04 at 13.30.16.png]]

Hitunglah nilai varians $g(X)=4X+3$

##### Penyelesaian

![[Screenshot 2024-10-04 at 13.30.54.png]]
###### Tahap 1: Menghitung Varian $(σ²)$

![[Screenshot 2024-10-04 at 13.40.00.png]]

---

# [[Kegiatan Belajar 3 - Distribusi Peluang Bersama]]

Misalkan ada suatu variabel acak X dan variabel acak Y, maka distribusi peluang gabungan dari dua variabel acak X dan Y dengan kejadian simultan antara keduanya adalah $f(x,y)=P(X=x, Y=y)$ kejadian peluang bersama ini terdiri atas kejadian diskrit dan kontinu


## 09. Distribusi Peluang Bersama Diskrit

#### 1. Syarat Pertama:

$$f(x, y) \geq 0 \text{ untuk semua } (x,y) $$

Ini berarti bahwa fungsi distribusi peluang gabungan f(x,y) selalu bernilai non-negatif untuk setiap pasangan nilai x dan y. Ini adalah syarat dasar dari fungsi peluang karena peluang tidak bisa bernilai negatif.

#### 2. Syarat Kedua:

$$\sum_x \sum_y f(x, y) = 1.$$

Persamaan ini menunjukkan bahwa jumlah semua peluang dari semua kemungkinan pasangan nilai x dan y harus sama dengan 1. Ini menggarisbawahi konsep bahwa total probabilitas dari semua kejadian dalam ruang sampel harus 1.

#### 3. Syarat Ketiga:

$$P(X = x, Y = y) = f(x, y).$$

Persamaan ini mendefinisikan bahwa probabilitas bersama dari X=x dan Y=y adalah nilai dari fungsi distribusi peluang gabungan f(x,y). Jadi, fungsi f(x,y) merupakan representasi langsung dari peluang gabungan dari X dan Y untuk nilai-nilai spesifik x dan y.

#### 4. Persamaan Tambahan:

Untuk daerah sembarang A di bidang xy, probabilitas bahwa pasangan (X,Y) berada dalam daerah A dinyatakan sebagai:

$$P[(X, Y) \in A] = \sum_{(x, y) \in A} f(x, y).$$

Persamaan ini menunjukkan cara menghitung peluang gabungan jika ingin mengetahui probabilitas bahwa pasangan nilai (X,Y) berada dalam suatu wilayah atau subset tertentu A di bidang xy. Caranya adalah dengan menjumlahkan semua f(x,y) untuk setiap (x,y) yang termasuk dalam wilayah A.

#### Kesimpulan:

Distribusi peluang gabungan ini menggambarkan bagaimana peluang dua variabel diskrit (misalnya, X dan Y) bergantung satu sama lain, dan persyaratan-persyaratan di atas memastikan bahwa distribusi peluang tersebut sah sesuai dengan aturan dasar probabilitas.

#### Contoh 4.12

Dua isi ulang ballpoint diambil dari box yang berisi 3 warna biru, 2 warna merah, dan 3 warna hijau. Jika X menyatakan jumlah warna biru dan Y menyatakan jumlah warna merak, tentuikan

1. Fungsi peluang gabungan f(x,y)
2. $P[(X,Y ∈ A)]$ dimana A adalah daerah ${(x, y)|x+y≤1}$

##### Penyelesaian

##### 1. Menentukan Fungsi Peluang Gabungan $f(x,y)$

Kita harus menentukan peluang gabungan $f(x,y)$, yaitu probabilitas bahwa kita mengambil X ballpoint berwarna biru dan Y ballpoint berwarna merah dalam satu pengambilan.

###### Langkah-langkah:

- Total isi ulang ballpoint dalam kotak ada 3 biru, 2 merah, dan 3 hijau, sehingga total ada 8 ballpoint.
  
- Kita memilih dua ballpoint secara acak dari total 8 ballpoint tersebut.
  
- Fungsi peluang gabungan f(x,y) adalah probabilitas mengambil X ballpoint biru dan Y ballpoint merah.

###### 1. Langkah Pertama

Hitung total kemungkinan kombinasi memilih dua ballpoint dari 8:

![[Screenshot 2024-10-04 at 14.43.53.png]]

###### 2. Langkah Kedua

Kita perlu menghitung peluang setiap pasangan (X,Y), dengan mengingat bahwa X adalah jumlah ballpoint biru, dan Y adalah jumlah ballpoint merah. Karena kita memilih dua ballpoint, nilai X+Y haruslah 0, 1, atau 2.

![[Screenshot 2024-10-04 at 14.46.06.png]]

###### 3. Langkah 3

Fungsi Peluang Gabungan

![[Screenshot 2024-10-04 at 14.46.37.png]]

![[Screenshot 2024-10-04 at 14.52.45.png]]


##### 2. Menentukan Probabilitas $P[(X, Y) \in A]$ Dimana A Adalah Daerah $\{(x, y) | x + y \leq 1\}$ 
###### Langkah 1:

Daerah A adalah daerah dengan syarat $x + y \leq 1$, yaitu pasangan (x,y) yang memenuhi:

$$x + y \leq 1$$

Dengan kata lain, kita harus menghitung probabilitas ketika (x,y) mengambil nilai (0,0), (1,0), dan (0,1).

###### Langkah 2:

- Peluang $(0,0): f(0,0) = \frac{3}{28}$​,
- Peluang $(1,0): f(1,0)) = \frac{9}{28}$​,
- Peluang $(0,1): f(0,1)) = \frac{6}{28}$​.

###### Langkah 3:

![[Screenshot 2024-10-04 at 14.51.13.png]]

##### Jawaban Akhir:

1. Fungsi peluang gabungan $f(x,y)$ sudah ditentukan di atas.
2. Probabilitas $P[(X, Y) \in A]$ adalah $\frac{9}{14}$​.


## 10. Distribusi Peluang Bersama Kontinu


#### 1. Syarat pertama:
$$f(x, y) \geq 0$ untuk semua $(x,y)$$

Ini adalah syarat dasar dari fungsi distribusi peluang, yang menyatakan bahwa fungsi distribusi bersama f(x,y) harus selalu bernilai non-negatif untuk semua pasangan (x,y) dalam domainnya. Hal ini karena peluang tidak pernah bisa negatif.
  
#### 2. Syarat kedua:
$$\int_{-\infty}^{\infty} \int_{-\infty}^{\infty} f(x, y) \, dx \, dy = 1$$

Integral ganda ini menghitung total peluang di seluruh ruang x dan y. Nilai total peluang dari semua kejadian harus sama dengan 1. Ini adalah kondisi normalisasi yang memastikan bahwa seluruh distribusi f(x,y) merupakan distribusi peluang yang valid.
  
#### 3. Syarat ketiga: 
$$P[(X,Y) \in A] = \int\!\!\int_A f(x, y) \, dx \, dy$$

Ini adalah pernyataan probabilitas bahwa pasangan (X,Y) berada di dalam wilayah A pada bidang xy. Peluang ini diperoleh dengan menghitung integral ganda fungsi distribusi peluang f(x,y) di atas wilayah A, yang merupakan subset dari bidang xy. Jadi, untuk setiap daerah A, peluang bahwa (X,Y) berada di A dihitung dengan menjumlahkan semua nilai f(x,y) di dalam wilayah tersebut.

Secara keseluruhan, persamaan-persamaan ini merangkum syarat-syarat yang harus dipenuhi oleh fungsi distribusi peluang bersama dari dua variabel acak kontinu X dan Y agar bisa dianggap sebagai distribusi peluang yang valid.


#### 4. Contoh 4.13

Suatu perusahaan coklat mengirim berkotak kotak coklat dengan campuran krem, tofe, dan kacang berlapis coklat cerah dan pekat. Bila kotak dipilih acak serta X dan Y masing masing menyatakan proporsi yang krem berlapis coklat cerah dan pekat dan misalkan bahwa fungsi distribusi peluang bersamanya adalah

![[Screenshot 2024-10-04 at 15.00.33.png]]

1. Tunjukan bahwa syarat $\int_{-\infty}^{\infty} \int_{-\infty}^{\infty} f(x, y) \, dx \, dy = 1$ terpenuhi
   
2. Cari $P[(X,Y) \in A]$, bila A daerah 
	   ![[Screenshot 2024-10-04 at 15.02.02.png]]


##### Penyelesaian

##### 1. Menunjukan bahwa syarat  $\int_{-\infty}^{\infty} \int_{-\infty}^{\infty} f(x, y) \, dx \, dy = 1$ terpenuhi

![[Screenshot 2024-10-04 at 15.04.20.png]]

###### Langkah 1:
Integralkan terhadap x terlebih dahulu

![[Screenshot 2024-10-04 at 15.04.54.png]]

###### Langkah 2
Integralkan terhadap y

![[Screenshot 2024-10-04 at 15.06.04.png]]

###### Langkah 3
Totalkan integral X dan Y

![[Screenshot 2024-10-04 at 15.06.35.png]]

###### Kesimpulan
bahwa syarat  $\int_{-\infty}^{\infty} \int_{-\infty}^{\infty} f(x, y) \, dx \, dy = 1$ terpenuhi



##### 2. Mencari $P((X,Y) \in A)$ bila A adalah daerah $\left\{(x, y) | 0 < x < \frac{1}{2}, \frac{1}{4} < y \leq \frac{1}{2}\right\}$

Untuk menghitung probabilitas pada daerah A, kita perlu mengintegralkan fungsi kepadatan bersama f(x, y) di atas daerah A, yaitu:

![[Screenshot 2024-10-05 at 10.03.22.png]]

###### Langkah 1 
Integralkan terhadap x:

![[Screenshot 2024-10-05 at 10.03.49.png]]

###### Langkah 2
Sekarang, integralkan terhadap y:

![[Screenshot 2024-10-05 at 10.04.23.png]]

###### Simpulan

Dengan demikian, probabilitas $P((X,Y) \in A)$ adalah $\frac{13}{96}$.





