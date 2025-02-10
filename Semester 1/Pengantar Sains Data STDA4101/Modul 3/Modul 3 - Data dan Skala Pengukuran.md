---
tags:
  - sains_data
---
## [[01. Jenis Data]]

Data sains pada dasarnya adalah bidang ilmu yang sangat bergantung kepada data. Data merupakan inti dari setiap analisis dan pengambilan keputusan. Data sendiri adalah abstrak dari entitas di dunia nyata seperti halnya manusia, benda, dan kejadian.

Dalam data sains terdapat banyak jenis atribut dimana ia menentukan jenis analisis yang nantinya akan digunakan dalam pengolahan data. Dalam data sains terdapat beberapa jenis data yaitu 1)Data terstruktur 2) data tidak terstruktur 3) Bahasa alami (natural language) 4) data yang dihasilkan oleh komputer (machine-generated) 5) data berbasis graph 6) audio, video, dan citra 7) data streaming


## [[02. Data Terstruktur]]

Data terstruktur adalah data yang tergantung pada sebuah model data dan memiliki kolom yang tetap dalam sebuah pangkalan data. contoh yang paling sederhana adalah data yang disimpan dalam format spreadsheet (Excel File). Data ini juga dikenal dengan istilah data attribute karena menyimpan atribut atau infomasi detail tentang sesuatu yang terbagi bagi atas baris dan kolom (field and column).

Perangkat yang paling sering digunakan untuk mengolah data atribut dalam sebuah pangkalan data adalah seperti Structured Querry Language (SQL) atau Postgre SQL untuk data spasial.

![[Screenshot 2024-09-27 at 19.32.30.png]]


## [[03. Data Tidak Terstruktur]]

Data tidak terstruktur adalah kebalikan dari data terstruktur. Data Tidak Terstruktur adalah data yang tidak memiliki kolom dan baris, selit untuk dikelola karena konteks-spesifik dan bervariasi. Contoh sederhana dari data ini adalah pesan teks di media sosial.

![[Screenshot 2024-09-27 at 19.34.34.png]]


## [[04. Bahasa Alami (Natural Language)]]

Bahasa alami atau yang sering disebut dengan Natural Language adalah salah satu bentuk dari jenis data tidak terstruktur. Sangat sulit diolah karena membutuhkan domain keilmuan dari pakar bahasa, tidak hanya dengan pendekatan data sains saja.

Pada analisis natural language biasanya peneliti akan melihat pola penggunaan, analysis sentimen, dan sebagainya yang membutuhkan bantuan kamus dari bahasa yang digunakan.



## [[05. Data yang Dihasilkan Oleh Komputer]]

Machine-generated atau data yang dihasilkan oleh komputer seperti jumlah nilai transaksi ATM dan sebagainya. Data ini murni dihasilkan oleh komputer tanpa adanya intervensi dari manusia di dalamnya. Sangan berbeda dengan data terstruktur, tidak terstruktur, dan natural language dimana masih ada intervensi dari manusia didalamnya



## [[06. Data Berbasis Graph]]

Data berbasis graph yang dimaksud disini bukanlah data berbentuk gambar grafis, namun data yang dapat divisualisasikan dalam bentuk jejaring seperti dalam teori graph dalam domain ilmu matematika.

![[Screenshot 2024-09-27 at 19.40.29.png]]

Dalam teori graph, sebuah graph adalah strukrut hubungan matematika dengan memodelkan hubungan objek yang saling berpasangan. Graph atau data jejaring adalah data yang fokus pada hubungan atau keterhubungan suatu objek satu dengan yang lainnya


## [[07. Data Audio, Video, dan Citra]]

Data Audio, video dan citra biasanya diperoleh dari sebuah atau beberapa sensor yang sengaja dipasang untuk memperioleh data yang dibutuhkan. Contoh yang paling sederhana adalah CCTV.

![[Screenshot 2024-09-27 at 19.43.27.png]]

data data ini kemudian dapat diolah menggunakan pendekatan Machine Learning maupun Deep LEarning sesuai dengan kebutuhan. Contohnya adalah data citra satelit Sentinel



## [[08. Data Streaming]]

Data streaming adalah data yang diperoleh, diubah, dan digunakan secara waktu nyata (Real Time). Data ini dapat dalam bentuk yang terstruktur, tidak terstruktur, audio, video, maupun citra. Data disimpan dalam sebuah pangkalan data ketika suatu fenomena sedang terjadi, bukan dikirim dan disimpan setelah fenomena terjadi. Data ini diobedakan dengan data lainnya karena sering kali peneliti harus beradaptasi dengan proses pengolahan data ini.


## [[09. Data Numerik]]

Data numerik menggambarkan besaran terukur yang direpresentasikan dengan menggunakan bilangan bulat atau rill. DAta numerik dibagi menjadi dua yaitu data diskret dan kontinu.

Data Diskret terbatas pada data integer, yaitu bentuk khusus dari data numerik yang tidak memiliki nilai desimal. Contoh jenis data integer adalah jumlah hari, dan lainnya

Data Kontinu menggambarkan tipe data yang memiliki nilai tak terbatas dalam rentan nuilai tertentu dan dapat dituliskan dalam bentuk desimal atau koma. Data kontinu didapatkan dari proses pengukuran.

Kita dapat melakukan operasi matematika seperti penjumlahan, pengurtangan, dan lainnya paad data Diskret dan Kotinu.

Skala pengukuran data numerikdibagi menjadi dua jenis yaitu skala interval dan skala rasio. Apabila titik nol ditentukan maka data numerik tersebut disebut sebagai data rasio. Data Rasio memiliki nilai dasar (nol) mutlak dan menerapkan interval yang sama antar dua nulau yang berurutan.

Data skala interval tidak memiliki titik dasar (nol) mutlak sehingga tidak memungkinkan untuk dilakukan perbandingan



## [[10. Data Kategorik]]

Data kategorik adalah jenis data yang terdiri atas variabel kategori atau data hasil pengelompokan berdasarkan kategori tertentu. Skala pengukuran data kategori dibagi menjadi dua macam yaitu skala nominal dan skala ordinal.

Skala nominal bertujuan untuk penggolongan saha tanpa mengukur besaran. Nilai maksimum dan minimum tidak dapat diterapkan pada data dengan skala nominal.

Skala Ordinal hampir sama dengan skala niminal, namun selain digunakan untuk membedakan data, skala ordinal juga berguna untuk menyajikan urutan tingkatan, Nilai 1 memiliki tingkatan yang lebih tinggi daripada nilai 0 dan seterusnya.

Tidak semua metopde data sains dapat memproses semua jenis data seperti halnya algoritme neural network yang tidak dapat memproses darta kategori. Akan tetapi kita bisa melakukan proses konversi dari tipe data kategori menjadi tipe data numerik

![[Screenshot 2024-09-27 at 20.07.14.png]]