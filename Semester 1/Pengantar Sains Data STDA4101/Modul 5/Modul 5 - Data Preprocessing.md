---
tags:
  - sains_data
  - materi_5_PSD
---
## [[01. Pemprosesan Data]]

Data cenderung memiliki sifat noise, missing, dan incosistency karena ukurannya yang besar dan berasal dari berbagai sumber data yang berbeda beda. 

Data dengan sifat tersebut memiliki kualitas yang rendah sehingga menyebabkan hasil analisis yang tidak reliable. Ada beberapa faktor yang dapat menentukan kualitas dari suatu data yaitu:

1. Akurasi (Accuracy) misalnya beberapa atribut tidak memiliki nilai atai memiliki nilai yang salam
   
2. Kelengkapan (completeness) misalnya terdapat error dan nilai data yang sangat menyimpang
   
3. Konsistensi (Consistency), misalnya menggunakan kode yang berbda beda untuk kategori
   
4. Ketepatan waktu (timeliness) misalnya data yang dikumpulkan tidak tepat waktu sehingga data tidak tersedia
   
5. Kepercayaan (Believability), misalnnya data yang sering error atau perhitungan data yang salah sehingga pengguna tidak percaya dengan hasil yang ditampilkan
   
6. Kemudahan interpretasi (interpretability) menunjukan seberapa mudah data diinterpretasikan. Misalnya penggunaan kode kode yang tidak mudah untuk diterjemahkan orang lain.


## [[02. Teknik Pemprosesan Data]]


Salah satu cara untuk meningkatkan kualitas dari suatu data sebelum masuk ke tahapan data mining adalah dengan melakukan teknik pemprosesan data (data preprocessing). Beberapa teknik yang diterapkan pada data preprocessing adalah sebagai berikut :

#### 1. Data Cleaning

Pembersihan data dilakukan untuk tujuan menghapus noise, melakukan koreksi terhadap data yang tidak konsisten, mengusu dara yang kosong, dan menghapus data yang duplikat dan data yang sangat menyimpang adri nilai normal (data data outliers)

#### 2. Data Integration

Integrasi data menggabungkan data dari berbagai sumber ke dalam penyimpanan data yang koheren seperti gudang data (data warehouse)

#### 3. Data Reduction

Reduksi data dapat digunakan untuk mengurangi ukuran data, misalnya melakukan agregasi data, menghilangkan dfirtur yang berlebihan, atau melakukan pengelompokan (clustering). Strategi untuk reduksi terdiri dari pengurangan dimensi (dimension reduction) dan pengurangan jumlah (numerosity reduction)

#### 4. Data Transformation

Transformasi data misalnya teknik normalisasi data diterapkan dengan cara memberikan skala pada data agar berada dalam rendatang yang lebih kecil seperti 0,0 hingga 0,1

![[Screenshot 2024-10-05 at 00.31.12.png]]

Teknik ini dapat meningkatkan akurasi serta efisiensi algoritme data mining yang melibatkan pengukuran jarak (distance measurement). Contoh sederhananya adalah mengubah nilai pada sumbu x menjadi log x sehingga hubungan antara x (variabel bebas) dan y (variabel terkait) menjadi linear.



## [[03. Data Cleaning]]

#### Penanganan Missing Value

Contohnya adalah ketika banyak tuped (catatan atau barisa pada tabel database) yang tidak memiliki nilai untuk beberapa atribut seperti pendapatan pelanggan. Beberapa metode yang dapat diterapkan untuk penanganan missing value adalah sebagai berikut:

1. Mengabaikan atau menghapus tupel, misalnya untuk kasusu klasifikasi beberapa label kelas tidak ada
   
2. Mengisi nilai yang hilang secara manual, namun cara ini memakan banyak waktu dan tidak bisa diterapkan pada dataset dengan ukuran yang sangat besar
   
3. Menggunakan konstanta global untuk mengisi nilai yang kosong seperti mengisinya dengan "unknow" atau "null". Data dengan nilai null yang banyak membuat model data semakin tidak baik
   
4. Mengunakan tendensi sentral dari atribut, misalnya nilai mean untuk data dengan distribusi normal dan nilai median untuk skewed data distribution



## [[04. Penanganan Noise Data]]

Noise adalah istilah yang sering digunakan untuk menyatakan kesalahan acak atau varians dalam variabel yang dikukur, Beberapa metode yang dapat diterapkan untuk menangani noise pada data adalah sebagai berikut :

#### 1. Binning

Teknik ini melakukan perbaikan terhadap data dengan cara menihat nilai tetangganya (yang terdekat dengan nilai tertentu). Untuk melakukan binning, data dari suatu atribut harus dalam kondisi yang terurut sebelum dilakukan pengelompokan ke beberapa bin atau bucket dengan jumlah data yang sama.

Teknik partisi ke dalam bin ada dua cara yaitu:
1. Equal-Width (Distance) Partitioning
2. Equal-Depth (Frequency) partitioning.

Sedangkan untuk smoothing terdapat tiga macam teknik yaitu:
1. Smoothing by bin-means
2. Smoothing by bin-median
3. Smoothing by bin-boundary

![[Screenshot 2024-10-05 at 00.41.42.png]]


#### 2. Regresi

Teknik yang digunakan untuk penghalusan data dengan cara memasukan data ke dalam fungsi regresi

#### 3. Analisis Outlier

Mendeteksi nilai nilai pencilan yang mencurigakan dan membuang nilai tersebut. Nilai pencilan dapat terlalu tinggi ataupun terlalu rendah dibandingkan dengan nilai lainnya

![[Screenshot 2024-10-05 at 00.43.27.png]]


