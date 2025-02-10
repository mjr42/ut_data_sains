---
tags:
  - algoritma_pemprograman
  - materi_2_AP
---
# Kegiatan Belajar 1 - FlowChart

Flowchart adalah jenis diagram (grafis atau simbolik) yang mewakili suatu algoritma atau proses-proses tertentu. Setiap langkah dalam algoritma diwakili oleh simbol yang sama atau berbeda dan berisi penjelasan singkat setiap langkah. Simbol flowchart dihubungkan dengan garis dan panah yang menunjukkan arah aliran proses. Suatu diagram alur biasanya menunjukkan aliran data dalam suatu proses, merinci operasi/langkah dalam format bergambar agar lebih mudah dipahami dibanding dengan membacanya dalam format tekstual.

Flowchart menggambarkan bentuk operasi dalam urutan proses yang diperlukan untuk memecahkan masalah yang diberikan. Flowchart dapat disamakan dengan cetak biru (bluprint) bangunan atau cetak biru pesawat.

Seperti kita ketahui, seorang desainer pesawat menggambar cetak biru sebelum memulai pembuatan sebuah pesawat. Demikian pula seorang analis atau seorang pembuat algoritma lebih suka menggambar flowchart untuk memahamkan kepada orang awam atau kepada programmer sebelum programmer menuliskannya kedalam program. 

Flowchart adalah representasi gambar atau grafis dari suatu proses. Tujuan dari semua flowchart adalah untuk mengkomunikasikan bagaimana suatu proses bekerja tanpa peristilahan teknis atau peristilahan yang hanya dipahami suatu kelompok tertentu.

Flowchart merepresentasikan algoritma dalam bentuk desain, simbol dan dijadikan dokumentasi dan kemudian dituangkan menjadi kode-kode program. Flowchart umumnya digambar pada tahap awal pengembangan program sehingga dapat menjadi suatu gambaran aliran fungsi kerja suatu program komputer. 

Hadirnya flowchart dapat membantu programmer untuk memahami permasalahan yang ada dan target yang dikehendaki secara logika, walaupun suatu masalah cukup rumit dan kompleks, tapi setelah flowchart dibuat, programmer tidak kesusahan menuliskannya ke dalam program dalam bahasa pemrograman apa pun. 

Teks program yang dibuat oleh orang lain tanpa ada dokumentasi dalam bentuk flowchart atau apapun namanya, kadang sulit untuk memahami alur prosesnya. Sebaliknya, menerangkan atau memahami sebuah flowchart jauh lebih mudah walau sesulit apapun permasalahannya.

Di bawah ini diberikan contoh algoritma mencari kecepatan dan percepatan. 
Kita mengetahui bersama bahwa rumus sebuah kecepatan:

![[Screenshot 2025-02-02 at 09.51.44.png]]

Sedangkan untuk percepatan (a), dengan formulasi sebagai berikut:

![[Screenshot 2025-02-02 at 09.52.00.png]]

Flowchart untuk mencari kecepatan dengan langkah demi langkah dengan simbol-simbol sebagai berikut:
![[Screenshot 2025-02-02 at 09.52.17.png]]

Tidak semua proses harus dibuat sebagai simbol dalam suatu flowchart. Beberapa proses dapat digabung apabila memiliki proses yang sama, misalkan pada proses menampilkan nilai pada flowchart di atas, beberapa langkah digabung menjadi satu yakni tampilkan nilai kecepatan dan percepatan digabung menjadi satu demikian juga dengan simbol digabung antara tampilkan Kecepatan (v) dan Percepatan (a), tapi ketika flowchart tersebut dibuat dalam kode-kode program pada bahasa pemrograman tertentu, semua perintah akan dikerjakan satu demi satu.


## [[01. Keuntungan Menggunakan Flowchart]]

Ada pun keuntungan menggunakan sistem flowchart, sebagai berikut:

1. **Komunikasi**: Flowchart adalah cara yang lebih baik untuk mengkomunikasikan logika suatu sistem kepada semua pihak yang terkait.

2. **Analisis  yang  efektif**: Dengan bantuan flowchart, masalah dapat dianalisis dengan cara yang lebih efektif.
﻿﻿﻿
3. **Dokumentasi**: Program flowchart berfungsi sebagai dokumentasi program yang baik, yang diperlukan untuk berbagai tujuan.

4. **Pengkodean Efisien**: Flowchart bertindak sebagai panduan atau cetak biru (blueprint) selama analisis sistem dan fase pengembangan program.

﻿﻿﻿1. **Proper Debugging**: Diagram alur membantu dalam proses debugging dengan cepat, karena dari awal kita sudah mengetahui secara detil permasalahan dan apa yang dikerjakan.  
﻿﻿﻿
﻿﻿﻿2. **Pemeliharaan Program yang Efisien**: Pemeliharaan program operasi menjadi mudah dengan bantuan flowchart. Ini membantu programmer untuk menempatkan upaya lebih efisien pada bagian itu.



## [[02. Keterbatasan Menggunakan Flowchart]]

Di samping keuntungan-keuntungan menggunakan flowchart, ternyata penggunaan flowchart mempunyai keterbatasan-keterbatasan tersendiri.

Beberapa keterbatasan penggunaan flowchart di bawah ini:

1. ﻿﻿﻿**Logika yang kompleks (rumit)**: Ada kalanya suatu logika program cukup rumit untuk di ekspresikan secara visual, sehingga menyajikan proses tersebut ke dalam suatu flowchart merupakan kendala baru (tugas tambahan lain yang berat). Beberapa pemrogram lebih memilih untuk langsung menulis programnya setelah berkomunikasi dengan pengguna, dibandingkan jika harus menunggu representasi dari analis.

2. ﻿﻿﻿**Perubahan/Modifikasi**: Jika diperlukan perubahan, flowchart mungkin memerlukan perubahan total pada desainnya (simbol-simbol flowchart).

3. ﻿﻿﻿**Reproduksi**: Karena flowchart berupa simbol (grafik), tidak bisa diketik, sehingga menjadi permasalahan tersendiri.




## [[03. Simbol Simbol Flowchart]]

Berikut ini adalah beberapa unsur dalam flowchart tersebut :
 - Input Percabangan (biasanya menggunakan perintah if dan switch) 
 - Perulangan (biasanya menggunakan perintah atau kode while, for, each, loop)
 - Output

Flowchart biasanya digambar menggunakan beberapa simbol standar, namun tidak menutup opsi lain untuk menyertakan simbol-simbol di luar standar untuk digunakan jika memang sangat diperlukan simbol tersebut dalam desain yang kita buat. Adapun simbol-simbol standar yang sering gunakan sebagai berikut:

#### 3.1 Terminator (Terminal)

Terminator (Terminal): Bentuk bagan alir oval menunjukkan awal atau akhir proses, biasanya berisi kata "Mulai", "Start", "Selesai", "Akhir", atau "End"

![[Screenshot 2025-02-02 at 09.57.43.png]]

#### 3.2 Preparation (predifined process)

Preparation (predifined process): digunakan sebagai penyiapan storage (ruang) atau pendeklarasian sebuah variabel yang dibutuhkan dalam suatu proses

![[Screenshot 2025-02-02 at 09.58.18.png]]

#### 3.3 Proses

Proses: Bentuk flowchart persegi panjang menunjukkan langkah aliran proses normal/generik. Misalnya, "Hitung kecepatan v = s/t".
![[Screenshot 2025-02-02 at 09.58.45.png]]

#### 3.4 Decision (Keputusan)

Decision (Keputusan): Bentuk simbol diamond (bentuk ketupat) menunjukkan cabang dalam aliran proses. Simbol ini digunakan ketika keputusan harus dibuat, biasanya pertanyaan Ya/Tidak atau Benar/Salah.
![[Screenshot 2025-02-02 at 09.59.34.png]]

#### 3.5 Connector (Titik sambung)

Connector (Titik sambung): Bentuk lingkaran kecil, berlabel, yang digunakan untuk menunjukkan lompatan dalam aliran proses. Connector umumnya digunakan dalam diagram kompleks atau alur panjang hingga lebih dari 1 lembar.

![[Screenshot 2025-02-02 at 09.59.59.png]]

#### 3.6 Data (Input/Output)

Data (Input/Output): Bentuk jajaran genjang yang menunjukkan input atau output data (I/O) untuk suatu proses. Contoh: Dapatkan X dari pengguna, Display X.

![[Screenshot 2025-02-02 at 10.00.26.png]]

#### 3.7 Delay

Delay: Digunakan untuk menunjukkan penundaan atau menunggu proses untuk masukan dari beberapa proses lainnya.

![[Screenshot 2025-02-02 at 10.00.48.png]]

#### 3.8 Arrow (Tanda Panah)

Arrow (Tanda Panah): digunakan untuk menunjukkan aliran kontrol dalam suatu proses. Panah yang datang dari satu simbol dan berakhir pada simbol lain menunjukkan bahwa kontrol melewati simbol yang ditunjukkan oleh panah.

![[Screenshot 2025-02-02 at 10.01.15.png]]


Simbol-simbol di atas adalah simbol dasar yang digunakan secara umum. Sekarang, pedoman dasar untuk menggambar flowchart dengan simbol di atas adalah:

1. ﻿﻿﻿Dalam menggambar flowchart yang tepat, semua persyaratan yang diperlukan harus dicantumkan dalam urutan logis.
2. ﻿﻿﻿Diagram alur harus rapi, jelas, dan mudah diikuti. Seharusnya tidak ada ruang untuk ambiguitas dalam memahami flowchart.
3. Flowchart harus dibaca dari kiri ke kanan atau dari atas ke bawah.
4. Sebuah simbol proses hanya dapat memiliki satu garis aliran yang keluar darinya.
5. ﻿﻿﻿Untuk simbol keputusan, hanya satu garis aliran yang dapat memasukinya, tetapi garis keluarnya memiliki 2 dengan kemungkinan (true(false).
6. ﻿﻿﻿Simbol terminal hanya dapat memiliki satu garis aliran saja.  


Lihat flowchart di bawah, hampir memuat semua simbol dasar yang ada.

![[Screenshot 2025-02-02 at 10.03.08.png]]

Di bawah ini terdapat contoh kasus dan kemudian diselesaikan dengan kalimat bebas dan sebuah flowchart.

#### Contoh Kasus 1:

Tiga angka yang di-input bebas dan acak, 3 angka tersebut disimpan dalam sebuah variabel, buatlah flowchart untuk mencari angka terbesar?

###### Penyelesaian kasus dengan bahasa bebas:

Angkal, Angka2, dan Angka3 yang di-input kita bandingkan satu demi satu, Angkal dibandingkan dengan Angka2, jika Angkal lebih besar dengan Angka2, kemudian Angkal dibandingkan lagi dengan Angka3, jika Angkal lebih besar dari Angka3, maka Terbesar adalah Angkal. Tapi jika Angkal lebih kecil dari Angka2, maka Angka2 dibandingkan dengan Angka3, jika Angka2 lebih besar dengan Angka3 maka Terbesar adalah Angka3, dan jika tidak maka Angka3 yang Terbesar.

Membaca penyelesaian di atas, harus lebih hati-hati dalam membacanya.

###### Penyelesaian kasus dengan flowchart:
![[Screenshot 2025-02-02 at 10.03.47.png]]

Penyelesaian dengan flowchart jauh lebih sederhana dibandingkan penyelesaian secara kalimat.



