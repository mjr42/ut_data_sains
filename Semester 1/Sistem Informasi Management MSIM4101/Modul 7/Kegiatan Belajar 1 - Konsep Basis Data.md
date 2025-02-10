---
tags:
  - sistem_informasi_management
  - materi_7_SIM
---
# Kegiatan Belajar 1 - Konsep Basis Data


## [[01. Definisi Basis Data]]

Basis data (database) merupakan kumpulan dari data yang saling berhubungan satu dengan yang lainnya, tersimpan di perangkat keras komputer, dan digunakan perangkat lunak untuk memanipulasinya.

Penerapan basis data dalam sistem informasi disebut dengan database system. Sistem basis data (database system) adalah suatu sistem informasi yang mengintegrasikan kumpulan dari data yang saling berhubungan satu dengan yang lainnya dan membuatnya tersedia untuk beberapa aplikasi yang bermacam-macam dalam suatu organisasi.

Dengan sistem basis data ini, tiap-tiap orang atau bagian dapat memandang basis data dari beberapa sudut pandangan yang berbeda. Bagian kredit dapat memandangnya sebagai data piutang. Bagian penjualan dapat memandangnya sebagai data penjualan. Bagian personalia dapat memandangnya sebagai data karyawan. Bagian penggajian dapat memandangnya sebagai data penggajian. Semuanya terintegrasi dalam sebuah data yang umum.

Berbeda dengan sistem pengolahan data tradisional (traditional data processing systems), sumber data ditangani sendiri-sendiri untuk tiap-tiap aplikasi.



## [[02. Pendekatan Tradisional dan Pendekatan basis Data]]

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



## [[03. Jenjang Data]]

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



## [[04. Tipe File]]

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



## [[05. File Secara Fisik dan File Secara logika]]

#### a. File Secara Fisik

File secara fisik menunjukkan bagaimana file tersebut secara fisik disusun dan disimpan di media simpanan luar, misalnya pita magnetis atau disk magnetis.

#### b. File secara logika

File secara logika menyangkut bagaimana hubungan antara data dipandang untuk menyediakan informasi kepada pemakai di basis data. Dalam meraneang suatu file, biasanya dirancang secara logika.

Tugas pengubahan dari file secara logika ke bentuk nyata secara fisik diselesaikan dengan suatu perangkat lunak.