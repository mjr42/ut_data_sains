---
tags:
  - metode_statistika
---

## [[07. Ukuran Penyebaran]]

Ukuran pemusatan kurang bermanfaat apabila tidak diketahui atau disertai pemencaran (dispersi) atau penympangan (deviasi) setiap datanya dengan nilai rata ratanya. Misalnya jika nilai deviasi besar maka nilai rata-rata yang didapatkan kurang baik dalam menggambarkan kondisi datanya.

Dalam hal ini, ukuran penyebaran digunakan untuk menganalisis pemencaran, penyimpangan, atau keragaman suatu kelompok data. beberapa ukurannya adalah range, varians, standard deviasi, dan koefisien variant



## [[08. Range]]

Range merupakan selisih antar data tertinggi (maksimum) dan data terendah (minimum). Perhitungan ukuran ini muydah didaptkan untuk menjunjukan seberapa jauh data memencar, tetapi tidak menunjukan keberagaman. 

Ukuran ini jarang digunakan karena hanya berdasarkan dua amatan yaitu nimai maksimum dan minimum

$Range = x_{max} - x_{min}$


## [[09. Varians dan Standard Deviasi]]

Berbeda dengan range, varians menggunakan keseluruhan data dan menunjukan deviasi atau keberagaman data. Ukuran ini didasarkan pada perbedaan antara nilai-nilai suatu amatan dengan rata ratanya. Dalam perhitungannya dirumuskan sebagai penjumlahan kuadrat selisih antara amana dengan rata-ratanya, kemudian dibagi dengan total amatan.

#### a. Varian Populasi (Persamaan 2.11)

Varian populasi $(\sigma^2)$ digunakan untuk mengukur seberapa tersebar data dalam suatu populasi. Rumusnya adalah:


$\sigma^2 = \sum_{i=1}^{N} \frac{(x_i - \bar{x})^2}{N}$


###### **Penjelasan:**

- $\sigma^2$: Varian populasi.
- $N$: Total jumlah data dalam populasi.
- $x_i$: Setiap observasi (nilai data ke-i) dalam populasi.
- $\bar{x}$: Rata-rata populasi, yaitu rata-rata dari semua nilai $x_i$.
- $\sum_{i=1}^{N} (x_i - \bar{x})^2$: Penjumlahan kuadrat deviasi setiap observasi dari rata-rata populasi.

###### **Langkah-langkah menghitung varian populasi:**

1.	Hitung rata-rata populasi $(\bar{x})$.
2.	Hitung selisih antara setiap data dengan rata-rata $(x_i - \bar{x})$.
3.	Kuadratkan selisih tersebut untuk setiap data.
4.	Jumlahkan semua kuadrat deviasi.
5.	Bagi hasil jumlah kuadrat deviasi dengan total jumlah data $N$.


#### b. Varian Sampel (Persamaan 2.12)

Jika kita mengambil sampel dari populasi, rumus untuk menghitung varian sedikit berbeda. Varian sampel $s^2$ dihitung dengan rumus:


$s^2 = \sum_{i=1}^{n} \frac{(x_i - \bar{x})^2}{n-1}$


###### **Penjelasan:**

- $s^2$: Varian sampel.
- $n$: Jumlah data dalam sampel.
- $x_i$: Setiap observasi dalam sampel.
- $\bar{x}$: Rata-rata sampel.
- $\sum_{i=1}^{n} (x_i - \bar{x})^2$: Penjumlahan kuadrat deviasi setiap observasi dari rata-rata sampel.

Perbedaan utama di sini adalah bahwa kita membagi dengan n-1 (bukan n), karena hal ini memperhitungkan derajat kebebasan dalam sampel.


###### **Langkah-langkah menghitung varian sampel:**

1.	Hitung rata-rata sampel $(\bar{x})$.
2.	Hitung deviasi masing-masing data dari rata-rata sampel.
3.	Kuadratkan setiap deviasi.
4.	Jumlahkan hasil kuadrat deviasi.
5.	Bagi hasilnya dengan $n-1$ (jumlah data dikurangi satu).


#### c. Bentuk Alternatif Rumus Varian Sampel (Persamaan 2.13)

Persamaan 2.13 merupakan bentuk rumus lain untuk varian sampel yang diperoleh dari pengembangan persamaan 2.12. Rumus ini menghindari langkah penghitungan rata-rata terlebih dahulu dan mempermudah perhitungan langsung dari nilai observasi:


$s^2 = \frac{\sum_{i=1}^{n} x_i^2 - \frac{\left(\sum_{i=1}^{n} x_i\right)^2}{n}}{n-1}$


###### **Penjelasan:**
 
•	$\sum_{i=1}^{n} x_i^2$: Jumlah kuadrat dari setiap observasi.
•	$\left(\sum_{i=1}^{n} x_i\right)^2 / n:$ Kuadrat dari jumlah seluruh observasi, dibagi dengan jumlah data.


###### **Langkah-langkah menghitung varian sampel dengan persamaan ini:**

1.	Hitung jumlah kuadrat observasi $(\sum x_i^2)$.
2.	Hitung kuadrat dari jumlah seluruh observasi, lalu bagi dengan jumlah data.
3.	Kurangkan hasil langkah kedua dari langkah pertama.
4.	Bagi hasilnya dengan $n-1$.


Nilai variants lebih baik digunakan dan diinterpretasikan ketika membandingkan beberapa varians dari dua atau lebih variabel. Dari beberapa nilai variabel tersebut, varians atau deviasi yang besar menunjukan penyimpangan dan keberagaman yang besar pula. Dalam hal interpretasi, niklai variant yang diperoleh dari pengkuadratan menyebabkan sulit untuk mendapatkan interpretasinya. Oleh karena itu diperlukan standar deviasi.

---

## Standar Deviasi

Standar deviasi dikenal juga sebagai simpangan baku, yang merupakan akar dari nilai varians. Hal ini dikarenakan standar deviasi merupakan hasil pengukuran yang memberikan nilai sama dengan data asli.

Untuk populasi, standar deviasi merupakan akar dari varians populasi, sedangkan standar deviasi sampel merupakan akar dari varians sampel.


#### Simpangan Baku Sampel


$s = \sqrt{s^2} = \sqrt{\sum_{i=1}^{n} \frac{(x_i - \bar{x})^2}{n-1}}$


###### **Penjelasan:**

1.	**Simpangan Baku (Standard Deviation, s):**
	•	Simpangan baku adalah ukuran dispersi atau seberapa tersebar data di sekitar rata-ratanya.
	
	•	Simpangan baku diperoleh dengan mengambil akar kuadrat dari varian. Simpangan baku memberikan nilai dalam satuan yang sama dengan data asli, sehingga lebih mudah untuk ditafsirkan dibandingkan varian (yang satuannya adalah kuadrat dari data asli).

2.	**Komponen Rumus:**
	•	$\sum_{i=1}^{n} (x_i - \bar{x})^2$: Jumlah kuadrat dari deviasi (selisih) setiap data $(x_i)$ dari rata-rata sampel (\bar{x}).
	
	•	$n-1$: Merupakan derajat kebebasan. Pada varian sampel, kita menggunakan n-1 untuk memperhitungkan fakta bahwa kita hanya menggunakan sampel, bukan seluruh populasi.
	
	•	\sqrt{}: Akar kuadrat dari varian, yang memberikan simpangan baku.

3.	**Langkah-langkah Menghitung Simpangan Baku Sampel:**
	1.	Hitung rata-rata sampel $(\bar{x})$.
	2.	Hitung deviasi setiap data dari rata-rata, yaitu $x_i - \bar{x}$.
	3.	Kuadratkan setiap deviasi.
	4.	Jumlahkan hasil kuadrat deviasi.
	5.	Bagi jumlah kuadrat deviasi dengan $n-1$ (derajat kebebasan) untuk mendapatkan varian sampel $s^2$.
	6.	Ambil akar kuadrat dari varian $s^2$ untuk mendapatkan simpangan baku s.

4.	**Perbedaan dengan Varian:**
	•	Varian $(s^2)$ adalah ukuran dispersi data yang menggunakan kuadrat dari deviasi, sehingga satuannya adalah kuadrat dari satuan asli.
	
	•	Simpangan baku $(s)$ mengembalikan hasil dalam satuan yang sama dengan data asli, sehingga lebih mudah dipahami dalam konteks aplikasi.


#### Simpangan Baku Populasi

Rumus simpangan baku populasi (\sigma) dapat dituliskan sebagai berikut:


$\sigma = \sqrt{\frac{\sum_{i=1}^{N} (x_i - \mu)^2}{N}}$


###### Penjelasan komponen dalam rumus:

•	$\sigma$: Simpangan baku populasi.
•	$x_i$: Setiap observasi (data ke-i) dalam populasi.
•	$\mu$: Rata-rata populasi, yaitu jumlah seluruh data dalam populasi dibagi dengan total jumlah data dalam populasi $(N)$.
•	$N$: Jumlah total observasi atau data dalam populasi.
•	$\sum_{i=1}^{N} (x_i - \mu)^2$: Penjumlahan kuadrat deviasi setiap data dari rata-rata populasi.


###### Langkah-langkah Menghitung Simpangan Baku Populasi:

1.**Hitung rata-rata populasi (\mu):**

$\mu = \frac{1}{N} \sum_{i=1}^{N} x_i$

Rata-rata populasi adalah jumlah seluruh data dalam populasi $(x_i)$ dibagi dengan jumlah total data N.


2.**Hitung deviasi setiap data dari rata-rata $(x_i - \mu)$:**
Untuk setiap data dalam populasi, hitung selisih antara nilai data tersebut dan rata-rata populasi.


3.**Kuadratkan setiap deviasi $((x_i - \mu)^2)$:**
Setelah mendapatkan deviasi, kuadratkan nilai tersebut untuk setiap data.


**4.Jumlahkan semua kuadrat deviasi:**

$\sum_{i=1}^{N} (x_i - \mu)^2$

Ini adalah total kuadrat deviasi dari seluruh data dalam populasi.


**5.Bagi jumlah kuadrat deviasi dengan $N$:**
Setelah mendapatkan jumlah kuadrat deviasi, bagi hasilnya dengan jumlah total data dalam populasi $(N)$.


**6.Ambil akar kuadrat hasil tersebut:**
Ambil akar kuadrat dari hasil langkah sebelumnya untuk mendapatkan simpangan baku populasi $(\sigma)$.

###### Contoh

![[Screenshot 2024-09-19 at 11.42.28.png]]

Hitunglah varians dan standar deviasi


**Langkah 1: Hitung Rata-rata Sampel $(\bar{x})$**

•	Data berat badan yang diberikan adalah 20 data $(n = 20)$.
•	Rata-rata sampel $(\bar{x})$ dihitung dengan menjumlahkan semua data berat badan dan membaginya dengan jumlah total data.

Tabel berat badan:

$\bar{x} = \frac{\sum_{i=1}^{20} x_i}{20} = \frac{48,070}{20} = 2,4$


Jadi, rata-rata berat badan adalah 2,4 kg.


**Langkah 2: Hitung Deviasi Setiap Data dari Rata-rata**

Untuk setiap data $x_i$, hitung deviasi (selisih) antara nilai data dengan rata-rata sampel $(x_i - \bar{x})$:

- Contoh untuk data pertama:
  $x_1 = 2,5 \quad \text{dan} \quad \bar{x} = 2,4$
  $x_1 - \bar{x} = 2,5 - 2,4 = 0,1$


Deviasi dihitung untuk setiap data dalam tabel. Misalnya, untuk data kedua:

$x_2 = 2,6, \quad x_2 - \bar{x} = 2,6 - 2,4 = 0,2$


**Langkah 3: Kuadratkan Setiap Deviasi $((x_i - \bar{x})^2)$**

Setiap deviasi kemudian dikuadratkan untuk mendapatkan nilai $(x_i - \bar{x})^2.$

•	Contoh untuk data pertama:

$(x_1 - \bar{x})^2 = (0,1)^2 = 0,010$


Kuadratkan nilai deviasi untuk semua data dan hasilnya dicantumkan dalam kolom terakhir pada tabel.


**Langkah 4: Jumlahkan Kuadrat Deviasi**

Jumlahkan semua kuadrat deviasi dari data sampel:

$\sum_{i=1}^{20} (x_i - \bar{x})^2 = 0,010 + 0,040 + 0,010 + … + 0,003 = 0,395$



**Langkah 5: Hitung Varian Sampel (s^2)**

Varian sampel dihitung dengan rumus:

$s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}$

Dengan $n = 20$, maka:

$s^2 = \frac{0,395}{20-1} = \frac{0,395}{19} = 0,021$


Jadi, varian sampel $s^2$ adalah $0,021$.


**Langkah 6: Hitung Simpangan Baku Sampel (s)**

Simpangan baku adalah akar kuadrat dari varian:

$s = \sqrt{s^2} = \sqrt{0,021} = 0,144$


**Kesimpulan:**

•	Rata-rata sampel: 2,4 kg.
•	Jumlah kuadrat deviasi: 0,395.
•	Varian sampel: 0,021.
•	Simpangan baku sampel: 0,144.


## [[10. Koefisien Varians]]

Nilai koefisien varians menunjukan nilai relatif standar deviasi terhadap rata rata. Secara umum, nilai ini digunakan untuk membandingkan keragaman beberapa variabel yang memiliki standar deviasi dan rata rata yang berbeda. 

Koefisien Varians dapat dinyatakan dengan presentase seperti berikut:


$CV = \frac{s}{\bar{x}}x100$%

![[Screenshot 2024-09-19 at 13.33.33.png]]

Secara umum, kedua kelompok memiliki keragaman yang hampir sama, karena memiliki nilai CV yang hampir sama. Namun kelompok B memiliki nilai CV yang lebih kecil dan dapat dikatakan memiliki keragaman lebih kecil dan dapat dikatakan pula lebih homogen.

