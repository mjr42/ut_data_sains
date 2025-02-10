---
tags:
  - basis_data
  - materi_2_BD
---


# [[Kegiatan Belajar 1 - Model Database dan Model Data]]

Pada Kegiatan Belajar 1 ini kita akan membahas Model Database dan Model Data, jika diamati dalam kehidupan sehari-hari, model database dan model data sebenarnya sudah tidak asing lagi. Misalnya ketika melakukan perjalanan menggunakan kereta api maka mulai dari pemesanan tiket, keberangkatan, sampai tiba di tujuan sebenarnya terdapat model database dan model data. 

Contoh lain adalah ketika kuliah di Perguruan Tinggi, mulai dari proses pendaftaran menjadi mahasiswa, pembayaran uang perkuliahan, melaksanakan perkuliahan, sampai dengan lulus perkuliahan itu juga sudah terdapat model database dan model data.


## 01. Model Database

> Model database adalah suatu konsep yang terintegrasi dalam menggambarkan hubungan (relationship) antar data dan batasan-batasan (constraint) data dalam suatu sistem database. Model data yang paling umum berdasarkan pada hubungan antar-record dalam database (Record Based Data Models) dan terbagi atas tiga jenis, yaitu:


#### 2.1.1 Model Database Hierarki (Hierarchical Database Model)

Model hierarki biasa disebut model pohon karena menyerupai pohon terbalik. Model ini menggunakan pola hubungan orang tua anak seperti pada Gambar 2.1 berikut ini

![[Pasted image 20250209124729.png]]

Pada Gambar 2.1 contoh model database hierarki yaitu menggambarkan hierarki entitas dosen, mata kuliah dan mahasiswa. Dosen mengampu mata kuliah dan mata kuliah dipelajari oleh mahasiswa. Model ini menggunakan istilah orang tua dan anak. Orang tua dapat memiliki anak, dan anak hanya memiliki satu orang tua.


#### 2.1.2 Model Database Jaringan (Network Database Model)

Model database jaringan yaitu model database yang dapat mewakili objek suatu hubungan dan membentuk suatu jaringan. Sama seperti model database hierarki, model database jaringan dapat direpresentasikan sebagai orang tua dan anak. Perbedaannya yaitu jika dalam model database hierarki anak hanya memiliki satu orang tua, namun pada model database jaringan anak dapat memiliki lebih dari satu orang tua. Gambar 2.2 berikut adalah contoh model database jaringan.

![[Pasted image 20250209124807.png]]

#### 2.1.3 Model Database Relasi (Relational Database Model)

Model database relasi merupakan model yang paling sederhana sehingga mudah digunakan dan dipahami oleh pengguna. Model ini menggunakan sekumpulan tabel berdimensi dua yang disebut relasi atau tabel dengan relasi tersusun atas tupel atau baris dan atribut. DBMS yang bermodelkan relasional biasa disebut RDBMS (Relational Data Base Management System). Model database ini dikemukakan pertama kali oleh EF Codd, seorang pakar basis data. Model ini sering disebut juga dengan model database relasi.

Model database hierarki dan jaringan merupakan model database yang tidak banyak lagi dipakai saat ini karena adanya berbagai kelemahan dan hanya cocok untuk struktur hierarki dan jaringan saja. Artinya, model database hierarki dan jaringan tidak mengakomodasi berbagai macam jenis persoalan dalam suatu sistem database. Model database relasi merupakan model database yang paling banyak digunakan saat ini karena paling sederhana dan mudah digunakan serta yang paling penting adalah kemampuannya dalam mengakomodasi berbagai kebutuhan pengelolaan database.

Sebuah database dalam model ini disusun dalam bentuk tabel dua dimensi yang terdiri dari baris (record) dan kolom (field), pertemuan antara baris dengan kolom disebut item data (data value), tabel-tabel yang ada di hubungkan (relationship) sedemikian rupa menggunakan field-field kunci (key field) sehingga dapat meminimalkan duplikasi data.





## 02. Model Data

> Model data adalah sekumpulan konsep yang terintegrasi untuk mendiskripsikan data, hubungan antar data, dan batasan-batasannya. Model data harus merepresentasikan serta menyediakan konsep dasar dan notasi yang memungkinkan perancang basis data dan pemakai untuk dapat mengkomunikasikan pemahamannya mengenai organisasi data.


#### 2.2.1 Komponen Model Data

Komponen model data dapat dikategorikan menjadi 3 (tiga) bagian yang meliputi:

1. ﻿﻿﻿Bagian struktural, memuat sekumpulan aturan untuk melakukan konstruksi basis data ( database).

2. ﻿﻿﻿Bagian manipulasi, melakukan definisi tipe operasi yang diizinkan pada data, termasuk operasi yang digunakan untuk melakukan perubahan (update), atau membaca data (retrieve) dari basis data dan untuk melakukan perubahan struktur basis data.

3. ﻿﻿﻿Sekumpulan aturan mengenai integritas yang akan menjaga keakuratan dari data dalam basis data (database).

#### 2.2.2 Kelompok Model Data

Secara garis besar, model data dapat dikelompokkan dalam 3 macam, yaitu:

4. Object based data model (Model data berbasis objek), terdiri atas:

	1. ﻿﻿﻿Entity relationship model.
	2. ﻿﻿﻿Binary model.
	3. ﻿﻿﻿Semantic model.

5. Record based data model (Model data berbasis relasi), terdiri atas:

	1. ﻿﻿﻿Hierarchycal model.
	2. ﻿﻿﻿Network model.
	3. ﻿﻿﻿Relational model.

6. Physical based data model (Model data berbasis fisik), terdiri atas

	4. ﻿﻿﻿Unifying model.
	5. ﻿﻿﻿Frame memory.


#### 2.2.3 Penjelasan Macam-Macam Model Data

##### 2.2.3.a Object based data model.

Model ini merupakan himpunan data dan prosedur atau relasi yang menjelaskan hubungan logis antar data dalam suatu basis data berdasarkan obyek datanya. Dalam object based data model terdapat Entity Relationship Model merupakan suatu model untuk menjelaskan hubungan antar data dalam basis data berdasarkan suatu persepsi bahwa real word terdiri dari objek-objek dasar yang mempunyai hubungan atau relasi antara objek-objek tersebut yang digambarkan dengan menggunakan simbol-simbol grafis tertentu. Semantic Model hampir sama dengan Entity Relationship model dimana relasi antara objek dasar tidak dinyatakan dengan simbol tetapi menggunakan kata-kata (Semantic).

Object Based Data Model dan Semantic Model dapat dilihat pada Gambar 2.3 dan 2.4 berikut ini.

![[Pasted image 20250209125252.png]]

##### 2.2.3.b Record based data model

Model ini mendasarkan pada record atau rekaman untuk menjelaskan kepada para pengguna tentang hubungan logis antar data dalam basis data.

Pada record based data model di samping digunakan untuk menguraikan struktur logika keseluruhan dari suatu basis data, juga digunakan untuk menguraikan implementasi dari system database. Terdapat 3 data model record-based, yaitu:

###### 1) Pertama, Relational model

Hubungan logis antar data dalam basis data dengan mempresentasikannya ke dalam bentuk tabel-tabel yang terdiri atas sejumlah baris yang menunjukkan record dan kolom yang menunjukkan atribut tertentu. Model ini banyak digunakan dalam pemodelan dan perancangan basis data. Hal ini dikarenakan konsep dan terminologi yang digunakan dalam model ini hampir sama dengan kondisi sesungguhnya yang dihadapi oleh para pengguna sehingga memudahkan para pengguna memahaminya.

![[Pasted image 20250209125354.png]]

Ketiga tabel tersebut saling berelasi yaitu tabel Supplier berelasi dengan tabel Pengiriman dengan atribut yang merelasikannya yaitu No_Sup.

Kemudian tabel Pengiriman berelasi dengan tabel Suku Cadang dengan atribut yang merelasikannya yaitu No_Part.


###### 2) Kedua, Hierarchical model.

Model data hierarki sering juga disebut tree structure yaitu menjelaskan hubungan logis antar data dalam basis data dalam bentuk hubungan bertingkat/hirarki. Elemen-elemen penyusunannya disebut sebagai node yang pada kenyataannya dapat berupa perincian data, agregat data, atau record. Level paling tinggi dalam suatu hirarki hanya terdapat satu node dan disebut root. 

Suatu node pada level yang lebih rendah hanya diizinkan mempunyai satu relasi dengan node pada yang lebih tinggi, yang disebut orang tua (parent). Kebalikannya orang tua dapat mempunyai lebih dari satu anak (child) yaitu node-node yang mempunyai level lebih rendah dan dihubungkan dengan orang tua. 

Suatu node yang tidak mempunyai anak disebut leaves. Simpul yang punya anak disebut akar, simpul yang tidak punya anak disebut daun. Hubungan antara orang tua dan anak disebut cabang, dimana data serta hubungan antar data direpresentasikan dengan record dan link (pointer), dimana record-record tersebut disusun dalam bentuk tree (pohon), dan setiap node pada tree tersebut merupakan record atau grup data elemen. 

Contoh model data hierarki dapat dilihat pada Gambar 2.5.

![[Pasted image 20250209125451.png]]

###### 3) Ketiga, Network Model

Model data jaringan juga sering disebut plex structure. Data dalam model jaringan direpresentasikan dengan sekumpulan record dan relasi antar data direpresentasikan oleh record dan link. Link dipandang sebagai pointer. Model ini hampir sama dengan model hierarki. Namun, perbedaannya pada model ini satu anak bisa mempunyai lebih dari 1 orang tua. Pada model jaringan, orang tua disebut pemilik dan anak disebut anggota.

Mirip dengan Hierarchical model, data dan hubungan antar data direpresentasikan dengan record dan links. Perbedaannya terletak pada susunan record dan linknya yaitu network model menyusun record-record dalam bentuk graph.

![[Pasted image 20250209125522.png]]


##### 2.2.3.c Physical based data model (Model data berbasis fisik)

Model ini mendasarkan pada teknis penyimpanan record atau rekaman dalam basis data bagaimana data disimpan dalam media penyimpanan secara fisik. Model data berbasis fisik ini terdiri dari 2 yaitu unifying model dan frame memory. 

Unifying model menggabungkan memori dan suatu transaksi basis data dalam kesatuan model. 

Sedangkan frame memory adalah sebuah virtual view dari sebuah tempat penyimpanan yang digunakan untuk mendukung record basis data.






---





# [[Kegiatan Belajar 2 - Relational Database Model dan Entity Relationship Diagram]]

Pada Kegiatan Belajar 2 ini akan di bahas materi mengenai relational database model dan entity relationship diagram. Seperti yang telah diketahui

pada materi sebelumnya, bahwa sebuah basis data merupakan kumpulan dari tabel yang saling berelasi antara satu dengan yang lainnya. Proses untuk merelasikan kumpulan tabel-tabel tersebut tentunya tidak mudah. Perlu adanya pemahaman khusus terkait dengan sistem yang akan dibangun dan konsep basis data.


## 03. Relational Database Model

Entity Relationship Model (ERM) adalah model konseptual tingkat tinggi pada proses perancangan basis data. Model data konseptual adalah himpunan konsep yang mendeskripsikan struktur basis data, transaksi pengambilan, dan pembaruan basis data. ERM merupakan suatu model data yang dikembangkan berdasarkan objek dan digunakan untuk menjelaskan hubungan antar data dalam basis data kepada pengguna secara logis. ERM didasari pada suatu persepsi bahwa real world (dunia nyata) terdiri atas objek-objek dasar yang mempunyai hubungan atau kerelasian antar objek-objek dasar tersebut. ERM digambarkan dalam bentuk diagram yang disebut Entity Relationship Diagram (ERD) dengan menggunakan simbol-simbol grafis tertentu.

ERD merupakan model konseptual yang dapat mendeskripsikan hubungan antar entity yang digunakan dan untuk memodelkan struktur data serta hubungan antar data. ERD digunakan untuk mendokumentasikan data institusi, lembaga, atau perusahaan dengan mengidentifikasi jenis entitas dan hubungannya. ERD juga menggambarkan hubungan antara satu entitas yang memiliki sejumlah atribut dengan entitas yang lain dalam suatu sistem yang terintegrasi. ERD digunakan oleh seorang perancang sistem untuk memodelkan data dari hasil analisis yang nantinya akan dikembangkan menjadi basis data.

#### 2.3.1 Diagram dan Komponen Model ER

ERD terbagi atas tiga komponen yaitu entitas (entity), atribut (attribute), dan relasi atau hubungan (relation). Secara garis besar entitas merupakan dasar yang terlibat dalam sistem. Atribut atau field berperan sebagai penjelas dari entitas, dan relasi yang menunjukkan hubungan yang terjadi antara dua entitas.

ERD merupakan model data konseptual, yang mempresentasikan data dalam suatu organisasi dalam bentuk objek-objek dan hubungannya. 

![[Pasted image 20250209125837.png]]

Sebagai contoh pada Gambar 2.7 dimana data pada dunia nyata akan direpresentasikan pada sebuah objek-objek ER.

Simbol yang digunakan dalam Entity Relationship Diagram (ERD) dapat dilihat pada Tabel 2.4 dibawah ini.

![[Pasted image 20250209125852.png]]


#### 2.3.2 Komponen Model ER

Konsep dasar atau komponen dari model ER terdiri dari Entitas, Atribut, dan Relationship seperti tampak pada Gambar 2.8 berikut ini:

![[Pasted image 20250209125925.png]]

##### 2.3.2.a Entitas (Entity) dan Himpunan Entitas (Entity Sets)

Entitas menunjukkan objek-objek dasar yang terkait di dalam sistem. Objek dasar dapat berupa orang, benda atau hal lain yang keterangannya perlu disimpan dalam basis data. Untuk menggambarkan entitas dilakukan dengan mengikuti aturan-aturan berikut:

1. ﻿﻿﻿Entitas dinyatakan dengan simbol empat persegi panjang.
2. ﻿﻿﻿Nama entitas berupa kata benda tunggal.
3. ﻿﻿﻿Nama entitas sedapat mungkin menggunakan nama yang mudah dipahami dan menyatakan maknanya dengan jelas.

Entitas merupakan individu yang mewakili sesuatu yang nyata (eksistensinya) dan dapat dibedakan dari sesuatu yang lain. Sebagai contoh sebuah kursi yang kita duduki, seseorang pegawai di sebuah perusahaan, dan sebuah mobil yang melintas di depan kita merupakan entitas. 

Sekelompok entitas yang sejenis dan berada dalam lingkup yang sama membentuk sebuah himpunan entitas (entity sets), secara sederhana entitas menunjuk pada individu suatu objek sedangkan himpunan entitas menunjuk pada rumpun (family). 

Contoh lain pada Gambar 2.9 yaitu sebuah entitas mahasiswa dan atributnya pada sistem informasi akademik perguruan tinggi.

![[Pasted image 20250209130011.png]]
Atribut yang melekat pada mahasiswa diantaranya NPM (Nomor Pokok Mahasiswa), NAMA, ALAMAT, KOTA, TGL_LHR, dan TELP. 

NPM merupakan primary key karena NPM merupakan kode unik setiap mahasiswa yang tidak dimiliki oleh mahasiswa lain.


##### 2.3.2.b Atribut (Attribute)

Atribut sering juga disebut properti, yaitu merupakan keterangan-keterangan yang terkait pada sebuah entitas yang perlu disimpan dalam basis data.

Atribut berfungsi sebagai penjelas dari sebuah entitas. Untuk menggambarkan atribut dilakukan dengan mengikuti aturan sebagai berikut:

4. ﻿﻿﻿Atribut dinyatakan dengan simbol elips
5. ﻿﻿﻿Nama atribut berupa kata benda tunggal
6. ﻿﻿﻿Nama atribut sedapat mungkin menggunakan nama yang mudah dipahami dan dapat menyatakan maknanya dengan jelas.
7. ﻿﻿﻿Atribut dihubungkan dengan entitas yang bersesuaian dengan menggunakan garis.

Jenis atribut antara lain:

###### a. Simple Attribute. (Atribut sederhana)

Simple Attribute (Atribut sederhana) adalah atribut yang bersifat atomik atau tidak dapat dipilah lagi, misalnya entitas Pegawai memiliki atribut Nama_peg. Seperti yang dapat dilihat pada Tabel 2.5.

![[Pasted image 20250209130117.png]]

###### b. Composite Attribute (Atribut Komposit)

Composite Attribute (Atribut Komposit) adalah atribut yang dapat dipecah menjadi atribut-atribut lain misalnya atribut Alamat_peg, didekompisikan menjadi Nama _jalan, Nama_kota, dan Kode_pos. 

Contohnya pada Gambar 2.10 berikut ini.

![[Pasted image 20250209130158.png]]


###### c. Single Value Attribute (Atribut Tunggal):

Single Value Attribute (Atribut Tunggal): adalah atribut yang memiliki satu nilai harga. Pada Gambar 2.11 yaitu entitas Mahasiswa memiliki atribut Single Value Attribute yaitu NIM, Nama_mhs, Tempat_lahir, dan Tg _lahir.

![[Pasted image 20250209130236.png]]

###### d. Multi Value Attribute

Multi Value Attribute adalah atribut yang memiliki banyak nilai harga, misalnya entitas Mahasiswa memiliki atribut Hobbi. Seperti pada Gambar 2.12 yaitu atribut Hobbi memiliki nilai yang lebih dari satu.

![[Pasted image 20250209130311.png]]

###### e. Mandatory Attribute

Mandatory Attribute adalah atribut harus bernilai artinya atribut tersebut harus berisi data, misalnya pada tabel Mahasiswa, NIM, Nama_mhs merupakan mandatory attribute karena setiap mahasiswa datanya disimpan ke dalam tabel dan harus diketahui NIM dan Nama_mhs tersebut artinya tidak boleh kosong (Not Null). 

Contohnya dapat dilihat pada Gambar 2.13 berikut ini.

![[Pasted image 20250209130407.png]]

###### f. Non-Mandatory Attribute

Non-Mandatory Attribute adalah atribut tidak bernilai artinya atribut tersebut nilainya boleh kosong, misalnya pada tabel Mahasiswa, Alamat_mhs, Tgl_lahir, dan Hobbi merupakan non-mandatory attribute karena boleh dikosongkan (Null). 

Gambar 2.14 merupakan contoh dari non-mandatory atribut.

![[Pasted image 20250209130432.png]]

#### 2.3.3 Relasi (Relationship) dan Himpunan Relasi (Relationship Sets)

Relasi atau hubungan adalah transaksi yang terjadi di antara dua entitas. Dalam transaksi tersebut terdapat keterangan yang perlu disimpan dalam basis data. Aturan penggambaran relasi antara entitas adalah:

8. ﻿﻿﻿Relasi dinyatakan dengan simbol belah ketupat.
9. ﻿﻿﻿Nama relasi dituliskan di dalam simbol belah ketupat.
10. ﻿﻿﻿Relasi menghubungkan dua entitas.
11. ﻿﻿﻿Nama relasi menggunakan kata kerja aktif (diawali awalan me) tunggal
12. ﻿﻿﻿Nama relasi sedapat mungkin menggunakan nama yang mudah dipahami dan dapat menyatakan maknanya dengan jelas.


##### Contoh 

Misalkan pada suatu perguruan tinggi dimana diketahui mata kuliah apa saja yang diambil oleh setiap mahasiswanya. Maka relasi yang terjadi antara entitas Mahasiswa dengan Mata kuliah adalah Mengambil. 

Dari pernyataan tersebut dapat digambarkan pada Gambar 2.15 sebagai berikut:

![[Pasted image 20250209130536.png]]

Gambar di atas menunjukkan relationship banyak (M) ke banyak (N) yang artinya setiap mahasiswa dapat mengambil satu atau lebih mata kuliah pada entitas mata kuliah dan setiap mata kuliah dapat diambil oleh satu atau lebih mahasiswa.

```
Misalnya, entitas seorang mahasiswa dengan
nim = '980001' dan
nama_mhs = 'Ali Akbar' (yang ada di himpunan entitas Mahasiswa)

mempunyai relasi dengan entitas sebuah mata kuliah dengan kode_kul='IF-110' dan nama_kul='Struktur Data'.

```

Kumpulan semua relasi di antara entitas-entitas yang terdapat pada himpunan-himpunan entitas tersebut membentuk himpunan relasi (relationship sets). Sebagaimana istilah himpunan entitas yang banyak sekali disingkat menjadi entitas, istilah himpunan relasi jarang sekali digunakan dan lebih sering disingkat dengan istilah relasi saja.

Beberapa istilah yang disepakati dalam Relasi dapat dilihat pada Tabel 2.6.

![[Pasted image 20250209130620.png]]

Berikut contoh tabel Supplier pada sebuah basis data.

![[Pasted image 20250209130639.png]]

Pada tabel Supllier tersebut, terdapat 3 atribut yaitu KD_SUPP, NAMA_SUPP, dan ALAMAT. Kemudian domain, baris, derajat (degree), dan relasi.

###### Kardinalitas/Derajat Relasi

Kardinalitas Relasi menunjukkan jumlah maksimum entitas yang dapat berelasi dengan entitas pada himpunan entitas yang lain. Kardinalitas relasi merujuk kepada hubungan maksimum yang terjadi dari himpunan entitas yang satu ke himpunan entitas yang lain dan begitu juga sebaliknya.

![[Pasted image 20250209130730.png]]

Kardinalitas di antara dua himpunan entitas misalnya entitas A dan entitas B dapat berupa:

1. Satu ke satu (one to one)
	Setiap entitas pada himpunan entitas A berhubungan dengan paling banyak dengan satu entitas pada himpunan entitas begitu juga sebaliknya setiap entitas pada himpunan entitas B berhubungan dengan paling banyak dengan satu entitas pada himpunan entitas A
	![[Pasted image 20250209130930.png]]
	Pada Gambar 2.18 entitas KARYAWAN dengan entitas JABATAN memiliki relasi menempati di mana derajat kardinalitasnya adalah satu ke satu.
	
	Artinya satu (1) KARYAWAN menempati satu (1) JABATAN. Atau bisa juga sebaliknya satu (1) JABATAN ditempati satu (1) KARYAWAN.

2. Satu ke banyak (one to many)
	Setiap entitas pada himpunan entitas A dapat berhubungan dengan banyak entitas pada himpunan entitas B, tetapi tidak sebaliknya, dimana setiap entitatas pada himpunan entitas B berhubungan dengan paling banyak dengan satu entitas pada himpunan entitas A.
	
	![[Pasted image 20250209131011.png]]
	Pada Gambar 2.19 entitas RUANG berelasi dengan entitas PASIEN dengan relasi menempati. Derajat kardinalitasnya adalah satu ke banyak. Jika dibaca maka menjadi satu (1) RUANG ditempati banyak (M) PASIEN. Atau bisa juga sebaliknya banyak (M) PASIEN menempati satu (1) RUANG.

3. Banyak ke Satu (Many to One)
	Setiap entitas pada himpunan entitas A berhubungan dengan paling banyak dengan satu entitas pada himpunan entitas B, tetapi tidak sebaliknya, dimana setiap entitas pada himpunan entitas A berhubungan dengan paling banyak satu entitas pada himpunan entitas B. 
	
	![[Pasted image 20250209131050.png]]
	Pada Gambar 2.20 entitas MAHASISWA berelasi dengan entitas DOSEN dengan derajat kardinalitas banyak ke satu. Cara membacanya adalah banyak MAHASISWA (M) diajarkan oleh satu (1) DOSEN. Atau bisa juga sebaliknya yaitu satu (1) DOSEN mengajarkan banyak (M) MAHASISWA.

4. Banyak ke Banyak (Many to Many)

	Setiap entitas pada himpunan entitas A dapat berhubungan dengan banyak entitas pada himpunan entitas B demikian juga sebaliknya, di mana setiap entitas pada himpunan entitas B dapat berhubungan dengan banyak entitas pada himpunan entitas A.
	
	![[Pasted image 20250209131136.png]]
	Pada Gambar 2.21 entitas CUSTOMER berelasi dengan entitas BARANG dengan derajat kardinalitas banyak ke banyak. Cara membacanya adalah banyak (M) CUSTOMER memesan banyak BARANG (N) atau banyak BARANG (N) dipesan banyak (M) CUSTOMER.





## 04. Menggambar Diagram Kerelasian antar Relasi (Relationship)

Dalam menggambar sebuah diagram ER terdapat langkah-langkah praktis yang dapat dilakukan. Langkah-langkah tersebut diantaranya sebagai berikut:

5. ﻿﻿﻿Tuliskan setiap relasi dan atribut pada setiap relasi dalam bentuk tabel satu kolom, di mana kepala tabel memuat nama relasi dan isi tabel memuat nama-nama atributnya.
6. ﻿﻿﻿Identifikasikan setiap atribut pada setiap entitas.
7. ﻿﻿﻿Identifikasikan setiap kerelasian berikut jenisnya yang terjadi di antara entitas.
8. ﻿﻿﻿Gambarkan simbol-simbol entitas, atribut, dan kerelasian antarentitas sehingga simbol kerelasian dapat digambarkan dengan jelas.
9. ﻿﻿﻿Gambarkan jenis kerelasian antar relasi dengan menggunakan tanda panah ganda untuk jenis banyak dan sebuah mata panah untuk jenis satu.
10. ﻿﻿﻿Cek entity relatioship diagram (ERD) yang terbentuk dalam kelengkapan entitas, atribut, kerelasian antar entitas, dan jenis kerelasian antar entitas.

Langkah 1.sd 6 tersebut dapat dilakukan ketika akan membuat sebuah entity relatioship diagram (ERD) dari awal sampai dengan akhir.

#### 2.4.1 Diagram Entity-Relationship (ER)

Penggambaran Model ER secara sistematis dilakukan melalui ERD. Notasi-notasi simbolik di dalam ERD yang dapat digunakan adalah:

11. Persegi panjang, menyatakan himpunan entitas.
12. Lingkaran/elips, menyatakan atribut (atribut yang berfungsi sebagai key digaris bawahi).
13. ﻿﻿﻿Belah ketupat, menyatakan himpunan relasi.
14. ﻿﻿﻿Garis, sebagai penghubung antara himpunan relasi dengan himpunan entitas dan himpunan entitas dengan atributnya.
15. ﻿﻿﻿Kardinalitas relasi dapat dinyatakan dengan banyaknya garis cabang atau dengan pemakaian angka (1 dan 1 untuk relasi one to one, 1 dan M untuk relasi one to many dan M untuk relasi many to many).







## 05. Tahapan Pembuatan Entity Relationship Diagram (ERD)

Entity relatioship diagram (ERD) selalu dibuat secara bertahap. Berikut adalah tahapan yang biasa ditempuh di dalam pembuatan ERD, yaitu:

16. ﻿﻿﻿mengidentifikasi dan menetapkan seluruh entity yang terlibat dalam sistem basis data tersebut.

17. ﻿﻿﻿menentukan attribute-attribute atau field dari masing-masing entity beserta kunci (key)-nya.  Menentukan attribute dari suatu entitas sangat menentukan baik atau tidaknya sistem basis data yang dirancang, karena attribute ini akan sangat menentukan dalam proses relasi nantinya. Attribute merupakan ciri khas yang melekat pada suatu entity, misalnya attribute pada mahasiswa dapat berupa nomor telepon genggam, nama, tempat lahir, tanggal lahir, alamat, nama orang tua, pekerjaan orang tua dan lain-lain. Dari sekian banyak kemungkinan attribute yang ada pada entity mahasiswa, kita dapat menggunakan hanya yang perlu saja. Setelah menentukan attribute-nya selanjutnya adalah menentukan field kunci. Field kunci adalah penanda attribute tersebut sehingga bisa digunakan untuk relasi nantinya dan field kunci ini harus bersifat unik. Misalnya pada entity mahasiswa, attribute nomor induk mahasiswa (NIM) bisa dijadikan field kunci karena bersifat unik dan tidak ada mahasiswa yang mempunyai NIM yang sama.

18. ﻿﻿﻿mengidentifkasi dan menetapkan seluruh himpunan relasi di antara himpunan-himpunan entity yang ada beserta kunci tamu (foreign key). Setelah menentukan entity dan attribute beserta field kuncinya, maka selanjutnya adalah menentukan entity yang terbentuk akibat adanya relasi antar-entity. Misalnya antara entity mahasiswa dengan entity dosen, terjadi suatu hubungan proses mengajar maka proses mengajar ini merupakan entity baru. Entity mengajar ini harus kita tentukan juga attribute yang melekat padanya beserta kunci tamu (foreign key). Kunci tamu adalah field kunci utama pada tabel lain dan field tersebut digunakan juga pada tabel yang satu lagi. Misalnya NIM adalah field kunci dari entity mahasiswa, pada entity mengajar terdapat juga attribute NIM, maka keberadaan attribute NIM pada entity mengajar disebut sebagai kunci tamu. Proses menentukan hubungan antar entitas juga sangat menentukan kualitas sistem basis data yang dirancang.

19. ﻿﻿﻿menentukan derajat relasi untuk setiap himpunan relasi. Setelah semua entitas dan atribut yang dibutuhkan terbentuk, maka selanjutnya adalah menentukan derajat relasi antar entitas tersebut, apakah satu ke satu, satu ke banyak atau sebaliknya, atau banyak ke banyak. Berhati-hatilah dalam menentukan derajat relasi ini karena nantinya akan berhubungan dengan proses pengambilan (query) terhadap data.

20. ﻿﻿﻿melengkapi himpunan entitas dan himpunan relasi dengan atribut-atribut deskriptif (non-key).


#### 2.5.1 Jenis-Jenis Kunci (Key)

Terdapat beberapa jenis kunci dalam sebuah tabel diantaranya super key, candidat key, primary key, foreign key, dan alternate key.

##### 2.5.1.a Super Key

Super-key merupakan satu atau lebih atribut (kumpulan atribut) yang dapat membedakan setiap baris data dalam sebuah tabel secara unik. Super key bisa terjadi pada lebih dari satu kumpulan atribut yang bersifat seperti itu di dalam sebuah tabel. Misalnya:

Di dalam tabel Mahasiswa, yang dapat menjadi super-key adalah:

- ﻿﻿(NIM, NamaMhs, AlamatMhs, TglLahirMhs)
- ﻿﻿(NIM, NamaMhs, AlamatMhs)
- ﻿﻿(NIM, NamaMhs)
- ﻿﻿(NamaMhs)
- ﻿﻿(NIM)

Dalam tabel tersebut terdapat NIM, NamaMhs, AlamatMhs, TglLahirMhs. Maka yang memungkinkan menjadi super key adalah NIM.

##### 2.5.1.b Candidat Key

Candidate Key adalah sebuah atribut atau lebih yang secara unit mengidentifikasi sebuah record. Atribut ini mempunyai nilai yang unik pada hampir setiap record-nya. 

Fungsi dari candidate key ini adalah sebagai calon primary key. Contoh candidate-key pada Gambar 2.22 berikut:

![[Pasted image 20250209131550.png]]

Pada Gambar 2.22 terdapat 4 atribut yaitu ID_Cus, Name, NoOfPay, dan Amount. Jika diperhatikan pada masing-masing baris terlihat unik karena tidak ada data yang sama. Oleh karena itu candidate key pada tabel tersebut adalah semua atribut yang ada.


##### 2.5.1.c Primary Key

Salah satu atrribut dari candidat key dapat dipilih menjadi primary key dengan 3 kriteria sebagai berikut:

21. ﻿﻿﻿Key tersebut lebih natural untuk dijadikan acuan
22. ﻿﻿﻿Key tersebut lebih sederhana
23. ﻿﻿﻿Key tersebut cukup unique  


Kembali ke Gambar 2.22 jika diperhatikan dari candidate key, maka primary key yang terpilih adalah ID_Cus karena ID_Cus yang paling unik diantara atribut yang lainnya.

##### 2.5.1.d Foreign Key

Jika sebuah primary key terhubung ke table atau entity lain, maka keberadaan primary key pada entity tersebut disebut sebagai foreign key. Misal Primary Key Kode_Dosen dari entity Dosen digunakan juga pada field entity KRS, maka keberadaan field Kode_Dosen pada entity KRS disebut sebagai foreign key.

##### 2.5.1.e Alternate Key

Setiap atribut dari candidate key yang tidak terpilih sebagai primary key akan dinamakan alternate key. Pada contoh sebelumnya bila untuk primary key dipilih ID_Cus maka alternate key nya adalah NoOfPay.

![[Pasted image 20250209131723.png]]

#### 2.5.2 Relational Integrity Rules

24. ﻿﻿﻿Null: suatu atribut yang tidak diketahui dan tidak cocok untuk baris (tuple) tersebut. Nilai (konstanta) Null digunakan untuk menyatakan atau mengisi atribut-atribut yang nilainya memang belum siap atau tidak ada.

25. ﻿﻿﻿Entity Integrity. Tidak ada satu komponen kunci primer yang bernilai null.

26. ﻿﻿﻿Referential Integrity. Suatu domain dapat dipakai sebagai kunci primer bila merupakan atribut tunggal pada domain yang bersangkutan.


#### 2.5.3 Kerelasian Antar-Relasi (Relationship)

27. ﻿﻿﻿Istilah kerelasian berbeda dengan istilah relasi. Relasi adalah sebuah tabel dalam basis data, sedangkan kerelasian menyatakan hubungan antar relasi dalam basis data.

28. ﻿﻿﻿Kerelasian antar relasi dapat dapat ditunjukkan oleh FK (Foreign Key) atau relasi-relasi bertipe transaksi yang digunakan dalam basis data.

29. ﻿﻿﻿Kerelasian antar relasi dapat ditunjukkan menggunakan sebuah diagram yang disebut Diagram Kerelasian Antar Relasi.



## 06. Varian Relasi

Relasi berfungsi menghubungkan antar entitas. Entitas yang berelasi tidak hanya terdiri dari dua relasi saja. Tetapi entitas bisa berelasi dengan dirinya sendiri atau berelasi lebih dari 2 entitas. Relasi ini dapat dikelompokkan menurut varian sebagai berikut:

#### 2.6.1 Unary Relation (Relasi Tunggal)

Relasi yang terjadi dari sebuah himpunan entitas ke himpunan entitas yang sama atau sering disebut sebagai relasi tunggal. Misalkan relasi yang terjadi pada pasien dan syarat. Relasi ini menunjukkan adanya persyaratan utama menjadi pasien rawat inap. Misalkan pasien tersebut hanya boleh mengikuti rawat inap bila telah terdaftar menjadi pasien rawat jalan.

![[Pasted image 20250209131900.png]]

Pada contoh relasi tunggal Gambar 2.25, hubungan yang ingin ditunjukkan adalah fakta tentang adanya dosen pendamping yang sudah senior bagi para dosen baru dalam rangka pembinaan profesi.

Setiap dosen senior bisa menjadi pendamping bagi beberapa dosen baru sekaligus. Sementara setiap dosen baru hanya dapat memiliki seorang dosen pendamping. Baik entitas dosen senior maupun entitas dosen baru ditempatkan di sebuah himpunan entitas dosen, sehingga relasinya terjadi pada sebuah himpunan entitas saja.

Pada contoh kedua, ditunjukkan pula relasi tunggal tetapi dengan derajat relasi banyak-ke-banyak. Relasi pada contoh ini menunjukkan adanya persyaratan pengambilan mata kuliah. Misalnya, mata kuliah 'Basis Data' hanya boleh diikuti jika telah lulus mata kuliah 'Struktur Data' dan 'Pemrograman'.

Derajat relasi banyak-ke-banyak menunjukkan bahwa yang menjadi prasyarat dalam pengambilan sebuah mata kuliah bisa saja lebih dari satu mata kuliah dan sebuah mata kuliah dapat menjadi prasyarat bagi beberapa mata kuliah yang lain.



#### 2.6.2 Binery Relation (Relasi Biner)

Relasi yang terjadi dari dua himpunan entitas. Relasi ini kerap terjadi dan paling banyak digunakan. Contoh relasi biner adalah relasi antara pasien dengan obat.

![[Pasted image 20250209131950.png]]

#### 2.6.3 Threenary Relation

Relasi yang terjadi dari hubungan 3 buah entitas. Contoh relasi ini adalah hubungan antara Pasien, Tindakan, dan Dokter.

![[Pasted image 20250209132023.png]]

#### 2.6.4 N-ary Relation (Relasi Multi Entity)

Relasi yang menghubungkan 3 (tiga) atau lebih entitas, dimasukkan dalam relasi multi entity. Bentuk relasi semacam ini sedapat mungkin dihindari karena akan mengaburkan derajat relasi yang ada dan juga akan menyebabkan desain database-nya semakin kompleks.

![[Pasted image 20250209132049.png]]

#### 2.6.5 Relasi Ganda (Redundant Relation)

Ada kalanya, relasi yang muncul antara dua himpunan entitas tidak hanya satu relasi, tetapi ada lebih dari satu relasi. Relasi itu disebut Relasi Ganda (Redundant Relation). Kita dapat mengambil contoh relasi antara himpunan entitas Dosen dan Kuliah, Relasi yang telah kita ketahui adalah 'Mengajar.

Namun, jika ada kebutuhan untuk mengakomodasi adanya fakta bahwa setiap Dosen juga memiliki kemampuan mengajar mata kuliah lain yang sudah ada pengajarnya. Dosen X telah ditetapkan untuk mengajar mata kuliah A dan dosen Y untuk mata kuliah B. Ada fakta bahwa dosen X tersebut juga berkemampuan untuk mengajar mata kuliah B dan mata kuliah C, begitu pula dosen Y yang sesungguhnya juga menguasai mata kuliah A. 

Jika fakta-fakta ini ingin diakomodasi juga, maka kita harus menyatakannya dalam relasi yang berbeda. Sehingga antara himpunan entitas Dosen dan Kuliah, terdapat lebih dari satu jenis relasi (relasi ganda) seperti digambarkan dalam Gambar 2.29 Diagram ER berikut ini (atribut-atribut untuk Dosen dan Kuliah sengaja tidak diperlihatkan):

![[Pasted image 20250209132140.png]]

Relasi Ganda tersebut memang perlu dibuat karena memang kebutuhan makna dari kedua relasi tersebut memang berbeda. Demikian juga dengan atribut-atribut relasi dan derajat relasinya. 

Tidak sebagaimana pada himpunan relasi Mengajar, himpunan relasi Menguasai hanya memiliki atribut key yang berasal dari himpunan entitas Dosen dan Kuliah, karena memang hanya untuk menunjukkan daftar mata kuliah yang dikuasai oleh setiap dosen (seorang dosen yang tidak mengajar mata kuliah tertentu tidak berarti dia tidak menguasai mata kuliah tersebut).

Sementara itu, derajat relasi banyak-ke-banyak (M-N) pada himpunan relasi Menguasai menunjukkan bahwa seorang dosen dapat mengusai banyak mata kuliah sekaligus dan begitu juga sebaliknya, setiap mata kuliah dapat dikuasai oleh lebih dari seorang dosen.



## 07. Relational Data Base Management

Relational Data Base Management disebut juga sebagai model relasi atau basis data relasional atau RDBM adalah model yang paling sederhana sehingga mudah digunakan dan dipahami oleh pengguna, serta merupakan model paling populer saat ini. 

Model relasi pertama kali dikenalkan oleh Codd pada tahun 1970 dan dilanjutkan oleh Chen (1976). Sejak itu model relasi memainkan peranan yang sangat penting dalam berbagai perancangan basis data. 

Model ER adalah persepsi terhadap dunia nyata sebagai terdiri objek-objek dasar yang disebut entitas dan keterhubungan (relationship) antar entitas-entitas itu.

#### 2.7.1 Model Relational

30. ﻿﻿﻿Model data yang menjelaskan hubungan antar data dalam basis data dengan memvisualisasikan ke dalam bentuk-bentuk tabel.

31. ﻿﻿﻿Model ini menggunakan sekumpulan tabel yang berdimensi dua (yang disebut relasi atau table) dengan masing-masing relasi tersusun atas tupel atau baris dan atribut.

32. ﻿﻿﻿Relasi dirancang sedemikian rupa sehingga dapat menghilangkan kemubaziran data dan menggunakan kunci (Key) untuk berhubungan dengan relasi atau tabel lain.

33. ﻿﻿﻿DBMS yang bermodelkan relasional biasa disebut RDBMS (Relational Database Management System)

Berikut ini adalah contoh tabel dan keterhubungannya:

![[Pasted image 20250209132328.png]]

![[Pasted image 20250209132337.png]]

Dari ketiga tabel tersebut, tabel mahasiswa berelasi dengan tabel Nilai dan tabel nilai berelasi dengan tabel Mahasiswa. NIM pada tabel Mahasiswa merupakan primary key berelasi dengan tabel nilai maka NIM pada tabel Nilai merupakan foreign key. Kemudian Kode_MK pada tabel Mata Kuliah merupakan primary key dan berelasi dengan tabel Nilai sehingga kode_mk pada tabel Nilai merupakan foreign key.

Ada tiga alasan mengapa model relasi mempunyai peranan penting dalam perancangan basis data yaitu :

34. ﻿﻿﻿Mempunyai piranti komunikasi yang baik antara user and designer artinya relasi merepresentasikan struktur data yang dapat dimengerti oleh user maupun designer.

35. ﻿﻿﻿Model relasional mendefinisikan salah satu kriteria perancangan basis data yang penting yaitu relasi bentuk normal.

36. ﻿﻿﻿Struktur data yang direpresentasikan oleh relasi dapat segera dikonversikan dan diimplementasikan ke RDBMS.


RDBM merupakan salah satu model yang paling banyak digunakan, hal ini karena konsep dan terminologi yang digunakan dalam model ini hampir sama dengan kondisi sesungguhnya yang dihadapi oleh pengguna. Software basis data yang tersedia di pasaran pun banyak yang dikembangkan berdasarkan model ini. 

Sebagai salah satu model, RDBM menjelaskan kepada pengguna tentang hubungan logis antar data dalam basis data dengan mempresentasikannya ke dalam bentuk relasi-relasi berupa tabel mendatar yang terdiri atas sejumlah baris yang menunjukan record dan kolom yang menunjukkan atribut tertentu.

Relasi dirancang sedemikian rupa sehingga dapat menghilangkan kerangkapan data yang tidak berguna. Dalam sebuah basis data, kerelasian antar relasi satu dengan yang lainnya ditunjukkan menggunakan Foreign Key (FK) atau relasi bertipe transaksi.




## 08. Entity Relationship Diagram


#### 2.8.1 Model Data Lanjutan

Model Data sebelumnya ditekankan pada pengenalan komponen-komponen dasar dalam kegiatan perancangan serta langkah-langkah teknis yang dapat dilakukan untuk mentransformasikan fakta di lapangan ke dalam sebuah model data. Bahasan ini akan mempelajari sejumlah varian komponen-komponen perancangan basis data serta proses-proses lanjutan terhadap perancangan dasar yang telah kita buat.

#### 2.8.2 Varian Entitas

Idealnya, himpunan entitas yang kita libatkan dalam sebuah Diagram ER adalah himpunan entitas yang kuat atau bebas (Strong Entity Sets). Yang dimaksud dengan himpunan entitas yang kuat atau bebas adalah:

37. ﻿﻿﻿Tidak memiliki ketergantungan dengan himpunan entitas lainnya atau dapat berdiri sendiri, contoh himpunan entitas mahasiswa, dosen, dan kuliah sebagaimana yang ditunjukkan di contoh sebelumnya.
38. ﻿﻿﻿Kemunculan entitas-entitas di dalamnya tidak tergantung pada keberadaan entitas di himpunan entitas yang lain.
39. ﻿﻿﻿Bukan merupakan bagian (sub) dari himpunan entitas yang lain.

Selain entitas yang kuat atau bebas dalam pembuatan Diagram ER juga ada yang disebut dengan entitas lemah. Dalam pembuatan Diagram ER tersebut tidak selalu dapat melibatkan himpunan entitas yang kuat atau bebas. 

Namun, ada kalanya melibatkan himpunan entitas yang lemah (Weak Entity Sets) atau merupakan bagian dari himpunan entitas lainnya (Subtype Entities).

#### 2.8.3 Himpunan Entitas Lemah (Weak Entity Sets)

Berikutnya himpunan entitas lemah (Weak Entity Sets) Himpunan Entitas Lemah memiliki karakteristik:

40. ﻿﻿﻿Entitas-entitas yang kemunculannya tergantung pada eksistensinya dalam sebuah relasi terhadap entitas lain (Strong Entity).

41. ﻿﻿﻿Himpunan entitas yang biasanya tidak memiliki atribut yang dapat berfungsi sebagai key yang benar-benar dapat menjamin keunikan entitas di dalamnya. Sebagai contoh, untuk melengkapi data mahasiswa kita juga ingin mengelola data Hobbi dan Orang tua.  

Berikut adalah contoh fakta yang dapat kita gunakan beserta relasi yang terjadi, berdasarkan buku Sistem Basis Data oleh Fathansyah (2015: 94-109)

![[Pasted image 20250209132559.png]]

Dengan fakta tersebut, dapat kita lihat bahwa entitas mahasiswa berelasi satu-ke-satu dengan entitas orang tua dan berelasi satu-ke-banyak dengan entitas Hobbi, sehingga kita dapat menggambarkan Diagram ER sebagai berikut:

![[Pasted image 20250209132617.png]]

Data Orang tua dan Hobbi di atas dapat digolongkan sebagai himpunan entitas lemah (yang dalam Diagram ER dinyatakan dengan kotak bergaris ganda), karena kemunculannya sangat tergantung pada adanya relasi dengan entitas yang ada pada himpunan entitas mahasiswa. 

Misalnya mahasiswa bernama 'Budi Haryanto' tidak ada dalam tabel mahasiswa maka orang tua bernama 'Siswono Handoyo' serta Hobbi 'membaca' juga ditiadakan. Kedua himpunan entitas Orang tua dan Hobbi juga tidak memiliki atribut sendiri yang dapat menjamin keunikan entitas-entitas didalamnya. 

Atribut nama_ortu dan Hobbi sengaja diberi garis bawah yang putus-putus untuk menunjukkan bahwa kedua atribut itu merupakan atribut key yang tidak meyakinkan. Jika ada mahasiswa yang bersaudara atau yang mempunyai Hobbi yang sama, maka entitas-entitas yang sama akan muncul pada himpunan entitas Orang tua atau Hobbi.


#### 2.8.4 Sub Entitas (Subtype Entities)

Sub Entitas adalah himpunan entitas yang beranggotakan entitas-entitas yang merupakan bagian dari himpunan entitas yang lebih superior atau utama. Sub Entitas ini merupakan hasil dekomposisi (spesialisasi) himpunan entitas berdasarkan pengelompokkan tertentu (penjelasan tentang Spesialisasi dapat dilihat di bagian berikutnya). Berikut adalah contoh Sub Entitas:

![[Pasted image 20250209132707.png]]

Dosen merupakan himpunan entitas superior. Dengan proses Spesialisasi (yang dilambangkan dengan adanya relasi khusus 'ISA') terhadap himpunan entitas ini, dapat dibentuk dua buah sub entitas 'Dosen Tetap' dan 'Dosen Tidak Tetap'. 

Konsekuensinya, entitas-entitas di kedua sub entitas juga merupakan berasal dari entitas-entitas yang ada pada himpunan entitas Dosen, namun tidak sebaliknya. Seperti halnya himpunan entitas lemah, sub entitas juga tidak memiliki atribut yang dapat menjamin keunikan entitas-entitas di dalamnya.





## 09. Spesialisasi dan Generalisasi

Proses spesialisasi yang ditekankan adalah perbedaan antar kelompok entitas, sedangkan dalam generalisasi yang ditekan adalah persamaannya.

Adanya spesialisasi dan generalisasi diwujudkan dalam notasi relasi khusus, yaitu "Is A". Spesialisasi adalah proses dari atas kebawah (top-down), yaitu merupakan proses mendefiniskan sekumpulan entitas khusus ke entitas yang bersifat umum. Sedangkan generalisasi adalah proses untuk mendefinisikan dari sekumpulan entitas yang lebih khusus, sehingga dapat dikatakan generalisasi adalah proses dari bawah ke atas (bottom-top).

Pada sebuah himpunan entitas dimungkinkan adanya pengelompokkan entitas-entitas yang menjadi anggotanya. Kadang-kadang ditemui, atribut-atribut yang melekat pada masing-masing kelompok tersebut tidak sepenuhnya sama. Sebagai contoh pada Gambar 2.33, entitas-entitas yang ada pada himpunan entitas Dosen dapat dibagi dalam dua kelompok, yaitu:

42. ﻿﻿﻿Dosen Tetap yang sekaligus merupakan karyawan atau pegawai di perguruan tinggi yang bersangkutan
43. ﻿﻿﻿Dosen Tidak Tetap yang telah menjadi karyawan atau pegawai di perguruan tinggi atau perusahaan lain.

Atribut-atribut yang ada pada himpunan entitas dosen kita perluas. Kelompok Dosen Tetap bisa memiliki atribut-atribut tambahan seperti nik, pangkat, dan tgl_masuk. Bagi kelompok Dosen Tidak Tetap atribut-atribut tersebut tidak relevan. Atribut-atribut tambahan yang relevan bagi kelompok Dosen Tidak Tetap adalah nama_kantor dan alamat_kantor yang menunjukkan lokasi tempat dosen bekerja secara permanen. Adanya pembedaan atribut ini menyebabkan entitas-entitas dosen tersebut tidak mungkin disatukan dalam sebuah himpunan entitas saja. Karena itu, pemisahan (spesialisasi) entitas bisa dilakukan.

#### 2.9.1 Spesialisasi

> Jika kita memulai dari sebuah himpunan entitas lalu kemudian melakukan pengelompokan yang melahirkan himpunan entitas baru (top- down), maka kita sedang melakukan **Spesialisasi**. 

![[Pasted image 20250209132944.png]]

#### 2.9.2 Generalisasi

> Bisa juga yang terjadi adalah sebaliknya. Kita mengetahui bahwa entitas-entitas dalam himpunan entitas mahasiswa sebenarnya dapat dibagi dalam dua kelompok, yaitu mahasiswa D-3 (Diploma-3) dan mahasiswa S-1 (Strata-1). Tetapi pengelompokan ini tidak dipertegas dengan adanya perbedaan atribut. Karena tidak tegasnya perbedaan atribut dari kedua kelompok, maka kelompok-kelompok entitas tersebut malah disatukan dalam sebuah himpunan entitas dengan atribut-atribut yang sama. Jadi, pendekatannya bersifat bottom-up, mula-mula terpisah tetapi kemudian menjadi satu. Proses yang demikian disebut **Generalisasi**.

![[Pasted image 20250209132954.png]]


Dengan demikian, Spesialisasi dan Generalisasi merupakan dua proses yang berlawanan. Perbedaan dari keduanya yaitu spesialisasi ditekankan pada perbedaan antar kelompok entitas, sedangkan dalam generalisasi yang ditekankan adalah persamaannya. Adanya Spesialisasi dan Generalisasi diwujudkan dalam notasi relasi yang khusus, yang disebut Relasi 'ISA' (yang berasal dari 'Is A') sebagai berikut:


![[Pasted image 20250209133010.png]]

Dalam perancangan basis data, spesialisasi umumnya akan terlihat secara eksplisit pada hasil akhir Diagram ER. Sedangkan proses Generalisasi, dengan pertimbangan simplifikasi (penyederhanaan), seringkali ditiadakan (tidak diperlihatkan secara eksplisit) pada hasil akhir Diagram ER.

Peniadaan generalisasi ini direpresentasikan dengan adanya atribut baru pada himpunan entitas akhir. Pada contoh di atas, dapat menambahkan atribut baru (program_studi yang nilainya 'D-3' atau 'S-1') ke dalam himpunan entitas Mahasiswa.





## 10. Agregasi

Dalam realitas kehidupan, banyak dijumpai adanya relasi secara kronologis menyaratkan telah adanya relasi lain. Dengan kata lain, sebuah relasi terbentuk tidak hanya dari entitas tapi juga mengandung unsur dari relasi lain. Fenomena demikian dapat diakomodasi dengan Agregasi.

Sebagai contoh berikut untuk menunjukkan adanya Agregasi. Seperti yang telah diketahui sebelumnya pada tabel 2.7, 2.8, dan 2.9 bahwa adanya relasi antara himpunan entitas mahasiswa dan himpunan entitas kuliah. 

Ada sejumlah mata kuliah yang membutuhkan kegiatan praktikum tapi tidak semua mata kuliah. Kegiatan praktikum ini tidak wajib diikuti oleh mahasiswa yang mengulang karena di semester sebelumnya tidak lulus.

Himpunan relasi 'Mengikuti' dalam Diagram ER berikut ini menunjukkan entitas Mahasiswa yang mengikuti kegiatan Praktikum tertentu karena telah mempelajari suatu mata kuliah yang memang membutuhkan kegiatan praktikum. Sebagai contoh pada Gambar 2.34 berikut:

![[Pasted image 20250209133108.png]]

Himpunan entitas Praktikum memiliki atribut-atribut dengan kode_pra sebagai key. Atribut key pada himpunan relasi 'Mengajar' merupakan foreign key di mana kode_pra berasal dari himpunan entitas Praktikum dan nim+kode_kul diambil dari himpunan relasi 'Mempelajari'. 

Perlu ditegaskan sekali lagi, nim dan kode_kul ini tidak secara langsung berasal dari himpunan entitas Mahasiswa dan Kuliah, karena yang ada di himpunan relasi 'Mengajar' hanyalah pasangan nim+kode_kul yang sudah ada di himpunan relasi Mempelajari. Karena itulah, ada faktor kronologis yang ingin ditunjukkan dengan adanya agregasi seperti di atas, di mana sebuah relasi 'Mengajar' hanya akan ada jika telah ada relasi lainnya 'Mempelajari' kuliah.

#### 2.10.1 Key Alternatif (Alternate Key)

Sebuah key dapat dikategorikan baik jika berukuran kecil dan sekuensial. Perhatikan Gambar 2.32 pada himpunan entitas Dosen mempunya 2 atribut yaitu Nama_dosen dan Alamat_dos. Nama_dosen dipilih sebagai key. Namun, pemilihan nama_dosen merupakan pemilihan key yang buruk karena selain panjang juga nilai-nilainya bebas dan tidak sepenuhnya dapat menjamin keunikan karena walaupun kecil kemungkinannya, bisa saja ada dua orang dosen atau lebih dengan nama dan gelar yang tepat sama.

Dengan pertimbangan itu, dapat saja menambahkan atribut baru, misalnya kode_dos, pada himpunan entitas dosen yang selanjutnya kita jadikan sebagai key untuk menggantikan nama_dos. Key semacam ini disebut Key Alternatif (Alternate Key).

Penggunaan atribut kode_dos ini tentu saja akan berdampak pada atribut-atribut di semua relasi yang berhubungan dengan entitas dosen. Berikut koreksi Diagram ER-nya yang sebelumnya pada Gambar 2.32 jikaatribut kode_dosen kita tambahkan dan sekaligus kita jadikan sebagai key pada himpunan entitas dosen.

![[Pasted image 20250209133204.png]]

Sepintas lalu adanya penambahan atribut kode_dos ini akan menyebabkan kebutuhan ruang penyimpanan yang lebih besar. Namun, hal itu tidak sepenuhnya benar. Memang di sisi himpunan entitas dosen akan terjadi penambahan kebutuhan ruang penyimpanan, tetapi di relasi mengajar justru akan terjadi pengurangan ruang penyimpanan yang sangat berarti karena ukuran data kode_dos akan jauh lebih kecil dibanding ukuran data nama_dos.

Sehingga jika relasi yang terjadi dengan melibatkan entitas dosen semakin banyak, maka penambahan atribut ini justru akan lebih efisien dari sisi kebutuhan ruang penyimpanan. Apalagi, kita juga akan memperoleh keuntungan yang lain, yaitu kecepatan akses data yang lebih baik karena memanfaatkan key yang lebih kecil ukurannya.


#### 2.10.2 Pengkodean Internal

Salah satu alasan mengapa kita menyatakan suatu data atribut dalam bentuk lain adalah untuk mengefisienkan ruang penyimpanan. Cara yang

ditempuh untuk menyatakan suatu data dalam bentuk lain itu adalah melalui pengkodean (data coding).

Ada 3 (tiga) bentuk pengkodean yang dapat kita pilih, yaitu:

44. ﻿﻿﻿Sekuensial. Pengkodean dilakukan dengan mengasosiasikan data dengan kode terurut biasanya berupa bilangan asli atau abjad, Misalnya data nilai mata kuliah ('Sempuma', 'Baik', 'Cukup', 'Kurang', 'Buruk') dikodekan dengan 'A', 'B', 'C', 'D' dan 'E'.

45. ﻿﻿﻿Mnemonic. Pengkodean dilakukan dengan membentuk suatu singkatan dari data yang ingin dikodekan, misalnya data jenis-kelamin ('Laki-laki' dan 'Perempuan') dikodekan dengan 'L' dan 'P'.

46. Blok. Pengkodean dinyatakan dalam format tertentu, misalnya data no _induk mahasiswa dengan format XXYYYY yang terbentuk atas XX = dua digit terakhir angka tahun masuk dan YYYY = no_urut mahasiswa.


Jika pada himpunan entitas mahasiswa kita juga ingin menyimpan data agama setiap mahasiswa,maka data agama ini dapat juga kita nyatakan dalam bentuk kode. Pemakaian kode ini membutuhkan adanya himpunan entitas baru yang akan menjadi referensi, untuk mendapatkan nilai data agama yang sesungguhnya.

![[Pasted image 20250209133257.png]]

#### 2.10.3 Dekomposisi Himpunan Entitas dan Normalisasi

Sebuah himpunan entitas yang ada dalam sebuah Diagram ER dapat kita dekomposisi menjadi beberapa himpunan entitas baru karena pertimbangan efisiensi ruang penyimpanan atau karena pertimbangan kemudahan dan kecepatan pengaksesan data. Upaya dekomposisi ini senantiasa akan menghasilkan satu himpunan entitas kuat (strong entity set) dan satu atau beberapa himpunan entitas lemah atau sub entitas.

Secara umum ada dua bentuk dekomposisi himpunan entitas, yaitu:

##### 2.10.3.a Dekomposisi atribut (dekomposisi vertikal)

Dekomposisi ini dilakukan dengan cara membagi sebuah himpunan entitas menjadi dua atau lebih dengan pemisahan atribut. Perhatikan Gambar 2.37 yaitu pembentukan himpunan entitas orang tua dengan men-dekomposisinya dari himpunan entitas mahasiswa yang lengkap tersebut dapat dilakukan dengan pertimbangan bahwa data nama_ortu dan alamat_ortu jarang sekali dibutuhkan atau diakses. Semakin kecil ukuran himpunan entitas maka semakin kecil pula ukuran ruang yang dibutuhkan pada waktu implementasi. Semakin kecil ukuran datanya, akan semakin cepat pula pengaksesan datanya.

Sementara dekomposisi dengan membentuk himpunan entitas hobbi dilakukan dengan alasan bahwa atribut hobbi merupakan atribut bernilai banyak (multivalued attribute) dan tidak selalu setiap entitas mahasiswa memiliki data hobbi. Pendekomposisian ini akan mengurangi redundansi data dan mengefisiensikan ruang penyimpanan yang nantinya dibutuhkan.

![[Pasted image 20250209133341.png]]

Sebagai hasil dekomposisi di atas, jumlah entitas Mahasiswa hasil dekomposisi akan sama dengan jumlah entitas sebelum dekomposisi. Sementara, jumlah entitas Orang-tua akan sama atau lebih kecil daripada jumlah entitas Mahasiswa.

##### 2.10.3.b Dekomposisi entitas (dekomposisi horizontal)

Dekomposisi ini dilakukan dengan cara membagi sebuah himpunan entitas menjadi dua atau lebih dengan pemisahan entitas. Contoh dekomposisi entitas yang dilakukan dengan melakukan spesialisasi yang dapat berbentuk seperti Gambar 2.38 dibawah ini:

![[Pasted image 20250209133427.png]]

Sebagai hasil dekomposisi di atas, jumlah entitas Dosen sebelum dekomposisi akan sama dengan jumlah entitas Dosen Tetap ditambah dengan jumlah entitas Dosen Tidak Tetap.


#### 2.10.4 Fleksibilitas

Fleksibilitas dalam desain basis data dapat direalisasikan dalam bentuk:

47. ﻿﻿﻿Penambahan atribut.
48. ﻿﻿﻿Pemilihan domain atribut yang lebih luas direalisasikan pada tahap implementasi.
49. ﻿﻿﻿Generalisasi.
50. ﻿﻿﻿Perubahan struktur entitas dari yang berorientasi kolom (column-oriented) menjadi berorientasi baris (row-oriented).

Perhatikan Gambar 2.39 dibawah ini yang merupakan fleksibilitas.

![[Pasted image 20250209133515.png]]

Pada Gambar 2.39 merupakan contoh fleksibilitas di mana penambahan atribut dan penambahan domain atribut terjadi pada 'mempelajari'. Kemudian diubah menjadi tabel-tabel yang akan dimplementasikan dalam basis data.

Gambar 2.40 berikut adalah contoh penerapan model ER yang dapat dituangkan kedalam Diagram - ER:

![[Pasted image 20250209133833.png]]


Model ER pada Gambar 2.40 merupakan model ER yang telah utuh dan siap diimplemetasikan kedalam sebuah basis data. Namun, sebelum diimplementasikan pada sebuah basis data, model ER tersebut harus diubah terlebih dahulu ke dalam bentuk tabel-tabel. Setelah diubah ke dalam tabel-tabel baru dapat diimplementasi ke dalam basis data menggunakan perangkat lunak misalnya MySQL, PotsgreeSQL, Oracle atau yang lainnya.








