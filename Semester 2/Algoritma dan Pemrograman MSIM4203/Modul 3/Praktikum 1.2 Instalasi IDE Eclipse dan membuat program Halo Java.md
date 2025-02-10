---
tags:
  - algoritma_pemprograman
  - materi_3_AP
---
# Praktikum 1.2 Instalasi IDE Eclipse dan membuat program Halo Java

Java adala bahasa perograman yang sejak munculnya sudah sangat populer. Saat ini Java menjadi bahasa pemrograman yang paling diminati untuk membangun aplikasi mobile, web, maupun enterprise. Dalam pengembangan software, programmer Java tak lepas dari IDE (Integrate Development Environment).

Keuntungan menggunakan IDE adalah banyak fitur yang bisa digunakan untuk mempercepat pengembangan software, IDE pada Java sendiri sudah cukup banyak, misalnya Netbeans, Eclipse, BlueJ, JBuilder (Borland), JDeveloper (Oracle).

Pada Modul Praktikum ini akan digunakan IDE yang termasuk paling banyak digunakan yaitu Eclipse.


## [[06. IDE Eclipse]]

Eclipse adalah IDE yang digunakan untuk mengembangkan perangkat lunak yang bisa dijalankan diberbagai plaform, Eclipse dapat berjalan pada platfom Microsoft Windows, Linux, Solaris, IX, HP-UX, dan Mac OS X. Pada awal munculnya oleh IMB Visual Age diperuntukan untuk Java 4.0, seiring berjalannya waktu Eclipse mendukung pengembangan software berbasis bahasa pemrograman lainnya, seperti C/C++, Cobol, Phyton, Perl, PHP dan lain sebagainya.

Eclipse dapat digunakan untuk aktivitas dalam siklus pengembangan perangkat lunak, seperti dokumentasi, ujicoba perangkat lunak, pengembangan web dan lain sebagainya. Cukup banyak versi Eclipse yang sudah rilis yang biasanya akan selalu diperbaharui dengan rilisnya versi Java terbaru. Pada modul ini akan kita gunakan Eclipse SimRel.




## [[07. Mendapatkan IDE Eclipse]]

Untuk mendapatkan Eclipse versi SimRel Anda bisa mengikuti langkah-langkah berikut:

1. Kunjungi laman https://www.eclipse.org/downloads/packages/installer, lalu fokus pada bagian kanan laman tepat pada MORE DOWNLOADS

2. Pada halaman laman berikutnya arahkan ke "Get Eclipse SimRel 2018- 09" dan klik tombol "Download 64 bit" ', mungkin akan sangat berbeda link pengunduhannya, apalagi jika terdapat versi Eclipse yang terbaru.

3. Simpan pada folder yang Anda inginkan dan nama filenya adalah eclipse-inst-win64.exe, klik tombol "Save" (akan sangat berbeda jika menggunakan browser Chrome.

4. Tunggu hingga selesai terunduh dengan sempurna.

5. Setelah terunduh dengan sempurna, maka kita akan mendapat 1 file bernama eclipse-inst-win64.exe.




## [[08. Instalasi IDE Eclipse]]

Untuk instalasi IDE Eclispe dengan langkah-langkah sebagai berikut:

1. ﻿﻿﻿Pastikan file eclipse-inst-win64.exe sudah siap, pastikan komputer Anda terkoneksi dengan internet.
2. ﻿﻿﻿Pastikan file eclipse-inst-win64.exe terpilih dan kemudian lakukan klik kanan sampai muncul menu pop up, lalu pilih menu "Run as administrator".
3. Hingga splash secreen instalasi berjalan.
4. Pada window pilihan paket pilihlah dengan cara klik paket "Eclipse IDE for Java Developers".
5. Pada pilihan paket "Eclipse IDE for Java Developers"', ubah folder instalasi menjadi "C: leclipse\java-2018-09" dan untuk memulai instalasi klik tombol "INSTALL".
6. Pada proses instalasi akan tampak progress bar yang menunjukkan proses instalasi sementara berjalan.
7. Setelah muncul Window Lisensi, centang opsi "Remember accepted licenses" dan kemudian klik tombol "Accept".
8. Selanjutnya tunggu hingga proses instalasi berhasil dengan sempurna, hingga tampak seperti gambar di bawah, untuk menjalankan IDE Eclispe pertama kali, klik tombol "LAUNCH"
9. Splash Screen dari IDE Eclipse
10. Pada Window "Select a directory as workspace", pilihlah folder di mana Anda akan menyimpan file-file Java yang Anda buat, usahakan sama dengan folder seperti pada gambar di bawah walau drive nya berbeda. Di bawah saya menyimpannya pada folder "Latihan Java" dan disimpan pada drive "D: 1", sesuaikan drive yang ada di komputer Anda.
11. Selanjutnya klik tombol "Launch", dan tunggu hingga IDE Eclipse terbuka dengan sempurna.
12. Kemudian klik File → Close.



## [[09. Menjalankan IDE Eclipse dan Membuat Program Java]]

Pada sub bab C sudah dijelaskan instalasi dan menjalankan IDE Eclipse untuk pertama kali, sekarang akan dijelaskan bagaimana menjalankan kembali IDE Eclipse yang baru saja di instal sebagai berikut:

1. Klik dua kali Icon IDE Eclipse dari Desktop, shortcut dengan nama

2. "Eclipse Java 2018-09", dan tunggu sampai IDE Eclipse terbuka. Klik File → New → Java Project.

3. Pada window New Java Project, isi kolom Project Name: dengan nama "Aplikasi _Pertama", lalu klik tombol "Finish".

4. Project Aplikasi_Pertama akan tampak seperti Gambar 3.45 berikut:

![[Screenshot 2025-02-03 at 12.22.14.png]]

1. Untuk membuat Java pertama kita, kembali klik File → New → Class.
2. ﻿﻿﻿Pada window "New Java Class" ini kolom Name: dengan HaloJava (tidak perlu menyertakan ekstensi java, karena akan otomatis dibuat oleh IDE Eclipse)
3. Selanjutnya klik tombol Finish hingga terbentuk file class Java dengan nama HaloJava.Java
4. Sekarang kita akan menampilkan tulisan pada keluaran dengan tulisan "Halo Java", dan untuk membuatnya, pada file HaloJava.java sisipkan potongan kode program berikut di antara (...), sehingga menjadi kode program seperti di bawah ini:

![[Screenshot 2025-02-03 at 12.23.15.png]]

5. Kemudian simpan file HaloJavajava dengan cara klik File → Save.
6. Sekarang jalankan program pada file HaloJava.java dengan cara klik menu Run Run atau dengan cara cepat menekan CtrI+F11.
7. ﻿﻿﻿﻿Lihat hasil keluaran program pada Tab Console pada bagian bawah IDE Eclipse

![[Screenshot 2025-02-03 at 12.23.49.png]]


Untuk menulis kode dengan menggunakan IntelliSense juga berlaku pada IDE Eclipse, biasanya digunakan untuk mengurangi kesalahan-kesalahan ketik kode program.

Contoh

kode program System.out.println("Halo Java");, ini bisa dilakukan sebagai berikut:

8. ﻿﻿﻿Buka file class HaloJava.java.
9. ﻿﻿﻿Dalam body main method buat baris baru dan coba ketikkan System.
![[Screenshot 2025-02-03 at 12.24.21.png]]

10. Kemudian ketikkan o (hasilnya)
![[Screenshot 2025-02-03 at 12.24.39.png]]
11. Ketikkan ut. (hasilnya)
 ![[Screenshot 2025-02-03 at 12.25.06.png]]

Bukan hanya turunan dari sebuah perintah yang muncul, bahkan sampai pada deskripsi dan contoh dari perintah yang ada akan muncul.