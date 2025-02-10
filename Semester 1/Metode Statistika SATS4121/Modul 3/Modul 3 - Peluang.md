---
tags:
  - metode_statistika
---
# [[Kegiatan Belajar 1 - Konsep Dasar Peluang]]

Peluang adalah dasar berfikir yang digunakan dalam statistika. Oleh karenanya, statistika merupakan ilmu yang menggunakan kaidah probabilistik, bukan deterministik seperti matematika.

Data adalah output dari suatu pengukuran sedangkan pe-ubah adalah sesuatu yang diukur. Perbedaan akan kedua hal ini perlu  difahami,. Suatu perubahan acak memiliki nilai-nilai, dan nilai nilai yang muncul dari peubah acak inilah yang dinamakan data. Kemunculain nilai nilai suatu peubah acak memiliki peluang sedangkan data adalah sesuatu yang akan diolah dan dianalisis untuk menghasilkan informasi yang bermakna.


## Konsep Dasar Peluang

Beberapa kejadian akan membentuk suiatu himpunan yang lebih besar yang bisa disebut dengan ruang sampel. Untuk memperoleh hitungan yang benar terkait peluang suatu kejadian maka perlu diketahui seberapa banyak kejadian itu dapat terjadi dan ruang sampelnya terjadi.

Oleh karena itu, dalam menghitung suatu peluang perlu dilakukan suatu perhitungan banyaknya kejadian yang terjadi atau anggota suatu kejadian

> Peluang atau Probabilitas menggambarkan besarnya kesempatan yang akan muncul dalam suatu kejadian tertentu pada kondisi tertentu serta diwakili oleh nilai ainatara 0 dan 1


## Ruang Sampel

Ruang sampel merupakan himpunan semua kemungkinan hasil suatu percobaan. Biasanya dilambangkan dengan huruf "$S$". Setiap kemungkinan dalam suatu ruang sampel disebut unsur atau anggota ruang sampel atau titik sampel.

Dalam peluang salah satu masalah yang harus diselesaikan adalah unsur kemungkinan yang berkaiotan dengan munculnya kejadian tertentu bila suatu percobaan dilakukan. Dalam beberapa kasus, soal peluang dapat diselesaikan dengan menghitung jumlah titik dalam ruang sampel tanpa perlu membuat daftar unsur yang sidebut sebagai aturan perkalian.

>**Teorema 3.1**
>Bisa suatu operasi dapat dilakukan dengan $n_1$ cara, dan bila untuk tiap cara ini operasi kedua dapat dikerjakan dengan $n_2$ cara, maka kedua operasi itu dapat dikerjakan bersama sama dengan $n_1n_2$ cara.


![[Screenshot 2024-09-19 at 14.57.37.png]]

## Kejadian

Kejadian atau yang bisa disebut dengan peristiwa yaitu himpuinan bagian dari ruang sampel. Kejadian dibedakan menjadi dua bagian, yaitu kejadian sederhana dan kejadian majemuk.

> **Kejadian Sederhana**, bila suatu kejadian dapat dinyatakan sebagai sebuah himpunan yang hanya terdiri dari satu titik sampel

> **Kejadian Majemuk**, kejadian yang dapat dinyatakan sebagai gabungan beberapa kejadian sederhana.


## Peluang Suatu Kejadian

Secara umum peluang suatu kejadian dapat didefinisikan sebagai perbandingan banyaknya titik sampel kejadian dengan banyaknya anggota ruang sampel kejadian

> Peluang Suatu Kejadia. misalkan A adalah suatu kejadian yang terjadi maka nilai peluang kejadian A dinyatakan dengan :
> 
> $P(A) = \frac{n(A)}{n(S)}$
> 
> Dimana:
> 	n(A) adalah banyaknya kejadian A yang terjadi
> 	n(S) adalah banyaknya seluruh kejadian yang terjadi
> 	n(S) > n(A)

Adapun syarat syarat yang harus dipenuhi dalam peluang sebagai berikut:

![[Screenshot 2024-09-19 at 15.46.12.png]]





# [[Kegiatan Belajar 2 -  Rumus-Rumus Peluang]]

Rumusan rumusan peluang meliputi peliang beberapa kejadian yang terdiri dari Irisan, Gabungan, Komplemen, Kejadian saling lepas, kejadian saling bebas, dan perhitungan pengambilan titik sampel.

## Peluang Beberapa Kejadian

Peluang beberapa kejadian sering disebut dengan peluang kejadian majemuk. Kejadian majemuk dapat terjadi dengan cara mengkombinasikan dua atau lebih kejadian. Pengkombinasian dua atau lebih kejadian dapat dilakukan dengan cara gabungan, irisan, dan komplemen.

#### 1. Irisan

Irisan antar dua kejadian A dan B yang dilambangkan dengan A ∩ B merupakan kejadian yang mengandung semu elemen yang berada di A dan B sekaligus. Notasi ∩ juga berarti "dan"

> Irisan A dan B dapat dinotasikan dengan:
> 
> $A∩B=(x|x∈ A$ dan $x∈B)$

![[Screenshot 2024-09-19 at 15.54.13.png]]

---


#### 2. Gabungan (Union)

Gabungan dua buah kejadian, A dan B dilambangkan dengan A ∪ B merupakan kejadian yang mengandung semua elemen dari A, atau B, atau keduanya. Notasi "∪" dapat berarti "Atau"

> Gabungan A dan B dapat dinotasikan dengan
> 
> $A∪B=(x|x∈A$ atau $x∈b)$

![[Screenshot 2024-09-19 at 15.57.07.png]]

---


#### 3. Komplement

Komplement dari kejadian A terhadap S yang dilambangkan dengan A' merupakan himpunan semua elemen S yang tidak berada dalam A.

> Komplemen A terhadap S dapat dinotasikan dengan 
> 
> $A' = (x|x∈S, x∉A)$

![[Screenshot 2024-09-19 at 15.59.43.png]]

Jika A adalah suatu kejadian pada suatu percobaan peluang komplemen, maka pelung komplemen kejadian A adalah

>$P(A')=1-P(A)$


---

#### 4. Kejadian Saling Lepas

Dua kejadian disebut sebagai kejadian saling lepas (Mutually Exclusive) apabila kedua kejadian tersebut tidak terjadi pada saat yang bersamaan. Dua kejadian saling lepas tidak akan mungkin memiliki anggota ruang sampel yang sama. Jika ada dua kejadian memiliki anggota sampel yang sama, maka dua kejadian tersebut bukan merupakan kejadian saling lepas. Dengan kata lain kejadian saling lepas adalah kejadian yang tidak memiliki irisan

> Dua kejadian saling lepas dinotasikan dengan A // B atau A ∩ B = 0

![[Screenshot 2024-09-19 at 19.59.57.png]]

Sehingga peluang kejadian A dan B dapat disimpulkan

a) $P(A∪B)=P(A)+P(B)$, jika A dan B saling lepas
b) $P(A∪B)=P(A)+P(B)-P(A∩B)$, jika A dan B tidak saling lepas

![[Screenshot 2024-09-19 at 20.03.08.png]]


---

#### 5. Kejadian Saling Bebas

Kejadian saling lepas adalah dua buah kejadian yang tidak memiliki irisan atau tidakl akan terjadi dalam waktu yang bersamaan. Sedangkan dua kejadian tersebut saling bebas (Mutually Exhaustic), jika kejadian pertama tidak tergantung pada terjadinya kejadian kedua.

Misalnya, kejadian A dikatakan bebas dari kejadian B jika terjadinya A tidak tergantung pada terjadinya B. Peluang terjadinya dua kejadian saling bebas sama dengan hasil kali peluang kedua kejadian

> $P(A∩B) = P(A)×P(B)$

![[Screenshot 2024-09-19 at 20.08.48.png]]

![[Screenshot 2024-09-19 at 20.07.53.png]]

## Pengambilan Sampel

Dalam menentukan peluang, hal yang sudah pasti dilakukan adalah mengetahui banyaknya ruang kejadian dan ruang sampel. Cara menentukan banyaknya anggota ruang sampel dan ruang kejadian ini bisa dengan cara permutasi atau kombinasi.

#### 1. Permutasi

Permutasi merupakan suatu susunan yang dibentuk oleh keseluruhan atau sebagian dari sekumpulan benda. Cara penyusunan benda ini dengan memperhatikan urutan. Misalnya, dalam permutasi AB berbeda dengan BA

> Teorama 3.2
> Banyaknya permutasi $n$ benda yang berlainan adalah $n!$

![[Screenshot 2024-09-19 at 20.13.16.png]]

> Teorama 3.3
> Panyaknya permutasi n benda yang berlainan bila diambil r sekaligus adalah $_nP_r= \frac{n!}{(n-r)!}$

![[Screenshot 2024-09-19 at 20.15.04.png]]

##### Permutasi Lingkaran

Selain kedua konsep permutasi tersebut terdapat beberapa cara penyusunan benda-benda yang disebut sebagai permutasi melingkar atau permutasi siklis. Permutasi ini berkaitan dengan penyusunan benda-benda dalam bentuk lingkaran atau penyusunan sederetan objek yang melingkar. Misalnya bagaimana cara menempati posisi tempat duduk pada meja yang bundar.

Dua permutasi melingkar tidak dianggap berbeda,. karena saat dua benda atau objek ditempatkan di posisi melingkar maka objek pertama pasti harus menjadi patokan, sehingga posisinya tetap. Mau digeser kemanapun objek pertama itu tidak akan mengubah cara penyusunannya.

Sementara itu kedua objek ditempatkan di sebelah objek pertama, jadi walaupun objek pertama digeser-geser, tetap saja posisi penempatannya sama, sehingga permutasi melingkar dari dua objek adalah satu.

![[Screenshot 2024-09-19 at 20.20.22.png]]

Misalnya objek pertama A dan objek kedua B. Karena A sudah menhjadi patokan, maka cara berikutnya adalah menempatkan B, karena hanya satu objek yaitu B maka cara menempatkan B adalah 1 cara. Sehingga cara menempatkan A dan B dalam posisi melingkar hanya ada satu cara yaitu AB. Disini jelas bahwa BA akan sama saja dengan AB karena posisinya melingkar.


![[Screenshot 2024-09-19 at 20.22.09.png]]
Misalkan A adalah patokannya, Katakanlah arah susunan tempat duduk ini adalah searah jarum jam. maka cara penyusunannya yang dapat dilakukan adalah hanya menempatkan B dan C. Apakah B berada di sebelah kanan atau kiri A. sehingga ada dua cara yang dapat dilakukan, yaitu ABC dan ACB.

Jadi untuk permutasi melingkar dari 3 objek akan ada dua kemungkinan susunan yang dapat terjadi. Hasil ini sesuai logika bahwa dari ketiga objek tersebut ada salah satu yang menjadi patokan, sehingga cara penyusunan berikutnya adalah 2 objek sisanya yang dapat disusun dengan $2!$ cara.

Untuk n objek, ada beberapa susunan yang dapat terjadi? Karena 1 objeck akan menjadi patokan, maka sisanya adalah sebanyak $(n-1)!$.

>Teorema 3.4
>Banyaknya permutasi n benda yang berlainan bila disusun melingkar adalah $(n-1)!$


##### Permutasi n benda yang berlainan

Misalkan terdapat n buah benda yang terdiri atas beberapa jenis. Jenis pertama sebanyak $n_1$, jenis kedua sebanyak $n_2$, dan seterusnya jenis ke-$k$ ada sebanyak $n_k$. Sehingga $n=n_1+n_2+...+n_k$

> Teorema 3.5
> Banyaknya permutasi n benda yang berlainan bila n benda yang n_1 diantaranya berjenis pertama, n_2 berjenis kedua, ... , n_k berjenis ke-k adalah 
> $\frac{n!}{n_1!n_2!...n_k!}$


##### Membagi n benda ke dalam r tempat

Terkadang kita berhadapan pada permasalahan dimana kita ingin menentukan banyaknya cara menyekat atau membagi n benda ke dalam r tempat atau sel. dengan catatan sel sel yang dihasilkan tidak saling tumpang tindih atau gabungan semuanya menghasilkan himpunan asalnya. Dalam hal ini susunan objek-objek dalam sel tidak diperhatikan.

Misalnya, himpuinan {A,B,C,D} adakn disekat menjadi dua sel. Sel pertama berisi 3 objeck dan sel kedua berisi satu objek. maka kemungkinan sekatannya adalah {(ABC),(D)} {(ABD),(C)} {(ADC),(B)} {(DBC),(A)}.

Banyaknya sekatan dalam ilustrasi tersebut dapat dihitung dari :
![[Screenshot 2024-09-20 at 08.19.42.png]]

Bilangan yang ada di dalam kurung yang diatas menyatakan keseluruhan objek, sedangkan yang dibawah menyatakan banyaknya unsur dalam setiap sel.

>Teorama 3.6
>Banyaknya permutasi n benda ke dalam k sel, dengan n_1 unsur dalam sel pertama, n_2 unsur sel kedua dan demikian seterusnya
>![[Screenshot 2024-09-20 at 08.20.55.png]]

![[Screenshot 2024-09-20 at 08.21.12.png]]


#### 2. Kombinasi

Lain halnya dengan permutasi yaitu cara penyusunan objek dengan memandang urutan, maka yang dinamakan dengan kombinasi adalah cara penyusunan objek dengan tidak memandang urutan, Konsep kombinasi ini berguna pada saat kita menghadapi suatu pertanyaan bagaimana mengambil r benda dari n benda yang tersedia. 

> Teorema 3.6
> Banyaknya kombinasi r benda dari n benda yang berbeda adalah
> ![[Screenshot 2024-09-26 at 07.58.21.png]]
> \


##### Contoh 3.22

Dari 4 orang anggota partai Republik dan 3 orang anggota partai Demokrat, hitung banyaknya komisi yang terdiri atas 3 orang dengan komposisi 2 orang dari partai Republik dan 1 orang dari partai Demokrat.


###### Langkah 1: Identifikasi komposisi anggota komisi

Kita diminta untuk membentuk komisi yang terdiri dari:

•	2 orang dari partai Republik
•	1 orang dari partai Demokrat

Sehingga kita akan menghitung dua kombinasi:

1.	Cara memilih 2 orang dari 4 anggota partai Republik.
2.	Cara memilih 1 orang dari 3 anggota partai Demokrat.


###### Langkah 2: Menghitung kombinasi memilih 2 dari 4 anggota partai Republik

Untuk menghitung berapa cara kita bisa memilih 2 orang dari 4 anggota partai Republik, kita menggunakan rumus kombinasi:


$C(n, r) = \frac{n!}{r! \cdot (n - r)!}$


Dengan  $n = 4$  dan  $r = 2$ , maka:


$C(4, 2) = \frac{4!}{2! \cdot (4 - 2)!} = \frac{4 \times 3 \times 2!}{2! \times 2!} = 6$


Jadi, ada 6 cara untuk memilih 2 orang dari 4 anggota partai Republik.


###### Langkah 3: Menghitung kombinasi memilih 1 dari 3 anggota partai Demokrat

Untuk menghitung berapa cara kita bisa memilih 1 orang dari 3 anggota partai Demokrat, kita juga menggunakan rumus kombinasi:


$C(3, 1) = \frac{3!}{1! \cdot (3 - 1)!} = \frac{3!}{1! \times 2!} = \frac{3 \times 2!}{1! \times 2!} = 3$


Jadi, ada 3 cara untuk memilih 1 orang dari 3 anggota partai Demokrat.


###### Langkah 4: Mengalikan hasil kombinasi

Karena kita harus memilih 2 orang dari partai Republik dan 1 orang dari partai Demokrat, maka total cara untuk membentuk komisi ini adalah hasil kali dari dua kombinasi yang sudah kita hitung:


$Total = C(4, 2) \times C(3, 1) = 6 \times 3 = 18$


###### Kesimpulan:

Jumlah cara untuk membentuk komisi yang terdiri atas 2 orang dari partai Republik dan 1 orang dari partai Demokrat adalah 18 cara.

**Jadi, langkah-langkahnya adalah:**

1.	Hitung kombinasi 2 orang dari 4 anggota partai Republik.
2.	Hitung kombinasi 1 orang dari 3 anggota partai Demokrat.
3.	Kalikan kedua hasil kombinasi untuk mendapatkan total cara.



# [[Kegiatan Belajar 3 -  Peluang Bersyarat dan Teorema Bayes]]

## Peluang Bersyarat

Peluang bersyarat dapat terjadi jika dua kejadian terjadi secara berurutan dan kedua kejadian tersebut tidak saling bebas namun saling mempengaruhi.

![[Screenshot 2024-09-26 at 08.15.12.png]]


#### Peluang yang terjadi sekaligus dengan syarat

Dalam konsep peluang bersyarat dikenal suatu kaidah penggandaan yang diperoleh dengan menggandakan kedua sisi rumus peluang bersyarat dengan P(A) sehingga memungkinkan untuk menghitung peluang terjadinya dia kejadian sekaligus

> Teorema 3.8
> Bila dalam suatu percobaan kejadian A dan B keduanya dapat terjadi sekaligus maka:
> ![[Screenshot 2024-09-26 at 08.16.37.png]]


#### Peluang kejadian A dan B serentak saling bebas

Jadi peluang terjadinya A dan B terjadi serentak sama dengan peluang A terjadi dikalikan dengan peluang terjadinya B bila A terjadi

>Teorema 3.9
>Bila kedua kejadian A dan B saling bebas maka:
> ![[Screenshot 2024-09-26 at 08.19.46.png]]


Jadi untuk mendapatkan peluang bahwa dua kejadian bebas akan terjadi secara bersamaan yaitu dengan mengalikan peluang kedua kejadian

> Teorema 3.10
> Bila dalam suatu percobaan kejadian kejadian $A_1, A_2, A_3, A_k$ dapat terjadi maka :
> ![[Screenshot 2024-09-26 at 08.21.53.png]]

> Teorema 3.11
> Bila kejadian kejadian $A_1, A_2, A_3, A_k$ bebas maka:
> ![[Screenshot 2024-09-26 at 08.22.40.png]]



#### Contoh 3.23

Milaskan, ruang S terdiri atas populasi sarjana di suatu kota. POpulasi dikategorikan menurut jenis kelamin dan status pekerjaan. Datanya adalah sebagai berikut :

![[Screenshot 2024-09-26 at 08.25.35.png]]

Dari populasi tersebut, akan dioambil secara acak satu orang yang ditugaskan mempublikasikan pentingnya didirikan industri baru di kota tersebut.
Perhatikan kejadian kejadian tersebut:

M : yang terpilih laki laki
E : yang terpilih telah bekerja

Berapa peluang terpilihnya orang laki laki bila yang diinginkan adalah orang yang bekerja?

##### Penyelesaian

Diketahui bahwa kita akan memilih orang yang **bekerja**. Kita diminta menghitung peluang terpilihnya orang laki-laki di antara orang-orang yang bekerja. Mari kita selesaikan soal ini langkah demi langkah.

**Data pada tabel:**

• Laki-laki bekerja: 460 orang

• Laki-laki menganggur: 40 orang

• Perempuan bekerja: 140 orang

• Perempuan menganggur: 260 orang

Total populasi: 900 orang


###### Langkah 1: Identifikasi kejadian

Dari soal, kita diperkenalkan dua kejadian:

•	 M : yang terpilih adalah laki-laki.
•	 E : yang terpilih adalah orang yang bekerja.

Peluang yang ditanyakan adalah peluang terpilihnya laki-laki bila kita sudah tahu bahwa yang dipilih adalah orang yang bekerja, yang dinyatakan sebagai peluang kondisional  P(M|E) .


###### Langkah 2: Rumus peluang kondisional

Peluang kondisional  P(M|E)  dihitung menggunakan rumus:

$P(M|E) = \frac{P(M \cap E)}{P(E)}$

Artinya, peluang terpilihnya laki-laki yang bekerja sama dengan peluang seseorang adalah laki-laki dan bekerja dibagi dengan peluang terpilihnya seseorang yang bekerja.


###### Langkah 3: Hitung komponen peluang

1.	Peluang  $P(E)$ , yaitu peluang terpilihnya orang yang bekerja:
	Jumlah orang yang bekerja adalah 600 orang (460 laki-laki + 140 perempuan).
	Jadi,  $P(E)$  dihitung sebagai:
	
	$P(E) = \frac{600}{900} = \frac{2}{3}$

2.	Peluang  $P(M \cap E)$ , yaitu peluang terpilihnya laki-laki yang bekerja:
	Jumlah laki-laki yang bekerja adalah 460 orang.
	Jadi,  P(M \cap E)  dihitung sebagai:
	
	$P(M \cap E) = \frac{460}{900} = \frac{23}{45}$ 



###### Langkah 4: Hitung peluang kondisional

Sekarang, kita substitusi nilai  P(M \cap E)  dan  P(E)  ke dalam rumus peluang kondisional:

$P(M|E) = \frac{P(M \cap E)}{P(E)} = \frac{\frac{460}{900}}{\frac{600}{900}} = \frac{460}{600}$


Sederhanakan pecahan:

$P(M|E) = \frac{460}{600} = \frac{23}{30}$


Rumusan tersebut diperoleh:
![[Screenshot 2024-09-26 at 08.32.30.png]]

###### Kesimpulan

Peluang terpilihnya orang laki-laki bila yang diinginkan adalah orang yang bekerja adalah $\frac{23}{30}$ atau sekitar 0,767 (76,7%).

**Jadi, langkah-langkah utamanya adalah:**

1.	Mengidentifikasi kejadian-kejadian dan menggunakan rumus peluang kondisional.
2.	Menghitung peluang kejadian gabungan  P(M \cap E) .
3.	Menghitung peluang kejadian  P(E) .
4.	Substitusi ke dalam rumus peluang kondisional dan sederhanakan.



#### Contoh 3.24

Peluang kereta api Gajayana berangkat tepat pada waktunya p(A) = 0,85. Peluang kereta api Gajayana datang tepat waktu adalah p(B) = 0,90
dan peluang kereta api tersebut berangkat dan datang tepat waktu adalah P(A∩B) = 0,75

Hitunglah:
- Peluang kereta Gajayana datang tepat waktu jika diketahui kereta tersebut berangkat tepat pada waktunya
- Peluang bahwa kereta api Gajayana berangkat tepat waktu bila diketahui kereta api tersebut datang tepat pada waktunya

##### Penyelesaian

Diketahui:

•	 P(A) = 0,85  → Peluang kereta api Gajayana berangkat tepat pada waktunya.
•	 P(B) = 0,90  → Peluang kereta api Gajayana datang tepat pada waktunya.
•	 P$(A \cap B)$ = 0,75  → Peluang kereta api berangkat dan datang tepat pada waktunya.

Kita diminta untuk menghitung:

1.	Peluang kereta api datang tepat waktu jika diketahui berangkat tepat pada waktunya.

2.	Peluang kereta api berangkat tepat waktu jika diketahui datang tepat pada waktunya.


###### Langkah 1: Peluang kereta api datang tepat pada waktunya bila diketahui kereta berangkat tepat waktu

Ini adalah peluang kondisional  P(B|A) , yang berarti “peluang kereta api datang tepat waktu jika diketahui berangkat tepat waktu.”

Rumus peluang kondisional adalah:

	$P(B|A) = \frac{P(A \cap B)}{P(A)}$

Substitusikan nilai yang diketahui:

	$P(B|A) = \frac{0,75}{0,85}$

Hitung hasilnya:

	$P(B|A) \approx 0,882$

Jadi, **peluang kereta api datang tepat pada waktunya bila diketahui kereta berangkat tepat pada waktunya adalah 0,882** atau sekitar 88,2%.


###### Langkah 2: Peluang kereta api berangkat tepat pada waktunya bila diketahui kereta datang tepat waktu

Ini adalah peluang kondisional  P(A|B) , yang berarti “peluang kereta api berangkat tepat waktu jika diketahui datang tepat waktu.”

Rumus peluang kondisional juga serupa:

	$P(A|B) = \frac{P(A \cap B)}{P(B)}$

Substitusikan nilai yang diketahui:

	$P(A|B) = \frac{0,75}{0,90}$

Hitung hasilnya:

	$P(A|B) \approx 0,833$

Jadi, **peluang kereta api berangkat tepat pada waktunya bila diketahui kereta datang tepat pada waktunya adalah 0,833** atau sekitar 83,3%.


###### Kesimpulan:

1.	Peluang kereta api datang tepat waktu jika diketahui berangkat tepat waktu adalah 88,2%  $(P(B|A))$ .

2.	Peluang kereta api berangkat tepat waktu jika diketahui datang tepat waktu adalah 83,3%  $(P(A|B))$ .

Langkah-langkah utama dalam menyelesaikan soal ini adalah:

1.	Mengidentifikasi peluang kondisional yang diminta.
2.	Menggunakan rumus peluang kondisional  $P(B|A) = \frac{P(A \cap B)}{P(A)}$  atau  $P(A|B) = \frac{P(A \cap B)}{P(B)}$
3.	Menghitung hasil dengan substitusi nilai-nilai yang diketahui.


## Teorema Bayes

Teorema bayes diawali dari konsep peluang total yang merupakan kejadian-kejadian $B_1, B_2, B_3, B_n ≠ 0$ untuk $i=1,2,3,...,n$ Maka untuk sembarang kejadian A yang merupakan himpunan bagian S berlaku:

![[Screenshot 2024-09-26 at 08.46.14.png]]

Illustrasi dari konsep Bayes dapat dilihat pada gambar berikut:

![[Screenshot 2024-09-26 at 08.46.39.png]]
>  Teorema 3.11
>  Misalkan kejadian-kejadian B_1, B_2, B_3, ..., B_k membentuk partisi dari ruang sampel S dimana P(B) ≠ 0 untuk i=1,2,3,...,n. Andaikan A adalah sembarang peristiwa dalam S sedemikian rupa hingga P(A)≠) maka untuk k = 1,2,3,..n berlaku:
>  
>  ![[Screenshot 2024-09-26 at 08.49.43.png]]


###### Bentuk umum Teorema Bayes adalah seperti yang ditunjukkan pada gambar:

	$P(B_k | A) = \frac{P(B_k \cap A)}{\sum_{i=1}^{n} P(B_i \cap A)} = \frac{P(B_k) P(A | B_k)}{\sum_{i=1}^{n} P(B_i) P(A | B_i)}$


###### Penjelasan Notasi:

•	 $P(B_k | A)$  : Peluang kejadian  $B_k$  terjadi jika diketahui kejadian  A  terjadi.
•	 $P(B_k \cap A)$  : Peluang kejadian  $B_k$  dan  A  terjadi bersamaan.
•	 $P(A | B_k)$  : Peluang kejadian  A  terjadi jika diketahui kejadian  $B_k$  terjadi.
•	 $P(B_k)$  : Peluang kejadian  $B_k$  terjadi.
•	 $\sum_{i=1}^{n} P(B_i \cap A)$  : Jumlah peluang semua kejadian  $B_i$  dengan kejadian  A .


###### Langkah-langkah Teorema Bayes:

1.	**Identifikasi Peluang Dasar (Prior Probability):**
	Dalam rumus ini,  $P(B_k$)  adalah peluang dasar atau prior dari kejadian  $B_k$ , yaitu peluang  $B_k$  terjadi sebelum kita mengetahui bahwa  $A$  telah terjadi.

2.	**Hitung Peluang Bersyarat (Conditional Probability):**
	Kita menghitung peluang bersyarat  $P(A | B_k)$ , yaitu peluang kejadian  A  terjadi dengan syarat bahwa  $B_k$  telah terjadi. Informasi ini bisa berasal dari data historis, statistik, atau asumsi yang diberikan dalam soal.

3.	**Hitung Peluang Total (Total Probability):**
	Untuk mendapatkan denominator (penyebut) pada rumus di atas, kita harus menghitung total peluang kejadian  A  terjadi, yang merupakan jumlah dari semua peluang bersyarat  $P(A | B_i)$  dikalikan dengan prior dari masing-masing  $B_i$  untuk setiap  $i$ . Ini merupakan bagian dari Teorema Total Peluang.
	
	Rumus total peluang:
	$P(A) = \sum_{i=1}^{n} P(B_i) P(A | B_i)$
	
	Di mana  $B_1, B_2, …, B_n$  merupakan semua kemungkinan kejadian yang dapat menyebabkan terjadinya  A .

4.	**Substitusi ke dalam Teorema Bayes:**
	Setelah kita mendapatkan peluang total  $P(A)$  (penyebut), kita dapat menghitung peluang kondisional  $P(B_k | A)$  dengan memasukkan nilai prior  $P(B_k)$  dan peluang bersyarat  $P(A | B_k)$  ke dalam rumus:
	
	$P(B_k | A) = \frac{P(B_k) P(A | B_k)}{P(A)}$
	
	Ini memberikan kita peluang posterior, yaitu peluang bahwa  B_k  terjadi setelah diketahui bahwa  A  telah terjadi.

#### Contoh 3.14

Suatu perusahaan besar menggunakan 3 hotel sebagai tempat menginap para langganannya. Dari pengalaman yang lalu diketahui bahwa 20% langganannya ditempatkan di Hotel I, 50% di hotel B, dan 30% di hotel S. Bila 5% kamar mandi di hotel I tidak berfungsi dengan baik, 4% di hotel B dan 8% di hotel S. berapa peluang bahwa

1. Seseorang langganan mendapat kamar yang kamar mandinya tidak berfungsi
2. Seseorang yang mendapat kamar mandi yang tidak baik ditempatkan di hotel S?

##### Penyelesaian

###### Bagian a: Peluang seorang pelanggan mendapat kamar dengan kamar mandi yang tidak berfungsi

Untuk menghitung peluang total seorang pelanggan mendapatkan kamar mandi yang tidak berfungsi, kita gunakan Teorema Total Peluang. Peluang total tersebut adalah jumlah dari peluang kamar mandi tidak berfungsi di setiap hotel, dikalikan dengan peluang pelanggan ditempatkan di hotel tersebut.

Rumus Teorema Total Peluang:

	$P(T) = P(T|I) \cdot P(I) + P(T|B) \cdot P(B) + P(T|S) \cdot P(S)$


Substitusikan nilai-nilai yang diketahui:

	$P(T) = (0,05 \times 0,20) + (0,04 \times 0,50) + (0,08 \times 0,30)$


Hitung setiap komponen:

	$P(T) = (0,01) + (0,02) + (0,024) = 0,054$


Jadi, **peluang seorang pelanggan mendapat kamar dengan kamar mandi yang tidak berfungsi adalah 0,054** atau 5,4%.


###### Bagian b: Peluang seseorang yang mendapatkan kamar mandi yang tidak berfungsi ditempatkan di hotel S

Untuk pertanyaan ini, kita menggunakan Teorema Bayes karena kita diminta mencari peluang pelanggan ditempatkan di hotel S dengan syarat bahwa kamar mandi yang didapat tidak berfungsi.

Rumus Teorema Bayes:

	$P(S|T) = \frac{P(T|S) \cdot P(S)}{P(T)}$


Dari bagian a, kita sudah menghitung  P(T) = 0,054 . Sekarang substitusikan nilai yang diketahui ke dalam rumus:

	$P(S|T) = \frac{(0,08 \times 0,30)}{0,054} = \frac{0,024}{0,054}$


Hitung hasilnya:

	$P(S|T) \approx 0,444$


Jadi, **peluang seseorang yang mendapat kamar mandi yang tidak berfungsi ditempatkan di hotel S adalah 0,444** atau 44,4%.

###### Kesimpulan:

1. Peluang seorang pelanggan mendapatkan kamar dengan kamar mandi yang tidak berfungsi adalah **5,4%**.

2. Peluang seseorang yang mendapatkan kamar mandi yang tidak berfungsi ditempatkan di hotel S adalah **44,4%**.


**Langkah-langkah utama untuk menyelesaikan soal ini adalah:**

1. Menghitung peluang total menggunakan **Teorema Total Peluang** untuk soal a.

2. Menggunakan **Teorema Bayes** untuk menghitung peluang kondisional pada soal b.


