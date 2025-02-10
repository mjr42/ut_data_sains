---
tags:
  - algoritma_pemprograman
  - materi_1_AP
---
# Kegiatan Belajar 2 - Struktur Dasar Algoritma

Ketika ingin membangun bangunan rumah hal yang paling pertama yang harus dipikirkan adalah kontruksi dasar, seperti pondasi, balok beton dan konstruksi dinding, hal sama juga dengan membangun sebuah algoritma harus tahu struktur dasarnya. Ada tiga struktur dasar dalam algoritma yaitu: skuesial (squenstial), seleksi (selection), dan perulangan (looping).

## [[08. Sekuensial]]

Struktur dasar skuensial adalah sebuah algoritma dibangun dengan langkah-langkah (instruksi/perintah) dikerjakan secara berurutan, tidak boleh melompati satu langkah perintah pun. Misal dalam sebuah algoritma terdapat 20 langkah, maka semua langkah tersebut dikerjakan berurutan mulai dari langkah 1 sampai pada langkah 20 tanpa melewatkan satu langkah pun.

Cara kerja skuensial juga nantinya berlaku dalan bahasa pemrograman, ketika instruksi bahasa pemrograman yang kita tulis diproses oleh komputer, maka komputer akan memproses dan menterjemahkan baris demi baris intruksi-instruksi bahasa pemrograman tersebut secara beruntun dari awal hingga akhir dimulai dari instruksi pada baris awal hingga baris akhir.

Dengan struktur skuensial ini, pembuat algoritma harus mampu menganalisa dan menentukan intruksi mana yang harus ditulis lebih awal dan seterusnya dan yang mana harus paling akhir.

![[Screenshot 2025-02-02 at 09.21.56.png]]

Pada Gambar 1.3 adalah contoh algoritma dengan skuensial untuk mencari kecepatan dan percepatan, tidak ada satupun proses yang terlewatkan atau melompati proses yang ada di bawahnya, semua dikerjakan secara berurutan.

Demikian juga dengan intruksi yang ada di dalam prosesnya, misalnya rumus hitung pecepatan (a) tidak mendahului proses perhitungan kecepatan (v), hal ini karena untuk mencari percepatan harus mencari atau menghitung kecepatan terlebih dahulu.

#### 8.1 Pseudocode

Jika struktur dasar skuensial direprestasikan menjadi algoritma pseudocode, urutan pekerjaannya akan sama. Perhatikan pseudocode mencari kecepatan dan percepatan di bawah ini:
![[Screenshot 2025-02-02 at 09.22.34.png]]






## [[09. Seleksi]]

Pada kenyataannya banyak algoritma setidaknya akan mengandung proses seleksi (selection) pada intruksi-intruksi pada tubuh algoritma, instruksi seleksi digunakan apabila menemukan/memiliki kasus dua atau lebih alternatif penyelesaian/keputusan.

![[Screenshot 2025-02-02 at 09.23.40.png]]

Gambar 1.4 adalah contoh algoritma penyelesaian dengan seleksi dua keputusan. Ada dua angka yang akan diseleksi dengan membandingkan keduanya mana yang terbesar/sama dengan atau terkecil. Misal nilai a = 6 dan nilai b = 5, maka seleksinya adalah akan tercetak "Nilai a >= b" dan jika sebaliknya maka keputusan yang lain adalah tercetak "Nilai a < b".

#### 9.1 Pseudocode

![[Screenshot 2025-02-02 at 09.24.22.png]]
![[Screenshot 2025-02-02 at 09.25.55.png]]

Dalam dunia algoritma dan pemrograman akan sering diperhadapkan kondisi seleksi seperti contoh di atas, baik tipe kasusnya sama maupun berbeda.




##  [[10. Perulangan (Looping)]]

Struktur algoritma yang ketiga adalah perulangan. Banyak hal terjadi di dunia ini berulang-ulang, kita bisa menghafal sesuatu salah satu cara adalah mengulang, materi yang diberikan dikelas oleh guru atau dosen mugkin tidak serta merta langsung bisa dimengerti, akan tetapi melakukan pengulangan materi yang pernah diberikan sebelumnya bisa menjadi efektif untuk memahaminya/menghafalnya.

Perulangan dalam algoritma sangat dibutuhkan untuk menyelesaikan banyak masalah. Pengurutan data yang banyak dalam program tertentu itu karena andil sebuah algoritma perulangan. Bayangkan jika harus menuliskan angka 1 sampai 100 dengan manual dalam sebuah program, akan memakan waktu, akan tetapi dengan menggunakan algoritma perulangan dalam progam hanya terdiri dari 4 langkah intruksi dalam algoritma sudah bisa menyelesaikan/menampilkan angka 1 sampai 100 bahkan lebih. Anda pernah menggunakan aplikasi/teknologi kecerdasan buatan pengenalan wajah atau sidik jari dari smartphone anda? Yakinlah bahwa didalamnya terdapat banyak perulangan.

Di atas sudah saya sebutkan bahwa algoritma sendiri untuk mengatasi kasus pengulangan data, memiliki intruksi tersendiri, dengan intruksi tersebut pengulangan akan lebih mudah ditulis secara singkat dan praktis daripada harus di tulis satu-persatu. Akan saya berikan satu contoh flowchart untuk menuliskan angka 1 sampai dengan angka 5, sebagai berikut:

![[Screenshot 2025-02-02 at 09.26.41.png]]

Gambar 1.5 secara sekilas tampak tidak ada masalah, kenapa? Sebab angka yang dicetak masih sedikit, tapi coba dibayangkan jika harus mencetak angka 1 sampai angka 100 dengan mengikuti pola pada Gambar 1.5, tentu cara seperti ini tidak efektif, kenapa? Berapa anda harus membuat 102 simbol (termasuk simbol mulai dan selesai) dalam flowchart hanya untuk mencetak angka 1 sampai 100. Tentu flowchart di atas sangat tidak efektif.

Lalu apakah ada cara yang efektif? Cara yang efektif adalah dengan algoritma perulangan. Di bawah disajikan contoh flowchart mencetak angka 1 sampai 100 dengan kolaborasi antara algoritma perulangan dengan algoritma seleksi:

![[Screenshot 2025-02-02 at 09.27.08.png]]

Sekarang bandingkan Gambar 1.5 dan Gambar 1.6. Gambar 1.5 hanya bisa mencetak angka 1 sampai 5, jika ingin cetak angka lebih dari 4 maka wajib menambahkan simbol flowchart baru. Sedangkan untuk Gambar 1.6 bisa mencetak angka 1 sampai angka 100, lalu bagaimana kalau kita ingin mencetak angka sampai 1000 untuk Gambar 1.6? jawabannya adalah tidak perlu menambah simbol flowchart baru, akan tetapi cukup mengubah b = 1000, cukup efektifkan?


#### 10.1 Pseudocode

![[Screenshot 2025-02-02 at 09.27.29.png]]
![[Screenshot 2025-02-02 at 09.27.38.png]]

Bagaimana proses perulangan berjalan pada flowchart Gambar 1.6 atau pseudocode perulangan? Berikut penjelasannya. Tahap awal variabel a diisi 1 dan variabel b diisi 100, (Perulangan Pertama) kemudian variabel a diisi dengan a = a + 1, sehingga a = 1, karena a = a + 1 sama dengan a = 0 +1.

Langkah berikutnya a diuji dengan b, apakah a > b atau 1 > 100, tentu jawabannya salah atau "Tidak", ', karena hasil selekasi adalah "Tidak" maka variabel a dicetak. (Perulangan Kedua) Dan kemudian kembali ke a = a + 1 atau a = 1 + 1 sehingga a = 2, proses ini akan berulang dan mencetak angka 100 hingga sampai memenuhi kondisi a > b benar atau "Ya" dan algoritma perulangan selesai.