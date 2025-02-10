---
tags:
  - sains_data
  - materi_16_PSD
---

Salah satu proses yang paling penting dalam data science adalah proses klasifikasi. Klasifikasi selalu terdiri atas tiga bagian utama, yaitu proses pelatihan dari data latih yang tersedia, proses klasifikasi berdasarkan hasil pelatihan, dan proses pengujian berdasarkan pada data uji.

#### Prinsip Pareto

Rasio atau perbandingan jumlah antara data latih dan data uji biasanya menggunakan prinsip Pareto, yaitu 80:20. Di mana peneliti akan meng-gunakan 80% data sebagai data latih dan 20% sisanya sebagai data uji. Prin-sip pareto menyatakan bahwa 80% hasil akhir disebabkan oleh 20% usaha.

Pareto sendiri adalah seorang ekonom dari Italia dengan nama lengkap Vilfredo Pareto, yang pada tahun 1895 menyatakan bahwa sekitar 80% tanah di Italia dimiliki oleh 20% populasi negara tersebut.

![[Screenshot 2024-10-27 at 11.29.43.png]]

Ide dasar dari proses klasifikasi adalah peneliti memiliki serangkaian kategori data yang memiliki kelas tertentu atau lazim disebut label. Kemu-dian, berdasarkan pada label tersebut peneliti akan membuat model yang akan digunakan untuk secara otomatis melakukan klasifikasi dari data uji yang benar-benar baru, tidak diketahui, atau bahkan, data yang berbeda sama sekali.

Gambar 16.1 memberikan ilustrasi tentang proses klasifikasi, di mana peneliti menentukan label atau melakukan proses ekstraksi fitur berdasarkan pada data latih yang dimiliki. Kemudian, proses klasifikasi dilakukan dan komputer akan melakukan penentuan apakah data yang diproses masuk ke dalam kelas pisang atau bukan pisang berdasarkan proses pelatihan (learning) sebelumnya.



## [[01. Supervised Learning]]

#### Tahapan 1

Supervised learning dikenal juga dengan istilah pembelajaran terbimbing/ terselia. Misal, peneliti memiliki koleksi gambar manusia dan gorila yang telah diberikan label dengan benar. Komputer kemudian diberikan proses pembelajaran dari koleksi gambar dengan label yang benar tersebut, ini adalah tahap pertama. Di mana komputer akan menemukan pola dan kesamaan dari gambar-gambar tersebut.

#### Tahapan 2

Pada tahap kedua, kita akan memberikan gambar yang benar-benar baru, komputer kemudian akan mencoba mengenali gambar tersebut, apakah akan diklasifikasikan sebagai manusia atau gorila. Ini adalah proses pengujian. Hasilya dapat akurat 100% atau bahkan, error 100% tergantung pada proses pembelajaran yang dilakukan.

Conto penerapannya adalah pada surat elektronik (email). Untuk dapat membedakan email yang masuk sebagai spam atau bukan, maka komputer akan diberikan proses pembelajaran berdasarkan kepada email yang telah diberikan label spam dan bukan spam. 

Berdasarkan pada proses pembelajaran tersebut, maka jika ada email baru masuk akan diuji, apakah memiliki pola dan kesamaan dari data latih, maka komputer akan memberikan label spam atau bukan spam. Aplikasi lainnya adalah pada pengenalan teks, wajah, tulisan tangan, klasifikasi dokumen, dan sebagainya.


![[Screenshot 2024-10-27 at 12.07.45.png]]


Gambar 16,2 memvisualisasikan distribusi spasial dari data latih yang akan digunakan dalam proses klasifikasi tutupan dan penggunaan lahan menggunakan data citra satelit PlanetScope. 


![[Screenshot 2024-10-27 at 12.08.22.png]]

Sementara Gambar 16.3 memvisualisasikan hasil klasifikasi tutupan dan penggunaan lahan meng gunakan metode supervised learning.



## [[02. Unsupervised Learning]]

jika pada supervised learning peneliti harus memiliki label yang benar terlebih dahulu, maka sebaliknya pada unsupervised learning tidak ada peran peneliti sebagai mediator dalam memberikan label yang benar. Unsupervised dikenal juga dengan istilah tidak terbimbing/terselia, artinya tidak ada proses "bimbingan" atau belajar terlebih dahulu berdasarkan data latih.

Pada unsupervised learning peneliti mencoba menemukan apakah ter-dapat pola yang khusus dalam data. Peneliti tidak memiliki label, namun akan memberikan label berdasarkan pada pola yang terbentuk secara alami dari data yang diolah. Komputer akan belajar secara mandiri menemukan dan mengidentifikasi pola tanpa ada arahan dari peneliti.

#### Unsupervised Learning ≠ Artificial Intelligence

Terdengar seperti kecerdasan buatan, di mana komputer dapat belajar tanpa intervensi manusia, namun kurang tepat. Pada unsupervised learning, peneliti tidak memiliki harapan luaran seperti apa, seperti pada proses regresi, dimana peneliti memiliki harapan terdapat hubungan linear. 

Pada unsupervised learning peneliti fokus pada data input dan mencoba menemukan pola dan hubungannya, maka mungkin saja pada hasil akhirnya tidak terdapat pola dan hubungan sama sekali.

Contoh aplikasi dari unsupervised learning adalah rekomendasi artikel berita, misal pada Google News menggunakan metode ini untuk memberikan rekomendasi berita berdasarkan berita yang sama atau mirip. Pada bidang kesehatan misalnya klasifikasi citra radiologi dan patologi untuk proses diagnosis yang cepat dan akurat. Atau rekomendasi kepada pelanggan seperti pada halaman Amazon atau jurnal ilmiah Springer, dimana komputer belajar berdasarkan pada tren data yang digunakan oleh pengguna.




## [[03. Semi-Supervised Learning]]

Pada supervised learning peneliti harus memiliki data dengan label yang benar terlebih dahulu atas seluruh data, sebaliknya pada unsupervised learning peneliti tidak memiliki label sama sekali. Sementara itu pada semi-supervised Learning peneliti hanya memiliki sebagian saja dari data yang dimiliki yang telah memiliki label yang benar, sementara sebagian lainnya tidak.

#### Tujuan Semi-Supervised Learning

Tujuan dari semi-supervised learning adalah 
1) untuk memprediksi label pada data uji di masa depan
   Tujuan yang pertama dikenal juga dengan istilah inductive semi-supervised learning,

2) memprediksi label pada data latih yang tidak berlabel dalam sampel pelatihan.
   Sementara yang kedua dikenal juga dengan istilah transductive learning.



## [[04. Reinforcement Learning]]

Pada algoritme sebelumnya hanya fokus pada pengolahan data dan bagai-mana memperoleh pengetahuan darinya, atau dengan kata lain peneliti hanya fokus pada kejadian di masa lalu atau di masa kini.

Data science data tidak hanya fokus pada data masa kini dan masa lalu, namun juga pada data di waktu nyata (real time) sehingga kita membutuhkan sebuah metode lain yang dapat mempelajari apa yang terjadi di waktu nyata guna men-dapatkan "hadiah" (reward) semaksimal mugkin.

#### Reinforcement Learning

Algoritme RI adalah tentang proses "pemaksaan" (reinforcing) perilaku yang benar seiring dengan berlalunya waktu. Jika prediksi benar, maka akan diberikan reward, dan akan diberikan hukuman jika salah. Contoh sederhana dari penerapan algoritme RL adalah iklan online berdasarkan klik yang dilakukan oleh pengguna, atau dikenal juga dengan istilah click-through rates (CTR). Hal ini banyak diterapkan pada market place online seperti Tokopedia, Bukalapak, dan sebagainya.

Jika kita ingin memaksimalkan profit, maka mengapa tidak melakukan penyesuaian saat iklan sedang dijalankan? Dengan kata lain, jangan me-nunggu seluruh anggaran iklan habis sebelum mengetahui mana yang ber-kinerja terbaik. Sebagai gantinya, cari tahu iklan mana yang berkinerja terbaik saat sedang dijalankan. Lakukan penyesuaian sejak dini agar nantinya hanya iklan dengan kinerja terbaik yang akan ditampilkan kepada pengguna.


#### Perbedaan

Perhatikan bahwa definisi algoritme RL tidak sepenuhnya sesuai dengan supervised learning atau unsupervised learning. Ingat bahwa super-vised learning adalah tentang proses belajar melalui pengawasan dan pelatihan oleh peneliti. Sementara itu, unsupervised learning berusaha mengungkapkan atau menemukan pola, kesamaan, atau perbedaan, dari data yang tidak terstruktur (tanpa pengawasan dan tanpa label).

Perbedaan utama dari algoritme RL adalah dalam memaksimalkan hadiah (reward) yang ditetapkan, belajar dari interaksi pengguna, dan kemampuan untuk memperbarui dirinya sendiri secara real time.



## [[Semester 1/Pengantar Sains Data STDA4101/Modul 16/05. Menentukan Metode yang Tepat|05. Menentukan Metode yang Tepat]]

Peneliti tidak perlu melakukan dikotomis dalam menentukan metode yang tepat untuk proses klasifikasi. Apakah menggunakan algoritme supervised learning saja atau unsupervised learning saja, atau bahkan reinforcement learning. Peneliti perlu menentukan hasil atau luaran akhir yang seperti apa yang diharapkan.

> Apakah peneliti memiliki label yang benar dan mengharapkan klasifikasi nilai variabel terikat berdasarkan variabel prediktornya (data latih)? Maka peneliti dapat menggunakan algoritme supervised learning.

> Apakah peneliti tidak memiliki label, dan berharap menemukan pola atau perbedaan atau persamaan antara setiap kelompok dalam data? Maka peneliti dapat menggunakan algoritme unsupervised learning.

>Apakah peneliti memiliki sebagian label yang benar dan berharap memperoleh label dari data yang tidak lengkap? Maka peneliti dapat menggunakan algoritme semi-supervised learning.

> Apakah peneliti berharap memperoleh klasifikasi yang akurat dalam waktu nyata? Maka peneliti dapat menggunakan algoritme RI.

> Jika akan melakukan proses eksploitasi dari data maka gunakan algoritme RL.

> Selanjutnya, algoritme supervised learning dan unsupervised learning dapat digunakan untuk melakukan proses pembelajaran pasif dari data historis (bukan waktu nyata) untuk melakukan proses pemetaan, klasifikasi, kelas/kategori tertentu.

Pada akhirnya peneliti hanya perlu fokus pada dua hal, apakah akan melakukan klasifikasi atas sesuatu (berdasarkan label yang dimiliki) atau melakukan eksplorasi atas data (kelas/kategorisasi, menemukan pola, per-samaan, atau perbedaan) karena tidak memiliki label sebelumnya.


![[Screenshot 2024-10-27 at 12.16.45.png]]

Perbedaan antara konsep algoritme supervised learning, unsupervised learning, semi-supervised learning, dan reinforcement learning diilustrasikan oleh Gambar 16.4.




## [[Semester 1/Pengantar Sains Data STDA4101/Modul 16/06. Kelebihan dan Kekurangan|06. Kelebihan dan Kekurangan]]

Algoritme klasifikasi memberikan banyak manfaat bagi peneliti data science, baik untuk kegiatan penelitian (non profit oriented) ataupun analisis bisnis (profit oriented). Berbagai Library yang siap pakai juga banyak tersedia untuk melakukan proses klasifikasi.

Selanjutnya, kini juga tersedia proses klasifikasi berbasis cloud, di mana performa komputer pengguna sudah tidak menjadi halangan karena semua berjalan di dalam cloud milik penyedia jasa, seperti Google Cloud dan AWS secara online.

Layanan klasifikasi berbasis cloud untuk data citra satelit berukuran sangat besar kini sudah tersedia. Misal, Google Earth Engine (GEE) yang dapat diakses melalui URL https://code.earthengine.google.com/maupun Microsoft Planetary Computer yang dapat diakses melalui URL https:/ planetarycomputer.microsoft.com/.

#### Tantangan

Namun selain beberapa kelebihan tersebut, beberapa tantangan hadir dalam proses klasifikasi. Beberapa tantangan tersebut adalah seperti berikut.

1. ﻿﻿﻿Membutuhkan label yang benar, dan ketersediaannya tidak selalu ter-jamin ada.
2. ﻿﻿﻿Membutuhkan performa komputer yang mumpuni jika dilakukan secara offline karena volume dari data latih yang besar.
3. ﻿﻿﻿Membutuhkan waktu komputasi yang tidak sebentar.
4. ﻿﻿﻿Terdapat risiko hasil klasifikasi yang tidak akurat.
5. Membutuhkan bantuan interpretasi manusia untuk memvalidasi hasil akhir.
6. ﻿﻿﻿Kurangnya transparansi terkait proses pengelompokan data (black box issue).
7. ﻿﻿﻿Membutuhkan biaya berlangganan jika proses klasifikasi dilakukan secara online berbasis cloud.
