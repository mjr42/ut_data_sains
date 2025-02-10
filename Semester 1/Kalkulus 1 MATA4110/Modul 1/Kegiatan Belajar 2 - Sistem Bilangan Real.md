---
tags:
  - kalkulus_1
---

Materi : 
- [[02. Sistem Bilangan Real]]
- [[03. Urutan]]
- [[04. Selang (Interval)]]
- [[05. Pertidak Samaan dan Persamaan]]
- [[06. Nilai Mutlak]]
- [[07. Pengenalan Bilangan Kompleks]]

---


## Sitem Bilangan Real

Dalam himpunan bilangan real ℝ didefinisikan operasi penambahan " + " dan perkalian "." yang tertutup. Artinya apabila x,y ∈ ℝ  maka x   y ∈ ℝ dan x.y ∈ ℝ. Untuk penulisan x.y lebih sering ditulis xy saja. Operasi penambahan dan perkalian ini memenuhi sifat-sifat yang disebut **Medan Bilangan Real**.

#### Sifat-sifat Medan Bilangan Real

Untuk x,y,z ∈ ℝ maka:

- **Sifat Komutatif**
	- x + y = y + x
	- x.y = y.x
	  
- **Sifat Asosiatif**
	- x + (y+z) = (x+y) + z
	- x(yz) = (xy)z
	  
- **Sifat Distributif**
	- x(y+z) = xy + xz
	  
- **Unsur Satuan (identitas):**
	- 0 sehingga x + 0 = x (penambahan)
	- 1 sehingga x.1 = x (perkalian)
	  
- **Unsur Inverse (balikan):**
	- 𝕍x ∈ ℝ ada inverse (-x) sehingga x+(-x) = 0
	- 𝕍x ≠ 0 ada inverse x^-1 sehingga x.x^-1 = 1 


#### Operasi pengurangan dan Pembagian

- Pengurangan x-y = x+(-y) (penambahan dengan inversenya)
  
- Pembagian: x/y = x.y^-1 (perkalian dengan inversenya)
  
![[Screenshot 2024-08-11 at 09.56.28.png]]

## Urutan

###### Himpunan bilangan real ℝ dipisahkan oleh bilangan 0 menjadi dua bagian yaitu 
- bagian yang lebih besar 0 selanjutnya disebut **bilangan positif**, dan 
- bagian yang lebih kecil dari 0 disebut **bilangan negatif**

![[Pasted image 20240811100732.png]]

###### - Dalam sistem bilangan real ℝ didefinisikan relasi urutan "<" dibaca  "lebih kecil dari" sebagai
    x < y ↔ y - x positif
###### - Tanda ↔ dibaca "jika dan hanya jika" artinya x < y jika y - x- positif jika x < y.
###### - Penulisan x < y sama artinya dengan y > x, tanda ">" dibaca "lebih besar dari"

![[Screenshot 2024-08-11 at 10.16.13.png]]

##### Sifat Urutan

- **Triknotomi :**  
  untuk setiap dua bilangan x dan y hanya berlaku salah satu dari hubungan, x < y atau x = y atau x > y
  
- **Transif** : 
  JIka x < y dan y < z maka x < z
  
- **Penambahan** : 
  Jika x < yU x+z < y+z
  
- **Pengalian** :
	- Jika z > 0 maka x < yU xz < yz
	- jika z < 0 maka x < yU xz > yz

Contoh : 

![[Screenshot 2024-08-11 at 10.23.32.png]]
![[Screenshot 2024-08-11 at 10.23.50.png]]
## Selang (Interval)

> Selang atau Interval merupakan cara lain untuk penulisan himpunan bilangan real, ditulis sebagai (...,...) (...,...] [...,...) atau [...,...]. ] 

Notasi "(" dan ")" serta selang buka "[" dan "]" selang tutup. misalkan (a,b) ini berarti a termasuk anggota selang, sedangkan b tidak termasuk anggota selang.

#### Selang dan Gambarannya

- (a,b) Himpunannya : x | a < x < b
- (a,b] Himpunannya : x | a < x ≦ b
- [a,b) Himpunannya : x | a ≦ x < b
- [a,b] Himpunannya : x | a ≦ x ≦ b
- (-∞, b] Himpunannya : x | x ≦ b
- (-∞, b) Himpunannya : x | x < b
- [a, ∞) Himpunannya : x | x ≧ a
- (a, ∞) Himpunannya : x | x > a
- (-∞, ∞) Himpunannya ℝ

![[Pasted image 20240811105830.png]]
![[Pasted image 20240811105840.png]]



## Pertidak Samaan (<,>,≦, ≧) dan Persamaan (=)

Istilah lain dari pertidak samaan adalah pertaksamaan. Perbedaan antara Pertidaksamaan dan Persamaan. untuk membedakan antara Pertidaksamaan dan Persamaan berikut contohnya:

#### Perbedaan antara Pertidaksamaan dan Persamaan

- Berapa nilai x yang memenuhi pertidaksamaan 2x - 4 < 0
  ![[Screenshot 2024-08-11 at 11.18.26.png]]
  
- Berapa nilai x yang memenuhi persamaan 2x - 4 = 0
  ![[Screenshot 2024-08-11 at 11.19.00.png]]
  
- Berapa nilai x yang memenuhi pertidaksamaan -2x + 4 < 0
  ![[Screenshot 2024-08-11 at 11.19.15.png]]


> Jadi nilai yang memenuhi pertidaksamaan berupa selang

> Nilai x yang memenuhi persamaan berupa titik


#### Pertidaksamaan yang terdiri dari beberapa Faktor


###### Tentukan nilai x yang memenuhi pertidaksamaan (x-2)(x+1) < 0

Pandang pertidaksamaan ( x - 2 )( x + 1 ) < 0 sebagai persamaan sehinggga ( x - 2 )( x + 1 ) = 0
sehingga persamaan ini memiliki penyelesaian x1 = -1 dan x2 = 2 . Selanjutnya titik x1 = -1 dan x2 = 2 disebut sebagai titik pemecah (split point). Apabila digambarkan dalam garis bilangan maka titik titik pemecah tersebut akan membentuk selang (-∞, -1), (-1, 2), (2, ∞)

![[Screenshot 2024-08-11 at 11.28.58.png]]


Kemudian ambil satu buah titik sembarang pada masing-masing selang. Titik titik sembarang ini selanjutnya di sebut titik uji (test point) misalnya:
x = -2 pada (-∞, -1)
x = 0 pada (-1, 2)
x = 3 pada (2, ∞)
selanjutnya periksa nilai (x-2)(x-1) pada titik titik uji

Titik uji x = -2 memberikan nilai (-2-2)(-2-1) = (-4)(-2) = 8>0. selanjutnya selang (-∞, -1)  diberikan tanda "+"
Titik uji x = 0 memberikan nilai (0-2)(0+1) = (-2)(1) = -2 < 0 selanjutnya pada selang  (-1,2)diberikan tanda "-"
Titik uji x = 3 memberikan nilai (3-2)(3+1) = (1)(4) = 4 > 0 selanjutnya pada selang (2, ∞) diberikan tanda "+"

kemudia tanda "+" "-" dan "+" diletakan pada selang selang yang berkaitan, sehingga menghasilkan

![[Screenshot 2024-08-11 at 11.38.50.png]]
> Karena tanda pertidaksamaan "<" maka nilai x yang memenuhi selang yang bertanda "-"
j.  jadi nilai x yang memenuhi pertidaksamaan adalah -1 < x < 2

> untuk tanda pertidaksamaan ">" maka nilai x yang memenuhi selang yang bertanda "+"



#### Pertidaksamaan dari hasil pembagian dan perkalian

| 8/4 = 2 > 0   | (8)(4) = 31 > 0   | ">" |
| ------------- | ----------------- | --- |
| -8/4 = -2 < 0 | (-8)(2) = -32 < 0 | "<" |
| 8/-4 = -2 < 0 | (8)(-2) = -32 < 0 | "<" |
| -8/-4 = 2 > 0 | (-8)(-2) = 32 > 0 | ">" |

Ternyata dua bilangan sama apabila dilakukan operasi pembagian datau perkalian memberikan tanda pertidaksamaan yang sama pula. 
> secara umum perkalian dan pembagian tidak mengubah tanda pertidaksamaan


#### Contoh $\frac{(x-1)(x+1)}{(x+2)(x-3)} > 0$

Untuk menyelesaikan pertidaksamaan tersebut, Anda dapat mengikuti langkah-langkah berikut:

###### 1. **Identifikasi Pembilang dan Penyebut:**
   Pertidaksamaan yang diberikan adalah:

   $\frac{(x-1)(x+1)}{(x+2)(x-3)} > 0$
   
   - Pembilang: \((x-1)(x+1)\)
   - Penyebut: \((x+2)(x-3)\)

###### 2. **Cari Titik Kritis:**
   Titik kritis adalah nilai \(x\) yang membuat pembilang atau penyebut menjadi nol.

   - Untuk pembilang \((x-1)(x+1) = 0\), \(x = 1\) dan \(x = -1\).
   - Untuk penyebut \((x+2)(x-3) = 0\), \(x = -2\) dan \(x = 3\).

   > Jadi, titik kritisnya adalah \(x = -2\), \(x = -1\), \(x = 1\), dan \(x = 3\).

###### 3. **Buat Tabel Tanda:**
   Anda perlu membuat tabel tanda dengan interval yang dibatasi oleh titik-titik kritis tersebut:

   - Interval 1: \(x < -2\)
   - Interval 2: \(-2 < x < -1\)
   - Interval 3: \(-1 < x < 1\)
   - Interval 4: \(1 < x < 3\)
   - Interval 5: \(x > 3\)

   Kemudian, tentukan tanda dari setiap faktor di pembilang dan penyebut pada setiap interval tersebut.

###### 4. **Evaluasi Tanda pada Setiap Interval:**

   Misalkan kita tentukan tanda setiap faktor pada setiap interval:
![[Screenshot 2024-08-11 at 12.51.27.png]]
###### 5. **Tentukan Interval Solusi:**
   Berdasarkan tabel di atas, pertidaksamaan \(\frac{(x-1)(x+1)}{(x+2)(x-3)} > 0\) akan berlaku pada interval-interval dengan tanda positif. Dari tabel, solusi pertidaksamaannya adalah:

   
  > $x \in (-\infty, -2) \cup (-1, 1) \cup (3, \infty)$
   

###### 6. **Pertimbangkan Pembatas:**
   Titik-titik kritis di mana penyebutnya menjadi nol (\(x = -2\) dan \(x = 3\)) harus dikeluarkan dari solusi karena menyebabkan pembagian dengan nol.

###### **Solusi Akhir:**
   
 >  $x \in (-\infty, -2) \cup (-1, 1) \cup (3, \infty)$
   
Ini adalah interval-interval di mana pertidaksamaan tersebut benar.


## Nilai Mutlak

Nilai mutlak a, ditulis |a| dan didefinisikan : 

##### Nilai mutlak suatu bilangan \( a \), yang ditulis sebagai \( |a| \), didefinisikan sebagai berikut: $|a| = \begin{cases} a, & \text{jika } a \geq 0 \\ -a, & \text{jika } a < 0 \end{cases}$

- Jika \( a \) adalah bilangan positif atau nol $(\( a \geq 0 \))$, maka nilai mutlaknya adalah \( a \) itu sendiri.
- Jika \( a \) adalah bilangan negatif $(\( a < 0 \))$, maka nilai mutlaknya adalah kebalikan dari \( a \) (yaitu, \(-a\)).

Secara sederhana, nilai mutlak dari suatu bilangan adalah jarak bilangan tersebut dari nol pada garis bilangan, tanpa memperhatikan tanda positif atau negatifnya.

> Dari definisi ini telihat bahwa nilai |a| akan selalu positif atau 0, tidak pernah negatif


##### Sifat Nilai Mutlak

Gambar ini menampilkan beberapa sifat-sifat nilai mutlak dalam bentuk persamaan dan ketidaksamaan. Berikut penjelasannya:

###### a. $( \pm a \leq |a| )$
   - Ini berarti bahwa nilai suatu bilangan \( a \) (baik positif maupun negatif) selalu lebih kecil atau sama dengan nilai mutlaknya. Nilai mutlak \( |a| \) selalu non-negatif.

###### b. $( |ab| = |a||b| )$
   - Ini adalah sifat dari nilai mutlak, yang menyatakan bahwa nilai mutlak dari perkalian dua bilangan sama dengan perkalian nilai mutlak dari masing-masing bilangan.

###### c. $( \left|\frac{a}{b}\right| = \frac{|a|}{|b|}, b \neq 0 )$
   - Ini menyatakan bahwa nilai mutlak dari suatu pecahan sama dengan pecahan dari nilai mutlak pembilang dan penyebutnya. Persamaan ini berlaku selama penyebut \( b \) tidak sama dengan nol.

###### d. $( |a + b| \leq |a| + |b| )$
   - Ini adalah ketaksamaan segitiga untuk nilai mutlak, yang menyatakan bahwa nilai mutlak dari jumlah dua bilangan selalu kurang dari atau sama dengan jumlah dari nilai mutlak masing-masing bilangan.

###### e. $( |a - b| \leq |a| + |b| )$
   - Ini adalah bentuk lain dari ketaksamaan segitiga, yang menyatakan bahwa nilai mutlak dari selisih dua bilangan selalu kurang dari atau sama dengan jumlah nilai mutlak masing-masing bilangan.

Secara umum, sifat-sifat ini penting dalam berbagai aplikasi matematika, terutama dalam analisis fungsi dan aljabar.


##### Sifat Pertidaksamaan dalam Nilai Mutlak

![[Screenshot 2024-08-11 at 14.38.09.png]]
Gambar ini menunjukkan sifat-sifat pertidaksamaan dalam nilai mutlak, yang berkaitan dengan interval dan cara menyelesaikan pertidaksamaan nilai mutlak. Berikut penjelasan dari masing-masing sifat:

###### **a.** $( |x| < a \iff -a < x < a )$
   - Jika nilai mutlak dari \( x \) lebih kecil dari \( a \), maka \( x \) berada di antara \(-a\) dan \( a \). Ini digambarkan dengan garis yang menunjukkan interval terbuka dari \(-a\) hingga \( a \).

###### **b.** $( |x| > a \iff x < -a ) atau ( x > a$ )
   - Jika nilai mutlak dari \( x \) lebih besar dari \( a \), maka \( x \) berada di luar interval \(-a\) hingga \( a \), yaitu \( x \) lebih kecil dari \(-a\) atau lebih besar dari \( a \). Ini digambarkan dengan dua garis yang menunjuk ke arah yang berlawanan dari \(-a\) dan \( a \), menunjukkan interval terbuka.

###### **c.** $( |x| \leq a \iff -a \leq x \leq a )$
   - Jika nilai mutlak dari \( x \) kurang dari atau sama dengan \( a \), maka \( x \) berada di antara \(-a\) dan \( a \), termasuk titik \(-a\) dan \( a \) sendiri. Ini digambarkan dengan garis yang menunjukkan interval tertutup dari \(-a\) hingga \( a \).

###### **d.** $( |x| \geq a \iff x \leq -a ) atau ( x \geq a )$
   - Jika nilai mutlak dari \( x \) lebih besar dari atau sama dengan \( a \), maka \( x \) berada di luar interval \(-a\) hingga \( a \), atau tepat di titik \(-a\) dan \( a \). Ini digambarkan dengan dua garis yang menunjuk ke luar dari \(-a\) dan \( a \), menunjukkan interval tertutup di kedua ujungnya.

Sifat-sifat ini digunakan dalam pemecahan pertidaksamaan yang melibatkan nilai mutlak, yang sering kali muncul dalam aljabar dan kalkulus. Interval dan cara penyelesaiannya penting untuk memahami bagaimana nilai mutlak membatasi atau mengatur rentang nilai suatu variabel.

![[Screenshot 2024-08-11 at 14.53.34.png]]

##### Contoh A


```
|2x - 1| ≥ 5
```

###### **Konsep Mutlak**

Nilai mutlak dari suatu bilangan selalu positif atau nol. Jadi, |a| dapat diartikan sebagai jarak dari a ke 0 pada garis bilangan.

###### **Memecahkan Pertidaksamaan Mutlak**

Pertidaksamaan mutlak ini dapat dipecah menjadi dua pertidaksamaan biasa:

1. **Jika isi mutlak positif:**
    
    - 2x - 1 ≥ 5
2. **Jika isi mutlak negatif:**
    
    - -(2x - 1) ≥ 5

###### **Menyelesaikan Masing-masing Pertidaksamaan**

1. **2x - 1 ≥ 5**
    
    - 2x ≥ 6
    - x ≥ 3
2. **-(2x - 1) ≥ 5**
    
    - -2x + 1 ≥ 5
    - -2x ≥ 4
    - x ≤ -2 (Ingat, ketika mengalikan atau membagi dengan bilangan negatif, tanda pertidaksamaan berbalik)

###### **Menggabungkan Hasil**

Jadi, nilai-nilai x yang memenuhi pertidaksamaan adalah:

- x ≤ -2 atau x ≥ 3

###### **Interpretasi dalam Garis Bilangan**

Jika kita gambarkan pada garis bilangan, solusinya adalah semua bilangan yang berada di sebelah kiri -2 atau di sebelah kanan 3, termasuk -2 dan 3 sendiri.

###### **Kesimpulan**

Himpunan penyelesaian dari pertidaksamaan |2x - 1| ≥ 5 adalah {x | x ≤ -2 atau x ≥ 3}.


##### Contoh B

```
|x - 1| ≤ |2x + 4|
```


###### **Menyelesaikan Pertidaksamaan Mutlak Bentuk Khusus**

Pertidaksamaan mutlak ini sedikit berbeda dari yang sebelumnya karena melibatkan dua nilai mutlak. Ada beberapa cara untuk menyelesaikannya, namun kita akan menggunakan cara kuadrat untuk kasus ini.

###### **Cara Kuadrat**

1. **Kuadratkan kedua ruas:**
    
    - (x - 1)² ≤ (2x + 4)²
2. **Expand kedua ruas:**
    
    - x² - 2x + 1 ≤ 4x² + 16x + 16
3. **Pindahkan semua suku ke satu ruas dan sederhanakan:**
    
    - 3x² + 18x + 15 ≥ 0
    - x² + 6x + 5 ≥ 0
4. **Faktorkan:**
    
    - (x + 5)(x + 1) ≥ 0
5. **Buat garis bilangan:**
    
    - Tentukan titik-titik kritis, yaitu nilai x yang membuat hasil kali faktor menjadi nol. Dalam kasus ini, x = -5 dan x = -1.
    - Uji tanda pada setiap interval yang terbentuk.
6. **Tentukan interval yang memenuhi:**
    
    - Dari garis bilangan, kita dapat melihat bahwa (x + 5)(x + 1) ≥ 0 ketika x ≤ -5 atau x ≥ -1.

**Kesimpulan**

Jadi, nilai-nilai x yang memenuhi pertidaksamaan |x - 1| ≤ |2x + 4| adalah:

- x ≤ -5 atau x ≥ -1


## Pengenalan Bilangan Kompleks

Bilangan kompleks adalah himpunan bilangan yang paling lengkap pada diagram hierarki himpunan bilangan. Himpinan bilangan kompleks berbentuk:

##### $ℂ = a+bi ; a,b ∈ ℝ ; i = √(-1) atau ; i² = -1:$

1. **C = ℂ**: Simbol "C" ini mewakili himpunan bilangan kompleks.

2. **z = a + bi**: Ini adalah bentuk umum dari bilangan kompleks, di mana:
   - \(z\) adalah bilangan kompleks.
   - \(a\) adalah bagian riil dari bilangan kompleks, dan \(a \in R\) artinya \(a\) adalah bilangan riil.
   - \(b\) adalah bagian imajiner dari bilangan kompleks, dan \(b \in R\) artinya \(b\) juga adalah bilangan riil.
   - \(i\) adalah satuan imajiner.

3. **i = √(-1)** atau **i² = -1**: Ini mendefinisikan sifat dari satuan imajiner \(i\). \(i\) adalah bilangan imajiner yang didefinisikan sebagai akar kuadrat dari -1, dan \(i^2\) sama dengan -1.

Jadi, bilangan kompleks adalah bilangan yang terdiri dari bagian riil dan bagian imajiner, di mana bagian imajinernya melibatkan \(i\), satuan imajiner yang memiliki sifat \(i^2 = -1\).
Pada kalkulus, bilangan kompleks hanya diberikan sebagai pengantar saja, sekedar menunjuka bahwa selain sistem bilangan real yang digunakan pada kalkulus, masih ada sistem bilangan lainnya yaitu sistem bilangan kompleks.


$$
z_1 = a + bi ; z_2 = c + di
$$

#### a. Penjumlahan Bilangan Kompleks $(z_1 + z_2)$
- $z_1 + z_2 = (a + bi) + (c + di) = (a + c) + (b + d)i$
  
  - Ketika dua bilangan kompleks $(z_1)$ dan $(z_2)$ dijumlahkan, bagian riilnya (a dan c) dijumlahkan, begitu pula bagian imajinernya (b dan d).
  - Hasilnya adalah bilangan kompleks baru dengan bagian riil $(a + c)$ dan bagian imajiner $(b + d)$.

#### b. Pengurangan Bilangan Kompleks $(z_1 - z_2)$
- $z_1 - z_2 = (a + bi) - (c + di) = (a - c) + (b - d)i$
  
  - Pada pengurangan dua bilangan kompleks, bagian riilnya (a dan c) dikurangkan, dan bagian imajinernya (b dan d) juga dikurangkan.
  - Hasilnya adalah bilangan kompleks dengan bagian riil $(a - c)$ dan bagian imajiner $(b - d)$.

#### c. Perkalian Bilangan Kompleks $(z_1 \times z_2)$
- $(z_1)(z_2) = (a + bi)(c + di) = (ac - bd) + (ad + bc)i$
  
  - Dalam perkalian bilangan kompleks, kita menggunakan distributif untuk mengalikan bagian riil dan imajiner masing-masing.
  - Hasilnya adalah bilangan kompleks dengan bagian riil $(ac - bd)$ dan bagian imajiner $(ad + bc)$.
  - Rumus ini berasal dari sifat $(i^2 = -1)$, yang menyebabkan komponen $(bd)$ menjadi negatif dalam bagian riil.

#### d. Pembagian Bilangan Kompleks $(\frac{z_1}{z_2})$
- $\frac{z_1}{z_2} = \frac{(a + bi)}{(c + di)} = \frac{(a + bi)(c - di)}{(c + di)(c - di)} = \frac{(ac + bd) + (bc - ad)i}{c^2 + d^2}$
  
  - Untuk membagi dua bilangan kompleks, kita mengalikan pembilang dan penyebut dengan konjugat dari penyebut, yaitu $(c - di)$.
  - Konjugat dari bilangan kompleks adalah bilangan yang memiliki tanda bagian imajiner yang berlawanan.
  - Setelah dilakukan perkalian, penyebut menjadi bilangan riil $(c^2 + d^2)$, dan pembilang menjadi $(ac + bd)$ untuk bagian riil, serta $(bc - ad)$ untuk bagian imajiner.
  - Hasil akhir adalah bilangan kompleks dengan bagian riil $(\frac{ac + bd}{c^2 + d^2})$ dan bagian imajiner $(\frac{bc - ad}{c^2 + d^2})$.
  

