---
tags:
  - sistem_informasi_management
  - materi_5_SIM
---
# Kegiatan Belajar 2 - Metodologi Pengembangan Sistem Informasi Terstruktur

Metode SDLC hanya memberikan tahapan-tahapan (apa yang harus dilakukan) dalam mengembangkan sistem, tetapi tidak memberikan cara (bagaimana mengembangkannya) dan alat (apa yang harus digunakan) untuk mengembangkannya. Supaya pengembang sistem dapat bekerja dengan efisien dan efektif, metodologi pengembangan sistem perlu diketahui. Metodologi pengembangan sistem (system development methodology) memberikan cara dan alat pengembangan sistem tersebut. 

Metodologi pengembangan sistem yang populer dan banyak digunakan adalah metodologi pengembangan sistem terstruktur (structured approach). Metodologi pendekatan terstruktur (structured approach) memberikan beberapa cara dan beberapa alat pengembangan sistem


## [[07. Cara Pengembangan Sistem]]

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



## [[08. Alat Alat Pengembangan Sistem]]

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


## [[09. Alat-Alat Komunikasi di Tahap Perencanaan]]

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