---
tags:
  - kalkulus_1
  - materi_6_KLS1
---
# [[Kagiatan Belajar 1 - Aturan Rantai]]


## 01. Turunan Fungsi Komposisi

 Kita telah membahas fungsi komposisi pada Modul 2. Jika f (x) = sin x dan
g(x) = x^2, maka:

![[Pasted image 20241106200412.png]]

dan 

![[Pasted image 20241106200428.png]]

Sekarang, bagaimana cara menentukan turunan fungsi komposisi F'(x) dan G'(x)? Berikut ini adalah teorema yang membantu kita untuk menentukan turunan fungsi komposisi tersebut:

#### Theorema 6.1.1

![[Pasted image 20241106200459.png]]

##### Bukti :

Teorema ini akan dibuktikan dengan asumsi (persyaratan), jika g diferensiabel di $x_1$ dan f diferensiabel di $g(x_1)$ maka untuk semua $x ≠ x_1$

di dalam selang buka I yang memuat $x_1$ berlaku

![[Pasted image 20241106200802.png]]

Jadi ada selang buka I yang memuat x, sedemikian rupa sehingga,

![[Pasted image 20241106200747.png]]

untuk semua x di I .

Misalkan h(x)=(f∘g)(x) fungsi komposisi f(x) dan g(x), maka menurut Catatan 2 pada Definisi 5.1.1, maka:

![[Pasted image 20241106200933.png]]

Karena h(x) = f(g(x)), maka (6.1.2) dapat ditulis sebagai:

![[Pasted image 20241106200949.png]]

Kemudian dikalikan 1 dalam bentuk:

![[Pasted image 20241106201011.png]]

sehingga :

![[Pasted image 20241106201025.png]]

dan jika limitnya ada, maka:

![[Pasted image 20241106201037.png]]

Karena g diferensiabel di x, maka limit kedua di ruas kanan (6.1.4) ada,
dan

![[Pasted image 20241106201123.png]]

karena

![[Pasted image 20241106201306.png]]

maka maka g kontinu di $x_1$ sehingga:

![[Pasted image 20241106201331.png]]

jadi, jika $x → x_1$ maka $g (x) → g(x_1)$ .

Oleh karena itu, limit pertama ruas kanan (6.1.4) $x → x_1$ dapat diganti

dengan  $g (x) → g(x_1)$  , sehingga diperoleh:

![[Pasted image 20241106201449.png]]

Substitusikan (6.1.5) dan (6.1.6) ke (6.1.4) maka diperoleh:

![[Pasted image 20241106201510.png]]

![[Pasted image 20241106201520.png]]

#### Contoh 6.1.1

![[Pasted image 20241106201542.png]]

##### Penyelesaian:

![[Pasted image 20241106201641.png]]

#### Contoh 6.1.2

![[Pasted image 20241106201655.png]]
##### Penyelesaian:

![[Pasted image 20241106201709.png]]

![[Pasted image 20241106201720.png]]

#### Contoh 6.1.3

![[Pasted image 20241106201822.png]]

##### Penyelesaian :

![[Pasted image 20241106201837.png]]

![[Pasted image 20241106201849.png]]

![[Pasted image 20241106201857.png]]





## 02. Aturan Rantai

Penulisan turunan fungsi komposisi dapat disajikan dengan cara lain yaitu yang dikenal dengan Aturan Rantai. Penulisan dengan cara Aturan Rantai sebagai berikut.

![[Pasted image 20241106202028.png]]

![[Pasted image 20241106202035.png]]

dengan demikian contoh 6.1.1 dapat ditulis sebagai berikut :

![[Pasted image 20241106202118.png]]

Sedangkan Contoh 6.1.2 dapat ditulis sebagai berikut.

![[Pasted image 20241106202132.png]]
![[Pasted image 20241106202143.png]]

#### Contoh 6.1.4

![[Pasted image 20241106202157.png]]

##### Penyelesaian:

![[Pasted image 20241106202239.png]]

#### Contoh 6.1.5a

![[Pasted image 20241106202307.png]]

##### Penyelesaian:

![[Pasted image 20241106202328.png]]

#### Contoh 6.1.5b

![[Pasted image 20241106202346.png]]

##### Penyelesaian :

![[Pasted image 20241106202419.png]]


#### Perluasan Aturan Rantai

Aturan Rantai dapat diperluas menjadi n buah fungsi komposisi.
Misalkan :

![[Pasted image 20241106202455.png]]

maka :

![[Pasted image 20241106202512.png]]

#### Contoh 6.1.6

![[Pasted image 20241106202525.png]]

##### Penyelesaian :

![[Pasted image 20241106202536.png]]
![[Pasted image 20241106202546.png]]

#### Contoh 6.1.7

![[Pasted image 20241106202601.png]]

##### Penyelesaian : 

![[Pasted image 20241106202614.png]]


#### Contoh 6.1.8

![[Pasted image 20241106202637.png]]

##### Penyelesaian : 

![[Pasted image 20241106202706.png]]
![[Pasted image 20241106202927.png]]

#### Contoh 6.1.9

![[Pasted image 20241106203015.png]]

##### Penyelesaian :

![[Pasted image 20241106203031.png]]
![[Pasted image 20241106203043.png]]







## 03. Turunan Fungsi Implisit

![[Pasted image 20241106203129.png]]

#### Contoh Lainnya :

![[Pasted image 20241106203153.png]]

![[Pasted image 20241106203200.png]]

#### Contoh Lainnya :

![[Pasted image 20241106203304.png]]

#### Menurunkan Fungsi Implisit

Sejauh ini kita baru membahas cara penurunan fungsi eksplisit. Sekarang bagaimana cara menurunkan fungsi implisit?

![[Pasted image 20241106203336.png]]

Penurunan fungsi implisit akan lebih jelas kalau kita langsung membahas contoh-contoh.

#### Contoh 6.1.10

![[Pasted image 20241106203404.png]]

##### Penyelesaian :

![[Pasted image 20241106203417.png]]

![[Pasted image 20241106203427.png]]


#### Contoh 6.1.11

![[Pasted image 20241106203451.png]]

##### Penyelesaian :

![[Pasted image 20241106203505.png]]

![[Pasted image 20241106203512.png]]

#### Contoh 6.1.12

![[Pasted image 20241106203526.png]]

##### Penyelesaian :

![[Pasted image 20241106203548.png]]
![[Pasted image 20241106203557.png]]


#### Contoh 6.1.13

![[Pasted image 20241106203622.png]]

##### Penyelesaian :

![[Pasted image 20241106203635.png]]
![[Pasted image 20241106203643.png]]




---


# [[Kegiatan Belajar 2 - Turunan Tingkatan Tinggi]]


## 04. Turunan Tingkat Tinggi

Apabila kita sudah paham betul turunan pertama, maka untuk menentukan turunan kedua, ketiga, keempat dan seterusnya tidak terlampau sukar. Turunan kedua diperoleh dengan cara menurunkan turunan pertama, turunan ketiga diperoleh dengan cara menurunkan turunan kedua, dan seterusnya.

Adapaun definisi secara lengkap turunan tingkat tinggi tersebut sebagai berikut.

#### Turunan Kedua

![[Pasted image 20241106204134.png]]

#### Turunan Ketiga

![[Pasted image 20241106204143.png]]

#### Turunan Keempat

![[Pasted image 20241106204206.png]]

#### Turunan ke -n

![[Pasted image 20241106204216.png]]


#### Cara Penulisan Turunan y = f(x)

![[Pasted image 20241106204242.png]]


Catatan: kolom terakhir tidak digunakan pada Kalkulus I, tetapi digunakan
di modul atau buku-buku atau BMP lain.


#### Contoh 6.2.1

![[Pasted image 20241106204316.png]]

##### Penyelesaian : 

![[Pasted image 20241106204332.png]]
![[Pasted image 20241106204344.png]]
![[Pasted image 20241106204401.png]]


![[Pasted image 20241106204407.png]]
![[Pasted image 20241106204423.png]]

Ini berarti, kalau ingin mencari turunan kedua harus mengetahui turunan pertama, kalau mencari turunan ketiga harus mengetahui rurunan kedua, dan seterusnya.

Selanjutnya untuk menentukan turunan kedua, ketiga dan seterusnya cukup menggunakan rumusnya saja, kecuali secara khusus apabila diminta dengan menggunakan definisi.


#### Contoh 6.2.2

![[Pasted image 20241106204453.png]]
![[Pasted image 20241106204522.png]]


#### Contoh 6.2.3

![[Pasted image 20241106204539.png]]


#### Contoh 6.2.4

![[Pasted image 20241106204600.png]]

##### Penyelesaian : 

![[Pasted image 20241106204618.png]]


#### Contoh 6.2.5

![[Pasted image 20241106204641.png]]

##### Penyelesaian : 

![[Pasted image 20241106204658.png]]






## 05. Percepatan

Kita sudah membahas kecepatan sesaat pada Modul 5 Kegiatan Belajar 2, apabila s(t) fungsi jarak maka v(t) kecepatan sesaat merupakan turunan pertama dari fungsi jarak yaitu v(t) = s'(t).

Sekarang kita akan membahas percepatan yang berkaitan dengan kecepatan dan fungsi jarak. Perhatikan ilustrasi pada Gambar 6.2.1 berikut ini. Sebuah mobil bergerak pada saat t memiliki kecepatan v(t) dan pada saat t + h memiliki kecepatan v(t + h).

![[Pasted image 20241106204803.png]]

![[Pasted image 20241106204812.png]]

Jadi percepatan sesaat merupakan turunan pertama dari kecepatan, sedangkan kecepatan merupakan turunan pertama dari fungsi jarak. Jadi percepatan merupakan turunan kedua dari fungsi jarak, yaitu:

![[Pasted image 20241106204833.png]]


#### Contoh 6.2.6

![[Pasted image 20241106204852.png]]

##### Penyelesaian : 

![[Pasted image 20241106204906.png]]


#### Contoh 6.2.7

![[Pasted image 20241106204929.png]]

#### Penyelesaian : 

![[Pasted image 20241106204948.png]]






## 06. Deret Tailor dan Maclaurin

Deret Taylor dan Maclaurin yang dibahas di sini hanya sebatas kaiatannya dengan turunan tingkat tinggi, tidak sampai pada kekonvergenannya.

Pembahasan secara lengkap termasuk kekonvergenannya akan disajikan di Kalkulus II.


![[Pasted image 20241106205141.png]]

Persamaan garis singgung ini dapat diubah bentuknya menjadi,

![[Pasted image 20241106205153.png]]

Ruas kanan merupakan polinom orde 1 sehingga dapat dituliskan,

![[Pasted image 20241106205210.png]]

![[Pasted image 20241106205247.png]]

![[Pasted image 20241106205339.png]]

![[Pasted image 20241106205352.png]]

#### Polinom / Deret Taylor Orde n pada a

Polinom ini disebut polinom/deret Taylor orde n pada a, dan ini merupa-kan hampiran dari f(x) , sehingga dapat dituliskan:

![[Pasted image 20241106205424.png]]

#### Polinom / Deret Maclaurin Orde n 

Dalam hal a =0 maka polinom yang berkaitan disebut polinom/deret Maclaurin orde n, ditulis:

![[Pasted image 20241106205444.png]]

Deret Taylor dan deret Maclaurin merupakan polinom sebagai hampiran fungsi f(x) di suatu titik (Taylor di x=a, Maclaurin di x =0), dua-duanya berkaitan dengan turunan tingkat tinggi fungsi yang dihampiri.


#### Contoh 6.2.8

![[Pasted image 20241106205511.png]]

##### Penyelesaian : 

![[Pasted image 20241106205531.png]]
![[Pasted image 20241106205547.png]]


#### Contoh 6.2.9

![[Pasted image 20241106205606.png]]

##### Penyelesaian : 

![[Pasted image 20241106205619.png]]
![[Pasted image 20241106205631.png]]


#### Contoh 6.2.10

![[Pasted image 20241106205644.png]]

##### Penyelesaian : 

![[Pasted image 20241106205728.png]]


Deret Taylor dan deret Maclaurin merupakan polinom yang berguna untuk menghampiri suatu fungsi yang diperoleh dari turunan-turunan tingkat tinggi fungsi tersebut. Deret Taylor hampiran di titik sebarang x=a dan deret Maclaurin di titik x=0. Pembahasan lebih dalam deret Taylor dan deret Maclaurin akan dijumpai pada Kalkulus II.