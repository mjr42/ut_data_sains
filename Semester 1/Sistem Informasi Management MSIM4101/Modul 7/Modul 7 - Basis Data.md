---
tags:
  - sistem_informasi_management
  - materi_7_SIM
---
# [[Kegiatan Belajar 1 - Konsep Basis Data]]


## 01. Definisi Basis Data

Basis data (database) merupakan kumpulan dari data yang saling berhubungan satu dengan yang lainnya, tersimpan di perangkat keras komputer, dan digunakan perangkat lunak untuk memanipulasinya.

Penerapan basis data dalam sistem informasi disebut dengan database system. Sistem basis data (database system) adalah suatu sistem informasi yang mengintegrasikan kumpulan dari data yang saling berhubungan satu dengan yang lainnya dan membuatnya tersedia untuk beberapa aplikasi yang bermacam-macam dalam suatu organisasi.

Dengan sistem basis data ini, tiap-tiap orang atau bagian dapat memandang basis data dari beberapa sudut pandangan yang berbeda. Bagian kredit dapat memandangnya sebagai data piutang. Bagian penjualan dapat memandangnya sebagai data penjualan. Bagian personalia dapat memandangnya sebagai data karyawan. Bagian penggajian dapat memandangnya sebagai data penggajian. Semuanya terintegrasi dalam sebuah data yang umum.

Berbeda dengan sistem pengolahan data tradisional (traditional data processing systems), sumber data ditangani sendiri-sendiri untuk tiap-tiap aplikasi.



## 02. Pendekatan Tradisional dan Pendekatan basis Data

Pendekatan tradisional mengumpulkan data ke dalam file-file yang tidak berhubungan satu dengan yang lainnya. Biasanya, tiap-tiap file dirancang untuk aplikasi yang tertentu.

![[Pasted image 20241027191124.png]]

Pendekatan tradisional ini mempunyai beberapa kelemahan sebagai berikut.

##### 1. Terjadi Duplikasi Data (data redundancy)

Oleh karena tiap-tiap aplikasi membentuk file data tersendiri, hal itu akan dapat menimbulkan duplikasi data yang sama. Misalnya, dua buah file, yaitu file karyawan dan file data gaji sebagai berikut.

![[Pasted image 20241027191158.png]]

Kedua file tersebut, yaitu file data karyawan digunakan untuk aplikasi personalia, sedangkan file data gaji digunakan untuk aplikasi penggajian yang berisi beberapa item data yang sama sehingga terjadi duplikasi. Akibat lebih lanjut dari duplikasi data ini adalah

1. ﻿﻿﻿modifikasi dari data yang duplikat harus dilakukan untuk beberapa file sehingga kurang efisien;
2. ﻿﻿﻿pemborosan tempat simpanan luar.

##### 2. Tidak terjadi hubungan data (data reliability)

Karena tiap-tiap aplikasi menyelenggarakan file tersendiri,hubungan data ke file di aplikasi yang lain tidak ada. Misalnya, aplikasi penjualan menyelenggarakan file data penjualan dengan struktur sebagai berikut.

![[Pasted image 20241027191420.png]]

Apabila pada aplikasi ini diinginkan laporan penjualan yang menampilkan nama salesman yang menjual,hal itu tidak dapat dilakukan karena data salesman tersebut tidak terdapat dalam file penjualan. Sebenarnya, data salesman tersebut ada di file personalia. Disebabkan hubungan data untuk aplikasi lain tidak dapat dilakukan, terpaksa data salesman juga harus dimasukkan dalam file penjualan.Akibatnya, terjadi duplikasi data.

![[Pasted image 20241027191430.png]]

#### 3. Pendekatan Basis Data

Pendekatan basis data mencoba memperbaiki kelemahan-kelemahan yang terjadi

di pendekatan tradisional sebagai berikut.

1. ﻿﻿﻿**Duplikasi data (data redundancy) dikurangi**  
    Karena basis data merupakan kumpulan dari semua data secara umum, hal itudapat digunakan bersama-sama untuk semua aplikasi sehingga duplikasi data dapat dikurangi.

2. ﻿﻿﻿**Hubungan data (data reliability) dapat ditingkatkan**  
    Karena data dikumpulkan bersama-sama,hubungan dari data dapat ditingkatkan yang berarti data di file tertentu dapat dihubungkan dengan data di file-file lainnya.



## 03. Jenjang Data

Sampai dengan membentuk suatu basis data, data mempunyai jenjang, mulai dari karakter-karakter (characters), item data (data item atau field), record, file, kemudian basis data. Jenjang ini dapat digambarkan sebagai berikut.

![[Pasted image 20241027191709.png]]

#### 1. Karakter - Karakter

Karakter-karakter merupakan bagian data yang terkecil, dapat berupa karakter numerik, huruf, ataupun karakter-karakter khusus (special characters) yang membentuk suatu item data.

#### 2. Field

Suatu field menggambarkan suatu atribut dari record yang menunjukkan suatu item dari data, misalnya nama dan alamat. Kumpulan dari field membentuk suatu record. Ada tiga hal yang penting dalam suatu field sebagai berikut.

1. Nama dari field (field name)
   Field harus diberi nama untuk membedakan field yang satu dengan field yang lainnya.
   
2. Representasi dari field (field representation)
   Representasi dari field menunjukkan tipe dari field (field type) serta lebar dari field (field width). Field dapat bertipe numerik ataupun huruf. Lebar dari field menunjukkan ruang maksimum dari field yang dapat diisi dengan karakter-karakter data.
   
3. Nilai dari field (field value)
   Nilai dari field menunjukkan isi dari field untuk masing-masing record.

#### 3. Record

Kumpulan dari field membentuk suatu record. Record menggambarkan suatu unit data individu tertentu. Kumpulan dari record membentuk suatu file. Misalnya, file personalia, tiap-tiap record dapat mewakili data tiap-tiap karyawan.

#### 4. File

File terdiri atas beberapa record yang menggambarkan satu kesatuan data yang sejenis. Misalnya, file mata kuliah berisi data tentang semua mata kuliah yang ada.

#### 5. Basis data

Kumpulan dari file membentuk suatu basis data.

![[Pasted image 20241027191933.png]]



## 04. Tipe File

File dalam pemrosesan aplikasi dapat dikategorikan dalam beberapa tipe, tergantung dari kegunaannya. Perhatikan berikut ini.

#### 1. File Induk (Master File)

Dalam aplikasi, file ini merupakan file yang penting karena berisi beberapa record yang sangat perlu dalam organisasi. File ini akan tetap terus ada selama hidup dari sistem. File induk dapat dikategorikan lagi menjadi berikut.

1. File induk acuan (reference master file), yaitu file induk yang record-nya relatif statis, jarang berubah nilainya. Misalnya, file daftar gaji atau file daftar mata kuliah.

2. File induk dinamis (dynamic master file), yaitu file induk yang nilai dari record-recordnya sering berubah atau sering dimutakhirkan (updated) sebagai hasil dari suatu transaksi. Misalnya, file induk data barang yang setiap saat field unitnya harus dimutakhirkan apabila terjadi transaksi.

#### 2. File Transaksi (Transaction File)

File transaksi disebut juga dengan nama input file. File ini digunakan untuk merekam data hasil dari transaksi yang terjadi. Contoh dari file transaksi adalah file penjualan yang berisi data hasil transaksi penjualan.

#### 3. File Laporan (report file)

File ini disebut juga dengan nama output file, yaitu file yang berisi informasi yang akan ditampilkan. Isi dari file ini biasanya diambilkan dari field di satu atau lebih masterfile untuk mempersiapkan pembuatan laporan.

#### 4. File sejarah (history file)

File sejarah (history file) disebut juga dengan nama file arsip (archival file) merupakan file yang berisi data masa lalu yang sudah tidak aktif lagi, tetapi masih disimpan sebagai arsip.

#### 5. File pelindung (back up file)

File pelindung merupakan salinan dari file-file yang masih aktif dalam basis data pada suatu saat tertentu. File ini digunakan sebagai pelindung atau cadangan apabila file basis data yang aktif mengalami kerusakan atau hilang.



## 05. File Secara Fisik dan File Secara logika

#### a. File Secara Fisik

File secara fisik menunjukkan bagaimana file tersebut secara fisik disusun dan disimpan di media simpanan luar, misalnya pita magnetis atau disk magnetis.

#### b. File secara logika

File secara logika menyangkut bagaimana hubungan antara data dipandang untuk menyediakan informasi kepada pemakai di basis data. Dalam meraneang suatu file, biasanya dirancang secara logika.

Tugas pengubahan dari file secara logika ke bentuk nyata secara fisik diselesaikan dengan suatu perangkat lunak.



---



# [[Kegiatan Belajar 2 - Organisasi file]]

Organisasi file secara tradisional dapat berupa :

- organisasi file urut (sequential file), 
- file urut berindeks (indexed sequential file) atau sering disebut juga dengan indexed sequential access method (ISAM) dan 
- file akses langsung (direct access file) atau disebut juga dengan file alamat langsung (direct address file).

Organisasi filebasis data mencoba meningkatkan struktur dari data supaya integrasi data antara satu file dan file yang lainnya lebih meningkat dengan menunjukkan hubungan dari data yang satu dengan data yang lainnya dalam file yang lain. Organisasi filebasis data dapat berbentuk :

- struktur data berjenjang (hierarchical data structure), 
- struktur data jaringan (network data structure) dan 
- struktur data hubungan (relational data structure).

Data yang sudah direkam dengan pendekatan basis data dengan struktur data hubungan (relational data structure), selanjutnya dapat diakses dengan mudah oleh pemakai sistem informasi. Paket yang mulai banyak digunakan untuk mengakses basis data ini disebut dengan DMS (database management system).



## 06. Organisasi file Tradisional

Organisasi file dihubungkan dengan pengaturan dari record dalam file secara fisik pada media simpanan luar. 

File dapat diorganisasikan secara urut (sequential organization) atau secara acak (random organization). Pengaksesan file dihubungkan dengan prosedur atau metode yang digunakan untuk mengakses record dari media simpanannya.

Pengaksesan file dapat dilakukan secara urut (sequential access) atau secara langsung (direct access). Walaupun organisasi file dan pengaksesan file dapat dipandang secara terpisah, biasanya pembahasan mengenai organisasi file menyangkut keduanya seperti berikut.

1. File urut (sequential file) merupakan file dengan organisasi urut (sequential organization) dan dengan pengaksesan secara urut (sequential access).

2. File urut berindeks (indexed sequential file) atau sering disebut juga dengan indexed sequential access method (ISAM) merupakan file dengan organisasi urut (sequential organization) dan dengan pengaksesan secara langsung (direct access).
   
3. File akses langsung (direct access file) atau disebut juga dengan file alamat langsung (direct address file) merupakan file dengan organisasi acak (random organization) dan dengan pengaksesan secara langsung (direct access).

Organisasi file seperti ini disebut dengan organisasi file tradisional atau konvensional. Disebut demikian karena telah ada sebelum struktur basis data dikembangkan.

#### 1. Organisasi File Urut

Dalam organisasi file urut, tiap-tiap record disimpan dengan urutan yang sudah tertentu. File urut ini kadang-kadang disebut juga sebagai file datar (flat file) karena tidak memberikan hubungan record yang berjenjang. Urutan dari record-record dalam file urut biasanya dipilih dari salah satu field yang ada dan yang disebut dengan field kunci (key field).

![[Pasted image 20241027192943.png]]

Record dalam file urut diakses secara urut, yaitu dibaca mulai dari record pertama saecara urut sampau dengan record yang diinginkan. Apabila ada record baru yang akan ditambahkan, harus disiapkan pada posisi sesuai dengan urutan keyfield-nya dalam file. File urut dapat disimpan di media simpanan luar SASD (misalnya pita magnetis) ataupun DASD (misalnya disk magnetis)


#### 2. Organisasi File Urut Berindex

Dengan organisasi file berurut berindex, reciord diatur secara urut pada media DASD. Untuk pengaksesannya secara langsung, tabel-tabel index perlu dibuat untuk tujuan menunjukan alamat dari masing masing record yang akan di akses. Sering kali tidak hanya sebuah tabel indeks yang dibuat, tetapi dapat lebih dari sebuah tabel indeks secara berjenjang untuk mempercepat pencarian

![[Pasted image 20241027193440.png]]

Pengaksesan data pada file urut berindeks ini dilakukan dengan mencarinya terlebih dahulu di file indeks. Misalnya, kode dosen "089" akan diakses. Pertama kali indeks dicari pada file indeks secara urut. Kode dosen "089" berada di antara kode dosen "055" dan kode dosen "100" yang berarti pada file urut terdapat di antara record dengan alamat relatif 06 dan alamat relatif 10. Kontrol kemudian dipindahkan ke alamat relatif 06 pada file urut dan dilakukan pencarian secara urut, mulai dari alamat relatif 06 sampai dengan alamat relatif 10.

#### 3. Organisasi File Akses Langsung

Dalam organisasi file akses langsung, record diletakkan tanpa memandang urutannya. Tiap-tiap record di DASD terletak pada alamat tertentu. Tiap-tiap record dapat diakses tanpa harus membaca dari record pertama, tetapi dapat langsung menuju pada record yang dimaksud. Hal ini dimungkinkan karena alamat dari record yang dikehendaki dapat ditentukan terlebih dahulu. Dua buah cara dapat dipergunakan untuk menentukan alamat dari record yang dikehendaki sebagai berikut.

##### a. Direct conversion

Dengan cara konversi langsung (direct conversion), setiap nilai dari field kunci menunjukkan secara langsung alamat di media simpanan luar yang berisi record bersangkutan. 

Sebagai contoh, suatu disk mempunyai 40 track dan tiap-tiap track terdiri atas delapan sector. Misalnya, tiap sector dalam track dapat menyimpan data sebanyak 10 record. Berarti tiap track dapat menyimpan data sebanyak 8 x 10 record = 80 record (tiap track terdiri atas delapan sector). Suatu record dengan nilai kunci field-nya adalah 1832 dapat terletak pada alamat berikut.

![[Pasted image 20241027193711.png]]

##### b. Hashing method

Metode hashing disebut juga dengan randomizing method, algorithm method, atau transformation method.

Dengan metode ini, nilai dari field kunci ditransformasikan menggunakan operasi algoritma matematika supaya didapatkan alamat fisik dari record. Cara yang paling banyak dilakukan dalam metode ini adalah membagi nilai field kunci dengan suatu bilangan prima. Bilangan prima yang digunakan adalah bilangan prima terdekat dari jumlah record yang akan dialamati.

Permasalahan dalam metode hashing adalah adanya nilai field kunci yang kembar sehingga alamatnya juga sama. Masalah ini disebut dengan collision. Untuk mengatasi hal ini, dapat disediakan lokasi tambahan di disk untuk menampung record dengan nilai field kunci yang sama.

Sebagai contoh, jumlah record yang akan dialamati adalah sebanyak delapan buah record. Untuk menampung collision, disediakan lokasi tambahan, misalnya diambil sebesar 40%, berarti sebanyak 12 lokasi yang harus disediakan.



## 07. Organisasi File Basis Data

Organisasi data secara konvensional dirasakan kurang mengena lagi karena berorientasi pada file. Itu artinya data cenderung hanya berhubungan dengan data yang lainnya dalam satu file, kurang ada hubungan dengan data lain yang berada di file lain. Sebagai akibatnya, integrasi data dengan file yang lainnya kurang dan sulit. Menyadari hal ini mulai dikembangkan metode-metode baru untuk organisasi file yang lebih baik, yang kemudian dikenal dengan organisasi filebasis data.

Organisasi filebasis data ini mencoba meningkatkan struktur dari data supaya integrasi data antara satu file dan file yang lainnya lebih meningkat dengan menunjukkan hubungan dari data yang satu dengan data yang lainnya dalam file yang lain.

Berikutnya dikembangkan suatu struktur data yang baru, yaitu struktur data berjenjang (hierarchical data structure) dan struktur data jaringan (network data structure).

Struktur data jaringan kemudian distandardisasikan pada tahun 1971 oleh Data Base Task Group (DBTG) yang merupakan panitia dari COmmittee on DAta SYstem Languages (CODASYL). Struktur data jaringan ini sekarang dikenal dengan nama model DBTG. Juga pada tahun 1970 dan 1971, muncul dua buah paper oleh E.F. Codd yang mendefinisikan struktur data yang lain, yaitu struktur data hubungan (relational data structure).


#### 1. Struktur Data Berjenjang

Struktur data berjenjang (hierarchical data structure) atau disebut juga dengan nama struktur data pohon (tree data structure) menunjukkan hubungan antara data membentuk suatu jenjang, seperti pohon.

Suatu pohon dibentuk dari beberapa elemen grup data yang berjenjang yang disebut dengan node. Node yang paling atas atau level 1 disebut dengan akar (root). Tiap-tiap node dapat bercabang ke node-node yang lain. Data yang diwakili dengan struktur pohon ini harus memenuhi dua kondisi sebagai berikut.

- a. Pohon hanya mempunyai sebuah root saja.

- b. Tiap-tiap node, kecuali root hanya dapat mempunyai sebuah orang tua, tetapi tiap-tiap node dapat mempunyai beberapa anak.

![[Pasted image 20241027194548.png]]

Keterangan

1. ﻿﻿﻿Node 1 adalah root dan merupakan orang tua dari (parent of) node 2, 3, dan 4.
   
2. ﻿﻿﻿Node 2, 3, dan 4 adalah node level 2 yang merupakan anak dari (children of) node. Node 2 adalah orang tua dari (parent of) node 5 dan 6. Node 4 adalah orang tua dari node 7, 8, dan 9.
   
4. Node 5 dan 6 adalah node level 3 dan merupakan anak dari (children of) node 2.
   
5. Node 7, 8, dan 9 adalah node level 3 dan merupakan anak dari node 4.

Contoh dari suatu struktur pohon adalah struktur data suatu fakultas sebagai berikut.

![[Pasted image 20241027194638.png]]

Hubungan dari satu node ke node lain dapat berupa hubungan 
1. satu-ke-satu (one-to-one), 
2. hubungan satu-ke-banyak (one-to-many), 
3. hubungan banyak-ke-banyak (many-to-many).

Hubungan data antara fakultas dengan tenaga nonedukatif, dosen, dan mahasiswa adalah hubungan satu-ke-banyak (one-to-many). Satu fakultas ini mempunyai beberapa tenaga nonedukatif, beberapa dosen, dan beberapa mahasiswa. Seorang tenaga nonedukatif mengalami beberapa kali perubahan jabatan, berarti hubungannya adalah satu-ke-banyak. Tiap-tiap dosen mengalami beberapa kali kenaikan pangkat dan mengajar beberapa kelas. Sebuah kelas hanya diajar oleh seorang dosen, tetapi seorang dosen dapat mengajar beberapa kelas sehingga hubungannya adalah satu-ke-banyak.

Ketika tiap-tiap kelas mempunyai lebih dari seorang dosen yang mengajar, itu berarti hubungannya adalah banyak-ke-banyak (many-to-many). Demikian juga dengan tiap-tiap mahasiswa mempunyai beberapa nilai untuk mata kuliah yang sudah ditempuhnya, itu berarti hubungannya juga satu-ke-banyak.


#### 2. Struktur Data Jaringan

Struktur data jaringan (network data structure) disebut juga dengan complex data structure. Kalau struktur data pohon tiap-tiap node tidak dapat mempunyai lebih dari satu orang tua; pada struktur data jaringan ini, tiap-tiap node dapat mempunyai lebih dari satu orang tua.

![[Pasted image 20241027194854.png]]

#### 3. Struktur Data Hubungan

Struktur data hubungan (relational data structure) mempunyai dua karakteristik sebagai berikut.

a. File dalam bentuk tabel yang persis dengan file urut.

b. Hubungan antara record didasarkan pada nilai dari field kunci, bukan berdasarkan alamat atau pointerdalam record seperti pada struktur data pohon dan jaringan.


Maksud utama dari model struktur data hubungan ini adalah meletakkan semua hubungan data dalam bentuk tabel dua dimensi. Data dalam model ini dapat diidentifikasi dalam hubungan nyata terhadap item data yang ada dalam record.

Ini merupakan keuntungan yang penting dibandingkan dengan model berjenjang atau model jaringan. Lebih lanjut akan lebih mudah bagi mereka yang akan merancang basis data menggunakan model hubungan. Akibatnya, model hubungan ini banyak dipergunakan dan dikembangkan mulai dari komputer-komputer mikro sampai dengan komputer besar.

Seperti telah disebutkan bahwa model hubungan ini menggunakan tabel dua dimensi yang menggambarkan hubungan antara data. Kolom dari tabel menunjukkan atribut (attribute) dari file. Atribut ini menunjukkan item-item data atau field. Masing-masing baris dari record dalam tabel basis data disebut dengan tuple.

![[Pasted image 20241027195035.png]]

Supaya tidak selalu menggambarkan file data dalam bentuk tabel,dapat diwakili dengan suatu notasi sebagai berikut.

![[Pasted image 20241027195049.png]]

DATA_DOSEN merupakan nama dari file basis datanya dan elemen-elemen dalam tanda kurang merupakan nama-nama dari atribut atau field. Dalam istilah relational, kumpulan dari atribut disebut dengan domain. Atribut dalam domain yang digarisbawahi menunjukkan field kunci (key field).




## 08. Basis Data Management Sistem

Data base management system (DBMS atau DMS) adalah paket perangkat lunak yang kompleks digunakan untuk memanipulasi basis data.

Banyak sekali paket DBMS yang telah beredar. Untuk memilih paket mana yang tepat untuk digunakan, ada beberapa kriteria yang harus diikuti.

Kriteria-kriteria paket DBMS yang baik, di antaranya: 
1. harus mudah digunakan, 
2. kemampuan membuka file pada suatu saat secara serentak, 
3. kecepatan pengolahannya, 
4. kemampuan memodifikasi struktur data, 
5. kemampuan indexing, 
6. mempunyai query language, 
7. kemampuan hubungan dengan file yang lain, 
8. harga dari paket tersebut, serta 
9. dukungan purna jual apabila ada versi yang lebih baru.



## 09. Data Base Administrator

Database administrator (DBA) adalah orang yang bertanggung jawab terhadap penanganan basis data dalam suatu organisasi. Umumnya, DBA bertanggung jawab terhadap area-area berikut.

1. Perancangan dan koordinasi secara keseluruhan dari database.
   
2. Mengembangkan skema.
   
3. Bertanggung jawab terhadap keamanan dari basis data.
   
4. Menentukan organisasi dari data.
   
5. Membuat dokumentasi sistem dan penggunaannya.
   
6. Menjadi penengah antara pemakai dan manajemen.
   
7. Melatih dan mendidik personel yang berhubungan dengan basis data.
   
8. Bertanggung jawab terhadap seluruh operasi dari sistem dasar data.
   
9. Penerapan terhadap DBMS.
   
10. Pengetesan dan pemeliharaan dari sistem basis data.
    
11. Menerapkan prosedur darurat dalam kasus terjadinya kegagalan sistem atau kerusakan basis data.
