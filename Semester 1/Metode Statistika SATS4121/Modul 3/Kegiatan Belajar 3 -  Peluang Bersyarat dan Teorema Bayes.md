---
tags:
  - metode_statistika
---

## [[07. Peluang Bersyarat]]

Peluang bersyarat dapat terjadi jika dua kejadian terjadi secara berurutan dan kedua kejadian tersebut tidak saling bebas namun saling mempengaruhi.

![[Screenshot 2024-09-26 at 08.15.12.png]]


#### Peluang yang terjadi sekaligus dengan syarat

Dalam konsep peluang bersyarat dikenal suatu kaidah penggandaan yang diperoleh dengan menggandakan kedua sisi rumus peluang bersyarat dengan P(A) sehingga memungkinkan untuk menghitung peluang terjadinya dia kejadian sekaligus

> Teorema 3.8
> Bila dalam suatu percobaan kejadian A dan B keduanya dapat terjadi sekaligus maka:
> ![[Screenshot 2024-09-26 at 08.16.37.png]]


#### Peluang kejadian A dan B serentak saling bebas

Jadi peluang terjadinya A dan B terjadi serentak sama dengan peluang A terjadi dikalikan dengan peluang terjadinya B bila A terjadi

>Teorema 3.9
>Bila kedua kejadian A dan B saling bebas maka:
> ![[Screenshot 2024-09-26 at 08.19.46.png]]


Jadi untuk mendapatkan peluang bahwa dua kejadian bebas akan terjadi secara bersamaan yaitu dengan mengalikan peluang kedua kejadian

> Teorema 3.10
> Bila dalam suatu percobaan kejadian kejadian $A_1, A_2, A_3, A_k$ dapat terjadi maka :
> ![[Screenshot 2024-09-26 at 08.21.53.png]]

> Teorema 3.11
> Bila kejadian kejadian $A_1, A_2, A_3, A_k$ bebas maka:
> ![[Screenshot 2024-09-26 at 08.22.40.png]]



#### Contoh 3.23

Milaskan, ruang S terdiri atas populasi sarjana di suatu kota. POpulasi dikategorikan menurut jenis kelamin dan status pekerjaan. Datanya adalah sebagai berikut :

![[Screenshot 2024-09-26 at 08.25.35.png]]

Dari populasi tersebut, akan dioambil secara acak satu orang yang ditugaskan mempublikasikan pentingnya didirikan industri baru di kota tersebut.
Perhatikan kejadian kejadian tersebut:

M : yang terpilih laki laki
E : yang terpilih telah bekerja

Berapa peluang terpilihnya orang laki laki bila yang diinginkan adalah orang yang bekerja?

##### Penyelesaian

Diketahui bahwa kita akan memilih orang yang **bekerja**. Kita diminta menghitung peluang terpilihnya orang laki-laki di antara orang-orang yang bekerja. Mari kita selesaikan soal ini langkah demi langkah.

**Data pada tabel:**

• Laki-laki bekerja: 460 orang

• Laki-laki menganggur: 40 orang

• Perempuan bekerja: 140 orang

• Perempuan menganggur: 260 orang

Total populasi: 900 orang


###### Langkah 1: Identifikasi kejadian

Dari soal, kita diperkenalkan dua kejadian:

•	 M : yang terpilih adalah laki-laki.
•	 E : yang terpilih adalah orang yang bekerja.

Peluang yang ditanyakan adalah peluang terpilihnya laki-laki bila kita sudah tahu bahwa yang dipilih adalah orang yang bekerja, yang dinyatakan sebagai peluang kondisional  P(M|E) .


###### Langkah 2: Rumus peluang kondisional

Peluang kondisional  P(M|E)  dihitung menggunakan rumus:

$P(M|E) = \frac{P(M \cap E)}{P(E)}$

Artinya, peluang terpilihnya laki-laki yang bekerja sama dengan peluang seseorang adalah laki-laki dan bekerja dibagi dengan peluang terpilihnya seseorang yang bekerja.


###### Langkah 3: Hitung komponen peluang

1.	Peluang  $P(E)$ , yaitu peluang terpilihnya orang yang bekerja:
	Jumlah orang yang bekerja adalah 600 orang (460 laki-laki + 140 perempuan).
	Jadi,  $P(E)$  dihitung sebagai:
	
	$P(E) = \frac{600}{900} = \frac{2}{3}$

2.	Peluang  $P(M \cap E)$ , yaitu peluang terpilihnya laki-laki yang bekerja:
	Jumlah laki-laki yang bekerja adalah 460 orang.
	Jadi,  P(M \cap E)  dihitung sebagai:
	
	$P(M \cap E) = \frac{460}{900} = \frac{23}{45}$ 



###### Langkah 4: Hitung peluang kondisional

Sekarang, kita substitusi nilai  P(M \cap E)  dan  P(E)  ke dalam rumus peluang kondisional:

$P(M|E) = \frac{P(M \cap E)}{P(E)} = \frac{\frac{460}{900}}{\frac{600}{900}} = \frac{460}{600}$


Sederhanakan pecahan:

$P(M|E) = \frac{460}{600} = \frac{23}{30}$


Rumusan tersebut diperoleh:
![[Screenshot 2024-09-26 at 08.32.30.png]]

###### Kesimpulan

Peluang terpilihnya orang laki-laki bila yang diinginkan adalah orang yang bekerja adalah $\frac{23}{30}$ atau sekitar 0,767 (76,7%).

**Jadi, langkah-langkah utamanya adalah:**

1.	Mengidentifikasi kejadian-kejadian dan menggunakan rumus peluang kondisional.
2.	Menghitung peluang kejadian gabungan  P(M \cap E) .
3.	Menghitung peluang kejadian  P(E) .
4.	Substitusi ke dalam rumus peluang kondisional dan sederhanakan.



#### Contoh 3.24

Peluang kereta api Gajayana berangkat tepat pada waktunya p(A) = 0,85. Peluang kereta api Gajayana datang tepat waktu adalah p(B) = 0,90
dan peluang kereta api tersebut berangkat dan datang tepat waktu adalah P(A∩B) = 0,75

Hitunglah:
- Peluang kereta Gajayana datang tepat waktu jika diketahui kereta tersebut berangkat tepat pada waktunya
- Peluang bahwa kereta api Gajayana berangkat tepat waktu bila diketahui kereta api tersebut datang tepat pada waktunya

##### Penyelesaian

Diketahui:

•	 P(A) = 0,85  → Peluang kereta api Gajayana berangkat tepat pada waktunya.
•	 P(B) = 0,90  → Peluang kereta api Gajayana datang tepat pada waktunya.
•	 P$(A \cap B)$ = 0,75  → Peluang kereta api berangkat dan datang tepat pada waktunya.

Kita diminta untuk menghitung:

1.	Peluang kereta api datang tepat waktu jika diketahui berangkat tepat pada waktunya.

2.	Peluang kereta api berangkat tepat waktu jika diketahui datang tepat pada waktunya.


###### Langkah 1: Peluang kereta api datang tepat pada waktunya bila diketahui kereta berangkat tepat waktu

Ini adalah peluang kondisional  P(B|A) , yang berarti “peluang kereta api datang tepat waktu jika diketahui berangkat tepat waktu.”

Rumus peluang kondisional adalah:

	$P(B|A) = \frac{P(A \cap B)}{P(A)}$

Substitusikan nilai yang diketahui:

	$P(B|A) = \frac{0,75}{0,85}$

Hitung hasilnya:

	$P(B|A) \approx 0,882$

Jadi, **peluang kereta api datang tepat pada waktunya bila diketahui kereta berangkat tepat pada waktunya adalah 0,882** atau sekitar 88,2%.


###### Langkah 2: Peluang kereta api berangkat tepat pada waktunya bila diketahui kereta datang tepat waktu

Ini adalah peluang kondisional  P(A|B) , yang berarti “peluang kereta api berangkat tepat waktu jika diketahui datang tepat waktu.”

Rumus peluang kondisional juga serupa:

	$P(A|B) = \frac{P(A \cap B)}{P(B)}$

Substitusikan nilai yang diketahui:

	$P(A|B) = \frac{0,75}{0,90}$

Hitung hasilnya:

	$P(A|B) \approx 0,833$

Jadi, **peluang kereta api berangkat tepat pada waktunya bila diketahui kereta datang tepat pada waktunya adalah 0,833** atau sekitar 83,3%.


###### Kesimpulan:

1.	Peluang kereta api datang tepat waktu jika diketahui berangkat tepat waktu adalah 88,2%  $(P(B|A))$ .

2.	Peluang kereta api berangkat tepat waktu jika diketahui datang tepat waktu adalah 83,3%  $(P(A|B))$ .

Langkah-langkah utama dalam menyelesaikan soal ini adalah:

1.	Mengidentifikasi peluang kondisional yang diminta.
2.	Menggunakan rumus peluang kondisional  $P(B|A) = \frac{P(A \cap B)}{P(A)}$  atau  $P(A|B) = \frac{P(A \cap B)}{P(B)}$
3.	Menghitung hasil dengan substitusi nilai-nilai yang diketahui.


## [[08. Teorema Bayes]]

Teorema bayes diawali dari konsep peluang total yang merupakan kejadian-kejadian $B_1, B_2, B_3, B_n ≠ 0$ untuk $i=1,2,3,...,n$ Maka untuk sembarang kejadian A yang merupakan himpunan bagian S berlaku:

![[Screenshot 2024-09-26 at 08.46.14.png]]

Illustrasi dari konsep Bayes dapat dilihat pada gambar berikut:

![[Screenshot 2024-09-26 at 08.46.39.png]]
>  Teorema 3.11
>  Misalkan kejadian-kejadian B_1, B_2, B_3, ..., B_k membentuk partisi dari ruang sampel S dimana P(B) ≠ 0 untuk i=1,2,3,...,n. Andaikan A adalah sembarang peristiwa dalam S sedemikian rupa hingga P(A)≠) maka untuk k = 1,2,3,..n berlaku:
>  
>  ![[Screenshot 2024-09-26 at 08.49.43.png]]


###### Bentuk umum Teorema Bayes adalah seperti yang ditunjukkan pada gambar:

	$P(B_k | A) = \frac{P(B_k \cap A)}{\sum_{i=1}^{n} P(B_i \cap A)} = \frac{P(B_k) P(A | B_k)}{\sum_{i=1}^{n} P(B_i) P(A | B_i)}$


###### Penjelasan Notasi:

•	 $P(B_k | A)$  : Peluang kejadian  $B_k$  terjadi jika diketahui kejadian  A  terjadi.
•	 $P(B_k \cap A)$  : Peluang kejadian  $B_k$  dan  A  terjadi bersamaan.
•	 $P(A | B_k)$  : Peluang kejadian  A  terjadi jika diketahui kejadian  $B_k$  terjadi.
•	 $P(B_k)$  : Peluang kejadian  $B_k$  terjadi.
•	 $\sum_{i=1}^{n} P(B_i \cap A)$  : Jumlah peluang semua kejadian  $B_i$  dengan kejadian  A .


###### Langkah-langkah Teorema Bayes:

1.	**Identifikasi Peluang Dasar (Prior Probability):**
	Dalam rumus ini,  $P(B_k$)  adalah peluang dasar atau prior dari kejadian  $B_k$ , yaitu peluang  $B_k$  terjadi sebelum kita mengetahui bahwa  $A$  telah terjadi.

2.	**Hitung Peluang Bersyarat (Conditional Probability):**
	Kita menghitung peluang bersyarat  $P(A | B_k)$ , yaitu peluang kejadian  A  terjadi dengan syarat bahwa  $B_k$  telah terjadi. Informasi ini bisa berasal dari data historis, statistik, atau asumsi yang diberikan dalam soal.

3.	**Hitung Peluang Total (Total Probability):**
	Untuk mendapatkan denominator (penyebut) pada rumus di atas, kita harus menghitung total peluang kejadian  A  terjadi, yang merupakan jumlah dari semua peluang bersyarat  $P(A | B_i)$  dikalikan dengan prior dari masing-masing  $B_i$  untuk setiap  $i$ . Ini merupakan bagian dari Teorema Total Peluang.
	
	Rumus total peluang:
	$P(A) = \sum_{i=1}^{n} P(B_i) P(A | B_i)$
	
	Di mana  $B_1, B_2, …, B_n$  merupakan semua kemungkinan kejadian yang dapat menyebabkan terjadinya  A .

4.	**Substitusi ke dalam Teorema Bayes:**
	Setelah kita mendapatkan peluang total  $P(A)$  (penyebut), kita dapat menghitung peluang kondisional  $P(B_k | A)$  dengan memasukkan nilai prior  $P(B_k)$  dan peluang bersyarat  $P(A | B_k)$  ke dalam rumus:
	
	$P(B_k | A) = \frac{P(B_k) P(A | B_k)}{P(A)}$
	
	Ini memberikan kita peluang posterior, yaitu peluang bahwa  B_k  terjadi setelah diketahui bahwa  A  telah terjadi.

#### Contoh 3.14

Suatu perusahaan besar menggunakan 3 hotel sebagai tempat menginap para langganannya. Dari pengalaman yang lalu diketahui bahwa 20% langganannya ditempatkan di Hotel I, 50% di hotel B, dan 30% di hotel S. Bila 5% kamar mandi di hotel I tidak berfungsi dengan baik, 4% di hotel B dan 8% di hotel S. berapa peluang bahwa

1. Seseorang langganan mendapat kamar yang kamar mandinya tidak berfungsi
2. Seseorang yang mendapat kamar mandi yang tidak baik ditempatkan di hotel S?

##### Penyelesaian

###### Bagian a: Peluang seorang pelanggan mendapat kamar dengan kamar mandi yang tidak berfungsi

Untuk menghitung peluang total seorang pelanggan mendapatkan kamar mandi yang tidak berfungsi, kita gunakan Teorema Total Peluang. Peluang total tersebut adalah jumlah dari peluang kamar mandi tidak berfungsi di setiap hotel, dikalikan dengan peluang pelanggan ditempatkan di hotel tersebut.

Rumus Teorema Total Peluang:

	$P(T) = P(T|I) \cdot P(I) + P(T|B) \cdot P(B) + P(T|S) \cdot P(S)$


Substitusikan nilai-nilai yang diketahui:

	$P(T) = (0,05 \times 0,20) + (0,04 \times 0,50) + (0,08 \times 0,30)$


Hitung setiap komponen:

	$P(T) = (0,01) + (0,02) + (0,024) = 0,054$


Jadi, **peluang seorang pelanggan mendapat kamar dengan kamar mandi yang tidak berfungsi adalah 0,054** atau 5,4%.


###### Bagian b: Peluang seseorang yang mendapatkan kamar mandi yang tidak berfungsi ditempatkan di hotel S

Untuk pertanyaan ini, kita menggunakan Teorema Bayes karena kita diminta mencari peluang pelanggan ditempatkan di hotel S dengan syarat bahwa kamar mandi yang didapat tidak berfungsi.

Rumus Teorema Bayes:

	$P(S|T) = \frac{P(T|S) \cdot P(S)}{P(T)}$


Dari bagian a, kita sudah menghitung  P(T) = 0,054 . Sekarang substitusikan nilai yang diketahui ke dalam rumus:

	$P(S|T) = \frac{(0,08 \times 0,30)}{0,054} = \frac{0,024}{0,054}$


Hitung hasilnya:

	$P(S|T) \approx 0,444$


Jadi, **peluang seseorang yang mendapat kamar mandi yang tidak berfungsi ditempatkan di hotel S adalah 0,444** atau 44,4%.

###### Kesimpulan:

1. Peluang seorang pelanggan mendapatkan kamar dengan kamar mandi yang tidak berfungsi adalah **5,4%**.

2. Peluang seseorang yang mendapatkan kamar mandi yang tidak berfungsi ditempatkan di hotel S adalah **44,4%**.


**Langkah-langkah utama untuk menyelesaikan soal ini adalah:**

1. Menghitung peluang total menggunakan **Teorema Total Peluang** untuk soal a.

2. Menggunakan **Teorema Bayes** untuk menghitung peluang kondisional pada soal b.


