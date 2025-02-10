---
tags:
  - dasar_infrastruktur_teknologi_informasi
---
# Kegiatan Belajar 1 - Perancangan Jaringan
## [[01. Konsep Perancangan Jaringan]]

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


## [[02. Metodologi Perencanaan Jaringan Komunikasi Data]]

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



## [[03. NDLC (Network Development Life Cycle)]]

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



## [[04. Metode Jaringan Bertingkat]]

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
