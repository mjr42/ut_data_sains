---
tags:
  - metode_statistika
---

## [[05. Jenis dan Skala Pengukuran Data]]

Secara umum terdapat dua jenia data yang digunakan dalam analisis data atau pengolahan data, yaitu:
- Data Kategorik (kualitatif)
- Data Kontinu (Kuantitatif). di beberapa literasi lain, data kontinu juga daapt disebut data numerik dan pengukuran (Numerical or Measurement)

Kemudia data kategorik dan nimerik diklasifikasikan kembali menjadi beberapa jenis data,
Menurut skala pengukurannya, Klasifikasi data adalah sebagai berikut


### Klasifikasi Data

##### 1. Nominal

>Suatu data dikatakan meiliki skala pengukuran nominal jika data tersebur berbentuk kategorik yang disajikan dalam bentuk label non-numerik dan kode numerik.

Untuk kekepntingan pengolahan data, data-data kategorik tersebut seringkali disajikan dalam bentuk kode numerik. Meskipun data tersebut dilabel dalam bentuk numerik, namun operasi aritmatikanya seperti penjumlahan, pengurangan, dan lainnya tidak berlaku. Dengan demikian pelabelan numerik pada kategori hanya untuk membedakan antar data. 

Olehkarena itu perhitungan rata-rata data tidak mungkin dilakukan dan menghasilkan informasi yang kurang sahih. Informasi yang bisa diberikan dari data kategorik ini adalah Frekuensi dan Presentase.

##### 2. Ordinal

>Suatu data dikatakan memiliki skala pengukuran ordinal, jika data tersebut meiliki sidat skala dan memiliki order (urutan) jika dilabelkan dalam kode numerik.

Seperti halnya pada data nominal, pada data skala pengukuran ordinal tidak bisa dilakukan operasi aritmatika.

##### 3. Interval

>Data dikatakan memiliki skala pengukuran interval, jika data tersebut memiliki sifat skala ordinal dan memiliki interval yang sama dalam unit pengukuran.

Hal terpenting yang membedakan dengan skala pengukuran rasio adalah skala interval tidak memiliki nilai 0 (nol) mutlak. artinya nilai perbandingan (rasio) tidak bermakna.

Pada data skala interval, dapat dilakukan operasi aritmatika

##### 4. Rasio

>Suatu data dikatakan memiliki skala pengukuran rasio, jika data tersebut memiliki sifat skala interval dan memiliki nilai 0 (nol) mutlak.

Contoh data skala rasio adalah berat badan, tinggi badan, jarak lokasi, waktu, dan sebagainya. Jika seorang membayar sebesar Rp 0.000 artinya mereka tidak membayar atau gratis. 

Data dengan skala rasio selalu datanya numerik sehingga dapat dilakukan operasi aritmatik.


#### Data yang memiliki skala pengukuran nominal dan ordinal seringkali diklasifikasikan data kategorik atau kualitatif, 
#### sementara data yang memiliki data skala pengukuran interval dan rasio diklasifikasikan sebagai data kontinu atau kualitatif


![[Screenshot 2024-08-17 at 18.06.02.png]]


---

## [[06. Notasi Penjumlahan (𝚺)]]

>Dalam analisis statistika, data yang terhimpun biasanya cukup banyak, sehingga dibutuhkan cara menyajikan data yang efektif melalui lambang matematik. 

Misalkan sekumpulan data yang ditulisakan $x_1 , x_2 , x_3, ... x_n$. Sebanyak n pengamatan, $x_1$ adalah pengamatan pertama, $x_2$ adalah pengamatan ke dua dan seterusnya.

>Untuk menyajikan data yang lebih efektif, maka jumlah data pengamatan dapt ditulis dengan lambang 𝚺 atau bisa dibaca "sigma"

Gambar yang Anda unggah menjelaskan tentang notasi sigma $(\Sigma)$ dalam matematika, yang digunakan untuk menunjukkan jumlah dari sejumlah bilangan. Berikut penjelasan lebih rinci:

1. Notasi $\Sigma_{i=1}^{n} x_i$: 
   - Menunjukkan jumlah dari \(n\) bilangan \($x_1, x_2, \dots, x_n$\).
   - Dibaca sebagai "jumlah ($x_i$) dari ($i = 1$) hingga (n)". 
   - Secara umum, ini menyatakan ($x_1 + x_2 + \dots + x_n$), yaitu penjumlahan semua bilangan \($x_i$\) dari \($i = 1$\) hingga \(n\).

2. Contoh-contoh yang diberikan:
   - $\Sigma_{i=1}^{4} x_i = x_1 + x_2 + x_3 + x_4$: Ini menunjukkan jumlah dari empat bilangan ($x_1, x_2, x_3,$) dan ($x_4$).
   
   - $\Sigma_{i=1}^{3} (7 + x_i) = (7 + x_1) + (7 + x_2) + (7 + x_3)$: Menunjukkan jumlah dari tiga ekspresi, masing-masing menambahkan 7 pada \($x_1$\), \($x_2$\), dan \($x_3$\).

   - $\Sigma_{i=1}^{5} x_i^3 = x_1^3 + x_2^3 + x_3^3 + x_4^3 + x_5^3$: Menunjukkan jumlah dari lima bilangan yang dikuadratkan, yaitu $(x_1^3, x_2^3, x_3^3, x_4^3,) dan (x_5^3)$.

Intinya, notasi \(\Sigma\) digunakan untuk merangkum proses penjumlahan deret angka atau ekspresi tertentu.

### Sifat dasar operasi penjumlahan 𝚺

Gambar yang Anda unggah menjelaskan beberapa sifat dasar dari notasi sigma (\(\Sigma\)) dan beberapa contoh aplikasinya. Berikut penjelasan untuk setiap bagian:

### Sifat-sifat Dasar Sigma:

1. $\Sigma_{i=1}^{n} c = c + c + \dots + c = nc$
   - Jika \(c\) adalah suatu konstanta, jumlah \(n\) kali konstanta tersebut sama dengan \(nc\).

2. $\Sigma_{i=1}^{n} cx_i = c \Sigma_{i=1}^{n} x_i$
   - Jika setiap elemen \($x_i$\) dikalikan dengan konstanta \(c\), hasilnya sama dengan konstanta \(c\) dikalikan dengan jumlah dari \($x_i$\).

3. $\Sigma_{i=1}^{n} (x_i + y_i) = \Sigma_{i=1}^{n} x_i + \Sigma_{i=1}^{n} y_i$
   - Jumlah dari penjumlahan dua deret \($x_i$\) dan \($y_i$\) sama dengan penjumlahan dari jumlah masing-masing deret.

#### $\Sigma_{i=1}^{n} (ax_i + by_i)^2$
![[Screenshot 2024-08-17 at 18.43.11.png]]
- Awalnya, ekspresi ini dikembangkan menjadi bentuk $\Sigma_{i=1}^{n} ((ax_i)^2 + ab(x_i y_i) + (by_i)^2)$.
  
- Kemudian, ekspresi tersebut dijumlahkan menjadi tiga bagian terpisah menggunakan sifat 3: $\Sigma_{i=1}^{n} (ax_i)^2 + \Sigma_{i=1}^{n} ab(x_i y_i) + \Sigma_{i=1}^{n} (by_i)^2$.
  
- Menggunakan sifat 2, kita dapat memfaktorkan konstanta $(a^2), (ab)$, dan $(b^2)$ dari setiap jumlah.
   
#### $\Sigma_{i=1}^{n} (x_i + k)^2$
![[Screenshot 2024-08-17 at 18.43.27.png]]
- Sama seperti contoh sebelumnya, ekspresi ini dikembangkan menjadi bentuk $\Sigma_{i=1}^{n} (x_i^2 + 2kx_i + k^2)$.
  
- Lalu, ekspresi dijumlahkan menjadi tiga bagian menggunakan sifat 3: $\Sigma_{i=1}^{n} x_i^2 + \Sigma_{i=1}^{n} kx_i + \Sigma_{i=1}^{n} k^2$.
  
- Konstanta $(k)$ dan $(k^2)$ dapat difaktorkan keluar, dan kemudian hasilnya disederhanakan menggunakan sifat 2 dan 1.

#### $\Sigma_{i=1}^{n} (x_i + 2)(x_i - 2)$
![[Screenshot 2024-08-17 at 18.43.38.png]]
- Dikembangkan menjadi $\Sigma_{i=1}^{n} (x_i^2 - 4)$.
  
- Lalu, hasil ini dapat dipisahkan menjadi dua bagian: $\Sigma_{i=1}^{n} x_i^2 - \Sigma_{i=1}^{n} 4$.
  
- Menggunakan sifat 3 dan sifat 1, hasil akhir adalah $\Sigma_{i=1}^{n} x_i^2 - 4n$.


Pada dasarnya, notasi sigma digunakan untuk merangkum proses penjumlahan dari suatu ekspresi dengan berbagai sifat yang mempermudah penghitungan dalam kasus-kasus tertentu. Sifat-sifat ini dapat digunakan untuk menyederhanakan atau menguraikan ekspresi kompleks dalam bentuk yang lebih mudah dikelola.

### Penjumlahan Rangkap Sigma:

Dalam pengembangan selanjutnya, data yang kita jumlahkan tidak hanya dari satu pengukuran atau variabel, namun bisa berasal dari satu variabel. Sebagai contoh, terdapat dua pengukuran yaitu pengukuran tinggi badan mahasiswa pria dan tinggi badan bahasiswa wanita. Oleh karena itu penggunaan notasi penjumlahan dapat diperluas menjadi penjumlahan rangkap

Gambar yang Anda unggah menjelaskan tentang bagaimana melakukan penjumlahan elemen-elemen dalam sebuah matriks dengan menggunakan notasi sigma (\(\Sigma\)). Berikut penjelasannya:

### Penjelasan:

1. **Matriks dengan \(m\) baris dan \(n\) kolom**:
   - Matriks ini terdiri dari \($mn$\) elemen \($x_{ij}$\), di mana \($i$\) menunjukkan indeks baris (dari 1 hingga \($m$\)) dan \($j$\) menunjukkan indeks kolom (dari 1 hingga \($n$\)).
   - Bentuk umum matriks ini adalah:

     $\begin{matrix}x_{11} & x_{12} & \dots & x_{1n} \\x_{21} & x_{22} & \dots & x_{2n} \\\vdots & \vdots & \ddots & \vdots \\x_{m1} & x_{m2} & \dots & x_{mn} \\\end{matrix}$

2. **Penjumlahan Semua Elemen (Metode 1 - Kolom)**
   - Untuk menjumlahkan semua elemen dalam matriks, Anda dapat melakukannya dengan menjumlahkan elemen-elemen pada setiap kolom terlebih dahulu, kemudian menjumlahkan hasilnya.
   - Rumusnya:

     $\sum_{i=1}^{m} x_{i1} + \sum_{i=1}^{m} x_{i2} + \dots + \sum_{i=1}^{m} x_{in} = \sum_{j=1}^{n} \left( \sum_{i=1}^{m} x_{ij} \right)$

3. **Penjumlahan Semua Elemen (Metode 2 - Baris)**
   - Alternatifnya, Anda bisa menjumlahkan elemen-elemen pada setiap baris terlebih dahulu, lalu menjumlahkan hasilnya.
   - Rumusnya:

     $\sum_{j=1}^{n} x_{1j} + \sum_{j=1}^{n} x_{2j} + \dots + \sum_{j=1}^{n} x_{mj} = \sum_{i=1}^{m} \left( \sum_{j=1}^{n} x_{ij} \right)$

4. **Kesimpulan**:
   - Kedua metode ini pada dasarnya menghasilkan hasil yang sama, karena urutan penjumlahan tidak mempengaruhi hasil akhir. Oleh karena itu, rumusnya dapat disederhanakan menjadi:

     $\sum_{j=1}^{n} \sum_{i=1}^{m} x_{ij} = \sum_{i=1}^{m} \sum_{j=1}^{n} x_{ij} = \sum_{i=1}^{m} \sum_{j=1}^{n} x_{ij}$


Notasi sigma ganda $(\sum_{j=1}^{n} \sum_{i=1}^{m} x_{ij})$ digunakan untuk merangkum proses penjumlahan elemen-elemen dalam matriks, baik dilakukan berdasarkan kolom maupun baris. Urutan penjumlahan tidak berpengaruh pada hasil akhir, sehingga kedua metode ini setara.


## [[07. Penggunaan Dasar Notasi (𝚺)]]

### Nilai Rata rata data($\bar{x}$)

Dalam dunia statistika, banyak dijumpai beberapa ukuran statistik, misalnya nilai rata rata data
($\bar{x}$) dan ragam ($s^2$) atau variasi. Nilai rata-rata dirumuskan sebagai berikut :

> $\bar{x} = \frac{x_1 + x_2 + \cdots + x_n}{n}$

Gambar tersebut menunjukkan rumus rata-rata (mean) dalam statistika. Penjelasannya adalah sebagai berikut:

- $\bar{x}$ adalah simbol untuk rata-rata dari sekumpulan data.
- $x_1, x_2, \dots, x_n$ adalah nilai-nilai data dalam sekumpulan data.
- $n$ adalah jumlah data dalam sekumpulan data.

>Rumusnya adalah:
>$\bar{x} = \frac{x_1 + x_2 + \cdots + x_n}{n}$

>atau dalam bentuk lain:
$\bar{x} = \frac{\sum_{i=1}^{n} x_i}{n}$

Artinya, rata-rata ($\bar{x}$) dihitung dengan menjumlahkan semua nilai ($x_i$) dari ($i = 1$) sampai ($i = n$), lalu membaginya dengan jumlah data ($n$).

Gambar tersebut menjelaskan proses penurunan rumus varians dan kovarians dalam statistika.

### Penurunan Rumus Varians/Ragam ($s^2$)

1. **Rumus Varians / Ragam:**
   $s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}$
   Varians (\($s^2$\)) merupakan ukuran sebaran atau ragam dari nilai-nilai $\(x_1, x_2, \dots, x_n\)$.

2. **Penguraian Bagian Pembilang:**
   ![[Screenshot 2024-08-17 at 20.15.26.png]]
   - Mulai dari rumus dasar varians, dilakukan substitusi dan penguraian kuadrat perbedaan dari rata-rata $(\(\bar{x}\))$.
   - Langkah-langkah yang ditunjukkan melibatkan ekspansi aljabar dan manipulasi penjumlahan, termasuk penggunaan sifat distribusi dari jumlah.

3. **Hasil Akhir:**
   ![[Screenshot 2024-08-17 at 20.16.51.png]]
   - Rumus varians dapat dinyatakan dalam bentuk lain yang lebih ringkas, dengan memisahkan kontribusi dari setiap nilai $\(x_i\)$ terhadap varians secara keseluruhan.

### Penurunan Rumus Kovarians ($s_{xy}$)

1. **Rumus Kovarians:**
   $s_{xy} = \frac{\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})}{n}$
   Kovarians $(s_{xy})$ mengukur bagaimana dua variabel, \($x$\) dan \($y$\), berhubungan satu sama lain.
![[Screenshot 2024-08-17 at 20.25.42.png]]
2. **Penguraian Rumus:**
   ![[Screenshot 2024-08-17 at 20.28.50.png]]
   - Sama seperti penurunan varians, rumus kovarians ini juga diuraikan dengan memanipulasi penjumlahan dan substitusi rata-rata.
   - Setiap komponen kovarians dijelaskan dengan lebih mendetail, menunjukkan interaksi antara \($x$\) dan \($y$\) serta bagaimana kontribusi masing-masing nilai terhadap hasil akhir.

3. **Hasil Akhir:**
   - Kovarians juga dapat dinyatakan dalam bentuk yang menunjukkan hubungan langsung antara dua variabel dalam hal penjumlahan dan rata-rata.

Secara umum, kedua bagian ini menunjukkan bagaimana konsep dasar varians dan kovarians dapat dipecah menjadi bentuk-bentuk yang lebih mudah untuk dipahami dan dihitung. Manipulasi aljabar yang digunakan sangat penting dalam mengungkapkan berbagai aspek dari distribusi data.


### Contoh Lainnya

> ![[Screenshot 2024-08-17 at 20.30.22.png]]
> ![[Screenshot 2024-08-17 at 20.30.35.png]]