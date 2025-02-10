---
tags:
  - dasar_infrastruktur_teknologi_informasi
  - materi_5_DITI
---
# Kegiatan Belajar 1 - Praktik 2 - Implementasi Virtualisasi


## [[01. Konsep Virtualisasi]]

Virtualisasi merupakan suatu konsep yang mengijinkan suatu komputer untuk dibagi dalam beberapa lingkungan pada saat yang sama. Lingkungan ini dapat saling berhubungan atau bahkan tanpa saling berhubungan sama sekali. Suatu lingkungan disadari ataupun tidak bisa jadi berjalan pada suatu lingkungan yang bersifat virtual; situasi semacam ini umum disebut sebagai Virtual Machine (VM). 

VM sering menjadi tempat bagi sistem operasi yang lainnya (misalnya Linux, Windows dan sebagainya). Instalasi sistem operasi lanjutan ini umum dikenal sebagai sistem operasi tamu (Guest operating systems). 

Virtual machine melakukan abtraksi perangkat keras dari suatu komputer (CPU, memori, disk) lokasi dimana VM di install, menjadi beberapa lingkungan eksekusi, sehingga menciptakan ilusi bahwa masing-masing lingkungan menjalankan komputernya secara terpisah

#### Keuntungan Virtualisasi Server

Penerapan virtualisasi server memiliki beberapa keuntungan antara lain:

1. pengurangan biaya investasi perangkat keras,
2. kemudahan dalam mekanisme backup dan recovery
3. kemudahan deployment,
4. mengurangi penggunaan energi listrik dan pembangkitan panas,
5. mengurangi biaya ruang penyimpanan perangkat keras,
6. kemudahan pemeliharaan dan pengelolaan,
7. standarisasi perangkat keras,
8. kemudahan aktivitas replacement

#### Kekurangan Virtualisasi Server

Penerapan virtualisasi server  juga memiliki beberapa kekurangan antara lain:

1. satu pusat masalah. Hal ini bisa diantisipasi dengan menyediakan fasilitas backup  secara otomatis dan periodik atau dengan menerapkan prinsip fail over/clustering
   
2. spesifikasi perangkat keras. Virtualisasi membutuhkan spesifikasi server  yang lebih tinggi untuk menjalankan server  induk dan virtual machine di dalamnya.

#### Perangkat Lunak Virtualisasi

Terdapat beberapa macam perangkat lunak virtualisasi, diantaranya Virtual Box, Proxmox, Microsoft Hyper-V dan VMware. Salah satu perangkat lunak yang lazim digunakan untuk melakukan virtualisasi terhadap server adalah VMware. VMware memiliki banyak jenis dan tipe, hal ini dikarenakan adanya banyak keperluan spesifik virtualisasi di berbagai aspek kebutuhan

1. Untuk kebutuhan virtualisasi data center dan infrastruktur cloud disarankan menggunakan seri VMware vCloud, vSphere dan vCenter
   
2. Untuk kebutuhan virtualisasi personal desktop bisa menggunakan VMware Workstation. VMware workstation ada dua jenis: VMware workstation Pro dan VMware workstation Player

Secara umum VMware berisi dua lapisan, yakni:

1. lapisan hardware virtual (virtual machine) di komputer fisik. VMware akan membuat CPU, storage, memory RAM, network adapter dan berbagai komponen virtual lainnya untuk kemudian menjadi virtual machine yang utuh;
   
2. lapisan software Hypervisor yang secara dinamis mengalokasikan sumberdaya di komputer fisik (host computer) pada virtual machine sesuai dengan yang dibutuhkan.

Sistem operasi yang diinstal di virtual machine akan dikenal sebagai guest OS, akan berjalan secara terpisah dengan sistem operasi utama (host OS). Setiap virtual machine tersimpan dalam bentuk file yang dapat disalin dan pindahkan




## [[02. Skenario Membuat Virtual Machine di VMWare]]

Tahapan-tahapan dalam proses pembuatan suatu virtual machine pada Vmware adalah sebagai berikut.

1. Diawali dengan membuka aplikasi Vmware sehingga muncul tampilan berikut: 
   
   ![[Screenshot 2024-10-26 at 10.23.09.png]]

2. Untuk membuat virtual machine, klik Create a New Virtual Machine, sehingga muncul tampilan berikut
   
   ![[Screenshot 2024-10-26 at 10.24.02.png]]
3. Pilih jenis konfigurasi Typical dan tekan tombol Next untuk melanjutkan proses, sehingga muncul tampilan seperti pada Gambar 5.3. 
   
   ![[Screenshot 2024-10-26 at 10.25.09.png]]
   
   Untuk menentukan lokasi file sumber sistem operasi yang akan diinstal. Terdapat 3 pilihan sumber instalasi, yang terdiri atas:
   
   - melalui installer disc, pilih item tersebut jika sistem operasi yang akan diintal dalam bentuk CD/DVD;
   - lokasi directory tertentu dalam bentuk file *.iso, pilih item ini jika installer dalam bentuk file iso. Arahkan ke lokasi file installer berada;
   - tanpa instal sistem operasi, pilih item ini jika hanya akan membuat virtual machine saja, tidak langsung melakukan instalasi sistem operasi

4. Pilih opsi “I will install the operating system later”, untuk membuat virtual machine tanpa menginstal sistem operasi
   
5. Kemudian lanjutkan dengan menekan tombol Next, sehingga muncul tampilan Gambar 5.4 berikut
   ![[Screenshot 2024-10-26 at 10.25.45.png]]

6. Pilih salah satu jenis sistem operasi yang akan diinstal pada virtual machine. Kemudian tekan tombol Next, sehingga muncul tampilan seperti pada Gambar 5.5 berikut
   ![[Screenshot 2024-10-26 at 10.26.30.png]]

7. Tentukan nama virtual machine dan lokasi penyimpanan hasil instalasi.
   
8. Kemudian Tekan tombol Next dan tetapkan kapasitas harddisk dari virtual machine yang akan dibuat
   
   ![[Screenshot 2024-10-26 at 10.27.06.png]]
9. Setelah menetapkan kapasitas disk yang akan digunakan untuk virtual machine tersebut, tekan tombol Next
   
   ![[Screenshot 2024-10-26 at 10.28.54.png]]

10. Proses pembuatan virtual machine telah siap untuk dibuat, proses pembuatan akan dilakukan setelah menekan tombol Finish
    ![[Screenshot 2024-10-26 at 10.29.22.png]]
    



## [[03. Instalasi Sistem Operasi di Virtual Machine]]

![[Screenshot 2024-10-26 at 10.30.41.png]]

1. Untuk melakukan instalasi sistem operasi pilih CD/DVD (SATA), kemudian tentukan lokasi file sumber sistem operasi yang akan diinstal
   
   ![[Screenshot 2024-10-26 at 10.31.12.png]]

2. Kemudian tekan Tombol OK, dilanjutkan dengan mengaktifkan “Power on this virtual machine”. Untuk mengaktifkan virtual machine dan melakukan proses instalasi sistem operasi (guest OS)
   
   ![[Screenshot 2024-10-26 at 10.31.35.png]]
3. Lakukan proses instalasi sistem operasi sampai selesai, sehingga bisa dijalankan melalui virtual machine
   
   ![[Screenshot 2024-10-26 at 10.32.04.png]]
   

Satu komputer fisik dapat dibuat beberapa virtual machine tergantung pada kapasitas memori dan processor serta harddisk yang tersedia



## [[04. Skenario - Mengkonfigurasi Jaringan Virtual Machine]]

Salah satu kemampuan pada Vmware adalah menyediakan kemampuan antar virtual machine agar dapat saling bertukar data melalui jaringan virtual. Virtual Switch digunakan untuk menghubungkan beberapa virtual machine dapat saling berkomunikasi. Beberapa virtual machine dapat dipasang satu atau beberapa network adapter virtual yang memiliki alamat IP dan MAC yang berbeda dan dapat berkomunikasi dengan network adapter fisik

#### Konfigurasi Virtual Adapter

Secara umum dalam VMware terdapat 3 jenis konfigurasi virtual adapter, yaitu:

1. **Bridged network connection**, jenis koneksi ini digunakan jika mengijinkan guest (VM) dapat terhubung dengan guest lainnya dan jaringan fisik dari host sehingga dapat berkomunikasi dengan komputer fisik lainnya. Komputer fisik lainnya akan melihat guest seperti komputer fisik lainnya.

2. **Network Address Translation (NAT) network connection**, jenis koneksi ini mirip seperti jenis koneksi bridge digunakan jika mengijinkan guest (VM) dapat terhubung dengan guest lainnya dan ke jaringan luar (fisik) akan tetapi dengan menggunakan teknik penggantian satu atau beberapa alamat IP yang dimiliki virtual machine ke alamat IP dari komputer fisik (host), sehingga jaringan luar hanya mengetahui alamat IP dari host
   
3. **Host-Only network connection**, jenis koneksi jaringan ini digunakan jika hanya mengijinkan guest hanya dapat terhubung dengan guest lainnya dan dengan komputer host saja
   
   ![[Screenshot 2024-10-26 at 10.35.15.png]]

#### Bridge Network Connection

Pada praktik berikut ini Anda akan mencoba memanfaatkan jenis koneksi Bridge agar Guest OS dapat terhubung dengan host dan jaringan fisik lainnya

![[Screenshot 2024-10-26 at 10.36.29.png]]

Tahapan yang perlu dilakukan untuk menyediakan jaringan dengan topologi seperti pada Gambar 5.14 adalah sebagai berikut

1. Pilih virtual machine yang sudah terinstall dengan sistem operasi Windows sebelumnya
   ![[Screenshot 2024-10-26 at 10.37.13.png]]

2. Pilih Network Adapter kemudian tekan Enter
   
   ![[Screenshot 2024-10-26 at 10.37.42.png]]

3. Setelah muncul tampilan seperti Gambar 5.17, pilih jenis koneksi Bridge dan ceklis Replicate physical network connection state, kemudian tekan tombol OK sehingga jenis koneksi Network adapter berubah menjadi Bridge
   
   ![[Screenshot 2024-10-26 at 10.38.05.png]]

4. Langkah selanjutnya memastikan atau mengkonfigurasi Vmnet yang akan berkorelasi dengan network adapter fisik dan bridge. Untuk melakukan hal tersebut, Pilih Virtual Network Editor yang berada di menu Edit, sehingga muncul Gambar 5.18
   
   ![[Screenshot 2024-10-26 at 10.38.30.png]]

5. Pilih dan klik Tombol Change Setting yang ada pada bagian bawah, untuk mengubah konfigurasi diperlukan hak administrator. Sehingga muncul tampilan seperti pada Gambar 5.19. Kemudian pilih network adapter yang terhubung dengan jaringan fisik untuk dihubungkan dengan network adapter virtual (VMnet0) melalui mekanisme Bridge pada Opsi Bridge to
   
   ![[Screenshot 2024-10-26 at 10.39.07.png]]

6. Kemudian tekan tombol OK, dan aktifkan virtual machine sehingga sistem operasi Windows 7 yang terdapat di dalamnya operasional
   
7. Langkah berikutnya adalah memasangkan alamat IP pada sistem operasi yang terdapat pada network adapter Host (komputer fisik) yang dihubungkan dengan VMnet0 dan network adapater yang terdapat pada sistem operasi Guest (VM), dengan rincian alamat sebagai berikut:
   
   ![[Screenshot 2024-10-26 at 10.40.03.png]]

8. Setelah memasangkan alamat IP pada kedua mesin. Lakukan uji konektivitas diantara kedua mesin tersebut. Dengan menggunakan perintah ping melalui command prompt pada sistem operasi Guest
   
   ![[Screenshot 2024-10-26 at 10.40.36.png]]
   9. Jika mendapatkan hasil seperti pada Gambar 5.21 dan Gambar 5.22, hal tersebut menunjukkan bahwa virtual machine (Guest) sudah terhubung dan dapat berkomunikasi dengan mesin fisik (Host). Bisa dilanjut dengan menguji konektivitas ke mesin fisik lainnya, misal ke alamat 192.168.1.1
  ![[Screenshot 2024-10-26 at 10.41.06.png]]

Dari uji konektivitas tersebut menunjukan bahwa virtual machine (Guest) dapat terhubung dan dapat berkomunikasi dengan mesin fisik lain selain Host.

Dari kedua uji konektivitas tersebut dapat disimpulkan dengan menggunakan mekanisme Bridge, virtual machine (guest) dapat terhubung dan berkomunikasi dengan jaringan fisik

