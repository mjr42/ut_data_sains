---
tags:
  - sistem_informasi_management
  - materi_6_SIM
---
# [[Kegiatan Belajar 1 - Teknologi Perangkat Keras]]

Perangkat keras (hardware) sebagai subsistem dari sistem komputer juga mempunyai komponen, yaitu komponen alat masukan (input device), komponen alat pemroses (processing device), komponen alat keluaran (output device), dan komponen alat simpanan luar (storage)

## Alat Masukan

Alat masukan (input device/input unit/input equipment) adalah alat yang digunakan untuk menerima masukan yang dapat berupa masukan data ataupun masukan program

Beberapa alat masukan mempunyai fungsi ganda, yaitu sebagai alat masukan sekaligus sebagai alat keluaran (output) untuk menampilkan hasil. Alat input/output (I/O) demikian ini disebut dengan terminal

Alat masukan dapat digolongkan dalam beberapa golongan, yaitu:

#### 1. Keyboard

Keyboard adalah alat input yang paling umum dan banyak digunakan. Input dimasukkan ke alat proses dengan cara mengetikkan lewat penekanan tombol yang ada di keyboard. 

Keyboard sebagai alat input biasanya didampingi dengan suatu tampilan (display) yang akan menampilkan apa yang ditekan di keyboard. Keyboard dengan display ini merupakan suatu terminal.

#### 2. Pointing Device

Untuk keperluan tertentu, misalnya pembuatan grafik, gambar, atau pemilihan suatu icon di layar, penggunaan keyboard kurang memuaskan. Alat input yang berupa pointing device akan lebih tepat digunakan.Yang termasuk dalam kategori alat ini adalah mouse, touchscreen, light pen,dan digitizer graphic tablet

#### 3. Scanner

Alat masukan scanner bekerja dengan cara meraba secara elektronik input yang akan dibaca. Alat peraba banyak digunakan karena akan membuat proses pemasukan data lebih cepat dan akurat dibandingkan jika harus dimasukkan lewat keyboard. Alat masukan scanner dapat berupa magnetic ink character recognition (MICR) reader dan optical data reader

###### MICR (Magnetic Ink Character Recognition) Reader

Bentuk pertama dari alat peraba (scanner) adalah alat pembaca pengenal karakter tinta magnetis atau magnetic ink character recognition (MICR) reader.

Dengan MICR, dibutuhkan tinta magnetis yang khusus supaya bisa dibaca oleh alatnya

###### Optical Data Reader

Optical data reader mempunyai kemampuan untuk membaca data langsung dari kertas biasa dan tanpa menggunakan tinta magnetisyang khusus. 

Bentuk karakter yang paling populer adalah OCR A yang dikembangkan oleh business equipment manufacture association (BEMA). Bentuk karakter lain yang dapat dibaca oleh OCR reader adalah bentuk OCR B dan bentuk OCR E. OCR E mempunyai bentuk yang sama dengan bentuk karakter pada MICR

Optical data reader dapat berupa optical character recognition (OCR) reader, OCR tagreader, barcode reader dan optical mark recognition (OMR) reader

1. **OCR Reader**
   
   OCR reader dapat membaca dokumen yang ditulis dengan tangan. Beberapa OCR reader masih mampu mengenal karakter yang dibaca walaupun 80% dari karakter tersebut tidak jelas. OCR reader yang lama masih mempunyai tingkat kesalahan pembacaan yang cukup tinggi, yaitu sampai 15%, tetapi OCR reader yang sekarang, tingkat kesalahan pembacaan kecil, yaitu kurang dari 1% atau tanpa kesalahan sama sekali apabila karakter yang ditulis cukup sempurna.

2. **OCR Tag Reader**
   
   OCR tag reader banyak dipergunakan di toko-toko serba ada untuk membaca label data barang yang dijual yang dicetak dengan bentuk (font) karakter OCR. OCR tag reader dilekatkan pada POS terminal yang dihubungkan dengan pusat komputer.

3. **Barcode Reader**
   
   Bar code reader untuk membaca label data barang dagangan yang dicetak dalam bentuk kode batang (bar code). Bar code reader dapat berupa bar code wand (alat peraba berbentuk batang pena) dan bar code window (alat peraba berbentuk jendela kaca). Bar code wand membaca kode batang dengan menggeserkan batang penanya ke kode batangnya.

4. **Barcode Window**
   
   Barcode window membaca kode batang dengan menggeserkan kode batangnya di jendela peraba. Kode batang (bar code) yang paling banyak dipergunakan adalah sistem universal product code (UPC). 
   
   UPC menggunakan 10 kode digit yang terdiri atas lima digit pertama menunjukkan identitas pabrik danlima digit berikutnya menunjukkan kode barang dan ukurannya. 
   
   Alat peraba kode batang melakukan kesalahan pembacaan kurang dari satu kesalahan dari 10,000 transaksi pembacaan, sedangkan operator berpengalaman melakukansatu kali kesalahan penekanan tombol keyboard dari 1000 kali penekanan tombol

5. **Optical Mark Recognition**
   
   Optical mark recognition (OMR) reader sekarang banyak digunakan untuk penilaian test (testscoring). Jawaban dari tes yang diberikan dijawab di kertas mark sense form dengan menandai tempat jawaban menggunakan pensil hitam (umumnya jenis 2B

#### 4. Censor

Censor merupakan alat yang mampu secara langsung menangkap data kejadian fisik. Data analog dikumpulkan oleh alat sensor dan dimasukkan ke pengubah analog-to-digital converter yang berikutnya akan diproses oleh komputer.

#### 5. Voice Recognizer

Voice recognizer atau speech recognizer membuat komputer mengerti omongan manusia. Voice recognizer menggunakan microphone untuk menangkap suara input. Digital camera, camcorder dan voice recognizer termasuk dalam perlengkapan dasar multimedia dan mulai banyak digunakan untuk teleconference



## Alat Pemproses

Alat pemroses (processingdevice) adalah alat ketika instruksi-instruksi program dieksekusi untuk memproses data yang dimasukkan lewat alat masukan yang hasilnya nanti akan ditampilkan di alat output. Alat pemroses terdiri atas:

#### 1. Central Processing Unit (CPU)

Central processing unit (CPU) merupakan tempat pemrosesan instruksi-instruksi program. Pada komputer mikro, processor ini disebut dengan microprocessor. CPU terdiri atas dua bagian utama, yaitu unit kendali (control unit) serta unit aritmatika dan logika (ALU).

Di samping dua bagian utama tersebut, CPU mempunyai beberapa simpanan yang berukuran kecil yang disebut dengan register

##### a. Control Unit

Control unit mengartikan instruksi-instruksi dari program komputer, membawa data dari alat input ke main memory, serta mengambil data dari main memory untuk diolah

Hasil dari pengolahan data ini dibawa oleh control unit ke main memory untuk disimpan. Dengan demikian, tugas dari control unit sebagai berikut:

1. Mengatur dan mengendalikan alat-alat input dan output.
   
2. Mengambil instruksi-instruksi dari main memory.
   
3. Mengambil data dari main memory kalau diperlukan oleh proses.
   
4. Mengirim instruksi ke arithmetic and logic unit apabila ada perhitungan aritmatika atau perbandingan logika serta mengawasi kerja dari arithmetic and logic unit
   
5. Menyimpan hasil proses ke main memory

##### B. Arithmetic and Logic Unit (ALU)

Tugas utama dari arithmetic and logic unit (ALU) adalah melakukan semua perhitungan aritmatika atau matematika yang terjadi sesuai dengan instruksi program. 

ALU melakukan operasi aritmatika dengan dasar pertambahan, sedangkan operasi aritmatika yang lainnya, seperti pengurangan, perkalian, dan pembagian, dilakukan dengan dasar penjumlahan. 

Oleh karena dasar operasi aritmatika di ALU adalah penjumlahan,sirkuit elektronik di ALU yang digunakan untuk melaksanakan operasi aritmatika ini disebut adder. 

Tugas lain dari ALU adalah melakukan keputusan dari operasi logika sesuai dengan instruksi program

##### C. Register

Register merupakan simpanan kecil yang mempunyai kecepatan tinggi, lebih cepat sekitar limasampai 10 kali dibandingkan dengan kecepatan perekaman atau pengambilan data di main memory. 

Register digunakan untuk menyimpan instruksi dan data yang sedang diproses oleh CPU, sedangkan instruksi-instruksi dan data lainnya yang menunggu giliran untuk diproses masih disimpan di main memory


#### 2. Memori Utama (Main Memory)

Alat pemroses dilengkapi dengan simpanan yang kapasitasnya lebih besar, yaitu main memory atau disebut juga dengan main storage, internal memory, internal storage, primary storage, temporary storage atau immediate access storage. Memori utama (main memory) terdiri atas random access memory (RAM) dan read only memory (ROM)

##### 1. Random Access Memory (RAM)

digunakan untuk menyimpan program dan data yang akan diproses oleh CPU. RAM dapat dibayangkan sebagai sekumpulan kotak yang masing-masing kotak dapat menyimpan suatu penggal informasi, baik berupa data maupun instruksi. Tiap-tiap lokasi dari kotak ditunjukkan oleh suatu alamat (address)

Kode yang dipergunakan untuk mewakili suatu karakter tergantung dari komputer yang digunakan, dapat berbentuk sistem kode binary coded decimal (BCD), sistem kode extended binary coded decimal interchange code (EBCDIC), atau sistem kode American standard code for information interchange (ASCII). 

Kode BCD banyak digunakan di komputer generasi awal. Kode EBCDIC (diucapkan ib-si-dik) dikembangkan oleh IBM pada tahun 1950-andengan menggunakan delapan bit dan banyak digunakan di komputer besar (mainframe). 

Kode ASCII (diucapkan aski) dikembangkan oleh American National Standards Institute (ANSI) dan banyak digunakan di komputer mikro

##### 2. Read Only Memory (ROM)

Read only memory(ROM), dari namanya, memori ini hanya dapat dibaca dan tidak dapat diisi. Isi ROM sudah diisi oleh pabrik pembuatnya yang berupa bootstrap program dan basic input output systems (BIOS). Bootstrap program diperlukan untuk mengambil pertama kali sistem operasi dari diskette atau dari harddisk.

Basic input output systems (BIOS) merupakan perangkat lunak untuk mengoperasikan alat-alat input/output di sistem komputer. Instruksi-instruksi yang tersimpan di ROM ini disebut juga dengan micro instructions atau micro code atau disebut juga dengan firmware karena hardware dan software dijadikan satu oleh pabrik pembuatnya. 

ROM itu adalah hardware, sedangkan micro instructions adalah software


## Alat Keluaran

Output yang dihasilkan dari pengolahan data dapat digolongkan dalam tigamacam bentuk, yaitu tulisan (huruf, kata, angka, karakter khusus, dan simbol-simbol lain), image (bentuk grafik atau gambar),serta suara (bentuk musik atau omongan). 

Untuk mendapatkan bentuk-bentuk output tersebut,mdibutuhkan alat untuk menampilkannya, yaitu alat keluaran, alat output, output device, atau output unit

#### 1. Hard Copy Device

Hardcopy device merupakan alat keluaran yang digunakan untuk mencetak tulisan (kata, angka, karakter khusus dan simbol-simbol lain) serta citra berupa grafik atau gambar pada media hard (keras), misalnya kertas atau film.

Alat output hardcopy device yang umum dipergunakan adalah printer yang digolongkan dalam dua kategori impact printer dan nonimpact printer. Alat output hardcopy device yang lain adalah plotter dan computer output to microfilm

#### 2. Soft Copy Device

Soft copy device merupakan alat yang digunakan untuk menampilkan tulisan (kata, angka, karakter khusus dan simbol-simbol lain), image (grafik atau gambar), dan suara (voice) pada media soft(lunak) yang berupa sinyal elektronik. Yang termasuk dalam softcopy device adalah video display, flat panel display dan speaker


## Alat Simpanan Luar

Kadang-kadang diperlukan suatu simpanan yang mempunyai kapasitas besar dan bersifat nonvolatile untuk menyimpan data dan program dalam kurun waktu yang tertentu. Simpanan yang mempunyai ciri-ciri tersebut adalah external memory (simpanan luar karena terletak di luar alat prosesnya) atau disebut:

1. Mass storage (simpanan massal karena kapasitas umumnya lebih besar dari main memory), 
   
2. Secondary storage (simpanan kedua, simpanan pertama adalah main memory)  
   
3. Auxiliary storage (simpanan tambahan, simpanan utama adalah main memory), 
   
4. Permanent storage (simpanan tetap karena nonvolatile), 

5. Backing storage (simpanan pendukung) atau disebut juga computer data bank (bank data komputer)

Simpanan luar dapat digolongkan ke dalam sequential-access storage device (SASD), alat simpanan pengaksesan urut dan direct-access storage device (DASD), atau alat simpanan pengaksesan langsung

#### 1. Sequential-Access Storage Devices (SASD)

Data yang disimpan di sequential-access storage device (SASD) tidak dapat dilakukan pengaksesan secara langsung di posisinya (seperti mencari lagu di pita cassette). 

Kapasitas SASD cukup besar dan harga per bit informasi yang dapat direkam murah, tetapi kecepatannya juga lebih lambat.

Simpanan luar yang termasuk dalam SASD adalah punched card, paper tape dan magnetic tape

#### 2. Direct-Access Storage Devices (DASD)

Data yang disimpan di direct-access storage device (DASD) dapat dilakukan pengaksesan secara langsung di posisinya (seperti mencari lagu di piringan hitam atau di CD ROM). 

Dibandingkan dengan main memory, kapasitas DASD umumnya lebih besar dan harga per bit informasi yang dapat direkam lebih murah, tetapi kecepatannya lebih lambat

Simpanan luar yang termasuk dalam DASD di antaranya adalah magnetic disk, tape strip cartridge dan optical disk

##### 1. Magnetic Disk

Magnetic disk (piringan/disk magnetis) adalah simpanan luar yang terbuat dari satu atau lebih piringan yang bentuknya seperti piringan hitam yang terbuat dari metal atau dari plastik dan permukaannya dilapisi dengan lapisan magnet iron-oxide. 

Disk magnetis yang terbuat dari plastik dan terdiri atas sebuah piringan saja disebut dengan floppy disk, yaitu microdisk dan mini disk, sedangkan yang terbuat dari metal dan terdiri atas banyak piringan disebut dengan harddisk.

##### 2. Tape Strip Catridge

IBM menyebut tape strip cartridge dengan istilah mass storage systems. Misalnya, IBM 3.850 mass storage systems menggunakan suatu strip pita magnetisyang panjangnya 770 inci dengan lebar 3 inci. Masing-masing strip pita magnetis digulung dan disimpan di suatu silinder cartridge berdiameter 2 inci dan panjangnya 4 inci. 

Tiap-tiap cartridge dapat menyimpan data sampai 50 juta byte dan diletakkan pada suatu tempat berbentuk sel-sel yang menyerupai rumah lebah tempat madu (honeycomb). Tiap-tiap sel digunakan untuk menempatkan sebuah cartridge

##### 3. Optical Disk

Optical disk ini disebut juga dengan nama compact disk - read only memory (CD-ROM), compact disks, atau laser optical disks. CD-ROM mempunyai ukuran diameter 12 cm (4,75 inci) dan dapat menyimpan sampai dengan 660 MB (megabyte) yang ekuivalen dengan lebih dari 400 microdisk berukuran 1,44 MB. 

CD-ROM menggunakan teknologi sinar laser dan bersifat WORM (write once, read many), yaitu hanya dapat direkam sekali dan tidak dapat dihapus, tetapi dapat dibaca berkali-kali

Dengan teknologi compact disk - recordable (CD-R), hal itu memungkinkan seseorang untuk membuat CD-ROM sendiri dengan merekamkan data ke CD ROM yang menggunakan alat rekam CD-R. Teknologi terbaru adalah CD-rewritable (CD-RW), yaitu teknologi CD yang dapat direkam berulang-ulang. 

Teknologi digital video disks (DVD) atau disebut juga digital versatile disks merupakan optical disk yang mempunyai ukuran fisik sama dengan CD-ROM, tetapi dengan kapasitas yang lebih besar. Sebuah DVD dapat menyimpan minimum 4.7 GB yang cukup untuk merekam film dengan masa putar dua jam.



## Ukuran Memori

Kapasitas dari memori secara umum, baik memori utama maupun memori luar, dihitung dengan satuan byte. Satu byte terdiri atas delapan binary digit (bit)jika komputernya menggunakan kode bilangan delapan bit (misalnya kode EBCDIC dan ASCII). Seribu bytes (tepatnya 1024 bytes) disebut dengan satu kilobyte (KB). Satu megabyte (MB) terdiri atas 1024 kilobytes. Satu gigabyte (GB) terdiri atas 1024 megabytes dan satu terabyte (TB) terdiri atas 1024 gigabytes

![[Screenshot 2024-10-09 at 10.49.28.png]]



## Ukuran Kecepatan Proses

Kecepatan proses komputer ditunjukkan dengan satuan kecepatan komputer siklus mesin (machinecycle) per detiknya. Komputer yang lambat mempunyai kecepatan proses dengan ukuran milliseconds (ribuan siklus mesin per detik). Komputer yang lebih cepat menggunakan ukuran microseconds (jutaan siklus mesin per detik). Komputer yang lebih cepat lagi menggunakan ukuran nanoseconds (miliaran siklus mesin per detik). Komputer yang sangat cepat menggunakan ukuran picoseconds (triliunan siklus mesin per detik

Ukuran lain dari siklus mesin per detik adalah satuan Hertz. Kecepatan proses 1 KHz (Kilo Hertz) sama dengan seribu siklus mesin per detik, 1 MHz (Mega Hertz) sama dengan 1 juta siklus mesin per detik, 1 GHz (Giga Hertz) sama dengan 1 miliar siklus mesin per detik, dan 1 THz (Tera Hertz) sama dengan 1 triliun siklus mesin per detik

![[Screenshot 2024-10-09 at 10.51.22.png]]

Satuan ukuran lain dari kecepatan komputer adalah dihitung dari kecepatannya mengolah instruksi program. Ukuran satuan millions of instructions per second (MIPS) menunjukkan kemampuan mengolah jutaan instruksi program per detik. 

Satuan ukuran lainnya dari kecepatan komputer adalah dihitung dari kecepatannya memproses perhitungan dasar (pertambahan) bilangan pecahan (floatingpoint). Ukuran satuan millions of floating points per second (MFLOATS) menunjukkan kemampuan menghitung jutaan bilangan pecahan per detik



## Klasifikasi Komputer

Pengklasifikasian yang umum berdasarkan kemampuannya, yaitu kecepatan dan kapasitasnya. Berdasarkan hal ini, komputer dapat diklasifikasikan sebagai komputer mikro, komputer mini, komputer mainframe dan komputer super

![[Screenshot 2024-10-09 at 10.53.11.png]]

---


# [[Kegiatan Belajar 2 - Teknologi Perangkat Lunak]]

## Perangkat Lunak Sistem Operasi

Sistem operasi (operating systematau banyak disebut dengan singkatannya OS) merupakan program yang ditulis untuk mengendalikan dan mengoordinasi kegiatan operasi dari sistem komputer

OS secara formal pertama kali dikembangkan untuk komputer IBM 701 pada tahun 1954 dan pada tahun 1955 oleh General Motors Research Laboratories. Pada waktu itu, tujuan utama dari OS adalah mengurangi waktu menganggur (idle time) dari CPU dan digunakan untuk menjalankan beberapa tugas (job) komputer bersama-sama yang dikumpulkan terlebih dahulu (batch)

Pada April 1964, IBM memperkenalkan OS yang disebut dengan OS/360 untuk dipergunakan pada semua seri komputer Sistem 360

Apple DOS merupakan contoh suatu OS yang hanya dapat digunakan pada komputer Apple, sedangkanCP/M, MS-DOS, Windows, dan UNIX merupakan contoh OS yang dapat diterapkan pada beberapa merek komputer. Apple DOS, CP/M, Windows, dan MS-DOS merupakan OS untuk komputer mikro, sedangkan UNIX merupakan OS, baik untuk komputer mikro maupun komputer mini

Sumber-sumber daya sistem komputer yang harus dikelola oleh sistem operasi supaya efisien dan efektif adalah memori utama, processor, memori luar (harddisk) dan alat-alat I/O lainnya. 

Oleh karena sebagai manajer, sistem operasi harus melakukan kegiatan-kegiatan manajemen memori (memory management), manajemen alat pengolah (processor management), manajemen informasi di disk (information management) dan manajemen alat-alat I/O (device management



## Perangkat Sistem Bantuan

OS juga menyediakan fasilitas sejumlah program bantuan yang disebut dengan operating system service atau utility (bantuan). Program-program bantuan ini misalnya adalah text editor(di Windows adalah notepad), beberapa bantuan untuk menangani disk (misalnya memformat, menyalin, mengecek diskdan sebagainya), menangani file (mengurutkan isi file dan mencarifile), menangani tampilan (menyetel ukuran layar),serta penanganan peralatan lainnya




## Perangkat Lunak Bahasa

Language software (perangkat lunak bahasa) merupakan program khusus yang sudah disediakan oleh pabrik komputer atau sudah dibuat oleh perusahaan perangkat lunak yang digunakan untuk mengembangkan program aplikasi. Program ini berfungsi sebagai penerjemah antara program yang ditulis dengan bahasa awam sehari-hari menjadi bahasa mesin (machine language) yang dimengerti oleh komputer

#### 1. Generasi Pertama

Bahasa mesin (machine language) merupakan perangkat lunak bahasa generasi pertama. Suatu instruksi program yang ditulis dalam bahasa mesin dapat berbentuk sebagai berikut. 000100110010

#### 2. Generasi Kedua

Perangkat lunak bahasa (language software) generasi kedua adalah assembler. Assembler merupakan program yang digunakan untuk menerjemahkan program aplikasi yang ditulis dengan bahasa perakit (assembly language) atau bahasa pemrograman simbolis (symbolic programming language) menjadi bahasa mesin

Instruksi program yang ditulis dengan mnemonic akan diterjemahkan ke dalam bentuk bilangan binari bahasa mesin dengan menggunakan assembler

#### 3. Generasi Ketiga

Source program yang ditulis dengan bahasa tingkat tinggi harus diterjemahkan menjadi program bahasa mesin dengan suatu program penerjemah, yaitu compiler dan interpreter. 

Bahasa tingkat tinggi yang sifatnya compilerdi antaranya adalah FORTRAN, COBOL, PASCAL dan C language; sedangkan yang bersifat interpreteradalah BASIC dan beberapa bahasa tingkat tinggi yang disediakan oleh data base management systems (DBMS

#### 3. Generasi Keempat

Perangkat lunak bahasa generasi keempat disebut juga dengan perangkat lunak bahasa nonprosedural (nonprocedural language) atau productivity language atau perangkat lunak bahasa tingkat sangat tinggi (very highlevel language). Disebut dengan perangkat lunak nonprosedural karena pemakai komputer dapat membuat program aplikasi dengan mudah, yaitu hanya memberikan instruksi apa yang harus diselesaikan

Disebut dengan very highlevel language menunjukkan tingkatan lebih tinggi daripadahigh bahasa tingkat tinggi (highlevel language) generasi ketiga. Perangkat lunak bahasa generasi keempat dapat dikelompokkan sebagai alat komputer mikro (microcomputer tools), bahasa kueri (query language) dan pembuat laporan (report generator), bahasa grafik (graphics language), pembuat aplikasi (application generator), paket perangkat lunak aplikasi (application software package) dan bahasa tingkat sangat tinggi (very highlevel programming language

![[Screenshot 2024-10-09 at 11.11.31.png]]

Beberapa perangkat lunak bahasa lainnya tidak dapat dimasukkan dalam kategori-kategori sebelumnya. Misalnya, tidak dapat dimasukkan sebagai kategori generasi keempat walaupun keberadaannya sama dengan perangkat lunak generasi keempat karena mereka mempunyai konsep yang berbeda. Perangkat-perangkat lunak bahasa ini adalah OOP(object-oriented programming), bahasa visual (visual language) dan bahasa-bahasa yang digunakan untuk pembuatan aplikasi internet, seperti Javadan HTML (hypertext markup language



## Perangkat Lunak Aplikasi

Perangkat lunak aplikasi(application software) merupakan program yang ditujukan untuk menyelesaikan suatu permasalahan dalam aplikasi tertentu yang sudah dibuat oleh pabrik pembuat perangkat lunak aplikasi. Program aplikasi dibuat dengan menggunakan perangkat lunak bahasa (language software). 

Perangkat lunak aplikasi dapat berupa perangkat lunak aplikasi tujuan umum (general purpose application software) dan perangkat lunak aplikasi tujuan khusus (special purpose application software)

#### 1. General Purpose Application Software

Perangkat lunak aplikasi tujuan umum (general purpose application software) ditulis untuk keperluan kebanyakan pemakai komputer secara umum. Aplikasi yang banyak dibutuhkan secara umum misalnya adalah aplikasi pengolah kata (word processing), kertas kerja elektronik (spreadsheet), DBMS (data base management systems)dan pengolah grafik (graphic editor)

#### 2. Special Purpose Application Software

Perangkat lunak aplikasi tujuan khusus (special purpose application software) ditulis untuk keperluan khusus. Aplikasi khusus di organisasi bisnis yang banyak dibutuhkan adalah aplikasi buku besar (general ledger), pengendalian persediaan (inventory control) di bidang akuntansi, manajemen kas (cash management), anggaran modal (capital budgeting) di bidang keuangan, CAD (computer aided design), pengendalian produksi (production control) di bidang produksi, analisis penjualan (sales analysis), dan analisis langganan (customers analysis) di bidang pemasaran