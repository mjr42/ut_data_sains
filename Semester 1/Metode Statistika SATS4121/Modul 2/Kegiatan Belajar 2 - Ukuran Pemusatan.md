---
tags:
  - metode_statistika
---
Ukuran Pemusatan atau Central Tendency adalah bagian dari Statistik Deskriptif.
Nilai Sentral atau nilai tengah sekumpulan data adalah nilai yang dipandang dapat menggambarkan ukuran pemusatan data yang berkaitan dengan letak (Lokasi)

Statistik yang tergolong dalam ukuran pemusatan adalah Rata-rata, Media, Modus, Kuartil, dan Persentil. Berikut adalah masing-masing ukuran pemusatan untuk bentuk data tunggal, data berbobot, dan data berkelompok.

---

## A. [[02. Rata-Rata]]


#### 1. Data Tunggal

Didefinisikan segabai jumlah semua data yang dibagi dengan banyaknya data. Apabila terdapat n data yang dinyatakan dengan $X_1, X_2, X_3, ..., X_n$ maka rata ratanya adalah:

$\overline{X} = \frac{\sum_{i=1}^{n} X_i}{n}$

Di mana:

- $\overline{X}$ adalah rata-rata dari data.
- $\sum_{i=1}^{n} X_i$ adalah jumlah keseluruhan dari data $X_i$ dari $i = 1$ sampai $i = n$.
- n adalah jumlah total data.


#### 2. Data Berbobot

Data berbobot adalah data yang nilai-nilainnya disajikan bersama dengan frekuensi kemunculannya dalam kelas kelas. 

Rumus rata rata adalah sebagai berikut:

$\bar{X} = \frac{\sum_{i=1}^{k} m_i f_i}{\sum_{i=1}^{k} f_i}$

Di mana:

•	$k$ = banyaknya kelas
•	$m_i$ = nilai data pada kelas ke-i
•	$f_i$ = frekuensi kelas ke-i

Langkah-langkah untuk menghitung rata-rata curah hujan:

1.	Kalikan masing-masing nilai curah hujan ($m_i$) dengan frekuensinya ($f_i$).
2.	Jumlahkan hasil perkalian tersebut untuk mendapatkan $\sum_{i=1}^{k} m_i f_i$.
3.	Jumlahkan semua frekuensi untuk mendapatkan $\sum_{i=1}^{k} f_i$.
4.	Bagi hasil dari langkah 2 dengan hasil dari langkah 3.


![[Screenshot 2024-08-24 at 11.09.27.png]]

#### 3. Data Berkelompok

Data berkelompok adalah data yang nilai-nilainnya disajikan bersama frekuensinya dalam kelas-kelas interval.

Rumusannya adalah sebagai berikut:

$\bar{X} = \frac{\sum_{j=1}^{k} m_j f_j}{\sum_{j=1}^{k} f_j}$

Di mana:

•	 $k$  adalah jumlah kelas.
•	 $f_i$  adalah frekuensi kelas ke-i.
•	 $m_i$  adalah titik tengah kelas ke-i.


Titik tengah kelas  $m_i$  dihitung dengan rumus:

$m_i = \frac{BA + BB}{2}$

Di mana:

•	 $BA$  adalah batas atas kelas.
•	 $BB$  adalah batas bawah kelas.


Dengan kata lain, untuk menghitung rata-rata data berkelompok, langkah-langkahnya adalah sebagai berikut:
1.	Hitung titik tengah tiap kelas  $m_i$  dengan menjumlahkan batas atas dan batas bawah kelas, kemudian bagi dengan dua.
2.	Kalikan setiap titik tengah  $m_i$  dengan frekuensi  $f_i$  dari kelas tersebut.
3.	Jumlahkan semua hasil perkalian  $m_i f_i$  untuk mendapatkan pembilang.
4.	Jumlahkan semua frekuensi  $f_i$  untuk mendapatkan penyebut.
5.	Bagi pembilang dengan penyebut untuk mendapatkan nilai rata-rata  $\bar{X}$ .


## B. [[03. Median]]

Median adalah suatu nilai yang membagi data yang telah diurutkan menjadi dua bagian yang sama. Frekuensi dat ayang di bawah median sama dengan data diatas median.

#### 1. Data Tunggal
Jika terdapat $n$ data yang dinyatakan dengan $x_1, x_2, x_3, x_n$ maka median adalah nimai $x$ yang sedemikian sehingga $x$ tersebut tepat berada di tengah-tengah barisan data yang telah disusun dari kecil ke besar atau dari besar ke kecil.

###### a. Untuk jumlah data ganjil:
Rumus median yang digunakan adalah  $X_k$  di mana  $k = \frac{n+1}{2}$ . Dalam hal ini, nilai median adalah data yang terletak di posisi ke- k  setelah data diurutkan.

###### b. Untuk jumlah data genap:
Rumus median yang digunakan adalah  $\frac{X_k + X_{k+1}}{2}$  di mana  $k = \frac{n}{2}$ . Dalam hal ini, median adalah rata-rata dari dua data yang berada di posisi tengah.

###### Contoh :
Dari data dengan n=20, setelah data diurutkan didapatkan letak posisi median berada pada data urutan ke 10 dan ke 11 yaitu :

| 2.12 | 2.19 | 2.22 | 2.25 | 2.29 | 2.3 | 2,33 | 2.43 | 2.45 | 2.45 |
| 2.45 | 2.5 | 2.5 | 2.5 | 2.5 | 2.5 | 2.5 | 2.5 | 2.6 | 2.6 | 2.6 |

Nilainya adalah rata-rata dari data ke-10 dan ke-11, yaitu  $\frac{2,45 + 2,45}{2} = 2,45$ .


#### 2. Data Berkelompok

Apabila data dikelompokan dalam interval kelas maka mediannya adalah:

$\text{Median} = I_{\text{med}} + \left( \frac{\frac{n}{2} - \sum_{j} f_j}{f_{\text{med}}} \right) \times i$

$I_{\text{med}}$  adalah batas bawah kelas dari interval yang memuat median.

$i$  adalah lebar interval kelas. $i = \text{Batas atas} - \text{Batas bawah} + 1$

$\sum_j f_j$  adalah jumlah frekuensi dari semua interval kelas sebelum median.

$f_{\text{med}}$  adalah frekuensi kelas interval yang memuat median.

###### Contoh :

Tentukan median dari stok barang pada tabel berikut
![[Screenshot 2024-08-27 at 18.49.20.png]]
## C. [[04. Modus]]

Modus adalah data yang sering muncul (frekuensi terbesar)

#### 1. Data Tunggal

Modus dari $n$ data dengan $X_1, X_2, X_3,... X_n$ adalah nilai $X$ yang sering muncul atau nilai yang memiliki frekuensi terbesar, sehingga cara menentukan modus adalah mencari data yang memiliki frekuensi terbesar.

Hal ini berlaku bagi data tunggal maupun berbobot

###### Contoh :

![[Screenshot 2024-08-27 at 19.07.31.png]]

Berdasarkan tabel tersebut, Modus curah hujan tahunan adalah 82mm, 95mm, dan 121mm


#### 2. Data Berkelompok

Modus dari $n$ data yang telah dikelompokan dalam interval kelas dirumuskan dalam persamaan sebagai berikut :


$\text{Modus} = I_{mo} + i \cdot \frac{d_1}{d_1 + d_2}$


Keterangan:

$I_{mo}$ : Batas bawah interval kelas yang memuat modus. Ini adalah nilai paling kecil dari kelas interval yang memiliki frekuensi tertinggi (modus).

$d_1$ : Selisih frekuensi antara kelas yang memuat modus dengan kelas sebelumnya. Ini dihitung sebagai  $f_{mo} - f_{sebelum}$ , di mana  $f_{mo}$  adalah frekuensi dari kelas modus dan  $f_{sebelum}$  adalah frekuensi dari kelas sebelum kelas modus.

$d_2$: Selisih frekuensi antara kelas yang memuat modus dengan kelas sesudahnya. Ini dihitung sebagai  $f_{mo} - f_{sesudah}$ , di mana  $f_{sesudah}$  adalah frekuensi dari kelas setelah kelas modus.

$i$ : Lebar interval kelas, yaitu jarak atau rentang antara batas atas dan batas bawah dari kelas tersebut.  $i = \text{Batas atas} - \text{Batas bawah} + 1$


###### Contoh :
![[Screenshot 2024-08-27 at 19.19.12.png]]


## D. [[05. Kuartil]]

Kuartil adalah titik atau nilai yang membagi seluruh distribusi data menjadi empat bagian yang sama setelah data diurutkan sehingga didapatkan tiga buah kuartil yaitu :

- Kuartil Bawah ($Q_1$) 
- Kuartil Tengah ($Q_2$) 
- Kuartil Atas ($Q_3$) 

#### 1. Data Tunggal

Jika terdapat $n$ data  $X_1, X_2, X_3,... X_n$ dan diurutkan dari data terkecil ke besar maka :

- Kuartil bawah yang disebut sebagai kuartil pertama ($Q_1$) adalah nilai X yang sedemikian rupa sehingga 1/4 jumlah data yang berada di bawahnya sedangkan 3/4 sisanya berada di atasnya
  
- Kuartil tengah yang disebut sebagai kuartil kedua ($Q_2$) atau median yaitu nilai X yang sedemikian rupa hingga membagi dua bagian yang jumlah datanya sama banyaknya
  
- Kuartil atas yang disebut sebagai kuartil ketiga ($Q_2$) yaitu nilai X sedemikian rupa hingga 3/4 jumlah data yang berada di bawahnya. sedangkan 1/4 sisanya berada di atasnya.

Ada dua pendekatan yang dapat dilakukan untuk menentukan kuartil yaitu metode belah dua dan metode interpolasi (Mattjik & Sumertajaya, 2013)

##### Pendekatan 1 : Metode Belah Dua

Perinsip adri metode belah dua yaitu tahap pertama pecah gugus data menjadi dua bagian yang sama, selanjutnya setiap bagian pecah kembali dibagi menjadi dua sehingga akan terbentuk empat bagian yang sama. Secara teknis, langkah-langkah perhitungannya adalah sebagai berikut :

- Urutkan data mulai dari data terkecil sampai data terbesar.
  
- Hitung posisi kuartil kedua ($n_{q2}$). Perlu di catata bahwa kuartil kedua ini sama dengan median.
  
- JIka posisi kuartil kedua bulat, maka kuartil kedua adalah data ke $n_{q2} = \frac{n + 1}{2}$ . sedangkan jika bernilai pecahan maka kuartil kedua adalah rata rata dari data ke $\frac{n}{2}$ dan $\frac{n}{2}+1$
  
- Hitung posisi kuartil perta adan kuartil ketiga dengan menggunakan rumus berikut:
  $n_{q1} = n_{q3} = \frac{Posisi Kuartal Terpangkas + 1}{2} = \frac{n_{q2} + 1}{2}$

- Posisi kuartil kedua terpangkas maksudnya adalah angka bulat dari posisi kuartil kedua. Misalnya dari perhitungan diperoleh $n_{q2} = 6,5$ maka $n_{q2}=6$ . Pecahan 0/5 nya dihilangkan
  
- Penetapan nilai kuartil pertama dan ketiga pada prinsipnya sama dengan penentuan kuartil kedua pada langkah 3. Nilai kuartil pertama dihitung mulai pengamatan terkecil, sedangkan nilai kuartil ketiga dihitung dari pengamatan terbesar


##### Pendekatan 2 : Metode Interpolasi

Pendekatan interpolasi digunakan untuk menentukan nilai kuartil pada software minitab. Formulasi yang digunakan adalah sebagai berikut:

- Urutkan data dari yang terkecil sampai terbesar
  
- Posisi kuartil ke-i adalah:
  $n_{qi} = \frac{i}{4}(n+1)$

- Jika posisi kuartil pecahan maka nilai kuartil dihitung dengan pendekatan interpolasi, formulanya adalah sebagai berikut:
  $X_{q1} = X_{a,i} + h (X_{b,i} - X_{a,i})$ 
  
  $X_{a,i}$ = Data sebelum posisi kuartil ke-i
  $X_{b,i}$ = Data setelah posisi kuartil ke-i
  $h_i$ = Nilai pecahan dari posisi kuartil

Karena ada dua pendekatan dalam menghitung kuartil. Maka ada kemungkinan nilai yang dihasilkan dari kedua mmetode tidaklah sama. Lalu, bagaimana jika nilai kuartil yang dihasilkan berbeda?

Ternyata, hal ini tidak menjadi masalah. pendekatan apapun yang digunakan asalkan nilai kuartil yang dihasilkan dapat membagi data menjadi empat bagian yang sama yaitu masing masing bagian 25%. Todaklah menjadi masalah


###### Contoh
Tentukan Kuartil pertama, kedua dan ketiga dari data berikut:
5, 3, 4, 8, 5, 10, 6, 8

**Pendekatan I: Metode Belah Dua**

1.	**Urutkan Data:**
- Data awal: 5, 3, 4, 8, 5, 10, 6, 8
- Data setelah diurutkan: 3, 4, 5, 5, 6, 8, 8, 10

2.	**Posisi Kuartil:**
- Untuk kuartil kedua ($Q_2$), posisinya adalah $\frac{8+1}{2} = 4.5$.
- Untuk kuartil pertama ($Q_1$), posisinya adalah $\frac{4+1}{2} = 2.5$.
- Untuk kuartil ketiga ($Q_3$), posisinya adalah $\frac{4+1}{2} = 6.5$.

3.	**Nilai Kuartil:**
- Kuartil kedua ($Q_2$) dihitung dengan mengambil rata-rata data pada posisi ke-4 dan ke-5, yaitu:

	$Q_2 = \frac{5 + 6}{2} = 5.5$

- Kuartil pertama ($Q_1$) dihitung dengan mengambil rata-rata data pada posisi ke-2 dan ke-3, yaitu:

	$Q_1 = \frac{4 + 5}{2} = 4.5$

- Kuartil ketiga ($Q_3$) dihitung dengan mengambil rata-rata data pada posisi ke-6 dan ke-7, yaitu:

	$Q_3 = \frac{8 + 8}{2} = 8$


**Pendekatan II: Metode Interpolasi**

1.	**Urutkan Data:**
- Data sudah diurutkan sama seperti pada pendekatan pertama: 3, 4, 5, 5, 6, 8, 8, 10.
  
2.	**Posisi Kuartil:**
- Untuk kuartil pertama ($Q_1$), posisinya adalah $n_{Q1} = \frac{1}{4}(8+1) = 2.25$.
- Untuk kuartil kedua ($Q_2$), posisinya adalah $n_{Q2} = \frac{2}{4}(8+1) = 4.50$.
- Untuk kuartil ketiga ($Q_3$), posisinya adalah $n_{Q3} = \frac{3}{4}(8+1) = 6.75.$
  
3.	**Nilai Kuartil:**

- **Kuartil pertama ($Q_1$):**
- Nilai interpolasi: $Q_1 = 4 + 0.25 \times (5 - 4) = 4.25.$
  
- **Kuartil kedua ($Q_2$):**
- Nilai interpolasi: $Q_2 = 5 + 0.50 \times (6 - 5) = 5.50.$
  
- **Kuartil ketiga ($Q_3$):**
- Nilai interpolasi: $Q_3 = 8 + 0.75 \times (8 - 8) = 8.$


Kesimpulan:

**Pendekatan I (Metode Belah Dua):**
	•	$Q_1 = 4.5$
	•	$Q_2 = 5.5$
	•	$Q_3 = 8$

**Pendekatan II (Metode Interpolasi):**
	•	$Q_1 = 4.25$
	•	$Q_2 = 5.50$
	•	$Q_3 = 8$

Pada pendekatan kedua, interpolasi digunakan untuk menemukan posisi kuartil yang tidak bulat, sehingga hasilnya bisa berbeda dengan pendekatan pertama.

Catatan : Sama halnya dengan median. Jika data yang disajikan dalam bentuk data berbobot. Penggunaan kuartil masih sama saja dengan cara menentukan kuartil pada data tunggal


#### 2. Data Berkelompok

Bila data berkelompok dalam interval kelas maka kuartil-kuartil dapat dirumuskan pada persamaan sebagai berikut :


$Q_1 = I_{Q1} + i \left( \frac{\frac{n}{4} - \sum f_j}{f_{Q1}} \right)$

$Q_3 = I_{Q3} + i \left( \frac{\frac{3n}{4} - \sum f_j}{f_{Q3}} \right)$

###### Kuartil Pertama (Q_1):

$Q_1 = I_{Q1} + i \left( \frac{\frac{n}{4} - \sum f_j}{f_{Q1}} \right)$

- $I_{Q1}$ = tepi bawah kelas kuartil pertama
- $i$ = panjang interval kelas
- $n$ = jumlah data
- $\sum f_j$ = jumlah frekuensi sebelum kelas kuartil pertama
- $f_{Q1}$ = frekuensi kelas kuartil pertama


###### Kuartil Ketiga (Q_3):

$Q_3 = I_{Q3} + i \left( \frac{\frac{3n}{4} - \sum f_j}{f_{Q3}} \right)$

- $I_{Q3}$ = tepi bawah kelas kuartil ketiga
- $i$ = panjang interval kelas
- $n$ = jumlah data
- $\sum f_j$ = jumlah frekuensi sebelum kelas kuartil ketiga
- $f_{Q3}$ = frekuensi kelas kuartil ketiga

###### Langkah-langkah Perhitungan Kuartil dengan Metode Interpolasi:

1.	Tentukan Tepi Bawah Kelas Kuartil:
	•	Kelas kuartil adalah kelas di mana kuartil terletak.
	•	Tepi bawah kelas adalah batas bawah dari kelas kuartil tersebut.

2.	Hitung Panjang Interval Kelas ($i$):
	•	Ini adalah jarak antara batas bawah dan batas atas kelas.

3.	Hitung Jumlah Data ($n$):
	•	n adalah jumlah seluruh data atau frekuensi total dalam distribusi.

4.	Identifikasi Frekuensi dan Jumlah Frekuensi:
	•	$f_{Q1} dan f_{Q3}$ adalah frekuensi kelas kuartil pertama dan ketiga.
	•	$\sum f_j$ adalah jumlah frekuensi sebelum kelas kuartil.

5.	Masukkan Nilai ke dalam Rumus:
	•	Masukkan nilai-nilai yang telah Anda identifikasi ke dalam rumus kuartil pertama ($Q_1$) atau kuartil ketiga ($Q_3$).

6.	Hitung Nilai Kuartil:
	•	Setelah semua nilai dimasukkan, hitung untuk mendapatkan hasil kuartil.


###### Contoh

![[Screenshot 2024-08-28 at 20.25.55.png]]
![[Screenshot 2024-08-28 at 20.26.16.png]]

## E. [[06. Persentil]]

Nilai persentil ke-100$p$ adalah suatu nilai yang sedemikian rupa sehingga paling sedikit 100$p$ persen dari semua data berada di bawahnya dan paling sedikit 100 (1-$p$)% lebih dari nilai tersebut. Prinsipnya sama saja dengan median dan kuartil. Apabila datang dikelompokan dalam interval kelas maka rumus persentil ke-$p$ dapat ditulis sebagai berikut :


###### $p = I_p + i \left(\frac{pn - \sum_j f_j}{f_p}\right)$

- $p$ : Persentil yang ingin dihitung. Misalnya, untuk persentil ke-25,  p = 25\% .
  
- $I_p$ : Batas bawah dari interval kelas di mana persentil ke- p  terletak.
  
- $i$ : Lebar dari interval kelas tersebut.
  
- $n$ : Jumlah total observasi dalam data.
  
- $\sum_j f_j$ : Jumlah frekuensi dari semua kelas sebelum kelas persentil ke- p . Ini adalah akumulasi frekuensi dari semua kelas sebelum kelas persentil yang dihitung.
  
- $f_p$ : Frekuensi dari kelas persentil ke- p . Ini adalah jumlah observasi dalam kelas di mana persentil tersebut terletak.

###### Cara Kerja Rumus:

1.	Menentukan  p : Tentukan persentil yang ingin dihitung. Misalnya, jika Anda menghitung persentil ke-25, maka  p = 0.25 .

2.	Menemukan Kelas Persentil: Temukan kelas interval yang mengandung persentil ke- p . Ini dilakukan dengan membandingkan nilai kumulatif frekuensi.

3.	Menghitung Batas Bawah Kelas  I_p : Ini adalah nilai awal kelas di mana persentil tersebut terletak.

4.	Menggunakan Rumus: Setelah semua nilai di atas diidentifikasi, substitusikan ke dalam rumus. Rumus ini membantu menghitung nilai persentil dengan menambahkan batas bawah kelas ( I_p ) dengan proporsi interval yang dihitung menggunakan sisa persentase dalam kelas tersebut.

5.	Interpretasi: Hasil akhirnya adalah nilai yang memisahkan  p % data dari data lain.

###### Contoh :
![[Screenshot 2024-08-31 at 14.33.49.png]]

