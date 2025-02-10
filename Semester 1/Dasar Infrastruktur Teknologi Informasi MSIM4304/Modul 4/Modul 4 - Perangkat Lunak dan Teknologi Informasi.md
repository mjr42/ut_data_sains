---
tags:
  - dasar_infrastruktur_teknologi_informasi
  - materi_4_DITI
---
# [[Kegiatan Belajar 1 - Perangkat Lunak]]

Perangkat lunak menurut Roger S Pressman adalah suatu perintah program dalam komputer yang apabila dieksekusi oleh penggunanya akan memberikan fungsi dan unjuk kerja seperti yang diharapkan oleh penggunanya.

Program yang digunakan oleh komputer untuk mengatur dan mengontrol perangkat keras komputer dan program aplikasi dikenal sebagai software sistem. Software sistem akan diposisikan sebagai suatu platform yang digunakan oleh program aplikasi

Perangkat komputer dapat berfungsi untuk memproses data apabila ada gabungan dari dua buah komponen, yaitu perangkat keras dan perangkat lunak serta program aplikasi akan dapat berfungsi sesuai dengan instruksi program yang diberikan apabila ada software sistem

![[Screenshot 2024-10-06 at 17.43.17.png]]

Berdasarkan tugas dan fungsinya, software atau perangkat lunak dikelompokkan menjadi beberapa bagian, yaitu software yang bertindak sebagai sistem operasi, program aplikasi, program utility (tambahan) dan bahasa pemrograman


## Sistem Operasi

Sistem operasi merupakan perangkat lunak yang digunakan untuk mengatur proses kerja dari perangkat keras komputer, seperti memory dan processor sebagai komponen utama dalam memproses data yang masuk dari alat input komputer seperti keyboard

Proses kerja antara program aplikasi dan perangkat keras komputer akan diatur oleh sistem operasi mulai dari data masuk dari alat input, disimpan terlebih dahulu ke dalam memory, kemudian diproses oleh processor sampai dikeluarkan hasilnya ke alat output atau disimpan ke tempat penyimpanan luar seperti hard disk akan dilakukan oleh sistem operasi

Pengguna komputer akan memandang sistem operasi hanya sebagai tampilan atau interface yang digunakan untuk mengakses atau menggunakan komputer

#### Kernel 

Pada saat komputer pertama kali dijalankan atau dihidupkan maka program kecil yang tersimpan di dalam memory dengan nama ROM (Read Only Memory) akan dijalankan. Nama dari programnya adalah bootloader dan nama dari prosesnya adalah booting

Setelah dipastikan perangkat keras komputer dapat berfungsi dengan baik, kemudian program sistem operasi akan dipindahkan ke RAM (Random Access Memory) agar dapat dijalankan oleh komputer

Karena letak dari sistem operasi di antara program aplikasi dan komponen perangkat keras komputer maka fungsi dari sistem operasi akan mengatur penggunaan perangkat keras komputer antar program aplikasi yang berbeda yang dijalankan pada perangkat komputer yang sama

Bagian penting dalam sistem operasi yang bertugas melakukan fungsi pengaturan sumber daya komputer, yaitu kernel sehingga posisi kernel dalam sistem operasi adalah sebagai komponen utama dalam mengatur penggunaan sumber daya perangkat keras komputer

![[Screenshot 2024-10-06 at 17.50.33.png]]

Dalam sistem operasi terdapat program inti, yaitu kernel yang mengatur operasi dari sistem komputer. Pada saat komputer dinyalakan, program pertama yang akan dijalankan pada sistem operasi adalah kernel. Selanjutnya kernel akan bertugas dalam menjalankan fungsi-fungsi operasi, seperti pengaturan jalur input/output menuju ke perangkat output seperti monitor, printer atau speaker dan masukan data dari perangkat input seperti keyboard dan mouse

Pada suatu komputer biasanya dijalankan beberapa program aplikasi sekaligus secara bersamaan. Kernel sebagai program utama dalam sistem operasi akan bertugas mengatur penggunaan sumber daya perangkat keras oleh masing-masing program aplikasi yang digunakan oleh pengguna. Kernel akan mengatur waktu dan lama penggunaan sumber daya perangkat keras komputer


## Fungsi Sistem Operasi

Sistem operasi adalah program yang digunakan untuk mengatur proses eksekusi dari program aplikasi yang digunakan oleh pengguna. Posisi dari sistem operasi terletak di antara program aplikasi dan perangkat keras komputer sehingga fungsi sistem operasi adalah sebagai interface antara proses yang dijalankan oleh pengguna menggunakan program aplikasi dengan perangkat keras komputer yang digunakan untuk memproses masukan data dari program aplikasi yang digunakan oleh pengguna

![[Screenshot 2024-10-06 at 17.53.13.png]]

Berikut adalah tiga fungsi utama dari sistem operasi

#### 1. Sistem Operasi sebagai Pengatur Aliran Data

Sistem operasi akan mengatur proses aliran data dari alat masukan seperti keyboard atau data yang berisi instruksi dari program aplikasi yang digunakan oleh pengguna. 

Sebelum data diproses oleh bagian CPU, terlebih dahulu data akan disimpan pada bagian memory. Pada bagian CPU yang berperan dalam mengatur alur proses data diambil dari memory kemudian diproses oleh bagian ALU akan dikerjakan oleh CU (Control Unit)

Data dan instruksi program akan diambil dari memory kemudian akan disimpan pada tempat penyimpanan sementara dalam CPU yang dinamakan sebagai Register sebelum data tersebut diproses oleh bagian ALU

#### 2. Sistem Operasi sebagai Pengatur Sumber Daya

Alokasi penggunaan kapasitas memory dan penggunaan CPU sebagai bagian utama dalam memproses data akan diatur oleh sistem operasi. Sistem operasi secara khusus akan memberikan instruksi pada CPU sesuai dengan kode program yang diberikan. 

Apabila dalam menginstruksi program masih dibutuhkan data tambahan maka sistem operasi akan menginstruksikan bagian CU dalam CPU untuk mengambil data tambahan tersebut dalam register

#### 3. Sistem Operasi sebagai Pengatur Proses

Sistem operasi akan mengatur setiap ada permintaan proses dari program aplikasi. Sistem operasi akan mengatur mekanisme penjadwalan terhadap pemakaian sumber daya perangkat keras komputer, terutama bagian processor (CPU) dan memory.

Proses sendiri didefinisikan sebagai entitas yang terdiri dari dua elemen penting, yaitu kode program yang berisi instruksi dan kumpulan data yang berhubungan dengan kode program yang akan dijalankan. Agar memudahkan untuk mengatur dan melacak proses dari beberapa program aplikasi yang sedang dijalankan, sistem operasi akan memberikan identitas pada setiap proses yang aktif, yaitu dengan menggunakan istilah PID (Process ID)



## Kategorisasi Sistem Operasi

Sistem operasi terdiri dari beberapa kategori sebagai berikut.

#### Sistem operasi stand alone, 

Sistem operasi ini digunakan pada komputer desktop atau yang bertindak sebagai workstation. Contoh sistem operasi desktop ini antara lain: Microsoft Windows 8/10 , Ubuntu desktop, Apple Mac OS, dan sebagainya

#### Sistem operasi jaringan (Network Operating System/NOS), 

Sistem operasi ini digunakan pada jaringan komputer dan bertindak sebagai server. Sistem operasi server merupakan sistem yang menyediakan layanan bagi komputer klien yang terhubung dengan jaringan. Sistem operasi server memiliki lebih banyak fitur dan fungsi khusus dibandingkan dengan sistem operasi desktop. Misalnya pada sistem operasi server memiliki fungsi menyediakan fungsi pemasangan alamat IP  secara  otomatis terhadap komputer client, dengan memanfaatkan fitur DHCP (Dynamic Host Configuration Protocol). Beberapa contoh sistem operasi jaringan/server antara lain: Microsoft Windows Server 2012, Ubuntu Server, Centos, FreeBSD, UNIX dan sebagainya

#### Sistem operasi Embeded, 

sistem operasi jenis ini biasanya ditanam pada komputer kecil yang diperuntukan untuk tujuan khusus. Beberapa contoh sistem operasi embedded adalah IPhone OS, Windows CE, Windows mobile, Palm OS, Symbian OS, dan sebagainya.

#### Sistem operasi Live CD, 

sistem operasi ini dirancang khusus agar dapat berjalan menggunakan CD/DVD, USB. Contoh CD Knoppix, Windows Mini PE, Gentoo, dan sebagainya



## Device Driver

Semua perangkat keras tersebut bisa berfungsi dengan baik atau dapat dijalankan apabila perangkat tersebut sudah dikenali oleh sistem operasi. Agar perangkat keras komputer dapat dikenali oleh sistem operasi maka diperlukan peran dari device driver. Fungsi dari device driver dapat juga dikatakan sebagai perantara antara perangkat keras dengan sistem operasi

![[Screenshot 2024-10-06 at 18.03.44.png]]

![[Screenshot 2024-10-06 at 18.03.54.png]]

Device driver atau driver sendiri merupakan program yang memungkinkan perangkat dapat dikenali oleh sistem operasi. Device driver juga dapat difungsikan agar program aplikasi dapat menggunakan perangkat keras dalam menjalankan instruksinya

Device driver akan mengubah instruksi program yang diberikan oleh sistem operasi agar dapat dimengerti oleh perangkat keras komputer



## Utility Software

Utility software merupakan salah satu jenis perangkat lunak yang terdapat pada sistem software yang pemanfaatan software tersebut digunakan untuk menganalisis, merawat, dan mengoptimalkan kinerja dari sistem komputer

Utility software akan digunakan oleh sistem operasi mengatur kinerja dari perangkat keras komputer agar lebih optimal. Utility software berbeda fungsi dengan software aplikasi yang cenderung digunakan untuk membantu dalam mengatasi persoalan yang dihadapi oleh pengguna aplikasi. 

Nama software yang termasuk dalam utility software berbeda antar sistem operasi, tetapi dengan fungsi yang sama, yaitu mengoptimalkan kinerja dari perangkat keras komputer

#### 1. System Restore

System restore merupakan fasilitas yang disediakan oleh sistem operasi Windows untuk mengembalikan hasil konfigurasi awal sesuai posisi waktu yang diinginkan. 

System restore akan berhubungan dengan sistem operasi Windows, di mana fungsi dari system restore digunakan untuk mengembalikan file sistem yang sudah berubah dan konfigurasi ke posisi awal, seperti kesalahan pada instalasi driver dari perangkat keras yang terpasang pada komputer, kesalahan konfigurasi pada register key, terdapat permasalahan dari program aplikasi yang telah dipasang (install) dan mengembalikan ke hasil konfigurasi ke posisi sesuai waktu yang sudah ditentukan

Permasalahan instalasi driver perangkat keras komputer juga menjadi salah satu masalah yang bisa diatasi dengan menggunakan system restore

Kumpulan dari hasil konfigurasi sistem operasi Windows akan tersimpan dalam database yang dinamakan sebagai Windows Registry. Informasi yang berkaitan tentang konfigurasi dari perangkat lunak yang sudah dipasang pada komputer, perangkat keras yang terpasang, profil user dan konfigurasi dari sistem operasi akan tersimpan dalam Windows Registry. Susunan database dalam Windows Registry terdiri kumpulan file dalam folder yang tersusun berdasarkan konsep hierarki

![[Screenshot 2024-10-06 at 18.08.36.png]]

Diasumsikan terdapat dua drive dalam tempat penyimpanan hard disk, yaitu drive C dan E. Apabila terdapat keterangan protection [on] itu artinya pada drive tersebut telah diaktifkan system restore

#### 2. System Configuration Utility

System configuration utility merupakan fasilitas yang disediakan oleh sistem operasi Windows untuk mengatur mode saat awal komputer dijalankan (startup options), pilihan program aplikasi dan layanan yang akan dijalankan pada komputer. Nama lain dari system configuration utility adalah msconfig dan diperkenalkan oleh Microsoft pada saat penggunaan sistem operasi Windows 98

![[Screenshot 2024-10-06 at 18.12.55.png]]

#### 3. Disk Defragmenter

Semua tipe data tersebut akan tersimpan dalam hard disk pada ruang yang sama namun terpencar. Setiap ada data baru yang akan disimpan, processor yang terdapat pada hard disk akan mencari ruang kosong. Proses ini akan terus dilakukan setiap ada data baru yang ingin disimpan sampai alokasi ruang kosong dalam hard disk penuh

Pada saat semua data sudah tersimpan dan kemungkinan besar pola penyimpanan data yang sama akan terpisah atau terpencar. Hal ini yang dapat mengakibatkan kerja komputer terutama disaat mencari data dalam ruang hard disk menjadi lama

Sebagai solusi dari permasalahan ini digunakan mekanisme yang dinamakan sebagai disk defragmenter. Proses yang dilakukan oleh disk defragmenter adalah mengumpulkan kembali bagian pecahan (fragment) data yang sejenis atau sama dengan posisi berdekatan. Apabila proses ini dilakukan untuk semua jenis data yang sebelumnya sudah tersimpan dalam hard disk maka proses kerja komputer dalam mencari lokasi data dan mengambil data tersebut dari hard disk menjadi lebih cepat

![[Screenshot 2024-10-06 at 18.15.03.png]]

#### 4. Antivirus

Antivirus juga termasuk perangkat lunak dalam kategori utility software, tetapi pengguna harus memasang perangkat lunak tersebut dalam komputer karena perangkat lunak ini termasuk dalam kategori utility eksternal.

Antivirus dikategorikan sebagai utility software karena sistem kerja dari perangkat lunak ini akan menghadang dan menghapus virus yang dapat memengaruhi kinerja dari sistem komputer

Ketika komputer pertama kali dihidupkan, perangkat lunak antivirus akan secara otomatis bekerja dalam mengamankan, mendeteksi, dan menghapus virus dalam komputer. Di dalam perangkat lunak antivirus terdapat basis data terkait kode-kode dari virus yang disebut sebagai virus signature database. 

Ketika ada data yang masuk ke dalam komputer, antivirus akan mencocokkan dengan database yang berisi virus signature. Apabila ada tingkat kecocokan antara data dengan virus signature dalam database maka data tersebut dikategorikan sebagai virus dan perangkat lunak antivirus akan menghapus data tersebut dari dalam komputer

Produk antivirus terbaru memiliki peningkatan dalam hal cara kerja dalam mendeteksi virus, yaitu dengan menambahkan fasilitas IDS (Intrusion Detection System). Perangkat lunak antivirus tidak hanya mendeteksi dari data yang masuk, tetapi dari pola trafik data yang masuk. Misalnya ketika komputer mendeteksi adanya trafik data dari alamat komputer tertentu dengan jumlah yang sangat besar (massive) maka perangkat lunak antivirus akan menghentikan proses yang dilakukan oleh komputer tersebut




## Bahasa Pemprograman

Komputer memiliki bahasa untuk berkomunikasi dengan menggunakan kode-kode biner (bilangan 0 dan 1) yang disusun sedemikian rupa sehingga menghasilkan suatu makna dan bahasa tersebut dikenal dengan istilah bahasa mesin. Komputer tidak mengenal bahasa yang digunakan oleh manusia sehingga untuk mengoperasikan komputer harus menggunakan bahasa mesin.

Penerjemah bahasa ini dikenal sebagai bahasa pemrograman. Bahasa pemrograman ini digunakan dengan tata cara penulisan berupa sintaks dan semantik untuk memerintahkan komputer melakukan suatu proses.

Seiring dengan perkembangan, bahasa pemrograman dapat diklasifikasikan sebagai berikut:

#### 1. Bahasa Pemprograman Generasi Pertama (Bahasa Mesin)

Yaitu bahasa pemrograman yang digunakan memakai kode biner, contohnya 1001000101100011

#### 2. Bahasa Pemprograman Generasi Kedua (Assembly)

Yaitu memberikan perintah kepada komputer dengan memakai kode-kode singkat (kode mnemonic), contohnya MOV, SUB, CMP, JMP, JGE, JL, LOOP, dsb. 

Jadi, instruksi program akan ditulis dalam bentuk kode simbol kemudian akan diterjemahkan ke dalam bentuk bahasa mesin menggunakan assembler

Istilah dari instruksi program awal sebelum diubah menjadi bahasa mesin dinamakan sebagai source program, kemudian ketika semua instruksi program sudah berubah menjadi bahasa mesin namanya juga ikut berubah menjadi object program. 

Berikut adalah contoh program dalam bahasa assembly:

![[Screenshot 2024-10-07 at 16.13.58.png]]

Penulisan bahasa assembly menggunakan kode yang dinamakan sebagai mnemonic


#### 3. Bahasa Pemprograman Generasi Ketiga

yaitu bahasa komputer yang memakai campuran instruksi dalam kata-kata bahasa manusia seperti READ, WRITE, FOR-NEXT dan sebagainya. Bahasa pemrograman yang digunakan sudah mendukung pemrograman terstruktur. Contoh bahasa pemrogramannya Pascal, FORTRAN, COBOL, BASIC dan sebagainya. 

Komputer dapat mengerti bahasa manusia itu diperlukan program compiler atau interpreter.

##### a. Complier

alur kerja yang dilakukan oleh compiler memiliki beberapa tahapan dimulai dari pembuatan program awal yang dikenal dengan nama source code atau source program. 

Bahasa pemrograman yang bisa digunakan untuk membuat source code misalnya C, C++ atau Pascal yang merupakan kategori bahasa pemrograman tingkat tinggi. 

Source code yang sudah dibuat kemudian akan dikompilasi untuk diubah menjadi bahasa mesin yang dinamakan sebagai object program.

Tahapan terakhir dari proses kompilasi adalah membuat program yang bisa langsung dijalankan oleh komputer. Proses tersebut dinamakan sebagai linkage. 

Proses ini bisa juga memungkinkan untuk menggabungkan beberapa object program menjadi satu dan mengubah menjadi program yang bisa dijalankan secara otomatis atau dinamakan sebagai executable program

##### b. Interpreter

konsep yang digunakan oleh interpreter dalam menterjemahkan source code program adalah tidak sekaligus memproses keseluruhan syntax yang digunakan dalam program. Interpreter akan memproses baris-demi-baris dari syntax atau instruksi program yang diberikan. 

Jadi dengan menggunakan interpreter, kesalahan penulisan program dapat diketahui secara lebih cepat dibandingkan dengan menggunakan compiler karena proses penterjemahan program dilakukan per-baris perintah (syntax).

Hasil keluaran dari proses interpreter tidak menghasilkan file object, sehingga bahasa pemrograman yang menggunakan konsep interpreter tidak bisa menghasilkan file program yang executable. Contoh bahasa pemrograman yang menggunakan interpreter dalam mengubah kode program menjadi bahasa mesin adalah Perl, Python dan Matlab.

Ketika ingin menjalankan program yang sudah dibuat, maka tahapan proses yang dilakukan oleh interpreter harus dari awal. Berbeda dengan konsep yang digunakan oleh compiler. Ketika ingin menjalankan program tidak perlu lagi mengulangi proses dari awal, akan tetapi cukup menjalankan program yang sudah berupa file *.exe atau program yang sudah bisa dijalankan secara otomatis.

#### 4. Bahasa Pemprograman Generasi Ke Empat

Bahasa pemrograman generasi ke empat, menggunakan pendekatan nonprocedural yang bertujuan untuk mempercepat proses pembuatan program. Contoh bahasa pemrograman generasi empat adalah Informix, Oracle, Powerbuilder, SQL, ABAP

#### 5. Bahasa Pemprograman Generasi Kelima

mengenalkan konsep kecerdasan buatan, yaitu cabang ilmu komputer yang meniru kecerdasan manusia. Pada bahasa pemrograman generasi kelima, bersifat object oriented.Contoh bahasa pemrograman generasi ke lima, antara lain: PROLOG, LISP, MERCURY dan sebagainya.


#### Bahasa Pemprograman Berbasis Web dan Mobile

Saat ini berkembang pula bahasa pemrograman berbasis web dan mobile. Pengembangan halaman web menggunakan HTML (Hypertext Markup Language). 

Dalam pengembangan aplikasi berbasis web, terdapat dua mekanisme yakni: 

1. **Client-side scripting** adalah bahasa pemrograman web yang pengolahan datanya dilakukan oleh komputer pengguna. Jadi, ketika seseorang berkunjung ke suatu web, komputernya akan mengunduh data/script yang bersifat client-side di web tersebut. Contoh client-side antara lain HTML, CSS, Javascript dan XML.
   
2. **Server-side scripting** adalah bahasa pemrograman web yang pengolahan datanya dilakukan oleh komputer server. Jadi, setiap kali web dikunjungi, server akan mengirimkan data-data yang diminta dari database yang kemudian akan ditampilkan di web. Contoh server-side antara lain PHP dan ASP

#### Bahasa Pemprograman Mobile

Pemrograman mobile adalah pembuatan aplikasi yang berjalan pada perangkat mobile seperti HP / tablet. Aplikasi mobile dikembangkan untuk platform tertentu. Platform yang populer saat ini adalah iOS dan Android. Implementasi pemrograman Android dapat menggunakan:

1. Pemrograman Java dan Android Software Development Kit (SDK).
   
2. IDE (Integrated Development Environment) yang bisa digunakan adalah Eclipse, Android Studio

Sedangkan untuk platform iOS yang digunakan pada iPhone dan iPad, bahasa pemrogramanya adalah:

1. Pemrograman Objective-C dan Cocoa framework digunakan untuk membuat aplikasi pada iPhone/iPad.
   
2. IDE (Integrated Development Environment) yang digunakan adalah Xcode. Xcode hanya berjalan di Mac




## Perangkat Lunak Aplikasi Umum

Perangkat lunak aplikasi umum adalah tipe dari perangkat lunak yang digunakan untuk menyelesaikan permasalahan yang umum atau banyak permasalahan yang dapat dipecahkan dengan menggunakan satu perangkat lunak yang sama

Perangkat lunak tipe ini banyak digunakan karena banyak permasalahan umum yang dapat dibantu dan dipecahkan dengan menggunakan tipe perangkat lunak aplikasi umum

#### 1. Perangkat Lunak Aplikasi Perkantoran

Program aplikasi ini diimplementasikan untuk menyelesaikan masalah perkantoran, seperti membuat proposal penawaran barang kepada calon pelanggan, membuat laporan neraca pembukuan keuangan atau membuat materi presentasi kepada teman sejawat atau pelanggan 

Program aplikasi yang banyak digunakan pengguna adalah yang bersifat proprietary, misalnya program aplikasi buatan Microsoft yaitu Microsoft Office yang merupakan aplikasi untuk mengolah kata, mengolah angka, mempresentasikan ide atau membuat aplikasi database sederhana

![[Screenshot 2024-10-07 at 16.26.48.png]]

![[Screenshot 2024-10-07 at 16.27.07.png]]

#### 2. Perangkat Lunak Aplikasi Surat Elektronil

Agar mempermudah proses pertukaran surat lewat media elektronik diperlukan peran perangkat lunak dalam menggantikan peran kantor pos dan orang yang mengirimkan surat. Semua pekerjaan tersebut akan dilakukan oleh satu perangkat yang namanya komputer dengan menggunakan program aplikasi yang mendukung proses kirim surat elektronik atau istilah-nya dikenal dengan nama e-mail (electronic mail)

![[Screenshot 2024-10-07 at 16.27.52.png]]

Konsep layanan e-mail tidak menggunakan peran hanya dari satu perangkat komputer saja, karena layanan e-mail menggunakan konsep client-server. Terdapat satu komputer server yang difungsikan untuk menyediakan layanan e-mail. Biasanya pengguna yang menggunakan layanan e-mail akan berposisi sebagai client




## Perangkat Lunak Aplikasi Khusus

Perangkat lunak aplikasi khusus adalah perangkat lunak yang digunakan untuk menjalankan program atau instruksi yang spefisik atau khusus. Penggunaan perangkat lunak aplikasi khusus sudah spesifik tidak bisa digunakan untuk menjalankan tugas yang lain.

Kemampunan dasar dalam menguasai penggunaan perangkat lunak aplikasi khusus tidak meluas dan cenderung mempunyai fungsi yang spesifik, sehingga diperlukan waktu penguasaan yang lebih cepat dibandingkan dengan perangkat lunak aplikasi umum. 

Beberapa contoh program aplikasi dalam kategori perangkat lunak aplikasi khusus :

#### 1. Aplikasi Kamera Webcam

program aplikasi kamera webcam hanya dikhususkan untuk mengambil gambar hasil tangkapan kamera yang terpasang di laptop. 

Kebutuhan terhadap aplikasi kamera webcam biasanya digunakan untuk melakukan rapat atau belajar jarak jauh menggunakan aplikasi Zoom, Micorsoft Teams atau Google Meet

Kedua contoh aplikasi tersebut juga termasuk dalam kategori perangkat lunak aplikasi khusus karena dikhususkan hanya untuk layanan video conference. Contoh aplikasi yang digunakan untuk mengambil gambar pada laptop dengan memanfaatkan kamera depan laptop adalah YouCam

#### 2. Aplikasi Permainan

Aplikasi permainan merupakan salah satu perangkat lunak dalam kategori aplikasi khusus. Hal ini dikarenakan program aplikasi ini khusus hanya digunakan untuk menjalankan permainan (game) tertentu saja

#### 3. Aplikasi Pemutar Musik

Aplikasi pemutar musik juga dapat dikatakan sebagai perangkat lunak aplikasi khusus, karena perangkat lunak ini diperuntukkan hanya memutar musik saja. Terdapat beberapa format file audio yang dapat diputar dengan menggunakan program aplikasi pemutar musik seperti MP3 atau MWA. 

Format file audio MP3 (MPEG Layer 3) adalah format yang sering digunakan untuk memutar musik. Format MP3 sendiri dikembangkan oleh suatu asosiasi dengan nama MPEG (Moving Picture Experts Group). 

MP3 sendiri merupakan suatu metode kompresi file audio dimana kualitas dari hasil kompresi dapat mendekati CD stereo jika digunakan jumlah bit encoder sebesar 16-bit dan menggunakan bit rate sebesar 320 kbps. Pilihan bit rate yang bisa digunakan sebenarnya dimulai dari 128, 160, 192, 256 dan 320 kbps. 

Namun dengan semakin tinggi nilai bit rate yang digunakan akan menghasilkan kualitas suara yang semakin bagus

#### 4. Aplikasi Desain Grafis

Terdapat beberapa pilihan program aplikasi yang dikhususkan untuk aplikasi menggambar diantaranya adalah Adobe Photoshop, Corel Draw atau Adobe Illustrator

![[Screenshot 2024-10-07 at 16.32.14.png]]

---


# [[Kegiatan Belajar 2 - Layanan Teknologi Informasi]]


## Pengertian Layanan Teknologi Informasi

Selain perangkat keras dan perangkat lunak, infrastruktur teknologi informasi juga meliputi masalah layanan. Layanan memiliki pengertian sebagai berikut:

1. **Menurut Hunnebeck**, layanan merupakan pemberian nilai ke pengguna dengan memfasilitasi hasil yang ingin dicapai pengguna tanpa kepemilikian biaya dan risiko khusus.
   
2. **Berdasarkan ISO/IEC 20000-1:2011**, layanan adalah penyampaian nilai kepada pengguna dengan menyediakan hasil yang ingin dicapai pengguna. 
   
3. Layanan adalah aksi atau kinerja yang dapat ditawarkan oleh seseorang ke lainnya, yang tidak dapat diukur, dihasilkan pada waktu pemberian dan tidak menghasilkan perpindahan kepemilikan, pengertian layanan **menurut O’Loughlin**. Menurut O’Loughlin, tipe layanan terdiri atas:
	1. layanan pelanggan yaitu layanan yang disediakan untuk pelanggan organisasi
	2. layanan bisnis, yaitu layanan yang mendukung proses bisnis yang memungkinkan organisasi untuk meraih hasil yang diinginkan.
	3. layanan teknologi informasi, yaitu layanan yang menyediakan kemampuan teknologi informasi yang mendukung dan memberikan layanan bisnis dan pelanggan

4. Layanan **menurut Office Government Commerce**, atau lebih dikenal dengan OGC adalah sebagai berikut.“A service is a means of delivering value to customers by facilitating outcomers want to chieve without the ownership of specific costs and risks.”

5. Teknologi informasi merupakan salah satu kategori layanan yang digunakan oleh bisnis **menurut OGC**, teknologi informasi sebagai suatu layanan biasanya berupa aplikasi-aplikasi dan infrastruktur yang dipaketkan dan ditawarkan sebagai layanan-layanan oleh organisasi teknologi informasi internal atau penyedia-penyedia jasa eksternal.
   
6. **Menurut Hunnebeck**, layanan teknologi informasi adalah layanan yang disediakan oleh penyedia layanan teknologi informasi. Layanan teknologi informasi dibentuk dari kombinasi teknologi informasi, manusia dan proses.

Layanan teknologi informasi adalah layanan yang disediakan oleh penyedia layanan teknologi informasi, yang terdiri dari kombinasi berupa teknologi informasi, orang dan proses. Layanan pendukung merupakan layanan yang tidak digunakan secara langsung oleh pengguna tetapi diperlukan oleh penyedia layanan untuk memberikan layanan yang langsung digunakan oleh pengguna.



## Jenis Jenis Layanan Teknologi Informasi

#### 1. Menurut Hunnebeck

Menurut Hunnebeck, perbedaan jenis layanan dapat dibagi menjadi 2 yaitu: 

##### a. customer-facing services

Layanan teknologi informasi yang terlihat dan dirasakan langsung oleh pengguna. Layanan ini biasanya merupakan layanan yang mendukung unit bisnis pengguna/proses bisnis, yang memberikan hasil yang diinginkan pengguna secara langsung.

##### b. supporting services, 

layanan teknologi informasi yang mendukung customer-facing services. Layanan ini biasanya tidak terlihat oleh pengguna, tetapi penting untuk memberikan customer facing services. 

Layanan pendukung dapat terdiri dari banyak nama jenis yang berbeda seperti layanan infrastruktur, layanan jaringan, layanan aplikasi atau layanan teknis


#### 2. Menurut Susanto

Menurut Susanto, layanan-layanan teknologi informasi dapat dibedakan dan dikelompokkan berdasarkan:

##### 1. Hubungan Penyedia Layanan

1. Internal services adalah layanan teknologi informasi yang disampaikan kepada unit-unit dalam organisasi yang sama dengan penyedia layanan
   
2. External Services adalah layanan teknologi informasi yang disampaikan kepada pelanggan di luar organisasi penyedia layanan, umumnya merupakan layanan komersial

##### 2. Manfaat Layanan

1. **Core services** adalah layanan teknologi informasi yang menyediakan kebutuhan utama pelanggan (umumnya terkait fungsi-fungsi penting suatu bisnis) dan memberikan nilai yang diinginkan oleh satu atau beberapa pelanggan
   
2. **Enabling services** adalah layanan teknologi informasi yang dibutuhkan agar core services dapat disediakan. Hal ini merupakan faktor dasar agar pelanggan dapat menerima layanan yang ada.
   
3. **Enhancing Services** adalah layanan teknologi informasi yang memberikan nilai tambah bagi core services. Layanan teknologi informasi yang membuatnya lebih menarik akan mendorong pelanggan untuk menggunakannya.

#### 3. Interaksi

1. Customer-facing services.
2. Supporting services



## Manajemen Layanan Teknologi Informasi

Manajemen layanan teknologi informasi merupakan aktivitas merancang, memberikan, mengelola, dan meningkatkan cara bisnis memanfaatkan layanan teknologi informasi. 

Manajemen layanan teknologi informasi memastikan dalam pengelolaan teknologi, orang-orang dan proses yang tepat digunakan untuk menghasilkan nilai tambah

#### Menurut ITIL V3,

proses manajemen layanan teknologi informasi terdiri atas:

1. **strategi layanan**, tahapan ini membentuk kerangka dasar pembuatan proses manajemen layanan teknologi informasi.
   
2. **desain layanan**, merencanakan dan merancang layanan teknologi informasi yang diberikan perusahaan untuk memenuhi tuntutan bisnis dan pasar.
   
3. **transisi layanan**, memastikan bahwa proses mengalir seperti yang dirancang, mengevaluasi segala jenis perubahan teknologi informasi yang dapat mencakup perubahan strategis, operasional dan taktis selama perencanaan transisi
   
4. **operasi layanan**, tahap ini terdiri dari penerapan hasil rancangan yang diuji di lingkungan operasional. Proses pemantauan pada proses harus dilakukan dengan cermat karena memungkinkan adanya masalah ketika pengguna atau pelanggan memulai pemanfaatan layanan.
   
5. **peningkatan layanan** yang berkesinambungan, berdasarkan parameter kinerja, dilakukan identifikasi terhadap area yang memerlukan upaya peningkatan



## Stakeholder Layanan Teknologi Informasi

Penyedia layanan teknologi informasi adalah suatu organisasi atau perusahaan atau unit yang menyediakan layanan teknologi informasi untuk customer. 

Terdapat 3 pilihan penyedia layanan:

1. Internal service merupakan suatu bagian organisasi yang menyediakan layanan teknologi informasi khusus untuk satu organisasi yang sama.
   
2. Shared service unit adalah unit departemen atau unit teknologi informasi yang menyediakan layanan teknologi informasi khusus untuk banyak bisnis dalam organisasi yang sama.
   
3. External service provider, merupakan perusahaan yang menyediakan layanan teknologi informasi untuk pelanggan di luar perusahaan

#### Stakeholder Layanan

Stakeholder layanan teknologi informasi dibagi menjadi 2 yaitu:

##### 1. Internal

Internal dibedakan menjadi:

- Function, menjelaskan struktur organisasi, sekaligus lokasi sumber daya manusia pelaksana aktivitas proses manajemen layanan teknologi informasi. Setiap function memiliki service asset (resource dan capabilities).
  
- Grup, merupakan sekelompok orang yang melakukan aktivitas serupa, misalnya sekelompok orang menangani manajemen. Grup umumnya tidak tampak dalam struktur formal organisasi.
  
- Team, merupakan sekelompok orang bekerjasama untuk mencapai tujuan tugas tertentu dan lebih terstruktur secara formal dalam organisasi. Contoh, tim pelaksana suatu proyek teknologi informasi atau tim pengembang aplikasi.

##### 2. Eksternal

1. Customer merupakan seseorang yang membeli barang atau jasa. Dalam konteks layanan teknologi informasi pelanggan adalah orang atau kelompok orang yang menyetujui SLA (Service Level Agreement). Terbagi dalam 2 jenis customer:
	
	- Internal customer, yakni orang atau unit organisasi pengguna layanan teknologi informasi yang bekerja di organisasi atau perusahaan yang sama dengan penyedia layanan teknologi informasi
	
	- Eksternal customer, yakni orang atau institusi pengguna layanan teknologi informasi yang tidak bekerja di organisasi atau perusahaan yang sama dengan penyedia layanan teknologi informasi

2. Pengguna merupakan seseorang yang langsung dan secara rutin memakan layanan teknologi informasi setiap hari
   
3. Supplier merupakan pihak ketiga di luar organisasi penyedia layanan yang membantu menyediakan barang atau jasa yang dibutuhkan untuk mewujudkan layanan-layanan teknologi informasi penyedia layanan tersebut



## Nilai Layanan Teknologi Informasi

Nilai layanan merupakan manfaat atau keuntungan yang diharapkan dari suatu layanan. Setiap layanan bertujuan menciptakan dan menyampaikan value yang tepat kepada pelanggan.

Berdasarkan sudut pandang pelanggan nilai suatu layanan adalah kombinasi antara fungsi layanan (Utility) dan kualitas layanan (Warranty)

![[Screenshot 2024-10-07 at 21.59.41.png]]
1. Utility adalah sesuatu yang pengguna dapat dari layanan. Utility suatu layanan, diukur berdasarkan jumlah manfaat yang dapat diperoleh oleh pengguna. Utility digunakan untuk menunjukan tingkat kinerja dari layanan dan untuk memperbaiki kinerja tugas yang dibutuhkan untuk mencapai suatu hasil atau untuk menghilangkan hambatan yang mencegah agar tugas tidak dilakukan secara memadai.
   
2. Warranty adalah bagaimana layanan disediakan atau bagaimana kualitas layanan atau jaminan bahwa suatu layanan memenuhi service level agreement. Utility terkait seberapa besar manfaat menggunakan suatu layanan teknologi informasi, sedangkan warranty terkait dengan kenyamanan atau seberapa kecil kemungkinan kehilangan atau kerugian saat menggunakan layanan teknologi informasi. Warranty mengharuskan layanan tersedia, berkesinambungan dan aman serta memiliki kapasitas yang memadai agar layanan dapat dilakukan pada tingkat yang dipersyaratkan.
   
   Manfaat dari utility dapat berupa:
   
3. Peningkatan kinerja, dukungan terhadap pencapaian kinerja, kebutuhan, atau keinginan pelanggan.
   
4. Mengurangi keterbatasan (constraint), mengatasi keterbatasan pelanggan mencapai tujuan tertentu.

#### Warranty Layanan Teknologi

Warranty layanan teknologi informasi mencakup 4 aspek berikut.

1. **Ketersediaan (Availability)**: memastikan bahwa layanan selalu tersedia atau dapat digunakan pada waktu dan lokasi yang disepakati
   
2. **Kapasitas (Capacity)**: memastikan kapasitas layanan sistem tersedia bagi semua pengguna dan sesuai dengan kebutuhan sistem
   
3. **Kontinuitas (Continuity)**: memastikan tersedianya alternatif sistem lain yang dapat digunakan ketika sistem utama bermasalah sehingga pengguna tetap dapat memanfaatkan layanan.
   
4. **Keamanan (Security)**, memastikan tingkat keamanan terhadap sistem atau layanan serta melindungi informasi dan kepentingan pengguna


#### Nilai Berdasarkan Sudut Pandang Pelanggan

Nilai suatu layanan dapat dilihat dari sudut pandang pelanggan maupun penyedia layanan, berikut merupakan karakteristik dari nilai berdasarkan sudut pandang pelanggan:

1. Value didefinisikan oleh pelanggan, syarat nilai layanan terpenuhi jika suatu layanan menyediakan utility yang cocok dengan keinginan pelanggan (fit for purpose) dan warranty yang baik (fit for use). Fit for purpose terpenuhi apabila salah satu manfaat utility terpenuhi, fit for use terpenuhi apabila seluruh warranty terpenuhi.
   
2. Pelanggan akan memilih layanan yang menyediakan kombinasi utility dan warranty terbaik dengan harga terjangkau
   
3. Value diukur pelanggan tidak selalu berdasar uang, tergantung pada pemenuhan terhadap tujuan/kebutuhan. Persepsi pelanggan terhadap nilai suatu layanan dipengaruhi 3 hal:
	
	1. Business outcomes, tujuan bisnis/kebutuhan pelanggan apa yang terpenuhi oleh layanan
	   
	2. Preferences, pilihan/selera pelanggan
	   
	3. Perceptions, persepsi pelanggan terhadap layanan

4. Value berubah seiring berjalannya waktu dan kondisi, untuk dapat memengaruhi pelanggan agar menggunakan layanan maka penyedia layanan teknologi informasi harus membantu pelanggan menghitung nilai yang diperoleh dari layanan teknologi informasi dengan cara:
	
	1. menyesuaikan dengan pilihan/selera pelanggan
	   
	2. menyediakan dan mempromosikan informasi terkait layanan apa yang disediakan oleh sistem teknologi informasi
	   
	3. menyampaikan biaya layanan

#### Nilai Bagi Penyedia Layanan

Bagi penyedia layanan, nilai suatu layanan harus diciptakan. Untuk menciptakan nilai, maka penyedia layanan harus memiliki service asset. Berdasarkan sudut pandang penyedia layanan teknologi informasi, nilai suatu layanan adalah kombinasi antara fungsi sumberdaya (resource) dan kemampuan (capability) yang harus dimiliki penyedia layanan untuk menyediakan layanan

![[Screenshot 2024-10-07 at 22.11.17.png]]

##### 1. Sumberdaya Teknologi Informasi (Resource)

Sumberdaya teknologi informasi merupakan komponen-komponen sistem teknologi informasi yang masih harus diolah untuk menghasilkan layanan teknologi informasi, yaitu:

1. uang/modal
2. infrastruktur teknologi informasi (hardware)
3. aplikasi (software)
4. informasi (data, record)
5. orang (jumlah karyawan)

##### 2. Kemampuan Teknologi Informasi (Capability)

Kemampuan teknologi informasi merupakan sejumlah kemampuan organisasi untuk mengolah/mengelola sumberdaya teknologi informasi menjadi layanan teknologi informasi, yaitu:

1. kemampuan manajemen (culture, leadership)
2. organisasi (struktur, tugas, fungsi)
3. proses-proses yang telah berjalan
4. pengetahuan (knowledge)
5. orang (pengalaman, keahlian, personal network)


#### Layanan Informasi yang Menghasilkan Nilai

Untuk memperoleh layanan teknologi informasi yang menghasilkan nilai, terapkan proses layanan teknologi informasi berikut.

1. Lakukan perencanaan strategis (jangka panjang) yang baik
2. Rancang detil setiap sistem layanan,
3. Realisasi implementasi setiap rancangan dengan baik,
4. Operasional penyampaian layanan teknologi informasi yang selalu terjaga,
5. Mengevaluasi, memperbaiki, dan meningkatkan setiap proses layanan secara berkesinambungan. 



## Bentuk Layanan Teknologi Informasi

Dalam penerapannya bentuk layanan teknologi informasi terus berkembang dan bervariasi, beberapa diantaranya:

##### 1. Penyediaan dan Pengelolaan Perangkat Infrastruktur Teknologi Informasi dan Jaringan

Perusahaan pengadaan perangkat atau sistem teknologi informasi menyediakan semua peralatan yang dibutuhkan untuk menyiapkan jaringan maupun infrastruktur teknologi informasi lainnya. Penyedia layanan dapat mengatur jaringan telekomunikasi, termasuk koneksi internet. 

Sebagian besar perusahaan pengadaan juga menyediakan layanan pemeliharaan dan manajemen asset serta menyediakan peningkatan perangkat dan juga perbaikan terhadap peralatan yang rusak secara fisik

##### 2. Penyedia Layanan Solusi Keamanan Informasi

Layanan ini berfungsi untuk melindungi komputer dan jaringan dari serangan digital. Langkah-langkah keamanan siber yang efektif dapat mencegah program jahat ini masuk ke jaringan. Hal ini menjadikan keamanan siber sebagai layanan teknologi informasi yang penting. 

Mekanisme yang dilakukan oleh penyedia keamanan siber adalah memasang dan memelihara program perlindungan malware, memantau data yang masuk dan keluar dari jaringan. Selain itu, melacak semua perangkat yang terhubung ke jaringan

##### 3. Layanan Berbasis Cloud

Layanan berbasis cloud merupakan layanan teknologi informasi yang dioperasikan dari fasilitas jarak jauh. Penyedia layanan cloud menyewakan perangkat keras, perangkat lunak, dan sistem operasi kepada klien. 

Layanan cloud menghilangkan kebutuhan bisnis untuk memiliki banyak ruang fisik. Ini juga membebaskan bisnis dari perawatan peralatan yang mahal. 

Banyak layanan berbasis cloud juga dapat diskalakan, sehingga Anda dapat meningkatkan atau menurunkan spesifikasi sistem sesuai kebutuhan.

Beberapa jenis layanan berbasis cloud antara lain:

1. **Infrastructure as a Service (IaaS)**, memungkinkan perusahaan untuk melakukan outsourcing kebutuhan infrastruktur komputasi kepada penyedia layanan cloud IaaS. Salah satu contoh penerapan layanan Iaas adalah web hosting.
   
2. **Platform as a Service (PaaS)**, menyediakan infrastruktur dan daya komputasi. Penyedia layanan dapat menyediakan tempat penyimpanan data, sistem operasi, dan bahasa pemrograman. Semua aktivitas peningkatan dan pemeliharaan sistem juga ditanggung oleh penyedia pihak ketiga.
   
3. **Software as a Service (SaaS)**, menyediakan software yang dapat digunakan oleh klien secara jarak jauh. Salah satu contoh penerapan Saas, Google Form dan Gmail. 

##### 4. Penyedia Layanan Komunikasi Berbasis Internet

Penyedia layanan teknologi informasi juga dapat menginstal menyediakan layanan komunikasi berupa VOIP (voice over IP). VOIP adalah perangkat teknologi informasi yang berfungsi sebagai platform komunikasi, selain saluran telepon (PSTN). 

VoIP menghubungkan panggilan telepon melalui Internet. Beberapa contoh sistem VoIP antara lain Skype dan WhatsApp

Layanan komunikasi berbasis internet lainnya adalah video conference, komunikasi jarak jauh yang memanfaatkan jaringan internet untuk melakukan panggilan dan komunikasi video, salah satu contohnya layanan yang diberikan oleh Zoom

##### 5. Layanan Technical Support

Bentuk layanan teknologi informasi lainnya adalah layanan yang dapat memberikan dukungan teknis terhadap pemanfaatan maupun permasalahan teknis terhadap perangkat maupun sistem teknologi informasi


