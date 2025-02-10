---
tags:
  - algoritma_pemprograman
  - materi_2_AP
---

# Kegiatan Belajar 2 - Pseudocode

Bahasa pemrograman yang banyak digunakan saat ini sudah menggunakan

keyword bahasa alamiah (natural language); hal ini berbeda dengan bahasa pemrograman pada saat pertama kali komputer digunakan, yang pada saat itu menggunakan bahasa mesin. Pada saat ini, kita bebas dalam menetapkan nama variabel dengan mengikuti kaidah yang telah ditetapkan, misalnya saja variabel dengan nama "kecepatan", "tinggi", "berai", "luas".

Pernyataan-pernyataan dalam bahasa pemrograman, pada umumnya menggunakan bahasa Inggris untuk keyword-nya. Namun untuk kata/kalimat dalam setiap baris pada pseudocode boleh menggunakan kata/kalimat yang dari bahasa yang dikuasai.


## [[04. Kalimat Deklaratif]]

Bagi analis/programmer yang sudah terbiasa dengan penggunaan bahasa Inggris maka dapat dengan mudah membuat pseudocode dengan keyword mendekati bahasa pemrograman pada umumnya, dan ini merupakan nilai tambah bagi analis/programmer yang berasal dari negara-negara yang berbasis bahasa Inggris. Namun kita tidak harus kecewa dengan itu semua.

Analis atau programmer yang lahir di Indonesia dengan latar belakang bahasa Indonesia sangat boleh menggunakan bahasa Indonesia dalam membuat pseudocode. Jika nanti ada beberapa kata-kata bahasa Inggris dalam contoh-contoh kasus, semata-mata karena penulis ingin menggiring pembaca untuk lebih awal mengenali perintah-perintah dalam bahasa pemrograman Java, misalnya kata-kata "if", "else", "else if", "while", "do while" ', "loop", dan lain-lain, akan tetapi kata-kata seperti "Add" atau "Divide", ', bisa diganti dengan "Tambahkan" atau "Kalikan", atau bagi variabel yang sifatnya deklaratif, kita bisa menggunakan variabel berbahasa Indonesia.



## [[05. Definisi Pseudocode]]

Pseudocode adalah deskripsi tingkat tinggi dan singkat (ringkas) yang ditulis untuk dibaca oleh manusia dan bukan untuk dibaca oleh mesin (kompilator). Anda dapat menganggap pseudocode sebagai "kode bahasa Inggris" atau "kode bahasa Indonesia" atau yang lainnya yang dapat dipahami oleh siapa pun (bukan hanya ilmuwan komputer). 

Walaupun pseudocode adalah sebuah narasi yang pendek-pendek (khusus) dan sudah mirip-mirip dengan bahasa pemrograman akan tetapi tidak terikat oleh bahasa pemrograman apapun, akan tetapi pseudocode dapat dikonversi ke bahasa pemrograman apapun, apalagi bahasa pemrograman tingkat tinggi, seperti Java, Pascal/Delphi, Visual Basic, C++.



## [[06. Cara Menulis Pseudocode]]

Tidak ada aturan baku yang mengikat cara menulis pseudocode, namun, ada standar yang bisa diterima secara umum. Seorang pembaca harus dapat mengikuti pseudocode dan mampu mengerti dengan baik apa yang diinginkan, sehingga dengan mudah menerjemahkan permasalahan dengan cara pemecahan pada setiap langkah-langkah yang ada. Setelah menulis pseudocode, seharusnya progammer jauh lebih mudah mengkonversi ke dalam bahasa pemrograman.

Penulisan pseudocode dari langkah pertama, mungkin terlihat biasa saja atau mengikuti alur yang ada, akan tetapi pada blok tertentu anda bisa membuat indentasi (tulisan menjorok kedalam) untuk menggambarkan blok kode, sehingga jelas garis mana di dalam method, loop, dan lain sebagainya.

Indentasi sangat penting untuk menulis pseudocode. Dalam bahasa pemrograman tidak memperdulikan tidak peduli jika setelah penyataan if menjorok ke dalam atau tidak pada penulisan, tetapi pembaca manusia/programmer akan benar-benar kehilangan jejak tanpa tanda indentasi. 

Penulisan pseudocode tidak boleh membuat programmer kesusahan dalam mengidentifikasi setiap langkah, sehingga penyertaan nomor urut pada setiap langkah menjadi sangat penting, bahkan jika dalam satu sub blok indentansi, diberikan dengan nomor urut yang anak beranak, misalnya suatu blok dimulai dari nomor urut 6, maka indentasi biasanya diberikan nilai 6.1 atau 6.a (sub urut). Ingat! Pemahaman manusia adalah inti dari pseudocode.

Walaupun dalam menyusun pseudocode tidak mempunyai aturan baku yang mengikat, namun beberapa panduan umum yang sering digunakan dalam membuat pseudocode sebagai berikut:

#### 6.1. Dituliskan dalam bahasa yang sederhana

Dituliskan dalam bahasa yang sederhana dan mudah dimengerti, setiap penulisan boleh 1. dimulai dengan kata kata "Mulai" dan diakhiri dengan kata "Selesai"

#### 6.2 Notasi ←

Notasi ← digunakan untuk mengisi nilai pada sebuah variabel, contoh:
![[Screenshot 2025-02-02 at 10.10.43.png]]

Semua apa yang ada di belakang notasi ← adalah nilai yang akan diisi kedalam variabel yang ditujunya (variabel sebelah kiri, jarak, waktu, kecepatan dan percepatan).

#### 6.3 Independen

Setiap pernyataan atau intruksi dapat independen atau ditulis dalam baris sendiri, contoh:
![[Screenshot 2025-02-02 at 10.11.21.png]]

#### 6.4 Variabel Skalar

Disarankan (tidak wajib diikuti) untuk variabel skalar menggunakan huruf kecil, variabel skalar adalah variabel menyimpan nilai yang dapat berubah nilainya, contoh:

![[Screenshot 2025-02-02 at 10.11.46.png]]
Variabel v, tentu sangat bisa berubah nilainya, tergantung nilai yang diberikan pada variabel s dan t. Atau perubahan nilai v bisa terjadi jika pada instruksi berikutnya.


#### 6.5 Variabel Larik

Disarankan (tidak wajib) untuk variabel larik (array), menggunakan huruf besar semua atau menggunakan huruf besar di depannya, contoh:

![[Screenshot 2025-02-02 at 10.12.43.png]]

Misalnya: Variabel L ← [2,3,4], berisi tiga buah angka yaitu 2, 3, dan Angka 2 elemen pertama, angka 3 elemen kedua, dan 4 elemen ketiga dari variabel L.

#### 6.6 Notasi Larik  L[i]

Notasi seperti L[i], menyatakan elemen ke-i dari variabel larik L, Larik selalu dimulai dari 0 (Nol), sehingga L[®] merupakan elemen pertama dari variabel L. Sedangkan untuk bernotasi L[i,j], dengan i adalah indeks untuk baris, dan j adalah indeks untuk kolom, contoh: 4[®, 1] maka dibaca dengan variabel L pada bari ke-0, kolom ke-1.


#### 6.7 Notasi  jumLahELemen$(**l**)$

Notasi $jumlahElemen(**l**)$ digunakan sebagai ekspresi untuk mendapatkan jumlah elemen larik.


#### 6.8 Variabel Majemuk
Variabel majemuk yang digunakan untuk menyimpan tipe majemuk yang dapat menyimpan beberapa jenis data sekaligus, contoh penggunaan:

![[Screenshot 2025-02-02 at 10.16.12.png]]

#### 6.9 Menyertakan Nomor Urut

Bisa menyertakan nomor urut pada setiap baris, baik pernyataan ataupun komentar, jika dalam pseudocode mengandung sub-blok, maka disarankan ditandai dengan indentasi, misalnya penggunaan if:

![[Screenshot 2025-02-02 at 10.17.16.png]]


#### 6.10 Pembacaan Dilakukan Secara Berurut

Pembacaan pseudocode dilakukan secara urut, jika suatu kondisi harus lompat ke urutan tertentu, maka harus ditulis lompatnya kemana.  

Contoh dari langkah 2.2, karena kondisi tertentu harus lompat ke langkah 3, maka harus dituliskan lompat ke langkah 3 atau Go to step 3.


#### 6.11 Commentator

Simbol $//$ atau $/* ... */$ digunakan untuk komentar, contoh:

![[Screenshot 2025-02-02 at 10.18.48.png]]

#### 6.12 Baris Instruksi Harus Jelas

Setiap baris instruksi harus jelas, misalnya: sebuah variabel menyertakan tipe datanya.

![[Screenshot 2025-02-02 at 10.19.16.png]]

#### 6.13 Notasi ()

Notasi masukan(), input(), tampilkan(), cetak(), atau print() mewakili I/O. Contoh:
![[Screenshot 2025-02-02 at 10.20.08.png]]

Notasi di atas mulai semakin semakin beragam, apalagi pembuat pseudocode terafiliasi dengan bahasa pemrograman tertentu, sehingga membuat beragam untuk sebuah masukan atau


#### 6.14 Logika

Untuk Logika, jika pernah belajar logika informatika, maka dengan mudah memahami sebuah logika nilainya hanya "Benar/true" atau "Salah/false". Jika komponen tersebut adalah sebuah operator pembanding maka operatornya berikut:

![[Screenshot 2025-02-02 at 10.21.04.png]]

#### 6.15 While/Loop

Pseudocode untuk perulangan (while-loop), selama kondisi bernilai benar (true), maka perulangan akan dijalankan terus:
![[Screenshot 2025-02-02 at 10.21.29.png]]

#### 6.16 Do-Loop

Pseudocode perulangan (do-loop), blok perulangan akan berjalan minimal sekali, baru kemudian melakukan pengecekan benar (true) atau salah (false), jika kondisi benar maka akan terus melakukan perulangan.

![[Screenshot 2025-02-02 at 10.21.58.png]]

#### 6.17 For-Loop

Untuk perulangan (for-loop), sebuah perulangan akan berhenti selama nilainya sampai pada akhir yang ditentukan, misal 1 sampai 10, maka akan melakukan perulangan sampai 10.

![[Screenshot 2025-02-02 at 10.22.27.png]]

#### 6.18 Prosedur, Fungsi, Methode

![[Screenshot 2025-02-02 at 10.22.54.png]]
Begitu juga dengan fungsi/method, atau sebuah class ataupun sub-class.


#### Contoh 1:

Mari kita lihat contoh pseudocode dan bagaimana bentuk asli dalam bentuk bahasa pemrograman Java untuk mencari kecepatan dan percepatan, sebagai berikut:

![[Screenshot 2025-02-02 at 10.23.17.png]]

Pseudocode di atas adalah pseudocode sangat ideal, begitu gamblang dan jelas dalam penyajian baris demi baris, mulai dari penamaan proses (pada Java akan membuat class MencariKecepatandanPercepatan), variabel-variabel yang digunakan dan lengkap dengan tipe datanya, formulasi kecepatan dan percepatan jelas, kemudian tahap akhir adalah menampilkan hasil. 

Proses demi proses bercerita dan memberikan instruksi yang sangat informatif, khususnya kepada programmer karena sudah tahu apa yang harus dikerjakan, tidak perlu mengorek informasi lebih jauh tentang variabel, formulasi dan hasil akhir akan dicetak atau tidak. Jika algoritma di atas ditransformasi ke bahasa Java, maka hasilnya sebagai berikut:

![[Screenshot 2025-02-02 at 10.23.44.png]]

Mari mengoreksi baris demi baris pseudocode yang tidak ideal di atas,

sebagai berikut:

1. ﻿﻿﻿Baris 1 dan 2: tidak ada masalah karena cukup informatif
2. ﻿﻿﻿Baris 3: programmer bisa saja membuat variabel dan tipe data dan mengantisipasi tipe data dengan tipe data float jika ada hasil pembagian.
3. ﻿﻿﻿Baris 4: mulai timbul pertanyaan, berapa variabel harus dibuat untuk di inisisasi, bisa saja programmer buat 1, 2, 5, atau 10 variabel, kemudian di inisiasi awal dengan angka sembarang, programmer akan berpikir berapa variabel dan apa tipe data yang harus digunakan.
4. ﻿﻿﻿Baris 5 dan 6: Programmer akan sangat bingung, formulasi kecepatan dan percepatan seperti apa? Apakah betul semua programmer mengetahui formulasi kecepatan dan percepatan dalam ilmu fisika?  Tentu tidak!, Artinya bahwa programmer masih butuh informasi tambahan.
5. ﻿﻿﻿Baris 7 dan 8: nilai kecepatan dan percepatan akan ada jika baris baris 5 dan 6 bisa diselesaikan.
6. ﻿﻿﻿Baris 9: hanya penutup proses.

Melihat langkah-langkah pseudocode yang tidak ideal di atas akan memberikan sebuah pertanyaan besar, yaitu: Variabel apa saja yang dibutuhkan untuk mencari kecepatan dan percepatan serta apa tipe datanya apa? Bagaimana mungkin bisa mencari kecepatan dan percepatan jika saya tidak mengetahui formulasi? Hal ini adalah sinyal/indikasi bahwa pseudocode tersebut tidak cukup detail. Berinisiatif untuk membangun deklarasi variabel tidak akan pernah memecah kebingungan dan kebuntuan yang ada.



## [[07. Struktur Pseudocode]]

Melihat beberapa pseudocode dari buku, internet atau dari analis, ditemukan beragam cara penyajian pseudocode, ada yang menggunakan nomor urut dan ada yang tidak, ada yang sudah menggunakan pernyataan yang mirip dengan bahasa pemrograman tertentu, bahkan ada yang hanya menyertakan prosesnya saja, ada yang menyertakan lengkap seperti tipe data dari variabel, ada yang mencampurkan bahasa Inggris dengan bahasa Indonesia, dan berbagai variasi lainnya. 

Kita harus menerima fakta bahwa sulit untuk menerapkan suatu standar tertentu apabila kita sudah berkiblat kepada sebuah bahasa pemrograman tertentu dan melihat latar belakang para analis yang amat berbeda. Oleh karena itu suatu pseudocode diusahakan untuk dibuat mendekati standar agar dapat mudah dipahami oleh para programer.

Tentu kita tidak bisa memaksakan sebuah struktur yang baku, mengingat karakteristik setiap bahasa pemrograman yang tersedia memiliki beberapa perbedaan. Tidak ada bahasa pemrograman yang benar-benar sama persis.

Beberapa bahasa pemrograman memiliki kemiripan, misalnya: bahasa pemrograman Java dan Pascal. Secara subtansi kedua bahasa pemrograman ini mempunyai karakteristik yang berbeda, contoh: Dalam mendeklarasikan variabel, Pascal medeklarasikan variabel di luar blok program (begin...end;), di sisi lain bahasa Java bebas dalam lokasi mendeklarasikan variabel, bahkan dalam blok ((.../) program sekalipun tetap diijinkan. Inti dari pseudocode adalah mampu dibaca oleh programmer atau bukan programmer dengan tanpa perlu mempelajari ilmu tertentu untuk bisa mengerti.

Secara umum, dapat dikatakan bahwa pseudocode bisa distrukturkan sebagai berikut: dimulai dengan Judul (Nama Program, class), Deskripsi (Deklarasi), Implementasi (Inti dari Algoritma).

![[Screenshot 2025-02-02 at 10.25.28.png]]



## [[08. Perbedaan Gaya Penulisan Pseudocode]]

Pseudocode sangat dekat dengan prosa bahasa Inggris, misalnya pernyataan "while", "if", "else" dan sebagainya. Namun kita masih diijinkan untuk membuat suatu toleransi selama memungkinkan dan khalayak umum mampu memahami maksud dan tujuan dari pernyataan tersebut. Gaya pseudocode sangat bergantung pada preferensi pribadi, masalah yang ingin dipecahkan. Makin sering Anda membuat/menulis pseudocode maka Anda akan menemukan gaya apa yang paling alami dan paling cocok bagi Anda.




## [[09. Contoh Algoritma dengan Pseudocode]]

#### 9.1 Contoh 1 - Algoritma untuk mencari bilangan ganjil dari 1 sampai 10

Sebagai bahan pengayaan, berikut ini diberikan contoh pseudocode. Algoritma untuk mencari bilangan ganjil dari 1 sampai 10 Pada pseudocode berikut adalah untuk mencari bilangan ganjil dari angka 1 sampai dengan angka 10, tentu yang dicari adalah 1, 3, 5, 7, dan 9. Pseudocode-nya sebagai berikut

![[Screenshot 2025-02-02 at 10.27.00.png]]

Untuk baris 1 sampai dengan baris 7, sudah sangat jelas, pada baris 8 mengandung indentasi 8.1 hingga 8.3 dapat dikatakan satu blok yang utuh.

Untuk 8.2 mempunyai sub indentasi 8.2.1 memberikan informasi jelas merupakan sub blok dalam satu blok.

Perulangan (lihat While... pada baris 8) adalah membentuk blok indentasi, minimal 1 indentasi dalam bloknya (bloknya 8.1 hingga 8.3), kemudian untuk kondisi (lihat if... pada baris indentasi 8.2), minimal memiliki 1 indentasi dalam bloknya.

Sekarang kita masuk kepada subtansi algoritma, kenapa harus menggunakan algoritma untuk mencari nilai ganjil dari angka 1 sampai 10?

Terkadang pertanyaan sepele seperti ini sering muncul dan menyepelekan hasil karya orang lain, tanpa berpikir panjang bahwa seandainya data yang dikerjakan bukan hanya l sampai 10, akan tetapi sampai 100, 500, 1000, atau 10.000, tentu akan sangat merepotkan jika harus mencari satu per satu.

Sangat gampang menemukan dan menuliskan jika datanya hanya 1 sampail0, dimana hasilnya adalah 1, 3, 5, 7, 9. Tetapi akan memerlukan waktu yang lama untuk menemukan angka ganjil antara 1 sampai 1000. Nah disinilah fungsinya algoritma dan bahasa program. Anda hanya menginput nilai dan selanjutnya menekan tombol enter, hasilnya keluar kurang dari 1 detik.

Pseudocode mengurutkan data di atas jika ditransformasi kedalam bahasa pemrograman Java, maka bentuknya seperti berikut:
![[Screenshot 2025-02-02 at 10.27.46.png]]

![[Screenshot 2025-02-02 at 10.27.58.png]]

#### 9.2 Contoh 2 - Algoritma untuk mengurutkan data

Mungkin anda pernah menggunakan Microsoft Office Excel, dalam satu kolom terdapat data random (tidak berurutan), pada Excel terdapat fungsi untuk mengurutkan data dengan nama fungsi "Sort & Filter".

![[Screenshot 2025-02-02 at 10.28.48.png]]

Gambar 2.2 adalah data di aplikasi excel, data sebelah kiri adalah data yang belum disortir, dan yang sebelah kanan adalah data yang sudah disortir. Fungsi "Sort & Filter" sangat mudah dan sederhana penggunaannya. Di dibalik kemudahan penggunaan fungsi sortir, tersimpan algoritma pengurutan data.

Contoh kasus lain misalkan kita mempunyai sekumpulan data random yang belum terurut, adapun data-data tersebut adalah sebagai berikut: 3, 1, 6, 4, 6, 7, 2, 5, 6, 3. Buatlah pseudocode untuk mengurutkan data.

![[Screenshot 2025-02-02 at 10.29.25.png]]

Pseudocode di atas, walau belum memiliki kerumitan penyelesaian tinggi, tetapi sudah memiliki indentasi dengan 3 kedalaman, yaitu: 8.1.2.1, 8.1.2.2, dan 8.1.2.3. Jika dirasa indentansi seperti ini terlalu panjang, maka bisa menyingkat dengan 8121, 8122, dan 8123, atau jika merasa terlalu panjang, maka bisa menggantinya dengan huruf, misalnya:

![[Screenshot 2025-02-02 at 10.29.46.png]]
![[Screenshot 2025-02-02 at 10.30.03.png]]

Dua contoh pseudocode di atas, akan sangat mudah dibaca oleh programmer secara sistematis dan jika pseudocode tersebut ditransformasi ke dalam bahasa pemrograman Java, maka hasilnya sebagai berikut:

![[Screenshot 2025-02-02 at 10.30.22.png]]
![[Screenshot 2025-02-02 at 10.30.31.png]]


