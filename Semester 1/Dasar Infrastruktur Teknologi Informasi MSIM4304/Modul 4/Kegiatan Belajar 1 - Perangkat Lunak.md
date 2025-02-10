---
tags:
  - dasar_infrastruktur_teknologi_informasi
  - materi_4_DITI
---
# Kegiatan Belajar 1 - Perangkat Lunak

Perangkat lunak menurut Roger S Pressman adalah suatu perintah program dalam komputer yang apabila dieksekusi oleh penggunanya akan memberikan fungsi dan unjuk kerja seperti yang diharapkan oleh penggunanya.

Program yang digunakan oleh komputer untuk mengatur dan mengontrol perangkat keras komputer dan program aplikasi dikenal sebagai software sistem. Software sistem akan diposisikan sebagai suatu platform yang digunakan oleh program aplikasi

Perangkat komputer dapat berfungsi untuk memproses data apabila ada gabungan dari dua buah komponen, yaitu perangkat keras dan perangkat lunak serta program aplikasi akan dapat berfungsi sesuai dengan instruksi program yang diberikan apabila ada software sistem

![[Screenshot 2024-10-06 at 17.43.17.png]]

Berdasarkan tugas dan fungsinya, software atau perangkat lunak dikelompokkan menjadi beberapa bagian, yaitu software yang bertindak sebagai sistem operasi, program aplikasi, program utility (tambahan) dan bahasa pemrograman


## [[01. Sistem Operasi]]

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


## [[02. Fungsi Sistem Operasi]]

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



## [[03. Kategorisasi Sistem Operasi]]

Sistem operasi terdiri dari beberapa kategori sebagai berikut.

#### Sistem operasi stand alone, 

Sistem operasi ini digunakan pada komputer desktop atau yang bertindak sebagai workstation. Contoh sistem operasi desktop ini antara lain: Microsoft Windows 8/10 , Ubuntu desktop, Apple Mac OS, dan sebagainya

#### Sistem operasi jaringan (Network Operating System/NOS), 

Sistem operasi ini digunakan pada jaringan komputer dan bertindak sebagai server. Sistem operasi server merupakan sistem yang menyediakan layanan bagi komputer klien yang terhubung dengan jaringan. Sistem operasi server memiliki lebih banyak fitur dan fungsi khusus dibandingkan dengan sistem operasi desktop. Misalnya pada sistem operasi server memiliki fungsi menyediakan fungsi pemasangan alamat IP  secara  otomatis terhadap komputer client, dengan memanfaatkan fitur DHCP (Dynamic Host Configuration Protocol). Beberapa contoh sistem operasi jaringan/server antara lain: Microsoft Windows Server 2012, Ubuntu Server, Centos, FreeBSD, UNIX dan sebagainya

#### Sistem operasi Embeded, 

sistem operasi jenis ini biasanya ditanam pada komputer kecil yang diperuntukan untuk tujuan khusus. Beberapa contoh sistem operasi embedded adalah IPhone OS, Windows CE, Windows mobile, Palm OS, Symbian OS, dan sebagainya.

#### Sistem operasi Live CD, 

sistem operasi ini dirancang khusus agar dapat berjalan menggunakan CD/DVD, USB. Contoh CD Knoppix, Windows Mini PE, Gentoo, dan sebagainya



## [[04. Device Driver]]

Semua perangkat keras tersebut bisa berfungsi dengan baik atau dapat dijalankan apabila perangkat tersebut sudah dikenali oleh sistem operasi. Agar perangkat keras komputer dapat dikenali oleh sistem operasi maka diperlukan peran dari device driver. Fungsi dari device driver dapat juga dikatakan sebagai perantara antara perangkat keras dengan sistem operasi

![[Screenshot 2024-10-06 at 18.03.44.png]]

![[Screenshot 2024-10-06 at 18.03.54.png]]

Device driver atau driver sendiri merupakan program yang memungkinkan perangkat dapat dikenali oleh sistem operasi. Device driver juga dapat difungsikan agar program aplikasi dapat menggunakan perangkat keras dalam menjalankan instruksinya

Device driver akan mengubah instruksi program yang diberikan oleh sistem operasi agar dapat dimengerti oleh perangkat keras komputer



## [[05. Utility Software]]

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




## [[06. Bahasa Pemprograman]]

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




## [[07. Perangkat Lunak Aplikasi Umum]]

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




## [[08. Perangkat Lunak Aplikasi Khusus]]

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



