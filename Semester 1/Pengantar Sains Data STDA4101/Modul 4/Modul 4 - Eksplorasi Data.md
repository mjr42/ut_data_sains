---
tags:
  - sains_data
---
# Modul 4 - Eksplorasi Data

## [[01. Eksplorasi Data]]

Eksplorasi data adalah tahapan dasar dalam memahami karakteristik dari suatu dataset. Eksplorasi data bertujuan untuk memahami data dengan lebih baik sebelum diproses dalam tahapan analisis lebih lanjut. Waktu yang dibutuhkan dalam memahami suatu data lebih cepat  dengan menggunakan metode eksplorasi data.

Dalam data sains eksplorasi data lebih dikenal dengan istilah Exploratory Data Analysis (EDA) yaitu seperangkat alat yang digunkaan untuk memahami sifat, struktur, dan distribusi data. 

EDA juga dapat digunakan dalam data sains untuk melihat hubungan antar beberapa atribut dalam suatu dataset. KEluaran yang dihasilkan dalam eksplorasi data berupa tabel pivot, perhitungan statistik sederhana seperti nilai mean atau deviation, dan plotting data dalam bentuk line, bar, atau scatter chart.

Keluaran tersebut dapat dijadikan panduan dan pertimbangan dalam emilih metode data sains yang tepat untuk analisis lebih lanjut,


## [[02. Tujuan Eksplorasi Data]]

Dalam proses sains data, Eksplorasi data dapat dimanfaatkan dalam tahapan persiapan data (preprocessing), pemodelan, dan tahapan interpretasi dari hasil pemodelan. BErikut adalah bebrapa tujuan dari eksplorasi data dalam data sains.

#### 1. Memahami Data

Eksploraasi data memberikan gambaran umum mengenai setiap atribut atau variable dalam data set serta hubungannya. Selain tiu eksplorasi data juga membantu dalam mengetahui nilai khas dari suatu atribut, data yang berbeda dari nilai tipikal, data pecilan (outlier), serta nilai minimum dan maksimum dari suatu kumpulan data.

#### 2. Mempersiapkan Data

Sebelum menerapkan algoritme data sains, data set harus siap untuk menanganai setiap anomali yang mungkin terjadi seperti adanya data pecilan (data outlier), nilai yang hilang (missing value), dan atribut yang memiliki nilai kolerasi yang sangat tinggi.

Beberapa algoritme sains data tidak dapat bekerja dengan baik ketika atribut saling berkolerasi dengan nilai yang sangat tinggi.

#### 3. Metode Data Sains

Terkadang eksplorasi data saja sudah dapat menggantikan keseluruhan proses dalam data sains. 

Sebagai contoh : Scatter Plot dapat digunakan untuk mengidentifikasi cluster untuk data dengan dimensi rendah (low-dimension data) dan visualisasi data dapat membantu dalam mengembangkan model regresi atau model klasifikasi yntuk kasus-kasus sederhana.

#### 4. Mentafsirkan Hasil

Eksplorasi data juga dapat digunakan untuk memahami hasil prediksi, klasifikasi, dan pengelompokan (clustering) yang didapatkan dari keseluruhan proses dari data sains. Sebagai contoh : Histogram membantu dalam memahami distribusi atribut dan juga berguuna untuk memvisualisasikan diksi numerik, estimasi tingkat kesalahan (error rate estimation) dan lainnya.


## [[03. Proses Pada Eksplorasi Data]]

Eksplorasi data biasanya dibagi menjadi beebrapa tahapan sebagai berikut :

#### 1. Data Understanding

yaitu proses dalam memahami data yang kita miliki, data apa yang tersedia, berapa jumlah datanya, relevan/tidak, bagaimana kualitas datanya, bagaimana data dikumpulkan, dan siapa memahami data tersebut, dan sebagainya

#### 2. Data Preprocessing

Yaitu mengubah data mentah menjadi format yang dapat dimengerti. Data mentah apada kondisi nyata selalu tidak lengkap dan tidak bersih sehingga diperlukan proses awal dalam membersihkan data untuk mendapatkan model data yang reliable.

Proses dasar melingkupi seleksi variabel, penggabungan (join), data cleaning untuntuk data yang duplikat, noise, dan outlier, transformasi data serta dimensional reduction.

Contohnya:
- Noise : umur bernilai negatif
- OUtlier : tinggi badan yang > 300 meter
- Duplikat : Baris nilai dan ID yang sama mmuncul lebih dari 100 kali
- Tidak Lengkap : Data agregat saja dimana tidak memiliki variabel penting
- Data yang hilang (MIssing Value): Cell kosong, N/A NA, NaN
	- Statistik dasar (descriptive statistic) seperti melihat ukuran pusat (mean, median, modus) dan penyebaran data (jangkauan, kuartil, dan jangkauan interkuartil)
	- Visualisasi Data (Univariat/Multivariat)
	- Membuat Hipotesis (Dugaan awal)
	- Pemeriksaan Asumsi
	- Story Telling/ pelaporan (reporting) hasil.



## [[04. Hasil Eksplorasi Data]]

Hasil akhir dari tahapan eksplorasi data adalah data yang sudah siap untuk diolah lebih lanjut. Data ini harus sudah memenuhi syarat, sebagai berikut:

#### 1. Clean

yaitu data yang sudah bersih dari data ganda maupun data kosong, pencilan, dan sebagainya.

#### 2. Tidy

Yaitu data yang sudah tersusun rapi dan terstruktur dalam sebuah kolom dan baris misalnya

#### 3. Consistent

Yaitu data yang sudah memiliki format yang sama dalam sebuah kolom, misalnya tidak tercampur antara data numeric dan teks




## [[05. Panduan Eksplorasi Data]]

Kotu dan Deshpande (2019) memberikan peta jalan atau panduan untuk melakukan eksplorasi data. Terdapat sembilan tahapan utama untuk melakukan eksplorasi data, namun tidak setiap tahapan ini sesuai untuk jenis data sehingga peneliti dapat memilih tahapan yang sesuai dengan kebutuhannya. Panduan ini akan berguna untuk melakukan eksplorasi dan analisis dari kondisi suatu data baru yang belum pernah digunakan sebelumnya.

Sembilan tahapan tersebut adalah sebagai berikut :

##### 1. Merapihkan data

Struktur dari data biasanya selalu terdiri atas baris dan kolom. Merapikan data agar memiliki informasi atribut pada baris dan kolom akan mempermudah proses pengolahan dan analisis data. Pada baris biasanya merepresentasikan sebuah fenomena, sementara kolom merepresentasikan atribut dari fenomena tersebut

##### 2. Menemukan Titik Tengah untuk setiap atribut

Menghitung rata rata, nilai tengah, ataupun modus sehingga nilai pencilan atau distribusi dari data dapat ditemukan

##### 3. Memahami sebaran data

Menghitung standar deviasi dan jangkauan untuk sebuah atribut, serta nilai maksimal dan minimal

##### 4. Memvisualisasikan distribusi dari data

Dapat memanfaatkan histogram maupun boxplot untuk melihat distribusi data, apakah terdistribusi dengan normal atau tidak.

##### 5. Melakukan Analisis Pivot

Dikenal juga dengan istilah Dimensional Slicing, sehingga peneliti akan terbantu dengan mengetahui hubungan antar data. Analisis pivot dapat dilakukan dengan menggunakan Microsoft Excel dan RStudio

##### 6. Mencari pencilan

Gunakan scatterplot untuk menemukan data pencilan. Setelah ditemukan, nilai data tersebut dapat dihapus dan ulangi analisis. Perhatikan jika terdapat hasil yang berbeda.

##### 7. Memahami hubungan antaratribut

Lakukan pengukuran korelasi antar atribut, misalnya dengan membuat matrik korelasi. Perhatikan atribut yang tergantung dengan atribut yang lain, dan lakukan analisis mengapa hal tersebut terjadi.

##### 8. Membuat visualisasi hubungan nataratribut.

Buatlah plot grafis untuk menemukan hubungan antar atribut. Plot sederhana dan dimensi dapat membantu memvvisualisasikan hubungan antar atribut.

##### 9. Membuat visualisasi data high-dimensional

Misalnya dengan membuat plot grafis parallelchart untuk memvisualisasikan data yang memiliki dimensi tinggi.

Sementara itu untuk data geospasial yang memanfaatkan data geometri seperti poligon batas administrasi, peneliti dapat memanfaatkan teknik visualisasi conditional Plot (Map, Scatter Plot, Histogram, Boxplot) dengan menggunakan data atribut dari data geospatial tersebut.

