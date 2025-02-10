---
tags:
  - dasar_infrastruktur_teknologi_informasi
  - materi_5_DITI
---
# Kegiatan Belajar 2 - Praktik 3 - Implementasi Sistem Operasi Server

## [[05. Melakukan Perencanaan dan Persiapan]]

Tahap perencanaan dan persiapan yang perlu dilakukan terhadap pemasangan sistem operasi di suatu komputer, antara lain sebagai berikut:

1. Tentukan sistem operasi yang akan digunakan.
2. Fungsi/peran yang akan dilakukan oleh sistem operasi.
3. Dukungan sistem operasi terhadap perangkat lunak aplikasi yang akan digunakan.
4. Spesifikasi, kapasitas, dan kompatibilitas perangkat keras.
5. File system dan struktur partisi yang akan digunakan.
6. Ketersediaan source file sistem operasi.
7. Metode instalasi sistem operasi yang dapat dilakukan.
8. Parameter-parameter yang diperlukan pada saat instalasi

Tahap pertama dalam perencanaan instalasi sistem operasi ini adalah menentukan sistem operasi yang akan digunakan. Faktor biaya perlu diperhatikan dalam menentukan sistem operasi yang akan digunakan, karena penggunaan sistem operasi ada yang bersifat open source, tetapi ada pula sistem operasi berlisensi (berbayar). Stabilitas dari sistem operasi juga merupakan faktor lain yang harus dipertimbangkan.

Sistem operasi yang dapat digunakan pada komputer bermacam-macam, beberapa diantaranya adalah:

1. Microsoft Windows.
2. Linux yang terdiri dari banyak varian seperti Centos, Redhat, Ubuntu dan sebagainya.
3. FreeBSD.
4. Sun Solaris

#### Peran dan Fungsi 

Salah satu faktor yang perlu diperhatikan untuk menentukan sistem operasi yang digunakan adalah peran atau fungsi yang akan diterapkan terhadap komputer (server atau workstation).Berdasarkan perannya sistem operasi terbagi dalam dua jenis, yakni sebagai berikut

Sistem operasi jaringan/server, sistem operasi yang memiliki banyak layanan untuk mendukung sistem jaringan, seperti:

- layanan DHCP (Dynamic Host Configuration Protocol), layanan penyedia sistem pengalamatan secara dinamis;
- layanan DNS (Domain Name System), layanan yang memetakan nama domain dengan alamat IP dan sebaliknya;
- layanan Web Server, layanan yang menyediakan konten dari suatu website
- layanan FTP (File Transfer Protocol) server, layanan untuk melakukan upload dan download file;
- dan sebagainya. 

Sistem operasi desktop/workstation, sistem operasi yang digunakan secara personal dan dapat digunakan pula untuk mengizinkan suatu klien melakukan permintaan sumber daya tertentu ke server yang menjalankan layanan server melalui jaringan.


#### Spesifikasi, Kapasitas dan Kompatibilitas Perangkat Keras

Spesifikasi, kapasitas dan kompatibilitas perangkat keras terhadap sistem operasi juga menjadi faktor yang perlu diperhatikan ketika memilih sistem operasi yang akan digunakan. Kemampuan sistem operasi akan optimal jika didukung atau diterapkan pada perangkat keras yang sesuai. 

Sebelum instalasi sistem operasi dilakukan Anda harus memastikan terlebih dahulu persyaratan perangkat keras yang diperlukan oleh sistem operasi untuk dapat bekerja secara optimal. Umumnya setiap sistem operasi menyediakan informasi terkait kebutuhan sumber daya minimal dan optimal, tapi dalam pelaksanaanya Anda harus menyediakan sumber daya yang relatif lebih besar dari yang dipersyaratkan oleh sistem operasi tersebut untuk memenuhi kebutuhan sumber daya yang dipersyaratkan bagi layanan yang akan diinstal pada sistem operasi tersebut

Beberapa sumber daya perangkat keras yang dipersyaratkan oleh sistem operasi, antara lain:
1. kapasitas memory RAM;
2. kapasitas harddisk;
3. spesifikasi processor;
4. spesifikasi video card (diperlukan bagi sistem operasi berbasis GUI

#### Faktor Lainya

1. struktur partisi yang akan digunakan, lakukan pemisahan partisi antara sistem dan data. Pemisahan antara sistem dan data bertujuan supaya ketika terdapat proses upgrading sistem atau troubleshooting terhadap sistem tidak mengganggu tempat penyimpanan data. Pemisahan ini pun sangat memudahkan administrator melakukan aktivitas backup dan restore terhadap sistem atau data;
   
2. penentuan jenis file system, terdapat beberapa mekanisme pengelolaan file yang diterapkan sistem operasi untuk mengelola file-file yang tersimpan di harddisk. Beberapa diantaranya adalah FAT16/32, NTFS, HPFS, ext2, ext3, ext4. Setiap sistem operasi dapat memiliki lebih dari satu sistem file. Setiap sistem file yang dipilih memiliki kekurangan dan kelebihannya masing-masing.

#### Metode Instalasi 

Ketersediaan source file dari sistem operasi yang akan diinstal pada komputer/host. Sebaiknya disesuaikan dengan kesiapan perangkat keras yang akan digunakan, sehingga memperlancar proses instalasi sistem operasi. Misalkan suatu notebook tidak memiliki DVD ROM tetapi mendukung mekanisme bootable dari USB drive untuk proses instalasi sistem operasi maka sumber file sistem operasinya tidak tersimpan dalam media DVD.

Metode instalasi sistem operasi dapat dilakukan terdiri dari berikut:

1. **Instalasi baru**, metode ini umum digunakan terhadap sistem yang baru. Isi partisi yang terpilih akan dihapus.
   
2. **Upgrade**, metode ini digunakan jika sebelumnya harddisk sudah berisi sistem operasi sebelumnya, hal ini dilakukan untuk menambah ataupun melakukan perbaikan fitur yang ada pada sistem operasi yang digunakan. Metode ini akan tetap menjaga aplikasi yang sudah terinstal sebelumnya. Metode ini hanya akan mengganti file-file sistem operasi sebelumnya dengan yang baru.
   
3. **Multiboot**, metode ini digunakan jika suatu komputer akan diinstal lebih dari satu sistem operasi yang digunakan secara bergantian. Sistem operasi akan ditempatkan pada partisi yang berbeda.
   
4. **Virtualisasi**, metode ini digunakan untuk mengoptimalkan kemampuan komputer sehingga dapat menyediakan beberapa komputer secara virtual di dalam satu perangkat komputer fisik sehingga dapat dimungkinkan untuk menginstal beberapa sistem operasi dan dapat digunakan secara simultan. Beberapa aplikasi virtualisasi ini antara lain: Virtual Box, VmWare dan Microsoft Hyper-V


#### Parameter

Parameter-parameter yang diperlukan pada saat instalasi sistem operasi sebaiknya sudah dipersiapkan sehingga tidak menghambat proses instalasi sistem operasi. Parameter-parameter yang diperlukan pada saat instalasi sistem operasi, antara lain berikut.

1. Nama host.
2. Username dan password Administrator.
3. Alamat IP (saat ini umumnya menggunakan sistem pengalamatan berbasis IP).
4. Subnet mask.
5. Default gateway.
6. DNS Server




## [[06. Melakukan Instalasi Sistem Operasi]]

Pada bagian ini Anda akan melakukan praktik instalasi sistem operasi. Sistem operasi yang digunakan pada praktik kali ini adalah Ubuntu server versi 16.04.6. Sistem operasi ini diperuntukan untuk komputer yang bertindak sebagai server. Diharapkan pada akhir proses instalasi ini server ini memiliki spesifikasi sebagai berikut.

1. ﻿﻿﻿Memiliki Nama : Server1.
2. ﻿﻿﻿Alamat IP : 192.168.100.5.
3. ﻿﻿﻿Subnet mask : 255.255.255.0.
4. ﻿﻿﻿Default gateway : 192.168.100.1.


#### Minimum Requirement

Untuk dapat menginstal server Ubuntu diperlukan spesifikasi perangkat yang memiliki sumber daya minimal sebagai berikut.

1. ﻿﻿﻿Memory RAM minimal: 2 GB.
2. ﻿﻿﻿Processor: minimal 700 MHz Intel Celeron.
3. ﻿﻿﻿Kapasitas Harddisk minimal: 25 GB.

Persiapkan bahan-bahan yang diperlukan:

1. File ISO Ubuntu Server 16.04, dapat di-download melalui situs resmi Ubuntu (https://ubuntu.com/download/server). Sesuaikan dengan arsitekur yang ingin anda install 32-bit atau 64-bit, sesuaikan dengan Processor yang digunakan i386 atau AMD.

2. Jika Anda menggunakan Virtualbox atau Vmware maka buatlah virtual machine baru. Jika instalasi dilakukan melalui USB drive, buat terlebih dahulu bootable via USB. Software VirtualBox dapat diunduh dari situs https://www.virtualbox.org/.


Untuk membuat Server1 memiliki karakteristik tersebut, tahapan yang harus dilakukan adalah sebagai berikut.

1. ﻿﻿﻿Instalasi Sistem operasi Ubuntu versi 16.04.6.
2. ﻿﻿﻿Konfigurasi Sistem operasi dengan memiliki peran sebagai DHCP, DNS, dan Web Server.



## [[07. Installasi Ubuntu Server]]

Proses instalasi sistem operasi Ubuntu server versi 16.04.6 dapat diikuti dengan langkah-langkah berikut.

1. Setelah masuk ke proses install Ubuntu Server akan muncul pilihan Bahasa pilih English.
![[Screenshot 2024-10-26 at 14.08.46.png]]

2. Berikutnya untuk melakukan instalasi Ubuntu server pilih "Install Ubuntu Server"
![[Screenshot 2024-10-26 at 14.09.08.png]]

3. Kemudian akan muncul tampilan seperti pada Gambar 5.25, pilih English sebagai bahasa yang akan digunakan untuk proses instalasi.
![[Screenshot 2024-10-26 at 14.09.26.png]]

4. Proses berikutnya menentukan lokasi zona waktu yang akan digunakan. Pilih Other
![[Screenshot 2024-10-26 at 14.09.43.png]]

5. Konfigurasi locale yang digunakan pilih United States - en.US.UTF-8, seperti pada Gambar 5.27. Locale merupakan sekumpulan parameter yang menentukan bahasa pengguna, wilayah, dan preferensi varian khusus apa pun yang ingin dilihat pengguna di antarmuka penggunanya.
   
   ![[Screenshot 2024-10-26 at 14.10.05.png]]

6. Langkah berikutnya menentukan konfigurasi layout keyboard, pilih No agar kita dapat menentukan layout keyboard.

![[Screenshot 2024-10-26 at 14.10.28.png]]

7. Pilih English (US) sebagai layout keyboard yang digunakan.
   
   ![[Screenshot 2024-10-26 at 14.10.47.png]]
8. Langkah berikutnya adalah mengkonfigurasi parameter yang berkaitan dengan jaringan. Konfigurasi dilakukan secara manual. Pilih item "Configure network manually"
   ![[Screenshot 2024-10-26 at 14.11.04.png]]
   
9.  Pasangkan alamat IP untuk komputer yang kita instal sistem operasi ini dengan alamat dan subnet mask misalnya 192.168.100.5/24. Format subnet mask menggunakan bit-count, jadi 124 sama dengan 255.255.255.0 dalam format desimal.
   
   ![[Screenshot 2024-10-26 at 14.11.35.png]]
10. Selanjutnya menetapkan parameter default gateway, alamat yang digunakan untuk menuju arah keluar jaringan, umumnya merupakan alamat dari perangkat router yang terhubung. Contohnya 192.168.100.1
    ![[Screenshot 2024-10-26 at 14.11.55.png]]


11. Langkah berikutnya menetapkan alamat server yang bertindak sebagai DNS server. Jika mesin yang kita instal saat ini akan dijadikan sebagai DNS server maka alamat yang ditetapkan sebagai DNS server adalah sama dengan yang didefinisikan pada parameter IP address yang sebelumnya sudah ditetapkan yakni 192.168.100.1. Tetapi jika di dalam jaringan tersedia DNS server lainnya maka parameter Name Server diisi dengan alamat IP dari DNS server tersebut
    
    ![[Screenshot 2024-10-26 at 14.12.24.png]]

12. Selanjutnya proses dilanjutkan dengan menetapkan nama host, isi dengan Servert sehingga hostname dari perangkat server ini adalah Server1.
    
    ![[Screenshot 2024-10-26 at 14.12.37.png]]

13. Tahap berikutnya menetapkan nama domain, contohnya diisi dengan nama ut.ac.id.
    
    ![[Screenshot 2024-10-26 at 14.13.01.png]]

14. Lanjutkan dengan menetapkan nama dari pengguna dan akun pengguna beserta password seperti pada Gambar 5.36. Misalnya seperti berikut.
	1. ﻿﻿﻿Nama user : Admin 1
	2. ﻿﻿﻿Username : Admin1
	3. ﻿﻿﻿Password : P@sswOrd
![[Screenshot 2024-10-26 at 14.13.26.png]]
15. Konfigurasi zona waktu Indonesia, sesuaikan dengan lokasi.
    
    ![[Screenshot 2024-10-26 at 14.13.41.png]]

16. Dilanjutkan dengan pengaturan partisi, Pilih Guided - Use entire disk and setup LVM. Seluruh kapasitas disk akan dijadikan 1 partisi dan sifat partisinya bersifat dinamis dapat dikembangkan kapasitasnya.
    ![[Screenshot 2024-10-26 at 14.14.04.png]]

17. Berikutnya proses pembuatan partisi berlangsung.
    ![[Screenshot 2024-10-26 at 14.14.22.png]]

18. Proses instalasi sistem berlangsung sampai muncul penambahan HTTP proxy, kosongkan saja dan langsung Continue.
    
    ![[Screenshot 2024-10-26 at 14.14.37.png]]

19. Tahapan berikutnya adalah mengkonfigurasi tasksel; tasksel merupakan utilitas baris perintah untuk sistem berbasis Debian/Ubuntu untuk menginstal sekelompok paket yang digunakan untuk tugas tertentu.

20. Pilih mekanisme pengembangan sistem, pada skenario ini pilih "No automatic updates".
    ![[Screenshot 2024-10-26 at 14.15.06.png]]

21. Pilih layanan atau komponen yang akan dinstal.
    
    ![[Screenshot 2024-10-26 at 14.15.29.png]]

22. Proses instalasi berlangsung.
    
    ![[Screenshot 2024-10-26 at 14.15.56.png]]

23. Proses berikutnya menginstal GRUB Loader. GRUB merupakan perangkat lunak boot loader atau boot menu yang menampilkan semua sistem operasi yang terinstal pada komputer. Pilih Yes untuk melakukan instalasi GRUB.
    ![[Screenshot 2024-10-26 at 14.16.13.png]]

24. Proses instalasi selesai.
    
![[Screenshot 2024-10-26 at 14.16.32.png]]

Sistem akan otomatis restart dan masuk ke dalam terminal konsol Ubuntu Server. Lakukan proses otentikasi dengan memasukan username dan password agar dapat memasuki server Ubuntu tersebut. Isi parameter username: Admin1 dan password: P@sswOrd

Sistem menampilkan tampilan berikut.

![[Screenshot 2024-10-26 at 14.17.06.png]]




## [[08. Konfigurasi Sistem Operasi]]

Setelah sistem operasi diinstal, tidak menutup kemungkinan terdapat parameter-parameter yang harus disesuaikan. Pada skenario berikut ini susun jaringan seperti topologi pada Gambar 5.47 dan akan dikonfigurasi dengan ketentuan sebagai berikut.

1. Server diberi alamat IP secara statik 192.168.1.135/24 dan default gateway diarahkan ke 192.168.1.1 yang merupakan alamat dari interface router yang terhubung ke internet dan DNS diarahkan ke 192.168.1.135  dan 8.8.8.8.
   
2. Server memiliki peran sebagai:
	1. ﻿﻿﻿web server dengan alamat www.UT.ac.id.
	2. ﻿﻿﻿DHCP server yang memiliki scope IP 192.168.1.10 s/d 192.168.1.100.
	3. ﻿﻿﻿DNS server.

3. Komputer yang bertindak sebagai klien diharapkan memperoleh IP address dari DHCP Server secara otomatis.

![[Screenshot 2024-10-26 at 14.18.44.png]]

#### Konfigurasi Server

Konfigurasi terhadap server akan dilakukan melalui tahapan-tahapan berikut.

1. Setting Interface Jaringan Untuk mengubah konfigurasi interface jaringan di Ubuntu dapat menggunakan perintah berikut.
![[Screenshot 2024-10-26 at 14.19.38.png]]

2. Ubah parameter IP sesuai dengan kebutuhan begitu pula parameter lainnya jika diperlukan. Kemudian tekan Ctrl+O untuk menyimpan hasil perubahan dan Ctrl+X untuk keluar dari text editor.
   
3. Kemudian restart interface dengan cara:
   ![[Screenshot 2024-10-26 at 14.20.19.png]]
   
4. Kemudian verifikasi menggunakan perintah sudo ifconfig Pastikan IP dan parameter lain sudah berubah. Jika terdapat masalah sehingga menyebabkan IP belum berubah lakukan perintah berikut.
   ![[Screenshot 2024-10-26 at 14.20.45.png]]
5. Verifikasi alamat IP yang terpasang Untuk memverifikasi alamat interface yang terpasang di server dapat kita lakukan dengan menggunakan perintah:
   
   ![[Screenshot 2024-10-26 at 14.21.04.png]]
   ![[Screenshot 2024-10-26 at 14.21.14.png]]



## [[09. Membangun DHCP Server]]

DHCP adalah singkatan dari Dynamic Host Configuration Protocol yang merupakan layanan yang dapat memasangkan alamat IP secara otomatis ke komputer yang memintanya. DHCP bertujuan untuk menghindari pemasangan alamat IP yang sama antar host satu dengan host lainnya. Masalah konflik IP address umum terjadi pada jaringan yang menggunakan mekanisme pengalamatannya dilakukan secara manual.

Sistem DHCP terdiri dari dua komponen, yakni sebagai berikut.

1. ﻿﻿﻿DHCP Server adalah pihak yang memberikan alamat IP.
2. ﻿﻿﻿DHCP Klien merupakan host yang melakukan permintaan alamat IP.

#### Pemasangan alamat IP di DHCP

Cara kerja pemasangan alamat IP di DHCP klien sebagai berikut.

1. ﻿﻿﻿DHCP Klien akan melakukan permintaan IP address ke DHCP server dengan melakukan proses IP request.
2. ﻿﻿﻿DHCP Server merespons permintaan alamat IP dari DHCP Klien dengan menawarkan serangkaian alamat IP yang belum digunakan oleh host lainnya dengan melakukan proses IP offers.
3. ﻿﻿﻿DHCP Klien akan memilih salah satu dari serangkaian alamat IP yang ditawarkan oleh DHCP server dengan melakukan proses IP selection.
4. ﻿﻿﻿DHCP Server akan mengesahkan dengan melakukan proses IP acknowledgment.

![[Screenshot 2024-10-26 at 14.22.29.png]]

Ubuntu server dapat bertindak sebagai DHCP Server. Untuk menjadi DHCP Server, komponen DHCP Server harus diinstal terlebih dahulu dan kemudian dikonfigurasi sesuai dengan kebutuhan.

Skenario berikut Anda akan membangun satu DHCP Server menggunakan Ubuntu Server versi 16.04 dengan topologi seperti pada gambar berikut.

![[Screenshot 2024-10-26 at 14.22.51.png]]

#### Instalasi dan konfigurasi DHCP

Proses instalasi dan konfigurasi DHCP Server dapat dilakukan dengan mengikuti

langkah-langkah berikut.

1. ﻿﻿﻿Pastikan komputer server terpasang alamat IP secara static dengan alamat IP 192.168.1.135/24 dan terhubung dengan internet.
   
2. ﻿﻿﻿Langkah pertama, instalasi komponen DHCP di server dengan menggunakan perintah:
   ![[Screenshot 2024-10-26 at 14.23.19.png]]
   ![[Screenshot 2024-10-26 at 14.23.49.png]]
   

3. Jawab Y untuk melanjutkan proses instalasi DHCP.
   
4. Langkah selanjutnya setelah install DHCP Server, yaitu konfigurasi DHCP dansetting beberapa data yang ada di isc-dhcp-server.
	
	1. Gunakan perintah nano /etc/default/isc-dhcp-server untuk mengubah isi file isc-dhcp-server.
	   
	2. Pada bagian paling bawah terdapat pernyataan INTERFACES = diisi dengan nama interface, sesuaikan dengan nama interface yang akan melayani permintaan alamat IP dari DHCP Klien, dapat dilihat dengan menggunakan perintah sudo ifconfig.
	   ![[Screenshot 2024-10-26 at 14.24.42.png]]
	3. Tetapkan nama interface yang akan melayani permintaan alamat IP dari klien.
	   ![[Screenshot 2024-10-26 at 14.24.56.png]]

5. Selesai simpan tekan Ctrl + O lalu Ctrl + X. Kemudian modifikasi file dhcp.conf dengan menggunakan text editor 
   ![[Screenshot 2024-10-26 at 14.25.16.png]]
	1. Tentukan scope alamat IP yang akan ditawarkan untuk klien (misalnya 192.168.1.10 - 192.168.1.100).
	   
	2. ﻿﻿﻿Lalu cari baris yang ada pada gambar di bawah hapus tanda pagar # untuk mengaktifkan konfigurasi.
	   
	3. ﻿﻿﻿Ubah informasi sesuai yang anda inginkan untuk komputer klien Anda.
	   
![[Screenshot 2024-10-26 at 14.25.45.png]]
	Pada konfigurasi DHCP tersebut bertujuan menyediakan IP untuk klien mulai dari 192.168.1.10 sampai dengan 192.168.1.100. Default gateway diarahkan ke 192.168.1.1 serta DNS Server 8.8 3.8.8 dan internal DNS Server 192.168.1.13
	
4. Simpan konfigurasi tersebut dengan menggunakan perintah Ctrl + O dan keluar Ctrl + X.
5. ﻿﻿﻿Restart service jaringan agar konfigurasi yang telah dibuat diperbarui, gunakan perintah berikut.
![[Screenshot 2024-10-26 at 14.26.39.png]]

6. 1. Restart service dhcp dengan menggunakan perintah:

![[Screenshot 2024-10-26 at 14.26.58.png]]

Proses konfigurasi DHCP server telah selesai dilakukan.

Untuk menguji hasil konfigurasi yang sudah dilakukan terhadap DHCP Server, atur mekanisme pengalamatan pada komputer klien menggunakan DHCP.

![[Screenshot 2024-10-26 at 14.27.14.png]]

Kemudian pastikan komputer klien (DHCP Klien) memperoleh alamat IP dari DHCP Server yang telah dibuat.

![[Screenshot 2024-10-26 at 14.27.32.png]]

Lakukan verifikasi konektivitas dengan Server1 menggunakan perintah ping dari komputer klien.

![[Screenshot 2024-10-26 at 14.27.51.png]]



## [[10. Membangun Server Web]]

Server web merupakan suatu perangkat lunak server yang berfungsi menerima permintaan protokol HTTP atau HTTPS dari klien berupa browser web dan mengirimkan kembali hasilnya dalam bentuk halaman-halaman web yang umumnya berbentuk dokumen HTML. Perangkat lunak server web yang umum digunakan antara lain: Microsoft IIS dan Apache.

#### Cara kerja web server

Cara kerja dari server web sebagai berikut.

1. ﻿﻿﻿Klien berupa browser mengirimkan permintaan menggunakan HTTP Request ke server.
2. ﻿﻿﻿Server Web akan merespons permintaan tersebut dengan mengirimkan HTTP Response ke browser.

![[Screenshot 2024-10-26 at 14.28.54.png]]

Untuk menjadikan server Ubuntu bertindak sebagai server web, lakukan instalasi perangkat lunak Apache. Proses instalasi diawali dengan mendownload Apache.

1. Pastikan Server sudah terhubung ke internet.
2. Lakukan download dan instalasi Apache menggunakan perintah berikut.
![[Screenshot 2024-10-26 at 14.29.32.png]]

Perintah tersebut akan melakukan update repository dan melakukan instalasi Apache. Secara default, konfigurasi Apache terletak pada directory letc/apache2.

Sekarang buka web browser dari komputer lain, lalu akses alamat IP http://192.168.1.135 (alamat dari web server Apache). Bila berhasil maka Anda menjumpai tampilan seperti pada Gambar 5.60.

![[Screenshot 2024-10-26 at 14.29.59.png]]

Secara default, konten tersebut berasal dari file index.html yang terdapat pada /var/www/html/index.html. Jika hendak mengubah konten website tersebut, dapat menggunakan perintah berikut.

![[Screenshot 2024-10-26 at 14.30.19.png]]

Jika diakses menjadi seperti tampilan berikut.

![[Screenshot 2024-10-26 at 14.30.38.png]]





## [[11. Membangun DNS Server]]

Pada dasarnya manusia lebih mudah mengingat nama, sedangkan komputer lebih memahami angka sehingga diperlukan satu sistem yang dapat menerjemahkan nama ke dalam angka sehingga mudah dipahami oleh komputer. Server Domain Name System (DNS) merupakan suatu layanan aplikasi yang menerjemahkan nama domain menjadi alamat IP atau sebaliknya.

Untuk memberikan ilustrasi cara kerja secara sederhana dari protokol DNS, perhatikan gambar berikut.

![[Screenshot 2024-10-26 at 14.31.21.png]]
1. ﻿﻿﻿Klien 192.168.1.10 mengakses server web menggunakan alamat www.UTku. ac.id, komputer klien akan mencari informasi tentang www.UT-ku.ac.id ke server DNS yang ditetapkan (192.168.1.200). Klien melakukan query ke server DNS.
   
2. ﻿﻿﻿Ketika menerima query dari DNS klien, server DNS akan mencari dalam tabel DNS, kemudian merespon query tersebut dengan memberikan informasi bahwa www.UT-ku.ac.id = 192.168.1.135 kepada klien.
   
3. ﻿﻿﻿Setelah mengetahui bahwa www.UT-ku.ac.id adalah 192.168.1.135 maka klien akan melakukan http request (http://192.168.1.135) ke HTTP server (192.168.1.135).
   
4. ﻿﻿﻿Server web akan mengirimkan respons dengan mengirimkan konten dari server web tersebut ke Klien.

#### Bind

Perangkat lunak DNS dapat menggunakan Bind. Untuk menjadikan server Ubuntu sebagai server DNS maka Server perlu download dan diinstal Bind. Untuk proses instalasi dan konfigurasi Bind, pastikan server terhubung dengan internet dan lakukan langkah berikut.

1. Gunakan perintah berikut untuk melakukan instalasi Bind9.
   ![[Screenshot 2024-10-26 at 14.32.15.png]]
2. Setelah bind9 terinstal, langkah berikutnya adalah melakukan konfigurasi dengan menggunakan perintah:
   ![[Screenshot 2024-10-26 at 14.32.42.png]]

3. Mendefinisikan forward lookup zone dan reverse lookup zone. Forward lookup zone berisi pemetaan antara nama host dan alamat IP. Sebaliknya reverse lookup zone berisi pemetaan yang menghubungkan alamat IP dengan nama host. Untuk membuatnya tambahkan script yang terdapat pada Gambar 5.66 di bagian paling bawah dari file named.conf.default-zones
   
   ![[Screenshot 2024-10-26 at 14.33.00.png]]
4. ﻿﻿﻿UT.ac.id merupakan nama domain yang akan dibuat. Db.UT merupakan forward dan db.192 merupakan reverse.
   
5. Salin file db.local ke db.UT dan db. 172 ke db.192 dengan menggunakan perintah berikut:
   ![[Screenshot 2024-10-26 at 14.33.28.png]]

6. Kemudian edit file db.UT menggunakan perintah berikut:
   ![[Screenshot 2024-10-26 at 14.33.47.png]]
7. Sehingga muncul tampilan berikut:
   
   ![[Screenshot 2024-10-26 at 14.34.10.png]]
   
8. Kemudian edit bagian bawah sehingga menjadi seperti berikut.
   
![[Screenshot 2024-10-26 at 14.34.31.png]]

9. Simpan dan keluar dari file db.UT. Kemudian edit file db. 192 menggunakan perintah berikut:
   
   ![[Screenshot 2024-10-26 at 14.34.53.png]]
10. Edit isi dari file db. 192 sehingga menjadi seperti berikut:

![[Screenshot 2024-10-26 at 14.35.11.png]]
11. Simpan dan keluar dari file db. 192
    ![[Screenshot 2024-10-26 at 14.35.36.png]]

12. Tambahkan script berikut di baris paling bawah pada file resolv.conf
    ![[Screenshot 2024-10-26 at 14.35.52.png]]

13. Restart service Bind9 dengan perintah /etc/init.d/bind9 restart

14. Kemudian verifikasi hasilnya dengan menggunakan nslookup, seperti pada Gambar 5.70
    ![[Screenshot 2024-10-26 at 14.36.19.png]]


15. Sekarang buka web browser dari komputer lain, lalu akses alamat www.UT.ac.id. Bila berhasil, maka anda menjumpai tampilan seperti pada Gambar 5.71
    
    ![[Screenshot 2024-10-26 at 14.36.40.png]]

Hasil akhir dari kegiatan praktik, Anda sudah berhasil melakukan instalasi dan konfigurasi server Ubuntu yang berperan sebagai Server Web, DNS dan DHCP.

