---
tags:
  - dasar_infrastruktur_teknologi_informasi
---
# [[Kegiatan Belajar 1 - Perangkat Keras Komputer]]

## Klasifikasi Komputer

Komputer merupakan salah satu perangkat dalam konsep Teknologi Informasi (TI) yang digunakan untuk memepertukarkan data yang menjadi bahan awal sebelum bisa diolah menjadi suatu informasi. Selain komputer juga terdapat peranfgkat lain yang dugunakan unruk proses pertukaran data misalnya telepon dan lainnya. Proses pertukaran data antar komputer akan menggunakan jaringan dan sistem pengalamatan yang digunakan oleh perangkat dalam jaringan.

Definisi komputer sendiri merupakan suatu perangkat yang fungsi utamanya melakukan proses perhitungan (Compute). Komputer akan menerima masukan data kemudian data tersebut akan diproses program tertentu sehingga diperoleh hasil keluaran berupa informasi.

Dalam melakukan hal tersebut Komputer memerlukan bantuan perangkat keras seperti memory dan Processor (CPU) yang terdapat dalam komputer. Fungsi memori adalah untuk menyimpan data masukan kemudian akan diproses untuk dilakukan operasi hitung oleh processor (CPU)


#### 1. Embedded Computer

Embeded Computer adalah komputer yang diperuntukan untuk melakukan fungsi spesifik dan ditanam pada suatu sistem yang lebih besar. Berbeda dengan komputer pada umumnya yang lebih kita kenal dengan nama PC (Personal Computer) pada Embedded computer, kita hanya bisa melakukan satu fungsi tertentu saja dan tidak dapat melakukan fungsi lain di saat yang bersamaan.

Embedede conmputer akan menggunakan komponen pemprosesan data utama yang dinamakan microcontroller. Contoh yang paling sering dijumpai adalah Adruinni, Biasanya Adruino akan dipasang pasa suatu modul yang dapat berkomunikasi dengan modul pada perangkat lain secara wireless. mosul ini dikenal dengan nama LoRa (Long Range). Dengan bantuan internet alat ini dapat dikontrol dan dimonitor dari jarak jauh.

![[Screenshot 2024-09-02 at 14.50.10.png]]

Gabungan alat yang memiliki komponen input dan output serta jaringan penghubung untuk memonitor alat dari jarak jauh bisa disebbut dengan istilah IoT (Internet of Things)

Perangkat IoT sendiri terdiri atas tiga bagian yaitu :

- Input
  Bagian input akan dipasang sensor yang difungsikan untuk mengubah fenomena fisik seperti kelembaban udara atau pergerakan benda ke dalam bentuk impulse sinyal tertentu. Perangkat yang berfungsi untuk mengubah sinyal elektris ke gerakan mekanik dinamakan Actuator
  
- Pemproses
  Konsep sinyal digital digital dari komponen input akan digunakan sebagai masukan perangkat Microcontroller sehingga nantinya keputusan atau keluaran yang oleh perangkat mocrocontroller ada dua yaitu melakukan dan ditak melakukan aksi
  
- Output


---

#### 2. Perangkat Mobile

PPerbedaan utama antara komputer dan perangkat mobile terletak pada fleksibilitasnya. Perangkat mobile adalah komputer yang bisa digunakan dan dibawa kemana-mana. 

Perangkat mobile dirancang dengan ukuran yang lebih kecil dan mudah digenggam sehingga memudahkan pengguna untuk berkomunikasi secara bergerak (Mobile)

![[Screenshot 2024-09-02 at 14.57.48.png]]
Perangkat mobile sudah bisa menjalankan fungsi yang berbeda beda pada saat yang bersamaan tidak seperti perangkat embeded computer.

---

#### 3. Komputer Desktop

Penempatan komputer desktiop cenderung berada pada suatu tempat sesuai dengan namanya. artinya komputer yang ditempatkan diatas meja. Komputer Desktop lebih cenderung dikatakan sebagai komputer pribadi (Personal Computer) karena penggunaan komputer ini berada pada tempat yang sama.

Pada implementasinya dalam jaringan, baik Personal Computer dan Laptop lebih diperuntukan untuk mengakses sumber daya yang terdapat di komputer server seperti mengakses layanan Google lewat Internet. Dengan kata lain terdapat istilah lain dari komputer dektop/laptop yaitu Komputer Client.


---

#### 4. Komputer Server

Dalam konseop teknologi informasi, peran dari komputer server digunakan sebagai penyedia informasi dan komputer yang digunakan untuk mengakses informasi yang terdapat di server adalah Computer Client.

Komponen penyuisusn komputer server tidak jauh berbeda dengan komputer desktop seperti CPU, RAM dan lainnya. Tetapi dari segi ketersediaan layanan, scalability dan unjuk kerja komputer menjadikan pembeda dengan komputer client. Layanan yang disediakan oleh komputer server harus bisa diakses setiap saat. Oleh karena itu spesifikasi perangkat keras dari server berbeda dengan komputer client.

Parameter kedua adalah Scalability, atau kemampuan komputer server untuk dikembangkan. Kompunen perangkat keras server harus bisa diubah sesuai dengan permintaan. Biasanya kapasitas Harddisk dan RAM yang dimiliki komputer server jauh lebih besar jika dibandingkan dengan komputer Client, begitu pula dengan kecepatan processornya.

Parameter terakhir adalahunjuk kerja server dalam melayani perminataan client.Misalnya web server maka unjuk kerja web server akan dikaitkan dengan jumlah maksimal komputer client yang dapat dilayani komputer server ketika melakukan request halaman web dan jumlah maksimal halaman web yang dikuirimkan oleh komputer server ke client setiap detik. Nilai dari parameter unjuk kerja servwer ini akan berbanding lurus dengan spesifikasi perangkat keras atau bandwidth saluran yang digunakan oleh komputer server.


## Peripheral Komputer

Komputer merupakan perangkat yang digunakan untuk memproses data, Dalam memproses data tersebut diperlukan komponen untuk memproses data yang terdapat dalam komputer itu sendiri. seperti processor dan RAM. Data yang diproses dari perangkat lain yang terhubung secara terpisah. Pearngkat ini dinamakan sebagai perangkat input, sebagai contoh adalah keyboard, mouse, dan lainnya. Hasil dari pemprosesan ddata oleh komputer ini akan ditampilkan menggunakan perangkatr output seperti monitor, printer, atau speaker, dll.

![[Screenshot 2024-09-02 at 15.41.37.png]]

## Storage - Harddisk, SAN, NAS

Fungsi komputasi yang dilakukan oleh komputer akan dikerjakan oleh CPUSebelum data digital diproses oleh CPU, terlebih dahulu data tersebut akan disimpan dalam Memory (RAM). Semakin banyak proses atau aplikasi yang dijalankan oleh komputer maka semakin besar pula kapasitas memori yang harus disediakan. Hasil kerja / data akan tersimpan dalam memori komputer karena sifat yang dimiliki oleh RAM adalah Volatile artinya daya yang tersimpan adalah data yang bersidat sementara, dan mhasil dari pengerjaan data akan hilang ketika komputer mendadak mati. Oleh karena itu diperlukan tempat penyimpanan lain dalam komputer yang bersipat permanen yang dinamakan dengan sitilah Storage

![[Screenshot 2024-09-02 at 16.27.29.png]]

Penyimpanan storage berbeda dengan memori, walau secara fungsi dari kedua komponen tersebut sama, Storage merupakan tempat penyimpanna data yang lebih aman jika dibandingkan dengan memory

Bentuk storage dari komputer salah satunya Hard Disk Drive, Storage dalam komputer terdiri dari dua tipe, Hard Disk Internal dan Hard Disk External.

#### 1. NAS (Network Attached Storage)

Konsep tempat penyimpanan (storage) awal yang dimiliki komputer selalu identik terletak pada komputer itu sendiri. Hard Disk internal terhubung dengan Mainboard komputer menggunakan kabel SCSI (Small Computer System Interface) . Nama pada perkembangannya tempat penyimpanan komputer server bisa terletak pada komputer yang berbeda. Posisi antar konputer dengan storage dan komputer server terhubung melalui jaringan. Terdapat dua konsep penyimpanan yang terhubung ke dalam suatu jaringan yaitu:

1. NAS (Network Attached Storage)
2. SAN (Storage Area Network)

Konsep yang digunakan oleh NAS adalah dengan menempatkansatu unit penyimpanan (storage) yang terhubung ke dalam suatu jaringan. Perangkat tersebut merupakan satu komputer yang memiliki beberapa media penyimpanan (Disk Array) yang tersimpan dalam satu perangkat.

Pengguna dapat melakukan proses penyimpanan dan pengambilanm data ke dan atau dari perangkat penyimpanan NAS melalui jaringan. Perbedaan dengan konseop NAS adalah perangkat yang digunakan sebagai media penyimpanan adalah biasany amilik pribadi
![[Screenshot 2024-09-02 at 19.15.39.png]]

Fungsi server NAS biasanya hanya sebagai tempat penyimpanan saja atau istilahnya File Server. Biasanya proses komunikasi antar komputer klien untuk mengakses file ke dalam server NAS menggunakan jaringan Ethernet dan sebagai identitas antar komputer digunakan mekanisme pengalamatan IP (Internet protocol)

Biasanya komputer NAS sudah terpasang sistem operasi khusus yang memiliki kinerja Sistem Operasi yang lebih cepat dari sistem operasi biasa. Keunggulan NAS lainnya adalah tingkay scalability yang tinggi.

---

#### SAN (Storage Area Network)

konsep Storage yang terpisah antar komputer server dan klien yang terhubung dalam jaringan selain NAs terdapat juga konsep SAN. Pengaturan pada server SAN atau NAs diatur secara terpusat dan digunakan secara bersama sama oleh beberapa komputer klien atau server. Konsep penyimpanan SAN memiliki kecepatan yang lebih tinggi jika dibandingkan dengan NAS.

Ada SAN digunakan kabel fiber optic sebagai media untuk proses komunikasi antar server SAN dengan komputer klient. Dengan menggunakan protokol FCoE (Fibre Channel Over Ethernet) pada layer data link. Kecepatan tinggi SAN menurunkan latency sehingga kerja alat menjadi lebih baik.

Server NAS lebih mudah bagi pengguna dan membutuhkan biaya yang lebih murah jika dibandingkan dengan SAN
![[Screenshot 2024-09-02 at 19.21.45.png]]

Pada satu jaringan SAN terdapat beberapa server SAN, salah satu dari server tersebut digunakan sebagai server utama yang merespons setiap permintaan data dari client dan yang lain sebagai server cadangan. File data terduplikasi antar server sehingga apabila server utama mengalami masalah, proses transfer masih bisa dilakukan oleh server SAN yang lain.

![[Screenshot 2024-09-02 at 19.23.31.png]]




Di dalam suatu komputer. storage terdapat pada harddisk yang terhubung langsung dengan mainboard komputer dengan kabel SCSI. KOnsep storage network memisahkan antara storage dengan komputer server jaringan, Dengan menggunakan konsep storage network, penambahan jumlah dan kapasitas storage bisa lebih fleksibel. Permasalahan peningkatan permintaan layanan penyimpanan data dapat diatasi dengan konsep SAN.

SAN Juga menerapkan konsep disk arrat, yakni data dari server disatukan secara virtual mengginakan teknologi RAID (Redundant Array of Independent Disk). Hal ini yang menyebabkan kapasitas dan server SAN lebih besar.

Dalam membaca dan mengeksekusi data dala storage, teknologi RAID menggunakan cache sehingga prtoses pengambilan.pembacaan data dan eksekusi penyimpanan data dalam server lebih cepat. Perangkat perangkat tersebut terhubung dalam suatu jaringan menggunakan teknologi, topoligi jaringan dan protokol yang spesifik.

Berikut adalah kelebihan yang dimiliki oleh teknologi SAN

1. Availability Tinggi
   Konsep jaringan SAN memingkinkan adanya suatu sistem yang menyediakan suatu sistem dengan tingkan keterdesiaan layanan yang tinggi. Konsep penggunaan server SAN yang lebih dari satu dalam jaringan menmungkinkan adanya sistem dengan availability tinggi. Hal ini dimungkinkan karena konsep SAN menerapkan konsep Redundancy Server,  JIka salah satu server SAN mengalami masalah maka bisa langsung tergantikan dengan server SAN yang lainnya.
   
2. Reliability
   Selain menerapkan konsep Redundancy server, SAN juga menerapkan konsep Redundancy Link, Jalur komunikasi antar monputer clint dan serve dibuat lebih dari satu, Dengan adanya konsep Redundancy link memingkinkan dapat tersedianya sistem dengan tingkat reliability yang tinggi. JIka ada masalah pada jalur utama maka bisa langsung dialihkan ke jalur lainnya.
   
3. Scalability
   Ukuran dan kapasitas Storage SAN dapat dinaikan sesuai dengan permintaan pengguna. Penggunaan teknologi RAID juga memungkinkan untuk menanmbah kapasitas storage kareba beberapa harddisk dapat digabung menjadi seolah olah hanya 1 saja.
   
4. Performance
   Terdapat beberapa pilihan teknologi di sisi jaringan akses yang digunakan diantaranya FCoE (Fibre Channer over Ethernet) yang menyediakan  kecepatan akses data tinggi.


## Storage - Harddisk, SAN, NAS

Fungsi komputasi yang dilakukan oleh komputer akan dikerjakan oleh CPUSebelum data digital diproses oleh CPU, terlebih dahulu data tersebut akan disimpan dalam Memory (RAM). Semakin banyak proses atau aplikasi yang dijalankan oleh komputer maka semakin besar pula kapasitas memori yang harus disediakan. Hasil kerja / data akan tersimpan dalam memori komputer karena sifat yang dimiliki oleh RAM adalah Volatile artinya daya yang tersimpan adalah data yang bersidat sementara, dan mhasil dari pengerjaan data akan hilang ketika komputer mendadak mati. Oleh karena itu diperlukan tempat penyimpanan lain dalam komputer yang bersipat permanen yang dinamakan dengan sitilah Storage

![[Screenshot 2024-09-02 at 16.27.29.png]]

Penyimpanan storage berbeda dengan memori, walau secara fungsi dari kedua komponen tersebut sama, Storage merupakan tempat penyimpanna data yang lebih aman jika dibandingkan dengan memory

Bentuk storage dari komputer salah satunya Hard Disk Drive, Storage dalam komputer terdiri dari dua tipe, Hard Disk Internal dan Hard Disk External.

#### 1. NAS (Network Attached Storage)

Konsep tempat penyimpanan (storage) awal yang dimiliki komputer selalu identik terletak pada komputer itu sendiri. Hard Disk internal terhubung dengan Mainboard komputer menggunakan kabel SCSI (Small Computer System Interface) . Nama pada perkembangannya tempat penyimpanan komputer server bisa terletak pada komputer yang berbeda. Posisi antar konputer dengan storage dan komputer server terhubung melalui jaringan. Terdapat dua konsep penyimpanan yang terhubung ke dalam suatu jaringan yaitu:

1. NAS (Network Attached Storage)
2. SAN (Storage Area Network)

Konsep yang digunakan oleh NAS adalah dengan menempatkansatu unit penyimpanan (storage) yang terhubung ke dalam suatu jaringan. Perangkat tersebut merupakan satu komputer yang memiliki beberapa media penyimpanan (Disk Array) yang tersimpan dalam satu perangkat.

Pengguna dapat melakukan proses penyimpanan dan pengambilanm data ke dan atau dari perangkat penyimpanan NAS melalui jaringan. Perbedaan dengan konseop NAS adalah perangkat yang digunakan sebagai media penyimpanan adalah biasany amilik pribadi
![[Screenshot 2024-09-02 at 19.15.39.png]]

Fungsi server NAS biasanya hanya sebagai tempat penyimpanan saja atau istilahnya File Server. Biasanya proses komunikasi antar komputer klien untuk mengakses file ke dalam server NAS menggunakan jaringan Ethernet dan sebagai identitas antar komputer digunakan mekanisme pengalamatan IP (Internet protocol)

Biasanya komputer NAS sudah terpasang sistem operasi khusus yang memiliki kinerja Sistem Operasi yang lebih cepat dari sistem operasi biasa. Keunggulan NAS lainnya adalah tingkay scalability yang tinggi.

---

#### SAN (Storage Area Network)

konsep Storage yang terpisah antar komputer server dan klien yang terhubung dalam jaringan selain NAs terdapat juga konsep SAN. Pengaturan pada server SAN atau NAs diatur secara terpusat dan digunakan secara bersama sama oleh beberapa komputer klien atau server. Konsep penyimpanan SAN memiliki kecepatan yang lebih tinggi jika dibandingkan dengan NAS.

Ada SAN digunakan kabel fiber optic sebagai media untuk proses komunikasi antar server SAN dengan komputer klient. Dengan menggunakan protokol FCoE (Fibre Channel Over Ethernet) pada layer data link. Kecepatan tinggi SAN menurunkan latency sehingga kerja alat menjadi lebih baik.

Server NAS lebih mudah bagi pengguna dan membutuhkan biaya yang lebih murah jika dibandingkan dengan SAN
![[Screenshot 2024-09-02 at 19.21.45.png]]

Pada satu jaringan SAN terdapat beberapa server SAN, salah satu dari server tersebut digunakan sebagai server utama yang merespons setiap permintaan data dari client dan yang lain sebagai server cadangan. File data terduplikasi antar server sehingga apabila server utama mengalami masalah, proses transfer masih bisa dilakukan oleh server SAN yang lain.

![[Screenshot 2024-09-02 at 19.23.31.png]]




Di dalam suatu komputer. storage terdapat pada harddisk yang terhubung langsung dengan mainboard komputer dengan kabel SCSI. KOnsep storage network memisahkan antara storage dengan komputer server jaringan, Dengan menggunakan konsep storage network, penambahan jumlah dan kapasitas storage bisa lebih fleksibel. Permasalahan peningkatan permintaan layanan penyimpanan data dapat diatasi dengan konsep SAN.

SAN Juga menerapkan konsep disk arrat, yakni data dari server disatukan secara virtual mengginakan teknologi RAID (Redundant Array of Independent Disk). Hal ini yang menyebabkan kapasitas dan server SAN lebih besar.

Dalam membaca dan mengeksekusi data dala storage, teknologi RAID menggunakan cache sehingga prtoses pengambilan.pembacaan data dan eksekusi penyimpanan data dalam server lebih cepat. Perangkat perangkat tersebut terhubung dalam suatu jaringan menggunakan teknologi, topoligi jaringan dan protokol yang spesifik.

Berikut adalah kelebihan yang dimiliki oleh teknologi SAN

1. Availability Tinggi
   Konsep jaringan SAN memingkinkan adanya suatu sistem yang menyediakan suatu sistem dengan tingkan keterdesiaan layanan yang tinggi. Konsep penggunaan server SAN yang lebih dari satu dalam jaringan menmungkinkan adanya sistem dengan availability tinggi. Hal ini dimungkinkan karena konsep SAN menerapkan konsep Redundancy Server,  JIka salah satu server SAN mengalami masalah maka bisa langsung tergantikan dengan server SAN yang lainnya.
   
2. Reliability
   Selain menerapkan konsep Redundancy server, SAN juga menerapkan konsep Redundancy Link, Jalur komunikasi antar monputer clint dan serve dibuat lebih dari satu, Dengan adanya konsep Redundancy link memingkinkan dapat tersedianya sistem dengan tingkat reliability yang tinggi. JIka ada masalah pada jalur utama maka bisa langsung dialihkan ke jalur lainnya.
   
3. Scalability
   Ukuran dan kapasitas Storage SAN dapat dinaikan sesuai dengan permintaan pengguna. Penggunaan teknologi RAID juga memungkinkan untuk menanmbah kapasitas storage kareba beberapa harddisk dapat digabung menjadi seolah olah hanya 1 saja.
   
4. Performance
   Terdapat beberapa pilihan teknologi di sisi jaringan akses yang digunakan diantaranya FCoE (Fibre Channer over Ethernet) yang menyediakan  kecepatan akses data tinggi.


## Virtualisasi Server dan Storage

Server merupakan suatu perangkat komputer yang difungsikan untuk memebrikan layanan kapada kompuyter lainnya dalam jaringan. Konsep dari proses komunikasi antar perangkat dalam jaringan menggunakan komsep Client-Server. 

Terdapat beberapa jenis layanan data yang diberikan oleh komputer server antara lain:
- Server yang menyediakan tempat penyimpanan database (Database Server)
- Server yang menyediakan tempat penyimpanan file (File Server)
- Server yang menyediakan layanan pertukaran email (E-mail Server)
- Server yang menyediakan layanan berupa halaman web (Web Server)
- Server yang menyediakan layanan game (Game Server)

Jadi semua proses yang dilakukan oleh Server lebih cenderung memberikan layanan kepada komputer client.

Idealnya satu aplikasi server diaktifkan pada satu komputer server. Hal ini diperlukan untuk menjaga kualitas layanan kepada komputer client. Artinya jumlah komputer server yang perlu disiapkan berbanding lurus dengan jumlah aplikasi server yang akan di aktifkan. Solusi dari permasalahan ini adalah dengan menggunakan konsep Virtualisasi Server.

Inti dari konsep Virtualisasi Server adalah membuat server secara virtual dalam suatu perangkat komputer fisik sehingga sumber daya yang tersedia pada komputer secara fisik dapat dimanfaatkan secara lebih efisien. Konsep Vistualisasi adalah dengan membuat komputer secara logik dalam satu komputer fisik. masing masing komputer virtual adapt menjalankan sistem operasi yang berbeda.


#### 1. Virtualisasi Server

Terdapat 3 bagian utama dalam suatu perangkat komputer server yaitu:
- Aplikasi yang menunjuk pada layanan yang diaktifkan pada suatu komputer server
- Sistem Operasi
- Perangkat Keras Komputer

Tiga komponen tersebut wajib ada dalam komputer server

![[Screenshot 2024-09-03 at 09.09.46.png]]

Konsep virtualisasi komputer atau istilah lainnya adalah virtual machine (VM) merupakan suatu konsep dalam menduplikasi perangkat lunak yang baru dalam suatu komputer atau mesin yang sama. Dengan menggunakan konsep virtualisasi nantinya adakan ada beberapa virtual machine (VM) yang baru dalam suatu perangkat fisik yang sama. Virtual machine berbeda dengan menggunakan perangkat keras yang sama untuk membuat virtual machine memerlukan bantuan Hypervisor

Hypervisor atau lebih dikenal dengan istilan VMM (Virtual Machine Monitor) merupakan software yang digunakan untuk membuat dan menjalankan VM. Dalam suatu komputer dapat dijalankan/dibuat lebih dari satu virtual machine. Hypervisor berperan untuk mencegah terjadinya gangguan komunikasi antar VM sehingga Hypervisor berfungsi untuk mengatur komunikasi antar VM.

![[Screenshot 2024-09-03 at 09.13.51.png]]
\
Antar VM dapat mengakses ke komponen perangkat keras melalui peran dan fungsi Hypervisor. Komputer yang menjalankan hypervisor dan digunakan untuk membuat dan menjalankan suatu atau beberapa VM disebut sebagai Host machine, dan masing masing VM dalam Host Machine disebut sebagai Guest Machine.

Hypervisor akan mengatur proses komunikasi antar VM dalam satu komputer. Hypervisor akan memisahkan fungsi dan peran antar VN dalam satu komputer dan memastikan bahwa terjadinya penurunan unjuk kerja pada suatu VM tidak berpengaruh pada VM lainnya. Hypervisor juga mengatur penggunaan resource hardware bersama oleh beberapa VM.

Terdapat dua cara yang umum dilakukan untuk membuat mesin virtual menggunakan Hypervisor yaitu:
![[Screenshot 2024-09-03 at 09.18.36.png]]


##### **Hypervisor tipe 1**

  Hypervisor tipe 1 berjalan langsung dalam suatu hardware komputer, sedangkan Hypervisor tipe 2 berjalan diatas suatu sistem operasi. Nama lain dari Hypervisor tipe 1 adalah para-virtualization atau mare metal. Apabila dibandingkan dengan melihan unjuk kerjha host machine, penggunaan hypervisor tipe 1 lebih efisien juka dibandingkan dengan HYpervisor tipe 2. Masing masing VN dapat mengakses langsung resource hardware melalui Hypervisor tanpa melewati Sistem Operasi lahi. Produk Hypervisor tipe 1 yang biasa digunakan adalah VMware ESXi, Microsoft Hyper-v server atau KVM
  
##### **Hypervisor tipe 2**

  Hypervisor tipe 2 berjalan diatas suatu sistem operasi. Hypervisor tipe 2 menggunakan bantuan sistem operasi yang suidah berjalan pada suatu komputer. Sistem operasi berjalan pada host machine menjadi terbebani jika jumlah guset machine yang di buat terlalu berlebihan. Beberapa contoh produk software Hypervisor tipe 2 adalah Microsoft Virtual PC, Parallels Desktop, Virtual Box dan QEMU


## Virtualisasi Storage

Komputer server sangat erat hubungannya dengan storage. Komputer server difungsikan untuk menyimpan data dengan ukuran yang relatif besar. Data yang tersimpan dalam suatu server harus bisa diakses setiap saat oleh komputer client. Pada implementasinya, suatu komputer server memiliki kumpulan hard disk sebagai storage. Istilah lain dari kumpulan hard disk ini adalah disk array. Kemudian kumpulan hard disk tersebut akan digabung menjadi satu harddisk secara virtual dengan teknologi yang disebut dengan RAID (Redundant Array of Independent Disk)

Saat ini teknologi RAID banyak digunakan pada komputer server. Konsep dari RAID adalah kebalikan dari hypervisor. Teknologi RAID akan menggabungkan beberapa harddisk fisik menjadi seolah olah hanya ada satu hard disk saja secara logic (Virtual)

Asumsinya semua Hard Disk yang difungsikan sebagai storage sudah digabung sehingga ketika ada proses penyimpanan data ke dalam storage maka semua hard disk akan difungsikan. data akan di simpan dan diduplikasi pada semua hard disk.

Tujuan dari penggunaan teknologi RAID sendiri adalah tersedianya sistem dengan tingkat availability yang tinggi, Dari sisi untuk kinerja, teknologi RAID juga dilengkapi dengan komponen cache sebagai pengganti peran memory.

![[Screenshot 2024-09-03 at 10.10.19.png]]

Pengaturan proses penyimpanan data (write) and Read diatur secara terpusat oleh Controller.  Biasanya standar jalur yang digunakan dalam satu komputer adalah menggunakan kabel SCSI, tetapi bila menggunakan konsep storage network SAN, kabel SCSI akan digantikan dengan jaringan fiber atau neggunakan protokol FCoE.

Dalam sistem disk, bagian yang berfungsi mengatur alur proses instruksi untuk menyimpan dan mengambil data dilakukan oleh controller atau istilahnya dikenal dengan nama RAID Contrioller. Apabila alamt instruksinya adalah sama maka controller tidak menuju ke memori untuk menangakan alamat lagi, melainkan controller akan menggunakan bagian cache yang terdapat dalam Disk. Dengan menggunakan cahce proses penyimpanan dan pengambilan data dari harddisk akan lebih cepat dan efisien



---


# [[Kegiatan Belajar 2 - Perangkat Jaringan Teknologi Informasi]]

## Perangkat Jaringan Teknologi Informasi

Sebelum menjadi suatu informasi yang bermanfaat bagi manusia, data mentah perlu dioleh terlebih dahulu. Perangkat kompiter sebagai pengirim atau penerima data membutuhkan peran jaringan agar data tersebut dapat dipertukarkan antar perangkat.

### Pengenalan Jaringan

Jaringan didefinisikan sebagai hubungan/interkoneksi antar sekumpulan perangkat. Tujuan utama dengan membuat konsep jaringan adalah agar masing masing perangkat yang sudah terhubung dapat saling berkomunikasi atau bertukar data. Dalam konsep sistem informasi, data merupakan bentuk dasart suatu informasi. Perlu peran dari jaringan agar antar komputer dapat saling mempertukarkan data.

Perangkat dalam kategori perangkat penghubung dapat berupa router atau switch. Perangkat router digunakan untuk menghubungkan komputer yang terletak pada wilayah jaringan yang berbeda, sedangkan switch digunakan untuk menghubungkan perangkat perangkat komputer yang terletak pada wilayah jaringan yang sama.

Konsep jaringan juga dikenal perangkat berupa Modem (Modular-Demodulator) yang digunakan untuk emngubah bentuk sinyak yang merupakan representasio dari data yang dikirim. Modem sendiri tidak dikategorikan sebagai perangkat penghubung.

Perangkat penghubung memerlukan peran media sebagai penghung antar komputer sehingga membentuk jaringan. 

Terdapat dua jenis media yang bisa digunakan, yakni kabel (wired) dan nirkabel (wireless)

Perangkat dalam konsep jaringan dapat dibagi lagi menjadi dua bagian yaitu perangkat akhir (end devices) dan perangkat penghubung (intermediary device). PErangkat akhir adalah perangkat yang difungsikan untuk mengirimkan dan menerima data. Fungsi dari perangkat penghubung adalah untuk menghubungkan antar perangkat akhir saja seperti, Hub, Switch, dan Router.

Jaringan dapat dikategorikan berdasarkan letak geogrtafisnya yaitu LAN, WAN, dan Internet

#### 1. LAN (Local Area Network)

LAN didefiniskan sebagai suatu jaringan yang terdapat pada suatu wilayah tertentu seperti gedung kantor, dan lainnya. Pada suatu jaringan LAN tidak dibatasi akan jumlah perangkat yang terhubung tetapi lebih mengacu pada posisi wilayah jaringan tersebut dibangun. Ketika jaringan tersebut terdapat pada gedung yang sama dimana letak antar gedung saling berdelatan maka nama dari jaringan yang kita bangun adalah LAN

#### 2. WAN (Wide Area Network)

Definisi jaringan WAN adalah hubungan antar jaringan LAN, tetapi terletak pada wilatah geografis yang berbeda. Pada umumnya jaringan WAN adalah suatu konsep dalam menghubungkan jaringan LAN yang terletak pada jarak yang relatif jauh, misalnya jaringan LAN yang terletak pada procinsi yang berbeda.

![[Screenshot 2024-09-03 at 10.55.33.png]]
#### 3. Internet

Konsep jaringan iternet tidak terbatas oleh wilayah geografis. Konsep jaringan internet adalah suatu konsep jaringan yang menghubungkan perangkat jaringan dari seluruh dunia. Kebalikan dari jaringan Internet adalah jaringan Intranet. Nama lain dari jaringan Intranet adalah jaringan Private yaitu jaringan yang dinmiliki oleh instansi tertentu. Jaringan internet menggunakan mekanisme pengalamatan yang berbeda dengan Internet. 

Semua perangkat yang terhubung dengan jaringan internet menggunakan identitas alamat yang dikenal secara Public. Istilah dari alamatnya adalah IP Public, dedangkan private menggunakan jenis alamat IP Private. Saat ini protokol yang oaling banyak digunakan untuk memberikan alamat interface perangkat adalah IP (internet Protocol)


## Jenis dan topologi jaringan

Apabila kita menjumpai dua komputer yang dihubungkan secara langsung maka hal tersebut sudah bisa dikatakan sebagai satu jaringan. Istilah koneksi dari dua unit komputer yang dihubungkan secara langsung sehingga membentuk konsep jaringan dinamakan dengan istilah Peer-to-Peer

![[Screenshot 2024-09-03 at 19.01.19.png]]

Jaringan hanya terdiri dari dua komputer ang dihubungkan secara langsung. Penggunaan dari perangkat penghubung (intermediary devices) pada topologi ini tidak wajib karena komputer yang dihubungkan hanya dua unit saja. Namun apabila komputer yang dihubungkan lebih dari dua maka peran dari perangkat penghubung sangat diperlukan.

![[Screenshot 2024-09-03 at 19.02.51.png]]

(a) Hub
(b) switch
(c) Router

Langkah awal sebelum membangun sebuah konsep jaringan komputer adalah kita harus mengerti topologi fisik yang nantinya akan digunakan. Diantara parameter awal dalam proses perencanaan suatu jaringan adalah penentuan jenis dari topologi fisik yang akan digunakan.

Istilah dari topologi fisik mengacu pada bentuk jaringan jika dilihat secara fisik. Sedangkan istilah topologi mengacu pada link yang terbentuk ketika dua atau lebih perangkat dihubungkan satu sama lainnya sehingga membentuk suatu konsep jaringan.

Terdapat beberapa jenis topologi fisik jaringan antara lain Bus, Ring, Star, dan Mesh. Jenis topologi fisik yang sering digunakan adalah topologi Star dan Mesh.

#### 1. Topologi Star

Ciri khusus dari penggunaan topologi star adalah setiap perangkat dihubungkan pada satu perangkat penghubung ke perangkat perangkat lain atau dengan kata lain terdapat perangkat sentral. Semua proses komunikasi antar komputer akan melewati pearngkat penghubung tersebut.

![[Screenshot 2024-09-03 at 19.08.12.png]]

Topologi star dapat dikatakan sebagai topologi default ketika menghubungkan ke lebih dari dua perangkat komputer. Perangkat penghubung yang sering digunakan adalah, Hub, Swith, dan Router. Jika terjadi masalah atau gangguan dalam perangkat penghubung maka sistem jaringan juga akan mati dan komputer tidak bisa saling bertukar data.

---


#### 2. Topologi Mesh

Pada topologi mesh mempunyai ciri bahwa setiap perangkat atau node mempunyai konetsi secara langsung atau dedicated (Point to Point) dengan perangkat lainnya. Setiap perangkat yang mempunya konetsi dengan semua perangkat lain dinamakan dengan topologi full-mesh. Beda halnya jika tidak semua perangkat memiliki koneksi dengan semua perangkat yang lain, nama topologi yang digunakan adalah partial-mesh

![[Screenshot 2024-09-03 at 19.13.45.png]]

JIka dibandingkan dengan topolofi Star, topologi Mesh memiliki link yang jauh lebih banyak. Penggunaan topologi Mesh juga memeliki beberapa keunggulan diantaranya:

- Bandwidth,
  Saluran yang digunakan dalam menghubungkan komputer tidak terbagi karena jalur hanya diperutukan untuk dua perangkat saja yang disebut dengan istilah dedicated link, sehingga kualitas bandwith penuh.
  
- Availability,
  Jaringan mesh menyediakan tingkat availability yang tinggi, jika salah satu saluran terputus maka tidak akan mempengaruhi keseluruhan jaringan
  
- Keamanan,
  Memberikan jaminan keaman dalam pertukaran data. hal ini karena jalur hanya digunakan oleh dua perangkat saja.
  
- Isolation
  Mudah mengisolasi jika terjadi masalah dalam jaringan. hal ini karena hanya satu saluran saja yang digunakan untuk menghubungkan dua perangkat.

Jumlah link yang dibutuhkan berbanding lurus dengan jumlah perangkat yang akan dihubungkan. dalam mencari jumlah jalur (link) yang dibutuhkan untuk menghubungkan antar perangkat jika menggunakan topologi mesh adalah:

![[Screenshot 2024-09-03 at 19.19.18.png]]

Dimana n adalah jumlah perangkat yang akan dihubungkan.
Misalnya jika kita ingin membangun jaringan dengan menggunakan 5 perangkat yang akan dihubungkan maka link yang dibutuhkan adalah:

![[Screenshot 2024-09-03 at 19.20.01.png]]

## Jaringan Wired dan Wireless

Secara garis besar terdapat dua pilihan media sebagai penghubung antar perangkat dalam jaringan, yaitu media kabel (wired) dan media udara (wireless). Dari ssii kecepatan transfer data, penggunaan media kabel memberikan kecepatan yang lebih besar dibandingkan media wireless, namun, dari sisi fleksibilitas pengguna pada saat menggunakan perangkat bertukar data, penggunaan media wireless jauh lebih fleksibel dibandingkan dengan kabel. Manum saat ini penggunaan wireless juga tidak kalah cepat dengan hadirnya teknologi 5G pada sistem seloler yang dapat memberikan kecepatan transfer data sampai dengan 10 Gigabit per second.

#### 1. Jaringan Wired

Penggunaan media kabel ridak terlepas dari standarisasi atau protokol yang digunakan oleh perangkat untuk berkomunikasi, lembaga yang mengatur standarisasi dari penggunaan media kabel adalah IEEE (institute of Electrical dan Electronical Engineers) yang berada di New York, Amerika Serikat.

![[Screenshot 2024-09-15 at 11.18.22.png]]

Lembaga IEEE memperkenalkan standarisasi awal untuk menghubungkan antar komputer dengan kode IEEE 802.3m standarisasi IEEE dengan kode IEEE 802.3 menggunakan media coaxial yang merupakan jaringan kabel pertama, Nama produk awal NIC (Network nterface Cable) dengan kode IEEE 802.3 adalah 10Base5. komputer yang menggunakan perangkat NIC menggunakan kabel Coaxial dengan bandwidth maksimal 10Mbps.

Penggunaan kabel fiber optik memberikan kecepatan akses yang jauh lebih cepat dibandingkan dengan kabel Twisted Pair, seperti UTP atau STP. Semakin besar bandwidth yang diberikan suatu teknologi perangkat NIC, kabel yang digunakan juga beralih dengan menggunakan kabel fiber optic.

---


#### 2. Jaringan Wireless

Penggunaan media udara memberikan fleksibilitas penggunaanperangkat untuk berpindah-pindah tempat, hal ini merupakan kelebihan dari media wireless. Media wireless menggunakan  standarisasi protokol pada layer-2 (data link) yang berbeda dengan media kabel.

Terdapat dua lembaga standarisasi protokol untuk media wireless yaitu IEEEE dan 3GPP (3rd GEneration Partnership Project). Lembaga IEEE selain memberikan standarisasi kepada media kabel juga memberikan sdanrasisi media wireless. IEEE mengeluarkan dua teknologi yang menggunakan media wireless waitu Wi-Fi dengan kode standar 802.11 dan WiMAX dengan kode standar 802.16. Penggunaan teknologi Wi-Fi diperuntukan komunikasi antar perangkat yang jangkauannya lebih pendek dari WiMAX. penggunaan teknolofi dapat memberikan jarak jangkauan sekitar 30 meter sedangkan untuk WiMAX dapat menjangkau hingga 50KM. pada awalnya tejknologi WiMAX dirancang untuk bia mntransfer datas ebesar 30 sampai 40 Mbps, namun pada rancangan terbaru kecepatanya bisa mencapai 75Mbps.

Munculnya teknologi WiMAX dirancang ebagai penyempurna teknologi Wi-Fi, tetapi untuk pangsa pasar indonesia, teknlogi WiMAX kurang diminati.

Teknologi seluler yang pertama kali diluncurkan adalah 1G yang dikeluarkan oleh lembaga 3GPP. TEknologi ini menggunakan sisten NMT (Nordic Mobile technology) dari eropa atau AMPS (Advance obile Phone System) dari amerika, dimana kedua layanan tersebut masih menggunakan sinyal analog. Kemusia 3GPP mengeluarkan teknoloi seluler selanjutnya berna,ma 2G yang sudah menggunakan sistem digital. Teknologi ini sudah menggunakan standarisasi GSM (Global System for Mobile Comunication). Kapasitas pengguna dalam menggunakan layanannya lebih banyak jika dibandingkan dengan 1G.

Istilah dari cara mngeakses kanal untuk komunikasi dengan jumlah user yang banyak dikenal dengan nama metode akses. Teknologi 2G menggunakan metode akses TDMA (Time Division multiple Access) yang berbeda dengan teknologi 1G yang menggunakan metode akses (Frequency Division Multiple Access) dimana user dibedakan dengan frekuensi yang berbeda. Selain itu teknologi 2G juga memberikan layanan suara dan layanan data (Internet) meskipun kecepatanya hanya 14.4 Kbps.

Perkembangan setelah teknologi 2G dikenal dengan istilah teknologi 2.5G. Teknologi ini menggunakan standar yang berbeda yaitu GPRS (General Packet Radio Services) dengan kecepatan data transfer sampai 172,2 Kbps. alasan kenapa masih menggunakan nama 2.5G karena kecepatan transfernya tidak terlalu berubah secara signifikan. Lembaga 3GPP terus berkembang dimana perkembangan selanjutnya diberi nama teknologi 3G dengan kecepatan transfer data yang lebih besar yaiti diangka 3,1 Mbps dengan menggunakan standar CDMA2000 yang dikeluarkan oleh 3GPP yang menggunakan standar CDMA. CDMA memiliki singkatan Code Division multiple Access.

Setelah perkembangan teknologi 3G kemudian mucul teknologi selanjutnya yaitu 4G, yang memberikan kecepatan layanan yang lebih besar yaitu sekitar 50Mbps, dengan menggunakan standar LTE (Long Term evolution). Sebenarnya kecepatan teknologi LTE hampir sama dengan WiMAX yang dikeluarkan oleh IEEE.

Semua perkembangan yang teknologi yang dikeluarkan oleh 3GPP lebih mengarahj ke perbaikan dari sisi meningkatkan kapasitas user selain kjecepatan transfer data, Perkembangan terbaru dari teknologi seluler adalah teknologi 5G dengan kecepatan yang tinggi yaitu hingga 10 Gbps. 

WiFi sebagai terknologi jaringan wireless dapat dijadikan alternatif di indonesia sebegai antisipasi dari kurangnya minat masyarakat terhadap teknologi WiMAX. Implementasi teknologi Wi-Fi banyak digunakan pada jaringan LAN sehingga munculah istilah waringan Wireless LAN, Perkembangan dari keberadaaan teknologi Wi-Fi yang dikembangkan oleh lembaga IEEE dapat disimah di tabel berikut:

![[Screenshot 2024-09-15 at 18.12.30.png]]

Kode standar yang pertama kali dikeluarkan untuk Wi-Fi adalah 802.11b pada tahun 1999. Standar teknologi Wi-Fi ini menggunakan frekuensi sebesar 2,4 Ghz. Bandwidth kabal sebesar 20 Mhz dan teknik modulasi DSSS (Direct Sequence Spread Spectrum). Perangkat NIC yang menggunakan standar 802.11b akan menghasilkan kecepatan transfer sebesar 11 Mbps.

Pada tahun yang sama IEEE juga mengeluarkan standar 802.11a yang menggunakan frekuensi kerja yang berbeda, yaitu 5 Ghz, dengan frekuensi kerja yang lebih tinggi dari standar 802.11b, standar 802.11a dapat memberikan kecepatan transfer yang lebih cepat yaitu sekitar 54 Mbps.

Standar 802.11g dapat meberikan kecepatan transfer yang sama dengan standar 802.11a walaupun menggunakan frekuensi yang lebih kecil. hal ini dikarenakan standar 802.11g sudah menggunakan teknik modulasi OFDM (Orthogonal Frequency-Division Multiplexing) yang memberikan unjuk kerja yang lebih baik jika dibandingkan dengan teknik DSSS

Perkembangan WiFi selanjutnya adalah kode 802.11n. Frekuensi kerja yang digunakan oleh standar ini dapat menggunakan dua pilihan yaitu 2,4 GHz atau 5 GHz. Untutuk perangkat Laptop, Smartphone, atau AP (Access Point) yang diugunakan untuk implementasi wifi kebanyakan menggunakan frekuensi kerja 2,4 GHz sehingga standar 802.11b/g/n yang paling banyak digunakan pada perangkat.

Dengan menggunakan teknik modulasi OFDM, standar 802.11n memberukan kecepatan transfer sebesar 600 Mbps. Pada perkembangan selanjutnya,mpada tahun 2013 dikeluarkan standar baru yaitu kode 802.11ac. Penggunaan standar ini mampu memberikan kecepatan transfer data yang lebih besar yaitu sekitar 2,93 Gbps. Walaupun mampu memberikan kecepatan transfer data yang lebih baik, tetapi dengan menggunakan frekuensi kerja 5 GHz akan menjadikan salah satu penghambat berkembangnya standar ini untuk digunakan oleh banyak pengguna karena salah satu faktor suatu teknologi akan bisa bertahan adalah dukungan Vendor untuk membuat perangkat yang menggunakan standar tertentu seperti 802.11ac ini.

---

#### 3. Perbandingan Media Wired dan Wireless

##### a. Jaringan Wireless

- Karena media yang digunakan adalah wireless maka penggunaan radio frekuensi wajib digunakan pada masing masing perangkat contohnya standarisasi 802.11g yang menggunakan frekuensi kerja 2,4 GHz, agar hubungan dua perangkat atau lebih bisa terjadi, maka frekuensinya haruslah sama.
  
- Dalam membangun jaringan WiFi memerlukan perangkat penghubung antar laptop, Istilah ini adalah AP (Access Point). Perangkat ini yang akan menghubungkan antar perangkat laptop sehingga antar perangkap laptop bisa saling bertukar data. Agar perangkat AP dan laptop dapat erhubung maka frekuensi kerja antar kedua perangkat harus disamakan. Artinya, agar koneksi antar laptop dengan AP dapat terjadi atau membentuk suatu konsep jaringan maka diperlukan konfigurasi awal.

##### b. Jaringan Wired

- Dalam menghubungkan antar perangkat ridak membutuhkan frekuensi tetapi lebih kepada perangkat fisik, yaitu kabel. Keuntungan menggunakan media kabel adalah tidak adanya pengaruh interferensi ddengan perangkat lain menggunakan frekuensi yang sama yang dapat mnyebabkan menurunnya kualitas jaringan.
  
- Ketika ingin menghubungkan antar komputer dengan perangkat penghubung seperti switch, maka tidak perlu ada pengaturan perangkat switch. Cukup dengan menyediakan kabel dan menghubungkan antar perangkan tersebut lewat perangkat NIC maka anta perangkat sudah terhubung dan dapat digunakan untuk proses eprtukaran data.  Pada kasus tertentu, pada jaringan Switch yang memerlukan persyaratan khusus sebelum membangun jatingan, misalnya dengan menerapkan terknologi VLAN (Virtual LAN) maka disaat awal dieprlukan proses konfigurasi.

## Perangkat Jaringan

Perangkat Jaringan adalah perangkat yang digunakan untuk menghubungkan dua atau beberapa komputer sehingga dapat saling berbagi data. Cara kerja perangkat jaringan dalam melakukan proses pengiriman atau penerimaan data dilakukan secara Full-Duplex. Pada saat yang bersamaan perangkat dapat mengirim dan menerima data. Pada tahun 1990-an terdapat perangkat yang bersifat Half-Duplex dimana proses pengiriman dan penerimaan data dilakukan secara bergantian, teknologi Internet yang menggunakan media komunikasi berbasis Citixen-Band Radio.

Dalam pemilihan perangkay penghubung, faktor utama yang harus menjadi pertimbangan adalah masalah unjuk kerja jaringan. Parameter yang digunakan untuk mengetahui unjuk kerja jaringan ada dua yaitu Throughput dan Delay.

- Throughput adalah parameter yang menyatakan seberapa epat data dikirim atau diterima antar perangkat. Nilai throughput mentyatakan besaran trtansfer data sesungguhnya yang digunakan oleh suatu perangkat NIC. Satuan untuk menyatakan Throughput sama dengan Bandwidth yaitu bit per second (bps).
- Delay menyatakan lamanya (Keterlambatan) waktu proses kirim data dari komputer pengirim sampai ke komputer penerima melewati jaringan, 

 
unjuk kerja suatu jaringan dapat dinilai dengan menggunakan kecepatan mentrasnfer data dari komputer pengirim ke komputer penerima dengan melewati suatu perangkay penghubung. Terdapat 3 jenis perangkat penghubung yang dapat digunakan yaitu Hub, Switch, datau Router. Masing masing memiliki karakteristik dan aliran data yang berbeda.

Untuk mengetahui karakteristik masing-masing perangkat, terlebih dahulu perlu dipahami tentang pengertian konsep Colision Domain dan Broadcast Domain.

- Collision Domain, Collision atrinya tabrakan, Collision Domain (Wilayah Collision) didefiniskkan sebagai wilayah jaringan yang didalamnya terdapat perangkat komputer yang akan merakasan akibat apabila terjadinya tabrakan data yang dikirimkan antar perangkat komputer yang berbeda dalam jaringa. Jika terjadi proses collision dalam suatu jaringan, semua perangkat komputer yang memperoleh sinya collisioon tidak bisa mengirim atau menerima data. Kejadian ini bisa dinamakan dengan Jamming. Dampaknya adalah terjadinya delay atau keterlambatan dalam penyampaian paket data.
  
- Broadcast Domain adalah suatu wilayah dimana ketika terdapat dsalah satu komputer yang mengirimkan data yang sifat pengirimannya secara broadcast ke kemua komputer, maka semua komputer tersebut akan menerima data tersebut. 

Pemahaman awal mengenai konsep Collision Domain dan Broadcast Domain akan dijadikan dasar dalam menentukan pemilihan perangkat penghubung.

---

#### 1. Hub

Perangkat hub adalah perangkat yang bekerja di layer fisik dari sudut pandang konsep layer OSI. Karena berada di layer fisik, secara kerja dari perangkat hub lebih kepada sebagai penghubung antar perangkat komputer saja. Penggunaan perangkat hub merupakan penyumbang terbesar dalam terjadinya masalah collision dalam jaringan.

![[Screenshot 2024-09-16 at 09.38.46.png]]
Fungsi perangkat hub hanyalah sebagai penghubung saja dan bukan mengatur trafik data yang dipertukarkan antar komputer. Sumber masalah dapat terjadi pada perangkat hub tersebut. Ketika dua komputer atau lebnih mengirimkan data pada saat yang bersamaan, data tadi kemungkinan besar akan bertabrakan satu sama lainnya pada perangkat hub, terlebih jika perangkat yang dihhubungkan bertambah.

Teknologi yang digunakan oleh hub adalah CSMA/CD (Carrier Sense Multiple Access with Collision Detection), yang amat terkenal pada zamannya

---

#### 2. Switch

Perangklat penghubung yang digunakan untuk menggantikan Hub adalah Switch. JIka tujuan dalam membangun jaringan hanya untuk menghubungkan antar perangkat komputer saja maka penggunaan switch sudah cukup memadai. namun jika tujuan dari membangun jaringan adalah menghubungkan antar perangkat dalam wilayah yang berbeda maka wajib menggunakan router

![[Screenshot 2024-09-16 at 10.02.53.png]]

Perangkat switch dapat menekan pengaruh atas terjadinya collision. Apabila dalam suatu jaringan sama sekali tidak menggunakan perangkat hub, tetapi menggunakan perangkat switch atau router, maka jaringan tersebut akan terbebas dari masalah colision sehingga unjuk kerja jaringan akan menjadi lebih baik lagi.

---

#### 3. Router

Penggunaan perangkat switch hanya dapat mengatasi masalah colision dalam suatu jaringan namun belum bisa mengatasi permasalahan kerika ada pengiriman data yang sifatnya broadcast.Pengiriman data broadcast dalam volume yang bsar akan menimbulkan masalah dalam jaringan karena bandwidth saluran akan digunakan untuk mengirimkan paket yang sebenarnya tidak semua perangkat akan memprosesnya. 

Pengaruh pengiriman data broadcast akan mempengaruhi data yang sifat pengirimannya secara unicast. Pengiriman data secara unicast akan menggunakan suatu alamat tujuan yang jelas. Waktu pengiriman data unicast menjadi lebih lama dibandingkan jika dalam jaringan tidak terganggu dengan adanya pengiriman data secara broadcasr. Permasalahan ini dapat diatasi dengan mengubah perangkat penghubung menjadi perangkat router.

![[Screenshot 2024-09-16 at 10.30.11.png]]

Selain berguna untuk meningkatkan kualitas jaringan karena mampu menekan jumlah broadcast, penggunaan perangkat Router juga digunakan untuk menghubungkan antar perangkat komputer yang berada pada jaringan yang berbeda. Jika pada perangkat switch, antar port switch mewakili wilayah colision yang berbeda, maka pada perangkat router, antar Interface Router mewakili wilayah jaringan yang berbeda.


## Sistem Pengalamatan

Perangkat komputer dalam berkomuniaksi dengan perangkat komputer lainnya dalam suatu jaringan selain membutuhkan media untuk menghubungkan antar perangkat komputer juga perlu alamat agar data yag dikirimkan dapat sampai ke tujuan dan penerima barang harus dituliskan dengan benar.

Jenis alamat yang digunakan oleh suatu perangkat dibagi menjadi dua yaitu:

1. Alamat Fisik atau alamat yang menunjuk pada interface card perangkan atau NIC (Network Interface Card) yang digunakan oleh komputer. NIC digunakan sebagai perantara (Interface) antar komputer dengan media sebelum data bisa dikirimkan atau diterima ke dan/dari perangkat yang lain menggunakan media.
   
2. Alamat Logic atau alamat yang menunjuk pada alamat suatu komputer. Protokol jaringan yang saat ini digunakan untuk mengalamati komputer atau perangkat penghubung seperti router adalah IP (Internet Protocol). Antar perangkat dalam jaringan agar bisa saling berkomuniaksi harus menggunakan alamat IP yang unik atau berbeda satu-sama-lain.

Mekanisme pengalamatan dengan menggunakan protokol IP dapat menggunakan dua alternatif pilihan veris, yaitu menggunakan IP versi 4 (IPv4) atau IP versi 6 (IPv6). Perbedaan utama dari kedua versi IP tersebut adalah terletak pada jumlah ketersediaan alamay yang bisa disediakan.

IPv6 memberikan kelebihan dari sisi kapasitas alamat daripada IPv4, Hal ini dikarenakan jumlah bit yang digunakan pada format pengalamatan IPv6 lebih banyak daripada IPv4. IPv6 menggunakan jumlah bit alamat sebesar 128 bit, desangkan IPv4 sendiri hanya menggunakan jumlah bit sebesar 32 bit. Semakin banyak jumlah bit, jumlah alamat IP yang disediakan juga semakin banyak. 

JIka menggunakan versi alamat Ipv4 dengan julah bit sebesar 32, jumlah alamat IP yang disediakan adalah sebesar 2^32 atau 4.294.967.296 alamat IP. sedangkan dengan menggunakan versi alamat IPv6 dengan jumlah bit 128bit, jumlah alamat maksimal yang disediakan yaitu sebesar 2^128 atau sebanyak 3,4 x 10^38 alamat IP.

Jumlah alamat IPv6 yang banyak tersebut selain digunakan untuk meningkatnya jumlah pengguna internet juga digunakan untuk mengantisipasi perangkat IoT (Internet of Things) yang perkembangannya.

#### IPv4

Penulisan alamat IPv4 menggunakan format bilangan desimal, Misalnya terdapat alamat IPv4 192.168.10.10. Pada contoh tersebut terbagi menjadi 4 bagian dan mesing masing dikenal dengan istilah Octet. Berikut rinciannya:
- Bagian 1 / Octet-1 = 192
- Bagian 2 / Octet-2 = 168
- Bagian 3 / Octet-3 = 10
- Bagian 4 / Octet-4 = 10

Jika diperhatikan lebih rinci alamat IPv4 192.168.10.10 sebenarnyta masing masign dipisahkan dengan tanda titik (.) kemudian jika dilihat dari jumlah bit dari alamat IPv4, terdiri dari 32 bit maka dibagi menjadi empat bagian akan terdapat 8 bit per bagian (Octet).

Jika dalam Octet terdapat 8bit, nilai minimal untuk binernnya adalah 00000000 dan maksimalnya adalah 11111111 atau dituliskan ke dalam bentuk bilangan desimal akan memiliki rentang 0 sampai 255. Oleh karena itu penulisan IPv4 adalah di rentan 0-225. Diantara rentetan angka tersebut dibagi menjadi lima bagian dan masing masing dikenal dengan istilah Kelas.

![[Screenshot 2024-09-16 at 19.26.20.png]]

Terdapat lima kelas dalam pola pengelompokan alamat IPv4, yaitu kelas A, B, C, D, dan E. Namun dari kelima kelas yang ada hanya tiga kelas saja yang bisa digunakan untuk mengalamati Interface Komputer yaitu kelas A, B, dan C. Rentan alamat IP pada keas D dan E tidak bisa digunakan untuk mengalamati interface komputer. 

Rentan alamat IPV4 pada keas D digunakan untuk komunikasi antar perangkat secara Multicast. sedangkan untuk kelas E diperuntukan untuk alamat cadangan. 

Rentan alamat keas A dimulai dari angka 0.0.0.0 sampai 127.255.255.255. JIka kita memiliki nilai alamay IPv4 127.255.255.255 kemudian nailai alamat IPv4 tersebut dinaikan satu alamay maka nilai dari alamat IPv4 menjadi 128.0.0.0. 

Implementasi penggunaan alamat IPv4 akan digunkaan untuk dua tipe jaringan yang berbeda yaitu jaringan private dan public. Jaringan private adalah jaringan yang digunakan oleh suatu instansi kantor, kampus, atau jaringan pribadi rumahan. Alamat IP yang digunakan adalah alamat IP private. Pembagian dari rentan alamat IP private terbagi menjadi:

![[Screenshot 2024-09-16 at 19.31.35.png]]

Almat IP kategori private keas A dimuali dari rentang alamat 10.0.0.0 sampai dengan 10.255.255.255. kemudian untuk keals B dan C bertrut turut mulai dari alamat 172.16.0.0 sampai 172.31.255..255 dan 192.168.0.0 sampai 192.168.255.255. 

Kebalikan dari alamat IP private adalah amalay IP public yang merupakan IP address yang digunakan oleh perangkat untuk terhubung ke jaringan internet. Alamat IP 216.239.38.253 yang merupakan alamat IP keas C yang digunakan oleh server google. Alamat IP tersebut adalah alamay IP kelas C kategori public yang digunakan oleh server Google agar servernya dapat diakses oleh komputer client menggunakan jaringan internet.

---

#### IPv6

Menurut statistik pada bulan Juli tahun 2020, pengguna Internet sudah mencapai angka 4.57 juta. Maka dari itu kapasitas alamat IPv4 sudah tidak mampu menampung user untuk bisa terkoneksi ke jaringan internet.

Pengetahuan dasar yang perlu dikuasai dalam menggunakan alamat IPv6 yaitu tentang bilangan Hexadecimal karena penulisan alamat IPv6 menggunakan bilangan Hexadecimal. Contoh alamat IPv6 adalah 2001:0db8:85a3:0000:0000:8a2e:0370:7334. Apabila diperhatikan secara seksama, alamat IPv6 terbagi kedalam 8 grup dan setiap grup terdiri dari empat bilangan hexadecimal. Satu bilangan Hexadecimal terdiri dari 8 bit sehubgg total bit dalam satu grup, yaitu sebesar 16 bit. Karena 1-Octet adalah 8 bit maka dalam satu grup alamat IPv6 terdiri dari 2-octet yang lebih dikenal dengan istilah Hextet. Pada notasinya untuk memisahkan antar grup digunakan tanda (:)

Jumlah bilangan yang harus dituliskan dalam pengalamatan IPv6 cukup panjang, yaitu 32 bilangan Hexadecimal. Sebenarnya penulisan alamat IPv6 dapat didingkan dengan memperhatikan aturan berikut:

1. Apabila dalam satu grup alamat IPv6 (4 bilangan hexadecimal) dijumpai angka depan yaitu nol, maka nilai nol pada angka depan tersebut dapat dipisahkan. Contohnya bilangan hexadecilam 0db8 bisa diringkas menjadi db8 saja sehingga penulisan 2001:0db8:85a3:0000:0000:8a2e:0370:7334 dapat disingkat menjadi 2001:db8:85a3:0000:0000:8a2e:370:7334.
   
2. Dengan menggunakan contoh alamat IPv6 yang sama kemudian apabila dalam satu grup amalat IPv6 dijumpai empat angka nol yang berturut turut maka penulisan angka hexadecimal nol dalam grup tersebut cukup dituliskan sekali saja . Contohnya bilangan 0000 dapat ditulis dengan 0 saja, sehingga penulisan 2001:db8:85a3:0000:0000:8a2e:370:7334. dapat disingkat menjadi 2001:db8:85a3:0:0:8a2e:370:7334.
   
3. Apabila dijumpai angka nol berturut-turut dalam dua grup atau lebih penulisan alamat IPv6 cukup ditulis dengan tanda (::) sehingga penulisan 2001:db8:85a3:0:0:8a2e:370:7334. datap ditulis dengan 2001:db8:85a3::8a2e:370:7334.


## Virtualisasi Jaringan

Virtualisasi merupakan suatu proses dalam membuat perangkat dalam bentuk logic (Virtual) dalam suatu perangkat fisik. nama lain dari komputer logic tersebut adalah VM (Virtual Machine)

Nama dari teknologi yang digunakan untuk membuat perangkat switch secara virtual tersebut adalah VLAn (Virtual LAN). sama seperti halnya pada saat kita membuat beberapa VM dalam suatu perangkat komputer. Pada saat membuat koneksi antar VM dalam komputer hal tersebut sekaligus juga bermakna membuat perangkat switch virtual yang terpasang di dalam komputer sehingga antar VM yang berbeda dapat saling berkomunikasi.

#### 1. Revolusi Teknologi jaringan

###### Revolusi Teknologi Jaringan Pertama

Revolusi teknologi tahapan pertama dimulai dari perubahan penggunaan teknologi circuit-switched ke packet-switched. Ciri khusus pada penggunaan teknologi Circuit-Switched adalah jalur hanya bisa digunakan oleh dua perangkat saja untuk melakukan komunikasi. contoh implementasinya ada pada penggunaan jaringan PSTN (Public Switched Telephone Network) untuk layanan telepon rumah.

Perangkat yang akan menggunakan jaringan terlebih dahulu akan memecah data yang akan dikirimkan kemudian pecahan data tersebut akan dikirim melewati jaringan. Dengan menggunakan konsep ini dimungkinkan jalur bisa digunakan oleh lebih dari dua perangkat sekaligur. Implementasi penggunaan teknologi Packet-Switched ada pada komunikasi komputer antar komputer dalam suatu jaringan.


###### Revolusi Teknologi Jaringan kedua

Revolusi teknologi jaringan tahap dua ditandai dengan adanya peralihan perangkat yang menggunakan media kabel ke media wireless. Misalnya peralihan dari komputer desktop ke laptop. Masalah fleksibilitas merupakan salah satu alasan utama dalam menggunakan perangkat yang berbasiswakn media wireless

![[Screenshot 2024-09-23 at 19.58.29.png]]

PErtumbuhan jumlah PC desktop masih sekitar angka 14% dalam kurum waktu lima tahun, manum pertumbuhan pengguna perangkat mobile menyentuk angka 104 untuk tablet dan smartphone diangka 79%. Hal ini tidak terlepas dari hadirnya teknologi 3G/4G/5G dan Wi-Fi dalam dunia telekomunikasi yang memberikan kecepatan akses data yang tinggi.

Perkembangan teknologi wireless juga berdampak pada penggunaan komunikasi antar mesin atau komputer yang disebnut dengan M2M (Machine to Machine)


###### Revolusi Teknologi Tahapan ketiga

Revolusi teknologi tahapan ketiga dimulai saat ini, yakni dengan adanya tren penggunaan software sebagai pengganti hardware. Dengan kata lain fungsi hardfware akan digantikan oleh software. Sebagai contoh dalam dunia jaringan terdapat perangkat router atau switch yang menghubungkan antar komputer. Perubahan fungsi ini bisa terjadi karena adanya peran dari penggunaan teknologi virtualisasi.


---

#### 2. Cloud Computing 

Istilah lainnya dari kata pemprosesan yang dilakukan oleh komputer server dalam jaringtan internet adalah Computting, sehingga terdapat istilah lain yang sering kita jumlai yaitu Cloud Computing. Jadi Istilah dari Cloud computing adalah sekumpulan kiomputer server yang mempunya kecepatan proses yang tinggi di mana komputer tersebut ditempatkan di dalam jaringan internet. Kemudian komputer server tersebut akan ditempatkan ke dalam suatu lokasi yang sama dan terpusat yang dikenal dengan istilah Data Center.

Layanan yang diberikan oleh penyedia jasa layanan Cloud Computing dibagi kedalam tiga aktegori yaitu:

![[Screenshot 2024-09-23 at 20.13.42.png]]

###### 1. IAAS (infrastructure as a Services)

Kategori pertama dalam cloud computing adalah IAAS. Sesuai dengan namanya Infrastructure as a Service, konsep layanan cloud dari kategori ini menyediakan fungsi layanan infrastruktur. Arti dari kata infrastruktur sama seperti komponen hardware dalam suatu komputer. 

Jika kita menggunanakna layana cloud , tetapi hanya pada tingkat IAAS saja maka nantinya akan disediakan mesin vitrual-nya saja beserta parameter hardware yang lainnya. 

Contoh layanan IAAS adalah Google lewat jasa layanan cloud bernama GCE (Google Compute Engine)

###### 2. PAAS (Platform as a Services)

Kategori kedua dalam layanan cloud adalah PAAS (Platform as a Service). sesaui dengan namanya maka layanan cloud pada kategori PAAS menyediakan layanan berupa software yang akan digunakan sebagai pondasi awal dalam membuat suatu aplikasi. Sebagai contoh apabila kita ingin mebuat sualu layanan web di kategori SAAs, maka pada kategori PAAS kita akan menggunakan sistem operasi berupa Linux, Web server yang digunakan adalah Apache dan database yang digunakan adalah MySQL. Contoh layanan dalam kategori PAAS adalah Windows Azure yang disediakan oleh windows.

###### 3. SAAS (Software as a Services)

Kategori teratas adalah SAAS.  Pada kategori layanan cloud SAAS, semua proses terjadi di Cloud. Userhanya disediakan tampilannya saja. Karena semua proses terjadi di cloud maka nama lain dari layanan ini adalah CCloud Computing. Dalam artian, proses cloud computing itu terjadi ketika layanan yang digunakan adalah SAAS. Contoh layanan SAAS adalah Gmail, Google Drive, Dropbox dan lain sebagainya.


Perbedaan ketiga kategori layanan cloud bida dijabarkan dalam bentuk konsep layer sebagai berikut:
![[Screenshot 2024-09-23 at 20.19.08.png]]


##### Pemodelan Klasik

Pemodelan klasik dalam membuat suatu aoplikasi yang dijalankan dalam suatu komputer server terdiri dari tujuh lapis mulai dari lapis paling bawah hingga atas yaitu:

- **Network** - Merupakan lapisan yang menyediakan fungsi layanan jaringan. Agar layanan yang di-install dalam suatu komputer server bisa diakses oleh client maka perlu adanya jaringan yang menghubungkan antara komputer server dan client.
  
- **Storage** - Suatu komputer server harus memiliki tempat penyimpanan untuk menyimpan data yang nantinya akan diakses oleh komputer client. Fungsi tersebut ada pada lapisan Storage

- **Hardware Server** - lapisan ini mendefinisikan komponen hardware yang akan digunakan oleh komputer server, seperti jumlah dan kecepatan proses atau kapasitas memory.
  
- **Virtualization** - Lapisan ini menyediakan fungsi dalam membuat mesin komputer virtual
  
- **Operating System** - Suatu komputer tidak akan bisa berfungsi tanpa adalnya peran dari sistem operasi. Lapisan ini menyediakan fungsi sebagai penyedia sistem operasi dari komputer server yang akan di-install layanan atau aplikasi tertentu.
  
- **Database** - Lapisan ini menyediakan software yang digunakan untuk menyimpan data yang dimasukan oleh komputer client.
  
- **Application** - lapisan ini menyediakan layanan yang akan digunakan oleh pengguna.


Dalam konseop pemodelan sistem klasi, semua fungsi mulai dari lapisan network sampai lapisan apliukasi diimplementasikan dalam satu komputer yang sama, yaitu komputer server, Komputer client bisa mengakses layanan yang ter-install di komputer server dengan menyebut nama domain atau alamat IP dari komputer server.

Dengan menggunakan konsep pemodelan Cloud. Sebagian atau seluruh fungsi dari suatu komputer server diserahkankepada pihak penyedia layanan cloud.