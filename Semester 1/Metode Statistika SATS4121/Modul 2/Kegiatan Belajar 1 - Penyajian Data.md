---
tags:
  - metode_statistika
---


## [[01. Statistika Deskriptif]]

Kegiatan yang akan dibahas adalah tentang penyajian data melalui tabel dan grafik/diagram, membahas tentang ukuran pemusatan data, dan membahas tentang ukuran penyebaran data.

Statistika deskriptif sendiri secara umum meliputi dua bajian yaitu penyajian data dan ukuran-ukuran numerik. Sementara Ukuran numerik sendiri terbagi menjadi dua yaitu ukuran pemusatan dan ukuran penyebaran data.

### Penyajian Data

Penyajian data merupakan bagian penting dalam statistika Deskriptif. Statistika deskriptif sendiri secara umum meliputi dua bajian yaitu penyajian data dan ukuran-ukuran numerik. Sementara Ukuran numerik sendiri terbagi menjadi dua yaitu ukuran pemusatan dan ukuran penyebaran data.

Penyajian data dapat dilakukan dengan banyak cara, namun secara umum terbagi menjadi dua cara yaitu:
###### a. Tabel
Pendekatan tabel dapat dilakukan untuk jenis data kualitatif maupun kuantitatif.
###### b. Grafik/Diagram
Semnetara pendekatan Grafik/Diagram ada sebagian yang sesuai untuk tipe data kuantitatif dan sebagian lainnya hanya sesuai untuk data kualitatif. 


Beberapa Penyajian data yang biaya ditemuan adalah tabel distribusi frekuensi, histogram, diagram batang, diagram lingkaran, dan diagram kotak garis (box plot)

#### 1. Tabel Distribusi Frekuensi

Pada data yeng berjumlah besar, untuk memudahkan analisis deskriptif data tersebut dapat diringkas menjadi tabel distribusi frekuensi.

Bentuk deskripsi ini adalah dengan mengelompokan data tersebut ke dalam beberapa kelas atau kelompok. Selanjutnya menhitung frekuensu (jumlah) data pada masing masing kelas tersebut. 

##### Tabel Distribusi Frekuensi Kualitatif

Pada data kualitatif, distribusi frekuensinya ditunjukan oleh jumlah data pada masing masing kategori yang ada atau dibentuk.

![[Screenshot 2024-08-20 at 17.20.27.png]]

Tabel frekuensi untuk produk tersebut adalah
![[Screenshot 2024-08-20 at 17.20.52.png]]
##### Tabel Distribusi Frekuensi Kuantitatif

Pada data Kuntitatif, pembentukan distribusi frekuensi mengikuti beberapa langkah khusus, Menurut Anderson, Sweeney, dan Williams (2011) langkah tersebut adalah:

###### 1. Menentukan jumlah kelas yang diinginkan
   
   >Jumlah kelas dibentuk dari Range data yang akan digunakan untuk mengelompokan data. 
   
   Secara umum jumlah kelas yang dapat digunakan antara 5 hingga 20 kelas, Untuk jumlah data yang sedikit, cukup menggunakan 5 atau 6 kelas. sedangkan untuk data yang besar juga dibutuhkan keas yang besar pula.
   
   Beberapa referensi juga memberikan pendekatan rumus untuk mendapatkan kelas yang cukup baik, yaitu:
   
   ###### $k = 1 + 3,3log(n)$
   
   - dengan k adalah jumlah keas
   - dan n adalah jumlah sampel

###### 2. Menentukan Lebar Kelas

Lebar Kelas atau selang kelas ditentukan sama untuk semua kelas. 

>Perhitungan lebar kelas adalah dengan menghitung selisih data maksimum dan minimum kemudian membaginya dengan jumlah kelas

$Lebar Kelas = \frac{maksimum-minimum}{jumlah kelas}$
   
###### 3. Menentukan batasan bawah dan batas atas kelas

>Batas bawah didefinisikan sebagai nilai terkecil yang mungkin dari selang kelas yang bersangkutan. 

Begitu juga dengan batas atas. 

>Batas atas adalah nilai maksimum yang mungkin dari selang kelas yang bersangkutan

Batas bawah dan batas atas dipilih sehingga setiap data akan hanya masuk pada satu kelas


##### Case Study

![[Screenshot 2024-08-20 at 17.32.30.png]]

Dari data pendapatan tersebut, akan dibentuk distribusi frekuensi dengan jumlah data 20. berikut adalah langkah langkahnya :

1. **Menentukan Jumlah Kelas:**
   - $k = 1 +3,3 log (x)$ sehingga $k = 1 + 3log(20) = 5.29$ ~ $6$

2. **Menentukan Lebar Kelas:**
   - $Lebar Kelas = \frac{maksimum-minimum}{jumlah kelas}$ sehingga $Lebar Kelas = \frac{2.6-2.12}{6}$ = 0.08 ~ 0.1

3. **Menentukan batas bawah kelas dan batas atas kelas**
   - Dengan nilai minimum 2.12 dibentuk interval kelas pertama 2.10-2.19, dimanan batas bawah adalah 2.10 dan batas atas adalah 2.19.
   - Interval kelas selanjutnya adalah 2.20 - 2.29; 2.30 - 2.39; 2.40 - 2.49; 2.50 - 2.59; dan 2.60 - 2.96

Setelah didapatkan batas atas dan batas bawah masing masing kelas, dihitung frekuensi si masing masing kelas tersebut.

Hasil tabelnya adalah sebagai berikut
> 
![[Screenshot 2024-08-20 at 17.39.14.png]]


#### Frekuensi Kumulatif dan Relatif

Dari uraian uraian tersebut dapat disimpulkan bahwa:
> Frekuensi adalah banyaknya data yang termasuk pada masing masing selang interval atau kelas.

>Tabel distribusi frekuensi adalah tabel yang menunjukan distribusi banyaknya daya yang termasuk pada kelas-kelas tertentu.

Dari nilai frekuensi juga dapat dihitung frekuensi kumulatif dan frekuensi relatif (proporsi).

>Frekuensi Kumulatif adalah menjumlahan frekuensi kelas ke-k dengan frekuensi kelas sebelumnya.

>Frekuensi Relatif adalah frekuensi dibagi dengan banyaknya data. Apabila nilai frekuensi dikalikan 100 maka dinamakan presentase.

![[Screenshot 2024-08-20 at 17.45.58.png]]


---

#### 2. Diagram Batang

Diagram Batang adalah diagram yang menunjukan nilai-nilai frekuensi, frekuensi kumulatif, atau frekuensi relatif. Diagram ini memiliki sumbu horixontal yang menunjukan kelas atau kelompok dan sumbu vertikal yang merupakan batang batang nilai frekuensi, frekuensi kumulatif, atau frekuensi relatif.

Diagram batang ini lebih sering digunakan untuk data kualitatif.

![[Screenshot 2024-08-21 at 09.58.51.png]]


---

#### 3. Histogram

Histogram adalah diagram batang untuk data kuantitatif, Berbeda dengan diagram batang yang sebelumnya. Pada batang diagram ini memiliki lebar yang sama dengan interval kelasnya

![[Screenshot 2024-08-21 at 10.00.43.png]]

Histogram digunakan untuk melihat distribusi dari data, yang terdiri atas beberapa informasi berikut:
- Melihat ukuran penyebaran dan ukuran pemusatan data
- Melihat adanya data pencilan data (outlier)
- Mendeteksi adanya bimodus atau tidak

![[Screenshot 2024-08-21 at 10.02.05.png]]

Histogram tersebut memiliki informasi bahwa kedua data memiliki ukuran pemusatan data yang relatif sama, namun memiliki penyebaran yang berbeda. Data 2 memiliki penyebaran yang belih besar dibandingkan dengan Data 1. Hal ini dibuktikan dengan rentang histogram yang belih besar pada data 2 jika dibandingkan dengan data 1.

![[Screenshot 2024-08-21 at 10.03.35.png]]

Untuk Histogram diatas, menunjukan adanya kesamaan ukuran penyebaran data antara Data 1 dan Darat 3, sedangkan ukuran pemusatannya berbeda

![[Screenshot 2024-08-21 at 10.04.25.png]]
Histogram diatas memunjukan pencilan pada data, yaitu nilai yang posisinya jauh dari kumpulan data yang lainnya.

![[Screenshot 2024-08-21 at 10.05.12.png]]
Untuk histogram berikut memunjukan ada dua buah Modus (bimodus) pada gugus data asalnya. Hal ini mengindikasikan bahwa ada dua kelompok gugus data yang masing masing memiliki sebaran tersendiri.

---


#### 4. Diagram Melingkar

Diagram lingkaran adalah diagram yang menunjukan nilai-nilai presentase frekuensi pada masing masing kelas atau kelompok. Perbedaan presentase frekuensi pada masing masing kelompok ditinjau oleh bentuk luasan lingkarang yeng terbagi-bagi sesuai jumlah kelompok. Diagram ini dapat digunakan untuk data kualitatif dan kuantitatif

![[Screenshot 2024-08-21 at 10.21.36.png]]

Gambar diatas menunjukan diagram lingkarang. terlihat bahwa lingkaran yang ada terbagi-bagi menjadi 3 kelompok. Bagian terluas menunjukan kelompok yang memiliki frekuensi atau presentase frekuensi tertinggi.

![[Screenshot 2024-08-21 at 10.22.51.png]]Gambar diatas menunjukan diagram lingkaran dari data kuantitatif berat badan ayam

---


#### 5. Boxplot

Boxplot atau diagram kotak garis berfungsi untuk eksplorasi atau ringkasan data yang digambarkan secara grafis. Disebut juga diagram kotak (box) dan whisker. Diagram ini dapat menggambarkan pemusatan, penyebaran, dan Outlier. Penyebaran data ditunjukan oleh nilai nilai kuartil.

###### Langkah untuk membuat Boxplot:

1. Menghitung nulai kuartil pertama ($Q_1$), kedua ($Q_2$), dan ketiga ($Q_3$). Lalu gambarlah kotak garis dengan garis horizontal di bagian bawah adalah quartil pertama dan garis horizontal di bagian atas adalah kuartil ketiga. Sementara itu garis yang berada di bagian tengah yang membagi kotak menjadi dua bagian adalah kuartil keduia atau median.
   
2. Menghitung nilai jangkauan kuartil ($Inner Quartil Range = IQR$)
   $IQR = Q_3 - Q_1$

3. Menghituing upper whisker dan lowe whisker
   Upper Whisker = $Q_3 + 1.5 IQR$
   Lower Whisker = $Q_1 - 1.5 IQR$

Nilai ini digunakan untuk menentukan posisi data outlier. Suatu data dikatakan outlier apabila terletak di atas upper whisker atau dibawah lowe whisker. Data yang berada di luar $2(Q_3 + 1.5IQR)$ atau $2(Q_1 - 1.5IQR)$ dinamakan extreme outlier.

Menggambar garis whisker antara garis kuartil ketiga hingga nilai terakhir yang masih masuk wilayah upper whisker. Selanjutnya digambarkan juga garis whisker antara garis kuartil pertama hingga nilai terakhir yang masuk wilayah lower whisker
![[Screenshot 2024-08-21 at 10.28.20.png]]


---
