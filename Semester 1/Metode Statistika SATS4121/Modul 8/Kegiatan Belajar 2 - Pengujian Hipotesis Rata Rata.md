---
tags:
  - metode_statistika
  - materi_8_MS
---
# Kegiatan Belajar 2 - Pengujian Hipotesis Rata Rata

engujian hipotesis rata-rata dimaksudkan untuk mengetahui apakah rata-rata populasi berbeda dengan suatu nilai rata-rata tertentu ($\mu_0$). Uji hipotesis ini terdiri dari dua jenis, yaitu ketika jumlah sampel besar (n > 30) dan sampel kecil. Ketika jumlah sampel besar, dibedakan lagi menjadi ketika varians $(\sigma^2$) diketahui dan varians tidak diketahui.

Hipotesis dinyatakan dalam satu arah dan dua arah.

1. Satu Arah
   ![[Pasted image 20241107020621.png]]
   
2. Dua Arah
   ![[Pasted image 20241107020628.png]]


## [[05. Sampel Besar]]

Suatu sampel acak x_1,x_2...x_n dari n menunjukkan sampel acak dari suatu distribusi dengan rata-rata $\mu$ dan varians $\sigma^2$ diketahui. Misalnya hipotesis pertama adalah:

![[Pasted image 20241107020750.png]]

Statistik uji diperoleh berdasarkan variabel random x. Pada materi teorema limit pusat, diketahui bahwa random variabel x dapat didekati dengan distribusi $N(\mu,\sigma^2/n)$. Sehingga didapatkan:

![[Pasted image 20241107020846.png]]

![[Pasted image 20241107020900.png]]

Dimana $\alpha$ adalah peluang kesalahan jenis I, yaitu menolak $H_o$ padahal $H_o$benar.

Persamaan tersebut dapat digunakan untuk daerah penerimaan. Sementara itu, daerah penolakannya adalah:

![[Pasted image 20241107020947.png]]

Pengujian hipotesis satu arah juga mengikuti prosedur hupotesis dua arah. Perbedaanya adalah pada daerah kritis.

Untuk hipotesis lower tail test:

![[Pasted image 20241107021123.png]]

Untuk hipotesis upper tail test:

![[Pasted image 20241107021151.png]]

Gambar daerah kritis dapat dilihat pada Gambar 8.2.

![[Pasted image 20241107021206.png]]

#### Contoh 8.1

Perusahaan industri besi baja mencatat bahwa pelat baja yang diproduksi memiliki rata-rata panjang 80 cm dan simpangan baku 7 cm. Setelah tiga tahun, teknisi perusahaan meragukan keabsahan rata-rata panjang tersebut.

Teknisi tersebut menduga bahwa rata-ratanya sudah tidak sama dengan 80 cm. Untuk meyakinkan hipotesisnya tersebut, dilakukan pengambilan sampel 100 pelat baja yang dipilih secara random dari populasi. Rata-rata panjang sampel tersebut adalah 83 cm. 

Apakah ada alasan untuk meragukan bahwa rata-rata panjang pelat baja tidak sama dengan 80 cm? Gunakan $\alpha$ = 5%.

##### Penyelesaian

Untuk menjawab pertanyaan in dilakukan pengujian hipotesis dengan langkah-langkah sebagal berikut:

1. Menentukan hipotesis
   
   Karena yang dihipotesiskan teknisi (peneliti) adalah rata-ratanya sudah tidak sama dengan 80 cm, maka hipotesis yang digunakan dua arah:
   
   ![[Pasted image 20241107021308.png]]

2. ﻿﻿﻿Menentukan taraf signifikansi $\alpha$ = 5%.
3. ﻿﻿﻿Menentukan statistik uji
   
   ![[Pasted image 20241107021339.png]]

4. Menentukan daerah kritis
   ![[Pasted image 20241107021406.png]]
   
5. Mengambil kesimpulan
   ![[Pasted image 20241107021424.png]]


#### Contoh 8.2

Seperti pada Contoh 8.1, teknisi dapat menguji juga apakah rata-rata panjang pelat baja kurang dari 80 cm.

##### Penyelesaian :

Langkah-langkah hipotesis :

1. ﻿﻿﻿Menentukan hipotesis
   ![[Pasted image 20241107021508.png]]

2. ﻿﻿﻿Menentukan taraf signifikansi $\alpha$ = 5%

3. ﻿﻿﻿Menentukan statistik uj1 z = 4,2857

4. ﻿﻿﻿Menentukan daerah kritis
   ![[Pasted image 20241107021558.png]]
	![[Pasted image 20241107021615.png]]

5. Mengambil kesimpulan
   ![[Pasted image 20241107021634.png]]


#### Contoh 8.3

Seperti pada Contoh 8.1, teknisi dapat menguji juga apakah rata-rata panjang pelat baja lebih dari 80 cm.

##### Penyelesaian :
Langkah-langkah hipotesis :

1. Menentukan hipotesis
   ![[Pasted image 20241107021744.png]]
2. Menentukan taraf signifikansi $\alpha$ = 5%
   
3. Menentukan statistik uji z = 4,2857

4. Menentukan daerah kritis
   ![[Pasted image 20241107021815.png]]

5. Mengambil Kesimpulan
   ![[Pasted image 20241107021842.png]]


![[Pasted image 20241107021900.png]]

![[Pasted image 20241107021908.png]]

![[Pasted image 20241107021918.png]]

![[Pasted image 20241107021930.png]]


#### Contoh 8.4
Dalam proses pengisian cairan botol di industri kosmetik, dicatat bahwa rata-rata waktu yang dibutuhkan untuk pengisian susu pembersih adalah 10 detik.

Industri ini ingin meningkatkan produktivitas dengan melakukan perbaikan proses yang dapat memperpendek proses pengisian. Sejumlah 20 sampel telah diambil, dan hasil pencatatan waktu pengisian adalah sebagai berikut.

![[Pasted image 20241107134015.png]]

Ujilah apakah perbaikan proses tersebut mampu memperpendek pengisian? Dengan kata lain, apakah rata-rata waktu pengisian sama dengan 10 detik seperti pada data sebelumnya? Gunakan $\alpha$ = 5%.

##### Penyelesaian :

1. Hipotesis
   
   ![[Pasted image 20241107134204.png]]
   
2. Taraf signifikansi $\alpha$ = 5%
   
3. Statistik uji
   ![[Pasted image 20241107134148.png]]
   
4. Daerah kritis
   ![[Pasted image 20241107134139.png]]
   
5. Mengambil kesimpulan
   ![[Pasted image 20241107134128.png]]![[Pasted image 20241107134230.png]]

#### Contoh 8.5

Dari contoh 8.4, dilakukan pengujian apakah rata-rata waktu pengisian lebih pendek dari 10 detik?

##### Penyelesaian :

1. Hipotesis
   ![[Pasted image 20241107134716.png]]
   
2. Taraf signifikansi $\alpha$=5%
3. Statistik uji t =-2,27
4. Daerah kritis
   ![[Pasted image 20241107134730.png]]
   
5. Mengambil kesimpulan
   ![[Pasted image 20241107134739.png]]




## [[06. Sampel Kecil]]

Pada kasus ukuran sampel besar maka digunakan statistik uji z yang mengikuti distribusi normal. Ketika varians tidak diketahui, maka simpangan baku $\sigma$ di estimasi dengan simpangan baku sampel s. Begitu juga ketika sampel kecil, yaitu ketika n < 30. Sehingga statistik ujinya adalah sama dengan ketika varians ($\sigma^2$) diketahui dengan mengganti o dengan s.

![[Pasted image 20241107135005.png]]




