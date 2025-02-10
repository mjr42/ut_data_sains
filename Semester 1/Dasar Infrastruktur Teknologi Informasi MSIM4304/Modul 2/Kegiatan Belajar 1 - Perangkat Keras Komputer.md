---
tags:
  - dasar_infrastruktur_teknologi_informasi
---

## [[01. Perangkat Keras Teknologi Informasi]]
### Klasifikasi Komputer

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


## [[02. Peripheral Komputer]]

Komputer merupakan perangkat yang digunakan untuk memproses data, Dalam memproses data tersebut diperlukan komponen untuk memproses data yang terdapat dalam komputer itu sendiri. seperti processor dan RAM. Data yang diproses dari perangkat lain yang terhubung secara terpisah. Pearngkat ini dinamakan sebagai perangkat input, sebagai contoh adalah keyboard, mouse, dan lainnya. Hasil dari pemprosesan ddata oleh komputer ini akan ditampilkan menggunakan perangkatr output seperti monitor, printer, atau speaker, dll.

![[Screenshot 2024-09-02 at 15.41.37.png]]

## [[03. Storage - Harddisk, SAN, NAS]]

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


## [[03. Storage - Harddisk, SAN, NAS]]

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


## [[04. Virtualisasi Server dan Storage]]

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


## [[05. Virtualisasi Storage]]

Komputer server sangat erat hubungannya dengan storage. Komputer server difungsikan untuk menyimpan data dengan ukuran yang relatif besar. Data yang tersimpan dalam suatu server harus bisa diakses setiap saat oleh komputer client. Pada implementasinya, suatu komputer server memiliki kumpulan hard disk sebagai storage. Istilah lain dari kumpulan hard disk ini adalah disk array. Kemudian kumpulan hard disk tersebut akan digabung menjadi satu harddisk secara virtual dengan teknologi yang disebut dengan RAID (Redundant Array of Independent Disk)

Saat ini teknologi RAID banyak digunakan pada komputer server. Konsep dari RAID adalah kebalikan dari hypervisor. Teknologi RAID akan menggabungkan beberapa harddisk fisik menjadi seolah olah hanya ada satu hard disk saja secara logic (Virtual)

Asumsinya semua Hard Disk yang difungsikan sebagai storage sudah digabung sehingga ketika ada proses penyimpanan data ke dalam storage maka semua hard disk akan difungsikan. data akan di simpan dan diduplikasi pada semua hard disk.

Tujuan dari penggunaan teknologi RAID sendiri adalah tersedianya sistem dengan tingkat availability yang tinggi, Dari sisi untuk kinerja, teknologi RAID juga dilengkapi dengan komponen cache sebagai pengganti peran memory.

![[Screenshot 2024-09-03 at 10.10.19.png]]

Pengaturan proses penyimpanan data (write) and Read diatur secara terpusat oleh Controller.  Biasanya standar jalur yang digunakan dalam satu komputer adalah menggunakan kabel SCSI, tetapi bila menggunakan konsep storage network SAN, kabel SCSI akan digantikan dengan jaringan fiber atau neggunakan protokol FCoE.

Dalam sistem disk, bagian yang berfungsi mengatur alur proses instruksi untuk menyimpan dan mengambil data dilakukan oleh controller atau istilahnya dikenal dengan nama RAID Contrioller. Apabila alamt instruksinya adalah sama maka controller tidak menuju ke memori untuk menangakan alamat lagi, melainkan controller akan menggunakan bagian cache yang terdapat dalam Disk. Dengan menggunakan cahce proses penyimpanan dan pengambilan data dari harddisk akan lebih cepat dan efisien

