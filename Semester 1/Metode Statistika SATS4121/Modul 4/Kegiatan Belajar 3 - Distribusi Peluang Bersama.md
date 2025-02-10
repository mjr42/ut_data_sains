---
tags:
  - metode_statistika
  - materi_4_MS
---
# Kegiatan Belajar 3 - Distribusi Peluang Bersama

Misalkan ada suatu variabel acak X dan variabel acak Y, maka distribusi peluang gabungan dari dua variabel acak X dan Y dengan kejadian simultan antara keduanya adalah $f(x,y)=P(X=x, Y=y)$ kejadian peluang bersama ini terdiri atas kejadian diskrit dan kontinu


## [[09. Distribusi Peluang Bersama Diskrit]]

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


## [[10. Distribusi Peluang Bersama Kontinu]]


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
