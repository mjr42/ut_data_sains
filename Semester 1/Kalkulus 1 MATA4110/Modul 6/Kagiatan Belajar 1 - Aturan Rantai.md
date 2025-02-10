---
tags:
  - kalkulus_1
  - materi_6_KLS1
---
# Kagiatan Belajar 1 - Aturan Rantai
## [[01. Turunan Fungsi Komposisi]]

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





## [[02. Aturan Rantai]]

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







## [[03. Turunan Fungsi Implisit]]

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




