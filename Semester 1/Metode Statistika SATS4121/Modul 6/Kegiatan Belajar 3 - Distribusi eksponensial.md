---
tags:
  - metode_statistika
  - materi_6_MS
---
## Kegiatan Belajar 3 - Distribusi eksponensial

Distribusi eksponensial sering disebut sebagai distribusi waktu. Peristiwanya sangat erat dengan peristiwa pada distribusi Poisson. Saudara perlu mengingat bahwa distribusi Poisson digunakan untuk menghitung jumlah kejadian selama jangka waktu atau selang tertentu.

Dalam banyak hal, jangka waktu atau selang waktu dapat berupa variabel acak. Nah, variabel acak yang berupa jangka waktu memiliki distribusi eksponensial. Misalnya, dalam suatu antrian kapal yang berlabuh di suatu dermaga, jumlah kedatangan kapal mengikuti distribusi Poisson, sedangkan waktu antara kedatangan kapal mengikuti distribusi eksponensial.

Andaikan X, mengikuti distribusi Poisson dengan parameter 𝜆, dimana 𝜆 menyatakan rataan banyaknya kejadian per satuan waktu, maka waktu sampai kejadian sukses pertama ($T_1$) mengikuti distribusi eksponensial dengan parameter β yang menyatakan rataan waktu antar kejadian, dimana 

![[Pasted image 20241027135039.png]]

Fungsi dari $T_1$ dapat diturunkan dengan menggunakan fungsi distribusi Poisson. $X_t$ dalam distribusi Poisson berarti jumlah kejadian sukses dalam interval t, sementara $T_1$, menyatakan waktu sampai terjadinya sukses maka $T_1 >t$ artinya dalam waktu tersebut tidak ada kejadian sukses, sehingga:

![[Pasted image 20241027135200.png]]

$T_1$ disebut sebagai waktu kejadian yang pertama dalam proses Poisson dan disebut waktu ulang atau waktu antara dua kejadian yang berurutan, karena kejadian sukses independen dari waktu ke waktu. Fungsi distribusi kumulatif dari $T_1$ adalah:

![[Pasted image 20241027135238.png]]

Dari fungsi distribusi kumulatif tersebut dapat diturunkan fungsi distribusi eksponensial. Dengan mengganti $T_1$ dengan $X$, distribusi variabel acak $X$ dinyatakan sebagai berikut.

#### Distribusi eksponensial

![[Pasted image 20241027135331.png]]

Berikut adalah gambar fungsi probability distribution function (pdf) dari distribusi eksponensial.

![[Pasted image 20241027135344.png]]

#### Contoh 6.2

Dari arsip mengenai gempa di San Fransisco, California, selama periode 1836-1961 terdapat 16 gempa yang berskala intensitas VI atau lebih. Jika kejadian gempa yang berintensitas tinggi demikian diasumsikan mengikuti distribusi Poisson. Berapa peluang tidak akan terjadi gempa dengan intensitas setinggi ini dalam 10 tahun mendatang?

##### Penyelesaian

![[Pasted image 20241027141131.png]]

#### Contoh 6.3

Andaikan ada 4 mesin diesel yang sama, digunakan sebagai penggerak utama untuk membangkitkan tenaga listrik serap untuk sistem pengendalian darurat dari suatu pembangkit tenaga nuklir.

Dalam keadaan darurat diperlukan minimal ada 2 mesin yang bekerja secara otomatis (jika tidak sistem pendamping tidak bisa bekerja). Umur operasional mengikuti distribusi eksponensial dengan rata-rata 15 tahun. Tentukan keandalan sistem pendamping darurat selama periode 2 tahun?

##### Penyelesaian

![[Pasted image 20241027141213.png]]

