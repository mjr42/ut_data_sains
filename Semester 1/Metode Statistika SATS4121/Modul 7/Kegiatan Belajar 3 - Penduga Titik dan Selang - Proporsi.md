---
tags:
  - metode_statistika
  - materi_7_MS
---
# Kegiatan Belajar 3 - Penduga Titik dan Selang - Proporsi

Selain rata-rata, parameter lainnya yang juga sangat penting untuk menggambarkan populasi dan sering dijumpai kasusnya dalam bidang-bidang terapan adalah proporsi. Pendugaan titik bagi proporsi mengikuti kejadian distribusi Binomial yang identik dengan kejadian sukses dan gagal.

Distribusi Binomial memiliki parameter p yang menyatakan peluang kejadian sukses. Dalam pembahasan kali ini, peluang tersebut dinamakan proporsi. Pendugaan titik proporsi adalah:

![[Pasted image 20241027152601.png]]

Dimana x adalah jumlah kejadian sukses yang diinginkan pada sampel dan n adalah jumlah sampel. Nilai proporsi berkisar antara 0 dan 1.

Dengan cara yang sama seperti pada pendugaan rata-rata u, maka perhitungan pendugaan selang proporsi p adalah sebagai berikut:

![[Pasted image 20241027152620.png]]

Sehingga didapatkan penduga selang:

![[Pasted image 20241027152638.png]]

#### Selang Proporsi pada Distribusi Normal Standar

![[Pasted image 20241027152736.png]]

![[Pasted image 20241027152743.png]]

#### Contoh 7.6

Seperti pada Contoh 7.5, hitunglah penduga titik dan selang untuk proporsi berat badan ayam yang lebih dari 2,4 kg. Jumlah sampel telah diketahui yaitu n =10. Gunakan $\alpha$ = 5%.

##### Penyelesaian

1. Terdapat 6 ayam yang memiliki berat badan lebih dari 2,4 kg, sehingga penduga titiknya adalah:
   
   ![[Pasted image 20241027152835.png]]

2. Penduga selang:
   
   ![[Pasted image 20241027152902.png]]


Batas bawah dan batas atas tersebut menunjukkan bahwa proporsi ayam yang memiliki berat badan lebih dari 2,4 kg adalah antara 0,296 dan 0,904. Dengan kata lain, terdapat sejumlah 29,6% hingga 90,4% ayam memiliki berat badan lebih dari 2,4 kg. Ilustrasinya disajikan pada Gambar 7.7.

![[Pasted image 20241027152918.png]]

Dalam pendugaan parameter sesungguhnya kita tidak mengetahui dimana letak parameter tersebut. Bila proporsi populasi p, berada tepat di tengah selang kepercayaan ($1-\alpha$)100% maka P menduga p tanpa error.

Tapi, yang sering dijumpai adalah kondisi dimana p tidak akan tepat sama dengan p dan dugaan titik meleset (mempunyai error). Nah, besarnya error ini sama dengan selisih positif antara p dan p, dan dengan kepercayaan ($1-\alpha$)100% selisih ini akan lebih kecil dari 

![[Pasted image 20241027153015.png]]

![[Pasted image 20241027153028.png]]


Kemudian, hal yang menarik untuk dikaji adalah penentuan ukuran sampel yang baik untuk menduga proporsi populasi ini. Terkait dengan kondisi di atas, berapa besarkah sampel yang diperlukan agar terjamin bahwa galat dalam menduga p tidak melebihi suatu besaran tertentu g. 

Menurut formula di atas, ini berarti n harus dipilih agar

![[Pasted image 20241027153106.png]]

![[Pasted image 20241027153112.png]]

Namun, formula tersebut agak membingungkan karena untuk menentukan ukuran sampel n digunakan P, padahal p dihitung dari sampel. Bila p dapat diduga secara kasar tanpa mengambil sampel maka dugaan ini dapat dipakai untuk menentukan n. Bila ini tidak tersedia atau tidak dapat dilakukan, maka ambil sampel pendahuluan berukuran n ≥ 30 untuk menduga p. Kemudian, dengan menggunakan formula

![[Pasted image 20241027153141.png]]

dapat ditentukan perkiraan besarnya sampel yang diperlukan agar derajat ketepatan yang dinginkan tercapai.


Sekali lagi, semua nilai pecahan n agar dibulatkan ke bilangan bulat yang lebih besar terdekat. Untuk lebih memahami konsep ini, pelajari soal-soal latihan.

![[Pasted image 20241027153210.png]]

Yang selalu lebih kecil dari ¼ kecuali bila p =1/2 yang mengakibatkan pâ =1/4. Jadi, bila dimasukkan p=1/2 pada rumus

![[Pasted image 20241027153224.png]]

Padahal, sesungguhnya, p cukup berbeda dengan ½, maka tentunya n akan melebihi dari yang diperlukan untuk taraf kepercayaan yang ditetapkan dan sebagai akibatnya taraf kepercayaan yang diperoleh akan meningkat (Walpole, 1995).

![[Pasted image 20241027153244.png]]




