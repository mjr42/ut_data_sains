---
tags:
  - sains_data
---
## [[01. Proses dalam Sains Data]]

Proses sains data (data Science Process) merupakan nilai inti dari bidang ilmu sains data dimana digunakan untuk menentukan pola hubungan dari suatu kumpulan data. Proses data sains adalah serangkaian kegiatan yang dilakukan secara berulang yang terditri dari:

- Pemahaman Masalah
- Persiapan Sampel Data
- Pembangunan Model
- Pengaplikasian Model kepada dataset untuk melihat hasil keluaran (output)
- Penyebaran dan pemeliharaan model.

>Salah satu kerangka kerja yang digunakan dalam proses data science adalah
>Cross Industry Standard Process for Data Mining (CRISP-DM).

Contoh kerangka kerja lainnya dalam proses data science adalah Sample, Explorer, Modify, Model, dan Asses (SEMMA) yang dibangun oleh institusi SAS, Define, Measure, Analize, Improve, and Contorl (DMAIC) dan The Selection, PreProcessing, Transformation, Data Mining, Intepretation, and Evaluation yang digunakan untuk menemukan pengetahuan baru berbasis data.

Dalam hal ini CRISP-DM adalah kerangka kerja yang paling banyak digunakan untuk mengembangkan solusi berbasis data.

Proses ekstraksi informasi dan pengetahun dari sebuah data dalam proses data sains bersifat iteratif, artinya langkah-langkah yang bersifat non-liner dan membutuhkan banyak perulangan. Terkadang dibutuhkanadanya hubungan dua arah pada setiap tahapan dan kembali ke tahapan pertama untuk mendefinisikan kembali pernyataan masalah

Secara umum Proses pada data sains berbicara mengenai ruang lingkup permasalahan, algoritme sains data, dan alat bantu yang digunkaan untuk memproses data (Data Science tools).

Tujuan utama dalam setiap proses yang melibatkan sains data adalah untuk menjawab sebuah pertanyaan atau permasalahan


Algoritme pembelajaran (Learning Algorithm) yang digunakan untuk menyelesaikan permasalahan dapat berupa pohon keputusan (Decision Tree)  dan Jaringa Saraf tiruan (Artificial Neural Network)

![[Pasted image 20240920100922.png]]
- Decision Tree

![[Pasted image 20240920100938.png]]
- Artificial Neural Network

Kemudian untuk penggunaan perangkat lunak yang membantu mengimplementasikan algoritme sais data dapat menggunakan perangkat lunak seperti R, Python, RapidMiner, Weks, SAS, Oracle Data Miner, dan lainnya

![[Pasted image 20240920101158.png]]
- Kerangka Kerja CRISP-DM

![[Screenshot 2024-09-20 at 10.15.19.png]]



## [[02. Tahapan Dasar]]

Tahapan pertama dalam proses data science adalah pemahaman akan subjek yang akan diteliti. Hal ini meliputi informasi yang sudah diketahui sebelumnya tentang suatu subjek penelitian atau yang sering disebut dengan Prior Knowledge.

Tahapan ini bertujuan untuk membantu dalam menentukan masalah apa yang akan dipecahkan, bagaimana permasalahan dipandang dalam konteks bisnis, dan data apa saja yang dibutuhkan untuk menyelesaikan permasalahan tersebut.

Data science selalu diawali dengan tahapan analisis permasalahan dan tujuan bisnis.  Apabila tahapan dasar tidak dilaksanakan dengan baik, maka akan berdampak pada kesalahan pemilihan dataset dan algoritme sains data yang digunakan

Pemahaman tentang data meliputi; bagaimana data dikumpulkan, disimpan, dimanipulasi, dilaporkan, dan digunakan dalam proses data science.

Ada banyak faktor yang perlu dipertimbangkan dalam pemilihan data seperti kualitas data, kuantitas data, dan letersediaan data. Tujuan dari langkah ini adalah bagaimana cara untuk memndapatkan dataset yang sesuai dengan konteks permasalahan.

Beberapa terminologi yang wajib diketahui dalam proses data science adalah sebagai berikut:

#### Dataset

Dataset adalah kupulan data dengan struktur yang sudah ditentukan, Dataset dapat berbentuk array (suatu tipe data terstruktur yang bisa menyimpan banyak data dalam satu nama) dan basis data lengkap yang disusun atas baris dan kolom.

Struktur ini juga sering disebut sebagai kerangka data atau dikenal dengan istilah data frame. Dalam data science dataset yang paling terkenal adalah Iris Dataset yang dibuat pertama kali oleh Ronal Fisher pada tahun 1936.


#### Data Point

Data point merujuk kepada baris data pada dataset


#### Attribute

Attribut adalah properti dari dataset dalam hal ini merujuk kepada kolom pada dataset. Setiap atribut memiliki tipe data seperti tipe data numerik, kategorikal, tanggal/waktu, teks atau Boolean.


#### Low-Dimensional Dataset

Yaitu istilah yang merujuk kepada jumlah firtur atau atribut yang dimiliki oleh dataset, Sebagai contoh data set yang memiliki empat firtur, di sisi lain, data set yang terdiri dari ratusan hingga ribuan atribut/firtur disebut dengan High-Dimension Dataset.


#### Data Terstruktur (Structured Data)

Yaitu data yang disimpan dalam format yang tetap. Sebagai contoh data yang disimpan dalam bentuk tabel yang erdiri dari kolom dan baris. Data terstruktur disimpan dalam format yang terorganisir seperti excel atau spreadsheet sehingga lebih mudah untuk diproses.


#### Data Tidak Terstruktur (Unstructured Data)

Yaitu kebalikan dari data terstruktur dimana data disimpan dalam format yang tidak terorganisir. Contohnya data dalam format teks, gambar, video, suara, dan data lainnya seperti log pengguna. Pada umumnya data tidak terstruktur membutuhkan penerapan lebih lanjut untuk penyesuaian dengan format penyimpanan data atau basis data


#### Big Data

Yaitu istilah yang merujuk kepada jumlah data yang sangat besar dan kompleks. Untuk dikatakan sebagai big datam data harus memiliki ukuran (volume) yang sangat besar dab dikumpulkan dari berbagai sumber data. kemudian data harus didapatkan dengan waktu yang singkat menggunakan teknologi yang mumpuni. Data si nisi dapat disajikan dalam bentuk data terstruktur dan data tidak terstruktur.  Faktor lain yang menentukan kualitas big data adalah kualitas datanya (veracity) dan variabilitas data. Data science dapat diterapkan pada big dataset maupun yang bukan.



## [[03. Tahapan Persiapan]]

Pada umumnya, algoritme data sains membutuhkan data yang sudah disusun dalam format tertentu seperti tabel yang terdiri atas kolom dan baris. Oleh karena itulah tahapan persiapan data merupakan tahapan yang paling banyak mengonsumsio waktu. Apabila data belum sesuai dengan format yang diinginkan maka dibutuhkan proses konversi dan pengkondisian data ke dalam struktur atau format yang sesuai. 

#### 1. Eksplorasi Data

Tahapan persiapan data biasanya dimulai dengan eksplorasi data untuk mendapatkan pemahaman yang baik tentang kumpulan daya atau dataset. Dalam data sains, eksplorasi data dikenal dengan istilah Exploratory Data Analysis (EDA). Eksplorasi data melibatkan dua kegiatan yaitu statistik deskriptif dan visualisasi data.

Tujuan utamanya adalah untuk mengetahui struktur data, distribusi data, dan keberadaaan data yang tidak normal. Tahapa ini juga bertujuan untuk mengetahui secara singkat mengenai hubungan antar data dalam dataset.

Statistik deskriptif memberikan ringkasan mengenai distribusi data seperti rata rata (mean), nilai tengah (median), nilai yang sering muncul (mode), standar deviasi, dan rentang nilai untuk setiap atribut data. di sisi lain visualisasi data memberikan pemahaman singkat mengenai data yang dikemas menggunakan bagan visual

#### 2. Kualitas Data

Kesalahan data dapat berupa kesalahan dalam memasukan data (entry data), keakuratan data, dan data yang bernilai tidak normal atau menyimpang dari pola keseluruhan.Untuk memastikan kualitas data, seorang data saintis biasanya menggunakan teknik seperti pembersihan data (data cleansing) dan transformasi data (Data Transformation)

Pembersihan data mencakup penghapusan data yang sama atau duplikat, penanganan data yang menimpang atau data pecilan, penggantian data yang kosong atau hilang (missing value), dan standarisasi nilai attribut. 

Missing value dapat diganti dengan nilai rata rata, nilai minimum atau nilai maksimum tergantung pada karakteristik datanya. Alternatif lainnya adalah menghapusdata yang memiliki missing value agar model yang dihasilkan lebih representatif.

#### 3. Seleksi Firtur

Tidak semua atribut dipakai atau berguna dalam emprediksi target. banyaknya atribut dalam kumpulan data secara signifikan dapat meningkatkan kompleksifitas model dan dapat menurunkan kinerja model. Bertambahnya jumlah dimensi juga dapat mempengaruhi reliabilitas model, terutama dalam kasus pengelompokan (clustering) dan klasifikasi (classification).

Oleh karen aitu dibutuhkan teknik untuk mengurangi jumlah atribut tanpa menutrunkan performa dari model secara signifikan. Teknik ini disebut dengan seleksi atau pemilihan firtur, Seleksi firtur dapat membuat model menjadi lebih sederhana dan memiliki penjelasan yang lebih efektif.

#### 4. Pengambilan Sampel Data (Data Sampling)

Data sampling adalah proses pemilihan sampel data, yaitu bagian kecil dari suatu data yang mewakili dataset secara keseluruhan untuk digunakan dalam proses analisis dan pemodelan. Teknik ini bermanfaat untuk mengurangi jumlah data yang akan diprosed dan mempercepat pembuatan model.

Dalam data sains, penggunaan data sampel dapat mempermudah proses ekstraksi informasi dan pembuatan model prediksi yang lebih representatif. Namun kesalahan dalam pengambilan data sampel akan berdampak pada relevansi dari model yang dihasilkan. Dalam membuat aplikasi sains data, dibutuhkan segmentasi dataset menjadi sampel data latih dan sampel data uji.


## [[04. Tahapan Pemodelan]]

Model adalah representasi abstrak dari suatu data. odel juga menggambarkan hubungan data dalam suatu kumpulan data (dataset). Model dalam data sains dibagi menjadi dua macam yaitu model deskriptif dan model prediksi. 

Model prediksi digunakan untuk memprediksi variabel hasil (outcom variable) bersdasarkan satu atau lebih variabel input (input variable). Teknik prediksi membutuhkan dataset yang digunakan untuk membuat dan mempelajari model.

Model deskriptif adalah teknik data sains dimana tidak ada variable target untuk diprediksi, sehingga tidak diperlukan dataset untuk pengujian. 

Teknik klasifikasi dan regresi dapat digunakan dalam teknik pemodelan prediktif. Sedangkan analisis asosiasi (association analysis) dan teknik clustering adalah contoh dari pemodelan dalam data sains yang bersifat deskriptif

![[Screenshot 2024-09-27 at 09.43.44.png]]

- data latih adalah dataset yag digunakan untuk membuat mnodel dimana data atribut dan variabel target sudah diketahui sebelumnya. 

- Sedangkan data uji adalah dataset yang digunakan untuk meneliti validasi dan akurasi dari model yang dibuat

Untuk memfasilitasi proses ini, kumpulan data yang diketahui secara keseluruhandapat dipecah mejadi data latih dan data uji. Pada umumnya dua pertiga dari total keseluruhan dataset akan digunakan sebagai data latih dan seper tiga nya akan digunakan sebagai data uji.

![[Screenshot 2024-09-27 at 09.48.38.png]]

Dalam membuat sebuah model, kita membutuhkan yang manamnya algoritma data sains. Sebagai contoh untuk kasus klasifikasi, algoritme yang dapat digunakan adalah Decision Tree, Rule Induction, Neural Netwioork, Bayesian Models, k-NN, dan lainnya

Teknik regresi linear sederhana akan digunakan untuk memodelkan dan menggeneralisasi buhungan antara skor kredit dan tingkat bunga. Model untuk kasus tersebut dapat dibuat dengan rumus regresi linear sederhana seperti berikut

$y=a*x + b$

y = variable terkait (dependent) atau output yang diprediksi
x = variabel bebas (independent) atau variable input
b = merupakan intercept, yaitu nilai perpotongan dengan sumbu y
a = koefisien regresi

Dengan regresi linear sederhana, model hubungan antara variabel terkait dan variabel bebas dapat digambarkan pada sebuah garis lurus.

![[Screenshot 2024-09-27 at 09.55.12.png]]

Garis yang dihasilkan dari persamaan di atas berfungsi sebagai model untuk memprediksi hasil dari dataset yang baru

Berikut adalah beberapa langkah yang dilakukan pada tahapan pemodelan:

1. Alanisis permasalahan dan membangun sebuah pertanyaan
2. Memilih sumber data yang releval untuk menjawab pertanyaan
3. memilih teknik saisn data yang sesuai
4. memilih algoritme saisn data yang tepat dan mempersiapkan data
5. Membagi data menjadi dataset pelatihan dan dataset pengujian
6. Membangun model dari dataset pelatihan
7. Memvalidasi model menggunakan dataset pengujian



## [[05. Tahapan Aplikasi]]

Tahapan selanjutnya pada prioses data saisn adalah dase deploymen. Pada tahapan ini model yang telah dihasilkan siap untuk diproduksu dan digunakan oleh pemangku kepentingan dalam perusahaan

Hasil dari proses data sains biasanya dirterapkan pada proses bisnis yang berjalan dalam bentuk aplikasi atau perangkat lunak

Tahap penerapan model dimulai dengan menilai kesiapan model, integrasi teknis, waktu respons, pemeliharaan model, dan asimilasi. Kualitas hasil prediksi, aksesibilitas data masukan dan waktu respons menjadi faktor penting dalam aplikasi bisnis berbasiskan data sains


## [[06. Tahapan Akhir]]

Tujuan utama dari proses data sains adalah ekstraksi informasi dari sebuah data. Data sains menyediakan kerangka kerja untuk melakukan ekstraksi infomrmasi dari kumpulan data. Dengan jumlah data yang sangat besar, proses komputasi yang canggih dan media penyimpanan data yang berkapasitas besar. Proses ekstraksi pengetahuan dari sebuah data memerlukan sebuah teknik dan pendekatan yang tepat.

Data sains dapat menjadi solusi dengan menyediakan seperangkat tahapan dan algoritme komputasi yang dapat membantu dalam penemuan pengetahuan dari kumpulan data. Pengetahuan dan Informasi yang didapatkan dari kumpulan data dapat dijadikan nilai tambah bagi suatu perusahaan guna meningkatkan bisnis mereka.