---
tags:
  - sistem_informasi_management
  - materi_9_SIM
---
# [[Kegiatan Belajar 1 - Internet]]

Sistem informasi mulai menghubungkan dua atau lebih organisasi. Bentuk sistem ini disebut dengan interorganizational systems, Salah satu aplikasi dari inter-organizational systems adalah electronic data interchange (EDI).

Dalam praktiknya, aplikasi EDI dapat menggunakan jalur telepon biasa, value added network atau menggunakan internet sebagai jalur komunikasinya. Aplikasi EDI dengan internet mulai banyak diterapkan. Tidak hanya aplikasi EDI yang mulai menggunakan internet, tetapi hubungan ke pelanggan pun mulai menggunakan internet.

## 01. Jejaring Komputer

Dalam sistem telekomunikasi, istilah jejaring (network) digunakan apabila paling sedikit dua atau lebih alat-alat dihubungkan satu dengan yang lainnya. Jaringan komputer ini me-mungkinkan tidak hanya organisasi yang sama dihubungkan satu dengan yang lainnya untuk pengiriman data, tetapi juga dengan organisasi lain dan bahkan langsung dengan pemasok dan konsumen.

Upaya-upaya ini telah mulai banyak dilakukan, misalnya jaringan ATM, yaitu menarik sistem informasi bank ke luar mendekati nasabah dengan menggunakan teknologi telekomunikasi. Contoh lainnya, toko buku maya lewat jaringan internet. Oleh karena itu, pemanfaatan teknologi telekomunikasi ke dalam teknologi sistem komputer merupakan hal yang penting.

#### Komponen Jejaring Komputer
Untuk membentuk jejaring komputer secara global, dibutuhkan beberapa komponen berikut ini:

1. komputer atau terminal pengirim untuk mengirim data atau informasinya;
2. media transmisi (transmission media), jalur, atau kanal komunikasi (communication channel) yang akan membawa data yang dikirimkan dari sumber data ke penerima;
3. pemroses komunikasi (communication processor) merupakan alat pendukung transmisi data, misalnya modem;
4. perangkat lunak komunikasi (communication software) yang akan mengendalikan proses komunikasi data;
5. komputer atau terminal penerima.

Sebelum data dikirimkan,data perlu dipersiapkan terlebih dahulu. Komputer pengirim mempunyai tugas melakukan hal tersebut. Demikian juga komputer penerima perlu melakukan tugas-tugas menerima kiriman data.

#### Media Transmisi

Beberapa media transmisi dapat digunakan sebagai kanal transmisi, yaitu dapat berupa kabel, radiasi elektromagnetis dan satelit. Apabila sumber data dan penerima jaraknya tidak terlalu jauh dan dalam area yang local,dapat digunakan kabel sebagai media transmisinya. Kabel dapat berbentuk kabel tembaga biasa (kabel UTP) yang digunakan pada telepon atau coaxial cable atau fiber optic cable. Kabel tembaga biasa karena bentuknya dipelintir disebut juga dengan nama fwisted wire. Coaxial cable merupakan kabel yang dibungkus dengan metal yang lembek. Coaxial cable mempunyai tingkat transmisi data yang lebih tinggi dibandingkan dengan kabel biasa, tetapi lebih mahal. Fiber optic cable (kabel serat optik) dibuat dari serabut-serabut kaca (optical fibers) yang tipis dengan diameter sebesar diameter rambut manusia.

Fiber optic cable mempunyai kecepatan pengiriman data sampai 10 kali lebih besar dari coaxial cable.

#### Bandwidth

Bandwidth (lebar band) menunjukkan sejumlah data yang dapat ditransmisikan untuk satu unit waktu yang dinyatakan dalam satuan bits per second (bps) atau characters per second (cps). Bandwidth dengan satuannya bps atau eps menyatakan ukuran dari kapasitas kanal transmisi, bukan ukuran kecepatan. Transmisi data dengan ukuran 1.000 bits per second tidak dapat dikatakan lebih cepat dari transmisi data dengan ukuran 200 bitspersecond, tetapi dapat dikatakan bahwa lebih banyak data yang dapat dikirimkan pada satu unit waktu yang tertentu.

#### Perangkat Keras Jejaring

Komunikasi data melibatkan dua atau lebih perangkat keras yang dihubungkan.
Supaya perangkat-perangkat keras ini dapat melakukan konektivitas, diperlukan perangkat lunak komunikasi. Perangkat lunak komunikasi yang digunakan di internet misalnya adalah internet explorer atau internet browser. Perangkat lunak ini berisi dengan protokol (protocol) yang diperlukan untuk konektivitas.



## 02. Domain Internet

Internet merupakan singkatan dari interconnected network atau jaringan-jaringan saling terkoneksi dari sistem-sistem komputer yang dapat saling diakses. Internet juga sering disebut dengan kependekannya, yaitu net. Internet diluncurkan pertama kali pada tahun 1969 sebagai proyek gabungan antara defense advanced research project agency (DARPA) yang merupakan agensi pemerintah dalam membangun internet untuk keperluan pertahanan militer dengan empat universitas di Amerika Serikat.

Internet menghubungkan sistem komputer di satu tempat dengan sistem komputer di tempat lain. Sistem komputer yang dihubungkan dapat berupa sebuah komputer tunggal atau jaringan komputer lokal atau local area network (LAN) di suatu lokasi.

Komunikasi antarsistem komputer ini menggunakan media transmisi gelombang radio (microwave), satelit, jaringan telepon, dan serat optik (fiber optic).

#### Alamat Protokol Internet

Masing-masing sistem komputer yang dihubungkan dengan internet diberi alamat protokol internet (alamat PI) atau internet protocol address (IP address) yang unik.

Alamat PI (IPaddress) terdiri atas empat kelompok angka digit yang dipisahkan dengan titik dan masing-masing kelompok bernilai dari angka 0-255 dengan format sebagai berikut: 999.999.999.999. Dengan demikian, terdapat kombinasi alamat PI sebanyak (256*) alamat atau sebanyak 4,294,967,296 alamat PI.

#### DNS Protocol

Untuk mengorganisasikan alamat PI lebih lanjut supaya lebih mudah ditemukan dan diakses, sistem komputer yang dihubungkan dengan internet juga dapat diberi protokol jasa nama domain (domain name service protocol atau DNS Protocol).

DNS dapat berupa .edu untuk institusi pendidikan (misalnya temple.edu), gov untuk pemerintah (misalnya sec.gov),.com untuk organisasi komersial (misalnya yahoo.com), .org untuk organisasi umum lainnya, net untuk penyedia jasa jaringan dan .mil untuk militer. DSN dapat juga dikelompokkan berdasarkan negaranya, misalnya .id untuk Indonesia (misalnya bapepam.go.id), ja untuk jepang, dan lainnya. Misalnya, suatu sistem komputer akan dihubungkan ke alamat PI temple.edu.

Pertama kali komputer ini akan mencarinya di daftar alamat, yaitu di memori utama apakah nama ini sudah pernah diakses. Jika sudah pernah diakses, biasanya alamat PI masih ada di sana atau dicari di hard disk nama-nama alamat PI favorit yang disimpan oleh komputer. Jika ditemukan alamat PI, komputer ini dapat langsung menghubungkannya ke alamat PI ini. Jika alamat PI tidak ditemukan, akan dicari di komputer-komputer atasnya sampai ditemukan. Jika semua komputer atasnya tidak menemukan alamat ini, akan dicari di komputer penyelenggara domain, yaitu server edu karena semua nama dengan .edu didaftarkan di server tersebut.

Penyelenggara domain yang pertama adalah internet assignment numbers authority (IANA). Lembaga ini dikontrol oleh Pemerintah Amerika Serikat. Lembaga ini bertanggungjawab mengontrol nama domain internet dan nomor alamat IP. Sekarang lembaga ini diganti dengan lembaga yang lebih luas dan bertaraf internasional, yaitu internet corporation for assigned names and numbers (ICANN). Lembaga ini menambah nama domain seperti biz untuk business, name untuk nama individual, .pro untuk professional, seperti akuntan, dokter, dan lainnya, serta .aero untuk perusahaan penerbangan dan lainnya.




## 03. Protokol Internet

Kemampuan komputer untuk berkomunikasi dan berbagi komunikasi satu dengan yang lainnya disebut dengan connectivity. Untuk mencapai connectivity, dibutuhkan standar komunikasi data yang disebut dengan protocol.

Protocol adalah suatu kumpulan aturan yang berhubungan dengan komunikasi data antara alat-alat komunikasi supaya komunikasi data dapat dilakukan dengan benar. Jabat tangan merupakan contoh dari protocol antara dua manusia yang akan berkomunikasi. Di istilah komputer, jabat tangan (handshaking) menunjukkan suatu protocol dari komunikasi data apabila dua buah alat dihubungkan satu dengan yang lainnya untuk menentukan bahwa keduanya telah kompatibel. Supaya kompatibel, pada waktu transmisi data, keduanya harus mempunyai transfer rate (tingkat pengiriman) yang sama, format datanya harus sama, tipe transmisinya harus sama, dan mode transmisinya juga harus sama.

Berita-berita elektronik (electronic messages) dikirimkan di internet dalam bentuk paket-paket (packets). Internet membutuhkan suatu protokol (protocol) untuk mengontrol pengiriman paket-paket ini supaya dapat diterima dengan baik oleh komputer penerima. Protokol (protocol) adalah suatu kumpulan aturan-aturan yang mengendalikan sistem-sistem yang berhubungan sehingga dapat beroperasi dan berkomunikasi dengan kompatibel dan lancar. Protokol di internet diorganisasikan dalam bentuk lapisan-lapisan. Lapisan tingkat paling bawah adalah protokol internet (internet protocol atau IP) dan transmission control protocol (TCP).Bersama-sama dengan internet protocol (IP), protokol-protokol ini disingkat menjadi TCP/IP yang mempunyai tugas meyakinkan bahwa paket-paket berita-berita elektronik dikirimkan dan diterima dengan benar dari satu sistem komputer ke sistem komputer yang lain. Protokol yang tingkatannya lebih tinggi adalah file transfer protocol (FTP) yang digunakan untuk memuat (uploading) berkas-berkas (files) yang akan dikirim dan mengambil (downloading) berkas-berkas (files) yang sudah diterima. Protokol tingkat lebih tinggi lainnya adalah simple mail transfer protocol (SMPT) untuk mengirim e-mail dan TELNET untuk emulasi terminal jaringan.



## 04. World Wide Web

World wide web atau WWW atau W3 atau cukup disebut dengan web (dalam bahasa Indonesia diusulkan menjadi JJJ atau jelajah jagat jembar atau jaringan jagat jembar) merupakan suatu sistem informasi multimedia yang memanfaatkan internet untuk mempublikasikan informasi. Informasi multimedia di WWW dibuat dengan menggunakan hypertext. Dokumen hypertext disimpan di server web (misalnya di geocities.com) dan diakses dengan menggunakan browser

Dua hal yang berhubungan dengan hypertext adalah hypertext transfer protocol (HTTP) dan hypertext markup language (HTML). Informasi tentang web ini dapat diakses di www.w3.org-

### HTTP

Hypertext transfer protocol (HTTP) adalah protokol (kumpulan dari aturan komunikasi) yang mengatur komunikasi antara serverweb dan web browser. Tiap-tiap dokumen web mempunyai sebuah alamat yang disebut dengan uniform resource locator (URL). Untuk mengakses suatu dokumen web, dapat dituliskan URL, misalnya http:// temple.edu/index.html. Pertama, kata http: menunjukkan bahwa URL akan diakses dengan menggunakan HTTP (halaman web dapat juga diakses dengan protokol lain, misalnya menggunakan FTP: atau GOPHER:). Kata kedua setelah // adalah alamat dari server, yaitu temple.edu. Kata terakhir, yaitu /index.html adalah lokasi dari dokumen web.

#### HTML

Hypertext markup language (HTML) merupakan bahasa yang digunakan untuk menentukan isi dan struktur dari halaman-halaman web. Bahasa HTML ini berkembang terus seiring dengan berkembangnya websites (situs-situs web yang semakin banyak dibuat). Generasi baru dari bahasa HTML ini adalah extensible markup language (XML) dan penerapannya dipelaporan akuntansi, yaitu extensible business reporting language (XBRL).

#### XML

Dengan extensible markup language(XML), nilai data dapat dituliskan di halaman web dengan menggunakan nama variabel. Misalnya, statesmen<LABA-PERLEMBAR="Rp">7500</LABA-PERLEMBAR> menunjukkan bahwa laba per lembar saham perusahaan yang laporan keuangannya ditampilkan di web ini adalah sebesar Rp 7500,00. Dengan keluwesan seperti ini, search engine dapat diprogram untuk mencari situs-situs web yang menampilkan laporan keuangan untuk perusahaan-perusahaan dengan nilai LABA-PERLEMBAR tertentu (misalnya yang lebih besar dari Rp 5000,00) dan kemudian nilainya dapat disimpan di basis data. Perusahaan perangkat lunak Microsoft dan IBM sedang bekerja sama dengan industri akuntansi dalam pelaporan-pelaporan keuangan untuk mengembangkan XML sebagai pelaporan bisnis yang disebut dengan extensible business reporting language (XBRL). XBRL ini gratis dan informasi lebih lanjut dapat dilihat di www.xbrl.org.



---


# [[Kegiatan Belajar 2 - E-Commerce dan E-Business]]

Penerapan e-commerce atau e-business tidak hanya penggunaan teknologi internet pada kegiatan bisnis, tetapi diperlukan suatu model bisnis di belakangnya. Keberhasilan e-commerce atau e-business terletak bagaimana penerapan model bisnis untuk memperoleh keuntungan kompetitif. Kegiatan belajar ini akan membahas e-commerce atau e-business ini.


## 05. Definisi E-Commerce

Beberapa definisi telah diberikan untuk e-commerce (electronic commerce). Martin dkk (1999) mendefinisikan e-commerce sebagai penggunaan TI untuk melakukan kegiatan bisnis antara dua atau lebih organisasi atau antara sebuah organisasi dengan satu atau lebih pelanggan akhir (end-customer) melalui satu atau lebih jaringan komputer.

#### Klasifikasi E-Commerce
Dari definisi yang luas ini, e-commerce dapat diklasifikasikan ke dalam dua aplikasi berikut.

##### 1. Aplikasi Electronic Commerce antara Organisasi-Organisasi Bisnis
Sistem aplikasi e-commerce yang melibatkan organisasi-organisasi bisnis ini sering disebut dengan sistem interorganisasi (interorganizational system atau IOS) atau business to business (B2B). Dengan sistem interorganisasi ini, dimungkinkan suatu perusahaan untuk lebih efisien dan efektif melakukan kegiatan bisnis dengan supplier, dengan langganan-langganan atau dengan dealer-dealer dan distributor-distributornya.

Contoh sukses dari aplikasi ini misalnya adalah SABRE, yaitu sistem reservasi tiket yang dimiliki oleh American Airline dan electronic data interchange (EDI).

##### 2. Aplikasi Electronic Commerce antara Organisasi Bisnis dan Pelanggan Akhir
Aplikasi e-commerce yang paling banyak dibicarakan sekarang ini adalah aplikasi e-commerce yang menggunakan jasa internet melalui jaringan world wide web (WWW). Aplikasi ini disebut juga dengan istilah B2C (business to customers). Dengan menggunakan internet,dimungkinkan suatu perusahaan untuk menjangkau pelanggan-pelanggan di mana pun, siapa pun, dan kapan pun. Konsep ini konsisten dengan konsep reach and range oleh Keen (1991), yaitu mengusulkan perusahaan-perusahaan yang menggunakan TI supaya mendapatkan keunggulan strategis untuk menarik jangkauan dari TI sampai pelanggan-pelanggan akhir.

Pada akhir tahun 1990-an, e-commerce mulai menggunakan teknologi internet, terutama menggunakan teknologi web. E-commerce lewat internet juga mempunyai keuntungan yang sama dengan yang dimiliki oleh EDI. Keuntungan yang lain lewat internet adalah pengurangan biaya yang lebih besar dibandingkan dengan pengurangan biaya akibat penggunaan EDI karena biaya akses internet lebih murah dibandingkan dengan biaya komunikasi dengan EDI. Tambahan keuntungan lainnya adalah penggunaan internet dapat menjangkau lebih jauh sampai pelangganakhir.

#### Keuntungan E-Commerce dengan Internet
Lebih lanjut, Martin dkk (1999) mengutarakan tambahan keuntungan e-commerce lewat internet dibandingkan lewat EDI sebagai berikut:

1. distribusi yang lebih murah dari dokumen dan produk digital,
2. kemampuan memberikan layanan dukungan kepada pelanggan,
3. kanal pemasaran yang baru,
4. ﻿﻿﻿mempunyai kemampuan untuk menarik pelanggan baru,
5. ﻿﻿﻿menyediakan satu titik lokasi kontak untuk bermacam-macam produk dan jasa,
6. dapat digunakan sebagai media riset pasar.

#### Hambatan E-Commerce dengan Internet

Selain keuntungan yang diperoleh e-commerce dari penggunaan internet, beberapa hambatan juga ditemui seperti berikut:

1. keamanan,
2. keamanan akses,
3. keamanan transmisi,
4. beban trafik yang terlalu banyak, kesulitan sensor,
5. kesultan mengukur kinerja dari situs, apakah keberhasilannya akan diukur dari jumlah orang yang mengunjungi atau diukur dengan cara lain.





## 06. E-Business

Tidak dapat dimungkiri bahwa peranan e-commerce sangat besar dalam mengubah model bisnis konvensional, mengubah struktur biaya transaksi, serta mengubah hubungan transaksi antara pembeli-pembeli, penjual-penjual, dan setiap orang yang terlibat di dalamnya. Peranan e-commerce ini tidak hanya terjadi dalam sekejap, tetapi lewat beberapa tahapan berikut.

#### 1. Tahap Pertama (1994-1997)

Tahapan ini merupakan tahapan awal e-commerce yang masih berbentuk website. Banyak perusahaan membangun situs jaringan yang memberikan informasi dan pengunjung dapat meninggalkan nama dan alamat untuk dihubungi kembali oleh perusahaan.

#### 2. Tahap Kedua (1997-2000)

Pada tahap ini,e-commerce sudah mulai digunakan untuk transaksi jual dan beli lewat media digital. Fokus dari e-commerce ini adalah melakukan order pembelian.

#### 3. Tahap Ketiga (2000-Sekarang)

Fokus dari e-commerce ini adalah mendapatkan keuntungan. Keuntungan tidak hanya meningkatkan pendapatan kotor, tetapi juga meningkatkan margin kotor. Kalakota dan Robinson (2001) menyebutnya sebagai e-business yang berbeda dengan e-commerce.

E-business tidak hanya jual dan beli lewat situs jaringan, tetapi lebih diarahkan ke strategi bisnis yang mengubah model atau struktur bisnis dengan bantuan teknologi internet memaksimumkan nilai kepada langganan dan meningkatkan laba kepada perusahaan. Menurut Turban dkk (2002), e-business lebih luas dari e-commerce, yaitu tidak hanya melibatkan penjualan dan pembelian barang-barang dan jasa-jasa, tetapi juga melibatkan pelayanan kepada pelanggan-pelanggan, kerja sama-kerja sama dengan partner-partner bisnis dan melakukan transaksi elektronik dalam suatu organisasi. Bagaimanapun banyak yang mengatakan, walaupun berbeda, e-commerce dan e-business merupakan dua istilah yang saling menggantikan.




## 07 Model Bisnis

Teknologi tidak hanya sebagai pemikiran berikutnya dari pembentukan strategi bisnis, tetapi lebih ke penyebab dan pemicunya. E-business akan menyebabkan dan memicu perusahaan untuk meningkatkan labanya. Penerapan e-business membutuhkan pemikiran ulang dan perancangan ulang dari model-model bisnis yang baru. Menurut Kalakota dan Robinson (2001), ini merupakan langkah awal untuk mendapatkan laba, bahkan untuk bertahan di era informasi e-business. Di dunia bisnis sekarang ini, yang satu bisnis terkait dengan bisnis lain di rantai nilai industri jika salah satu entitas di rantai nilai ini melakukan bisnis secara elektronik, perusahaan-perusahaan di atas dan di bawah rantai nilai entitas ini harus menyesuaikannya dengan melakukan bisnis juga secara elektronik jika tidak ingin mengambil risiko diganti atau dikeluarkan dari rantai nilainya.

Penerapan e-business tidak hanya penerapan internet atau teknologi dari sisi teknisnya, tetapi lebih dari perubahan struktur bisnis. E-business sekarang dipandang sebagai transformasi struktur bisnis yang mengubah cara dan model bisnis untuk bersaing mendapatkan laba. Contohnya adalah Encyclopedia Britannica yang dulu berbisnis menawarkan barangnya di toko, lewat salesman atau lewat katalog-katalog.

Dengan adanya internet, perusahaan ini terpaksa mengubah model bisnisnya dengan menjualnya lewat internet. Dengan perubahan lingkungan bisnis yang tajam dengan banyaknya informasi gratis yang dapat diperoleh lewat internet, sekali lagi perusahaan ini mengubah model bisnisnya untuk menyediakan barangnya lewat internet dengan gratis. Perusahaan ini mendapatkan laba dari sumber-sumber lain, seperti iklan yang dipasang di situsnya.

Contoh lainnya adalah IBM dan DEC (Digital Equipment Corporation) di sekitar tahun 1980-an. Di pasar PC, kedua perusahaan ini mulai dikalahkan oleh pendatang baru, seperti Compaq, Dell, dan Gateway. Akhirnya, perusahaan DEC malah diakuisisi oleh Compaq. Kegagalan perusahaan DEC disebabkan manajemen DEC melakukan dua kesalahan besar. Pertama, perusahaan ini tidak mau mengubah struktur bisnisnya dari komputer skala menengah ke PC dan bahkan ke client server system. Kedua, perusahaan terlambat menerapkan e-business dalam proses bisnisnya.

Perubahan struktur atau model bisnis sudah mulai merambah ke semua industri bisnis, seperti jasa keuangan, distribusi barang, pengecer dan agen. Dengan e-business, industri-industri ini mulai mentransformasikan dirinya dari model bisnis yang konvensional menjadi model-model bisnis yang baru, seperti penyedia jasa aplikasi, penyedia jasa internet, dan portal.

Transformasi struktur tidak hanya terjadi di aktiva-aktiva berwujud (tangible assets), seperti proses dan produk-produk yang dijual oleh perusahaan, tetapi juga terjadi di aktiva-aktiva tidak berwujud (intangible assets) semacam merek atau hubungan dengan pemasok dan pelanggan. 
>Menurut Kalakota dan Robinson (2001), informasi tentang aktiva tidak berwujud di sekitar produk dan jasa yang ditawarkan ini lebih penting dibandingkan dengan produk dan jasanya sendiri.

#### Transformasi Model

Transformasi model atau struktur bisnis bukan hal yang mudah, terutama pada perusahaan yang sudah mapan dengan model tradisionalnya.

1. Pertama, manajemen merasa model konvensional tersebut merupakan model yang sudah tepat dan menghasilkan laba. Pemikiran seperti ini benar jika kondisi persaingan statis tidak dinamis yang berubah terus karena banyak faktor lingkungan.
   
2. Kedua, keengganan untuk mentransformasi ke struktur baru karena banyaknya modal yang sudah ditanamkan (misalnya aktiva-aktiva tetap) yang tidak dapat dikembalikan karena perubahan struktur. Mereka juga tidak mau mengorbankan lini produknya yang sudah berhasil bertahun-tahun. Misalnya, perusahaan Toys "R"Us sudah menanamkan modalnya berupa lebih dari 1000 toko mainannya. Untuk perusahaan ini, akan sangat sulit merealokasikan aktivanya yang mahal dan banyak ini dalam waktu singkat dengan melakukan transformasi radikal ke penjualan secara elektronik. Dalam hal ini, transformasi model akan sangat mudah dilakukan oleh perusahaan-perusahaan berbasis e-business yang masih baru (e-start-up).

Untuk dapat mempertahankan dirinya dari perusahaan-perusahaan baru berbasis e-business, perusahaan-perusahaan yang sudah mapan dengan model konvensional harus mempunyai perencanaan strategi terarah ke transformasi struktur ini. Perusahaan-perusahaan ini harus bekerja keras dan cepat untuk melakukan perubahan. Aktiva-aktiva di struktur lama harus cepat diganti dan biaya-biaya yang sudah masuk lubang dalam (sunk costs) yang sudah tidak dapat dikembalikan lagi karena melekat pada struktur lama harus dilupakan dan memulai sesuatu yang baru.

#### CompuServe dan Prodigy

Cerita tentang CompuServe dan Prodigy merupakan contoh pemimpin pasar yang tidak mentransformasi model bisnisnya dengan cepat. 

Didirikan pada tahun 1969, perusahaan CompuServe menawarkan akses internet dan informasi kepada pelanggan-pelanggannya. Informasi yang dapat diakses dapat berupa informasi olahraga, perjalanan, bisnis, sumber-sumber untuk profesional, berita-berita ekonomi, politik dan lainnya yang terbaru dan basis data yang dapat digunakan untuk melacak. Prodigy muncul pada tahun

1990 sebagai kerja sama antara IBM dan Sears. Pada puncaknya, Prodigy memiliki 2 juta pelanggan tetap. Pada awal tahun 1990, baik CompuServe maupun Prodigy mendominasi dan menikmati posisi unggul di internet bisnis sampai akhirnya datang pesaing baru bernama American Online (AOL). Perusahaan AOL merupakan perusahaan yang kecil dibandingkan dengan CompuServe dan Prodigy, tetapi lebih agresif dan mulai mengambil banyak pangsa pasar. AOL mengirimkan jutaan disket kepada calon pelanggan potensial dan hanya dengan menginstal perangkat lunak yang ada dalam disket, pelanggan baru sudah dapat akses ke AOL. Pada tahun 1995, karena mulai kalah bersaing, Sears mau menjual bagiannya di Prodigy ke IBM dan tidak terlaksana karena IBM merasa harganya masih terlalu tinggi. Pada akhirnya pada tahun 1996, baik Sears maupun IBM menjual

Prodigy ke karyawan-karyawannya. Pada tahun 1998, CompuServe dijual pada AOL. Untuk lima jasa online pada tahun 1994, empat dimiliki oleh perusahaan besar, yaitu Prodigy oleh Sears dan IBM, Delphi oleh New Corp., Genie oleh General Electric dan CompuServe oleh H&R Block. Yang kelima adalah AOL.

#### AOL
Kalau dulu AOL yang cepat mentransformasi struktur bisnisnya, sekarang kebalikannya, AOL yang kalah cepat mentransformasi struktur bisnisnya. Pelanggan di AOL harus membayar biaya langganan per bulannya untuk dapat mengakses informasi dan jasa pelayanan online lainnya yang ditawarkan oleh AOL. Dengan masuknya pemain baru, seperti Yahoo! dan Google yang menawarkan jasa gratis, AOL harus cepat mengubah struktur bisnisnya jika ingin bertahan.

Ilustrasi ini menunjukkan bahwa perusahaan sekarang menghadapi tantangan yang besar, yaitu transformasi model terus-menerus, menghindari status quo, mengembangkan kemampuan untuk mendeteksi tren yang muncul di masa depan dan mengantisipasinya dengan lebih cepat dibandingkan dengan pesaing-pesaingnya, membuat keputusan yangcepat, melupakan sunk costs, serta membuat model bisnis yang baru.

Perusahaan tidak boleh hanya berdiri memandang tegak kepada pesaingnya. Perusahan harus berdiri tegak memandang dan mengantisipasi masa depan. Perusahaan tidak boleh hanya berfantasi dengan hasil-hasil solusi yang membuai. Perusahaan harus melakukan tindakan perbaikan terus-menerus, inovasi dan cepat, serta mengambil keputusan yang tepat. Jika model bisnis perusahaan sudah ketinggalan dan salah serta dibangun dengan asumsi-asumsi konvensional, perusahaan tidak akan dapat bertahan.

Untuk menghadapi tantangan sekarang ini, untuk dapat bertahan dan memenangkan persaingan, struktur atau model perusahaan perlu dirancang ulang terus-menerus disesuaikan dengan kondisi persaingannya. Untuk melakukan transformasi struktur ini, dapat dilakukan dengan mendisagregasi dan reagregrasi rantai nilai.

#### Nilai dari Suatu Bisnis

Nilai dari suatu bisnis adalah produk atau jasa yang dijualnya dan juga kebutuhan-kebutuhan pelanggan yang disediakannya. Kebutuhan-kebutuhan ini adalah hasil akhir, termasuk produk dan jasa yang akan diterima oleh pelanggan. Disagregrasi rantai nilai adalah memisahkan cara-cara (means) dengan akhir-akhir (ends). Means adalah produk atau jasa yang dijual dan ends adalah kebutuhan-kebutuhan akhir yang diminta oleh pelanggan tidak hanya produk atau jasa yang dijual. Disagregasi membutuhkan perusahaan untuk mengidentifikasikan, menilai, dan memelihara inti dari bisnisnya, yaitu kebutuhan-kebutuhan pelanggan yang dipuaskan lewat produk atau jasa yang dijual dan pelayanan serta informasi di sekitar produk atau jasanya. Cara ini memungkinkan perusahaan untuk mengurai struktur-struktur yang lama, berpikir kembali kemampuan-kemampuan inti, serta mengidentifikasikan bentuk dan sumber-sumber baru dari nilai yang akan diberikan kepada pelanggannya.


#### Reagregasi

Reagregasi berarti mengumpulkan kembali nilai-nilai yang sudah diurai.

Reagregrasi harus diarahkan ke visi yang sudah diperbarui dan berbasiskan pada kebutuhan-kebutuhan pelanggan yang akan dilayani. Reagregasi harus dapat memperlancar arus nilai di rantai nilai secara keseluruhan. Dengan hasil dari agregrasi ini, diharapkan pelanggan akan mendapatkan nilai yang diinginkannya, bahkan akan mendapatkan sesuatu yang lebih dari sebelumnya, lebih nyaman, lebih berinteraksi, serta lebih menantang dan memberikan pengalaman baru kepada pelanggan. Tujuan dari agregrasi ini adalah memberikan nilai lebih epada pelanggan lewat biaya yang lebih murah dan peningkatan diferensiasi dibandingkan dengan pesaing-pesaingnya.

Menggunakan teknologi untuk reagrgrasi di rantai nilai merupakan hal yang sangat fundamental di era ekonomi digital ini.




## 08. Topologi Model Bisnis

Tapscott dkk (2000) menggolongkan tipologi model bisnis secara elektronik (e-business) ke dalam lima macam model berdasarkan tingkat kontrol ekonomis dan tingkat nilai integrasinya.

![[Pasted image 20241123085928.png]]

Tipologi model e-business menurut Tapscott dkk (2000) sebagai berikut.

1. Agora adalah suatu e-commerce yang merupakan suatu tempat ketika pembeli dan penjual bertemu untuk melakukan transaksi. Contohnya, e-bay.com.
2. Agregasi (aggregation) adalah e-commerce yang menggabungkan (agregasi) beberapa pemasok ke dalam satu buah toko online yang nyaman. Contohnya, amazon.com.
3. Aliansi (alliance) adalah kerja sama beberapa anggota untuk mencapai tujuan tertentu.
4. Rantai nilai (value chain) adalah jaringan integrasi vertikal yang menambah nilai ke input berikutnya.
5. Jaringan distribusi (distributive network) menyediakan jasa mengalokasikan dan mendistribusikan daripada memproduksi dan membeli barang-barang, jasa, dan informasi. Contohnya, WSpridCom dan UPS.

Pengelompokan lainnya dari model e-business adalah mengelompokkannya berdasarkan siapa yang berpartisipasi dalam transaksi, yaitu business to consumer (B2C) dan business to business (B2B). Tiga model tersedia untuk B2C sebagai berikut.

#### 1. Toko Online (Online Stores), Pasar (Marketplaces) dan Jasa-Jasa

Toko online, pasar dan jasa-jasa menyediakan hampir semua kebutuhan bahan yang dapat dipilih dan dibeli lewat web. Barang-barang yang tersedia dari komputer, buku, majalah, pakaian, peralatan kantor, jam, musik, video, elektronik, mainan, obat, alat kecantikan, makanan, hingga mobil.

Keuntungan dari toko online ini sebagai berikut:

1. menyediakan informasi produk yang lengkap yang dapat digunakan oleh konsumen untuk mempertimbangkan keputusannya untuk membeli;
2. menyediakan informasi ketersediaan barang; 
3. mengurangi biaya ruangan toko bagi penjual; 
4. biaya mencetak brosur atau katalog dapat dihemat.

#### 2. Pengumpul Isi atau Pengagregasi Isi (Content Aggregators) dan Portal

 Pembeli dapat membandingkan barang-barang atau jasa-jasa yang ditawarkan dan kemudian dapat membeli langsung kepada penjual secara online atau secara manual. Pembeli dapat membeli secara online karena aggregator menghubungkan (link) ke alamat situs web penjual.

#### 3. Penyedia Infrastruktur (Infrastructure Providers)

Sekarang ini banyak perusahaan yang masuk dalam industri teknologi tinggi atau yang terkenal dengan nama perusahaan-perusahaan high-tech industry. Perusahaan-perusahaan ini membangun, menyediakan, dan menjual infrastruktur teknologi jaringan.
Bisnis-bisnis yang menyediakan infrastruktur teknologi seperti berikut:

1. pabrikan-pabrikan peralatandan komponen (equipment/component manufacturers); 
2. perusahaan-perusahaan perangkat lunak (software firms);
3. penyedia-penyedia perangkat lunak khusus dan jasa integrasi (custom software and integration service providers).





## 09. Penciptaan Nilai

Untuk dapat menyediakan kebutuhan-kebutuhan pelanggan (ends), perusahaan tidak hanya harus menyediakan produk atau jasa (means), tetapi juga nilai-nilai berupa pelayanan dan informasi yang disediakan di sekeliling produk dan jasanya. Perusahaan-perusahaan yang visionari, seperti Dell, Amazon.com, dan Domino's Pizza, berhasil karena mereka menyediakan kebutuhan-kebutuhan pelanggannya dengan meningkatkan produk, memotong harga dan meningkatkan kualitas pelayanan terus-menerus.

Nilai-nilai yang dapat disediakan oleh perusahaan di sekitar produk atau jasa yang dijual sebagai berikut:

1. 1. kecepatan layanan,
2. ﻿﻿﻿kecepatan layanan merupakan respons yang cepat, instan, akurat dan adaptif terhadap kebutuhan-kebutuhan pelanggan;perusahaan yang visioner melekatkan kecepatan pelayanan ini dalam produk dan jasa yang dijualnya;
3. nyaman;
4. pelanggan menilai kenyamanan dengan mendapatkan semua hasil dengan sekali belanja (one-stop shopping); pelanggan yang kebutuhan-kebutuhan harus dipenuhi berkali-kali belanja di waktu yang berbeda atau di tempat-tempat berbeda tidak akan merasa nyaman. Mereka akan merasa nyaman jika semua kebutuhannya akan terpenuhi dengan sekali belanja. Ini berarti pelanggan menuntut integrasi yang baik sepanjang rantai nilai;
5. personalisasi;
6. pelanggan menginginkan perusahaan untuk melayaninya secara individual dengan kebutuhan-kebutuhan akhir yang dapat berbeda dengan pelanggan lain;
7. harga;
8. harga produk dan jasa adalah relatif; harga yang ditawarkan harus masuk akal dan harga harus dihubungkan dengan kebutuhan-kebutuhan akhir yang diterima pelanggan dan dapat bersaing dengan harga akhir yang ditawarkan pesaing-pesaingnya.

Perusahaan e-business dapat mempercepat inovasi nilai (value innovation) di sepanjang nilai dimensi jasa, yaitu kecepatan layanan, kenyamanan, personalisasi dan harga. Pelanggan sekarang menghadapi banyak produk yang semacam dengan opsi-opsi pilihan yang banyak dengan harga-harga yang berbeda. Oleh karena kurangnya waktu yang tersedia, pelanggan akan mencari dengan usaha yang paling minimal produk yang termurah dan yang paling terkenal dengan kualitas terbaik. 

Misanya, suatu produk yang harganya Rp10,500,00 (lebih mahal Rp50,00 dari pesaing terdekatnya) kurang terkenal dengan kualitas 97% baik akan kalah dengan produk yang memenuhi satu dari ketiga kriteria tersebut. Oleh karena itu, Kalakota dan Robinson (2001) menunjukkan perusahaan-perusahaan e-business harus mendengarkan pelanggan-pelanggannya serta menciptakan inovasi nilai sehingga menjadi perusahaan "yang termurah" dan "paling dikenal" dengan "kualitas terbaik."

Termurah bukan berarti kualitas yang rendah. Misalnya, Wal-Mart dengan semboyannya every day low prices. Pelanggan yang membeli produk atau jasa dari perusahaan yang "paling dikenal" akan merasa yakin akan apa yang akan diterimanya karena perusahaan tersebut sudah terkenal membuktikan komitmennya. Contohnya, McDonald, Kentucky Fried Chicken, Wendy's, Pizza Hut dan Domino's Pizza di sektor gerai makanan; Coca Cola dan Pepsi di sektor minuman; Yahoo! atau Google di penyedia jasa internet dan sebagainya. Memberikan "kualitas terbaik" berarti memasukkan proses yang berkualitas untuk meningkatkan kualitas akhir, meningkatkan hubungan yang baik dengan pelanggan-pelanggan dan pemasok-pemasok sampai tingkat kerja sama yang menguntungkan, serta saling membantu dan saling percaya. Contohnya adalah American Express yang memberikan jaminan return protection refund, yaitu menjamin akan mengembalikan nilai barang yang dikembalikan jika penjual tidak mau menerima pengembalian barang. Contoh lainnya, Domino's Pizza yang menjamin pengiriman pizza maksimum 30 menit sejak dipesan sampai ke tangan pemesan. Kualitas yang diberikan oleh perusahaan-perusahaan ini akan meningkatkan kepercayaan pelanggan bahwa perusahaan akan melayani dengan kualitas terbaik yang tidak bisa diberikan oleh perusahaan-perusahaan lainnya.




## 10. Etika di E-Business

Sudah mulai dipahami bahwa isu etika akan muncul di penerapan e-business. Permasalahan etika perlu ditangani oleh manajer teknologi informasi. Permasalahan etika dapat terjadi pada pembeli lewat e-business. Jika permasalahan etika tidak ditangani, hal itu dapat mengakibatkan pembeli melalui e-business tidak mau melakukan transaksi bisnis dengan perusahaan. Permasalahan etika yang terjadi di transaksi e-business biasanya adalah menyangkut permasalahan privasi.

Permasalahan privasi muncul jika identitas atau informasi privat atau rahasia pembeli diketahui oleh perusahaan atau karyawan yang tidak berhak. Permasalahan privasi dapat muncul pada saat pembeli mendaftar menjadi anggota e-business, pada saat pembeli melakukan transaksi pembeliannya lewat e-business, pada saat pembayaran lewat sistem pembayaran elektronik, atau penjual melacaknya ke komputer pembeli.

Banyak penjual lewat e-business meminta pembeli menjadi anggota terlebih dahulu sebelum melakukan transaksi. Pada saat pendaftaran menjadi anggota e-business, pembeli diminta untuk memasukkan data pribadinya. Permasalahan privasi muncul jika data pembeli tersebut diketahui oleh orang, misalnya karyawan penjual yang tidak berhak.

Permasalahan privasi juga terjadi pada saat pembeli melakukan transaksi pembelian lewat e-business. Pada saat transaksi, data pribadi pembeli dapat diketahui oleh pihak yang mungkin tidak behak mengetahuinya.

Permasalahan privasi banyak terjadi pada saat pembayaran pembelian lewat sistem pembayaran elektronik (electronic payment). Pada saat pembayaran elektronik ini, pembeli biasanya ditanyakan mengenai informasi indentitanya, informasi privat dan informasi rahasia lainnya. Identitas pembeli yang ditanyakan contohnya adalah nomor pengenal (misalnya nomor KTP), nama dan alamat. Informasi privat itu meliputi tanggal lahir dan nama ibu kandung. Informasi rahasia lainnya yang dapat diketahui oleh orang lain misalnya adalah password atau nomor PIN (personal identification number) dari kartu kredit atau kartu debit. Perusahaan harus memproteksi informasi-informasi tersebut untuk keamanan dan privasi pembeli.

Permasalahan privasi dapat juga muncul jika perusahaan dengan sengajam melakukan pelacakan ke komputer pembeli. Jika pembeli pernah mengunjungi situs penjual, penjual dapat menanamkan cookies di komputer pembeli. Cookies adalah program keil yang disimpan di browser pembeli. Cookies ini akan merekam sejarah transaksi pembeli. Bahkan, lebih buruknya, cookies dapat berisi dengan program parasit yang disebut dengan spyware untuk memata-matai, melacak dan merekam informasi privat lainnnya di komputer pembeli. Nantinya, jika pembeli mengunjungi situs penjual kembali, komputer penjual akan mengetahui dengan perinci siapa pembelinya dengan membaca data personal di filecookies. Beberapa pemakai komputer merasa terganggu dengan hal ini. Pemakai komputer dapat menggunakan program-program untuk mencegah atau menghapus file cookies dan program parasit spyware. Program-program ini misalnya adalah CookieCrusher, CCleaner, SlimCleaner, AdAware dan lainnya.