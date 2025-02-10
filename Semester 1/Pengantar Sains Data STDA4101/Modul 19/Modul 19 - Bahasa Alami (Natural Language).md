---
tags:
  - sains_data
  - materi_19_PSD
---
Seperti yang sudah disinggung pada bab sebelumnya, manusia memiliki kemampuan yang jauh lebih baik daripada komputer dalam mengenali dan memahami kata dan kalimat. Namun, apakah kita dapat membuat komputer juga memiliki kemampuan yang sama? Pertanyaan ini kemudian menjadi salah satu motivasi peneliti untuk mengembangkan kemampuan komputer dalam memahami suatu komunikasi, memahami arti dari suatu kata atau kalimat, dan membuat suatu kesimpulan berbasis pada kata dan kalimat tersebut.

Berdasarkan pada motivasi tersebut kemudian muncullah metode

Natural Language Processing (NLP). NLP adalah satu catu cabang kecerdasan buatan yang fokus pada proses memahami dan menginterpretasi bahasa manusia. NLP juga meliputi proses memahami dan menginterpretasi teks dan percakapan.

Apakah Anda pernah menggunakan layanan pencarian Google meng. gunakan bantuan fitur suara? Atau pernahkah Anda bermain dengan fitur siri pada perangkat cerdas iPhone? Bagaimana dengan layanan Google Translate (Translate by voice) dan Google Documents menggunakan fitur suara (Gambar 19)?

![[Screenshot 2024-11-24 at 14.50.38.png]]

Semua layanan tersebut memanfaatkan bantuan algoritme NLP. Kini, nilai pasar dari layanan berbasis NLP dapat mencapai miliar, bahkan trilunan rupiah. Hal ini dikarenakan layanan NLP banyak digunakan dalam layanan pelanggan, asisten virtual pribadi, layanan kesehatan, layanan keuangan, dan sebagainya.

NLP juga banyak dimanfaatkan untuk memahami konten dan sentimen dari data media sosial seperti Twitter, komentar pada platform You Tube, ulasan pengguna di Android Palystore, maupun ulasan pelanggan di marketplace seperti Tokopedia dan Bukalapak, Analisis seperti ini mungkin dilakukan karena ketersediaan data yang sangat banyak dari aktivitas dalam jaringan (online). Perlu dipahami bahwa analisis data akan memberikan hasil yang semakin baik dan berkualitas jika data latih yang digunakan juga semakin banyak dan berkualitas.



## 01. Analisis Kata dan Sentimen

Analisis kata dan sentimen merupakan salah satu aplikasi dari algoritme

NLP. Karena dengan memanfaatkan ulasan dan komentar dari pelanggan kita dapat memahami bagaimana penerimaan layanan jasa atau produk tertentu. Jika kita memiliki beberapa atau puluhan ulasan dan komentar, maka kita dapat dengan mudah memahaminya tanpa memerlukan ban-tuan komputer. Namun bagaimana jika jumlahnya mencapai ribuan atau, bahkan ratusan ribu ulasan dan komentar?

Implementasi NLP akan menjadi jawabannya. Karena dengan me-manfaatkan NLP kita akan dapat dengan mudah mengetahui hasilnya, apakah ulasan dan komentar tersebut dominan negatif, positif, atau netral.

Kemudian, kita dapat mengulangi analisis yang sama untuk periode yang berbeda. Apakah ditemukan ulasan dan komentar yang berubah menjadi lebih baik setelah sebelumnya negatif, atau apakah tidak terjadi perubahan apa pun meskipun perbaikan layanan jasa atau produk telah dilakukan.



## 02. Jenis NLP

Berdasarkan tujuannya, NLP dapat dibagi menjadi dua, yaitu Natural Language Understanding (NLU) dan natural language generation (NLG).

Sebagian besar metode machine learning atau data mining, seperti proses klasifikasi teks, analisis topik, analisis sentimen, dan sebagainya termasuk ke dalam NLU. Terdapat berbagai macam pendekatan dari NLU untuk mela-kukan analisis topik dari sebuah dokumen, seperti Latent Dirichlet Allocation (LDA), Latent Semantic Indexing (LSI), Pachinko Allocation Machine (PAM), dan sebagainya.

Pendekatan LDA dapat memberikan hasil yang baik untuk analisis topik, namun hasilnya statis. Artinya kita harus mengulangi semua dari awal jika menggunakan dokumen yang berbeda Sementara LSI adalah sebuah pendekatan yang mudah diimplementasikan namun memiliki kemampuan yang rendah jika mengolah kata dengan komponen huruf yang sama namun memiliki arti yang berbeda. Hal ini dikenal juga dengan istilah polysemy.

Misal, kata "buku" dapat merujuk kepada lembaran kertas yang berjilid, atau tempat pertemuan dua ruas pada jari tangan, buluh, atau tebu.





## 03. Kelebihan dan Kekurangan

Implementasi NLP pada proses bisnis akan menekan biaya. Dibandingkan dengan menggunakan tenaga manusia lebih efektif menggunakan komputer dalam melakukan proses terjemahan, analisis sentimen, sistem tanya jawab pada layanan media sosial, analisis pasar, maupun klasifikasi musik, teks, dan dokumen.

Selain lebih murah, implementasi NLP juga lebih cepat dari sisi waktu.

Misal, layanan suara pada proses penulisan dokumen menggunakan Google Docs akan jauh lebih cepat daripada mengetik menggunakan bantuan keyboard. NLP juga kini mudah diterapkan dengan ketersediaan perangkat lunak yang komersial maupun yang tidak. Misal, dengan menggunakan bahasa R dan Python peneliti dapat dengan mudah melakukan analisis NLP berbasis LDA.

Kelemahan NLP di antaranya adalah tidak akan memberikan jawaban yang sesuai jika terdapat banyak kata yang ambigu. Untuk saat ini, analisis NLP sebagian besar tidak berbasis antarmuka pengguna (user interface) sehingga membutuhkan kemampuan programming yang baik. Analisis NLP tidak dapat digunakan ulang (not reproducable), peneliti selalu harus membuat model yang baru jika menggunakan data yang berbeda dari sebelumnya. Hasil akhir tidak dapat diprediksi dan akurasinya tidak akan mencapai 100% benar.

Kini tengah berkembang analisis NLP dengan platform berbasis cloud.

Misal Google Natural Language AI (https://cloud.google.com/natural-language), AWS Comprehend (https:/aws.amazon.com/comprehend/), Azure Text Analytics (https://azure.microsoft.com/en-us/services/cognitive-services/text-analytics/), Toloka (https://toloka.ai/), dan Lexalytics (https:// www.lexalytics.com/). Namun, tantangannya adalah pertama, biaya ber-langganan untuk platform komersial. Kedua, NLP berbasis cloud bersifat terlalu umum karena pengguna perlu mengakses via Application Programming Interface (API), maka hasilnya hanya berdasarkan teks atau doku-men yang di-input oleh pengguna saja. Pengguna tidak dapat melakukan modifikasi dari parameter NLP yang digunakan. Ketiga, platform cloud ini membutuhkan waktu untuk belajar bagi pengguna untuk mengguna-kannya serta belum tentu memberikan hasil akurasi yang tinggi.


