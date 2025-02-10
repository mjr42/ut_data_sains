---
tags:
  - metode_statistika
  - materi_8_MS
---
# [[Kegiatan Belajar 1 - Konsep Dasar Pengujian Hipotesis]]

## 01. Pengertian Hipotesis

Setelah dilakukan pendugaan, perlu dilakukan pengujian apakah pendugaan yang kita dapatkan tersebut benar-benar menggambarkan karakteristik populasi. Atau bertujuan untuk mengetahui apakah nilai pendugaan sesuai dengan yang diharapkan. 

Sebagai contoh perusahaan daging ayam sedang berupaya untuk meningkatkan produksi daging ayamnya. Untuk mencapainya dilakukan pemberian vitamin atau obat tambahan. Dengan pemberian tersebut, perusahaan beranggapan bahwa rata-rata berat badan ayam akan naik atau dengan kata lain akan menjadi lebih dari 2,5 kg. Untuk memastikan anggapan tersebut, perlu dilakukan pengujian "Apakah pemberian vitamin atau obat akan meningkatkan rata-rata berat badan menjadi lebih dari 2,5 kg?" Pengujian juga dapat dilakukan pada proporsi, misalnya apakah terdapat 75% peristiwa pencurian dilatarbelakangi oleh keperluan uang untuk membeli ganja atau sejenisnya.

Untuk menjawab hal-hal tersebut perlu dilakukan suatu pengujian hipotesis. Jadi, 
> pengujian hipotesis adalah suatu usaha menguji parameter populasi melalui pengambilan sampel. Hipotesis yang digunakan adalah hipotesis statistik, yaitu suatu anggapan atau pernyataan tentang satu atau lebih populasi yang dapat benar atau salah.


#### Hipotesis Statistik

Hipotesis statististik terdiri dari dua jenis, yaitu:

1) Hipotesis nol (Ho), adalah suatu dugaan awal terhadap pernyataan tertentu yang dapat diterima atau ditolak. Penolakan atau penerimaan tergantung pada hasil eksperimen dan pemilihan sampel.
   
2) Hipotesis alternatif (H1), adalah lawan dari hipotesis nol dan merupakan hipotesis yang ingin dicari (dibuktikan) oleh peneliti.

Dari contoh sebelumnya dapat dituliskan ke dalam hipotesis :  
- Ho: M≤2,5  
- H1: M > 2,5
- Ho : p = 0,75
- H1: p # 0,75


#### Pengujian HIpotesis

![[Pasted image 20241107015644.png]]

Jenis pengujian hipotesis ada dua jenis, yaitu :

1. Satu arah (one way), ditunjukkan oleh tanda pada hipotesis alternatif lebih dari (>) atau kurang dari (<).
   
   Sebagai contoh :
   ![[Pasted image 20241107015838.png]]

2. Dua arah (two way), ditunjukkan oleh tanda pada hipotesis alternatif # Sebagai contoh :
   
   ![[Pasted image 20241107015858.png]]
   
Pemilihan satu arah atau dua arah tentu saja tergantung pada dugaan yang dikemukakan peneliti.




## 02. Kesalahan Jenis I dan II

Hipotesis nol dan alternatif merupakan pernyataan penting tentang suatu karakteristik populasi. Beberapa alternatif kesimpulan dari pernyataan tersebut adalah apakah Ho benar, apakah H1 benar, ataukah bukan keduanya?.

![[Pasted image 20241107020015.png]]

Uji hipotesis dilakukan dengan mengambil sampel, kemudian mengambil kesimpulan dari pengambilan sampel tersebut. Dengan demikian uji hipotesis mengikuti pola berbagai kemungkinan kesalahan. Tabel berikut menunjukkan dua jenis kesalahan dalam uji hipotesis:

![[Pasted image 20241107020031.png]]

Dalam setiap pengambilan keputusan selalu dihadapkan pada jenis kesalahan tersebut, yaitu:

1. ﻿﻿﻿Kesalahan jenis I, merupakan kesalahan menolak hipotesis nol padahal hipotesis nol benar.
   
2. ﻿﻿﻿Kesalahan jenis II, merupakan kesalahan tidak menolak (menerima) hipotesis nol padahal hipotesis nol salah.

Secara teoritis, kedua kesalahan tersebut diharapkan sekecil mungkin melalui pemilihan daerah kritis yang setepat mungkin.

![[Pasted image 20241107020105.png]]


#### Pengambilan Keputusan

Pengambilan keputusan atau kesimpulan dari pengujian hipotesis dilakukan dengan menggunakan suatu taraf signifikansi, yaitu peluang menggunakan kesalahan jenis I. Taraf signifikansi dilambangkan dengan a.

Secara umum nilainya adalah 2,5% (0,025), 5% (0,05), 10% (0,1), dan lain sebagainya.

![[Pasted image 20241107020141.png]]






## 03. Statistik Uji

Seperti yang telah dibahas sebelumnya bahwa pengujian hipotesis memiliki berbagai macam alternatif jawaban. Oleh karena itu, diperlukan suatu batas untuk mengambil kesimpulan. Batas tersebut dinamakan daerah kritis dan titik kritis.

Untuk lower tail test, titik kritis digunakan untuk menentukan apakah nilai statistik uji lebih keil sehingga disimpulkan menolak Ho. Sebaliknya, untuk upper tail test, titik kritis digunakan untuk menentukan apakah nilai statistik uji lebih besar sehingga disimpulkan menolak Ho. Dengan kata lain, titik kritis merupakan nilai terbesar atau terkecil dari statistik uji untuk menolak Ho.




## 04. Prosedur Pengujian Hipotesis

Langkah-langkah pengujian Hipotesis adalah sebagai berikut.

1. ﻿﻿﻿Menentukan hipotesis, yaitu hipotesis nol dan alternatif. Penentuannya berdasarkan dugaan awal oleh peneliti.
2. ﻿﻿﻿Menentukan taraf signifikansi (a).
3. ﻿﻿﻿Menentukan statistik uji. Statistik uji dipilih berdasarkan karakteristik yang akan di uji, jenis hipotesis, asumsi pembentuk distribusi, dan jumlah sampel.
4. ﻿﻿﻿Menentukan daerah kritis. Daerah kritis bergantung pada jenis hipotesis.
5. ﻿﻿﻿Mengambil kesimpulan. Kesimpulan dilakukan dengan membandingkan nilai statistik uji dengan daerah kritis. Apabila statistik uji berada di daerah kritis maka kesimpulannya adalah Ho ditolak. Sebaliknya apabila statistik uji berada di luar kritis maka kesimpulannya adalah Ho gagal ditolak.




---


# [[Kegiatan Belajar 2 - Pengujian Hipotesis Rata Rata]]

engujian hipotesis rata-rata dimaksudkan untuk mengetahui apakah rata-rata populasi berbeda dengan suatu nilai rata-rata tertentu ($\mu_0$). Uji hipotesis ini terdiri dari dua jenis, yaitu ketika jumlah sampel besar (n > 30) dan sampel kecil. Ketika jumlah sampel besar, dibedakan lagi menjadi ketika varians $(\sigma^2$) diketahui dan varians tidak diketahui.

Hipotesis dinyatakan dalam satu arah dan dua arah.

1. Satu Arah
   ![[Pasted image 20241107020621.png]]
   
2. Dua Arah
   ![[Pasted image 20241107020628.png]]


## 05. Sampel Besar

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




## 06. Sampel Kecil

Pada kasus ukuran sampel besar maka digunakan statistik uji z yang mengikuti distribusi normal. Ketika varians tidak diketahui, maka simpangan baku $\sigma$ di estimasi dengan simpangan baku sampel s. Begitu juga ketika sampel kecil, yaitu ketika n < 30. Sehingga statistik ujinya adalah sama dengan ketika varians ($\sigma^2$) diketahui dengan mengganti o dengan s.

![[Pasted image 20241107135005.png]]



---


# [[Kegiatan Belajar 3 - Pengujian Hipotesis - Proporsi]]

Proporsi merupakan karakteristik yang mengikuti kejadian distribusi binominal dam identik dengan Kejadian sukes dan sagal. Dalam proporsi pun dapat dilakukan pengujian hipotesis, yaitu untuk mengetahui apakah proporsi kejadian sukses tertentu berbeda dengan dengan nilai tertentu ($P_o$).

Hipotesis dinyatakan dalam satu arah dan dua arah.

1. Hipotesis satu arah
   ![[Pasted image 20241107135644.png]]

2. Hipotesis dua arah
   
   ![[Pasted image 20241107135655.png]]

Menurut dalil/teorema limit pusat (central limit theorem), distribusi sampling proporsi f dapat mendekati distribusi normal dengan rata-rata p dan simpangan baku 

![[Pasted image 20241107135713.png]]

sehingga didapatkan
![[Pasted image 20241107135856.png]]

Di bawah hipotesis nol, jika $p = p_0$ maka didapatkan statistik uji:

![[Pasted image 20241107135928.png]]

dan

![[Pasted image 20241107135940.png]]

![[Pasted image 20241107135949.png]]

Untuk hipotesis lower tail test:

![[Pasted image 20241107140022.png]]

Untuk hipotesis upper tail test:

![[Pasted image 20241107140121.png]]


#### Contoh 8.6

Sejumlah 400 unit sampel tube televisi telah dipilih secara random. Setelah diteliti ternyata terdapat 12 tube televisi yang rusak atau tidak memenuhi kualitas standar. Dari sampel tersebut, apakah ada bukti yang cukup untuk menyimpulkan bahwa persentase tube yang rusak lebih dari 2%?. Gunakan a =5%. Jika persentase kerusakan memang lebih dari 2% maka proses produksi harus diperbaiki.

##### Penyelesaian

1. Hipotesis
   ![[Pasted image 20241107140324.png]]
   
2. Taraf signifikansi $\alpha$ =5%
   
3. Statistik uji
   ![[Pasted image 20241107140343.png]]
   
4. Daerah kritis
   
   ![[Pasted image 20241107140354.png]]
   
5. Mengambil kesimpulan
   ![[Pasted image 20241107140418.png]]



---



# [[Kegiatan Belajar 4 - Pengujian Hipotesis Varians]]

![[Pasted image 20241107141038.png]]

akan mengikuti distribusi $X^2$ dengan derajat bebas n-1. Uji hipotesis kesaman varians $\sigma^2$ dengan $\sigma_0^2$ dua arah :

![[Pasted image 20241107141205.png]]

Statistik uji hipotesis tersebut adalah :

![[Pasted image 20241107141217.png]]

Karena $X^2$ mengikuti distribusi Chi-square, maka daerah penolakannya dibandingkan dengan nilai Chi-square pada tingkat derajat tertentu. Dengan demikian, $H_0$ ditolak jika

![[Pasted image 20241107141249.png]]

![[Pasted image 20241107141301.png]]

Untuk hipotesis lower tail test:

![[Pasted image 20241107141319.png]]

Untuk hipotesis upper tail test:

![[Pasted image 20241107141333.png]]

![[Pasted image 20241107141343.png]]

#### Contoh 8.7

Dari Contoh 8.4. ujilah apakah varians waktu pengisian sama dengan 3?

##### Penyelesaian

1. Hipotesis
   ![[Pasted image 20241107141541.png]]
   
2. Taraf signifikansi $\alpha$ = 5%
   
3. Statistik uji
   ![[Pasted image 20241107141533.png]]
   
4. Daerah kritis
   ![[Pasted image 20241107141517.png]]
   
5. Kesimpulan
   ![[Pasted image 20241107141509.png]]