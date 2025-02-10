---
tags:
  - metode_statistika
  - materi_7_MS
---
# Kegiatan Belajar 2 - Pendugaan Titik dan Selang - Rata Rata

Sebagaimana telah disebutkan sebelumnya bahwa dalam statistika inferensia tujuan utamanya adalah melakukan generalisasi terhadap populasi, salah satunya yaitu pendugaan. Penduga bagi parameter populasi ini ada dua macam, yaitu penduga titik dan penduga selang. Penduga titik berupa sebuah nilai, sedangkan penduga selang berupa interval nilai. Penduga ini kita dapatkan dari data sampel yang kita ambil dari populasi. Konsep mengenai pendugaan ini adalah sebagai berikut.

![[Pasted image 20241027145816.png]]

Pendugaan selang rata-rata fe terdiri dari 2 jenis yaitu sampel besar (o diketahui) dan sampel kecil ($\sigma$ tidak diketahui). Pada $\sigma$ diketahui, maka distribusi sampling x mengikuti distribusi sampling

![[Pasted image 20241027145848.png]]

Atau
![[Pasted image 20241027145854.png]]

Pada distribusi normal standard,

![[Pasted image 20241027145906.png]]

maka:

![[Pasted image 20241027145915.png]]

Sehingga didapatkan penduga selang:

![[Pasted image 20241027145924.png]]
![[Pasted image 20241027145933.png]]

Dengan sampel yang berbeda maka akan menghasilkan banyak kemungkinan seperti pada Gambar 7.4.

![[Pasted image 20241027145953.png]]

##### 1. Penduga Selang Populasi dengan Ragam $\sigma^2$ Diketahui

![[Pasted image 20241027150019.png]]

Apabila $\sigma$ tidak diketahui maka dapat diduga dengan simpangan baku sampel atau s. Distribusi yang digunakan adalah distribusi f-student dengan derajat bebas n-1.

![[Pasted image 20241027150042.png]]

Pada distribusi t-student,

![[Pasted image 20241027150051.png]]

maka:

![[Pasted image 20241027150103.png]]

Sehingga didapatkan penduga selang:

![[Pasted image 20241027150125.png]]

#### 2. Penduga Selang Populasi dengan Ragam $\sigma^2$ Tidak Diketahui

![[Pasted image 20241027150312.png]]

![[Pasted image 20241027150331.png]]

#### Contoh 7.5

Data berat badan 10 sampel ayam adalah sebagai berikut:

![[Pasted image 20241027150415.png]]

Hitunglah penduga titik dan selang untuk rata-rata berat badan untuk populasi ayam dengan $\alpha$ = 5%!

###### 1. Penduga Titik

![[Pasted image 20241027150509.png]]


###### 2. Penduga Selang

![[Pasted image 20241027150534.png]]

Batas bawah dan batas atas tersebut menunjukkan bahwa dugaan rata-rata berat badan ayam adalah antara 2,138 hingga 2,644.


