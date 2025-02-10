---
tags:
  - sains_data
  - materi_20_PSD
---
Deep learning (DL) adalah metode pembelajaran mesin yang berdasarkan kepada algoritme ANN/JST. Algoritme DL berbasis kepada jaringan saraf yang berjumlah sangat besar, dengan jumlah lapisan hidden layer yang banyak, dan data latih yang juga sangat besar, untuk menghasilkan performa akurasi yang jauh lebih baik.

Algoritme DL sesuai untuk digunakan dengan jenis kasus non-linear. Input pada layer setelahnya adalah output dari layer sebelumnya. Begitu pun halnya dengan fitur pada tingkat yang lebih tinggi berasal dari fitur pada tingkat yang lebih rendah. Secara umum, parameter pada algoritme

DL tidak jauh berbeda dengan ANN/JST, seperti jumlah hidden layer, epochs (iterasi), learning rate, dan uji performa.

![[Pasted image 20241124145524.png]]

Namun, pada algoritme DL penentuan fitur atau proses labelling tidak lagi membutuhkan keterlibatan manusia atau peneliti sehingga proses ekstraksi fitur sudah tidak perlu lagi dilakukan secara manual. Misal, komputer akan mengenali karakteristik yang unik dari pisang dan membuat klasifikasi yang akurat. Komputer akan secara mandiri dan dinamis melakukan proses estraksi dan klasifikasi, peneliti hanya perlu memberikan data mentah berupa gambar pisang sebagai data masukan (input), selebihnya model akan berjalan sendiri dan melakukan perbaikan hingga menghasilkan klasifikasi yang tepat apakah pisang atau bukan pisang (Gambar 20.1).



## [[01. Jenis DL]]
Terdapat literatur terdapat berbagai jenis algoritme DL, yaitu (1) Fully Connected Networks (FC), (2), Convolutional Neural Networks (CNN), (3) Recurrent Neural Networks (RNN), dan (4) Generative Adversarial Networks (GAN). Hal ini sebagaimana dijelaskan berikut ini.

#### Fully Connected Networks (FC)

Fully Connected Networks (FC), adalah jenis algoritme DL yang paling umum dan paling sering digunakan untuk mengatasi berbagai kasus non-linear. Pada algoritme DL dengan jenis FC semua node (neuron) sebelumnya pada layer ke-n akan saling terhubung dengan neuron (node) setelahnya pada layer ke-n+1 secara keseluruhan begitu sete-rusnya sampai pada lapisan (layer) output. Algoritme DL dengan jenis FC biasa digunakan untuk jenis data tabular.

![[Pasted image 20241124145628.png]]

Seperti disajikan oleh Gambar 20.2, dapat dilihat bahwa terdapat sebuah input layer dengan tiga buah hidden layer dan sebuah output layer. Di mana setiap neuron (node) pada setiap layer semuanya saling terhubung secara menyeluruh. Algoritme DL dengan jenis FC dikenal sangat kompleks dan dengan neuron (node) yang saling terhubung secara menyeluruh akan menyebabkan proses komputasi yang tidak efektif (computationally expensive). Untuk menangani hal ini, maka dikenalkanlah model algoritme DL yang kedua, yaitu Convolutional Neural Networks (CNN).

#### Convolutional Neural Networks (CNN)

merupakan jenis algoritme DI yang didesain khusus untuk mengolah data gambar (citra). Aplikasinya seperti melakukan klasifikasi citra satelit, hasil pindai X-rays, citra tata surya, dan sebagainya. Algoritme CNN dianggap sebagai salah satu jenis algoritme DL yang dapat digunakan sebagai alternatif metode karena proses komputasi yang lebih baik daripada algoritme DL dengan jenis FC.

![[Pasted image 20241124145709.png]]

Algoritme DL dengan jenis CNN ini memiliki kelebihan lainnya, yaitu kemampuan belajar berdasarkan pada ekstraksi fitur yang tidak perlu dilakukan secara manual, terutama pada tingkat yang rendah. Namun, hal ini menyebabkan peneliti sulit menjelaskan sebenarnya apa telah dipelajari oleh sistem. Algoritme DL dengan jenis CNN ini memiliki arsitektur jaringan yang spesifik, yaitu memiliki dua lapisan utama, (1) convolution dan (2) pooling. Di mana neuron (node) pada lapisan ke-n akan berfungsi sebagai input pada lapisan ke-n+1, namun tidak terhubung secara keseluruhan seperti pada jenis FC. Lapisan (layer) ke-n+1 hanya terhubung pada sebagian potongan saja dari lapisan ke-n sehingga dikenal juga dengan istilah receptive field (Gambar 20.3).

#### Recurrent Neural Networks (RNN)

Recurrent Neural Networks (RNN) memiliki karakteristik yang berbeda dibandingkan dengan dua jenis algoritme DL sebelumnya. Algoritme DL jenis RNN ini khusus didesain untuk mengolah data yang berurutan (sequential). Algoritme DL jenis RNN ini banyak diterapkan pada kasus analisis data berbasis bahasa alami atau Natural Language Processing (NLP). Perhatikan Gambar 20.4, 

![[Pasted image 20241124145828.png]]

ilustrasi tersebut memperlihatkan adanya proses yang berulang pada hidden layer. Algoritme RNN sesuai digunakan untuk analisis yang berbasis suatu konteks atau latar belakang sebelumnya, misal untuk mengetahui makna suatu kata atau kalimat hanya dapat dianalisis dengan mengetahui kata atau kalimat sebelumnya.


#### Generative Adversarial Networks (GAN)

Generative Adversarial Networks (GAN) adalah algoritme DL yang terdiri atas dua komponen utama, yaitu (1) generator dan (2) discri-minator (Gambar 20.5). Komponen generator berfungsi untuk meng. hasilkan input yang akan diberikan ke discriminator. Sementara discri-minator berfungsi untuk membedakan mana sampel yang benar dan salah yang telah dibuat oleh generator pada tahap sebelumnya. Kedua komponen ini saling berhadapan secara konstan. Di mana generator belajar untuk membuat sampel yang benar untuk meyakinkan discri-minator, sementara discriminator terus bekerja untuk membedakan sampel yang terbaik yang diberikan oleh generator sehingga meng-hasilkan performa akurasi yang lebih baik.

Dengan kata lain, pada algoritme DL jenis GAN, komponen generator dan discriminator saling berkompetisi untuk menghasilkan data yang terbaik. Penerapan algoritme DL jenis GAN seperti pada klasifikasi citra satelit resolusi sangat tinggi tanpa label, menghasilkan gambar tiga dimensi, menghasilkan musik, menghasilkan artikel berita, simulasi sains pada bidang astrofisika (simulasi galaksi), simulasi pertumbuhan kota, simulasi model iklim dan cuaca, dan sebagainya yang menggunakan data berukuran sangat besar.

![[Pasted image 20241124145903.png]]





## [[02. Hubungan Antara AI dan DL]]

AI atau kecerdasan buatan adalah sebuah teknik yang bertujuan untuk membuat komputer meniru kemampuan manusia. Termasuk ke dalam AI adalah pembelajaran mesin (machine learning), natural language processing (NLP), sintesis bahasa, computer vision, robotika, simulasi dan optimasi.

Sementara machine learning (ML) adalah bagian dari AI yang bertujuan untuk membuat komputer memiliki kemampuan belajar dari pengalaman sebelumnya dan meningkatkan kemampuannya dalam bekerja membantu memberikan kemudahan bagi manusia untuk melakukan klasifikasi dan prediksi dari data yang berukuran sangat besar. Dalam hal ini yang termasuk ke dalam ML di antaranya adalah Support Vector Machines (SVM), pohon keputusan, k-means clustering, regresi, prediksi, neural networks, dan sebagainya.

Artificial Neural Network (ANN) atau JST adalah bagian dari ML, yang terinspirasi dari cara otak makhluk hidup bekerja. ANN/JST biasanya terdiri atas gabungan dari beberapa lapisan, dimana terdapat lapisan input, hidden, dan output. Setiap lapisan memiliki neuron (node) yang dapat saling terhubung secara penuh maupun sebagian saja. Karena neuron (node) ini dibuat dan ditentukan jumlahnya oleh peneliti, maka dikenal juga dengan istilah artifical neuron atau saraf tiruan.

Sementara Deep Learning (DL) adalah bagian dari NN/IST yang terdiri atas banyak sekali lapisan. Beberapa arsitektur dari algoritme DI seperti, convolutional neural networks (CNNs), recurrent neural networks (RNNs), generative adversarial networks (GAN), dan lain sebagainya. Rangkuman terkait hubungan Al dengan DL disajikan oleh Gambar 20.6.

![[Pasted image 20241124150033.png]]






## [[03. Aplikasi]]

Algoritme DI telah banyak diterapkan pada berbagai domain keilmuan dan kasus. Misal, pada kasus klasifikasi citra dan video satelit dengan reso-lusi sangat tinggi, maupun data citra hypersepctral, yaitu data citra yang memiliki ratusan panjang gelombang. Sementara pada domain keilmuan seperti biologi, ilmu kesehatan, kedokteran, fisika, dan astronomi, algoritme DL juga telah banyak dimanfaatkan.

Pada aplikasi yang lebih spesifik seperti pengenalan dan pengolahan teks, bahasa, dan dokumen, algoritme DI digunakan untuk memahami pola, sentimen, dan lain sebagainya dari berbagai macam bahasa di dunia. Selain itu, juga algoritme DI kini dimanfaatkan pada domain keamanan, seperti pengenalan wajah, jenis kelamin, usia, serta keamanan siber seperti analisis anomali, serangan siber, dan sebagainya.

Pada domain bisnis, algoritme DL dapat digunakan untuk analisis fraud pada transaksi kartu kredit, analisis tren pasar seperti fluktuasi harga saham, baik untuk pemantauan secara berkala maupun prediksi. Sementara itu untuk domain lain seperti robotika dan permainan, algoritme DI juga mulai banyak berperan penting. Misal pada kasus navigasi kendaraan tampa awak seperti pada pesawat udara nirawak (PUNA), mobil, motor, bahkan kapal selam.




## [[04. Kelebihan dan Kekurangan]]

Algoritme DL merupakan bagian dari machine learning yang bertujuan untuk melakukan klasifikasi maupun prediksi atas suatu data. Algoritme ini berbasis jaringan saraf tiruan yang terdiri atas berlapis-lapis layar, dengan berbagai fungsi yang berjalan di dalamnya. Algoritme DL saat ini semakin populer karena beberapa hal, seperti: (1) Semakin aplikatif karena kehadiran data latih yang semakin banyak dan bervariasi; (2) Peningkatan dari infrastruktur komputer yang semakin besar dan cepat; (3) Akurasi yang semakin baik seiring dengan berjalannya waktu; (4) Dapat dilakukan dengan berbagai cara, baik supervised, unsupervised, semi-supervised, mau-pun reinforcement learning; dan (5) Ketersediaan jasa layanan berbasis cloud yang dapat diakses dengan mudah oleh siapa pun.

Namun, dibalik kelebihan tersebut, algoritme DL juga memiliki keku-rangan. Seperti tidak adanya panduan atau standar untuk memilih parameter yang tepat, sehingga kemunculan uncertainty adalah suatu keniscayaan pada penerapan algoritme DI. Proses tuning pada parameter biasanya dila-kukan berulang-ulang dan disesuaikan dengan data atau domain keilmuan Sehingga tidak akan diperoleh sebuah model yang sesuai untuk semua kasus, Misal, sebuah model prediksi bencana banjir di suatu wilayah tidak akan bisa diterapkan untuk memprediksi banjir di wilayah lainnya meskipun menggunakan variabel yang sama seperti curah hujan, keting-gian, kelerengan, pola penggunaan dan tutupan lahan, dan sebagainya.

Kelemahan lainnya adalah memerlukan data latih dalam jumlah yang besar untuk menghasilkan akurasi yang baik, sementara proses meng-hasilkan data latih membutuhkan waktu dan biaya yang tidak sedikit.

Sehingga sering kali proses pembangunan data latih justru bisa jadi lebih lama dari proses pelatihannya. Pemilihan arsitektur dari algoritme DL yang akan digunakan pada penelitian menjadi sangat penting karena ini akan terkait dengan proses pelatihan yang dapat mencapai waktu berminggu-minggu, bahkan hingga berbulan-bulan. Sementara dengan waktu yang lama tersebut belum tentu memberikan hasil dengan akurasi yang tinggi.

Terakhir, hal yang paling sering tidak dihiraukan oleh peneliti adalah konsumsi energi. Proses pelatihan algoritme DL membutuhkan energi yang tidak sedikit dan menghasilkan emisi karbon yang sangat tinggi. Misal pada proses pelatihan algoritme DL pada kasus NLP, dapat menghasilkan emisi karbon yang lima kali lebih tinggi dari emisi kendaraan (Strubell, Ganesh, dan McCallum, 2019).

Perhatikan Gambar 20.7 yang memvisualisasikan perbandingan emisi karbon penerbangan pulang-pergi oleh seorang penumpang, emisi karbon kehidupan manusia rata-rata selama satu tahun, emisi karbon orang Amerika Serikat rata-rata dalam setahun, konsumsi kendaraan, dan proses pelatihan menggunakan algoritme DL. Emisi yang dihasilkan oleh proses pelatihan algoritme DL mencapai hampir 285.000 kg setara dengan emisi CO, ke atmosfer. Sehingga, penerapan algoritme DL dianggap sebagai tidak ramah lingkungan.

![[Pasted image 20241124150205.png]]

