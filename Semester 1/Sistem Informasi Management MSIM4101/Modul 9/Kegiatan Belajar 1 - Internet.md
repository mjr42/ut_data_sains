---
tags:
  - sistem_informasi_management
  - materi_9_SIM
---
# Kegiatan Belajar 1 - Internet

Sistem informasi mulai menghubungkan dua atau lebih organisasi. Bentuk sistem ini disebut dengan interorganizational systems, Salah satu aplikasi dari inter-organizational systems adalah electronic data interchange (EDI).

Dalam praktiknya, aplikasi EDI dapat menggunakan jalur telepon biasa, value added network atau menggunakan internet sebagai jalur komunikasinya. Aplikasi EDI dengan internet mulai banyak diterapkan. Tidak hanya aplikasi EDI yang mulai menggunakan internet, tetapi hubungan ke pelanggan pun mulai menggunakan internet.

## [[01. Jejaring Komputer]]

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



## [[02. Domain Internet]]

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




## [[03. Protokol Internet]]

Kemampuan komputer untuk berkomunikasi dan berbagi komunikasi satu dengan yang lainnya disebut dengan connectivity. Untuk mencapai connectivity, dibutuhkan standar komunikasi data yang disebut dengan protocol.

Protocol adalah suatu kumpulan aturan yang berhubungan dengan komunikasi data antara alat-alat komunikasi supaya komunikasi data dapat dilakukan dengan benar. Jabat tangan merupakan contoh dari protocol antara dua manusia yang akan berkomunikasi. Di istilah komputer, jabat tangan (handshaking) menunjukkan suatu protocol dari komunikasi data apabila dua buah alat dihubungkan satu dengan yang lainnya untuk menentukan bahwa keduanya telah kompatibel. Supaya kompatibel, pada waktu transmisi data, keduanya harus mempunyai transfer rate (tingkat pengiriman) yang sama, format datanya harus sama, tipe transmisinya harus sama, dan mode transmisinya juga harus sama.

Berita-berita elektronik (electronic messages) dikirimkan di internet dalam bentuk paket-paket (packets). Internet membutuhkan suatu protokol (protocol) untuk mengontrol pengiriman paket-paket ini supaya dapat diterima dengan baik oleh komputer penerima. Protokol (protocol) adalah suatu kumpulan aturan-aturan yang mengendalikan sistem-sistem yang berhubungan sehingga dapat beroperasi dan berkomunikasi dengan kompatibel dan lancar. Protokol di internet diorganisasikan dalam bentuk lapisan-lapisan. Lapisan tingkat paling bawah adalah protokol internet (internet protocol atau IP) dan transmission control protocol (TCP).Bersama-sama dengan internet protocol (IP), protokol-protokol ini disingkat menjadi TCP/IP yang mempunyai tugas meyakinkan bahwa paket-paket berita-berita elektronik dikirimkan dan diterima dengan benar dari satu sistem komputer ke sistem komputer yang lain. Protokol yang tingkatannya lebih tinggi adalah file transfer protocol (FTP) yang digunakan untuk memuat (uploading) berkas-berkas (files) yang akan dikirim dan mengambil (downloading) berkas-berkas (files) yang sudah diterima. Protokol tingkat lebih tinggi lainnya adalah simple mail transfer protocol (SMPT) untuk mengirim e-mail dan TELNET untuk emulasi terminal jaringan.



## [[04. World Wide Web]]

World wide web atau WWW atau W3 atau cukup disebut dengan web (dalam bahasa Indonesia diusulkan menjadi JJJ atau jelajah jagat jembar atau jaringan jagat jembar) merupakan suatu sistem informasi multimedia yang memanfaatkan internet untuk mempublikasikan informasi. Informasi multimedia di WWW dibuat dengan menggunakan hypertext. Dokumen hypertext disimpan di server web (misalnya di geocities.com) dan diakses dengan menggunakan browser

Dua hal yang berhubungan dengan hypertext adalah hypertext transfer protocol (HTTP) dan hypertext markup language (HTML). Informasi tentang web ini dapat diakses di www.w3.org-

### HTTP

Hypertext transfer protocol (HTTP) adalah protokol (kumpulan dari aturan komunikasi) yang mengatur komunikasi antara serverweb dan web browser. Tiap-tiap dokumen web mempunyai sebuah alamat yang disebut dengan uniform resource locator (URL). Untuk mengakses suatu dokumen web, dapat dituliskan URL, misalnya http:// temple.edu/index.html. Pertama, kata http: menunjukkan bahwa URL akan diakses dengan menggunakan HTTP (halaman web dapat juga diakses dengan protokol lain, misalnya menggunakan FTP: atau GOPHER:). Kata kedua setelah // adalah alamat dari server, yaitu temple.edu. Kata terakhir, yaitu /index.html adalah lokasi dari dokumen web.

#### HTML

Hypertext markup language (HTML) merupakan bahasa yang digunakan untuk menentukan isi dan struktur dari halaman-halaman web. Bahasa HTML ini berkembang terus seiring dengan berkembangnya websites (situs-situs web yang semakin banyak dibuat). Generasi baru dari bahasa HTML ini adalah extensible markup language (XML) dan penerapannya dipelaporan akuntansi, yaitu extensible business reporting language (XBRL).

#### XML

Dengan extensible markup language(XML), nilai data dapat dituliskan di halaman web dengan menggunakan nama variabel. Misalnya, statesmen<LABA-PERLEMBAR="Rp">7500</LABA-PERLEMBAR> menunjukkan bahwa laba per lembar saham perusahaan yang laporan keuangannya ditampilkan di web ini adalah sebesar Rp 7500,00. Dengan keluwesan seperti ini, search engine dapat diprogram untuk mencari situs-situs web yang menampilkan laporan keuangan untuk perusahaan-perusahaan dengan nilai LABA-PERLEMBAR tertentu (misalnya yang lebih besar dari Rp 5000,00) dan kemudian nilainya dapat disimpan di basis data. Perusahaan perangkat lunak Microsoft dan IBM sedang bekerja sama dengan industri akuntansi dalam pelaporan-pelaporan keuangan untuk mengembangkan XML sebagai pelaporan bisnis yang disebut dengan extensible business reporting language (XBRL). XBRL ini gratis dan informasi lebih lanjut dapat dilihat di www.xbrl.org.



