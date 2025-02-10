---
tags:
  - metode_statistika
  - materi_7_MS
---
# Kegiatan Belajar 1 - Distribusi Sampling dan Teorema Limit Pusat

Adanya proses generalisasi atau peramalan menandakan bahwa dalam konteks ini ada objek yang disebut populasi dan sampel. Tentunya, kita bekerja dengan data pada ranah sampel untuk kemudian digunakan dalam menyimpulkan keadaan populasi.

Karakteristik numerik dari populasi disebut sebagai parameter dan karakteristik sampel disebut statistik. Parameter dan statistik ini dapat berupa rata-rata, varians, simpangan baku, atau proporsi. Lalu apa hubungannya distribusi sampling dengan statistik?

Jika dilakukan pengambilan sampel lagi akan ada banyak kemungkinan sampel yang dapat terpilih. Seandainya, kita sedang berbicara mengenai rata-rata, maka rata-rata sampel yang diperoleh akan berbeda-beda dari satu sampel dengan sampel yang lain. 

Hal ini menunjukkan bahwa karakteristik sampel, yakni statistik, nilainya berubah-ubah, akan sangat bergantung pada sampel yang terambil. Karena nilainya berubah-ubah itulah, maka statistik merupakan variabel acak yang nilainya bervariasi sesuai dengan variasi sampel yang terambil.

#### Distribusi Sampling

Suatu variabel acak tentu memiliki distribusi peluang. Nah, karena statistik itu merupakan variabel acak, maka statistik juga memiliki distribusi peluang, yang dinamakan distribusi sampling.

![[Pasted image 20241027142001.png]]

#### Standard Error

Sebuah distribusi tentu memiliki nilai tengah atau rataan dan juga keragaman yang dicirikan oleh simpangan baku. Nah, simpangan baku dari suatu statistik disebut sebagai standar error atau galat baku.

Misalnya statistik yang kita perhatikan adalah rata-rata (X). Distribusi peluang X disebut distribusi sampel dari rataan, dan standar error bagi rataan adalah simpangan baku dari distribusi sampel x.

![[Pasted image 20241027142134.png]]

#### Fungsi Distribusi Sampling

Pertanyaan berikutnya yang menarik untuk dijawab adalah, untuk apa kita perlu mengetahui distribusi sampling?

Saudara, di awal tadi kita telah ketahui bahwa pada statistika inferensia yang menjadi fokusnya adalah adanya proses generalisasi mengenai karakteristik populasi melalui data sampel. Generalisasi ini meliputi pendugaan dan pengujian hipotesis. Ketidaktahuan kita mengenai parameter populasi yang sesungguhnya menjadi alasan perlunya kita melakukan pengukuran terhadap data sampel.

Pada saat melakukan generalisasi, karena data yang digunakan hanya data sampel, yaitu sebagian dari populasi, maka sudah pasti generalisasi tersebut tidak seratus persen akurat, meskipun sedikit pasti ada error-nya. Nah, untuk dapat melakukan generalisasi dengan baik terhadap populasi, pengetahuan mengenai distribusi dari suatu statistik atau distribusi sampling sangatlah diperlukan. Inilah yang dapat menuntun kita agar dapat melakukan generalisasi terhadap populasi dengan benar.

![[Pasted image 20241027142243.png]]

Penentuan distribusi sampling tergantung pada ukuran populasi, ukuran sampel, dan bagaimana metode pengambilan sampelnya. Oleh karena itu, ada beberapa formula mengenai distribusi sampling, yaitu pada saat pengambilan sampel dengan pengembalian, tanpa pengembalian, apabila ukuran sampelnya besar (teorema limit pusat), dan apabila ukuran sampelnya kecil.




## [[01. Distribusi Sampling Bagi Rata-rata untuk Pengambilan sampel dengan pengembalian]]

Ukuran penting dari suatu distribusi adalah rata-rata dan varians-nya atau simpangan bakunya. Sebagai contoh, misalnya kita memiliki sebuah populasi berukuran N=4, dengan data sebagai berikut: 1,2,3,4.

Dari populasi tersebut diambil sampel berukuran n =2 dengan pengembalian. Artinya, setelah mengambil sampel yang pertama, kemudian data yang terambil tersebut dikembalikan lagi sehingga ada kemungkinan satu data terambil berulang kali.

Jika dihitung, nilai rata-rata dan varians populasi dari data tersebut diperoleh Rata-rata:

![[Pasted image 20241027142406.png]]

Varians:

![[Pasted image 20241027142418.png]]

Dari populasi tersebut, berbagai kemungkinan sampel yang dapat diambil adalah sebagai berikut.

![[Pasted image 20241027142429.png]]

Ternyata, melalui pengambilan sampel dengan pengembalian, ada 16 kemungkinan sampel yang dapat diambil, dimana masing-masing sampel memiliki rata-rata. Misalnya sampel ke-1, rata-ratanya adalah $x_1 =1$, sampel kedua rata-ratanya $x_2$ =1,5, dan seterusnya hingga sampai ke-enam belas. Dapat Anda lihat bahwa setiap sampel nilai rata-ratanya berbeda.

bergantung pada hasil sampling yang diperoleh. Sehingga, nilai-nilai rataan ini membentuk suatu sebaran tersendiri yang jika dihitung ekspektasi atau rata-ratanya menjadi:

![[Pasted image 20241027142558.png]]

Lihat bahwa, nilai rata-rata dari rataan sampel (X) sama dengan rata-rata populasi,

![[Pasted image 20241027142633.png]]

Sedangkan, varians dari ratan sampel

![[Pasted image 20241027142649.png]]

Kemudian, bentuk distribusi dari adalah normal, sebagaimana diperlihatkan pada histogram

![[Pasted image 20241027142707.png]]

![[Pasted image 20241027142723.png]]


#### Distribusi Sampling Bagi (X) dengan Pengembalian

![[Pasted image 20241027142839.png]]

#### Contoh 7.1

Bila diberikan populasi 1, 1, 1, 3, 4, 5, 6, 6, 6, dan 7. Hitunglah peluang bahwa suatu contoh acak berukuran 36, yang diambil dengan pemulihan, akan menghasilkan nilai tengah yang lebih besar daripada 3,8 tetapi lebih kecil daripada 4,5 bila nilai tengah itu diukur sampai per sepuluh terdekat.

##### Penyelesaian

Karena data dalam populasi tersebut ada yang nilainya sama, maka setiap nilai memiliki peluang yang berbeda. Sebaran peluang bagi populasi tersebut dicatat sebagai berikut

![[Pasted image 20241027142907.png]]

###### Nilai ekspektasi atau rata-rata populasi adalah:

![[Pasted image 20241027142916.png]]

###### Varians populasi diperoleh:

![[Pasted image 20241027142941.png]]

![[Pasted image 20241027142954.png]]





## [[02. Distribusi Sampling Bagi Rata Rata Untuk Pengambilan Sampel Tanpa Pengembalian]]

Sekarang, bagaimana jika populasi yang beranggotakan nilai-nilai 1,2,3,4 dilakukan pengambilan sampel berukuran n = 2 tanpa pengembalian? Berbagai kemungkinan sampel yang akan terpilih adalah sebagai berikut.

![[Pasted image 20241027143456.png]]

![[Pasted image 20241027144343.png]]

![[Pasted image 20241027144349.png]]

Dengan demikian, jika sampel diambil tanpa pengembalian, distribusi X juga menyebar normal dengan rataan $\mu$ dan ragam

![[Pasted image 20241027144419.png]]

atau simpangan baku

![[Pasted image 20241027144432.png]]

#### Distribusi Sampling bagi (X) tanpa Pengembalian

![[Pasted image 20241027144503.png]]

#### Contoh 7.2

Diberikan sebuah populasi yang terdiri atas nilai-nilai 1, 1, 1, 3, 4, 5, 6, 6, 6, dan 7. Dari populasi ini diambil semua kemungkinan contoh berukuran 4 tanpa pemulihan, dan untuk setiap contoh yang diperoleh dihitung nilai tengah contohnya, sehingga diperoleh sebaran penarikan contoh bagi semua nilai tengah contoh itu. Hitunglah nilai tengah dan simpangan baku bagi sebaran penarikan contoh itu. Sekurang-kurangnya ¾ di antara semua nilai tengah contoh itu kita harapkan akan jatuh di antara dua nilai berapa?

##### Penyelesaian

Dari Contoh 7.1 diperoleh bahwa $\mu = 4$ dan $𝛔^2$ = 5 . Ekspektasi atau rataan dan simpangan baku bagi distribusi sampling X adalah:

![[Pasted image 20241027144643.png]]






## [[03. Teorema Limit Pusat untuk Ukuran Sampel Besar]]

Dalam kenyataannya, suatu populasi belum tentu berdistribusi normal. Banyak juga populasi yang tidak diketahui apa distribusinya. Nah, jika kita berkepentingan untuk mengetahui distribusi sampling bagi rata-rata sampel, apa yang harus kita lakukan? Sementara itu, sudah jelas bahwa distribusi sampling diturunkan dari distribusi populasinya.

Dalam kondisi demikian, ada sebuah dalil yang menyatakan bahwa jika ukuran sampel n besar, maka distribusi x mendekati normal apapun bentuk distribusi populasinya.

#### Teorema Limit Pusat

![[Pasted image 20241027144838.png]]

Teorema limit pusat akan sangat baik hasilnya jika digunakan pada n ≥ 30, apapun bentuk populasinya. Jika n ≤ 30, hampiran distribusi normal melalui teorema limit pusat ini baik digunakan hanya jika populasinya diketahui beristribusi normal atau mendekati normal.

Bisa populasi normal maka X akan tepat menyebar normal betapapun kecilnya ukuran sampelnya (Walpole, 1995).

#### Contoh 7.3

Misalkan bahwa distribusi populasi kekuatan genggaman karyawan-karyawan industri diketahui mempunyai rata-rata 110 dan simpangan baku 10 Untuk suatu sampel acak dengan 75 karyawan, berapakah peluang bahwa rata-rata genggaman sampel itu akan:

1. ﻿﻿﻿Antara 109 dan 112?
2. ﻿﻿﻿Lebih besar dari 111?

##### Penyelesaian

![[Pasted image 20241027144947.png]]

###### 1. Untuk mendapatkan P(109 <x <112)

![[Pasted image 20241027145024.png]]

###### 2. Untuk mendapatkan P(x >112)

![[Pasted image 20241027145115.png]]




## [[04. Distribusi t]]

Dalam penelitian sering pula kita jumpai keadaan dimana varians populasi tempat kita mengambil sampel tidak diketahui. Hal ini akan bermasalah pada penentuan nilai

![[Pasted image 20241027145153.png]]

karena $\sigma$ tidak diketahui. Jika demikian, bagaimana cara mengatasinya?

![[Pasted image 20241027145220.png]]


Nilai-nilai peluang distribusi t ini juga telah diberikan dalam tabel distribusi t, seperti halnya tabel distribusi normal baku. Mengenai hubungan distribusi t-student dengan distribusi normal dapat dilihat pada literatur lain, salah satunya Walpole (1995).

#### Distribusi T

![[Pasted image 20241027145251.png]]

#### Contoh 7.4

![[Pasted image 20241027145309.png]]

##### Penyelesaian

![[Pasted image 20241027145346.png]]


Demikianlah berbagai kondisi dari formulasi distribusi sampling bagi rata-rata. Dalam penggunaannya untuk menyelesaikan permasalahan Anda mesti dapat mengidentifikasi formula mana yang harus digunakan. Pemahaman terhadap materi ini merupakan fondasi penting untuk mempelajari materi pendugaan parameter.

