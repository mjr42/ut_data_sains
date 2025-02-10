---
tags:
  - aljabar_linear_elementer
  - materi_2_ALE
---
# Kegiatan Belajar 1 - Operasi Baris Elementer


## [[01. Operasi Baris Elementer]]

Pengubahan suatu system persamaan, sama artinya dengan pengubahan suatu baris pada matriks yang mewakilinya. Pengubahan dengan proses ini yang nantinya disebut dengan operasi baris elementer.

#### Contoh 2.1.1 (Operasi Baris Elementer)

Selesaikan (tentukan nilai x dan y yang memenuhi) sistem persamaan:

![[Pasted image 20250208154447.png]]

##### Penyelesaian

Ada beberapa cara menentukan nilai x dan y. Salah satu caranya adalah dengan metode substitusi

![[Pasted image 20250208154532.png]]

Jadi diperoleh nilai x = 2 dan y =1 .

Sekarang akan kita bahas penyelesaian Contoh 2.1.1 dengan cara lain, yaitu cara mengubah sistem persamaan menjadi bentuk matriks. Perubahan bentuk sistem persamaan menjadi bentuk matriks sebagai berikut.

![[Pasted image 20250208154613.png]]

Kemudian dilakukan operasi-operasi yang mengubah bentuk sistem persamaan atau mengubah bentuk matriks, antara lain dengan:

1. mengalikan suatu persamaan atau baris dengan bilangan tak nol; 
2. mempertukarkan tempat dua persamaan; atau
3. menambahi suatu persamaan atau baris dengan kelipatan persamaan atau baris lain.

Perbandingan perubahan sistem persamaan dan perubahan matriks sebagai berikut.

![[Pasted image 20250208154700.png]]

![[Pasted image 20250208154708.png]]

![[Pasted image 20250208154724.png]]


Kemudian Tahap I dilanjutkan ke Tahap II:

![[Pasted image 20250208154745.png]]

![[Pasted image 20250208154752.png]]

Hubungan antara pengubahan persamaan dengan pengubahan matriks dapat dilihat sebagai berikut.

![[Pasted image 20250208154808.png]]

Jelas terlihat bahwa pernyataan di sebelah kanan adalah pengubahan pernyataan di sebelah kiri dengan hanya mengganti perkataan persamaan dengan baris. Pengubahan baris suatu matriks dari sistem persamaan linear ini yang disebut dengan operasi baris elementer: Adapun definisi selengkapnya sebagai berikut.


#### Definisi 2.1.2

> ![[Pasted image 20250208154911.png]]


![[Pasted image 20250208154932.png]]

Pengerjaan operasi baris elementer pada suatu matriks P menjadi matriks Q dilakukan dengan cara penulisan seperti berikut ini.

![[Pasted image 20250208154951.png]]

Untuk lebih jelasnya perhatikan Contoh 2.1.2, berikut ini tentang cara penulisan operasi baris elementer.


#### Contoh 2.1.2

Kita akan melakukan 4 macam OBE pada matrik berikut,

![[Pasted image 20250208155035.png]]

##### a. Mengalikan baris ke-2 dengan 5:

![[Pasted image 20250208155106.png]]

##### b. Mempertukarkan baris ke-2 dengan baris ke-3:

![[Pasted image 20250208155120.png]]

##### c. Menambahi baris ke-1 dengan 2 kali baris ke-2:

![[Pasted image 20250208155134.png]]

##### d. Menambahi baris ke-2 dengan (-3) kali baris ke-1 dan sekaligus menambahi baris ke-3 dengan (-2) kali baris ke-1:

![[Pasted image 20250208155147.png]]


![[Pasted image 20250208155153.png]]


Pengerjaan OBE pada suatu matriks yang mempunyai kolom nol tidak
mengubah kolom nol itu, karena:

4. mengalikan baris ke-j dengan bilangan r # 0, mengubah unsur ke-j kolom nol itu dari 0 menjadi r.0 = 0 ;

5. mempertukarkan baris ke-j dengan baris ke-k, berarti menukar unsur ke-j kolom nol itu, yang adalah 0, dengan unsur ke-k kolom itu, yang juga adalah 0, dan juga menukar unsur ke k kolom itu dengan unsur ke-j; atau

6. menambahi baris ke-j dengan p kali baris ke-k berarti menambahi unsur ke-j kolom itu dengan p kali unsur ke-k, jadi menambahi unsur itu dengan p.O.

Jelaslah OBE tak mengubah kolom nol, ini penting nantinya untuk pembahasan sistem persamaan linear yang homogen.


#### Contoh 2.1.3a

Dengan operasi baris elememer (OBF), ubahlah matriks berikut

![[Pasted image 20250208155323.png]]

menjadi :

7. ﻿﻿﻿matriks segitiga atas; dan
8. ﻿﻿﻿matriks diagonal.

##### Jawaban

![[Pasted image 20250208155350.png]]


#### Contoh 2.1.3b

Dengan OBE, ubahlah mariks

![[Pasted image 20250208155531.png]]

menjadi:

9. matriks segitiga atas; dan 
10. matriks diagonal.

##### Jawaban

![[Pasted image 20250208155555.png]]

Proses sampai tahap ini (menjadikan matriks berbentuk matriks segitiga atas) disebut eliminasi Gauss. Proses dapat dilanjutkan sedemikian rupa sehingga matriks berbentuk matriks diagonal.

![[Pasted image 20250208155622.png]]

Matriks terakhir berbentuk matriks diagonal. Proses OBE sampai menjadi matriks diagonal disebut eliminasi Gauss-Jordan.





## [[02. Eliminasi Gauss dan Eliminasi Gauss-Jordan]]

Dengan demkian kita memiliki hal khusus untuk operasi baris elementer (OBE) yaitu eliminasi Gauss dan elminasi Gauss-Jordan.

#### Contoh 2.1.4a

Diketahui matriks H

![[Pasted image 20250208155722.png]]

Kerjakan :

1. ﻿﻿﻿eliminasi Gauss; dan
2. ﻿﻿﻿eliminasi Gauss-Jordan.

##### Jawaban

1. Eliminasi Gauss
![[Pasted image 20250208155801.png]]

2. Eliminasi Gauss-Jordan, kita lakukan OBE untuk bentuk matriks terakhir butir a:
![[Pasted image 20250208155821.png]]


#### Contoh 2.1.4b

Diketahui matriks B

![[Pasted image 20250208155854.png]]

Kerjakan:

1. eliminasi Gauss; dan
2. eliminasi Gauss-Jordan.

##### Jawaban

1. lakukan eliminasi Gauss:

![[Pasted image 20250208155938.png]]

2. lakukan OBE lanjutan (eliminasi Gauss-Jordan) untuk matriks terakhir a.:

![[Pasted image 20250208160004.png]]




## [[03. Menghitung Inverse dengan Eliminasi Gauss-Jordan]]

Eliminasi Gauss-Jordan dapat pula dipakai untuk mencari invers suatu matriks bujursangkar. Bila matriks itu tak punya invers (singular), akan dapat diketahui di tengah proses eliminasi, yaitu jika punya baris nol. Prosedur eliminasi Gauss-Jordan dapat dijelaskan sebagai berikut:

> ![[Pasted image 20250208160048.png]]


Agar lebih jelas, mari kita bahas Contoh 2.2.10 berikut ini.

#### Contoh 2.1.5a

Hitung invers H menggunakan eliminasi Gauss-Jordan

![[Pasted image 20250208160124.png]]

##### Jawaban

![[Pasted image 20250208160229.png]]



#### Contoh 2.1.5b

Hitung invers

![[Pasted image 20250208160312.png]]

dengan menggunakan eliminasi Gauss-Jordan, jika

![[Pasted image 20250208160322.png]]

##### Jawaban

![[Pasted image 20250208160336.png]]

![[Pasted image 20250208160410.png]]

Bagaimana kalau matriks A tak punya invers? Matriks A tak punya invers, apabila eliminasi Gauss-Jordan dikerjakan pada matriks [ A | I ] maka bagian matriks ini akan memuat baris nol. Untuk lebih jelasnya kita bahas Contoh 2.2.6 berikut.


#### Contoh 2.1.6

Periksa, apakah matriks A dan B berikut ini mempunyai invers atau tidak!

![[Pasted image 20250208160502.png]]

##### Penyelesaian

![[Pasted image 20250208160521.png]]


![[Pasted image 20250208160541.png]]

![[Pasted image 20250208160552.png]]











