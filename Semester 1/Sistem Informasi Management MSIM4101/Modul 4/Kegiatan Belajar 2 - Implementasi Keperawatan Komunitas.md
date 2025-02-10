---
tags:
  - sistem_informasi_management
  - materi_4_SIM
---
# Kegiatan Belajar 2 - Implementasi Keperawatan Komunitas

Manajemen dapat dibagi menjadi tiga level, yaitu level bawah (level operasional), level menengah (level taktik) dan level atas (level strategi). Oleh karena setiap level manajemen melakukan kegiatan yang berbeda, mereka juga membutuhkan informasi dan sistem informasi yang berbeda

## [[03. Sistem-Sistem Informasi di Level Bawah]]

Atau di level operasi mendukung manajer operasi untuik melakukan kegiatannya. Tujuan utama dari sistem informasi di level bawah adalah menjawab pertanyaan rutin untuk keperluan mengontrol arus dari transaksi yang terjadi di Organisasi. Sistem informasi di level bawah berbasis pada transaksi yang disebut Transaction Processing System (TPS) dan process control system (PCS).



## [[04. Sistem-Sistem Informasi di Level Menengah]]

Digunakan untuk pengendalian dan pengambilan keputusan manajemen yang bersifat setengah terstruktur (semisctructured). Sistem informasi ini adalah:

1) Sistem Pakat (SP) atau Expert System (ES)
2) Jaringan Neural Buatan (JNB) atau Artificial Neural Network (ANN)
3) Sistem Penunjang Keputusan (SPK) atau Decision Support System (DSS) atau Group Support System (GSS)
4) Sistem Informasi Geografis (SIG) atau Geographic Information System (GIS)

#### 1. Sistem Pakar (SP) Expert System (ES)

Adalah sistem informasi yang berisi dengan pengetahuan dari pakar sehingga dapat digunakan untuk konsultasi. Sistem pakar ini berisi pengetahuan dari satu atau lebih pakar. Pengetahuan dari pakar dalah sistem ini digunakan sebagai dasar oleh sistem pakar untuk menjawab pertanyaan.

Sistem pakar memiliki 3 komponen utama yaitu:
##### 1. User Interface

User interface merupakan media yang digunakan untuk berbuhuingan input dan output dengan pamakainya. Interface yang dipakai dalam sistem pakar adalah keyboard dengan monitor.

##### 2. Interference Engine

Interface adalah perangkat lunak sistem pakar yang akan mengevaluasi aturan aturan yang telah disediakan oleh knowledge base dengan urutan tertentu untuk memberikan jawaban dari pertanyaan pemakai sistem dan alasan konsultasi dengan pemakai sistem. 

Interface engine dapat dibangun menggunakan bahasa pemprograman umum seperti C dan bahasa pemprograman khusus seperti Lips dan Prolog.

Interface engine tersedia dalam benruk paket yang disebut dengan expert system shell (ESshell). ESshell yang dijual komersial pertama adalah knowledge engineering environment(KEE). KEE dimaksudkan untuk aplikasi sistem pakar di komputer yang menggunakan bahasa Lisp. Beberapa ES shell lainnya tidak menuntut penggunaan Lisp atau Prolog. Beberapa Esshell yang ada adalah Exsys, Level – 5, CLIPS dan Guru 

##### 3. Knowledge Base

Knowledge base dibentuk dari aturan aturan yang berkaitan dengan satu dengan yang lainnya. Pengetahuan yang disimpan dalam knowledge base ini diambil dari kepandaian pakar. Orang yang ahli di bidang pengambilan pengetahuan dari pakar disebut dengan Knowledge Engineer. Proses pengambilan pengetahuan dari pakar disebut dengan Knowledge Engineering atau Knowledge Acquisition atau Knowledge Extraction

![[Screenshot 2024-10-01 at 10.38.50.png]]

#### 2. Jaringan Neural Artificial (JNA) Artificial Neural Network (ANN)

merupakan jaringan neural buatan yang mencoba meniru jaringan neural manusia. Perancangan dari jaringan neural artificial diilhami dengan strtuktur dari otak manusia.  Jaringan eural artifisial memiliki intelegensia yang dapat belajar dan serfikir seperti layaknya otak manusia. Oleh karena jaringan neural arifisial dapat belajar,jaringan neural artifisial ini dapat dilatih dan mengembangkan dirinya sendiri sehingga hasil yang diberikan oleh jaringan neural artifisial ini tidak harus sama dari waktu ke waktu. Berbeda dengan sistem pakar yang tidak dapat belajar dan tidak dapat dilatih sehingga semua aturan-aturan dan pengetahuan harus dimasukkan dalam sistem pakar. Sistem pakar tidak dapat mengembangkan pengetahuannya sendiri

Jaringan neural artifisial mulai banyak digunakan untuk memprediksi harga saham, memprediksi kebangkrutan perusahaan, memprediksi kapan saham harus dijual atau dibeli dan memprediksi ranking dari obligasi.


#### 3. Sistem Penunjang Keputusan (SPK) Decision Support System (DSS)

Suatu sistem untuk membantu manajer level menengah untuk proses pengambilan keputusan setengah terstruktur (semistructure) supaya lebih efektif dengan menggunakan model model analitis dan data yang tersedia.

Tujuan dari SPK adalah sebagai berikut:

- Membantu manajer mengambil keputusan setengah terstruktur yang dihadapi oleh manajer level menengah.
  
- Membantu atau mendukung manajemen mengambil keputusan bukan menggantikannya.
  
- Meningkatkan efektivitas pengambilan keputusan manajemen bukan untuk meningkatkan efisiensi. Walaupun waktu manajer penting (efisiensi), efektivitas merupakan tujuan utama penggunaan SPK

Sistem penunjang keputusan (SPK) mempunyai tiga komponen utama, yaitu:
![[Screenshot 2024-10-01 at 10.51.41.png]]

##### 1. Dialog Manajemen atau User Interface

Yaitu komponen untuk berdialog dengan pemakai sistem. Komponen ini dalam sistem informasi merupakan komponen input dan komponen output.

##### 2. Model Manajemen

Yaitu komponen yang mengubah data menjadi informasi yang relevan. Model model yang banyak digunakan di sistem penunjang keputusan adalah model matematika optimisasi misalnya linear programing atau dynamic programing.

##### 3. Data Manajemen

Yaitu komponen basis data yang terditri atas semua basis data yang dapat diakses.

Sama seperti halnya sistem informasi pada umumnya, Sistem penunjang keputusan juga mempunyai kompobnen lain yaitu komponen teknologi dan kontrol. Komponen teknologi terdiri atas perangkat ekras dan perangkat lunak


Menurut Dhar dan Stein, SPK dibedakan kedalam dua tipe yaitu SPK yang berbasis kepada model (Model Driven DSS) dan SPK berbasis kepada data (Data Driven DSS)

###### Model Driven DSS

SPK lama yang dibangun pada tahun 1980-an hanya berbasis pada model (model driven DSS) dengan menggunakan data secukupnya. 

###### Data Driven DSS

SPK sekarang, selain berbasis pada model,juga mengandalkan basis data yang besar, misalnya mengandalkan data warehouse. Data driven DSS lebih mengandalkan data yang besar. SPK ini akan mengizinkan pemakai sistem untuk mengambil informasi dari data yang jumlahnya sangat besar. Online analytical processing (OLAP) dan data mining dapat digunakan untuk menganalisis data yang besar ini.

> Online Analytic Processing merupakan sisten informasi fungsional yang sudah ada yang mempunyai basis data yang lengkap ditambah dengan kemampuan mengambil data dan menganalisanya secara Online. OLAP biasanya menggunakan DBMS dan bahasa kueri sehingga memudahkan manajer semua tingkat untuk menggunakannya

>Datamining adalah teknik yang digunakan untuk menemukan pola dan hubungan antara item-item data di data warehouse. 

>Data Warehouse adalah salinan dari data dalam bentuk basis data yang terintegrasi

> Datamart adalah salinan dari berbagai porsi berbasis data yang terintegrasi


#### 4. Sistem Penunjang Keputusan Grup (SPKG) Group Decision Support System (GDSS)

Adalah SPK yang digunkaan oleh bebrapa pengambil keputusan bersama sama secara group. SPK grup ini muncul karena perdebatan pada awal-awal tahun 1990-an bahwa pengambilan keputusan secara grup akan lebih baik dari secara individual karena grup dianggap dapat memberikan sinergi akibat kontak sosial antarmereka.

Menurut Jessup dan Tansuk, Riset membuktikan bahwa penyediaan sistem komputer untuk mendukung keputusan grup menghasilkan komunikasi lebih mudah, melindungi identitas pengusung ide, dan hasilnya adalah meningkatnya efisiensi, kreatifitas, serta kualitas pengambilan keputusan


#### 5. Sistem Informasi Geografis (SIG) Geographic Information System (GIS)

Sistem ini menggunakan bentuk peta secara geografis, contohnya:

Perusahaan jaringan toko ritel Wal Mart mengumpulkan semua basis data di masing-masing tokonya yang tersebar di Amerika Serikat ke dalam data warehouse di kantor pusat. Dengan menggunakan data mining, manajer di Wal Mart dapat menganalisis perilaku konsumen secara nasional serentak. Wal Mart menampilkan informasi ini dalam bentuk peta wilayah Amerika Serikat dan dapat melihat pergerakan pola perilaku konsumen antarwaktu dan antartempat di seluruh tokonya di Amerika Serikat. Dari tampilan ini, dapat dilihat pergeseran-pergeseran penjualan yang terjadi dan perilaku konsumen dapat dipelajari sehingga alokasi promosi dan produk dapat dioptimalkan


## [[05. Sistem-Sistem Informasi di Level Atas]]

Sistem Informasi Eksekutif atau Executive Information System adalah sistem informasi yang digunakan manajer tingkat atas untuk membantu memecahkan masalah tidak terstruktur. SIE mempunya karakteristik khusus sebagai berikut:

1. Dirancang untuk eksekutif puncak\
2. Menggunakan data internal dan eksternal
3. Untuk pemecahan tidak terstruktur
4. Membantu perancangan dan perumusan strategi
5. Digunakan secara online oleh eksekutif
6. Mempunyai kemampuan untuk mengambil dan menyaring data
7. Mempunyai kemampuan untuk mengambil dan menggali data sampai data terkecil (Drill Down)
8. Harus mudah digunakan
9. Menggunakan teks, grafik, dan tabel yang mudah dicerna

Sistem informasi eksekutif (SIE) sama dengan sistem penunjang eksekutif (SPE) atau executive support system (ESS). Walaupun SPE dan SIE adalah sama, ada yang membedakannya. Perbedaannya adalah SIE tidak menggunakan sistem otomatisasi kantor, sedangkan SPE menggunakannya



## [[06. Sistem Otomatisasi Kantor]]

Adalah sistem yang menghubungkan tiga level manajemen Sistem Otomatisasi Kantor (SOK) atau Office Automation System (OAS) didefinisikan oleh O'Brien 1996 sebagai sistem informasi berbasis telekomunikasi yang mengumpulkan, memproses, menyimpan, dan mendistribusikan pesan, dokumen, komunikasi elektronik lainnya di antara individu, grup dan organisasi

Sistem Kantor Otomatis terdiri atas:

1. Sistem Komunikasi Elektronik
2. Sistem Kolaborasi Elektronik
3. Sistem Publikasi dan Pengolahan citra elektronik dan
4. Sistem pengelolaan kantor

![[Screenshot 2024-10-01 at 12.37.21.png]]
