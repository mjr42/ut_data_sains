---
tags:
  - metode_statistika
  - materi_6_MS
---

# Kegiatan Belajar 2 - Pendekatan Normal untuk Distribusi Binominal

menentukan peluang kejadian sukses sebanyak x dari percobaan yang dilakukan sebanyak n kali yang saling bebas antar percobaan satu dengan lainnya. Percobaan semacam ini juga dikenal dengan proses Bernoulli yang memiliki dua kemungkinan hasil, yaitu sukses atau gagal.

Ulangan sebanyak n kali dalam proses Bernoulli tentu tidak dibatasi jumlahnya. Dalam percobaan tertentu dapat saja dilakukan pengulangan berkali-kali sehingga n menjadi cukup besar. Nah, jika nilai n cukup besar, proses Bernoulli akan mendekati distribusi normal.

![[Screenshot 2024-10-27 at 13.40.47.png]]

Dengan menggunakan pendekatan distribusi Binomial oleh distribusi normal diharapkan bisa lebih praktis dan lebih efisien. Di samping itu rumus distribusi normal terkadang lebih praktis digunakan pada penjumlahan yang rumit, tentu saja dengan simpangan yang relatif kecil.

Diharapkan untuk masalah distribusi Binomial bisa diatasi dengan menggunakan pendekatan normal, dan hasil yang diperoleh tidak jauh berbeda dengan distribusi aslinya. Atau dengan kata lain simpangan yang diakibatkan pendekatan normal ini relatif kecil.

Dari perhitungan, distribusi normal memberikan pendekatan nilai probabilitas yang baik terhadap distribusi Binomial bila $n$ besar dan $p$ mendekati 0,5, bahkan nilai $n$ mengecil tapi $p$ tidak terlalu jauh dari 0,5 masih diperoleh pendekatan yang cukup baik.

![[Pasted image 20241027134219.png]]

Jika p kecil (mendekati 0) atau besar (mendekati 1), maka digunakan pendekatan dengan distribusi Poisson.


#### Contoh 6.2

Suatu proses menghasilkan sejumlah produk (dengan kemungkinan produk cacat 10%). Bila 100 produk diambil secara acak, berapakah kemungkinan bahwa terdapat lebih dari 13 produk cacat?

##### Penyelesaian:

![[Screenshot 2024-10-27 at 13.43.09.png]]

#### Contoh 6.3

Suatu pabrik pembuat CD menghasilkan 10% CD yang cacat. Jika 100 CD dipilih secara random, berapa probabilitas terdapat:

1. ﻿﻿﻿8 CD yang rusak
2. ﻿﻿﻿paling sedikit 12 CD yang rusak
3. ﻿﻿﻿paling banyak 5 CD yang rusak

##### Penyelesaian :
![[Screenshot 2024-10-27 at 13.43.53.png]]

###### a. P (x = 8) = luas kurva normal antara $x_1$ = 7.5 dan $x_2$ = 8,5

![[Pasted image 20241027134423.png]]

###### b. P (x ≥ 12) = Luas kurva normal dari x = 11,5 ke kanan


![[Screenshot 2024-10-27 at 13.44.46.png]]

###### C. P (x≤5) = Luas kurva normal dari x = 5,5 ke kiri

![[Pasted image 20241027134517.png]]


#### Contoh 6.4

Anggota suatu dewan juri berisikan 55% wanita. Berapa peluang terpilihnya 50 anggota juri yang dipilih secara acak akan berisikan anggota wanita sebanyak 30 orang atau lebih?

##### Penyelesaian :

Pemilihan ini jelas merupakan proses Binomial dengan $n = 50, p = 0.55$ dan $x ≥ 30$. Tabel Binomial tidak mempunyai nilai untuk $n = 50$. Pendekatan Poisson juga tidak dapat dilakukan karena $np = 27,5$. Demikian pula teknik menggunakan $1- p$ untuk p tidak dapat dilakukan juga karena $n(1- p)=23,5$. Akan tetapi, kriteria untuk pendekatan normal sudah dipenuhi dimana parameter Binomial untuk mendekati distribusi normal adalah :

![[Pasted image 20241027134630.png]]

Sebelum menghitung peluang distribusi normal, terlebih dahulu perlu dihitung suatu koreksi yang memperkenankan kita melakukan pendekatan dari distribusi diskrit ke distribusi kontinu. Dalam distribusi kontinu, nilai 29 didefinisikan mengambil nilai antara "28,5 sampai 29,5", nilai 30 di antara nilai 29.5 sampai 30.5 dan seterusnya. Dengan demikian, nilai-nilai diskrit yang sama atau lebih besar dari 30 dapat diperlihatkan dalam Gambar 6.10.

![[Pasted image 20241027134658.png]]

Akhirnya persoalan di atas dapat diselesaikan sebagaimana persoalan distribusi normal biasa yaitu:

![[Pasted image 20241027134706.png]]

Luas area dari 0 sampai 0,57 adalah 0,2157. Jadi:

![[Pasted image 20241027134724.png]]

Artinya, peluang terpilihnya anggota juri wanita lebih dari 30 orang adalah 0,2843. Jika dihitung dengan distribusi Binomial diperoleh 0,2862.
