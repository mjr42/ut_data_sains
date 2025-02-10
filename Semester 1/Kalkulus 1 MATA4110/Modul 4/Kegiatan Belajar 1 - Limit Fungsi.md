---
tags:
  - kalkulus_1
  - materi_4_KLS1
---
# Kegiatan Belajar 1 - Limit Fungsi

dalam bahasa matematika digunakan kata mendekati, diberi notasi "→". Pengertian x mendekati a ditulis x →a adalah ∀𝛿 > 0 terdapat x sehingga 0 |< x-a| < 𝛿 . Nilai x - a memiliki arti x < a atau x > a .

## [[01. Limit Fungsi]]

#### 1. Definisi 4.1.1 (Limit Fungsi)

Dituliskan sebagai:

$$\lim_{{x \to a}} f(x) = L$$

Hal ini berarti bahwa fungsi  f(x)  mendekati nilai  L  saat  x  mendekati  a . Untuk membuktikan hal ini secara formal menggunakan definisi epsilon-delta, berikut langkah-langkahnya:

•	Untuk setiap  $\varepsilon > 0$ , terdapat sebuah $\delta > 0$  sehingga:

$$|f(x) - L| < \varepsilon \quad \text{untuk semua} \quad 0 < |x - a| < \delta.$$

Penjelasannya:

- Epsilon ($\varepsilon$) adalah batas jarak vertikal (selisih antara  f(x)  dan  L ) yang bisa kita tetapkan, yang menunjukkan seberapa dekat nilai fungsi harus berada dengan  L .

- Delta ($\delta$) adalah batas jarak horizontal yang bisa kita tetapkan, yang menunjukkan seberapa dekat  x  harus berada dengan  a  agar nilai fungsi mendekati  L .

Artinya, selisih antara  f(x)  dan  L  dapat dibuat lebih kecil dari  $\varepsilon$  selama  x  cukup dekat dengan  a  (dengan jarak kurang dari  \delta , tetapi tidak sama dengan  a ).

- Saat kita mengambil nilai  x  yang semakin dekat dengan  a , nilai  f(x)  akan semakin mendekati  L .

-  $\delta$  menunjukkan seberapa kecil kita bisa memilih interval di sekitar  a , dan  \varepsilon  menunjukkan seberapa dekat nilai  f(x)  dengan  L .

![[Screenshot 2024-10-13 at 11.08.11.png]]

##### Contoh 4.1.1

Tunjukkan bahwa $$\lim_{{x \to 1}} (2x + 1) = 3.$$

###### Penyelesaian:

###### 1. Subtitusi Langsung

Untuk fungsi linear seperti  $f(x) = 2x + 1$ , kita dapat menyelesaikan limitnya dengan mensubstitusikan langsung nilai  x  yang mendekati 1 ke dalam fungsi.

$$f(1) = 2(1) + 1 = 2 + 1 = 3$$

Maka:

$$\lim_{{x \to 1}} (2x + 1) = 3.$$

Jawaban: Benar bahwa $\lim_{{x \to 1}} (2x + 1)$ = 3, karena dengan substitusi langsung nilai fungsi  f(x)  di  x = 1  menghasilkan 3.

###### 2. Pembuktian dengan definisi Epsilon Delta

Diberikan $\varepsilon > 0$ , kita harus menemukan  $\delta > 0$  sehingga jika  $0 < |x - 1| < \delta$ , maka  $|(2x + 1) - 3| < \varepsilon$ .

Misalnya:

$$|(2x + 1) - 3| = |2x - 2| = 2|x - 1|.
$$
Agar  $2|x - 1| < \varepsilon$ , kita pilih  $\delta = \frac{\varepsilon}{2}$ .

Maka jika  $0 < |x - 1| < \delta$ , kita dapat memastikan bahwa $|(2x + 1) - 3| < \varepsilon$ , sesuai dengan definisi limit.

##### Contoh 4.1.2

Tunjukkan bahwa $$\lim_{{x \to 3}} \sqrt{x} = \sqrt{3}.$$

###### Penyelesaian:

###### 1.Substitusi langsung:

Untuk fungsi  $f(x) = \sqrt{x}$ , kita juga dapat menyelesaikan limitnya dengan substitusi langsung  $x = 3$  ke dalam fungsi.

$$f(3) = \sqrt{3}.$$

Maka:

$$\lim_{{x \to 3}} \sqrt{x} = \sqrt{3}.$$

Jawaban: Benar bahwa $\lim_{{x \to 3}} \sqrt{x} = \sqrt{3}.$


###### 2. Pembuktian dengan definisi Epsilon Delta

Diberikan  $\varepsilon > 0$ , kita harus menemukan  $\delta > 0$  sehingga jika $0 < |x - 3| < \delta$ , maka  $|\sqrt{x} - \sqrt{3}| < \varepsilon$ .

Langkah pertama adalah manipulasi ekspresi  $|\sqrt{x} - \sqrt{3}|$ :

$$|\sqrt{x} - \sqrt{3}| = \frac{|x - 3|}{|\sqrt{x} + \sqrt{3}|}.$$

Agar  $|\sqrt{x} - \sqrt{3}| < \varepsilon$ , kita perlu mengatur  $|x - 3|$  sedemikian rupa sehingga memenuhi kondisi tersebut.

Karena  $|\sqrt{x} + \sqrt{3}|$  mendekati  $2\sqrt{3}$  saat  x  mendekati 3, kita bisa memilih  $\delta$  sedemikian sehingga:

$\delta = \varepsilon \cdot 2\sqrt{3}.$

Maka jika  $0 < |x - 3| < \delta$ , kita dapat memastikan bahwa $|\sqrt{x} - \sqrt{3}| < \varepsilon$ , sesuai dengan definisi limit.


#### 2. Pengertian Limit

##### 1. Naratif
Apabila x mendekati a untuk a berlainan dengan x,  maka f(x) mendekati L .

##### 2. Notasi
Jika x → a untuk a = x, maka f (x) → L.



## [[02. Teorema Dasar Limit]]

#### 1.	Teorema (1):

$$\lim_{{x \to c}} (mx + b) = mc + b$$

Ini adalah aturan dasar limit untuk fungsi linear. Jika kita memiliki fungsi linear  mx + b , maka ketika  x  mendekati nilai  c , limitnya adalah  mc + b .

###### Contoh:

Tentukan $\lim_{{x \to 2}} (3x + 5).$

###### Langkah-langkah:

1.	Fungsi yang diberikan adalah 3x + 5.
2.	Kita substitusikan x = 2 langsung ke fungsi karena ini adalah fungsi linear.


$$\lim_{{x \to 2}} (3x + 5) = 3(2) + 5 = 6 + 5 = 11$$


###### Penjelasan: 
Karena fungsi linear kontinu di seluruh domainnya, kita bisa langsung menggantikan nilai x dengan 2 untuk mendapatkan hasilnya.

#### 2.	Teorema (2):

$$\lim_{{x \to c}} k = k$$

Jika kita mengambil limit dari sebuah konstanta  k  ketika  x  mendekati nilai  c , hasilnya tetap  k . Ini berlaku karena nilai konstanta tidak tergantung pada  x .


###### Contoh:

Tentukan $\lim_{{x \to 3}} 7.$

###### Langkah-langkah:

1.	Fungsi yang diberikan adalah konstanta 7.
2.	Karena fungsi ini konstanta, limitnya akan tetap sama untuk setiap x.


$$\lim_{{x \to 3}} 7 = 7$$


###### Penjelasan: 
Fungsi konstanta selalu memiliki nilai yang sama, sehingga limitnya sama dengan konstanta itu sendiri.

#### 3.	Teorema (3):

$$\lim_{{x \to c}} x = c$$

Limit dari  x  ketika  x  mendekati  c  adalah  c  itu sendiri. Ini intuitif karena ketika  x  mendekati suatu nilai, maka  x  akan mendekati nilai tersebut.


###### Contoh:

Tentukan $\lim_{{x \to 5}} x.$

###### Langkah-langkah:

1.	Fungsi yang diberikan adalah x.
2.	Substitusikan x = 5 langsung ke dalam fungsi.


$$\lim_{{x \to 5}} x = 5$$


###### Penjelasan: 
Fungsi identitas x memiliki nilai yang sama dengan inputnya, sehingga limitnya adalah nilai dari x itu sendiri.

#### 4.	Teorema (4):

$$\lim_{{x \to c}} kf(x) = k \lim_{{x \to c}} f(x)$$

Jika kita mengambil limit dari suatu fungsi  f(x)  yang dikalikan dengan konstanta  k , hasilnya adalah konstanta  k  dikalikan dengan limit dari fungsi tersebut.


###### Contoh:

Tentukan $\lim_{{x \to 2}} 4f(x)$ jika diketahui $\lim_{{x \to 2}} f(x) = 3.$

###### Langkah-langkah:

1.	Kita tahu bahwa $\lim_{{x \to 2}} f(x) = 3.$
2.	Menggunakan teorema ini, kita kalikan konstanta 4 dengan limit dari f(x):


$$\lim_{{x \to 2}} 4f(x) = 4 \times \lim_{{x \to 2}} f(x) = 4 \times 3 = 12$$


###### Penjelasan:  
Limit dari konstanta yang dikalikan dengan fungsi adalah konstanta tersebut dikalikan dengan limit fungsi.

#### 5.	Teorema (5):

$$\lim_{{x \to c}} [f(x) + g(x)] = \lim_{{x \to c}} f(x) + \lim_{{x \to c}} g(x)$$

Aturan limit untuk penjumlahan. Jika kita menjumlahkan dua fungsi, maka limit dari penjumlahan itu adalah penjumlahan dari masing-masing limit fungsi.


###### Contoh:

Tentukan $\lim_{{x \to 1}} [x^2 + 2x]$.

###### Langkah-langkah:

1.	Pisahkan limitnya:

$$\lim_{{x \to 1}} [x^2 + 2x] = \lim_{{x \to 1}} x^2 + \lim_{{x \to 1}} 2x$$

2.	Hitung limit masing-masing:

$$\lim_{{x \to 1}} x^2 = 1^2 = 1$$
$$\lim_{{x \to 1}} 2x = 2(1) = 2$$

3.	Tambahkan hasilnya:

$$1 + 2 = 3$$


###### Penjelasan:  
Limit dari penjumlahan dua fungsi dapat dipisahkan menjadi limit dari masing-masing fungsi.

#### 6.	Teorema (6):

$$\lim_{{x \to c}} [f(x) - g(x)] = \lim_{{x \to c}} f(x) - \lim_{{x \to c}} g(x)$$

Aturan yang sama seperti teorema (5), tetapi berlaku untuk pengurangan fungsi.


###### Contoh:

Tentukan $\lim_{{x \to 1}} [x^2 - 2x].$

###### Langkah-langkah:

1.	Pisahkan limitnya:

$$\lim_{{x \to 1}} [x^2 - 2x] = \lim_{{x \to 1}} x^2 - \lim_{{x \to 1}} 2x$$

2.	Hitung limit masing-masing:

$$\lim_{{x \to 1}} x^2 = 1^2 = 1$$
$$\lim_{{x \to 1}} 2x = 2(1) = 2$$

3.	Kurangkan hasilnya:

$$1 - 2 = -1$$

###### Penjelasan:  
Limit dari pengurangan dua fungsi dapat dipisahkan menjadi limit dari masing-masing fungsi.

#### 7.	Teorema (7):

$$\lim_{{x \to c}} [f(x) \cdot g(x)] = \lim_{{x \to c}} f(x) \cdot \lim_{{x \to c}} g(x)$$

Aturan untuk perkalian fungsi. Limit dari perkalian dua fungsi adalah perkalian dari limit masing-masing fungsi.

###### Contoh:

Tentukan $\lim_{{x \to 2}} [x \cdot (x + 1)].$

###### Langkah-langkah:

1.	Pisahkan limitnya:

$$\lim_{{x \to 2}} [x \cdot (x + 1)] = \lim_{{x \to 2}} x \cdot \lim_{{x \to 2}} (x + 1)$$

2.	Hitung limit masing-masing:

$$\lim_{{x \to 2}} x = 2$$
$$\lim_{{x \to 2}} (x + 1) = 2 + 1 = 3$$

3.	Kalikan hasilnya:

$$2 \times 3 = 6$$

###### Penjelasan:  
Limit dari perkalian dua fungsi dapat dipisahkan menjadi perkalian dari limit masing-masing fungsi.

#### 8.	Teorema (8):

$$\lim_{{x \to c}} \frac{f(x)}{g(x)} = \frac{\lim_{{x \to c}} f(x)}{\lim_{{x \to c}} g(x)}, \text{ dengan } \lim_{{x \to c}} g(x) \neq 0
$$
Aturan untuk pembagian fungsi. Limit dari pembagian dua fungsi adalah pembagian dari limit masing-masing fungsi, dengan syarat bahwa limit dari  g(x)  tidak boleh sama dengan nol.



###### Contoh:

Tentukan $\lim_{{x \to 3}} \frac{x^2}{x+1}.$

###### Langkah-langkah:

1.	Pisahkan limitnya:

$\lim_{{x \to 3}} \frac{x^2}{x+1} = \frac{\lim_{{x \to 3}} x^2}{\lim_{{x \to 3}} (x+1)}$

2.	Hitung limit masing-masing:

$$\lim_{{x \to 3}} x^2 = 3^2 = 9$$
$$\lim_{{x \to 3}} (x+1) = 3 + 1 = 4$$

3.	Bagi hasilnya:

$$\frac{9}{4}$$


###### Penjelasan: 
Limit dari pembagian dua fungsi adalah pembagian dari limit masing-masing fungsi, asalkan penyebut tidak sama dengan nol.

#### 9.	Teorema (9):

$$\lim_{{x \to c}} [f(x)]^n = \left( \lim_{{x \to c}} f(x) \right)^n$$

Jika kita memiliki fungsi  f(x)  yang dipangkatkan dengan bilangan bulat positif  n , maka limit dari fungsi tersebut adalah limit dari  f(x)  yang dipangkatkan dengan  n .

###### Contoh:

Tentukan $\lim_{{x \to 2}} (x^2)^3.$

###### Langkah-langkah:

1.	Hitung limit bagian dalamnya terlebih dahulu:

$$\lim_{{x \to 2}} x^2 = 2^2 = 4$$

2.	Pangkatkan hasilnya:

$$4^3 = 64$$


###### Penjelasan: 
Limit dari fungsi yang dipangkatkan adalah limit fungsi yang dipangkatkan.

#### 10.	Teorema (10):

$$\lim_{{x \to c}} \sqrt[n]{f(x)} = \sqrt[n]{\lim_{{x \to c}} f(x)}, \text{ untuk } \lim_{{x \to c}} f(x) > 0 \text{ dan } n \text{ genap}$$

Untuk fungsi akar, limit dari akar  n  dari fungsi  f(x)  adalah akar  n  dari limit  f(x) , dengan syarat bahwa limit dari  f(x)  lebih besar dari nol dan  n  adalah bilangan genap.

###### Contoh:
Tentukan $\lim_{{x \to 1}} \sqrt[2]{x^2 + 1}.$

Langkah-langkah:

1.	Hitung limit dari bagian dalam akar:

$$\lim_{{x \to 1}} (x^2 + 1) = 1^2 + 1 = 2$$

2.	Ambil akar kuadrat dari hasilnya:

$$\sqrt{2}$$


Penjelasan: Limit dari fungsi akar dapat dipisahkan menjadi akar dari limit fungsi, dengan syarat bahwa limit dari fungsi tersebut lebih besar dari nol dan pangkat n adalah bilangan genap.




## [[03. Limit Sepihak]]


#### 1. Limit dari arah Kiri

x mendekati a dari arah kiri, ditulis $x → a^-$ artinya untuk setiap $𝛿 > 0$ terdapat x sehingga $a - 𝛿  <x<a.$

$$x \to a^-$$

- Artinya, nilai x mendekati a dari arah kiri, atau dari nilai-nilai x yang lebih kecil dari a.
- Dinyatakan: untuk setiap $\delta > 0$, terdapat x sehingga $a - \delta < x < a$.
- Secara visual, x mendekati a dari arah kiri pada interval terbuka $(a - \delta, a)$.

![[Screenshot 2024-10-13 at 11.07.41.png]]



#### 2. Limit dari arah Kanan

x mendekati a dari arah kiri, ditulis $x → a^+$ artinya untuk setiap $𝛿 > 0$ terdapat x sehingga $a  <x<a+𝛿.$


$$x \to a^+$$


- Artinya, x mendekati a dari arah kanan, atau dari nilai-nilai x yang lebih besar dari a.
- Dinyatakan: untuk setiap $\delta > 0$, terdapat x sehingga $a < x < a + \delta.$
- Secara visual, x mendekati a dari arah kanan pada interval terbuka $(a, a + \delta)$.


![[Screenshot 2024-10-13 at 11.11.17.png]]


#### 3. Definisi 4.1.2 (Limit Sepihak)

##### 1. Limit Kiri


$$\lim_{{x \to a^-}} f(x) = L$$

Dikatakan L adalah limit kiri fungsi f(x) untuk x \to a^- jika nilai f(x) mendekati L ketika x mendekati a dari arah kiri.
![[Screenshot 2024-10-13 at 11.14.43.png]]


##### 2. Limit Kanan


$$\lim_{{x \to a^+}} f(x) = M$$

Dikatakan M adalah limit kanan fungsi f(x) untuk x \to a^+ jika nilai f(x) mendekati M ketika x mendekati a dari arah kanan.

![[Screenshot 2024-10-13 at 11.14.55.png]]




##### Contoh 4.1.11

Diketahui:  f(x) = x^2 + 1 , maka:

(a)  $\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (x^2 + 1) = 2$ 

(b)  $\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (x^2 + 1) = 2$

(c)  $\lim_{x \to 1} f(x) = \lim_{x \to 1} (x^2 + 1) = 2$

###### Penjelasan:

Fungsi  $f(x) = x^2 + 1$  adalah fungsi polinomial yang kontinu di seluruh domainnya. Maka nilai limit dari arah kiri  $x \to 1^-$ , arah kanan $x \to 1^+$ , maupun limit saat  $x \to 1$  adalah sama, yaitu 2.

##### Contoh 4.1.12

Diketahui:  $f(x) = 3x^2 - 4x + 5$ , maka:

(a)  $\lim_{x \to -1^-} f(x) = \lim_{x \to -1^-} (3x^2 - 4x + 5) = 12$ 

(b)  $\lim_{x \to -1^+} f(x) = \lim_{x \to -1^+} (3x^2 - 4x + 5) = 12$ 

(c)  $\lim_{x \to -2^-} f(x) = \lim_{x \to -2^-} (3x^2 - 4x + 5) = 25$ 

(d)  $\lim_{x \to -2^+} f(x) = \lim_{x \to -2^+} (3x^2 - 4x + 5) = 25$ 

###### Penjelasan:

Karena  f(x)  juga merupakan fungsi polinomial yang kontinu, limit dari arah kiri dan kanan pada titik tertentu akan memberikan hasil yang sama. Pada  x = -1 , hasilnya adalah 12, dan pada  x = -2 , hasilnya adalah 25.

##### Contoh 4.1.13


Diketahui:

$f(x) =\begin{cases}x^2, & x \geq 2 \\x, & x < 2\end{cases}$

Hitung:
(a)  $\lim_{x \to 2^-} f(x) = \lim_{x \to 2^-} x = 2$

(b)  $\lim_{x \to 2^+} f(x) = \lim_{x \to 2^+} x^2 = 4$ 

###### Penjelasan:

- Untuk  $x \to 2^-$ , kita gunakan fungsi yang berlaku saat  $x < 2$ , yaitu  $f(x) = x$ , sehingga limitnya adalah 2.
  
- Untuk  $x \to 2^+$ , kita gunakan fungsi yang berlaku saat  $x \geq 2$ , yaitu  $f(x) = x^2$ , sehingga limitnya adalah 4.

##### Contoh 4.1.14

Hitung nilai:
(a)  $\lim_{x \to 1} f(x)$ 
(b)  $\lim_{x \to 1^-} f(x) , dengan  f(x) = \frac{|x - 1|}{x - 1}$ 

###### Penjelasan:

$f(x) = \frac{|x - 1|}{x - 1}$  adalah fungsi yang bersifat piecewise:
Jika  x > 1 , maka  $|x - 1| = x - 1$ , sehingga  $f(x) = 1$ .
Jika  x < 1 , maka  $|x - 1| = -(x - 1)$ , sehingga  $f(x) = -1$ .

(a)  $\lim_{x \to 1} f(x)$  tidak ada, karena nilai limit dari arah kiri dan kanan berbeda.
(b)  $\lim_{x \to 1^-} f(x) = -1$  (karena  $f(x) = -1$  untuk  $x < 1$ ).

##### Contoh 4.1.15

Hitung nilai:
(a)  $\lim_{x \to 1^-} f(x)$ 
(b)  $\lim_{x \to 1^+} f(x)$ , dengan:


$f(x) =\begin{cases}x^2, & x < 1 \\1, & x = 1 \\x, & x > 1\end{cases}$


###### Penjelasan:

- Untuk  $x \to 1^-$ , kita gunakan fungsi  f(x) = x^2 , sehingga  $\lim_{x \to 1^-} f(x) = 1^2 = 1$ .
- Untuk  $x \to 1^+$ , kita gunakan fungsi  f(x) = x , sehingga  $\lim_{x \to 1^+} f(x) = 1$ .

Jadi, limit dari arah kiri dan kanan sama-sama bernilai 1.



#### 4. Teorema 4.1.1

##### Teorema 1
  $$\lim_{{x \to a^-}} f(x) = L  dan  \lim_{{x \to a^+}} f(x) = L$$ maka:

$$\lim_{{x \to a}} f(x) = L$$

Penjelasan: 

Jika limit kiri dan limit kanan dari suatu fungsi f(x) sama di a, maka limit dari f(x) di a ada dan nilainya sama dengan L.


##### Teorema 2

Sebaliknya, jika  $$\lim_{{x \to a}} f(x) = L$$ maka:

$$\lim_{{x \to a^-}} f(x) = \lim_{{x \to a^+}} f(x) = L$$

Penjelasan: 

Jika limit fungsi f(x) di a ada dan sama dengan L, maka limit kiri dan limit kanan juga ada dan nilainya sama dengan L.


Dari Teorema 4.1.1 diperoleh, apabila

![[Screenshot 2024-10-13 at 12.33.40.png]]


##### Contoh 4.1.16

Diketahui:

$$f(x) = \begin{cases}1 - x^2, & x \leq 1 \\x, & x > 1\end{cases}$$

Diminta: Periksa apakah  f(x)  memiliki limit di  x = 1 .

###### Langkah 1 : Hitung limit dari arah kiri  $(x \to 1^-)$

Untuk  $x \leq 1$ , fungsi yang digunakan adalah  $f(x) = 1 - x^2$ .

Maka:

$$\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (1 - x^2) = 1 - (1)^2 = 0$$

###### Langkah 2 : Hitung limit dari arah kanan  $(x \to 1^+)$

Untuk  $x > 1$, fungsi yang digunakan adalah  $f(x) = x .$

Maka:

$$\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} x = 1$$
###### Langkah 3: Bandingkan limit kiri dan limit kanan

Dari arah kiri,  $\lim_{x \to 1^-} f(x) = 0$ , dan dari arah kanan,  $\lim_{x \to 1^+} f(x) = 1$ .

Karena  $$\lim_{x \to 1^-} \neq \lim_{x \to 1^+} $$, maka limit  $f(x)  di  x = 1$  tidak ada.

###### Kesimpulan

Limit tidak ada di  x = 1 .


##### Contoh 4.1.17

Diketahui:

$$f(x) = \begin{cases}\frac{x^2 - 3x + 2}{x - 1}, & x > 1 \\2x - 3, & x \leq 1\end{cases}$$

Diminta: Periksa apakah $\lim_{x \to 1} f(x)$  ada.

###### Langkah 1: Hitung limit dari arah kiri  $(x \to 1^-)$ 

Untuk  $x \leq 1$ , fungsi yang digunakan adalah  $f(x) = 2x - 3$ .

Maka:

$$\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} (2x - 3) = 2(1) - 3 = -1$$

###### Langkah 2: Hitung limit dari arah kanan  ($x \to 1^+$) 

Untuk  x > 1 , fungsi yang digunakan adalah  

$$f(x) = \frac{x^2 - 3x + 2}{x - 1}$$ .

Kita sederhanakan fungsi terlebih dahulu:

$$\frac{x^2 - 3x + 2}{x - 1} = \frac{(x - 1)(x - 2)}{x - 1}$$

Karena ada faktor  (x - 1)  di pembilang dan penyebut, kita bisa membatalkan  (x - 1) , sehingga:

$$f(x) = x - 2 \text{ untuk } x > 1$$

Maka:

$$\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (x - 2) = 1 - 2 = -1$$

###### Langkah 3: Bandingkan limit kiri dan limit kanan

Dari arah kiri,  $\lim_{x \to 1^-} f(x) = -1$ , dan dari arah kanan,  $\lim_{x \to 1^+} f(x) = -1$ .

Karena  $\lim_{x \to 1^-} = \lim_{x \to 1^+} = -1$ , maka limit  f(x)  di  x = 1  ada dan bernilai -1.

###### Kesimpulan

Limit ada di  x = 1  dan bernilai -1.



## [[04. Limit di Tak Hingga]]

Ada dua jenis limit di tak hingga yaitu:

- x semikin besar menuju ke ∞
  
-  x semikin kecil menuju ke ∞

#### a. Untuk x makin besar menuju ke ∞

Pengertian x makin besar menuju tak hingga, ditulis x →∞ adalah

> ∀K > 0 terdapat x sehingga x > K .

Nilai $lim_{x→∞} f(x) = L$, artinya f(x) → L apabila x makin besar menuju d0. Secara matematis, untuk setiap $\varepsilon > 0$ terdapat $K > 0$ 

sehingga

$|f(x) - L|$ < $\varepsilon$  untuk semua x > K . Secara geometris y = L merupakan asimtot datar

![[Screenshot 2024-10-13 at 15.45.22.png]]


#### b. Untuk x makin kecil menuju ke ∞

Pengertian x makin kecil menuju tak hingga, ditulis $x→ -∞$ adalah
$∀K > 0$ terdapat x sehingga $x <-K$.

Nilai $lim_{x→∞} f(x) =M$ artinya $f(x) → M$ apabila x makin kecil menuju
$-∞$. Secara matematis, untuk setiap $\varepsilon > 0$ terdapat $K > 0$ sehingga

$|f(x) - L| < \varepsilon$ untuk semua $x < - K$ . Secara geometris $y = M$ merupakan asimtot datar

![[Screenshot 2024-10-13 at 15.48.45.png]]

#### Contoh 4.1.18

![[Screenshot 2024-10-13 at 15.56.22.png]]

#### Contoh 4.1.19

![[Screenshot 2024-10-13 at 15.56.41.png]]

#### Contoh 4.1.20

![[Screenshot 2024-10-13 at 15.57.02.png]]



## [[05. Limit tak Hingga]]


#### (a) $\lim_{x \to a} f(x) = \infty$

Nilai $lim_{x→a} f(x) =∞$, 

artinya $f(x) → ∞$ apabila $x→a$. Secara matematis, untuk setiap $K > 0$ betapapun besarnya, terdapat $𝛿 > 0$ sehingga $f(x) > K$ untuk $0<|x-a| < 𝛿$. Secara geometris dapat dilihat Garis x = a merupakan asimtot tegak.

###### Makna dari limit ini:

- Ini berarti bahwa saat x mendekati a (baik dari kiri atau kanan), nilai fungsi f(x) meningkat tanpa batas, menuju tak hingga ($\infty$).
  
- Jadi, ketika x mendekati nilai tertentu aaa, nilai f(x) tidak berhenti bertambah besar, dan tidak ada batas atas untuk nilainya.

- **Contoh:**
   
  Fungsi yang sering menunjukkan perilaku ini adalah $f(x) = \frac{1}{(x - a)^2}$​. Ketika x mendekati a, nilai f(x) menjadi sangat besar, karena pembilang tetap konstan (1), sedangkan penyebut mendekati 0 dari kedua arah, sehingga hasilnya mendekati tak terhingga.

![[Screenshot 2024-10-13 at 16.06.35.png]]

#### (b) $\lim_{x \to a} f(x) = -\infty$

artinya $f(x) →—∞$ apabila $x→a$. Secara matematis, untuk setiap $K > 0$ betapapun besarnya, terdapat $𝛿 > 0$ sehingga $f(x) <-K$ untuk $0<|x-a|<𝛿$ . Secara geometris dapat dilihat Garis x = a merupakan asimtot tegak.

###### Makna dari limit ini:

- Ini berarti bahwa saat xxx mendekati aaa, nilai fungsi f(x) menurun tanpa batas, menuju negatif tak hingga ($-\infty$).
  
- Ketika x semakin dekat ke aaa, f(x) semakin kecil, namun tidak ada batas bawah, yaitu terus menurun hingga nilai yang sangat kecil tanpa batas.
  
- **Contoh:** 
  
  Fungsi yang bisa menunjukkan perilaku ini adalah $f(x) = \frac{-1}{(x - a)^2}$. Ketika x mendekati a, nilai fungsi f(x) menjadi sangat kecil dan menuju $-\infty$ karena pembilang negatif, sementara penyebut mendekati nol.

![[Screenshot 2024-10-13 at 16.06.53.png]]

#### Contoh 4.1.21

![[Screenshot 2024-10-13 at 16.11.36.png]]



