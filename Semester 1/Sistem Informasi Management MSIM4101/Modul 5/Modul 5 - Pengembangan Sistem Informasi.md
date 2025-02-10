---
tags:
  - sistem_informasi_management
---
# [[Kegiatan Belajar 1 - Siklus Hidup Pengembangan Sistem]]

## Tahapan-Tahapan di SDLC

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



## Analisis Sistem

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



## Perancangan Sistem

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


## Implementasi Sistem

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



## Operasi dan Perawatan Sistem

Tahap ini disebut dengan operasi dan perawatan sistem (system operation and maintenance). Sistem perlu dirawat karena beberapa hal berikut.
1. Sistem mengandung kesalahan yang dulunya belum terdeteksi sehingga kesalahan-kesalahan sistem perlu diperbaiki.
2. Sistem mengalami perubahan-perubahan karena permintaan baru dari pemakai sistem.
3. Sistem mengalami perubahan karena perubahan lingkungan luar.
4. Sistem perlu ditingkatkan


## Kelebihan dan Kekurangan Metode SDLC

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


---


# [[Kegiatan Belajar 2 - Metodologi Pengembangan Sistem Informasi Terstruktur]]

Metode SDLC hanya memberikan tahapan-tahapan (apa yang harus dilakukan) dalam mengembangkan sistem, tetapi tidak memberikan cara (bagaimana mengembangkannya) dan alat (apa yang harus digunakan) untuk mengembangkannya. Supaya pengembang sistem dapat bekerja dengan efisien dan efektif, metodologi pengembangan sistem perlu diketahui. Metodologi pengembangan sistem (system development methodology) memberikan cara dan alat pengembangan sistem tersebut. 

Metodologi pengembangan sistem yang populer dan banyak digunakan adalah metodologi pengembangan sistem terstruktur (structured approach). Metodologi pendekatan terstruktur (structured approach) memberikan beberapa cara dan beberapa alat pengembangan sistem


## Cara Pengembangan Sistem

Metodologi pendekatan terstruktur (structured approach) memberikan cara top down dan cara dekomposisi dalam pengembangan sistem informasi

#### 1. Cata Top-Down (Atas-Turun)

Cara atas turun (top down) berlawanan dengan cara bawah naik (bottom up). Cara atas turun (top down) dimulai dari atas, yaitu kebutuhan informasi pemakai dan turun sampai ke data untuk memenuhi kebutuhan ini. Jika dihubungkan dengan perancangan enam komponen sistem teknologi informasi, cara atas turun dimulai dengan perancangan komponen output, komponen model, komponen basis data, komponen input, komponen teknologi dan komponen pengendalian.

Cara atas turun (top down) lebih disarankan dibandingkan dengan cara bawah atas (bottom up). Alasannya adalah cara atas turun (top down) dimulai dari kebutuhan informasi pemakai yang harus dipenuhi, sedangkan cara bawah naik (bottom up) dimulai dari data yang tersedia sehingga kebutuhan informasi pemakai belum tentu dapat dipenuhi jika data tidak tersedia. 

Alasan lainnya adalah cara atas turun (top down) lebih didukung oleh pemakai sistem karena berhubungan dengan kebutuhan mereka

#### 2. Cata Bottom-Up (Bawah-Naik)

Cara bawah naik (bottom up) dimulai dari bawah, yaitu dari ketersediaan data naik hingga informasi yang dibutuhkan ke pemakai. Jika dihubungkan dengan perancangan enam komponen sistem teknologi informasi, cara bawah naik dimulai dengan perancangan komponen input, komponen basis data, komponen output, komponen model, komponen teknologi dan komponen pengendalian

####  3. Cara Dekomposisi

Cara dekomposisi (decomposition approach) atau disebut juga dengan cara moduler (modul air approach) memecah sistem yang rumit menjadi beberapa bagian sistem yang disebut dengan modul-modul yang lebih sederhana. Modul-modul ini kemudian akan dirangkai kembali menjadi sistem yang utuh

##### Keunggulan cara ini adalah :

- membuat sistem yang rumit menjadi mudah dipahami dalam bentuk-bentuk modul yang lebih sederhana, 
  
- dapat dilakukan pembagian kerja mengembangkan sistem sesuai dengan modul-modulnya, 
  
- sebagai dokumentasi yang baik untuk memahami sistem 
  
- menyediakan jejak audit (audit trail) dan proses menemukan kesalahan sistem (debugging) yang baik jika sistem mempunyai beberapa kesalahan yang akan diperbaiki



## Alat Alat Pengembangan Sistem

Beberapa alat (tools) diperlukan untuk metodologi pengembangan sistem terstruktur. Alat-alat yang tersedia untuk pendekatan ini, di antaranya bagan alir sistem (system flow chart), diagram arus data (data flow diagram), kamus data (data dictionary), bagan alir program (program flow chart), bagan terstruktur (structured chart), structured english, pseudo code dan tabel keputusan (decision table)

Alat-alat yang digunakan oleh analis sistem untuk berkomunikasi dengan pemakai sistem adalah diagram arus data (DAD), kamus data (KD) dan bagan alir sistem; sedangkan alat-alat yang digunakan oleh analis sistem untuk berkomunikasi dengan teknisi sistem adalah diagram arus data (DAD), kamus data (KD), bagan alir program, tabel keputusan, structured english, pseudo code dan bagan terstruktur

#### 1. Alat-Alat Komunikasi di Tahapan Analisis

Pada tahap ini, analis sistem perlu menyampaikan hasil analisisnya kepada pemakai sistem. 

Hasil analisisnya adalah pemahaman tentang sistem yang lama dan kebutuhan-kebutuhan informasi yang dibutuhkan oleh pemakai sistem. Analis sistem membutuhkan alat supaya komunikasi dengan pemakai mengena. Alat-alat komunikasi yang digunakan di tahap ini adalah bagan alir sistem (systems flow chart), diagram arus data (data flow diagram), dan kamus data (data dictionary)

##### a. Bagan Alir Sistem dan Bagan Alir Dokumen

Bagan alir sistem (system flow chart) digunakan untuk menggambarkan proses dari sistem yang lama atau sistem baru yang diusulkan. Bagan alir sistem juga menunjukkan arus dari dokumen-dokumen yang ada di organisasi sehingga disebut juga dengan nama bagan alir dokumen (document flow chart.

![[Screenshot 2024-10-01 at 20.14.24.png]]

##### b. Diagram Arus Data

Proses dari sistem yang lama dan yang baru dapat juga digambarkan dengan diagram arus data (DFD). Jika bagan alir dokumen lebih menunjukkan dokumen yang mengalir dalam organisasi, diagram arus data (DAD) atau data flow diagram (DFD) lebih menunjukkan data yang mengalir dari satu entitas ke entitas yang lain.

Karena prinsip kerja DAD adalah dekomposisi, yaitu memecah sistem yang kompleks menjadi beberapa modul-modul yang lebih mudah dipahami dan lebih teperinci, alat ini sangat tepat untuk pendekatan struktur yang juga menyarankan cara dekomposisi seperti ini.

Hal yang akan digambar pertama kali dalam DAD adalah diagram level atas (top level diagram) yang juga disebut dengan diagram konteks (context diagram). Dari context diagram ini kemudian akan digambar menjadi lebih teperinci lagi yang disebut dengan overview diagram atau diagram level 0. Dari diagram level 0 ini dapat dipecah-pecah kembali menjadi diagram-diagram yang lebih teperinci menjadi diagram level 1, diagram level 2, dan seterusnya sampai dianggap sudah cukup perinci

![[Screenshot 2024-10-01 at 20.16.17.png]]

sistem penjualan terlihat bahwa sistem ini terdiri atas tiga proses utama, yaitu (1) memproses order, (2) memverifikasi kredit, serta (3) merekamkan dan posting ke buku besar. Sistem ini melibatkan empat entitas dan tujuh file basis data, yaitu file induk langganan (D1), file transaksi order penjualan (D2), file transaksi penjualan (D3), file transaksi piutang dagang (D4), file transaksi barang (D5), file induk persediaan (D6) dan file induk buku besar (D7). 

Beberapa data juga mengalir  dari satu entitas ke proses (data order langganan) atau dari proses ke proses (misalnya data order penjualan) atau dari proses ke entitas (misalnya data tembusan permintaan sediaan) atau dari proses ke file basis data (misalnya data transaksi penjualan) atau dari file basis data ke proses (misalnya data order penjualan)

##### C. Kamus Data

Data yang mengalir di diagram arus data perlu dijelaskan detailnya. Alat kamus data (KD) dapat digunakan untuk maksud ini. Kamus data (KD) atau data dictionary (DD) adalah katalog fakta tentang data yang mengalir di sistem. Kamus data ini menjelaskan atribut dari data, yaitu tentang nama dari arus data, aliasnya, bentuk media data (dokumen dasar atau laporan atau layar komputer, variabel, atauparameter), arusnya (dari mana ke mana), penjelasannya, periode waktunya, volume datanya dan struktur datanya


## Alat-Alat Komunikasi di Tahap Perencanaan

Di tahap ini, analis sistem masih memerlukan beberapa alat yang sama dengan yang dibutuhkan untuk berkomunikasi dengan pemakai sistem. Alat-alat ini adalah diagram arus data dan kamus data.

Alat-alat komunikasi lainnya, seperti bagan alir program, bagan terstruktur, tabel keputusan, structured english dan pseudo code dibutuhkan oleh teknisi sistem untuk membangun sistem secara fisik, misalnya untuk membuat program komputer atau membangun basis data

Membuat kode-kode program akan sangat terbantu dengan melihat alur program yang sudah dituliskan dalam bentuk structured english dan pseudocode. Analis sistem sudah mengubah alur dari program yang lebih umum di bagan alir program, bagan terstruktur, dan tabel keputusan menjadi alur program yang lebih detail di structured english dan pseudo code. Teknisi sistem hanya mengubah kata-kata di structured english dan pseudo code dengan kata-kata yang digunakan di bahasa pemrograman yang dipilih tanpa mengubah alur logika program

#### a. Bagan Alir Program

Bagan alir program selanjutnya dapat digunakan untuk menggambarkan proses dari program dari modul-modul yang ada di bagan terstruktur. Bagan alir program (program flow chart) adalah bagan alir yang menunjukkan logaritma dari proses program.

![[Screenshot 2024-10-01 at 20.20.50.png]]


#### b. Bagan Terstruktur

Untuk keperluan pembuatan program, proses di bagan alir program yang lebih perinci dengan menunjukkan variabel-variabel atau parameter-parameter yang akan digunakan di program dapat digambarkan dalam bentuk bagan terstruktur (structured chart). Bagan terstruktur (structured chart) digunakan untuk mendefinisikan dan mengilustrasikan hubungan elemen data dan elemen kontrol antar modul-modul sistem secara berjenjang

#### c. Tabel Keputusan

Jika program mengandung banyak sekali penyeleksian kondisi yang harus dilakukan, penulisan langsung ke pseudo code akan sangat sulit dan mempunyai risiko kesalahan. Tabel keputusan dapat digunakan terlebih dahulu untuk maksud ini. Tabel keputusan (decision table) adalah tabel yang digunakan sebagai alat bantu untuk menyelesaikan logika penyeleksian kondisi dalam program.

#### d. Pseudo Code

Pseudo berarti imitasi atau mirip, sedangkan code berarti kode program sehingga pseudo code dapat diartikan sebagai kode yang mirip dengan instruksi kode program komputer. 

Pseudo code berbasis pada statesmen-statesmen dari bahasa program yang akan digunakan oleh pemrogram. Pseudo code akan sangat bermanfaat bagi pemrogram karena mirip dengan kode-kode program yang digunakan oleh pemrogram.

#### e. Structured English

Variasi lain dari pseudo code adalah structured english. Perbedaannya adalah jika pseudo code berbasis pada statesmen kode program, structured english berbasis pada bahasa Inggris