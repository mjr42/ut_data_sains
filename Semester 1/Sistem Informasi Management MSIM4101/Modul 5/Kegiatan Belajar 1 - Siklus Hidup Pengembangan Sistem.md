---
tags:
  - sistem_informasi_management
  - materi_5_SIM
---
# Kegiatan Belajar 1 - Siklus Hidup Pengembangan Sistem

## [[01. Tahapan-Tahapan di SDLC]]

Metode siklus hidup pengembangan sistem atau System Development Life Cycle (SDLC) mempunyai beberapa tahapan. Sesuai dengan namanya, SDLC dimulai dari suatu tahapan sampai tahapan terakhir dan kembali lagi ke tahapan awal untuk membentuk suatu siklus atau daur hidup

Tahapan tahapan dalam metode SDLC adalah sebagai berikut:

1. Analisis sistem (system analysisa. studi pendahuluan,
	- studi kelayakan,
	- mengidentifikasi permasalahan dan kebutuhan pemakai,
	- memahami sistem yang ada,
	- menganalisis hasil penelitian.

2. Perancangan sistem (system design):
	- perancangan awal,
	- perancangan perinci.

3. Implementasi sistem (system implementation).
   
4. Operasi dan perawatan sistem (system operation and maintenance

Siklus atau daur hidup pengembangan sistem tampak jika sistem yang sudah dikembangkan dan dioperasikan tidak dapat dirawat lagi sehingga dibutuhkan pengembangan sistem kembali

![[Screenshot 2024-10-01 at 19.31.37.png]]



## [[02. Analisis System]]

Tahap awal dari SDLC adalah analisis sistem (system analysis).Tahap ini dilakukan oleh analis sistem (system analyst). Analis sistem (system analyst) adalah orang yang dididik khusus untuk mengembangkan sistem secara profesional

Kegiatan analisis sistem terdiri atas kegiatan kegiatan berikut:

#### a. Studi Pendahuluan

Kegiatan awal dari analisis sistem adalah studi awal atau studi pendahuluan tentang jenis, ruang lingkup dan pemahaman awal dari proyek pengembangan STI ini. Dari studi pendahuluan ini, dapat diperoleh hasil pemahaman sistem secara awal, perkiraan biaya yang dibutuhkan dan waktu yang diperlukan untuk pengembangan STI ini

#### b. Studi Kelayakan

Studi kelayakan (feasibility study) terdiri atas lima macam kelayakan yang disebut dengan TELOS, yaitu studi kelayakan teknologi, studi kelayakan ekonomis, studi kelayakan legal, studi kelayakan operasi dan studi kelayakan sosial. Studi kelayakan ini dimaksudkan bahwa secara teknologi, ekonomi, legal, operasi dan sosial, pengembangan STI dapat dilakukan dan layak

Manfaat yang diperoleh dari STI dapat berbentuk manfaat-manfaat berwujud (tangible benefits) dan manfaat-manfaat tidak berwujud (intangible benefits)

###### Tangible Benefit

Manfaat-manfaat berwujud (tangible benefits) merupakan manfaat-manfaat yang langsung dapat diukur dengan nilai uang. Contoh manfaat-manfaat ini adalah manfaat penurunan biaya persediaan, manfaat penurunan biaya operasi, manfaat penurunan biaya alat tulis, danmanfaat peningkatan penjualan

###### Intangible Benefit

Manfaat-manfaat tidak berujud (intangible benefits) merupakan manfaat-manfaat yang tidak langsung dapat diukur dengan nilai uang. Contoh manfaat-manfaat ini adalah manfaat peningkatan pengambilan keputusan manajemen, manfaat peningkatan kepuasan pelanggan, dan manfaat peningkatan moral pekerja

Metode nilai ekspektasi (expected value) dilakukan dengan mengidentifikasi kejadian-kejadian (outcomes) yang akan terjadi akibat manfaat tidak berwujud dikalikan dengan probabilitas kemungkinan terjadinya. Misalnya, manfaat tidak berwujud adalah kepuasan pelanggan. Kejadian akibat kepuasan pelanggan adalah menaikkan penjualannya. Untuk menghitung nilai rupiah kepuasan pelanggan, yang pertama kali dilakukan adalah mengidentifikasi kenaikan penjualan akibat tingkat kepuasan langganan. Dimisalkan penjualan sebelumnya adalah Rp 20.000.000,00. Jika pelanggan “sangat puas”, diasumsikan penjualan akan meningkat sebesar 25% dari penjualan sebelumnya atau akan didapatkan kenaikan penjualan sebesar 25% × Rp 20.000.000,00, yaitu sebesar Rp 5.000.000,00. Jika pelanggan “puas”, diasumsikan penjualan akan meningkat sebesar 20% dari penjualan sebelumnya atau akan didapatkan kenaikan penjualan sebesar 20% × Rp 20.000.000,00, yaitu sebesar Rp 4.000.000,00. Jika pelanggan “cukup puas”, diasumsikan penjualan akan meningkat sebesar 10% dari penjualan sebelumnya atau akan didapatkan kenaikan penjualan sebesar 10% × Rp 20.000.000,00, yaitu sebesar Rp 2.000.000,00

![[Screenshot 2024-10-01 at 19.38.37.png]]

NIlai ekspektasi atau NE dihitung dengan menjumlahkan kejadian kejadian (outcomes) dengan nilai probabilitas terjadinya sebagai berikut:

![[Screenshot 2024-10-01 at 19.40.24.png]]
Di sini, rumus ini biasanya digunakan untuk menghitung suatu nilai ekspektasi (NE) dari suatu variabel acak diskrit dalam probabilitas atau statistika. Mari kita bahas elemen-elemen dalam rumus ini:

1.	$NE$ (Nilai Ekspektasi): NE merupakan singkatan dari “Nilai Ekspektasi” yang dalam statistika dan probabilitas menunjukkan nilai rata-rata yang diharapkan dari suatu distribusi probabilitas atau eksperimen acak.

2.	$\sum_{i=1}^{k}$: Ini adalah simbol sigma, yang menunjukkan bahwa kita menjumlahkan semua elemen dari i = 1 hingga i = k. Artinya, terdapat k elemen atau kejadian yang berbeda, dan kita melakukan penjumlahan terhadap semua elemen tersebut.

3.	$O_i$: Ini adalah nilai dari kejadian atau observasi ke-i yang diukur atau dipertimbangkan dalam perhitungan nilai ekspektasi. Bisa jadi dalam konteks lain, ini juga bisa merepresentasikan outcome dari suatu kejadian acak.

4.	$p_i$: Ini adalah probabilitas atau peluang dari kejadian i yang terjadi. Dalam konteks nilai ekspektasi, setiap nilai $O_i$ dikalikan dengan peluangnya $p_i$.


#### c. Mengidentifikasi Permasalahan dan Kebutuhan Informasi Pemakai

Mengidentifikasi masalah dilakukan dengan mengidentifikasi penyebab masalahnya. Penyebab masalah merupakan sumber dari permasalahan yang harus diperbaiki. Setelah diketahui sumber dan tempat permasalahannya, langkah selanjutnya adalah memahami sistem yang ada untuk mendapatkan data dan menganalisis permasalahannya. Memahami sistem yang ada dapat dilakukan dengan melakukan penelitian untuk mendapatkan data tentang sistem yang ada


#### d. Menganalisis Hasil Penelitian

Menganalisis hasil penelitian terdiri atas menganalisis kelemahan sistem yang lama dan menganalisis kebutuhan informasi pemakai.Menganalisis kelemahan sistem yang lama dimaksudkan untuk menemukan penyebab sebenarnya permasalahan-permasalahan yang terjadi sehingga sistem yang lama tidak berfungsi. Sistem yang lama akan diganti dengan sistem yang baru.

Jika sistem yang baru merupakan sistem teknologi informasi, perbaikan dari sistem yang lama berupa perbaikan-perbaikan dalam bentuk informasi yang disediakan oleh sistem yang baru. Supaya sistem yang baru berhasil, informasi-informasi yang dihasilkan harus sesuai dengan kebutuhan pemakainya



## [[03. Perancangan Sistem]]

Tahap berikutnya dari SDLC setelah tahap analisis sistem adalah tahap perancangan sistem (system design). Tahap perancangan sistem mempunyai dua tujuan utama sebagai berikut :

- Memberikan gambaran secara umum tentang kebutuhan informasi kepada pemakai sistem secara logika.
  
- Memberikan gambaran yang jelas dan rancang bangun yang lengkap kepada pemrogram komputer dan ahli-ahli teknik lainnya

Tujuan perancangan sistem yang pertama lebih dikenal dengan istilah perancangan sistem secara logika (logical system design) atau perancangan sistem secara umum (general system design). Tujuan perancangan sistem yang kedua lebih dikenal dengan istilah perancangan sistem secara teperinci (detail system design)

#### a. Perancangan Sistem Secara Umum

Tujuan dari perancangan sistem secara umum (general system design) atau perancangan sistem secara logika (logical system design) atau perancangan sistem secara konsep (conceptual system design) adalah memberikan gambaran secara umum kepada pemakai sistem tentang sistem teknologi informasi yang baru. Perancangan sistem secara umum merupakan persiapan dari perancangan sistem secara teperinci

Perancangan sistem secara umum lebih diarahkan kepada pemakai sistem untuk menyetujuinya ke perancangan sistem selanjutnya, yaitu perancangan sistem secara teperinci

#### Perancangan Sistem Terperinci

Jika perancangan sistem secara umum untuk menjawab pertanyaan apa yang dibutuhkan dari komponen-komponen sistem teknologi informasi, perancangan sistem secara teperinci menjawab pertanyaan bagaimana dan seperti apa bentuk dari komponen-komponennya. 

Perancangan sistem secara teperinci (detailed system design) atau perancangan sistem fisik (physical system design) dimaksudkan untuk menggambarkan bentuk secara fisik dari komponen-komponen STI yang akan dibangun oleh pemrogram dan ahli teknik lainnya


## [[04. Implementasi Sistem]]

Implementasi sistem (system implementation) adalah tahap meletakkan sistem supaya siap dioperasikan.Tahap implementasi sistem terdiri atas beberapa kegiatan sebagai berikut :

- Mempersiapkan rencana implementasi.
  
- Melakukan kegiatan implementasi:
	1) memilih dan melatih personel;
	2) memilih dan mempersiapkan tempat dan lokasi sistem;
	3) mengetes sistem;
	4) melakukan konversi sistem.
	   
- Menindaklanjuti implementasi

mplementasi sistem juga merupakan proses mengganti atau meninggalkan sistem yang lama dengan sistem yang baru. Untuk mengganti sistem yang lama dengan sistem yang baru, diperlukan suatu pendekatan atau strategi supaya berhasil. Pendekatan atau strategi konversi yang ada sebagai berikut:

#### a. Konversi Paralel

Pendekatan atau strategi konversi paralel (parallel conversion) dilakukan dengan mengoperasikan sistem yang baru bersama-sama dengan sistem yang lama selama satu periode waktu tertentu. Kedua sistem ini dioperasikan bersama-sama untuk meyakinkan bahwa sistem yang baru telah benar-benar beroperasi dengan sukses sebelum sistem yang lama dihentikan

>Keunggulan dari sistem ini adalah risiko penerapan yang rendah, yaitu jika sistem yang baru gagal, sistem yang lama masih tetap beroperasi. 

>Kelemahan dari pendekatan ini adalah biaya yang harus dikeluarkan


#### b. Konversi Pilot

Pendekatan atau strategi konversi pilot (pilot conversion) atau pendekatan konversi lokasi (location conversion) dilakukan bertahap pada suatu lokasi sebagai suatu percontohan dan jika berhasil dilanjutkan ke lokasi yang lainnya. Pendekatan ini biasanya dilakukan apabila suatu sistem yang sejenis akan diterapkan di banyak bagian atau lokasi atau departemen

> Keunggulan dari sistem ini adalah Kebaikan dari pendekatan ini adalah risiko kegagalan penerapan sistem sedang, yaitu kegagalan sistem mungkin terjadi hanya terletak pada lokasi konversi yang awal karena kesalahan pada lokasi sebelumnya dapat dibetulkan terlebih dahulu sehingga tidak terjadi kesalahan pada lokasi berikutnya. 

>Kelemahan dari pendekatan ini adalah waktu konversi dapat menjadi lama karena dilakukan tidak langsung untuk seluruh lokasi, tetapi bertahap untuk masing-masing lokasi


#### c. Konversi Bertahap

Pendekatan atau strategi konversi bertahap (phasing conversion, stepped conversion, staged conversion, phase-inconversion atau phased cut-over conversion) dilakukan dengan menerapkan masing-masing modul dari sistem secara bertahap dan urut. Pendekatan ini dilakukan dengan menerapkan sebuah modul terlebih dahulu. Jika sukses, disusul oleh modul lainnya sampai semua modul selesai diterapkan

>Keunggulan dari sistem ini adalah risiko kegagalan penerapan sistem sedang, yaitu kegagalan sistem mungkin terjadi hanya terletak pada modul konversi yang awal karena kesalahan pada modul sebelumnya dapat dibetulkan terlebih dahulu. 

>Kelemahan dari pendekatan ini adalah waktu konversi dapat menjadi lama karena dilakukan tidak langsung untuk seluruh modul, tetapi bertahap untuk masing-masing modul


#### d. Konversi Langsung

Pendekatan atau strategi konversi langsung (direct conversion, direct cutover, cold turkey conversion, atau abrupt cutover) dilakukan dengan mengganti sistem yang lama langsung dengan sistem yang baru. 

>Keunggulan dari pendekatan ini terletak pada biaya konversinya yang tidak terlalu besar.
 
>Kelemahan dari pendekatan ini adalah risiko yang harus ditanggung besar karena kegagalan sistem yang baru dapat berakibat fatal

## [[05. Operasi dan Perawatan Sistem]]

Tahap ini disebut dengan operasi dan perawatan sistem (system operation and maintenance). Sistem perlu dirawat karena beberapa hal berikut.
1. Sistem mengandung kesalahan yang dulunya belum terdeteksi sehingga kesalahan-kesalahan sistem perlu diperbaiki.
2. Sistem mengalami perubahan-perubahan karena permintaan baru dari pemakai sistem.
3. Sistem mengalami perubahan karena perubahan lingkungan luar.
4. Sistem perlu ditingkatkan


## [[06. Kelebihan dan Kekurangan Metode SDLC]]

Metode SDLC memiliki beberapa kelebihan dan juga kekurangan

#### Kelebihan Metode SDLC

1. Menyediakan tahapan yang dapat digunakan sebagai pedoman mengembangkan sistem.
   
2. Memberikan hasil sistem yang lebih baik karena sistem dianalisis dan dirancang secara keseluruhan sebelum diimplementasikan


#### Kekurangan Metode SDLC

1. Hanya menyediakan tahapan-tahapan, tetapi tidak menyediakan metodologi (cara dan alat-alat) untuk mengembangkan sistem sehingga harus digabungkan dengan metodologi yang ada, yaitu metodologi pengembangan sistem terstruktur misalnya.
   
2. Hasil dari SDLC sangat tergantung dari hasil di tahap analisis sehingga jika terdapat kesalahan analisis, akan terbawa terus dengan hasil sistem yang kurang memuaskan.
   
3. Dibutuhkan waktu yang lama untuk mengembangkannya karena sistem harus dikembangkan sampai selesai semua terlebih dahulu.
   
4. Dibutuhkan biaya yang relatif lebih besar dibandingkan dengan metode lainnya.
   
5. Hasil dari sistem tidak luwes untuk dimodifikasi karena perlu dilakukan analisis kembali
