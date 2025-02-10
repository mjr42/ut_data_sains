---
tags:
  - sains_data
  - materi_6_PSD
---
## [[01. Statistik Deskriptif]]

Yaitu metode yang digunakan untuk memberikan informasi mengenai kumpulan data. Dengan metode ini, dataset dengan jumlah yang sangat besar dapat disajikan dalam format yang lebih ringkas dan memberikan inti mengenai dataset yang akan diteliti.

Dengan menggunakan statistika deskriptif, data scientist dapat mengetahui ukuran pemusatan data, ukuran penyebaran data, dan bentuk distribusi data.

| Informasi Dataset      | Teknik yang Digunakan                   |
| ---------------------- | --------------------------------------- |
| Ukuran pemusatan Data  | Mean, Median, Mode                      |
| Ukuran Penyebaran Data | Range, Wariance, dan Standard Deviation |
| Bentuk Distribusi Data | Symetry, Skewness, dan Kurtosis         |

Berdasarkan julah atribut yang akan dianalisis, Statistik deskriptif dapat dibagi menjadi dua kelompok yaitu:

#### 1. Eksplorasi Univariat

Eksplorasi Univariat dilakukan pada satu variabel (fitur) atau per variabel. Selain itu eksplorasi univariat hanya memiliki variabel dependen

#### 2. Eksplorasi Multivariat

Eksplorasi Multivariat diterapkan kepada lebih dari dua variabel untuk menganalisa hubungan antarvariabel. Eksplorasi multivariat melibatkan dua atau lebih variabel dependen.


## [[02. Iris Dataset]]

Iris dataset adalah dataset yang paling banyak digunakan dalam bidang ilmu data science. Iris sendiri merupakan nama dari salah satu jenis bunga yang banyak dijumpai di berbagai belahan dunia

![[Screenshot 2024-10-05 at 00.55.42.png]]

Dataset iris terdiri dari 150 sampekl dan dibagi menjadi tiga kelompok berdasarkan spesiesnya. Masing-masing spesies (Iris setosa, Iris virginica, dan Iris versicolor) memiliki 50 data yang terdiri atas lima atribut, yaitu:

1. Nama Spesies
2. Panjang sepal
3. Lebar sepal
4. Panjang kelopak
5. Lebar kelopak

Kolom spesies dijadikan sebagai variabel target yang akan memuat kelas untuk kasus klasifikasi, sedangkan empat kolom lainnya disebut sebagai fitur yang nantinya digunakan untuk menentukan kelas.

Dataset iri adalah data kontinu yang diukura dalam satuan sentimeter. Contohnya : 
	Setosa adalah spesies yang dapat dibedakan dengan mudah dari dua spesies lainnya hanya dengan menggunakan aturan sederhana seperti panjang kelopak yang bernilai kurang dari 2,5 cm. Sedangkan, untuk me-nentukan spesies atau kelas virginica dan versicolor membutuhkan aturan yang lebih kompleks dengan melibatkan banyak atribut.

Iris dataset dapat diakses pada halaman website berikut ini: https://www.kaggle.com/arshid/iris-flower-dataset/code.

![[Screenshot 2024-10-05 at 00.59.06.png]]



## [[03. Eksplorasi Univariat]]


#### 1. Tendensi Sentral

Tujuan dari mengetahui lokasi sentral dari suatu atribut adalah untuk menghitung dataset menggunakan satu nilai pusat atau nilai yang umum. Untuk mengetahui tendensi sentral pada dataset, kita dapat menggunakan nilai mean, median dan modus (mode)

###### a. Mean
Adalah nilai rata-rata dari suatu himpunan data.

###### b. Median
Adalah nilai rata-rata dari suatu himpunan data. menyatakan nilai titik sentral dalam distri-busi data. Untuk mendapatkan nilai tengah, data harus diurutkan dari nilai terkecil ke terbesar. Jika terdapat dua data pada posisi tengah, maka nilai median didapatkan dari nilai rata-rata kedua data tersebut.

###### c. Modus (Mode)
Adalah nilai yang paling sering muncul dalam suatu himpunan

Nilai mean, median, dan mode mungkin saja berbeda di mana hal ini menunjukkan bentuk distribusi data.

![[Screenshot 2024-10-05 at 01.03.48.png]]

#### 2. Ukuran Penyebaran Data

Terdapat dua metrik yang umum digunakan dalam mengukur penyebaran data, yaitu range dan deviation.

##### a. Range
Range atau rentang digunakan untuk menghitung selish dari nilai maksimum dan nilai minimum suatu atribut. Contohnya seperti rentang suhu di daerah gurun yang berkisar 80°F dan di daerah tropis yang memiliki kisaran nilai suhu sebesar 20°F.

##### b. Deviation
Deviation dibagi menjadi nilai varians dan nilai standar deviasi (simpangan baku) dengan tujuan mengukur penyebaran data. Nilai deviasi diukur berdasarkan selish antara nilai yang diberikan (x;) dan nilai mean dari sampel (u).

Untuk dataset sebanyak N data, nilai varians (s) dapat ditentukan dengan rumus berikut:

![[Screenshot 2024-10-05 at 01.05.31.png]]


Nilai standar deviasi (s) didapatkan dari perhitungan akar kuadrat dari
nilai varian ($s^2$):

![[Screenshot 2024-10-05 at 01.06.11.png]]

> Standar deviasi yang bernilai tinggi mengindikasikan titik data yang tersebar luas di sekitar titik pusat (central point).

> nilai standar deviasi yang keil mengindikasikan titik data yang lebih dekat kepada titik pusat (central point).

![[Screenshot 2024-10-05 at 01.06.56.png]]



## [[04. Eksplorasi Multivariat]]

Eksplorasi multivariat adalah analisis yang dilakukan pada lebih dari satu atribut dalam dataset. Teknik ini sangat penting dalam bidang ilmu data science untuk memahami hubungan antaratribut. 

Pada eksplorasi multivariat dibutuhkan analisis mengenai ukuran tendensi sentral dan nilai varians. Kemudian, yang paling penting dari eksplorasi multivariat adalah perhitungan nilai korelasi. Korelasi adalah teknik statistika yang digunakan untuk memahami hubungan antara dua atribut. 

>Nilai korelasi menunjukkan besarnya ketergantungan satu atribut dengan atribut lain.

Korelasi antardua atribut diukur menggunakan Pearson Correlation Coefficient (r). Koefisien korelasi bernilai -1 ≤ r ≤ 1. 

> - Nilai yang mendekati angka 1 maupun -1 menandakan dua atribut yang sangat berkorelasi. 
> - Nilai korelasi 1 dan - 1 juga menandakan korelasi sempurna.
> - Nilai korelasi 0 menandakan tidak adanya hubungan antardua atribut.



## [[05. Statistik Interferensial]]

Statistik inferensial adalah pendekatan statistik yang berlandaskan kepada data sampel dari suatu populasi, untuk kemudian menarik kesimpulan atas populasi tersebut berdasarkan pada sampel yang telah dikumpulkan, diolah, dan dianalisis. Peneliti kemudian memilih sampel dari beberapa individu untuk melakukan penelitiannya. 

Dalam statistik inferensial kita perlu memahami beberapa konsep dasar seperti teori probabilitas, variabel random diskret dan kontinu, teknik sampling, distribusi probabilitas, dan uji hipotesisnya baik secara parametris maupun non-parametris.

#### 1. Teori Probabilitas

Probabilitas adalah sebuah ukuran angka yang menunjukkan tingkat atau derajat ketidakpastian atas suatu fakta ataupun fenomena tertentu.

##### a. Teori Probabilitas Laplace
menyatakan bahwa semua kejadian memiliki peluang yang sama untuk terjadi sehingga, peluang sesuatu terjadi dapat diprediksi dengan membagi jumlah kemungkinan yang muncul dengan total jumlah kejadian.

##### b. Teori Probabilitas Frequentist
di mana kita dapat mengocok dadu sebanyak mungkin dan akan memperoleh nilai ganjil dibandingkan dengan jumlah kocokan yang dilakukan. Berapa peluang kemungkinan angka ganjil yang muncul akan sangat tergantung kepada berapa sering dadu dikocok, semakin sering dikocok, maka peluang muncul angka ganjil akan semakin tinggi. Tidak ada batasan dalam jumlah percobaan.

Kesimpulannya, semakin banyak percobaan dilakukan maka semakin banyak pelung terjadinya sesatu.

##### b. Teori Probabilitas Bayesian / Subjective

di mana peneliti menentukan kemungkinan peluang berdasarkan informasi yang tersedia dan keyakinannya secara subjektif. Dengan kata lain peneliti telah memiliki pengetahuan awal atau yang dikenal dengan istilah a priori sehingga jika ada tiga peneliti, maka akan ada tiga kemungkinan peluang yang berbeda berdasarkan sudut pandang mereka masing-masing

#### 2. Sampling

Asumsi yang digunakan pada statistik inferensial adalah terdapat variabel random yang berkaitan dengan populasi yang akan kita teliti. Dari populasi ini kemudian kita menentukan dan mengambil sampel, yaitu sebuah variabel yang terbatas dan dapat mewakili populasi (representative).

Menurut Ramdani 2019 Terdapat banyak metode untuk menentukan sampel (sampling) dari suatu populasi. Misal untuk probability sampling, kita dapat menggunakan metode random, sistematik, klaster, ataupun stratified random. Sementara untuk non-proba-bility sampling kita dapat menggunakan metode purposive, convinient, kuota, ataupun snowball.

Untuk menjamin bahwa data sebuah sampel ini bersifat bebas (independen) di antara sampel yang lain, maka kita harus yakin terdapat sampel lain yang dapat menggantikan dengan sifat yang sama. Artinya, setiap sampel dapat digantikan dan dapat terus ditambah sesuai kebutuhan.

##### a. Penentuan Jumlah Sampel

Terdapat paling tidak tiga metode untuk menentukan jumlah sampel, yaitu (1) penentuan jumlah sampel jika populasi diketahui, (2) penentuan jumlah sampel jika populasi tidak diketahui, dan (3) penentuan jumlah sampel bertingkat.

###### 1) Penentuan Jumlah Sampel jika Populasi Diketahui

Yamane (1967) memberikan formula sederhana untuk menghitung jumlah sampel (Persamaan 1)

![[Screenshot 2024-10-05 at 01.18.32.png]]

Di mana,

n : jumlah sampel
N : jumlah populasi
e : tingkat presisi yang ditetapkan peneliti

Misal, diketahui jumlah populasi pengguna aplikasi ABC adalah 2000 dan tingkat presisi yang ditetapkan peneliti adalah 0.05 (p-value), dengan kata lain memiliki tingkat kepercayaan 95%. Maka jumlah sampel yang harus dikumpulkan adalah

###### 2) Penentuan Jumlah Sampel jika Populasi Tidak Diketahui

Selanjutnya, Cochran (1963) memberikan formula untuk menghitung jumlah sampel jika populasi tidak diketahui (Persamaan 2)

![[Screenshot 2024-10-05 at 01.19.28.png]]

Di mana,

$n_0$ : jumlah sampel

$Z^2$ : adalah absis kurva normal yang memotong luas di ekor (wilayah penolakan), di mana 1-asama dengan nilai tingkat kepercayaan yang diharapkan, misal 95%. Nilai Z dapat diperoleh dari tabel statistik

e : tingkat presisi yang ditetapkan peneliti

p : estimasi proporsi dari populasi

q : 1-p

Kita juga dapat mengurangi ukuran sample ini dengan menggunakan (Persamaan 3)

![[Screenshot 2024-10-05 at 01.21.11.png]]

Di mana,

n : jumlah sampel

$n_0$ : jumlah sampel yang diperoleh dari persamaan (2)

N : jumlah populasi

###### 3) Penentuan Jumlah Sampel Bertingkat

Pada penentuan jumlah sampel bertingkat ini, Sugiyono (2002) meng-ajukan (Persamaan 4) untuk menentukan berapa jumlah sampel pada setiap tingkatan.

![[Screenshot 2024-10-05 at 01.22.24.png]]

Di mana,

$n_i$ : jumlah sampel tingkat ke-i

$N_i$ : jumlah populasi tingkat ke-i

N : jumlah total populasi seluruhnya

n : jumlah sampel yang diperoleh dengan (Persamaan 1)



## [[06. Distribusi Probabilitas]]

Distribusi probabilitas terbagi atas dua bentuk, yaitu:

###### 1. Distribusi probabilitas paramateris
Distribusi parametris berasumsi bahwa data terdistribusi dengan normal. Distribusi probabilitas ini merupakan cara yang umum digunakan untuk menemukan pola yang terkandung di dalam suatu data. Parametris artinya melihat pola yang sepenuhnya ditentukan oleh parameter yang terkandung,

###### 2. Distribusi probabilitas non-paramateris
Distribusi non-parametris merupakan distribusi data yang tidak normal.
Non-parametris artinya melihat pola yang tidak sepenuhnya ditentukan oleh parameter yang terkandung, karena mungkin ada parameter lain yang berpengaruh namun tidak diteliti.



## [[07. Uji Hipotesis]]

Hipotesis adalah kesimpulan, teori, preposisi sementara yang dianggap benar, dan kebenaran tersebut masih harus dibuktikan. Hipotesis biasanya dibangun pada tahap awal penelitian kuantitatif yang berusaha membuk-tikan (konfirmasi) pernyataan dari sampel data yang telah dikumpulkan.

Cara untuk melakukan uji hipotesis adalah dengan membuat formulasi kalimat hipotesis, yaitu hipotesis null ($H_0$) dan hipotesis alternatif ($H_1$).

#### a. Hipotesis Null ($H_0$)

Hipotesis null adalah sebuah kalimat pernyataan negatif yang dianggap benar, kecuali terbukti sebaliknya setelah diuji. 
	$H_0$ berarti pernyataan bahwa orang tersebut tidak melakukan kejahatan, kecuali terbukti sebaliknya,
	Memberikan hukuman kepada orang yang tidak bersalah adalah kesalahan $H_0$

#### b. Hipotesis Alternatif ($H_1$)

Hipotesis alternatif adalah kalimat pernyataan positif yang dianggap salah, kecuali terbukti sebaliknya setelah diuji.
	$H_1$ berarti pernyataan bahwa orang tersebut telah melakukan kejahatan, kecuali terbukti sebaliknya.
	Membebaskan orang yang bersalah dari hukuman adalah kesalahan $H_1$.

![[Screenshot 2024-10-05 at 01.34.26.png]]

Penelitibiasanyamenggunakan ukuran tingkat signifikansi(significance level) dalam meminimalkan kesalahan. Nilai yang sering digunakan dalam penelitian ilmiah adalah antara 0.01 hingga 0.05. Nilai tersebut akan ditentukan tergantung pada tingkat kesalahan yang diharapkan oleh peneliti. Tingkat signifikansi 0.05 artinya dari 100 populasi, akan terdapat 5 kesalahan, dan sisanya adalah benar.

Sementara untuk menentukan nilai minimum dari tingkat signifikansi dimana $H_0$, ditolak adalah dengan menggunakan p-value. Jika nilai tingkat signifikansi yang lebih besar dari p-value, maka $H_0$, ditolak. Sebaliknya jika nilai tingkat signifikansi yang lebih kecil dari p-value, maka H, diterima Karena terkadang nilai tingkat signifikansi tidak selalu bulat 0.05 atau 0.01 bisa jadi memiliki nilai 0.07, pada kasus seperti inilah kemudian p-value digunakan.


## [[08. Tipe Uji Hipotesis]]

Terdapat dua tipe uji hipotesis, yaitu hipotesis langsung (direksional) dan hipotesis tidak langsung (non-direksional).

#### a. Hipotesis Langsung (Direksional)
Hipotesis langsung atau direk-sional adalah hipotesis yang telah miliki arah yang jelas. Pada uji jenis ini peneliti dapat melakukan uji pihak kanan dan uji pihak kiri.

#### b. Hipotesis Tidak Langsung (Non-Direksional)
hipotesis tidak langsung atau non-direksional, hipotesis tidak me-miliki arah tertentu (two tailed test). Bentuk kalimat pada uji hipotesis jenis ini biasanya menggunakan kata "sama dengan" pada kalimat $H_0$ dan menggunakan kata "tidak sama dengan" pada kalimat $H_1$

Terdapat paling tidak empat jenis kalimat hipotesis, yaitu:
1. deskriptif, 
2. asosiatif, 
3. komparatit, dan 
4. gabungan.

![[Screenshot 2024-10-05 at 01.39.12.png]]



## [[09. Uji Parametris]]

Uji parametris adalah uji yang dilakukan berdasarkan data sampel yang menggunakan pendekatan statistik inferensial atau dikenal juga dengan istilah statistik induktif.

Asumsi dasar pada uji parametris adalah data terdistribusi normal, sampel dipilih secara random, memiliki hubungan linear, dan data bersifat homogen.

Dalam uji parametris, diharuskan untuk melakukan uji homogenitas, uji normalitas data terlebih dahulu sebelum mengolah data lebih lanjut.



## [[10. Uji Non-Parametris]]

Uni non-parametris adalah kebalikan dari uji parametris. Pada uji jenis ini tidak memiliki asumsi dasar seperti pada uji parametris. Oleh karena itu uji ini dikenal juga dengan istilah "uji bebas distribusi".

Pada setiap uji hipotesis, peneliti dianjurkan untuk menyatakan secara tegas apakah data berasal dari populasi atau sampel. Jika berasal dari populasi, maka yang digunakan adalah rata-rata populasi ($\mu$), standart deviasi populasi (𝛔), dan varian dari populasi ($𝛔^2$). Namun bila berasal dari sampel, maka menggunakan rata-rata sampel (x), standar deviasi sampel (s), dam varian dari sampel ($s^2$)

![[Screenshot 2024-10-05 at 01.45.20.png]]

Dalam menentukan uji parametris atau non-parametris peneliti perlu memperhatikan sebagai panduan beberapa hal berikut:

1. Jenis/skala data: untuk skala data nominal dan ordinal biasanya meng-gunakan metode uji non-parametris, sementara skala data interval dan rasio biasanya menggunakan metode uji parametris.
2. Bentuk hipotesis: bentuk kalimat hipotesis deskriptif dan asosiatif biasanya lebih sesuai menggunakan metode uji non-parametris, se-mentara bentuk kalimat hipotesis komparatif biasanya lebih sesuai menggunakan metode uji parametris.
3. Data diskret atau kontinu: data diskret lebih tepat digunakan untuk metode uji non-parametris, sementara data kontinyu lebih tepat digunakan untuk metode uji parametris.

Ketiga hal tersebut di atas akan sangat membantu peneliti dalam mela-kukan eksplorasi dan analisis data.
