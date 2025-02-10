---
tags:
  - sains_data
  - materi_14_PSD
---
## [[01. Kualitas dan Kesalahan Data]]

Noise, outlier (pencilan), nilai yang hilang, duplikasi bisa dikelola, namun proses pengolahan yang kompleks juga berisiko pada munculnya kesalahan dan menyebabkan menurunnya kualitas informasi yang dihasil-kan. Dengan semakin bertambahnya tahap-tahap pengolahan data, maka akan semakin sulit pula memprediksi di mana kesalahan terjadi.

Terdapat enam komponen utama dari data yang berkualitas, yaitu:

1) **akurat secara posisi,** 
   Akurat secara posisi merujuk kepada keakuratan data yang digunakan, baik posisi geo-grafis maupun non geografis.
   
2) **akurat secara waktu,** 
   Akurat secara waktu merujuk pada data ter-baru bukan data yang sudah kadaluwarsa,
   
3) **memiliki atribut yang akurat,** 
   sementara akurat secara atribut merujuk pada label dari fitur data yang tepat.
   
4) **metode yang runtut,** 
   Metadata yang runtut merujuk kepada sejarah data yang tertulis dengan baik,
   
5) **lengkap,**
   sementara lengkap merujuk kepada data yang merepresentasikan semua fitur yang terkait dan mewakili dunia nyata.

6) **konsisten.**
   Terakhir, konsisten merujuk pada susunan data yang tersusun rapi dan logis.

#### a. Kualitas Data

Kualitas data sulit diukur, namun paling tidak terdapat tiga pendekatan untuk mengukurnya, yaitu: 1) Reliabilitas, 2) representasi fitur, dan 3) me-minimalkan skew.

##### 1. Reliabilitas

Reliabilitas mengacu kepada sejauh mana peneliti meyakini datanya. Dalam mengukur reliabilitas peneliti harus menentukan seberapa sering frekuensi kesalahan terjadi? Apakah terdapat noise dan bagaimana fluktuasinya? Apakah data telah disaring dengan benar sesuai dengan tujuan penelitian?

##### 2. Representasi Fitur

Representasi fitur mengacu pada apakah fitur telah mewakili dan sesuai dengan data yang peneliti gunakan. Apakah terdapat outlier? Apakah nor-malisasi data ke dalam bentuk numerik diperlukan?

##### 3. Kehadiran Skew

Skew di sini merujuk kepada perbedaan yang terjadi antara waktu pelatihan dan waktu implementasi. Kenapa hasilnya berbeda? Pastikan dalam proses pelatihan hanya menggunakan fitur yang sesuai saja.

#### b. Kesalahan Data

Terdapat paling tidak tiga sumber kesalahan sebagaimana telah disam-paikan sebelumnya, yaitu: 

- a) akuisisi data, 
- b) pengolahan data, dan 
- c) penggunaan data. 

Setiap tahapan ini mengandung kesalahan sehingga ketika berpindah pada tahapan selanjutnya kesalahan akan bertambah, dan kesalahan tersebut akan terus "diwariskan" sampai pada tahapan terakhir. Setiap kesalahan pada tahapan tersebut berkontribusi pada hasil akhir.

##### Data Science Chauvinism

Kekurangan ini perlu dipahami dengan baik oleh peneliti data science agar tidak terjebak pada "data science chauvinism", yaitu sebuah paham yang menganut bahwa pendekatan sains data tidak memiliki kekurangan dan dapat menjawab semua permasalahan modern secara mandiri tanpa bantuan domain keilmuan lainnya.

![[Screenshot 2024-10-27 at 10.27.16.png]]

Dalam upaya memperbaiki kesalahan, peneliti dapat menggunakan kerangka kerja sederhana seperti disajikan oleh Gambar 14.1. Temukan kesalahan yang mungkin ada dalam penelitian, kemudian buatlah sebuah hipotesis baru yang memperbaiki hipotesis sebelumnya. Lalu lakukan pengujian ulang. Lakukan berulang hingga kesalahan berkurang dan sudah tidak ditemukan lagi.




## 02. [[02. Deskriptif dan Prediktif]]

Data dapat digunakan untuk mencapai beragama tujuan, di antaranya adalah melakukan analisis historis untuk data di masa lalu, melakukan analisis deskriptif terhadap data di masa lalu dan kini, dan melakukan analisis prediktif untuk kemungkinan kejadian di masa depan.

Namun data memiliki keterbatasan usia, bisa saja data yang dibutuhkan untuk analisis historis tidak tersedia lengkap. Atau jika pun tersedia, maka masih dalam bentuk catatan-catatan manual dan membutuhkan sangat banyak waktu untuk mengubahnya ke dalam data digital.

Data masa kini juga belum tentu tersedia, mash banyak kemungkinan data tersebut memiliki banyak nilai ganda atau, bahkan nilai yang hilang Sementara untuk melakukan analisis prediktif membutuhkan data yang lengkap baik di masa kini maupun di masa lalu untuk dapat memprediksi kemungkinan kejadian dimasa depan secara akurat.

#### a. Deskriptif dan Prediktif

Persamaan dan perbedaan terkait analisis data deskriptif dan prediktif disajikan oleh Tabel berikut:


![[Screenshot 2024-10-27 at 10.29.03.png]]





## [[03. Diskret dan Kontinu]]

Data memiliki dua bentuk dasar, yaitu data dikret dan kontinu.

#### a. Data Diskret

Data diskret adalah data yang diperoleh dengan cara perhitungan. Misal, data jumlah mobil di jam kerja atau data jumlah penduduk di suatu wilayah. 

#### b. Data Kontinu

Sementara data kontinu adalah yang diperoleh dengan cara pengukuran. Misal, data suhu udara, curah hujan, ketinggian muka bumi, dan sebagainya.

Data diskret tidak memiliki satuan (unit) tertentu sementara data kon-tinu memiliki satuan (unit). Misal, data suhu udara memiliki satuan (unit) derajat Celsius, curah hujan memiliki satuan mm, dan ketinggian muka bumi memiliki satuan meter di atas permukaan laut (mdpl).

Secara teori data kontinu dapat digunakan untuk melakukan analisis prediksi, sementara data diskret tidak bisa. Namun dalam penerapannya, banyak peneliti menggunakan data diskret untuk analisis prediktif. Perang-kat lunak pasti dapat melakukan proses pengolahan datanya, namun prinsip dasar ilmiahnya dilanggar. Hal ini adalah keterbatasan yang sering kali tidak dipahami oleh peneliti data science.

Misal, kasus COVID-19 adalah data diskret, namun banyak peneliti menggunakan data kejadian COVID-19 untuk melakukan analisis prediktif. Jumlah kasus kejadian kriminal adalah data diskret, maka peneliti tidak dapat melakukan analisis interpolasi data dengan data tersebut. Data yang bisa di interpolasi adalah data kontinu bukan data diskret.

> Panduan untuk memilih visualisasi data diskret dan kontinu yang tepat dan lengkap dapat dilihat di sini https:/experception.net/FranconeriExperCeptionDotNetDataVisQuickRef.pdf


![[Screenshot 2024-10-27 at 10.32.24.png]]





## [[04. Presentasi vs Eksplorasi]]

Data juga dapat digunakan sebagai bahan presentasi maupun eksplorasi.

>Data sebagai bahan presentasi artinya data disajikan, divisualisasikan, dan didiseminasikan untuk keperluan komunikasi berbagai pihak yang berkepentingan. 

>Sementara data sebagai bahan eksplorasi artinya data diguna-kan untuk melakukan penjelajahan lapangan dengan tujuan memperoleh pengetahuan lebih banyak (tentang keadaan), terutama sumber-sumber alam yang terdapat di suatu lokasi.


Menurut KBBI, presentasi salah satu artinya adalah menyajikan, me-ngemukakan sesuatu dalam forum tertentu. Sementara masih menurut KBBI, eksplorasi salah satu artinya adalah kegiatan untuk memperoleh pe-ngalaman baru dari situasi yang baru.

#### a. Presentasi

Dalam konteks data science, presentasi berarti menyajikan atau me-ngemukakan data dan informasi kepada pemangku kepentingan untuk proses pengambilan keputusan yang tepat. Informasi di sini digunakan sebagai masukan atau bahan pertimbangan untuk meminimalkan risiko.

Presentasi adalah metode paling konvensional dalam pemanfaatan data, dimana peneliti dan pemangku kepentingan duduk bersama untuk proses pengambilan keputusan. Pada proses presentasi data biasanya digunakan untuk berbagai macam tujuan dan divisualisasikan dalam bentuk yang sederhana agar mudah dipahami.

#### b. Eksplorasi

Sementara eksplorasi dalam konteks data science adalah proses pengo-lahan data guna memperoleh pola, pengetahuan, wawasan, tentang sesuatu yang sebelumnya tidak terlihat atau tersembunyi. Kegiatan eksplorasi bia-sanya melibatkan banyak pakar dengan berbagai latar belakang keilmuan yang berbeda. Pada proses eksplorasi data biasanya digunakan untuk sebuah tujuan tertentu saja dan divisualisasikan dalam bentuk yang kompleks.


Sehingga, kemampuan data sebenarnya amat terbatas. Data hanya dapat digunakan untuk presentasi dan eksplorasi, Data hanya digunakan sebagai tambahan masukan untuk proses pengambilan keputusan. Masih banyak variabel lain selain data yang harus dipertimbangkan sebelum keputusan akhir diambil.

Tabel 14.2 merangkum perbedaan antara presentasi dan eksplorasi pada data science

![[Pasted image 20241027103543.png]]





## [[05. Persepsi Manusia]]

Manusia dalam proses pengambilan keputusan dipengaruhi oleh paling tidak dua hal, yaitu pengetahuan yang dikuasai dan pengalaman yang dimiliki. Kedua hal ini akan saling bekerja sama dan mendukung dalam proses pengambilan keputusan akhir.

Sementara persepsi adalah suatu proses yang berlangsung di pikiran dan perasaan seseorang untuk menge-tahui sesuatu yang dibantu juga oleh pancaindranya.


#### Hal yang mempengaruhi kapasitas persepsi

Paling tidak terdapat tiga hal yang memengaruhi kapasitas persepsi manusia, yaitu 1) sesuatu yang dianggap sama penting, 2) urutan, dan 3) jumlah atau kuantitas. Hal ini sebagai diuraikan sebagai berikut.

##### 1. Sesuatu yang dianggap sama penting.

Contoh sederhana jika menggunakan dominan warna merah pada suatu peta, maka persepsi manusia akan mengatakan bahwa peta tersebut adalah peta bencana. Bencana apa pun, dapat berupa bencana alam, maupun bencana kema-nusiaan (perang, konflik, dan lain-lain). Jika terdapat warna biru pada suatu peta, maka persepsi manusia lokasi tersebut adalah perairan. Selanjutnya, jika terdapat warna hijau, maka persepsi manusia akan mengatakan bahwa terdapat vegetasi atau hutan. 

Selain warna, variabel visual yang biasa digunakan adalah orientasi dan bentuk geometri. Persepsi berdasarkan persepsi ini hanya dapat digunakan untuk data dengan skala nominal.


##### 2. Urutan

Contohnya kasus kejadian COVID-19 yang diurutkan dari rendah ke tinggi berdasarkan Provinsi di Indonesia. Variabel visual yang biasa digunakan adalah tekstur, dan tingkat warna abu-abu. Persepsi berdasarkan urutan dapat digunakan untuk data dengan skala ordinal, interval, dan rasio.

##### 3. Kuantitas

Misalnya, simbol lingkaran yang berubah ukuran secara gradual, dari kecil ke besar yang menunjukkan kekuatan gempa dalam skala Richter atau Magnitudo. Variabel visual yang biasa digunakan adalah ukuran simbol yang digunakan. Persepsi berdasarkan kuantitas dapat digunakan untuk data dengan semua skala (nominal, ordinal, interval, dan rasio).'


Selanjutnya, penggunaan kombinasi ukuran dan kedalaman warna juga memengaruhi persepsi manusia. Misal, penggunaan simbol lingkaran yang semakin besar dengan warna yang semakin gelap akan memberikan persepsi bahwa terjadi peningkatan volume atau ukuran ataupun kejadian.

![[Screenshot 2024-10-27 at 10.43.25.png]]

Dalam membuat visualisasi data, peneliti perlu mempertimbangkan persepsi manusia secara umum. Agar data dan informasi yang disajikan dapat dipahami dengan benar. Informasi yang baik adalah jika terdapat tumpang-tindih antara informasi yang diharapkan oleh peneliti dengan informasi yang diperoleh oleh pemangku kepentingan

Atau dengan kata lain terdapat konsistensi informasi. Jika informasi yang diperoleh pemangku kepentingan berbeda sama sekali dengan informasi yang diharapkan oleh peneliti artinya proses pengolahan data yang dilaku-kan menjadi sia-sia.





## [[06. Visualisasi dan Persuasi]]

#### a. Visualisasi

Visualisasi dapat digunakan sebagai jembatan untuk menghubungkan antara banyak pemangku kepentingan dengan tingkat pengetahuan yang berbeda-beda. Sehingga mereka dapat mencapai sebuah keputusan yang disepa-kati oleh semua pihak. 

Visualisasi berperan sangat penting dalam proses pengambilan keputusan di mana pemangku kepentingan memiliki sudut pandang, kepentingan, dan kepakaran yang berbeda-beda. Ini yang disebut dengan visualisasi sebagai media persuasi.

#### b. Persuasi

Persuasi bermakna mengimbau orang lain meyakini sesuatu dengan cara memberikan alasan dan prospek baik yang meyakinkan. Alasan dan prospek tersebut akan bersandarkan kepada informasi yang tersaji di dalam media visualisasi. Sehingga, visualisasi dapat digunakan untuk dua tujuan, yaitu mencapai tujuan yang dikehendaki atau bahkan menjauhkan pemangku kepentingan dari tujuannya.

#### Dual Process Theory

Menurut teori dual process, proses pengambilan keputusan akan ber-sandar pada dua sistem berpikir di dalam otak manusia, yaitu sistem 1 dan sistem 2.

##### System 1
Sistem 1 merujuk kepada insting atau cara berpikir manusia yang cepat yang sebagian besarnya bergantung pada rasa yang dimiliki.

##### System 2
Sementara sistem 2 merujuk kepada kesadaran kognitif, proses analisis yang sebagian besarnya bergantung kepada pengetahuan yang dimiliki.

Kedua sistem ini saling bekerja sama dalam proses pengambilan keputusail.

Bagaimana peneliti dapat membuat visualisasi yang mampu memberikan persuasi positif akan tergantung pada pemahaman peneliti terhadap cara kerja kedua sistem ini di dalam otak pengguna.

Contoh sederhana dari visualisasi dalam upaya persuasi adalah peng-gunaan diagram dengan sumbu x dan sumbu y yang tidak memiliki rentang yang sama atau terdistorsi. Sehingga dapat menghasilkan visualisasi yang memberikan persuasi, seperti terdapat peningkatan/penurunan tajam, atau perbedaan yang signifikan, ataupun terdapat korelasi dan hubungan sebab-akibat.

![[Screenshot 2024-10-27 at 10.47.11.png]]

Perhatikan Gambar 14.4, pada gambar sebelah kiri untuk ukuran leher memiliki nilai maksimal 45 dan nilai minimal 42 pada sumbu y, rentang nilai adalah satu. Sementara pada gambar sebelah kanan, memiliki nilai maksimal 44 dan nilai minimal 38 pada sumbu y, dengan rentang nilai 2.

Pada gambar sebelah kiri kita akan mendapatkan kesan bahwa terdapat korelasi antara ukuran leher dengan berat badan. Namun, jika kita lihat gambar di sebelah kanan, kita tidak mendapatkan korelasi yang erat antara ukuran leher dan berat badan. Yang jelas terlihat adalah penurunan ukuran leher dan berat badan anjing sepanjang periode 2006 hingga 2015.



## [[07.  Bias Kognitif]]

#### a. Heuristics

Perangkat yang digunakan oleh manusia dalam melakukan evaluasi ber-bagai kemungkinan dan mengambil keputusan yang berlandaskan kepada penilaian subjektif berdasarkan kondisi mental dirinya disebut heuristics.

Pendekatan heuristic artinya metode kasar dan proses mental yang digu-nakan oleh seseorang untuk memecahkan persoalan. Pendekatan ini mungkin tidak sempurna dan akurat, namun cukup sesuai dalam meme-cahkan persoalan sederhana dalam hidup keseharian manusia. Namun, pendekatan ini berpeluang memberikan panduan yang keliru dan kesalahan sistematis dalam proses pengambilan keputusan yang krusial.

Seseorang dapat menggunakan pendekatan heuristic tanpa berpikir panjang atau tanpa pengetahuan tentang apa yang sedang ia lakukan. Sehingga kesalahan dalam pengambilan keputusan bisa saja muncul karena prosedur yang tidak sesuai.

#### b. Bias

Sementara bias adalah kekeliruan sistematis dari proses pengambilan keputusan, yang disebabkan oleh keterbatasan dalam penggunaan metode heuristic.

Dalam visualisasi bias kognitif dapat dibagi ke dalam tiga jenis (Valdez, 2018), yaitu 1) bias persepsi, 2) bias aksi, dan 3) bias sosial.

##### 1. Bias Persepsi

Bias persepsi, yaitu bias yang terjadi pada tingkat paling rendah dalam proses kognitif. Seorang manusia tidak mungkin menghilangkan bias persepsi, dan bias ini tidak bisa dihindari meskipun dengan melakukan pelatihan.

##### 2. Bias Aksi

Bias aksi, yaitu bias yang terjadi karena interpretasi, apa yang dilihat, dirasakan, dan diketahui dapat diolah secara objektif dan dianalisis secara sistematis. Bias ini dapat dihindari dan diminamilisir dengan kegiatan pelatihan.

##### 3. Bias sosial

Bias sosial, yaitu bias yang muncul dan hanya dapat dipahami terkait hubungannya dengan kondisi sosial budaya dan norma-norma yang dianut. Bias ini berakar pada kepercayaan dan pengalaman hidup yang dilalui.


![[Screenshot 2024-10-27 at 10.52.09.png]]

Gambar 14.5 adalah ilustrasi visualisasi dalam kasus kejadian badai di Amerika Serikat, Penggunaan visualisasi tersebut oleh Ruginski et al (2016) untuk mengukur tingkat bias yang dimiliki oleh pengguna. Penelitiannya menemukan bahwa penggunaan geometri cone, yang disertai dengan. garis tengah, serta bayangan kabur, akan menurunkan bias persepsi dari pengguna. Namun penggunaan geometri cone juga menyebabkan salah interpretasi menjadi daerah terdampak, padahal itu adalah kemungkinan area yang akan dilalui oleh badai.

Penggunaan geometri cone saja tanpa garis tengah juga menyebabkan kesalahan interpretasi. Bahwa daerah tersebut tidak terdampak parah akibat diterjang badai. Hal ini dikarenakan pengguna menggunakan pendekatan heuristic yang berbeda-beda.