---
tags:
  - aljabar_linear_elementer
  - materi_1_ALE
---
# Kegiatan Belajar 2 - Sifat Operasi Matriks

Pada BMP Pengantar Matematika/MATA4101 dan Kalkulus I/MATA4110, kita membahas sifat-sifat bilangan real. Hal ini mendorong kita untuk meninjau lebih lanjut sifat-sifat operasi matriks. Sudah kita ketahui penjumlahan matriks adalah komutatif, sedangkan perkalian matriks tak komutatif.

Keasosiatifan berlaku untuk penjumlahan matriks. Akan kita perlihatkan kelak bahwa perkalian matriks juga asosiatif. Perkalian matriks dengan skalar ternyata ekivalen dengan mengalikan matriks itu dengan suatu matriks diagonal yang setiap unsur diagonalnya adalah skalar itu. Beberapa sifat perkalian bilangan real yang diturunkan dari sifat grup bilangan real, seperti hukum kanselasi ternyata tak berlaku untuk perkalian matriks.




## [[07. Sifat Asosiatif Perkalian Matriks]]

Untuk membahas keasosiatifan perkalian matriks, perhatikan Contoh 1.2.1 berikut ini.

#### Contoh 1.2.1

Diketahui matriks

![[Pasted image 20250208141632.png]]

maka :

![[Pasted image 20250208141645.png]]

Kemudian,

![[Pasted image 20250208141701.png]]


Contoh 1.2.1 menunjukkan keberlakuan sifat asosiatif untuk perkalian, yaitu (AB)C = A(BC). Sifat asosiatif ini juga berlaku umum untuk perkalian matriks yang dinyatakan dalam Dalil 1.2.1 berikut ini.


#### Definisi 1.2.1 (Sifat Asosiatif)

> Jika A matriks berukuran m X n, B matriks berukuran n x k, dan C matriks berukuran k X q, maka (AB)C = A (BC).

bukti

> ![[Pasted image 20250208142149.png]]

> ![[Pasted image 20250208142200.png]]



Dengan berlakunya sifat asosiatif pada perkalian matriks, baik (AB)C maupun A(BC) dapat dinyatakan dengan ABC saja.







## [[08. Sifat Distributif Perkalian Matriks]]

Untuk membahas sifat distributif, perhatikan Contoh 1.2.2a dan Contoh 1.2.2b berikut ini.

#### Contoh 1.2.2a

Diketahui matriks,

![[Pasted image 20250208142419.png]]

Maka:

![[Pasted image 20250208142431.png]]

![[Pasted image 20250208142500.png]]


jadi, A(B+C) = AB+ AC .



#### Contoh 1.2.2b

Diketahui matriks,

![[Pasted image 20250208142554.png]]

maka:

![[Pasted image 20250208142610.png]]

jadi, (P+Q)R = PR+QR.


Contoh 1.2.2a dan Contoh 1.2.2b menunjukkan keberlakuan sifat distributif. Sifat distributif secara umum dinyatakan sebagai Dalil 1.2.2 berikut ini.


#### Definisi 1.2.2 (Sifat Distributif)

> ![[Pasted image 20250208142652.png]]


Bukti:

Unsur pada baris ke i kolom ke j matriks A (B + C) adalah

![[Pasted image 20250208142825.png]]

Ruas kanan adalala unsur pada baris ke i kolom ke j matriks AB + AC.


Unsur pada baris ke i kolom ke j matriks (P+Q)R adalah

![[Pasted image 20250208142903.png]]

Ruas kanan adalah unsur pada baris ke i kolom ke j matriks PR + QR.






## [[09. Sifat Perkalian Matriks dengan Bilangan Real dan Matriks Diagonal]]

Perkalian matriks dengan bilangan real (di kiri atau di kanan) adalah mengalikan setiap unsur matriks dengan bilangan real tersebut. Dapat dilihat nanti bahwa hal ini ekivalen dengan mengalikan matriks tersebut dengan suatu matriks diagonal di kiri atau di kanan. Untuk memperoleh gambarannya, perhatikan Contoh 1.2.3a dan Contoh 1.2.3b berikut ini.

#### Contoh 1.2.3a

Diketahui matriks A

![[Pasted image 20250208143250.png]]

matriks diagonal C

![[Pasted image 20250208143308.png]]

matriks diagonal D

![[Pasted image 20250208143325.png]]

dan bilangan real c = 3.

maka dapat diperoleh

![[Pasted image 20250208143344.png]]

Pada Contoh 1.2.3a, matriks A berukuran 3 x 2, matriks diagonal C berukuran 3 x 3 dengan unsur diagonal 3, dan matriks diagonal D berukuran 2 x 2 dengan unsur diagonal 3 memenuhi CA = AD = cA = Ac dengan c = 3.



#### Contoh 1.2.3a

Diketahui matriks B

![[Pasted image 20250208144137.png]]

matriks diagonal E

![[Pasted image 20250208144152.png]]

Matriks diagonal F

![[Pasted image 20250208144210.png]]

dan bilangan real

![[Pasted image 20250208144239.png]]

Maka dapat diperoleh:

![[Pasted image 20250208144255.png]]

Pada Contoh 1.2.3b, matriks B berukuran 2 x 3, matriks diagonal E berukuran 3 x 3 dengan unsur diagonal 2/3, matriks diagonal F berukuran 2 x 2 dengan unsur diagonal 2V3 memenuhi FB = BE = cB = Bc dengan c = 2v3 .

Sesungguhnya, dari Contoh 1.2.3a dan Contoh 1.2.3b berlaku secara umum yang dinyatakan oleh Dalil 1.2.3 berikut ini.

#### Definisi 1.2.3 (Perkalian Matriks dengan Bilangan Real dan matriks Diagonal)

> ![[Pasted image 20250208144408.png]]


Bukti:

Ukuran matriks CA, AD, dan cA sama yaitu m X n, Tuliskan:

![[Pasted image 20250208144445.png]]
maka :

![[Pasted image 20250208144458.png]]

Jadi, CA = AD = cA [terbukti].



#### Contoh 1.2.4

Diketahui A

![[Pasted image 20250208144800.png]]

Maka menurut Dalil 1.2.3, bila matriks

![[Pasted image 20250208144823.png]]

![[Pasted image 20250208144851.png]]

![[Pasted image 20250208144905.png]]

Dari sifat-sifat bilangan real, dengan mudah dapat dibuktikan Dalil 1.2.4 berikut ini.

#### Definisi 1.2.4

> ![[Pasted image 20250208144929.png]]

Bukti:

![[Pasted image 20250208144944.png]]

#### Contoh 1.2.5

Contoh ini menunjukkan keberlakuan Dalil 1.2.4.

![[Pasted image 20250208145005.png]]

![[Pasted image 20250208145012.png]]

![[Pasted image 20250208145027.png]]


Seperti halnya Dalil 1.2.4, sifat-sifat distributif lain yang dinyatakan Dalil 1.2.5 berikut juga dapat dibuktikan menggunakan sifat-sifat bilangan real.

#### Definisi 1.2.5

> ![[Pasted image 20250208145103.png]]


Bukti:

![[Pasted image 20250208145118.png]]


Beberapa dari sifat di atas akan diperlukan nanti dalam pembahasan ruang vektor.







## [[10. Matriks Bujur Sangkar dan Sifat Sifatnya]]

Karena matriks bujur sangkar adalah juga matriks, maka semua sifat operasi matriks juga berlaku untuk matriks bujur sangkar. Pandang himpunan matriks bujur sangkar orde m. Pada himpunan matriks ini perkalian matriks adalah suatu operasi biner. Unsur satuan adalah matriks satuan orde

![[Pasted image 20250208145337.png]]

unsur invers mungkin ada.

#### Definisi 1.2.1

> ![[Pasted image 20250208145435.png]]


Dari Definisi 1.2.1, jelas bahwa invers dari $A^{-1}$ adalah A sendiri, jadi

![[Pasted image 20250208145545.png]]

![[Pasted image 20250208145552.png]]


#### Contoh 1.2.6

Tentukan invers matriks A

![[Pasted image 20250208145613.png]]

Penyelesaian:

![[Pasted image 20250208145628.png]]

Tidak semua matriks bujur sangkar mempunyai invers. Hal ini akan diperlihatkan pada contoh berikut ini.


#### Contoh 1.2.7

Tentukan invers matriks B, jika ada

![[Pasted image 20250208145657.png]]

![[Pasted image 20250208145711.png]]

yang menghasilkan 4 persamaan, yaitu:

yaitu: $(1) p+r =1$; $(2)-p-r=0$; $(3)q+s=0$ ; dan $(4) -q -5 = 1$.

Jika persamaan (1) dan (2) dijumlahkan, maka diperoleh:

![[Pasted image 20250208150039.png]]

berarti menghasilkan pertentangan 0=1. Pertentangan ini diakibatkan karena pengandaian bahwa B mempunyai invers. Jadi, penandaian bahwa B mempunyai invers adalah salah, yang benar adalah B tidak mempunyai invers. Matriks yang tidak memiliki invers disebut matriks singular, yang definisi lengkapnya sebagai berikut.


#### Definisi 1.2.2

> ![[Pasted image 20250208150130.png]]


Jadi, matriks A pada Contoh 1.2.6 adalah matriks tak singular, dan matriks B pada Contoh 1.2.7 adalah matriks singular.

![[Pasted image 20250208150153.png]]

Untuk Contoh 1.2.6, det A =(-1x2) -(0)×(0) =-2#0. Sedangkan Contoh 1.2.7, det B = ((1)x(-1)) -(I)x(-1))=0. Tampaknya ada kaitan antara kenolan determinan matriks dengan kesingularannya. Keterkaitan antara kenolan determinan matriks dengan kesingularan dinyatakan pada Dalil 1.2.6 berikut ini.


#### Definisi 1.2.6

> Matriks A tak singular jika dan hanya jika det A # 0 .

Bukti: (untuk matriks 2 x 2)


diketahui A tak sngular maka harus dibuktikan det A # 0 

Andaikan A punya invers. Akan kita nyatakan matriks invers dalam unsur-unsur dari A , yaitu a,b,c, dan d. Misalkan

![[Pasted image 20250208150321.png]]

![[Pasted image 20250208150328.png]]

![[Pasted image 20250208150349.png]]



diketahui det A # 0 maka harus dibuktikan A tak singular

Andaikan ad -bc # 0 atau det A # 0, maka matriks

![[Pasted image 20250208150416.png]]

![[Pasted image 20250208150428.png]]

![[Pasted image 20250208150435.png]]



#### Contoh 1.2.8

![[Pasted image 20250208150538.png]]


Kita periksa determinannya: det P =(2) (1) - (-2) (-1) = 0.

Jadi, karena det P = 0 maka P tidak punya invers. Matriks apa sajakah yang inversnya dirinya sendiri? Matriks yang inversnya dirinya sendiri adalah matriks yang memenuhi

![[Pasted image 20250208150522.png]]



#### Contoh 1.2.9

Carilah matriks A yang berukuran 2 x 2 yang memenuhi AA = I (yakni A merupakan invers dari dirinya sendiri).

![[Pasted image 20250208150606.png]]

![[Pasted image 20250208150623.png]]


Opsi 1

![[Pasted image 20250208150634.png]]

Opsi 2

![[Pasted image 20250208150646.png]]

Sebagai contoh untuk persamaan $(**)$:

![[Pasted image 20250208150709.png]]






## [[11. Sifat Sifat Inverse]]

Sudah dibahas bahwa invers suatu matriks bujur sangkar adalah tunggal, begitu pula invers dari suatu matriks yang inversnya matriks itu sendiri. Sekarang akan dibahas sifat-sifat invers lainnya. Sebelumnya kita bahas Contoh 1.2.10 terlebih dahulu yang akan mengantarkan kepada sifat-sifat invers tersebut.

#### Contoh 1.2.10

Diketahui matriks

![[Pasted image 20250208150829.png]]

Tentukan

![[Pasted image 20250208150840.png]]

Penyelesaian

![[Pasted image 20250208150914.png]]

![[Pasted image 20250208150928.png]]

#### Definisi 1.2.7 

> ![[Pasted image 20250208150949.png]]


Bukti

![[Pasted image 20250208150958.png]]

Kalau pada bilangan real setiap bilangan yang tak nol punya invers, tetapi kalau pada himpunan matriks bujur sangkar maka ada matriks tak nol yang tak punya invers (singular), seperti terlihat pada Contoh 1.2.11 berikut.

#### Contoh 1.2.11

Buktikan bahwa matriks tak nol A tidak mempunyai Inverse
![[Pasted image 20250208151037.png]]

Bukti

![[Pasted image 20250208151057.png]]

Pada bilangan real berlaku sifat: ab = 0 dan a # 0 berakibat b=0. Sifat ini tidak berlaku untuk matriks: jika AB = O dan A # O tidak menjamin B = O . Ini diperlihatkan pada Contoh 1.2.12 berikut.


#### Contoh 1.2.12

![[Pasted image 20250208151934.png]]

Menghasilkan dua persamaan

![[Pasted image 20250208151956.png]]




## [[12. Transpose Matriks]]

#### Definisi 1.2.3

> ![[Pasted image 20250208152037.png]]


![[Pasted image 20250208152044.png]]

![[Pasted image 20250208152057.png]]


#### Contoh 1.2.13

![[Pasted image 20250208152133.png]]

Perhatikan, transpos matriks D dan E masing-masing adalah dirinya sendiri. Matriks seperti ini disebut matriks simetri, yang definisi formalnya sebagai berikut.



#### Definisi 1.2.4 (Matriks Simetri)

> Matriks yang sama dengan transposnya disebut matriks simetri.


![[Pasted image 20250208152218.png]]


#### Contoh 1.2.14

Periksa, matriks-matriks berikut matriks simetri atau bukan!

![[Pasted image 20250208152253.png]]

Jawab


![[Pasted image 20250208152306.png]]
![[Pasted image 20250208152330.png]]


