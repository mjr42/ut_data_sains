---
tags:
  - basis_data
  - materi_2_BD
---

# Kegiatan Belajar 1 - Model Database dan Model Data

Pada Kegiatan Belajar 1 ini kita akan membahas Model Database dan Model Data, jika diamati dalam kehidupan sehari-hari, model database dan model data sebenarnya sudah tidak asing lagi. Misalnya ketika melakukan perjalanan menggunakan kereta api maka mulai dari pemesanan tiket, keberangkatan, sampai tiba di tujuan sebenarnya terdapat model database dan model data. 

Contoh lain adalah ketika kuliah di Perguruan Tinggi, mulai dari proses pendaftaran menjadi mahasiswa, pembayaran uang perkuliahan, melaksanakan perkuliahan, sampai dengan lulus perkuliahan itu juga sudah terdapat model database dan model data.


## [[01. Model Database]]

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





## [[02. Model Data]]

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

	4. ﻿﻿﻿Hierarchycal model.
	5. ﻿﻿﻿Network model.
	6. ﻿﻿﻿Relational model.

6. Physical based data model (Model data berbasis fisik), terdiri atas

	7. ﻿﻿﻿Unifying model.
	8. ﻿﻿﻿Frame memory.


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






