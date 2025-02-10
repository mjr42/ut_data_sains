---
tags:
  - aljabar_linear_elementer
  - materi_3_ALE
---

# Kegiatan Belajar 2 - Analisis Jawab Sistem Persamaan Linear

ada Kegiatan Belaiar 1 modul ini sudah disimpulkan bahwa dengan eliminas Gauss atau eliminasi Gauss-Jordan, kita dapat:

![[Pasted image 20250209171122.png]]

Pada kesempatan ini akan dibahas keujudan dan ketunggalan. Keujudan terkait dengan ada jawab atau tidak adanya jawab sistem persamaan linear, sedangkan ketunggalan terkait dengan jawab tunggal atau jawab tidak tunggal.


## [[04. Keujudan Jawab]]

Keujudan jawab di sini berkaitan dengan ada jawab atau tidak ada jawab suatu sistem persamaan linear dengan cara operasi baris elementer matriks lengkapnya.

Diketahui sistem persamaan linear dan matriks lengkapnya:

![[Pasted image 20250209171228.png]]

Kemudian kita akan melakukan serangkaian operasi baris elementer pada matriks lengkap untuk menentukan sistem persamaan linear mempunyai jawab atau tidak mempunyai jawab (ada jawab atau tidak ada jawab).

#### 3.4.1 Tidak Ada Jawab

Bila dilakukan operasi baris elementer pada matriks lengkap menghasilkan matriks eselon tereduksi memuat baris yang unsur 1 utamanya pada kolom terakhir (yang berarti memberikan 0 = 1), maka sistem persamaan tidak konsisten atau tidak ada jawab. Jelasnya, kita lihat Contoh 3.2.1 berikut ini.

##### Contoh 3.2.1

Pandang sistem persamaan linear yang matriks lengkapnya
![[Pasted image 20250209180757.png]]

Proses mencari matriks eselonnya adalah sebagai berikut.

![[Pasted image 20250209180812.png]]

Matriks terakhir pada baris ke-3 mempunyai unsur tak nol, yaitu 1, terkiri pada kolom terakhir. Ini berarti sistem persamaan tak konsisten atau tak ada jawab. Dalil yang mendasari bahwa sistem persamaan linear tak ada jawab dinyatakan ke dalam Dalil 3.2.1 berikut ini.

##### Dalil 3.2.1 (Tidak Ada Jawab)

> Jika serangkaian operasi baris elementer dikerjakan pada matriks lengkap suatu sistem persamaan linear menghasilkan matriks yang memuat baris yang mempunyai unsur tak nol terkiri pada kolom terakhir, maka sistem persamaan linear tak ada jawab.

Pada matriks eselon setiap baris tak nol mempunyai tepat satu unsur satu utama.

Jadi banyaknya baris tak nol sama dengan banyaknya unsur satu utama. Susunan unsur satu utama menyebabkan pada tiap kolom ada paling banyak satu unsur satu utama. Jadi banyaknya unsur satu utama tak dapat melebihi banyaknya kolom, karena pada satu kolom ada paling banyak satu unsur satu utama. Karena banyaknya baris tak nol sama dengan banyaknya unsur satu utama, maka banyaknya baris tak nol juga tak melebihi banyaknya kolom.



#### 3.4.2 Ada Jawab (Punya Jawab)

Jika matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak memuat baris yang unsur 1 terkirinya pada kolom terakhir, kita dapat melakukan substitusi mundur untuk memperoleh jawab. Agar lebih jelas, kita perhatikan Contoh 3.2.2 berikut ini.

##### Contoh 3.2.2

Andaikan matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak mempunyai baris yang unsur satu utamanya terletak pada kolom terakhir, jadi unsur 1 utama tiap baris tidak pada kolom terakhir misalnya seperti berikut,

![[Pasted image 20250209180927.png]]

![[Pasted image 20250209180942.png]]

Kemudian dibuat dalam bentuk matriks kolom:

![[Pasted image 20250209180952.png]]

Dengan demikian, jika matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak memuat baris yang unsur 1 terkirinya pada kolom terakhir, sistem persamaan linear tersebut mempunyai jawab. Secara umum dinyatakan ke dalam Dalil 3.2.2 berikut ini.

##### Dalil 3.2.2 (Ada/Punya Jawab)

> Jika matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak memuat baris yang unsur satu utamanya pada kolom terakhir (unsur satu utama tiap baris tidak terletak pada kolom terakhir), maka sistem persamaan linear itu punya jawab.

Dalil 3.2.2 ini merupakan syarat perlu dan cukup untuk ada jawab, begitu pula Dalil 3.2.1 sebelumnya untuk tak ada jawab.

Kadang-kadang kita tidak harus menggunakan dalil di atas secara penuh untuk menetapkan bahwa suatu sistem persamaan linear punya jawab, dalam arti kita tidak harus betul-betul menentukan matriks eselon untuk matriks lengkap sistem persamaan itu. Hal itu kita perlihatkan pada Contoh 3.2.3 dan Contoh 3.2.4 berikut ini.

##### Contoh 3.2.3

Tunjukkan bahwa sistem persamaan linear yang matriks lengkapnya seperti berikut punya jawab tanpa lebih dulu mencari jawab itu.

![[Pasted image 20250209181124.png]]

###### Penyelesaian:
Me-nol-kan unsur pada kolom pertama di bawah baris pertama.

![[Pasted image 20250209181145.png]]

Matriks eselon untuk matriks lengkap ini jelas tak mempunyai baris yang unsur satu utamanya pada kolom terakhir, jadi sistem kita punya jawab.


##### Contoh 3.2.4 (Sistem Persamaan Linear Homogen)

Pandang sistem persamaan linear yang kolom terakhir matriks lengkapnya adalah kolom nol (kolom yang semua unsurnya adalah 0). Sistem persamaan linear yang begini disebut Sistem Persamaan Linear Homogen. Matriks koefisien dan matriks lengkapnya masing-masing adalah sebagai berikut,

![[Pasted image 20250209181224.png]]

Matriks eselon untuk matriks lengkap ini diperoleh dengan pengerjaan rangkaian operasi baris elementer pada matriks lengkap itu. Pengerjaan tiap operasi baris elementer pada matriks tak akan mengubah kolom nol matriks itu. Dengan demikian kolom terakhir matriks eselon untuk matriks lengkap di atas akan merupakan kolom nol, dengan demikian matriks eselon itu tak memuat baris yang unsur satu utamanya pada kolom terakhir. Jadi sistem persamaan linear homogen punya jawab.

Sesungguhnya untuk sistem persamaan linear homogen langsung terlihat bahwa

![[Pasted image 20250209181245.png]]

adalah jawab, karena jelaslah

![[Pasted image 20250209181257.png]]

jawab ini disebut jawab trivial (remeh, sepele).








## [[05. Ketunggalan Jawaban]]

Kalau suatu sistem persamaan linear punya (ada) jawab, pertanyaan selanjutnya: apakah jawab tersebut tunggal atau tak tunggal?

Pada pembahasan ketunggalan jawab berikut ini, kita akan memeriksa sistem persamaan yang punya jawab selanjutnya untuk menentukan: apakah jawab tersebut tunggal atau tak tunggal (banyak jawab). 

Mari kita melihat Contoh 3.2.5 dan Contoh 3.2.6, yang masing-masing dengan operasi baris elementer matriks lengkap sudah menghasilkan matriks eselon.

#### Contoh 3.2.5

Pandang sistem persamaan linear pada Contoh 3.2.3. Matriks eselon untuk matriks lengkapnya telah ditemukan, yaitu:

![[Pasted image 20250209181422.png]]

Banyaknya bilangan yang dicari adalah banyaknya kolom matriks koefisien sistem persamaan itu, yaitu matriks yang dilingkupi oleh persegi panjang terputus. Pada contoh ini ada 3 bilangan yang dicari, yaitu x, y, dan z.

Baris-baris tak nol pada matriks eselon itu menyatakan persamaan-persamaan yang saling bebas dalam sistem persamaan itu. Banyaknya baris tak nol pada matriks eselon ada 2 buah, sedangkan banyaknya bilangan yang dicari ada 3 , maka jawab tak tunggal karena kita dapat membuat salah satu y atau z bebas .


#### Contoh 3.2.6

Pandang sistem persamaan linear yang matriks eselon untuk matriks lengkapnya sudah diberikan berikut ini.

![[Pasted image 20250209181452.png]]

Jelas matriks ini tak mempunyai baris yang unsur satu utamanya pada kolom terakhir, jadi sistem persamaannya punya jawab. Banyaknya baris tak nol sama dengan banyaknya kolom matriks koefisien, setiap kolom pada matriks koefisien memuat unsur satu utama suatu baris. Tak ada bilangan yang dicari yang dibuat bebas, jawab sistem persamaan ini tunggal.

Pada umumnya banyaknya baris tak nol pada matriks eselon paling banyak sama banyaknya dengan banyaknya kolom matriks itu. Jadi banyaknya baris tak nol pada matriks eselon untuk matriks lengkap suatu sistem persamaan linear, paling banyak sama dengan banyaknya kolom matriks lengkap itu. Tetapi bila matriks eselon untuk matriks lengkap itu tak memuat baris yang unsur satu utamanya pada kolom terakhir, maka banyaknya baris tak nol itu paling banyak sama dengan banyaknya kolom dikurangi satu, jadi paling banyak sama banyaknya dengan banyaknya kolom matriks koefisien sistem persamaan itu.

Dari penjelasan pada Contoh 3.2.6, dalil berikut (yang bukti lengkapnya tidak dibahas di sini) dapat kita tuliskan

#### Dalil 3.2.3 (Ketunggalan)

> Jika pada matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak terdapat baris yang unsur satu utamanya pada kolom terakhir dan banyaknya baris tak nol sama dengan banyaknya kolom matriks koefisien, maka sistem persamaan linear itu punya tepat satu jawab.

Kembali pada Contoh 3.2.2. Matriks eselon untuk matriks lengkap sistem persamaan linear di situ adalah

![[Pasted image 20250209181541.png]]

banyaknya baris tak nol adalah 3, sedangkan banyaknya kolom matriks koefisien adalah 5. Kolom ke-2 dan kolom ke-5 tak memuat unsur 1 utama suatu baris. Hal ini mengakibatkan tak tunggalnya jawab.

Dapat dibuktikan bahwa hal itu berlaku umum, akan kita rumuskan berupa dalil berikut.

#### Dalil 3.2.4

> Jika matriks eselon untuk matriks lengkap suatu sistem persamaan linear tak memuat baris yang unsur satu utamanya terletak pada kolom terakhir, dan banyak baris tak nolnya kurang dari banyaknya kolom, maka sistem persamaan linear itu mempunyai lebih dari satu jawab.

Selanjutnya, dalil-dalil yang sudah kita bahas akan kita manfaatkan untuk memeriksa jawab contoh-contoh soal berikut ini.

##### Contoh 3.2.7

Periksa, apakah sistem persamaan linear yang matriks lengkapnya diberikan berikut ini, mempunyai jawab atau tidak mempunyai jawab, kalau mempunyai jawab apakah jawab tersebut tunggal atau tidak tunggal.

![[Pasted image 20250209181642.png]]

a. dan c. sistem persamaan linear homogen, b.,d., dan e. tidak homogen

###### Penyelesaian

Di sini akan diberikan matriks eselon dari masing-masing matriks lengkap. Sedangkan proses memperoleh masing-masing matriks eselon diserahkan kepada Anda sebagai latihan!.

a. Matriks Eselon

![[Pasted image 20250209181719.png]]

b. Matriks eselon:

![[Pasted image 20250209181739.png]]

c. Matriks Eselon

![[Pasted image 20250209181801.png]]

Matriks eselon untuk matriks lengkapnya tak mempunyai unsur satu utama pada kolom terakhir, jadi punya jawab. Banyaknya baris tak nol adalah 2, kurang dari banyaknya kolom matriks koefisien, yaitu 4. Jawab tak tunggal, jadi ada jawab yang bukan jawab trivial, yang disebut jawab tak trivial.

Pada sistem persamaan linear homogen masalah keujudan jawab jadi tidak penting, karena sistem persamaan linear homogen itu selalu punya jawab. Yang relevan adalah masalah ketunggalan.

Untuk sistem persamaan linear homogen jawab tunggal berarti satu satunya jawab adalah jawab trivial, ketaktunggalan jawab berarti adanya jawab tak trivial.

Anda akan menemukan penerapan masalah ini nanti pada masalah nilai eigen yang akan dibahas dalam Aljabar Linear Elementer II.


d. Matriks Eselon

![[Pasted image 20250209181838.png]]

tak terdapat baris yang unsur satu utamanya pada kolom terakhir, ada jawab.

Karena banyaknya baris tak nol (yakni 2) kurang dari banyaknya kolom matriks koefisien (yaitu 4) jawab sistem itu tak tunggal. Sebelum memperoleh matriks eselon kita sudah dapat menyimpulkan banyaknya baris(3) jelas kurang dari banyaknya kolom matriks koefisien, jadi baris tak nol pun begitu.


e. Dalam rangka mencari matriks eselonnya kita sampai ke pada matriks

![[Pasted image 20250209181904.png]]

yang memuat baris yang menyatakan persamaan yang tak mungkin dapat dipenuhi, sistem persamaannya tak punya jawab.

Pada Contoh 3.2.4 dibahas bahwa sistem persamaan linear homogen selalu punya jawab. Kalau jawab itu tunggal, yang ada hanya jawab trivial. Bila jawab tak tunggal, ada jawab yang disebut jawab tak trivial. Persoalan pada sistem persamaan homogen adalah masalah ada atau tak adanya jawab tak trivial. Pemeriksaan cukup dilakukan pada matriks koefisien saja seperti berikut.


##### Contoh 3.2.8

Diketahui 2 sistem persamaan linear homogen dengan matriks eselon untuk masing-masing matriks koefisiennya:


![[Pasted image 20250209181941.png]]

Tentukan, apakah sistem persamaan linear homogen yang berkaitan mempunyai jawab tak trivial atau jawab trivial.

###### Penyelesaian

a. Matriks koefisien mempunyai jawab tunggal karena banyaknya baris tak nol pada matriks eselon matriks koefisien sama dengan banyaknya kolom. Kemudian
dengan substitusi mundur menghasilkan jawab tunggal x = 0, y = 0, dan z = 0, yang berarti sistem persamaan linear homogen yang berkaitan mempunyai jawab trivial.

b. Sedangkan pada persamaan b. banyaknya baris tak nol pada matriks eselon kurang dari banyaknya kolom sehingga jawabnya tak tunggal, jadi sistem persamaan linear homogen yang berkaitan mempunyai jawab yang tak trivial.




## [[06. Analisis Sistem Persamaan Linear yang Matriks Lengkapnya Mengandung Unsur Parameter]]

Keujudan dan Ketunggalan Jawab yang telah dibahas di depan akan kita manfaatkan untuk menganalisis sistem persamaan linear yang beberapa unsur matriks lengkapnya masih berupa parameter.

Akan kita bahas syarat-syarat untuk parameter yang menyebabkan jawab sistem tak ada, ada tepat satu (tunggal), atau ada lebih dari satu (tak tunggal). Pembahasan dengan cara memberikan contoh-contoh soal.

#### Contoh 3.2.9

Tentukan hubungan antara p, q, dan r agar sistem persamaan linear (SPL):

![[Pasted image 20250209182128.png]]

![[Pasted image 20250209182134.png]]

##### Penyelesaian

Pengerjaan eliminasi Gauss pada matriks lengkap

![[Pasted image 20250209182200.png]]

Perhatikan baris terakhir, kemudian kita lihat 2 kasus berikut ini.

![[Pasted image 20250209182210.png]]
![[Pasted image 20250209182222.png]]

##### Kesimpulan

![[Pasted image 20250209182234.png]]


#### Contoh 3.2.10

Tentukan nilai-nilai p supaya sistem persamaan linear (SPL):

![[Pasted image 20250209182258.png]]

##### Penyelesaian

Karena SPL hanya mempunyai 2 persamaan, maka banyaknya baris tak nol pada matriks eselon untuk matriks koefisiennya paling banyak 2, jadi pasti kurang dari banyaknya kolom (yaitu 3). Dengan demikian, kita sudah dapat menyimpulkan bahwa kasus (ii) ada tepat satu jawab tak akan terjadi untuk nilai p berapapun (tak pernah ada tepat satu jawab).

Pengerjaan eliminasi Gauss untuk matriks lengkap

![[Pasted image 20250209182322.png]]

![[Pasted image 20250209182331.png]]

##### Kesimpulan

![[Pasted image 20250209182347.png]]


#### Contoh 3.2.11

Kerjakan seperti pada Contoh 3.2.10 untuk sistem persamaan linear (SPL) berikut tanpa mencari jawab

![[Pasted image 20250209182413.png]]

##### Penyelesaian

Karena banyaknya baris kurang dari banyaknya kolom matriks koefisien, maka banyaknya baris tak nol matriks eselon untuk matriks koefisien kurang dari banyaknya kolom. Jadi untuk nilai p berapapun kasus sistem persamaan linear tersebut punya tepat satu jawab tidak pernah terjadi.

Yang mungkin terjadi adalah tak punya jawab atau punya lebih dari satu jawab, yang akan kita periksa dengan mencoba mengerjakan langkah pertama eliminasi Gauss, sebagai berikut.

![[Pasted image 20250209182435.png]]

Perhatikan matriks terakhir:

![[Pasted image 20250209182447.png]]

##### Kesimpulan

![[Pasted image 20250209182457.png]]


#### Contoh 3.2.12

Tentukan nilai-nilai p supaya sistem persamaan linear homogen yang berkaitan dengan matriks koefisien berikut,

![[Pasted image 20250209182516.png]]

##### Penyelesaian

Pada sistem persamaan linear homogen: jawab selalu ada, sekurangnya jawab trivial. Bila jawabnya tunggal, jawab satu satunya itu adalah jawab trivial. Jawab tak tunggal ekivalen dengan adanya jawab tak trivial.

Langkah permulaan eliminasi Gauss mencari matriks eselon untuk matriks koefisien,

![[Pasted image 20250209182537.png]]
Perhatikan baris terakhir matriks (3.2.2):

![[Pasted image 20250209182552.png]]

##### Kesimpulan

![[Pasted image 20250209182603.png]]


#### Contoh 3.2.13

Tentukan nilai-nilai p supaya sistem persamaan linear (SPL) yang matriks lengkapnya:

![[Pasted image 20250209182619.png]]

##### Penyelesaian

Dengan pengerjaan eliminasi Gauss matriks lengkap menghasilkan,

![[Pasted image 20250209182641.png]]

![[Pasted image 20250209182650.png]]

##### Kesimpulan

![[Pasted image 20250209182702.png]]



