---
tags:
  - metode_statistika
  - materi_4_MS
---
# Kegiatan Belajar 2 - Ekspektasi dan Varians Distribusi Peluang

## [[04. Nilai Ekspektasi (Nilai Harapan)]]

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


## [[05. Nilai Harapan Fungsi Transformasi Acak]]

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


## [[06. Nilai Harapan dari Variabel Acak Diskrit]]

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


## [[07. Variansi]]

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



## [[08. Variansi Variabel Acak X]]

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



