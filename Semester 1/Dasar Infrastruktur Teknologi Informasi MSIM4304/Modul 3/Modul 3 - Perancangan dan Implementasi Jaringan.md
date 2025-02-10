---
tags:
  - dasar_infrastruktur_teknologi_informasi
---
# [[Kegiatan Belajar 1 - Perancangan Jaringan]]
## Konsep Perancangan Jaringan

Dalam membangun suatu sistem jaringan komuniaksi data maka diperlukan perencanaan yang matang agar dapat menghasilkan jaringan yang dapat memebuhi kebutuhan pengguna dengan anggaran biaya yang optimal. Perencanaan yang akurat terhadap pembangunan sistem jaringan komunikasi dapat memberi manfaat sebagai berikut

1. Memenuhi kebutuhan pengguna secara optimal
2. Mendukung sistem informasi yang telah ada
3. Memudahkan pengelola dan pemeliharaan jaringan
4. Memudahkan proses troubleshooting
5. Memudahkan penyususnan anggaran
6. memudahkan pengembangan jaringan (Scaleable)

Dalam membangun suatu jaringan, terdapt beberapa aspek yang perlu dipertimbangkan dapa proses perencanaan antara lain sebagai berikut:

#### Scaleable

Ssitem jaringan komunikasi data yang akan dibangun memiliki kemungkinan untuk diperbesar (bersifat scaleable) sehingga apabila diperlukan di kemudian hari jaringan dapat ditingkatkan kemampuannya (kapasitas, jangkauan, kecepatan) tanpa harus membongka jaringan secara total.

#### Ketersediaan (Availability) dan Stabilitas (Stability)

Ketersediaan dan kestabilan sistem merupakan hal yang sangat penting pada suatu layanan teknologi informasi termasuk didal;ammnya infrasutruktur jaringan data. Penerapan teknologi tault tolerant dan redundancy pada perangkat merupakan salah satu upaya untuk memastikan ketersediaan dan stabilitas sistem sehingga dapat menyediakan sistem jaringan yang andal

#### Migrasi (Migration)

Sistem harus menyediakan kemampuan untuk dapat diadaptasiklan secara mudah pada proses migrasi dengan adanya kemungkinan perubahan terhadap teknologi yang telah digunakan dengan teknologi baru.

#### Kompatibilitas (Compatibility) Perangkat

Penting bagi pengguna atau perencana memilih perangkat yang memiliki tingkat kompatibilitas yang tinggi agar daapt membangun jaringan yang fleksibel terhadap perbedaan perangkat dan protokol jaringan.


## Metodologi Perencanaan Jaringan Komunikasi Data

Dalam pembangunan suatu infrastruktur hjaringan komunikasi data dibutuhkan perancangan dan teknik untuk membangun jaringan komunikasi data. Tersedia beberapa jenis metode dalam perencanaan jaringan komunikasi data sebagai berikut:

#### A. Metode Bottom-Up

Jaringan dibangun berdasarkan kebutuhan setiap unit atau departemen dalam suatu instansi. Kelebihan dari metode ini adalah setiap unit dapat membangun jaringannya sesuai kebutuhan spesifik mereka. Metode ini memiliki kekurangan yakni pada saat melakukan penggabungan jaringan lokal setiap unit merupakan pekerjaan yang relatif lebih rumit sehingga memerlukan usaha yang lebih besar dari sisi biaya, tenaga dan waktu

#### B. Metode Top-Down

Metode untuk merancang jaringan yang dimulai dari lapisan atas model referensi Open System Interconnection sebelum pindah ke lapisan bawah. Metodologi top-down berfokus pasa lapisan aplikasi, session, dan transport sebelum pemilihan router, switch, dan media yang direncanakan akan beroperasi pada lapisan bawah. Metode top-down bersifat iteratif, desain model logis dan desain fisik dapat berubah sesuai dengan banyaknya informasi yang dikumpulkan.

Desain top-down dilakukan dengan menggunakan empat fase yang terdiri atas:

- **Melakukan analisis kebutuhan**, pada fase ini, network analyst melakukan wawancara kepada user dan personil teknis untuk memperoleh pemahaman sasaran bisnis dan teknis dari sistem yang baru akan dibangun atau sistem yang akan dikembangkan. Analisis kondisi jaringan yang telah ada atau sedang digunkaan, mencakup topologi jaringan dan kinerja dari jaringan.
  
- **Mengembangkan desain logis**, analisis topologi logis untuk jaringan baru atau yang akan dikembangkan, sisitem pengalamatan, penamaan, protokol routing dan switching, serta perencanaan keamanan dan desain pengelolaan jaringan.
  
- **Mengembangkan desain fisik**, pada fase ini ditentukan oleh teknologi dan produk khusus untuk merealisasikan desain logis yang telah dibuat sebelumnya.
  
- **Melakukan pengujian, optimasi, dan dokumentasi desain**, menulis dan menerapkan rencana pengujian, membangun dokumentasi desain jaringan.

#### C. Metode PPDIOO (Prepare, Plan, Design, Implement, Operate, dan Optimize)

![[Screenshot 2024-09-30 at 15.58.48.png]]

CISCO memperkenalkan suatu metode perancangan jaringan dengan model PPDIOO yang terdiri dari beberapa tahapan berikut:

##### 1. Fase Prepare (Persiapan)

Fase pertama ini sama sekali tidak teknis. Tujuan utama dari fase ini untuk memperkuat alasan terkait rencana pengembangan jaringan. Fase ini akan melibatkan pihak pengambil keputusan untuk mencari tahu bisnis yang dimiliki perusahaan dan dukungan teknis yang diperlukan untuk pengembangan bisnis

##### 2. Fase Plan (Perencanaan)

Dilakukan dengan tujuan untuk menilai jaringan tersebut, melakukan gap analysis (analisis kesenjangan) pada perancangan terbaik suatu arsitektur, dengan melihat perilaku dari lingkungan operasional. 

Berdasarkan hasil analisis sebelum dilakukan rencana penerapan, menetapkan petunjuk tahapan demi tahapan termasuk milestone untuk dilakukan pengujian. Perencanaan harus sejalan dengan ruang lingkup, biaya, dan parameter sumber daya yang disesuaikan dengan kebutuhan bisnis.

##### 3. Fase Design (Desain)

Desain yang dibuat dalam dase ini akan berisi semua yang diperlukan dalam poembangunan jaringan. Desain jaringan dikembangkan berdasarkan persyaratan teknis dan bisnis yang diperoleh dari kondisi sebelumnya. Spedifikasi desain jaringan adalah desain yang bersifat komprehensif, dan terperinci, yang memenuhi persyaratan teknis dan bisnis.

##### 4. Fase Implement

Pada fase ini, peralatan-peralatan dipasang dan dikonfigurasikan sesuai spedifikasi rancangan. Setiap langkah dalam implementasi harus menyertakan deskripsi, rindian pedoman pelaksanaan, perkiraan waku, langkah antisipasi jika terjadi kegagalan dan infomrasi lainnya sebagai referensi tambahan. Pada fase ini juga dilakukan proses pengujian sebelum melangkah pada fase operasional.

##### 5. Fase Operate (Operasional)

Dalam fase ini jaringan telah di-deploy dan digunakan oleh pengguna. Pada fase ini diperlukan personil yang senantiasa melakukan pemantauan dan pemeliharaan jaringan karena dalam dase ini aktivitas yang dilakukan meliputi pengelolaan dan pemantauan komponen-konponen jaringan serta pemeliharaan routing, memastikan kinerja jaringan berjalans ecara optimal, mengidentifijkasi, dan memperbaiki masalah yang muncul pada jaringan

##### 6. Fase Optimize (OPtimalisasi)

Dalam fase ini jaringan secara proaktif dipantau dan diubah untuk meningkatkan kinerja atau menyelesaikan masalah. Jika perubahannya cukup besar, siklus hidup ini dapat dimulai kembali pada tahapan persiapan.



## NDLC (Network Development Life Cycle)

Dalam proses pengembangan suatu jaringan, selah satu metoide yang umum diterapkan adalah Network Development Life Cycle (NDLC)

NDLC merupakan metode yang digunakan dalam mengembangkan atau merancang jaringan infrastruktur yang memungkinkan terjadinya pemantauan jaringan untuk mengetahui statuistik dan kinerja jaringan. yang dilakukan secara berkesinambungan.

NDLC dibagi menjadi 6 tahapan berikut:

##### 1. Analysis

Tahapan ini merupakan tahapan awal yaitu melakukan aktivitas pengumpulan infrmasi untuk menganalisa kebutuhan, permintaan user, dan topologi, serta masalah jaringan yang sudah tersedia. Metode yang digunakan untuk mengumpulkan informasi pada tahapan ini antara lain:

1. Wawancara, dilakukan dengan pihak terkait agar mendapatkan data yang konkret dan lengkap
2. Survey, Dilakukan l;langsung ke lokasi untuk memperoleh data secara visual terkait dengan sistem jaringan yang sudah ada dan pemanfaatan, serta kinerjanya.
3. Mempelajari dan memahami dokumen yang berkaitan dengan jaringan yang sudah dibangun dan master plan teknologi informasi. Pada umumnya pengembangan suatu sistem memiliki dokumentasi menjadi pendukung akhir dari pengembangan tersebut

![[Screenshot 2024-09-30 at 19.23.51.png]]

Berikut adalah contoh informasi yang dikumpulkan pada tahapan awal:

1. Pengguna; jumlah user, kegiatan yang sering dilakukan
2. Perangkat keras dan perangkat lunak yang digunakan dan status perangkat
3. Infomrsi jenis data yang dikelola dan digunakan pada organisasi serta mekanisme pengamanan dan mekanisme hak akses yang diterapkan serta kapasitas data.
4. Kondisi jaringan yang berkaitan dengan konfigurasi, volume trafik, protokol, network monitoring yang ada pada saat ini, harapan dan rencana pengembangan.
5. Kondisi fisik yang terkait dengan kondisi bangunan, kelistrikan, sistem keamanan yang ada, dan rencana pengembangan


###### 2. Design
Data data yang telah dikumpulkan pada tahapan ini digunakan sebagai bahan perancangan jaringan. Rancangan dapat perupa topologi jaringanm sistem pengalamatan jaringan, layout perkabelan yang akan dibangun dan sebagainya. Alat bantu yang daopat digunakan untuk melakukan perancangan ini misalnya Visio.

##### 3. Simulation Prototype

Tahapan selanjutnya adalah melakukan simulasi dan membuat contoh prototype berdasarkan hasil desain yang telah dirancang sebelumnya dengan menggunakan simulator ataupun perangkat rill. Alat bantu untuk menyediakan prototype berupa simulator Packet Tracert, GNS3, dan sebagainya

##### 4. Implementation

Tahapan ini merupakan tahapan mengimplementasikan rancangan yang telah dibuat meliputi
1. Penyediaan perangkat keras dan lunak
2. penetapan peralatan dan menginterkoneksikannya
3. Instalasi dan konfigurasi perangkat keras/lunak
4. pengujian
5. dekumentasi
6. pelatihan SDM
7. evaluasi terhadap hasil implementasi rancangan apakah telah sesuai dengan yang telah direncanakan
8. pemeliharaan, yakni pemeliharaan operasional jaringan agar kinerjanya tetap optimal

##### 5. Monitoring

Setelah tahapan implementasi dilaksanakan, tahapan pemantauan terhadap jaringan dapat dilakukan. Tahapn ini bertujuan untuk memastikan pembangunan/pengembangan jaringan yang dilakukan dapat berjalan sesuai dengan tujuan yang telah direncanakan

##### 6. Management

Tahapn in imerupakan tahapan terakhir dalam metode NDLC. Pada tahapan ini pembuatan kebijakan dibuat dan ditetapkan untuk mengatur adar sistem jaringan yang telah dibangun dapat berjalan secara baik dan optimal. Kebijakan yang ditetapkan bergantung pada level manajemen dan strategi bisnis. Penerapan teknologi informasi harus selaras dengan strategi bisnis organisasi.



## Metode Jaringan Bertingkat

Terlepas dari ukuran atau kebutuhan terhadap jaringan, Faktor penting untuk keberhasilan pelaksanaan setiap desain jaringan adalah dengan mengikuti prinsip prinsip rekayasa terstruktur yang baik, yang terdiri dari:

- Hierarki: Model jaringan hierarki merupakan suatu tool yang dapat digunakan untuk membagi kompleksitas jaringan menjadi area yang lebih kecil dan lebih mudah dikelola
  
- Modularitas: Dengan memisahkan berbagai fungsi yang ada pada jaringan menjadi modul akan lebih mudah untuk merancang jaringan.
  
- Resistan: Jaringan harus dapat dijamin ketersediannya agar tetap dapat digunakan baik dalam kondisi normal maupun kondisi abnormal
  
- Fleksibilitas: Kemampuan untuk memodifikasi bagian jaringan, menambahkan layanan baru atau meningkatkan kapasitas tanpa perlu merombak secara keseluruhan.

Pada arsitektur jaringan yang besar dan bersifat enterprise, akan lebih baik jmenggunakan jaringan berisfat heirarki agar dapat mempermudah dalam proses pembangunannya, serta daapt dilakukan secara bertahap dan scalable. Model jaringan hierarki terdiri dari tiga lapisan yang berfokus pada fungsionalnya:

##### 1. Access Layer

Berfungsi menyediakan akses terhadap jaringan bagi pengguna. Layer ini sering dikaitkan dengan perangkat perangkat jaringan layer dua dari arsitektur Open System Interconnection (OSI) reference model yaitu switch yang memiliki fungsi menghubungkan perangkat yang bersifat end point, misalnya komputer, notebook. Access Layer terhubung langsung dengan Distribution Layer

##### 2. Distribution Layer,

Merupakan layer yang menghubungkan access layer dengan core layer. Perangkat yang terpasang di distribution layer harus memiliki fungsi berikut:
- Sebagai aggregator dari perangkat perangkat access layer dan menjadi batas akhir dari broadcarst domain
- Menyediakan fungsi routing dan mengatur kebijakan akses pada jaringan

##### 3. Core Layer

Merupakan layer yang memiliki lalu lintas jaringan terpadat dan memiliki kecepatan yang tinggi. Core layer bertindak sebagai aggregator dari perangkat distribution layer


![[Screenshot 2024-09-30 at 19.57.20.png]]



# [[Praktik 1 - Merancang dan mengkonfigurasi Jaringan]]

Praktik merancang dan membangun jaringan menggunakan tool simulator Packet Tracert. Kegiatan praktik ini diawali dengan tahapan perencanaan, perancangan, implementasi dengan cara mengkonfigurasikan perangkat perangkat yang digunakan 

## Skenario 1

Pada skenario 1, mengkonfigurasi perangkat perangkat jaringan berdasarkan topologi dibawah ini

![[Screenshot 2024-09-30 at 20.14.58.png]]

#### Prangkat yang digunakan antara lain:

- 2 unit Switch 2960
- 2 unit router 1941
- 6 unit PC
- Kabel UTP (Straight Through dan Cross Over)

#### Pengalamatan IP yang terpasang direncanakan seperti yang terlihat pada tabel berikut:

![[Screenshot 2024-09-30 at 20.16.20.png]]

#### Tahapan Tahapannya

1. Buka aplikasi packet tracert kemudian susun perangkat perangkat jaringan seperti gambar di atas
   
2. Lakukan pemasangan alamat IP pada perangkat perangkat rtersebut sesuai dengan daftar alamat IP yang terdapat pada tabel diatas.
   
   Untuk memasang alamap pada perangkat PC contohnya sebagai berikut:
   
   - Masuk ke menu IP Configuration dan isikan parameter IP address, subnet mask dan default gateway seperti berikut ini
     
    ![[Screenshot 2024-09-30 at 20.18.28.png]]

- Lakukan verifikasi terhadap konfigurasi alamat IP pada PC0 dengan masuk ke Command Prompt dan ketikan ipconfig sehingga muncul tampilan berikut
	![[Screenshot 2024-09-30 at 20.19.34.png]]

- Perhatikan amalat yang terpasang, pastikan kesesuaiannya dengan alamat IP yang sudah direncanakan
- Dengan cara yang sama pada langkah sebelumnya. Pasangkan alamat IP dan parameter lainnya yang diperlukan pada PC 6 sampai 6 sesuai tabel diatas

3. Lakukan konfigurasi terhadap Router 1 seperti berikut:
   
- Pilih dan klik Router1
  
- Melalui tab CLUI, masuk ke console Router 1, seperti gambar berikut
	  ![[Screenshot 2024-09-30 at 20.21.41.png]]

- Jawab "No" pada pertanyaan " COntinue with coinfiguration dialog?". Kemudian tekan ENTER sehingga muncul promp Router>
  
- Beri nama perangkan router dengan nama R1 seperti bambar berikut
	  ![[Screenshot 2024-09-30 at 20.22.58.png]]

- Lanjutkan dengan mengkonfigurasi alamat IP beserta subnet mask dan aktifkan interface G0/0 dan G0/1 di Router1 seperti gambar berikut
	  ![[Screenshot 2024-09-30 at 20.23.41.png]]

- Verifikasi hasil konfigurasi alamat yang didefinisikan pada Router1 menggunakan perintah # show run
	  ![[Screenshot 2024-09-30 at 20.24.27.png]]

4. Lakukan konfigurasi terhadap Router2

- Pilih dan klik Router2
  
- Melalui tab CLI, masuk ke konsole Router2, sehingga muncul tampilan seperti pada gambar berikut:
	![[Screenshot 2024-09-30 at 20.26.13.png]]

- Jawab "no" pada pertanyaan "Continue with configuration dialog?" kemudian tekan ENTER sehingga muncul promp Router>
  
- Beri nama perangkat router dengan nama R2, dilakukan dengan cara berikut:
	![[Screenshot 2024-09-30 at 20.28.55.png]]

- Lanjutkan dengan mengkonfigurasi alamat IP beserta subnet mask dan aktifkan interface G0/0 dan G0/1 di Router2 seperti gambar berikut:
	![[Screenshot 2024-09-30 at 20.30.33.png]]

- Verifikasi hasil konfigurasi alamat yang didefinisikan pada router 2 menggunakan perintah # show run
	  ![[Screenshot 2024-09-30 at 20.31.11.png]]

 
 5. Untuk menghubungkan dua jaringan yang berbeda alamat network diantara dua atau beberapa router maka diperlukan routing protokol. Maka pada langkah berikutnya kita akan mengkonfigurasi routing protokol pada kedua router. Berikut caranya:
	![[Screenshot 2024-09-30 at 20.32.26.png]]

6. Hasil konfigurasi routing protokol RIP pada kedua router dengan menggunakan keywork "show ip route"
	![[Screenshot 2024-09-30 at 20.33.02.png]]
	 Dari tabel routing nempak alamat network 192.168.3.0 yang dapat dijangkau dengan jarak 1 hop melalui interface G0/0 begitu pula pada tabel routing yang terdapat di R2, tampak bahwa alamat jaringan 192.168.1.0 dapat dijangkauy dari r2 melalui interface G0/0 dengan jarak 1 hop


7.  Simpan hasil konfiguirasi ke R1 dan R2 ke NVRAM dengan menggunakan keyword copy run start di masing-masing router agar konfigurasi yang sudah dilakukan tidak hilang ketika router dimatikan
	   ![[Screenshot 2024-09-30 at 20.35.32.png]]

8. Untuk melihat hasil proses penyimpanan, dapat dilakukan dengan menggunakan keyword show start, pandingkan isinya dengan isi konfigurasi yang terdapat di RAM yang bisa kita lihat dengan keyword sh run.
   
9. Setelah selesai mengkonfigurasi jaringan, sehingga PC yang terdapat di jaringan 192.168.1.0 dapat berkomunikasi dengan PC yang berada di jaringan 192.168.3.0. Hal tersebut dapat dibuktikan dengan menggunakan tool ping melalui Command Prompt PC1. ketikan ping 192.168.3.12 untuk memastikan konektivitas sudah terbentuk antara PC1 ke PC4
	   ![[Screenshot 2024-09-30 at 20.38.03.png]]

10. Untuk mengetahui jalur yang dilalui dapat diverifikasi dengan menggunakan perintah tracert 192.168.3.2

11. Terakhir jangan lupa menyimpan hasil konfigurasi dengan menggunakan keyword copy run start di kedua router.
	![[Screenshot 2024-09-30 at 20.39.26.png]]

Pada gambar terlihat untuk menjangkau 192.168.3.12 dari PC1 dapat melalui 192.168.1.1 -> 192.168.2.2 -> dan akhirnya sampai di 192.168.2.13


## Skenario 2

Pada skenario ini akan dikonfigurasikan perangkat. perangkat jaringan berdasarkan topologi VLAN (Virtual Local area Network). VLAn merupakan jaringan LAN yang dapat melakukan sergemtasi jaringan berbasis player pada layer 2 secara logik sehingga pemisahan jaringan tidak berdasarkan lokasi fisik.

Praktik ini disimulasikan untuk 3 lantai dalam satu gedung yang terdiri dari 3 departemen yakni: marketing, education, dan engineering. Antar departemen memiliki alamat jaringan yang berbeda

![[Screenshot 2024-09-30 at 21.23.31.png]]

#### Prangkat yang digunakan antara lain:

- 1 unit Switch L3 3560
- 8 unit PC
- Kabel UTP (Straight Through dan Cross Over)


#### Pengalamatan IP yang terpasang direncanakan seperti yang terlihat pada tabel berikut:

![[Screenshot 2024-09-30 at 21.24.07.png]]

![[Screenshot 2024-09-30 at 21.24.16.png]]

![[Screenshot 2024-09-30 at 21.24.26.png]]

#### Ikuti tahapan-tahapan berikut :

1. Buka aplikasi packet tracert kemudian susun perangkat-perangkat jaringan seperti pada Gambar 3.22 dan berdasarkan Tabel 3.2, 3.3 serta 3.4
   
2. Lakukan pemasangan alamat IP pada perangkat-perangkat tersebut sesuai dengan daftar alamat IP yang terdapat pada Tabel 3.4. Untuk pemasangan alamat pada perangkat PC contohnya sebagai berikut:
   
- Masuk ke menu IP Configuration,  isikan parameter-parameter IP address, subnet mask dan default gateway seperti pada Gambar 3.23 berikut:
	![[Screenshot 2024-09-30 at 21.25.30.png]]

- Lakukan verifikasi terhadap konfigurasi alamat IP pada PC0 dengan masuk ke Command Prompt dan ketikan “ipconfig”
	![[Screenshot 2024-09-30 at 21.25.51.png]]

- Perhatikan alamat yang terpasang, pastikan sesuai dengan yang direncanakan.
  
- Dengan cara yang sama pada langkah sebelumnya, pasangkan alamat IP dan parameter lainnya yang diperlukan pada PC 2 s/d 8 sesuai dengan Tabel 3.4

3. Berikutnya kita akan membuat database VLAN di Switch MLS1, pembuatan database VLAN dilakukan pada suatu switch yang berstatus sebagai VTP server sedangkan switch lainnya berstatus sebagai VTP client. Database VLAN yang dibuat di VTP server secara periodik akan didistribusikan ke switch lainnya yang berstatus sebagai VTP Client dan berada dalam 1 domain dengan VTP server
   
   Cara mendefinisikan status VTP server dan database VLAN pada switch MLS1 dapat dilihat pada Gambar 3.24
	![[Screenshot 2024-09-30 at 21.26.54.png]]
	Pada konfigurasi yang terdapat pada Gambar 3.24 mendefinisikan status VTP dari switch MLS1 adalah VTP server sehingga MLS1 secara periodik akan menginformasikan VTP message (salah satunya informasi database VLAN) ke VTP client secara periodik. Selain status VTP, pada konfigurasi tersebut mendefinisikan juga nama domain bernama UniversitasTerbuka. Nama domain bersifat case-sensitif sehingga penggunaan huruf perlu diperhatikan pada saat mendefinisikan nama domain di switch yang berstatus VTP Client

4. Lakukan verifikasi daftar vlan yang terbentuk dengan menggunakan keyword show vlan
	![[Screenshot 2024-09-30 at 21.29.35.png]]
	Perhatikan daftar vlan yang terdapat di Gambar 3.25, nampak terdapat 3 VLAN yang sebelumnya telah didefinisikan yakni VLAN Marketing, Education dan Engineering akan tetapi saat ini belum memiliki anggota VLAN. Semua port yang terdapat pada MLS1 secara default merupakan anggota dari VLAN 1

5. Tahap berikutnya, mendefinisikan port trunking pada MLS1, dengan cara berikut:
	![[Screenshot 2024-09-30 at 21.30.35.png]]
	Pada konfigurasi yang terdapat pada Gambar 3.26 port trunking didefinisikan pada interface G0/1 dengan menggunakan protokol 802.1Q. Protokol ini didefinisikan pada jalur trunking agar dapat melewatkan trafik yang berasal dari beberapa VLAN berbeda pada jalur yang sama. Protokol 802.1Q merupakan protokol open standard

6. Agar vlan database yang sudah didefinisikan di MLS1 dapat didistribusikan ke switch lainnya, maka kita perlu mendefinisikan port trunking pada SW1 dan juga memberi domain yang sama dengan MLS1 serta menetapkan status sebagai VTP client, dengan cara berikut:
	![[Screenshot 2024-09-30 at 21.31.11.png]]

7. Lakukan perintah show vlan untuk melakukan verifikasi terhadap distribusi database vlan yang dilakukan oleh MLS1 ke SW1 sudah diterima melewati jalur trunking
	![[Screenshot 2024-09-30 at 21.31.34.png]]

8. Lakukan hal yang sama terhadap SW2 dan SW3 dengan cara yang sama seperti yang dilakukan pada SW1 (konfigurasi domain, vtp client dan port trunking). Sehingga SW2 dan SW3 juga memiliki daftar vlan yang sama seperti yang dimiliki SW1 dan MLS1.

9. Tahap berikutnya adalah menetapkan keanggotaan VLAN berbasis port pada masing-masing switch (SW1, SW2 dan SW3). Berikut konfigurasi yang dilakukan untuk menetapkan keanggotaan VLAN pada SW1 dengan ketentuan sebagai berikut:
	1. Anggota VLAN 2 terdiri dari port F0/1 sd F0/10
	2. Anggota VLAN 3 terdiri dari port F0/11 sd F0/20
	3. Anggota VLAN 4 terdiri dari port F0/21 sd F0/24
	![[Screenshot 2024-09-30 at 21.32.32.png]]

10. Lakukan verifikasi terhadap konfigurasi keanggotaan VLAN pada SW1 dengan menggunakan keyword sh vlan, seperti pada Gambar 3.30
	![[Screenshot 2024-09-30 at 21.33.30.png]]
	Lakukan verifikasi terhadap konfigurasi keanggotaan VLAN pada SW1 dengan menggunakan keyword sh vlan, seperti pada Gambar 3.30

11. Lanjutkan konfigurasi untuk menetapkan keanggotaan Vlan pada SW2 dan SW3. Lakukan dengan konfigurasi yang sama seperti yang dilakukan pada SW1. Sehingga Vlan yang terdapat pada SW2 dan SW3 memiliki anggota berupa port-port sebagai berikut:
	1. Anggota VLAN 2 terdiri dari port F0/1 sd F0/10
	2. Anggota VLAN 3 terdiri dari port F0/11 sd F0/20
	3. Anggota VLAN 4 terdiri dari port F0/21 sd F0/24

12. Setelah selesai menetapkan keanggotaan Vlan pada SW2 dan SW3, PC yang terhubung dalam Vlan yang sama sudah bisa saling berkomunikasi. Misalkan PC0 dengan PC2
	![[Screenshot 2024-09-30 at 21.34.39.png]]

13. Anggota Vlan yang berbeda belum bisa saling terhubung secara logik walaupun kedua host tersebut terhubung secara fisik pada switch yang sama. Misalkan antara PC0 dengan PC1
	![[Screenshot 2024-09-30 at 21.35.02.png]]
	Hal tersebut dikarenakan PC0 dan PC1 berada dalam vlan berbeda yang secara logic terpisah dan tidak saling terhubung

14. Anggota vlan yang berbeda dapat saling terhubung/berkomunikasi dengan melalui router atau switch layer 3. Pada topologi yang sedang kita gunakan dapat memanfaatkan kemampuan Switch MLS1 untuk menghubungkan antara Vlan dengan mengaktifkan kemampuan routing dan mengaktivasi dan memberi alamat pada interface virtual VLAN 2, 3 dan 4, seperti pada konfigurasi di Gambar 3.34 
	![[Screenshot 2024-09-30 at 21.35.45.png]]

15. Lakukan verifikasi hasil aktivasi routing dengan melihat isi tabel routing menggunakan keyword show ip route, seperti pada Gambar 3.34 
	![[Screenshot 2024-09-30 at 21.36.13.png]]

16. Aktivasi routing dan interface Vlan pada MLS1 menyebabkan seluruh anggota Vlan yang berbeda sudah dapat saling terhubung. Lakukan verifikasi menggunakan tool ping untuk menguji konektivitas antara PC0 yang merupakan anggota Vlan Marketing dapat berkomunikasi dengan PC1 yang merupakan anggota Vlan Education, seperti pada Gambar 3.35
	![[Screenshot 2024-09-30 at 21.36.41.png]]

17. Anda telah berhasil membangun jaringan Vlan, simpan hasil konfigurasi dengan menggunakan keyword copy run start pada setiap perangkat MLS1, SW1, SW2 dan SW3, agar konfigurasi tidak hilang ketika perangkat-perangkat tersebut dimatikan


