---
tags:
  - metode_statistika
  - materi_5_MS
---
# Kegiatan Belajar 2 - Distribusi Hipergeometrik dan Poisson


## [[04. Distribusi Hipergeometrik]]

Distribusi Hipergeometrik sering terjadi pada populasi produksi yang dapat dikategorikan cacat dan tidak cacat. Jika diambil sampel secara acak, karakteristik cacat dan tidak cacat masih mungkin nampak dalam sampel, dan peluang terjadinya dapat ditentukan.

Percobaan Hipergeometrik bercirikan dua sifat berikut :

1. ﻿﻿﻿Suatu sampel acak berukuran n diambil dari populasi berukuran N.
2. ﻿﻿﻿K dari N diklasifikasikan sebagai sukses dan N-k diklasifikasikan sebagai gagal.

#### Teorema Distribusi Hipergeometrik

> Andaikan suatu populasi komponen dalam suatu peti kemas berukuran N dan jumlah komponen cacat ada D buah. Jika diambil n komponen sebagai sampel dan x menyatakan jumlah cacat dalam sampel maka fungsi distribusi peluang dari X merupakan fungsi hipergeometrik dan dinyatakan dalam :
> 
> ![[Screenshot 2024-10-19 at 17.09.42.png]]
> 
> Rata-rata dan varians distribusi hipergeometrik adalah:
> 
> ![[Screenshot 2024-10-19 at 17.10.00.png]]


##### Contoh 5.7

PT Adikarya memproduksi alat pengukur regangan (strain gage). Produk ini disuplai ke PT Jaya secara rutin. Dalam proses transaksinya PT Jaya menuntut mutu 10% cacat dari satu peti yang berisi 30 komponen. Dalam proses transaksi PT Jaya selalu melakukan pemeriksaan berdasarkan sampel sebanyak 5 buah. Jika ditemukan cacat lebih dari 2 dalam sampel maka peti kemas ditolak, selain itu diterima.

1. Berapa peluang dalam sampel terdapat cacat sama dengan 3?
2. Berapa peluang peti kemas diterima?

###### Penyelesaian

![[Screenshot 2024-10-19 at 17.28.55.png]]



## [[05. Distribusi Poisson]]

Percobaan yang menghasilkan variabel acak X menyatakan banyaknya kejadian yang terjadi pada selang waktu tertentu disebut percobaan Poisson. Fenomena alam (percobaan) yang mengikuti pola Poisson mempunyai ciri-ciri sebagai berikut:

1. Suatu kejadian sukses dapat terjadi secara acak dalam suatu waktu (ruang, wilayah, dan lain sebagainya).
2. Kejadian sukses antara satu interval waktu saling bebas. ﻿﻿﻿Peluang terjadinya sukses di dalam interval yang kecil $Δt$ setara dengan $Δt$ dan dapat ditulis sebagai $𝛌Δt$ dengan $𝛌$ sebagai laju rata-rata sukses suatu kejadian dan biasanya diasumsikan konstan. Peluang dari dua kejadian atau lebih di dalam $Δt$ dapat diabaikan.

1. Proses Poisson banyak terjadi pada satu kasus yang jarang terjadi.

Misalnya kasus retak dalam suatu las besi (fatique cracks). Kejadian gempa di suatu daerah gempa aktif, jumlah kecelakaan di suatu lalu lintas dapat terjadi kapan saja, jumlah produk cacat di suatu pabrik, tetapi semua menginginkan kasus ini merupakan hal yang jarang terjadi.

Berdasarkan proses Poisson di atas, dapat dirumuskan fungsi distribusi Poisson sebagai berikut.

#### Teorema Distribusi Poisson

> Jika x, adalah jumlah kejadian sukses dalam selang waktu tertentu, maka fungsi distribusi Poisson dapat dijelaskan dalam :
> 
> ![[Screenshot 2024-10-19 at 17.34.53.png]]
> Rata-rata dan varians distribusi Poisson $p(x;𝛌t)$ keduanya adalah $𝛌t$.


##### Contoh 5.8

Untuk merancang jalur belok kanan pada suatu persimpangan jalan raya, diasumsikan jumlah kendaraan yang melewati jalur ini mengikuti proses Poisson. Waktu sukses lampu lalu lintas untuk belok kanan adalah 1 menit dan rata-rata ada 100 mobil yang belok kanan per jam. Jika kriteria perancangan mensyaratkan suatu jalur belok kanan yang cukup untuk 96% pada setiap waktu, berapakah panjang jalur belok kanan dalam satuan jumlah mobil?

###### Penyelesaian

![[Screenshot 2024-10-19 at 17.36.44.png]]
![[Screenshot 2024-10-19 at 17.37.08.png]]



