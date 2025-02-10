---
tags:
  - basis_data
  - materi_1_BD
---
# [[Kegiatan Belajar 1 - Basis Data]]

Pada tahun 60-an, perkembangan tempat penyimpanan data masih dilakukan secara manual dan belum dikenal apa yang dinamakan basis data. Seluruh tempat penyimpanan disimpan dalam bentuk fisik sehingga dokumen yang tersimpan dirasakan belum optimal baik dari sisi tempat penyimpanan maupun dalam hal pencarian data. Seiring dengan perkembangan teknologi banyak perangkat lunak yang dikembangkan untuk menyimpan atau mengolah data secara elektronik seperti Microsoft Excel atau Apache Open Office Calc. 

Namun jika datanya berukuran besar maka diperlukan sebuah tempat penyimpanan data yang terintegrasi supaya penyimpanan dan pengolahan data menjadi lebih maksimal. Selanjutnya data yang tersimpan tersebut dapat diolah untuk menghasilkan informasi secara tepat, akurat, dan bermanfaat. 

Selain itu, dapat mempercepat upaya pelayanan kepada pelanggan dan membantu pengambilan keputusan atas suatu masalah berdasarkan informasi yang ada yang berasal dari basis data. 

Kehadiran basis data juga dapat meningkatkan kinerja dan daya saing sebuah organisasi.



## 01. Latar Belakang

Diperlukannya basis data dalam suatu perusahaan, pada dasarnya adalah untuk kemudahan dan kecepatan dalam pengambilan data. Untuk lebih jelasnya dapat dilihat pada Gambar 1.1 dan Gambar 1.2.

![[Pasted image 20250209084514.png]]

![[Pasted image 20250209084525.png]]

Dari gambar tersebut, terlihat perbedaan antara basis data dan lemari arsip di mana setiap rak dalam lemari tersebut dapat menyimpan dokumen-dokumen manual yang terdiri dari lembaran-lembaran kertas.

Masalah yang dihadapi pada lemari arsip adalah kelambatan dalam proses penelusuran data pada lemari arsip tersebut.

Misalkan ingin mencari arsip untuk pegawai tertentu. Untuk menemukan hasilnya, akan membutuhkan waktu yang lama. Hal ini disebabkan proses pencarian harus mencari lembaran-lembaran yang ada pada dokumen tersebut dan dapat menyebabkan waktu pencarian yang kurang efisien.

Berikut adalah beberapa alasan mengapa sebuah organisasi atau perusahaan memerlukan sebuah basis data, diantaranya:

#### 1.1.1 Membantu Pengelolaan Data yang Besar

Basis data dapat menyimpan dan membantu mengelola data dalam jumlah yang besar secara rinci dan terintegrasi. Hal ini sangat tidak mungkin jika menggunakan Perangkat lunak spreadsheet seperti Microsoft Excel atau Apache OpenOffice Calc karena kapasitas penyimpanan dan kecepatan mengolah data dalam Microsoft Excel dan Apache OpenOffice sangat terbatas.

#### 1.1.2 Akurasi Data

Sebuah basis data secara umum dapat menjamin akurasi data. Hal tersebut dikarenakan basis data memiliki fitur constraints dan default value check. Constrains adalah aturan-aturan di dalam tabel basis data yang dapat mencegah penghapusan atau perubahan data dari suatu tabel karena data dalam tabel tersebut mempunyai keterkaitan dengan data pada tabel lain.

Sedangkan default value check adalah proses cek jika data yang dimasukkan ke dalam basis data tidak mempunyai nilai (null) maka nilai default yang akan digunakan.

#### 1.1.3 Mudah dalam Proses Manipulasi Data

Sebuah perangkat lunak basis data, memiliki fitur yang dapat memudahkan dalam melakukan proses manipulasi data (proses insert/update/delete). Salah satunya dengan menggunakan Data Manipulation Languages (DML) yang termasuk ke dalam Structured Query Language (SQL).

#### 1.1.4 Keamanan Data

Perangkat lunak basis data memiliki fitur keamanan. Hal tersebut bertujuan untuk menjaga data dari hal-hal yang tidak diinginkan. Sebagai contoh misalnya sebelum pengguna mendapatkan data yang diinginkan, pengguna harus melakukan login terlebih dahulu, sehingga data lebih aman.

#### 1.1.5 Integritas Data

Sebuah basis data dapat menjamin integritas data. Karena basis data memiliki fitur constrains, maka integritas data dalam basis data dapat terjamin. Sebagai contoh jika terjadi perubahan data di dalam Tabel A, maka tabel yang memiliki keterkaitan dengan Tabel A akan mengikuti perubahan tersebut atau basis data akan mencegah perubahan pada Tabel A jika diatur demikian.

Demikian juga untuk proses penambahan data maupun penghapusan data. Dengan adanya hal tersebut integritas data dapat terjamin.



## 02. Pengertian Basis Data

Berbicara tentang basis data dapat diartikan bahwa seluruh data yang disimpan dalam sebuah basis data ditempatkan pada masing-masing table/file sesuai dengan fungsinya. Dengan tersimpannya data dalam basis data tersebut, maka akan dengan mudah dapat melakukan penelusuran data yang diinginkan sehingga berdampak pada waktu pencarian yang lebih efisien.

Di dalam suatu media penyimpanan (misalnya harddisk), dapat ditempatkan lebih dari 1(satu) basis data secara elektronik. Namun, tidak semua bentuk penyimpanan data yang disimpan secara elektronik dikatakan basis data karena ketika menyimpan dokumen di dalam sebuah harddisk, harddisk tersebut dapat berisi data file teks dari program pengolahan kata, spreadsheet, dan lainnya.

Yang ditekankan dalam basis data adalah pengaturan, pemilahan, pengelompokan, dan pengorganisasian data yang disimpan sesuai dengan fungsinya. Hal tersebut bisa berbentuk sejumlah file, table terpisah, atau dalam bentuk pendefinisian kolom (field) data dalam setiap file atau table tersebut.

#### 1.2.1 Pengertian Basis Data

Basis Data berasal dari kata Basis dan Data. Adapun pengertian dari kedua kata tersebut adalah sebagai berikut:

1. Basis dapat diartikan sebagai markas atau gudang atau tempat bersarang atau tempat berkumpul.

2. Data dapat diartikan sebagai representasi fakta dunia nyata yang mewakili suatu objek seperti manusia (pegawai, siswa, pembeli, dan pelanggan), barang, hewan, peristiwa, konsep, keadaan, dan sebagainya. Objek tersebut direkam dalam bentuk angka, huruf, simbol, teks, gambar, bunyi, atau kombinasinya.


##### 1.2.1a Basis Data Sebagai Satu Kesatuan

Basis Data sebagai satu kesatuan dapat didefinisikan sebagai berikut.

1. ﻿﻿﻿Himpunan kelompok data yang saling berhubungan dan terorganisasi dengan baik agar kelak dapat dimanfaatkan kembali dengan cepat dan mudah.

2. ﻿﻿﻿Kumpulan data yang saling berhubungan dan disimpan dengan baik secara bersama-sama tanpa pengulangan (redudansi) yang tidak diperlukan.

3. ﻿﻿﻿Kumpulan file, tabel, atau arsip yang saling berhubungan dan disimpan dalam satu media penyimpanan elektronik. Kumpulan file ini selanjutnya disebut Tabel (Table) sebagai komponen utama untuk membangun basis data. (Fathahansyah, 2015)

Dalam beberapa literatur, basis data telah didefinisikan dengan cara yang berbeda. Salah satu definisi yang cukup lengkap dan baik tentang istilah basis data adalah yang diberikan oleh James Martin (1975) dalam buku Sistem Basis Data (Edhy Sutanta, 2004, h. 17) sebagai berikut:

> "A database may be defined as a collection of interrelated data stored together without harmful or unnecessary redundancy to serve one or more application in an optimal fashion; the data are stored so that they are independent of programs its used the data; a common and controlled approach its used in adding new data and in modifying and retrieving exiting data whithin the database".


Basis Data dapat dipahami sebagai suatu kumpulan data terhubung yang disimpan secara bersama-sama pada suatu media.

Walaupun disimpan secara bersama-sama dan saling terhubung, kumpulan data tersebut tersimpan tanpa saling tumpang tindih satu sama lain atau tidak terjadi kerangkapan data. Namun, jika pun terjadi kerangkapan data maka kerangkapan data tersebut harus terjadi seminimal mungkin dan dapat terkontrol. Beberapa kondisi data di dalam suatu basis data diantaranya:

4. ﻿﻿﻿data disimpan dengan cara-cara tertentu sehingga memudahkan ketika akan digunakan atau ditampilkan kembali.

5. ﻿﻿﻿data dapat digunakan oleh satu atau beberapa program aplikasi secara optimal.

6. ﻿﻿﻿data disimpan tanpa mengalami ketergantungan dengan program-program yang akan menggunakannya.

7. ﻿﻿﻿data disimpan sedemikian rupa sehingga proses penambahan, pengambilan, dan modifikasi data dapat dilakukan dengan mudah dan terkontrol.


##### 1.2.1b Kriteria Basis Data

Dari definisi tersebut dapat disimpulkan bahwa pengertian basis data adalah koleksi terpadu dari data yang saling berkaitan dan dirancang untuk memenuhi kebutuhan informasi suatu organisasi. Masing-masing table/file di dalam basis data tersebut berfungsi untuk menampung atau menyimpan data dimana data-data tersebut saling berhubungan dengan satu dengan yang lain.

Dari pengertian tersebut dapat dikatakan bahwa basis data memiliki beberapa kriteria penting antara lain:

8. ﻿﻿﻿beorientasi pada data.

9. ﻿﻿﻿data dapat digunakan oleh pemakai yang berbeda-beda atau beberapa program aplikasi tanpa perlu mengubah basis data.

10. ﻿﻿﻿data dalam basis data dapat berkembang dengan mudah baik volume maupun strukturnya.

11. ﻿﻿﻿data yang ada dapat memenuhi kebutuhan sistem-sistem baru secara mudah.

12. ﻿﻿﻿data dapat digunakan dengan cara yang berbeda-beda.

13. ﻿﻿﻿kerangkapan data minimal.





## 03. Manfaat dan Tujuan Basis Data

Manfaat basis data adalah untuk pengelolaan data dalam memudahkan atau menemukan kembali data yang dicari dengan cepat.

Tujuan Basis Data antara lain sebagai berikut:

14. ﻿﻿﻿**Kecepatan dan kemudahan (Speed)**. Dengan basis data dapat menyimpan data atau melakukan perubahan, penghapusan, penambahan, dan pemanggilan kembali data yang tersimpam dengan cepat dan mudah.

15. ﻿﻿﻿**Efisiensi ruang penyimpanan (Space)**. Dengan basis data penggunaan ruang penyimpanan data dapat dilakukan dengan melakukan meminimalisasi jumlah pengulangan data dan dengan menerapkan sejumlah pengkodean.

16. ﻿﻿﻿**Keakuratan (Accuracy)**. Dengan memanfaatkan pengkodean atau pembentukan relasi antar data, penerapan aturan atau batasan tipe data dapat diterapkan dalam basis data yang berguna untuk menentukan keakuratan saat input data atau penyimpanan data.

17. ﻿﻿﻿**Keamanan (Security)**. Sejumlah sistem (aplikasi) pengelolaan basis data tidak menerapkan aspek keamanan dalam penggunaannya. Akan tetapi, untuk sistem yang besar dan serius, aspek keamanan menjadi hal yang penting untuk diterapkan. Dengan begitu, sistem dapat menentukan siapa yang boleh menggunakan basis data dan menentukan jenis operasi-operasi apa saja yang boleh dilakukan.

18. ﻿﻿﻿**Terpeliharanya keselarasan data (Consistent)**. Apabila ada perubahan data pada aplikasi yang berbeda, secara otomatis perubahan itu berlaku untuk keseluruhan.

19. ﻿﻿﻿**Kebersamaan pemakaian (Sharebility)**. Data dapat dipakai secara bersama-sama oleh beberapa program aplikasi saat bersamaan.

20. ﻿﻿﻿**Dapat diterapkan standarisasi (Standardization)**. Dengan adanya pengontrolan yang terpusat, basis data dapat menerapkan standarisasi data yang disimpan sehingga memudahkan pemakaian, distribusi, maupun pertukaran data.

21. ﻿﻿﻿**Ketersediaan (Availability)**. Basis data dapat memilah data utama atau master, transaksi, data history hingga data kedaluwarsa. Data yang jarang atau tidak digunakan lagi dapat diatur untuk dipisahkan dari sistem basis data yang aktif.

22. ﻿﻿﻿**Kelengkapan (Completeness)**. Kelengkapan sebuah data bersifat relatif, dalam sebuah basis data penilaian kelengkapan data sangat bergantung pada pengguna sehingga penilaian tidak selalu sama.


## 04. Kelebihan dan Kekurangan Basis Data

#### 1.4.1 Kelebihan

23. ﻿﻿﻿**Dapat meningkatkan kemandirian data**. Sebuah basis data dapat digunakan untuk bermacam-macam program aplikasi tanpa harus mengubah format data yang sudah ada.

24. ﻿﻿﻿**Konsistensi data**. Konsistensi data di dalam basis data dilakukan dengan cara data disimpan hanya sekali dalam basis data sehingga jika terjadi perubahan pada nilai data tersebut, perubahan hanya dilakukan satu kali dan nilai baru tersebut akan tersedia untuk semua pengguna.

25. ﻿﻿﻿**Meningkatkan aksesibilitas terhadap data dan respon yang lebih baik.** Dengan basis data maka aksesibilitas data dan respon akan lebih baik. Hal tersebut dapat dicapai dengan integrasi data yang melewati batasan-batasan departemen dalam organisasi sehingga data dapat langsung diakses oleh pengguna.

26. ﻿﻿﻿**Pengendalian terhadap kerangkapan data**. Data dalam sebuah basis data dilakukan penyimpanan dengan cara disimpan satu kali. Hal ini mengurangi kerangkapan data dan mengurangi biaya untuk tempat penyimpanan.

27. ﻿﻿﻿**Meningkatkan keamanan data**. Keamanan basis data dapat melindungi basis data dari pengguna yang tidak memiliki otorisasi. Basis data dapat menentukan batasan-batasan pengaksesan data, misalnya dengan memberikan password dan pemberian hak akses bagi pemakai (misalnya untuk hak akses dalam proses update, delete, insert, maupun select).

28. ﻿﻿﻿**Memperbaiki integritas data.** Intergritas data mengacu pada validitas dan konsistensi dari data yang disimpan. Integritas biasanya diekspresikan dalam batasan (constraints) yang merupakan aturan yang konsisten dan tidak dapat dilanggar. Jika kerangkapan data dapat dikontrol dan kekonsistenan data dapat dijaga, maka data menjadi akurat.

29. ﻿﻿﻿**Data dapat dipakai secara bersama-sama.** Data yang ada pada basis data menjadi milik seluruh organisasi dan dapat dipakai secara bersama oleh pengguna yang berwenang pada saat bersamaan.

30. ﻿﻿﻿**Memperoleh lebih banyak informasi dari data yang sama.** Pengguna basis data dapat memperoleh informasi selain dari informasi rutin yang dikelolanya karena semua data lain berada dalam basis data yang sama. Dengan demikian, kebutuhan akan informasi selain dari informasi rutin dapat terpenuhi.


#### 1.4.2 Kekurangan

31. ﻿﻿﻿**Biayanya dapat menjadi sangat maha**l karena menyangkut biaya-biaya untuk pembelian sekaligus perawatan hardware dan software. Selain itu, terdapat juga biaya tambahan untuk untuk penyimpanan (storage), jaringan (network), dan lain-lain.

32. ﻿﻿﻿**Rumit**. Perancang, pengembang, Data Base Administator (DBA), dan pengguna akhir harus memahami secara rinci dan mendalam tentang fungsi basis data yang ditangani agar dapat mengambil manfaat dari basis data. Kegagalan dalam memanfaatkannya dapat menyebabkan kerugian yang cukup besar bagi organisasi atau perusahaan.

33. ﻿﻿﻿**Tambahan biaya konversi**. Diperlukan biaya yang besar untuk berpindah dari aplikasi atau sistem yang lama ke dalam sistem basis data yang baru.  Selain itu, diperlukan pula biaya untuk pelatihan staf dalam menggunakan sistem yang baru ini serta tambahan biaya untuk mempekerjakan staf khusus seperti DBA, dan lain-lain.






## 05. Tingkatan Data dalam Database Relasi

Dalam suatu sistem database relasi, data yang tersimpan dalam DBMS mempunyai tingkatan-tingkatannya, sebagaimana tampak dalam Gambar 1.3 berikut.

![[Pasted image 20250209085534.png]]

#### 1.5.1. ﻿﻿﻿Karakter (character)  

Merupakan bagian terkecil dalam database, dapat berupa karakter numerik (angka 0 s.d 9), huruf (A - Z, a - Z) ataupun karakter-karakter khusus, seperti *, &. %, # dan lain-lain.

#### 1.5.2. ﻿﻿﻿Field atau Attribute  
Merupakan bagian dari record yang menunjukkan suatu item data yang sejenis, misalnya field nama, field NIM, dan lain sebagainya. Setiap field harus mempunyai nama dan tipe data tertentu. Isi dari field disebut Data Value. Dalam table dari sebuah database, field ini disebut juga kolom.

#### 1.5.3. ﻿﻿﻿Record atau Tupple  
Tuple/Record adalah kumpulan data value dari attribute yang berkaitan sehingga dapat menjelaskan sebuah entity secara lengkap. Misal record entity mahasiswa adalah kumpulan data value dari field nomor telepon genggam, nama, jurusan, dan alamat per-barisnya. Dalam database, record disebut juga baris.

#### 1.5.4. ﻿﻿﻿Table/Entity  

Entity merupakan sesuatu yang dapat diidentifikasi dari suatu sistem database, bisa berupa objek, orang, tempat, kejadian, atau konsep yang informasinya akan disimpan di database. Misalnya pada sistem database akademik, yang menjadi entity adalah mahasiswa, dosen, mata kuliah, dan  lain-lain. Dalam aplikasinya, penggunaan istilah entity sering disamakan dengan istilah tabel (entity = table). Disebut table karena dalam  merepresentasikan datanya diatur dalam bentuk baris dan kolom. Baris mewakili 1 record dan kolom mewakili 1 field. Kemudian dalam sistem database tradisional, entity atau table ini disebut juga dengan file.  

Ada beberapa sifat yang melekat pada suatu tabel yaitu:

34. ﻿﻿﻿Tidak boleh ada record yang sama atau kembar.
35. ﻿﻿﻿Urutan record tidak terlalu penting karena data dalam record dapat diurutkan sesuai dengan kebutuhan.
36. ﻿﻿﻿Setiap field harus mepunyai nama yang unik atau tidak boleh ada yang sama.
37. ﻿﻿﻿Setiap field mesti mempunyai tipe data dan karakteristik tertentu.




## 06. Operasi Dasar Basis Data

Sebagai sebuah tempat penyimpan, data dalam basis data dapat dibuat, diubah atau dihapus. Berikut adalah operasi-operasi dasar terhadap basis data, antara lain:

#### 1.6.1 Pembuatan Basis Data Baru

Pembuatan basis data baru `(CREATE DATABASE)`. Pembuatan basis data baru identik dengan pembuatan lemari arsip yang baru. Sebagai contoh jika akan membuat database ` RUMAHSAKIT ` , maka perintah SQL nya adalah:

```
CREATE DATABASE RUMAHSAKIT;
```

#### 1.6.2 Penghapusan Basis Data Baru

Penghapusan basis data ``(DROP DATABASE)``. Penghapusan basis data identik dengan penghapusan seluruh lemari arsip sekaligus beserta isinya jika ada. Sebagai contoh terdapat sebuah basis data rumah sakit beserta tabel-tabel di dalamnya seperti tabel ``PASIEN``, `DOKTER`, `TRANSAKSI` dan lain-lain. Maka perintah SQL untuk menghapus basis data `RUMAHSAKIT` tersebut adalah:

```
DROP DATABASE RUMAHSAKIT;
```


#### 1.6.3 Pembuatan Tabel Baru ke Suatu Basis Data

Pembuatan tabel baru ke suatu basis data `(CREATE TABLE)`. Pembuatan tabel baru identik dengan penambahan kotak arsip baru ke sebuah lemari arsip yang telah ada. Misalnya dalam sebuah basis data `RUMAHSAKIT`, yang sudah ada akan ditambahkan sebuah tabel baru bernama tabel `PASIEN`. Maka perintah SQL nya adalah:

```
CREATE TABLE PASIEN (  
   PasienID int,  
   LastName varchar (255), 
   FirstName varchar (255), 
   Address varchar (255),  
   City varchar(255)
);
```


#### 1.6.4 Penghapusan Tabel dari Suatu Basis Data

Penghapusan tabel dan suatu basis data (DROP TABLE). Penghapusan tabel identik dengan penghapusan kotak arsip lama yang ada di sebuah lemari arsip besrta isinya jika ada. Misal akan dihapus tabel PASIEN dalam basis data RUMAHSAKIT maka contoh perintah SQL dalam penghapusan tabel adalah:

```
DROP TABLE PASIEN;
```


#### 1.6.5 Penambahan atau Pengisian Data Baru ke Tabel

Penambahan atau pengisian data baru ke sebuah tabel di sebuah basis data `(INSERT)`. Misalnya akan diisi data pada tabel `PASIEN` dengan nilai data PasienID: 1, LastName: Suryadi, FirstName: Andri, Address: Jalan Pondok Cabe, City: Tangerang Selatan. Maka contoh SQL penambahan data tersebut ke dalam sebuah tabel `PASIEN` adalah:

```
INSERT INTO PASIEN (PasienID, LastName, FirstName, Address, City)
VALUES (1, 'Suryadi', 'Andri', 'Jalan Pondok Cabe', "Tangerang Selatan' );
```


#### 1.6.6 Pengambilan Data dari Suatu Tabel

Pengambilan data dari sebuah tabel `(SELECT)`. Pengambilan data dari basis data identik dengan pencarian lembaran arsip pada sebuah kotak arsip dari sebuah basis data. Kumpulan data di dalam tabel akan ditampilkan di sebuah layar komputer. Sebagai contoh akan menampilkan data pasien dari tabel `PASIEN` maka contoh SQL-nya adalah:

```
SELECT * FROM PASIEN;
```

#### 1.6.7 Perubahan atau Manipulasi Data pada Tabel

Perubahan atau manipulasi data dari sebuah tabel `(UPDATE)`. Pengubahan atau manipulasi identik dengan perbaikan isi lembaran arsip yang ada sebuah kotak arsip pada sebuah basis data. Sebagai contoh data pasien dengan, `PASIENID=1` akan diubah alamatnya dari Jalan Pondok Cabe menjadi JI Pondok Cabe maka SQL nya adalah:

```
UPDATE PASIEN
SET Address = 'Jl Pondok Cabe'
WHERE PasienID=1;
```


#### 1.6.8 Penghapusan Data dan Sebuah Tabel

Penghapusan data dan sebuah tabel `(DELETE)`. Penghapusan data identik dengan penghapusan sebuah lembaran arsip di sebuah kotak arsip yang ada di sebuah basis data. Misalnya akan menghapus pasien dengan `PasienID = 1` maka SQL nya adalah:

```
DELETE FROM PASIEN WHERE PasienID=1
```

Pada operasi yang berkenaan dengan pembuatan objek basis data, operasi awal hanya dilakukan sekali dan berlaku seterusnya. Operasi-operasi yang berkaitan dengan isi tabel (data) merupakan operasi rutin yang akan berlangsung secara berulang-ulang dan karena itu operasi-operasi inilah yang lebih tepat mewakili aktivitas pengelolaan (management) dan pengolahan (processing) data dalam basis data. 

Operasi-operasi basis data yang telah dijelaskan diatas akan dipelajari secara rinci pada pembahasan di Modul 5 tentang Structured Query Language (SQL) dan Modul 6 tentang Praktikum SQL.




## 07. Penerapan Basis Data

Basis data dapat diterapkan dan dimanfaatkan hampir di semua bidang dalam sebuah institusi, baik di lingkungan pemerintah maupun di lingkungan usaha swasta. Untuk meningkatkan efesiensi dan menunjang operasional perusahaan dalam mengelola sistem informasi, digunakanlah basis data. Basis data merupakan salah satu komponen utama dalam setiap sistem informasi. 

Tidak ada sistem informasi yang bisa dibuat atau dijalankan tanpa adanya basis data.

#### 1.7.1 Pemanfaatan Basis Data

Beberapa adalah contoh pemanfaatan basis data:

38. Untuk menunjang akurasi, efisiensi, dan kecepatan operasi antara lain:
	1. ﻿﻿﻿Kepegawaian: untuk berbagai perusahaan yang memiliki banyak pegawai.
	2. ﻿﻿﻿Pergudangan (inventory): untuk perusahaan manufaktur (pabrikan), grosir (reseller), apotik, dan lain-lain.
	3. ﻿﻿﻿Akuntansi: untuk berbagai perusahaan.
	4. ﻿﻿﻿Reservasi: untuk hotel, pesawat, kereta api, dan lain-lain.
	5. ﻿﻿﻿Layanan Pelanggan (customer care): untuk perusahaan yang berhubungan dengan banyak pelanggan (bank, konsultan, dan lain-lain)

39. Sebagai komponen sistem informasi dalam organisasi atau perusahaan antara lain:
	6. ﻿﻿﻿Sistem Informasi Akademis. Dalam sistem informasi akademis, terdapat berbagai proses diantaranya penjadwalan kuliah, penjadwalan dosen, pencatatan absensi mahasiswa, pencatatan absensi dosen, penjadwalan ujian, dan pendataan nilai mahasiswa. Seluruh proses tersebut akan melakukan penyimpanan data dalam basis data. Petugas akademis dapat mengetahui jadwal kuliah tertentu dengan mengakses basis data melalui query jadwal kuliah yang terdapat pada sistem informasi. Selain itu, jika dosen menanyakan jadwal mengajar pada petugas akademis, petugas tersebut akan mengakses basis data melalui menu transaksi jadwal dosen pada sistem informasi akademis tersebut.
	7. ﻿﻿﻿Sistem Informasi Tabungan. Pada sistem ini terdapat beberapa proses, antara lain pendataan nasabah, pembukaan rekening, penyetoran uang, penarikan uang, perhitungan bunga, pencetakan buku tabungan, transfer, dan penutupan rekening. Layanan pelanggan akan mendata nasabah jika nasabah itu akan membuka rekening. Kemudian, nasabah akan melakukan setoran awal. Data tersebut akan disimpan ke dalam basis data melalui sistem informasi tabungan. Jika nasabah akan melakukan transfer ke berbagai rekening melalui teller, ATM, internet banking, dan mobile banking, di mana channel-channe/ tersebut akan memasukkan data transaksi itu dan menyimpannya dalam basis data. Nasabah pun akan dapat melihat posisi terakhir saldonya melalui channel-channel tersebut.
	8. ﻿﻿﻿Sistem Informasi Asuransi. Pada sistem ini terdapat beberapa proses yang berkaitan dengan pengelolaan asuransi, antara lain dalam melakukan pengelolaan data nasabah atau data pembayaran premi, pemrosesan pengajuan klaim asuransi, dan lain-lain.
	9. ﻿﻿﻿Sistem Informasi Rumah Sakit. Pada sistem ini terdapat beberapa proses yang berkaitan dengan pengelolaan rumah sakit. Pengelolaan rumah sakit tersebut antara lain dalam melakukan pengelolaan data pasien, riwayat penyakit atau pengobatan pasien, menangani pembayaran perawatan, dan lain-lain.




---



# [[Kegiatan Belajar 2 - Konsep Sistem Basis Data dan DBMS]]

pada Kegiatan Belajar 2 ini akan membahas konsep sistem basis data dan DBMS. Seperti yang telah dipelajari sebelumnya, bahwa basis data adalah sekumpulan file atau tabel yang saling berhubungan antara satu dengan yang lainnya. File atau tabel tersebut memungkinkan dilakukan manipulasi data supaya memberikan sebuah informasi yang berguna.


## 08. Pengertian Basis Data dan Komponen Sistem Basis Data

Berbeda dengan Basis Data (database), sistem basis data dapat diartikan sebagai suatu sistem yang di dalamnya terdiri dari koleksi data atau suatu kumpulan data yang saling berhubungan dan memungkinkan berbagai program untuk mengakses dan memanipulasi data tersebut. Sistem basis data juga merupakan suatu sistem yang menyusun dan mengelola data suatu organisasi, sehingga mampu menyediakan informasi yang diperlukan oleh pemakai.

#### 1.8.1 Komponen Sistem Basis Data

Terdapat beberapa komponen dalam sebuah sistem basis data diantaranya:

1. ﻿﻿﻿Perangkat keras (hardware).

2. ﻿﻿﻿Sistem operasi (operating system).

3. ﻿﻿﻿Basis data (database).

4. ﻿﻿﻿DBMS (database management system), merupakan perangkat lunak (software) yang digunakan untuk menentukan bagaimana data tersebut dapat terorganisasi, tersimpan, diubah serta diambil kembali. DBMS ini pun yang menerapkan suatu mekanisme sebagai pengamanan data secara bersamaan, konsistensi data, dan semacamnya.

5. ﻿﻿﻿Pengguna (user). Pengguna ini dapat dikategorikan menjadi pengguna akhir atau end user, pemrogram aplikasi dan administrator basis data atau DBA (Database Administrator).

6. ﻿﻿﻿Program aplikasi (application program) adalah perangkat lunak yang ditulis atau dikembangkan oleh Programmer atau pemrogram aplikasi dan kemudian digunakan oleh end user atau pengguna akhir.




## 09. Konsep dan Sejarah Database management System (DBMS)

Database Management System (DBMS) merupakan paket program (Software) yang digunakan untuk membuat dan mengelola basis data. DBMS dibuat agar memudahkan dan mengefisienkan proses input, update, delete, restore, view, dan pengambilan informasi terhadap basis data. Tujuan utama DBMS adalah menyediakan lingkungan yang mudah dan nyaman bagi pengguna dalam mengambil, menyimpan data dan informasi. Software yang tergolong ke dalam DBMS antara lain, Microsoft SQL, MySQL, Oracle, MS. Access, dan lain-lain.

#### 1.9.1 Sejarah Database Management System (DBMS)

##### 1.9.1.a Tahun 1960 Network Database

Sejarah sebuah basis data diawali tahun 1960. Pada awal tahun tersebut, Charles Bachman membuat sebuah desain DBMS pertama yang disebut dengan penyimpanan data terintegrasi. Desain DBMS tersebut berbentuk sebuah model jaringan basis data (network database). Model jaringan basis data tersebut distandarisasi oleh Conference on Data System Language (CODASYL). Gambar 1.4 merupakan contoh dari network database.

![[Pasted image 20250209091556.png]]

Network database terdiri dari kumpulan record yang dihubungkan melalui pointer yang membentuk relasi antar record. Model ini tidak memungkinkan banyak relasi namun mudah dalam menyisipkan data.

##### 1.9.1.b Tahun 1971 First Generation - Hierarchical Model

DBMS generasi pertama yaitu model hirarki (hierarchical model). Model hirarki ini merupakan kumpulan record yang dihubungkan satu sama lain berdasarkan pointer berbentuk pohon. Gambar 1.5 merupakan contoh dari model hirarki.

![[Pasted image 20250209091638.png]]

##### 1.9.1.c Tahun 1976 Second Generation - Relational Model

Pada tahun 1976 generasi kedua dari DBMS yaitu dengan penerapan model relasi (relational model). Dengan model relasi ini, data terorganisir dengan baik sehingga dapat dengan mudah dilakukan manipulasi data dan menghasilkan sebuah informasi yang baik. Gambar 1.6 berikut merupakan contoh dari model relasi.

![[Pasted image 20250209091705.png]]

##### 1.9.1.d Tahun 1990 Third Generation - Object Reletional dan Object Oriented

Generasi berikutnya muncul pada tahun 1990 yaitu object relational dan object oriented. Generasi ini merupakan sebuah respon terkait dengan berkembangnya bahasa pemograman berorientasi objek, atribut, dan metode. Gambar 1.7 berikut ilustrasi kemiripan antara Relational Model dan Object Model.

![[Pasted image 20250209091805.png]]





## 10. Pengguna (User)

Pengguna dapat digolongkan menjadi 3 yaitu:

1. Pengguna Akhir atau end user, dapat dibagi menjadi 2, yaitu
	1. ﻿﻿﻿Pengguna aplikasi adalah orang yang bertugas mengoperasikan program aplikasi. Program aplikasinya telah dibuat oleh pemrogram aplikasi sehingga pengguna aplikasi tinggal mengoperasikannya saja.
	2. ﻿﻿﻿Pengguna interaktif adalah orang yang dapat memberikan perintah-perintah pada antar muka basis data menggunakan SQL, misalnya SELECT, INSERT, UPDATE, DELETE.

2. ﻿﻿﻿Pemrogram aplikasi adalah orang yang membuat program aplikasi menggunakan basis data dan bahasa pemograman.

3. ﻿﻿﻿Administrator basis data atau DBA (Database Administrator) adalah orang yang bertanggungjawab terhadap pengelolaan basis data. Tugas dari DBA diantaranya:
	1. ﻿﻿﻿Mendefinisikan basis data.
	2. ﻿﻿﻿Menentukan isi basis data dan
	3. ﻿﻿﻿Menentukan keamanan basis data





## 11. Klasifikasi BDMS

Suatu DBMS dapat diklasifikasikan ke dalam beberapa kriteria diantaranya sebagai berikut:

#### 1.11.1 Klasifikasi Berdasarkan Model Data

Beberapa model data adalah model data relasi atau sering disebut DBMS, model data hierarki, dan model data jaringan. Model data yang paling sering digunakan saat ini adalah model data relasional atau DBMS. Sedangkan aplikasi yang mendukung model data relasi adalah Oracle, MS SQL Server, DB2, dan MySQL mendukung model ini.

Dalam beberapa tahun terakhir, terdapat model data baru yaitu model data berorientasi objek. Model ini merupakan sistem manajemen basis data dimana informasi direpresentasikan dalam bentuk objek seperti yang digunakan dalam pemrograman berorientasi objek. Basis data berorientasi objek berbeda dari basis data relasional atau yang berorientasi tabel. Sistem manajemen basis data berorientasi objek (OODBMS) menggabungkan kemampuan basis data dengan kemampuan bahasa pemrograman berorientasi objek. Model berorientasi objek belum menangkap seperti yang diharapkan sehingga tidak digunakan secara luas. Beberapa contoh DBMS berorientasi objek adalah 02, ObjectStore, dan Jasmine.


#### 1.11.2 Klasifikasi Berdasarkan Jumlah Pengguna

DBMS dapat diklasifikasikan berdasarkan jumlah pengguna yang didukungnya. DBMS ini bisa berupa sistem basis data pengguna tunggal, yang mendukung satu pengguna dalam satu waktu, atau sistem basis data multi pengguna, yang mendukung banyak pengguna secara bersamaan.

#### 1.11.3 Klasifikasi Berdasarkan Sistem Distribusi

Ada empat sistem distribusi utama dalam klasifikasi basis data ini diantaranya sistem terpusat dimana basis data disimpan dalam sebuah server terpusat dan digunakan oleh beberapa sistem lainnya. Kemudian sistem database terdistribusi yaitu basis data aktual dan perangkat lunak DBMS didistribusikan dari berbagai server yang dihubungkan oleh jaringan komputer. Sistem database terdistribusi homogen yaitu menggunakan perangkat lunak DBMS yang sama dari beberapa server. Pertukaran data antara berbagai situs ini dapat ditangani dengan mudah. Kemudian yang terakhir sistem database terdistribusi heterogen yaitu server yang berbeda mungkin menggunakan perangkat lunak DBMS yang berbeda, tetapi ada perangkat lunak umum tambahan untuk mendukung pertukaran data di antara server tersebut.

#### 1.11.4 Abstraksi Data

DBMS memiliki tujuan untuk menyediakan interface kepada pengguna. Abstraksi data merupakan tingkatan-tingkatan pengguna dalam memandang bagaimana sebenarnya data diolah dalam sebuah sistem basis data sehingga menyerupai kondisi yang sebenarnya dihadapi oleh pengguna dalam kehidupan sehari-hari. Sebuah DBMS seringkali menyembunyikan secara rinci tentang bagaimana sebuah data disimpan dan dipelihara (diolah) dalam sebuah sistem basis data. Hal ini bertujuan untuk memudahkan pengguna dalam menggunakan DBMS tersebut. Oleh karena itu, pengguna seringkali melihat perbedaan data sebelumnya dengan data yang tersimpan secara fisik.

Terdapat 3 level abstraksi yaitu:

4. Level Fisik (Physical Level)

	Level fisik merupakan lapisan terendah. Lapisan ini menjelaskan bagaimana (how) data sesungguhnya disimpan. Pada lapisan inilah struktur data


5. Level Logik / Konseptual (Conceptual Level)

	Level konseptual lebih tinggi dari lapisan fisik. Lapisan ini menjabarkan data apa (what) saja yang sesungguhnya disimpan pada basis data dan juga menjabarkan hubungan-hubungan antar data secara keseluruhan. Seorang pengguna dalam level ini dapat mengetahui bahwa data mahasiswa disimpan pada tabel mahasiswa, tabel KRS, tabel transkrip, dan lain sebagainya. Level ini biasa dipakai oleh DBA (Database Administrator).

6. Level Pandangan (View Level)

	Level pandangan merupakan lapisan tertinggi pada abstraksi data. Pada lapisan ini pengguna hanya mengenal struktur data sederhana yang berorientasi pada kebutuhan pengguna. Data yang dikenal oleh setiap pengguna bisa berbeda-beda dan barangkali hanya mencakup sebagian dari basis data. Misalnya, bagian keuangan hanya membutuhkan data keuangan, jadi yang digambarkan hanya pandangan terhadap data keuangan saja. Begitu juga dengan bagian akuntansi, hanya membutuhkan data akuntansi. Jadi, tidak semua pengguna basis data membutuhkan seluruh informasi yang terdapat dalam basis data tersebut.


Sebagai gambaran, misalnya terdapat struktur data bertipe record seperti berikut:

```
Pegawai = RECORD
	Nama : STRING;
	Alamat : STRING;
	Bagian : STRING;
	Gaji : LongInt;
End:
```

Pada contoh ini record pegawai berisi 4 buah field (nama, alamat, bagian, dan gaji). Setiap field memiliki nama dan setiap nama memiliki tipe data.

7. Pada level fisik, pegawai dapat dijabarkan sebagai blok data yang terletak pada lokasi berurutan (satuan byte). 

8. Pada lapisan konseptual, masing-masing record dijabarkan dengan definisi tipe data. 

9. Pada lapisan view, user tertentu hanya boleh mengakses data tertentu. Contohnya seorang yang menangani penggajian berhak mengetahui gaji seseorang bahkan mengubahnya. Akan tetapi orang yang bekerja di bagian lain tentu tidak boleh melihatnya.


## 12. Sistem Informasi, Aplikasi dan BDMS

Dalam kehidupan sehari-hari, sering ditemui sistem informasi dan aplikasi. Sistem informasi merupakan kombinasi dari beberapa teknologi informasi dengan aktivitas pengguna untuk dapat memenuhi kebutuhan sebuah organisasi. Sebagai contoh Sistem Informasi Perpustakaan, Sistem Informasi Akademis, Sistem Informasi Penggajian, Dan Sistem Informasi Persediaan. Beberapa penjelasan tentang keterkaitan antara basis data dan sistem informasi adalah sebagai berikut:

10. ﻿﻿﻿Dalam pengembangan sistem informasi diperlukan basis data sebagai media penyimpan data untuk menghasilkan informasi secara tepat, akurat, dan bermanfaat.
11. ﻿﻿﻿Sistem informasi merupakan kombinasi teratur dari manusia, hardware, software, jaringan komunikasi, dan sumber daya data, yang mengumpulkan, mengubah, dan menyebarkan informasi dalam sebuah organisasi.

Sedangkan aplikasi adalah program yang menentukan aktivitas pemrosesan data dan menghasilkan informasi yang dibutuhkan untuk penyelesaian tugas-tugas khusus dari pengguna komputer contohnya spreadsheet elektronic dan aplikasi word processing. Seperti yang dapat dilihat pada Gambar 1.8 berikut ini:

![[Pasted image 20250209092441.png]]

Pada gambar (A) merupakan gambaran dari sistem informasi di mana beberapa aktivitas pengguna sedang mengakses sebuah DBMS menggunakan kombinasi dari beberapa teknologi. Sedangkan pada gambar (B) merupakan contoh aplikasi yang ada pada sebuah sistem operasi. Aplikasi-aplikasi tersebut siap digunakan oleh pengguna sesuai dengan kebutuhannya.





## 13. Traditional File Base System vs Database Management System

#### 1.13.1 Traditional File Base System

Sistem pemrosesan traditional file base system ini sekelompok rekaman disimpan pada sejumlah berkas secara terpisah. Pada umumnya, perancangan sistem didasarkan pada kebutuhan individual pemakai, bukan berdasarkan kebutuhan sejumlah pemakai. Sebagai contoh dapat anda lihat pada Gambar 1.9 berikut:

![[Pasted image 20250209092559.png]]

Gambar 1.9 menjelaskan sebuah sistem informasi akademik perguruan tinggi. Terdapat dua unit yang terpisah yaitu BAAK dan JURUSAN. Kedua unit tersebut masing-masing memiliki basis data yang terpisah dan disimpan pada masing-masing file. Dengan traditional file base system file-file tersebut terpisah sehingga akan sulit dalam hal mendapatkan data atau dalam proses pertukaran data.

#### 1.13.2 Database Management System

Berbeda dengan traditional file base system. Pada sistem ini record-record data disimpan pada satu tempat yakni basis data dan di antara program aplikasi maupun pemakai terdapat DBMS (Database Management System). Pada gambar 1.10, baik BAAK dan JURUSAN sudah saling terhubung sehingga dapat memudahkan dalam proses mendapatkan sebuah informasi.

![[Pasted image 20250209092638.png]]


![[Pasted image 20250209092658.png]]





