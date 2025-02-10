---
tags:
  - metode_statistika
---


Rumusan rumusan peluang meliputi peliang beberapa kejadian yang terdiri dari Irisan, Gabungan, Komplemen, Kejadian saling lepas, kejadian saling bebas, dan perhitungan pengambilan titik sampel.

## [[05. Peluang Beberapa Kejadian]]

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

## [[06. Pengambilan Sampel]]

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


