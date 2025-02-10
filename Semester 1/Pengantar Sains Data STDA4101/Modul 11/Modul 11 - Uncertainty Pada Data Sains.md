---
tags:
  - sains_data
  - materi_11_PSD
---
Uncertainty atau ketidakpastian adalah suatu ukuran yang digunakan oleh peneliti untuk memahami perbedaan antara informasi yang diperoleh dari data yang diolah dengan fenomena yang sedang dikaji atau dengan kata lain sejauh mana perbedaan antara hasil pengolahan data dengan keadaan yang sebenarnya terjadi di dunia nyata.

Ketidakpastian ini hadir sebagai konsekuensi dari kompleksitas fenomena nyata yang terjadi di permukaan bumi sehingga tidak mungkin merepresentasikan dunia nyata ke dalam dunia digital secara utuh 100%. Ketidak-pastian itu tidak bisa dihindari dalam sains data namun bisa diminimalisir.

![[Screenshot 2024-10-26 at 20.32.22.png]]

Tidak ada yang benar-benar sempurna dalam proses pengolahan data menjadi informasi, semuanya memiliki kekurangan atau imperfection.

Imperfection ini dapat muncul dari beberapa hal, misal

1. kekeliruan dalam memahanifenomena di dunia nyata,
2. kesalahan dalam memilih, pengukuran/perhitungan dan cara mempresentasikannya,
3. kesalahan dalam kuantifikasi dan proses analisis.



## [[01. Kekeliruan Dalam Memahami Dunia Nyata]]

Hujan merupakan fenomena dunia nyata yang sangat kompleks. Hujan adalah salah satu fase dalam siklus hidrologi yang terdiri atas beberapa rangkaian fase. Mulai dari proses penguapan, transpirasi dan evapotranspirasi, kondensasi, hingga menjadi presipitasi. Semuanya tidak dapat dipisahkan satu dengan yang lainnya.

Curah hujan kemudian dipengaruhi oleh suhu, tekanan udara, intensitas penyinaran matahari, ketinggian, pola penggunaan dan tutupan lahan, dan variabel lainnya. Kekeliruan dalam memahami hujan akan menye-babkan munculnya kesalahan dalam pengolahan data dan analisisnya.

Memprediksi curah hujan akan sangat berbeda dengan memprediksi harga saham atau emas. Variabel internal dan eksternal dari setiap fenomena harus dipahami dengan sangat baik. Caranya adalah dengan banyak mengkaji literatur terkait atau diskusi dengan para pakar di bidangnya.



## [[02. Kesalahan dalam Memilih, Pengukuran atau Perhitungan dan Cara Mempresentasikannya]]

Masih tentang hujan, fenomena ini adalah fenomena alam yang dapar diukur dengan berbagai cara, baik secara langsung maupun tidak langsung. Mulai dari sensor yang sederhana yang dipasang di lahan terbuka hinga. sensor yang super canggih yang ditanam di satelit yang mengorbit di angkasa Hujan memilki satuan yaitu milimeter (mm), merupakan satuan yang digunakan untuk mengukr tinggi air dalam sebuah wadah berukuran luas satu meter persegi.

Data yang dapat diukur dan memiliki satuan (unit) tertentu merupakan data kontinu dan dapat direpresentasikan menggunakan grafik diagram garis

![[Screenshot 2024-10-26 at 20.36.34.png]]

Sementara data yang dapat dihitung dan tidak nemiliki satuan (unit) tertentu merupakan data diskret dan dapat direpresentasikan menggunakan grafik diagram batang. Setiap grafik harus memiliki informasi legenda baik di sumbu x maupun sumbu y untuk memberikan informasi kepada pemangku kepentingan.

Data curah hujan time-series hanya tepat divisualisasikan menggu-nakan grafik diagram garis, sementara data harga emas lebih tepat divisualisasikan dengan grafik diagram batang.

#### Imperfection

Kesalahan dalam pengukuran/perhitungan akan menyebabkan mun-culnya imperfection yang dapat menjadi masalah lebih lanjut jika di analisis. Contohnya adalah prediksi curah hujan menggunakan data curah hujan di stasiun BMKG Karangploso, Kota Batu, Jawa Timur untuk memprediksi curah hujan di taman nasional Bromo-Tengger-Semeru. Atau memprediksi harga emas hanya dengan menggunakan harga historis pada periode sebelumnya, atau memprediksi harga saham hanya dengan menggunakan data harga sama time-series pada tahun-tahun sebelumya


## [[03. Kesalahan dalam Kuantifikasi dan Proses Analisis]]

Kesalahan kuantifikasi seperti mengukur jumlah penduduk dan kepadatan penduduk. Jumlah penduduk adalah data diskret karena merupakan hasil perhitungan dan tidak memiliki satuan atau unit. Sementara kepadatan penduduk adalah data kontinu karena merupakan hasil pengukuran dan memiliki satuan atau unit, yaitu orang/km^2

Penentuan jenis, sifat, skala, distribusi, dan karakteristik data sangat penting agar peneliti tidak mela-kukan kesalahan kuantifikasi dan proses analisis.

Setiap data yang diperoleh selama proses akuisisi data tentunya akan memengaruhi keputusan akhir yang diambil, informasi yang berhasil diolah tidak mungkin 100% identik dengan fenomena di dunia nyata, maka yang dapat dilakukan oleh peneliti data science adalah mengukur sejauh mana perbedaan antara model yang dihasilkan dengan fenomena yang sebenarnya terjadi di lapangan. 

Beberapa metode pengukuran tersebut dijelaskan pada bagian selanjutnya, yaitu "mengukur uncertainty dari data".



## [[04. Kerangka Kerja Memvisualisasikan Uncertainty]]

Lapinski (2009) mengajukan 11 langkah strategis untuk memvisualisasikan uncertainty. 11 langkah tersebut dikenal dengan istilah Uncertainty Visualization Development Strategy (UVDS). UVDS memiliki 11 langkah utama yang terdiri atas:

1. ﻿﻿﻿mengidentifikasi apa peran dari visualisasi uncertainty;
2. ﻿﻿﻿memahami data apa saja yang diperlukan;  
3. memahami mengapa ketidakpastian perlu divisualisasikan, siapa peng gunanya, dan bagaimana visualisasi ketidakpastian bisa membantu pengguna;
4. memutuskan ketidakpastian yang akan divisualisasikan;
5. memutuskan definisi ketidakpastian;
6. menentukan penyebab spesifik dari ketidakpastian;
7. menentukan kategori kausal dari ketidakpastian;
8. menentukan persyaratan kebutuhan dari visualisasi;
9. menghiting, menetapkan, atau mengekstraksi ketidakpastian:
10. mencoba teknik Visualisasi ketidakpastian yang berbeda; dan
11. mendapatkan opini dan kritik dari pengguna

#### Langkah 1

Pada langkah pertama peneliti perlu mengidentifikasi apa peran dari visualisasi yang akan dibuat. Sebuah kalimat pernyataan permasalahan dan pernyataan misi perlu dibangun. Misal, "ketidakpastian muncul pada Iokasi mana saja yang rawan terdampak kebakaran hutan " sebagai kalimat pernyataan permasalahan dan *perlukan peta yang akurat untuk mem- visualisasikan lokasi mana saja yang rawan terdampak kebakaran hutan?

#### Langkah 2

Langkah kedua, adalah memahami data apa saja yang diperlukan untuk membuat visualisasi lokasi yang rawan terdampak kebakaran hutan. Maka peneliti perlu menentukan jenis data yang dibutuhkan, apakah data spasial, non-spasial, atau membutuhkan keduanya. Sumber data, unit, presisi, statis atau dinamis, format data, dan sebagainya perlu diperhatikan.

#### Langkah 3

Selanjutnya, pada lengkah ketiga peneliti perlu memahami mengapa ketidakpastian perlu divisualisasikan, siapa penggunanya, dan bagaimana visualisasi ketidakpastian bisa membantu pengguna. Misal pada kasus kebakaran hutan, pengguna adalah semua pemangku kepentingan seperti masyarakat awam, Badan Penanggulangan Bencana Daerah (BPBD), Lem-baga Swadaya Masyarakat (LSM), aparat berwenang, dan sebagainya. Hal ini menandakan bahwa rentang pendidikan dan pengetahuan pengguna sangat luas. Visualisasi lokasi mana saja yang rawan terdampak kebakaran hutan harus mudah dipahami oleh semua pihak, maka perlu ada prioitas keselamatan dibandingkan data-data statistik.

#### Langkah 4 - 7

Pada langkah ke-4 hingga ke-7 adalah tahapan yang harus berurutan. Artinya peneliti dapat memulai dari langkah yang mana saja untuk membuat visualisasi lokast mana saja yang rawan terdampak kebakaran hutan, Pada tahap ini peneliti prlu menentukan variabel seperti waktu, posisi, identitas atau kelas kebakaran hutan

#### Langkah 8

Langkah kedelapan adalah menentukan persyaratan kebutuhan dari visualisasi, Peneliti perlu memberikan informasi yang cukup baik untuk memberikan edukasi dan mediasi dalam proses pengambilan keputusan. 

Visualisasi harus menunjukkan terdapat permasalahan, namun tidak boleh fokus pada detail dari uncertainty. Warna dan simbol harus jelas dan me-miliki sifat self-expalanatory, atau mampu memberikan interpretasi yang konsisten antara satu pengguna dengan pengguna lainnya tanpa bantuan teks. Representasi geometri harus unik dan mudah dipahami secara instan tanpa diperlukan penjelasan tambahan. Ukuran dari simbol yang diguna-kan juga harus sesuai dengan skala yang dipakai.

#### Langkah 9

Langkah kesembilan adalah melakukan kuantifikasi dari uncertainty, seperti menghitung ketersediaan data, melakukan transformasi satuan jika diperlukan (misal dari km persegi ke hektare), membuat kelas-kelas tingkat kerawanan terdampak kebaran hutan, menentukan kategori warna yang sesuai, dan sebagainya.

#### Langkah 10

Sementara itu, pada tahap kesepuluh peneliti bisa menggunakan ber bagai macam alternatif cara, teknik, metode yang berbeda untuk men-dapatkan visualisasi yang terbaik dan paling sesuai dengan kebutuhan.

#### Langkah 11

Tahap terakhir adalah mendapatkan opini, kritik, dan umpan balik dari semua pemangku kepentingan. Semua saran tersebut kemudian dipilih mana yang sesuai untuk kemudian digunakan dalam memperbaiki visualisasi yang telah dibuat. Bisa dengan menggunakan instrumen kuesioner survei dengan beberapa pertanyaan yang disesuaikan untuk proses evaluasi. Skala yang digunakan bisa menggunakan skala Likert (1-5) dengan level 1 adalah sangat tidak setuju dan level 5 adalah sangat setuju. Setiap instrumen dapat dibedakan klasifikasinya, misal delapan pertanyaan untuk menilai kemu-dahan penggunaan, kemudian lima pertanyaan untuk menilai kesulitan yang dialami pengguna, dan sepuluh pertanyaan lain untuk menilai kua-litas visualisasi yang digunakan.


![[Screenshot 2024-10-26 at 20.49.43.png]]

Gambar 11.3 memvisualisasikan ketidakpastian sebuah lokasi yang rawan terdampak kebakaran hutan dengan pendekatan side-by-side. Lokasi yang rawan direpresentasikan dengan titik, dan area yang rawan terbakar divisualisasikan dengan geometri area (poligon). Penggunaan kombinasi warna, tingkat kekeruhan, transparansi, dan grid digunakan untuk men-dapatkan impresi dan interpretasi yang tepat dari pengguna.


## [[05. Kategori Uncertainty]]

Menurut Chung and Wark (2016) pada literatur dapat ditemukan beberapa kategori uncertainty, seperti yang disajikan oleh tabel berikut.

![[Screenshot 2024-10-26 at 20.51.17.png]]

Setiap kategori uncertainty ini dapat berlaku pada tipe informasi yang berbeda. Sehingga tingkat uncertainty dapat dihitung dan direpresentasikan dalam berbagai cara, baik secara kuantitatif maupun kualitatif.

Secara kuantitatif misalnya dengan menghitung nilai RMSE. Sementara secara kualitatif misalnya dengan cara visual, membandingkan hasil model visual dengan tampilan yang sebenarnya di dunia nyata.



