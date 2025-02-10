---
tags:
  - sains_data
  - materi_17_PSD
---
Sekilas, mungkin tidak terlihat perbedaan antara klasifikasi dengan prediksi. Namun, pada proses klasifikasi terdapat serangkaian dataset berupa kelas dalam bentuk diskret. Dataset ini kemudian diambil sebagian untuk digunakan sebagai data latih dalam proses pembelajaran (learning). Hasil akhirnya kemudian diperoleh berdasarkan kepada proses pembelajaran sebelumnya.

Pada proses prediksi, nilai akhir sepenuhnya diperoleh dari seluruh data yang tersedia tanpa ada pengambilan data latih. Pada proses prediksi juga tidak dibutuhkan label yang benar terlebih dahulu. Hasil prediksi dapat berupa beberapa kelas atau kategori yang belum memiliki definisi.

Definisi diberikan kemudian setelah peneliti melihat pola yang terbentuk berdasarkan pada kondisi seluruh data pada masing-masing klaster yang terbentuk. Prediksi merupakan bagian dari algoritme klastering.


## [[01. Clustering]]

Proses klastering merupakan salah satu pendekatan prediksi yang paling sederhana di mana peneliti berusaha mengelompokkan seluruh data ke dalam beberapa klaster yang berbeda-beda. Klastering juga dianggap sebagai salah satu metode unsupervised learning.

Data yang diolah tidak memiliki label dan kelas tertentu, algoritme klastering bekerja dengan cara melihat variabel atau fitur-fitur yang memiliki kemiripan. Semakin mirip atau dekat suatu fitur, maka akan semakin besar kemungkinan data tersebut masuk ke dalam klaster yang sama. Sebaliknya, semakin berbeda atau jauh suatu fitur dalam suatu data, maka akan semakin besar kemungkinan data tersebut masuk ke dalam klaster yang berbeda.

![[Pasted image 20241124143050.png]]

Gambar 17.1 menunjukkan contoh visualisasi klaster kejadian gempa di Indonesia sejak tahun 1900 hingga 2020. Pada contoh kasus ini, tidak ada fitur dari kejadian gempa yang dipilih sebagai data latih. Sebuah fitur dipilih, misal kekuatan gempa, kemudian digunakan untuk membuat klaster kejadian berdasarkan kekuatan gempa tersebut. Dapat dilihat bahwa kejadian gempa di Indonesia selama kurang lebih 120 tahun memiliki tiga klaster utama, yaitu klaster gempa dengan kekuatan besar yang sering terjadi di wilayah Maluku dan Sulawesi. Klaster gempa dengan kekuatan sedang yang sering terjadi di wilayah Jawa dan Sumatra, serta klaster gempa dengan kekuatan rendah yang tersebar mulai dari ujung timur hingga ujung Barat wilayah nusantara.




## [[02. Berbagai Jenis Clustering]]

Menurut literatur terdapat beberapa jenis klastering yang sering digunakan dalam proses pengolahan data, yaitu 
1) eksklusif atau strict partitioning klaster, 
2) klaster tumpang-tindih (overlapping), 
3) klaster bertingkat (hierarchical), 
4) klaster fuzzy (probabilistic), 
5) Prototype-based clustering,
6) density klaster, dan 
7) klaster berbasis model.


#### Metode eksklusif Klaster (strict partitioning)

Pada metode eksklusif klaster (strict partitioning) artinya setiap data akan masuk ke dalam sebuah klaster yang eksklusif. Ini adalah jenis klaster yang paling umum. Sementara pada metode klaster tumpang-tindih (over-lapping) kelompok klaster tidak eksklusif sehingga setiap data dapat masuk ke dalam lebih dari satu klaster. Metode ini dikenal juga sebagai metode multi-view klaster. Misal, mahasiswa suatu universitas dapat dikelompok-kan sebagai kelompok mahasiswa pandai dan kaya sekaligus dalam waktu yang sama.

#### Metode Cluster Bertingkat (hierarchical)

Metode klaster bertingkat (hierarchical) misalnya, pada kasus klasi-fikasi citra satelit ke dalam beberapa kelas hutan. Kelompok kelas hutan dapat dikelompokkan (dipisahkan) kembali menjadi kelompok kelas hutan tropis, hutan bakau, hutan tanaman industri, dan sebagainya.

Luaran dari klaster bertingkat adalah sebuah dendogram, yaitu sebuah diagram pohon yang memvisualisasikan perbedaan klaster berdasarkan tingkat presisi yang ditentukan oleh pengguna. Terdapat dua pendekatan dalam klaster bertingkat, yaitu bottom-up dan top-down. Pendekatan bottom-up adalah di mana sebuah data dianggap sebuah klaster kemudian digabungkan menjadi sebuah klaster dataset besar. Sebaliknya, pada pendekatan top-down, seluruh dataset dianggap sebagai sebuah klaster, kemudian secara berulang-ulang dibagi ke dalam beberapa subklaster sehingga setiap data individu/ tunggal terbagi ke dalam klaster-klaster yang berbeda. Metode klaster ber-tingkat (hierarchical) sesuai digunakan untuk data dengan ukuran yang terbatas. Tingkat presisi dapat disesuaikan secara interaktif oleh peneliti dengan cara menyederhanakan (memotong) pohon dendogram.

#### Fuzzy atau probabilistic klaster

Fuzzy atau probabilistic klaster merupakan metode pengelompokan data berdasarkan pada perbedaan tingkat atau derajat keanggotaan (degree of membership) dari 0 sampai 1: Misal pada sebuah dataset terdapat klaster 1, 2, dan 3, di mana setiap data dikategorikan ke dalam sebuah klaster ber-dasarkan derajat keanggotaannya. Klaster 1 memiliki derajat keanggotaan antara 0 sampai 0,3. Klaster 2 memiliki derajat keanggotaan antara 0,4 sampai 0,7. Terakhir, klaster 3 memiliki derajat keanggotaan antara 0,8 sampai 1.

#### Prototype-based clustering

Prototype-based clustering adalah metode di mana setiap klaster dire-presentasikan oleh sebuah central data object, dikenal juga dengan istilah prototype. Prototype dari setiap klaster biasanya adalah pusat dari klaster shingsa prototype-based klaster dikenal juga dengan istilah called centroid clustering atau center-based clustering.

#### Density clustering

Density clustering atau klaster kepadatan adalah suatu metode klaster yang melihat tingkat kepadatan per satuan unit area. Suatu klaster dapat diobservasi berdasarkan perbedaan tingkat kepadatan yang tinggi atau rendah. Klaster dengan kepadatan yang rendah dianggap sebagai noise dan tidak akan dianggap sebagai sebuah klaster. Dengan menggunakan metode ini akan ada data yang tidak termasuk ke dalam klaster mana pun karena dianggap sebagai noise.

#### Model-based clustering

model-based clustering, yaitu suatu metode klaster yang ber-basis pada statistik dan model distribusi probabilitas sehingga dikenal juga dengan distribution-based clustering. Sebuah klaster dianggap sebagai sebuah kelas jika memiliki nilai distribusi probabilitas yang sama sehingga setiap klaster dapat direpresentasikan oleh sebuah model distribusi misal Gaussian atau Poisson di mana parameter distribusi dapat dioptimasi se-cara berulang-ulang. Dengan menggunakan metode ini seluruh dataset dapat direpresentasikan oleh sebuah atau beberapa model distribusi.





## [[03. K-Means clustering]]

K-Means clustering merupakan metode clustering berbasis prototype di mana dataset dibagi menjadi k-klaster. K-Means clustering adalah salah satu algoritme prediksi yang paling sederhana dan paling umum digunakan.

Dalam teknik ini, peneliti menentukan jumlah klaster (k) yang perlu dike-lompokkan.

Tujuan dari k-means clustering adalah untuk menemukan titik data prototipe untuk setiap klaster; semua titik data kemudian ditugaskan ke prototipe terdekat, yang kemudian membentuk sebuah klaster. Prototipe disebut sebagai centroid (pusat klaster). Pusat klaster dapat berupa nilai mean (rata-rata) dari semua objek data dalam klaster, atau objek data yang paling terwakili. Pusat klaster atau objek data rata-rata tidak harus berupa titik data nyata dalam kumpulan data dan dapat berupa titik data imajiner yang mewakili karakteristik semua titik data dalam klaster.

Secara visual, algoritme k-means membagi ruang data menjadi k-partisi (batas), dimana centroid pada setiap partisi merupakan prototype dari klaster. Partisi ini juga disebut partisi Voronoi, dan setiap prototipe adalah benih dalam partisi Voronoi. Partisi Voronoi adalah proses segmentasi ruang menjadi wilayah, di sekitar sekumpulan titik yang disebut seed. Semua titik lainnya kemudian diasosiasikan dengan seed terdekat dan titik yang diaso-siasikan dengan seed dari partisi yang unik.

Metode k-means menciptakan k-partisi dalam ruang n-dimensi, di mana n adalah jumlah atribut dalam kumpulan data yang diberikan. Untuk mempartisi dataset, ukuran kedekatan harus ditentukan. Ukuran kedekatan yang paling umum digunakan untuk atribut numerik adalah Euclidean distance. Hasil akhir dari metode klaster k-means memberikan ruang partisi yang jelas untuk klaster 1 dan ruang yang sempit untuk dua klaster lainnya, yaitu klaster 2 dan klaster 3.

![[Pasted image 20241124143638.png]]

Gambar 17.2 memvisualisasikan hasil klaster menggunakan algoritme k-means dari data yang direkam oleh sensor RPLiDAR pada kasus identi-fikasi polutan. Seperti yang telah dijelaskan sebelumnya, pada algoritme k-means peneliti telah menentukan nilai k atau jumlah klaster terlebih dahulu. Pada contoh kasus ini peneliti menggunakan nilai k=5. Fitur yang digunakan adalah jarak (distance) dan nilai sudut (angule). Semua dataset kemudian diolah dan dihasilkan lima klaster dengan visualisasi seperti pada Gambar 17.2.




## [[04. Penentuan Nilai K]]

Penentuan jumlah klaster (nilai k) yang optimal dari suatu dataset adalah sebuah permasalahan yang mendasar. Namun, tidak ada jawaban yang paling tepat dari pertanyaan, "berapa jumlah klaster yang optimal untuk penelitian ini?" Jawaban akan bersifat subjektif, tergantung dari jenis pene-litian, jenis data, metode perhitungan, dan sebagainya.

Terdapat paling tidak dua metode perhitungan jumlah klaster (nilai k), yaitu metode perhitungan langsung dan metode uji statistik. Metode perhitungan langsung seperti Elbow dan Silhouette, sementara metode uji statistik seperti gap statistik. Metode ini dapat diuraikan berikut ini.

#### 1. Metode Elbow

Pada metode Elbow melakukan perhitungan total variasi intra-klaster (total within-cluster sum of square - WSS), yaitu proses perhitungan yang mencari jarak minimum antara data dengan centroid, dan mencari maksimum antara centroid. Nilai 0 dari WSS menunjukkan bawah semua data berada pada klaster yang berbeda, sementara nilai 1 dari WSS menunjukkan semua data berada pada klaster yang sama. Keduanya menunjukkan bahwa klaster tidak berguna atau tidak ditemukan. Diberikan nama "Elbow" karena grafis yang dihasilkan seakan-akan membentuk lengan manusia (Gambar 17.3).

![[Pasted image 20241124143752.png]]

#### 2. Metode Average Silhouette

Pada metode average Silhouette perhitungan dilakukan dengan cara meng-hitung nilai koefisien Silhouette dari setiap titik sehingga akan diperoleh tingkat kemiripan dari data. Jika semakin mirip, maka akan dikelompokkan ke dalam klaster yang sama. Diberikan nama "average" karena metode average Silhouette akan menghitung nilai rata-rata sehingga semakin tinggi nilai rata-ratanya maka akan semakin baik. Jumlah klaster yang dihasilkan dengan metode ini biasa lebih kecil dibandingkan dengan dua metode lainnya (Gambar 17.4). Namun, itu semua akan kembali kepada kondisi data yang diolah.

![[Pasted image 20241124143855.png]]

#### 3. Metode Gap Statistik

Metode gap statistik menghitung kesenjangan (gap) antara suatu data dengan data yang lainnya. Klaster yang optimal adalah yang memiliki nilai statistik kesenjangan (gap) terbesar (Gambar 17.5).

![[Pasted image 20241124143915.png]]




## [[05. Kelebihan dan Kekurangan]]

#### Kelebihan

Kelebihan dari algoritme seperti k.-means di antaranya adalah mudah untuk diimplementasikan. Dibandingkan dengan klaster bertingkat (hierar-chical), dengan jumlah data yang lebih besar algoritme k-means akan lebih cepat secara waktu komputasi. Algoritme k-means juga akan lebih meng. hasilkan klaster yang lebih rapat dibandingkan klaster bertingkat. Ketika centroid dihitung ulang, maka perpindahan secara instan akan terjadi, dan perubahan klaster akan mudah diobservasi.

#### Kekurangan

Namun, algoritme k-means juga memiliki kelemahan, seperti sulit untuk menentukan jumlah klaster yang sesuai (nilai k). Jika data mengalami proses normalisasi atau standardisasi, maka klaster juga akan mengalami perubahan. Nilai centroid juga mudah dipengaruhi oleh outlier, maka pastikan outlier tidak ada untuk menghasilkan klaster yang berkualitas.

Pada algoritme klaster bertingkat (hierarchical), luaran akhirnya adalah berupa tingkatan, misal sebuah struktur pohon bertingkat yang divisuali-sasikan oleh sebuah dendogram, visualisasi ini akan lebih mudah dipahami oleh pemangku kepentingan. Namun, hasil pada dendogram ini sudah merupakan hasil final dan tidak dapat dilakukan perubahan. Algoritme klaster bertingkat (hierarchical) juga tidak sesuai untuk data yang beru-kuran sangat besar (big data) karena struktur pohon yang akan sulit dije-laskan. Seperti halnya algoritme k-means, algoritme klaster bertingkat (hierarchical) ini juga sangat sensitif terhadap nilai pencilan (outliers).





