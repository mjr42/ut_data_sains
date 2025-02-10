---
tags:
  - kalkulus_1
---


Materi : 
- [[01. Fungsi]]
- [[02. Operasi Fungsi]]
- [[03. Fungsi Komposisi (Fungsi Bersusun)]]
---

## Pengertian Fungsi

![[Screenshot 2024-08-18 at 19.29.24.png]]

Terlihat dari bagan diatas bahwa setiap anggota di K memiliki hanya satu pasangan di N. Ada kemungkinan lebih dari satu anggota di K yang memiliki pasangan yang sama di N, tetapi tidak mungkin dua anggota di N berbeda memiliki pasangan di K yang sama. Ada kemungkinan unsur di N tidak memiliki pasangan di K, dari penjelasan tersebut dapat didefinisikan bahwa fungsi adalah

> Misalkan A dan B dua himpunan, Suatu fungsi F dari A ke B didefinisikan sebagai suatu aturan yang mengkaitkan setiap anggota A dengan satu dan hanya satu anggota B
> 
> - Himpunan A disebut Domain atau daerah definisi atau daerah asal f
> - Ditulis F himpunan B disebut domain atau daerah nilai f
> - Himpunan bagian B yang anggotanya memiliki kaitan dengan anggota di A disebut Jelajah atau Range f ditulis R(f)
> - Sehingga bisa dituliskan $R(f) = {f(x|x∊A)}$

>Fungsi F dari A ke B ditulis dengan f: A ➝ B
![[Screenshot 2024-08-18 at 19.37.55.png]]

Dalam konteks ini, baik himpunan A maupun himpunan B berupa himpunan bilangan Real ℝ yang meliputi bilangan asli, bulat, rasional dan lain lain kecuali bilangan kompleks


### Menentukan $D(f)$ dan $R(f)$

Daerah definisi D(f) dan jelajah R(f) cukup penting dalam pembahasan fungsi. Oleh karena itu, kita akan membahas D(f) dan R(f) lebih rinci

#### Case Study 1

![[Screenshot 2024-08-18 at 19.43.59.png]]

##### Definisikan fungsi $f: R ➝ R$ | $f(x) = x$ 
- Definisi: Fungsi  f(x) = x , yang artinya setiap nilai input  x  dipetakan langsung ke nilai yang sama pada output.
- Nilai fungsi : $f(-2) = -2$, Nilai fungsi : $f(-1) = -1$, Nilai fungsi : $f(0) = 0$
- Jika diteruskan dengan nilai nilai yang lain makan dapat secara umum dituliskan sebagai $f(x) = x . D(f) = (-∞,∞) = R . Kodomain F = R(f) = (-∞,∞) = R$
- Nilai-nilai seperti  -2 ,  -1 ,  0 ,  1 , dan  2  dipetakan langsung ke nilai yang sama di kodomain.
- Domain: Semua bilangan real  $\mathbb{R}$ 
- Kodomain: Semua bilangan real  $\mathbb{R}$ 
- Secara umum, fungsi  $f(x) = x$  adalah fungsi identitas, di mana outputnya sama dengan inputnya
-  $y = f(x) = x$

#### Case Study 2

![[Screenshot 2024-08-18 at 19.49.36.png]]

##### Definisikan fungsi $f: R ➝ R$ | $f(x) = x^2$
- Nilai-nilai seperti  -3 ,  -2 ,  -1 ,  0 ,  1 ,  2 , dan  3  dipetakan ke  9 ,  4 ,  1 , dan  0  di kodomain.
- Fungsi ini memetakan nilai negatif dan positif dari domain yang sama ke output yang sama, karena  $x^2$  adalah fungsi kuadrat.
- NIlai fungsi $f(-3) = 9 = (-3)^2 , f(3) = (3)^2 = 9, f(-2) = 4 = (-2)^2$
- Fungsi  $f(x) = x^2$ , yang artinya setiap nilai input  x  dipetakan ke nilai kuadratnya.
- JIka diteruskan dengan nilai nilai yang lain maka secara umum dapat diformulasikan sebagai $f (x) = x^2 . D(f) = (-∞,∞) = R . Kodomain f = R, R(f) = (0,∞) = {f(x)|f(x) ≥0}$
- Domain: Semua bilangan real  $\mathbb{R}$ 
- Kodomain: Semua bilangan real  $\mathbb{R}$  tapi karena fungsi ini menghasilkan bilangan kuadrat, hasilnya adalah bilangan real positif.
- fungsi  $f(x) = x^2$  adalah fungsi kuadrat, di mana outputnya adalah kuadrat dari inputnya.
- $y = f(x)=x^2$

#### Case Study 3
![[Screenshot 2024-08-18 at 20.00.20.png]]

##### Definisikan fungsi $f: R ➝ R$ 
- Nilai fungsi $f(-3) = 3, f(-2)=3, f(-1)=3$
- jika diteruskan dengan nilai nilai lainnya dapat diformulasikan sebagai $f(x)=3 . D(f) = (-∞,∞) = R . Kodomain f = R . r(f)={3}={f(x)|f(x)=3}$
- $y = f(x)=3$


#### Case Study 4
##### Diketahui fungsi $y = f(x) = \frac{1}{x}$ 

###### Nilai Fungsi (untuk x negatif)

- Fungsi ini dievaluasi pada beberapa nilai x, seperti  
  $x = -100 ,  x = -2 ,  x = -\frac{1}{2}$ , dan  $x = -\frac{1}{100}$ .
  
- Contoh nilai:
	•	 $f(-100) = -\frac{1}{100} = -0,01$ 
	•	 $f(-2) = -\frac{1}{2} = -0,5$ 
	•	 $f(-\frac{1}{2}) = -2$ 
	•	 $f(-\frac{1}{100}) = -100$ 

- Ketika  x  bernilai negatif dan semakin mendekati 0 dari kiri (kecil), nilai  f(x)  menjadi semakin besar secara negatif (makin kecil mendekati 0).

- Jika  x  semakin negatif tetapi tidak boleh bernilai 0, maka nilai  f(x)  akan semakin negatif dan mendekati nilai besar negatif (tapi tidak pernah mencapai nol). Jika  x  semakin negatif besar, maka nilai  f(x)  akan semakin mendekati nol dari arah negatif.
  
###### Nilai Fungsi (untuk x positif)

- Fungsi juga dievaluasi untuk nilai  x  positif seperti  $x = 100 ,  x = 2 ,  x = \frac{1}{2}$ , dan  $x = \frac{1}{100}$ .
  
- Contoh nilai:
	•	 $f(100) = \frac{1}{100} = 0,01$ 
	•	 $f(2) = \frac{1}{2} = 0,5$ 
	•	 $f(\frac{1}{2}) = 2$ 
	•	 $f(\frac{1}{100}) = 100$ 

- Ketika  x  bernilai positif dan mendekati 0 dari kanan (positif), nilai  f(x)  menjadi semakin besar (makin besar mendekati 0 dari arah positif).
  
- Jika  x  mendekati 0 dari kanan tetapi tidak boleh bernilai 0, maka nilai  f(x)  akan semakin besar. Sebaliknya, jika  x  semakin besar ke kanan, nilai  f(x)  akan semakin kecil menuju 0.

###### Daerah Definisi dan Daerah Hasil

- Karena fungsi ini tidak didefinisikan pada  x = 0  (akan menjadi tak terhingga), **daerah definisi** dari fungsi ini adalah semua bilangan real kecuali 0, yaitu  
  $D(f) = \{x | x \in \mathbb{R}, x \neq 0\} .$ atau ((-∞, 0) ∪ (0,∞))
  
- **Daerah hasil (range)** adalah semua bilangan real kecuali 0, yaitu  
  $R(f) = \{y | y \in \mathbb{R}, y \neq 0\} .$ atau ((-∞, 0) ∪ (0,∞))
###### Secara keseluruhan, fungsi ini memiliki sifat bahwa nilainya besar secara negatif saat  x  negatif mendekati 0 dari kiri dan nilainya besar secara positif saat  x  positif mendekati 0 dari kanan. Nilai fungsi tidak pernah mencapai 0, baik dari daerah definisi maupun daerah hasilnya.


#### Case Study 5
##### Diketahui fungsi  $y = f(x) = \sqrt{x}$ 

- Fungsi ini dievaluasi pada beberapa nilai x, seperti :
  0,  $\frac{1}{4}$, 2, 100, 1000

- Nilai fungsi:
	•	 $f(0) = \sqrt{0} = 0$ 
	•	 $f\left(\frac{1}{4}\right) = \sqrt{\frac{1}{4}} = \frac{1}{2}$ 
	•	 $f(2) = \sqrt{2}$ 
	•	 $f(100) = \sqrt{100} = 10$ 
	•	 $f(10000) = \sqrt{10000} = 100$ 

- Domain ($D(f)$): Karena fungsi akar kuadrat, nilai di dalam akar ( x ) harus lebih besar atau sama dengan 0 (karena jika lebih kecil, akan menghasilkan bilangan kompleks). Oleh karena itu,  $x \geq 0$ . Domain dari fungsi ini adalah  D(f) = [0, ∞) .
  
- Range ($R(f)$): Nilai dari akar kuadrat selalu positif atau 0, sehingga range dari fungsi ini adalah  $R(f)$ = [0, ∞) .


#### Case Study 6
##### Diketahui fungsi  $f(x) = \sqrt{x - 2}$ 

- **Domain (D(f))**:
	- Karena  $f(x) = \sqrt{x - 2}$ , maka  $x - 2 \geq 0$  atau  $x \geq 2$ .
	- Jadi, domain dari fungsi ini adalah  $D(f)$ = [2, ∞)

- **Range (R(f))**:
	- Nilai dari  $\sqrt{x - 2}$  selalu lebih besar atau sama dengan 0, sehingga range dari fungsi ini adalah  $R(f)$ = [0, ∞)

- Fungsi  $f: A \rightarrow B$  dikatakan satu-satu (injektif) jika untuk setiap  $x, y \in D(f)$  dan  $x \neq y$ , berlaku  $f(x) \neq f(y)$ .
	- Untuk membuktikan suatu fungsi  f  adalah satu-satu, kita ambil  f(x) = f(y)  kemudian tunjukkan bahwa  x = y .
	- Konsep fungsi satu-satu sangat penting untuk memahami fungsi invers.


#### Fungsi satu-satu (Injektif)

- **Diketahui Fungsi  $f: \mathbb{R} \rightarrow \mathbb{R}$  dengan  $f(x) = 2x$ .**
	- Untuk menunjukkan apakah fungsi ini satu-satu, diuji apakah  $f(a) = f(b)$  mengimplikasikan  $a = b$ .
	- Diperoleh  $f(a) = 2a$  dan  $f(b) = 2b$ , yang berarti  $2a = 2b$ , sehingga  $a = b$ .
	  ![[Screenshot 2024-08-19 at 21.33.02.png]]
	- Kesimpulan: Fungsi  $f(x) = 2x$  adalah fungsi satu-satu karena  $f(a) = f(b)$  hanya terjadi jika  $a = b$ .


- **Diketahui Fungsi  $f: \mathbb{R} \rightarrow \mathbb{R}$  dengan  $f(x) = x^2$ .**
	- Diuji apakah  $f(a) = f(b)$  mengimplikasikan  $a = b$ .
	- Diperoleh  $f(a) = a^2$  dan  $f(b) = b^2$ , yang berarti  $a^2 = b^2$ , sehingga  $a = \pm b$ .
	  ![[Screenshot 2024-08-19 at 21.35.47.png]]
	- Karena terdapat dua nilai untuk  b , yaitu  $b = a$  dan  $b = -a$ , fungsi ini tidak satu-satu. Misalnya,  $f(2) = f(-2) = 4$ , tetapi  $2 \neq -2$ .
	- Kesimpulan: Fungsi  $f(x) = x^2$  bukan fungsi satu-satu.


#### Definisi Fungsi Pada (Surjektif)

Fungsi  $f: A \rightarrow B$  disebut pada (surjektif) jika untuk setiap  $y \in B$ , terdapat  $x \in A$  sehingga  $f(x) = y$ . 

>- Dengan kata lain  $f: A \rightarrow B$  pada apabila $R(f)=B$
>- Untuk menentukan bahwa $f: A \rightarrow B$ pada, ambil sembarang $y \in B$ dan carilah $x \in A$  sehingga  $f(x) = y$ . 

Contoh 2.1.9:
- Bagian (a): Fungsi  $f: \mathbb{R} \rightarrow \mathbb{R}$  dengan  $f(x) = x^2$  tidak pada, karena tidak ada  $x \in \mathbb{R}$  sehingga  $y = f(x) = -2$

- Fungsi  $f: \mathbb{R}^+_0 \rightarrow \mathbb{R}^+_0$  dengan  $f(x) = x^2$  adalah fungsi pada, karena untuk setiap  $y \geq 0$  terdapat  $x = \sqrt{y} \in \mathbb{R}$  sehingga  $f(x) = y$ .

-  Fungsi $f: \mathbb{R} \rightarrow$ [0,∞) dengan f(x)=x^2 pada karena ∀y ∈ [0,∞] terdapat $x = \sqrt{y} \in \mathbb{R}$  sehingga  $f(x) = y$ .


#### Case Study 7

######  $f: \mathbb{R} \rightarrow \mathbb{R}$  dengan  $f(x) = \sqrt{x^2 + 1}$  bukan fungsi pada.

- Langkah 1: Ambil  y = -6 , yang merupakan anggota dari  $\mathbb{R}$ .
  
- Langkah 2: Coba temukan  $x \in \mathbb{R}$  sehingga  $f(x) = \sqrt{x^2 + 1} = -6$ .
  
- Kesimpulan: Tidak ada  $x \in \mathbb{R}$  yang memenuhi persamaan  $\sqrt{x^2 + 1} = -6$ . Ini karena hasil akar kuadrat selalu non-negatif, sehingga tidak mungkin mendapatkan hasil negatif seperti -6. Karena tidak semua  $y \in \mathbb{R}$  memiliki  x  yang memenuhi  $f(x) = y$ , maka fungsi  $f(x) = \sqrt{x^2 + 1}$  bukan fungsi pada.
  
- Pada bagian (a), fungsi  $f(x) = \sqrt{x^2 + 1}$  tidak pada karena tidak semua nilai  $y \in \mathbb{R}$  dapat dicapai oleh fungsi ini (misalnya, nilai negatif tidak mungkin tercapai).

######  $f: \mathbb{R} \rightarrow ([-1, \infty)  dengan  f(x) = \sqrt{x + 1}$  adalah fungsi pada.

- Langkah 1: Ambil  y  sebagai anggota dari  $([-1, \infty)$ .
  
- Langkah 2: Cari  x  sedemikian rupa sehingga  $f(x) = \sqrt{x + 1} = y$ .
  
- Langkah 3: Persamaan ini dapat ditulis sebagai  $y^2 = x + 1$ , sehingga  $x = y^2 - 1$ .
  
- Kesimpulan: Setiap  y  di interval  $([-1, \infty)$  memiliki nilai  x  yang sesuai, yaitu  $x = y^2 - 1$ , sehingga fungsi ini adalah fungsi pada.
  
- fungsi  $f(x) = \sqrt{x + 1}$  pada untuk domain  $\mathbb{R}$  dan kodomain  $([-1, \infty)$ , karena setiap nilai  y  dalam kodomain dapat dicapai dengan nilai  x  tertentu.


## Operasi Fungsi

Pada umumnya fungsi-fungsi yang kita temui merupakan hasil operasi atau aljabar dari beberapa fungsi sederhana. Misalnya, 

![[Screenshot 2024-08-20 at 10.01.35.png]]

Fungsi ini merupakan hasil operasi dari beberapa fungsi sederhana. Operasi atau aljabar antar fungsi didefinisikan sebagai berikut:

#### Misalkan $f : \mathbb{R} \rightarrow \mathbb{R}$  dan  $g : \mathbb{R} \rightarrow \mathbb{R}$ , dua fungsi dan  $\alpha \in \mathbb{R}$ . Maka fungsi fungsi $(f \pm g) , (\alpha f) , (fg),$ dan $\left(\frac{f}{g}\right)$


###### 1. Penjumlahan / Pengurangan Fungsi

- $(f \pm g)(x) = f(x) \pm g(x)$
- Domain dari  $f \pm g$  adalah  $D(f) \cap D(g)$ .

###### 2. Pengalian Fungsi dengan Skalar

- $(\alpha f)(x) = \alpha \cdot f(x)$
- Domain dari  $\alpha f$  adalah  $D(f)$ .

###### 3. Perkalian Dua Fungsi

- $(fg)(x) = f(x) \cdot g(x)$
- Domain dari  $fg$  adalah  $D(f) \cap D(g)$ .

###### 4. Pembagian Dua Fungsi

- $\left(\frac{f}{g}\right)(x) = \frac{f(x)}{g(x)}, \quad g(x) \neq 0$
- Domain dari  $\frac{f}{g}$  adalah  $D(f) \cap D(g)$ , dengan syarat  $g(x) \neq 0$ .


#### Misalkan diketahui fungsi  $f(x) = x^2$ ,  $D(f) = \mathbb{R}$  dan  $g(x) = 3$ ,  $D(g) = \mathbb{R}$ . Maka operasi aljabar antara  $f$  dan  $g$  adalah sebagai berikut:


###### 1. Penjumlahan Fungsi

- $(f + g)(x) = f(x) + g(x) = x^2 + 3$
- Domainnya adalah  $D(f + g) = D(f) \cap D(g) = \mathbb{R}$ .

###### 2. Pengurangan Fungsi

- $(f - g)(x) = f(x) - g(x) = x^2 - 3$
- Domainnya adalah  $D(f - g) = D(f) \cap D(g) = \mathbb{R}$ .

###### 3. Pengalian Fungsi dengan Skalar:

- $(5f)(x) = 5f(x) = 5x^2$
- Domainnya adalah  $D(5f) = D(f) = \mathbb{R}$ .

###### 4. Perkalian Dua Fungsi:

- $(fg)(x) = f(x)g(x) = x^2 \cdot 3 = 3x^2$
- Domainnya adalah  $D(fg) = D(f) \cap D(g) = \mathbb{R}$ .

###### 5. Pembagian Dua Fungsi:

- $\left(\frac{f}{g}\right)(x) = \frac{f(x)}{g(x)} = \frac{x^2}{3}$
- Domainnya adalah  $D\left(\frac{f}{g}\right) = D(f) \cap D(g) = \mathbb{R}$ .

Penjelasan ini menunjukkan bagaimana operasi dasar dalam aljabar fungsi dilakukan, beserta dengan domain dari hasil operasi tersebut.


#### Diketahui fungsi  $f(x) = x^2$  dengan domain  $D(f) = \mathbb{R}$ , dan  $g(x) = \sqrt{x-1}$  dengan domain  $D(g) = ([1, \infty)$ . Diminta untuk menentukan:


#####  $5f - g$  dan  $D(5f - g)$ 

 - $5f(x) - g(x) = 5x^2 - \sqrt{x-1}$ 
 - Domain dari  5f - g  adalah perpotongan dari domain  f  dan  g : $D(5f - g) = D(f) \cap D(g) = \mathbb{R} \cap ([1, \infty) = [1, \infty)$

##### $\frac{1}{2} f g^2$  dan  $D\left(\frac{1}{2} f g^2\right)$ 

 - $\frac{1}{2} f(x) g(x)^2 = \frac{1}{2} x^2 \left(\sqrt{x-1}\right)^2 = \frac{1}{2} x^2 (x-1) = \frac{1}{2} x^2 x - \frac{1}{2} x^2 = \frac{1}{2} x^3 - \frac{1}{2} x^2$ 
 - Domain dari  $\frac{1}{2} f g^2$  adalah  $D(f) \cap D(g^2)$ . Karena  $g(x)^2 = (\sqrt{x-1})^2 = x-1$ , maka domainnya: $D(g^2) = D(g) = ([1, \infty)$
 - Sehingga: $D\left(\frac{1}{2} f g^2\right) = D(f) \cap D(g^2) = \mathbb{R} \cap ([1, \infty) = [1, \infty)$

##### $\frac{2f - g}{g}$  dan  $D\left(\frac{2f - g}{g}\right)$ 

- Pertama, hitung  $2f(x) - g(x) : 2f(x) - g(x) = 2x^2 - \sqrt{x-1}$
- Kemudian, bagi hasil di atas dengan  $g(x) : \frac{2f - g}{g} = \frac{2x^2 - \sqrt{x-1}}{\sqrt{x-1}}$
- Domain dari fungsi ini adalah perpotongan dari domain  $2f - g$  dan  $g(x)$ , dengan syarat  $g(x) \neq 0$ . Karena  $g(x) = \sqrt{x-1}$ , maka: $D(g) = ([1, \infty), \quad g(x) \neq 0$  untuk $x > 1$
- Sehingga: $D\left(\frac{2f - g}{g}\right) = ([1, \infty)$


#### Diketahui  $f(x) = 1 - x^2$  dan  $g(x) = x + \sqrt{x}$ . Diminta untuk menentukan:

![[Screenshot 2024-08-20 at 10.46.02.png]]

#####  $f + g^2$  dan  $D(f + g^2)$ 

![[Screenshot 2024-08-20 at 10.48.34.png]]
- $g^2(x) = (x + \sqrt{x})^2$  sehingga  $f(x) + g^2(x) = (1 - x^2) + (x + \sqrt{x})^2$ 
- Domain dari  $f + g^2$  adalah perpotongan dari domain  $f(x)$  dan domain  $g^2(x)$ .

#####  $3fg$  dan  $D(3fg)$ 

![[Screenshot 2024-08-20 at 10.48.20.png]]
- $3fg(x) = 3(1 - x^2)(x + \sqrt{x})$ 
- Domain dari  $3fg$  adalah perpotongan dari domain  $f(x)$  dan  $g(x)$ .


Untuk menentukan domain secara tepat, perlu dilakukan analisis lebih lanjut terhadap  $g(x)$  dan  $g^2(x)$ , serta memeriksa syarat-syarat yang harus dipenuhi agar fungsi tersebut terdefinisi dengan baik.


#### Tentukan fungsi-fungsi sederhana dari fungsi  $f(x) = \frac{\sqrt{x} - x^2}{5x^3 + x}$ 
![[Screenshot 2024-08-20 at 11.01.38.png]]

- Fungsi  $f(x)$  dapat ditulis sebagai: $f(x) = \frac{g}{h}$
- Di mana:
	•	 $g = g_1 - g_2$ 
	•	 $h = h_1 + h_2$ 

- Selanjutnya, masing-masing fungsi  g  dan  h  juga dapat diuraikan lebih lanjut menjadi fungsi-fungsi yang lebih sederhana:
	-  $g_1 = (g_{11})(g_{12})$ , dengan  $g_{11}(x) = x$  dan  $g_{12}(x) = \sqrt{x}$ , sehingga  $g_1(x) = x \cdot \sqrt{x}$ .
	- $g_2(x) = x^2$ 

- Untuk  h :
	-  $h_1(x) = (h_{11})(h_{12})$ , dengan  $h_{11}(x) = 5$  dan  $h_{12}(x) = x^3$ , sehingga  $h_1(x) = 5x^3$ .
	- $h_2(x) = x$ 

- Dengan demikian, fungsi  f(x)  yang semula kompleks dapat diuraikan menjadi operasi-operasi fungsi sederhana sebagai berikut:
	- $f(x) = \frac{(g_{11})(g_{12}) - g_2}{(h_{11})(h_{12}) + h_2}$

- Atau lebih eksplisit:
	- $f(x) = \frac{x \cdot \sqrt{x} - x^2}{5x^3 + x}$

Dengan langkah ini, kita melihat bahwa fungsi kompleks  f(x)  sebenarnya dibentuk oleh operasi sederhana dari beberapa fungsi dasar, yaitu perkalian, pengurangan, dan penjumlahan antara fungsi-fungsi yang lebih sederhana.


## Fungsi Komposisi (Fungsi Bersusun)

Fungsi komposisi atau fungsi bersusun adalah dua fungsi dengan aturan f: A → B dan g: B → C. kemudian didefinisikan sebagai h: A → C dengan aturan sebagai berikut:

Untuk $x ∈ A$ gunakan aturan $f$ untuk menentukan unsur $y=f(x) ∈ B$ dan kemudian gunakan aturan g untuk menentukan $g(y) ∈ C$ yang disebut dengan $h(x)$, dan ini dituliskan dengan notasi

$h(x) = g f(x) , x ∈ A$

fungsi $h= g ∘ f$ dikenal sebagai komposisi g dan f.
Umumnya, dapat didefinisikan fungsi komposisi g ∘ f dari A ke C apabila f : A → B dan g: B → C dengan $R(f) ∩ D(g) ≠ ∅.$

Daerah definisi $D(g∘f) = x ∈ A|f(x)∈R(f)∩D(g)$
![[Screenshot 2024-09-22 at 13.46.27.png]]

Dengan cara yang sama $D(f∘g) = x ∈ A|g(x)∈R(g)∩D(f)$
Pada umumnya $D(f∘g) ≠ D(g∘f)$

### Contoh 2.1.10

Diketahui fungsi  $f(x) = x - 1$  dan  $g(x) = x^2 + 2$ , kita diminta untuk menentukan:

##### (a) Hitunglah  $(g \circ f)(x)$

1.	Definisi komposisi fungsi: $(g \circ f)(x) = g(f(x))$

2.	Langkah pertama: Substitusi  $f(x) = x - 1$  ke dalam  $g(x)$ : $g(f(x)) = g(x - 1) = (x - 1)^2 + 2$

3.	Langkah kedua: Hitung ekspresi tersebut:
	$(x - 1)^2 + 2 = x^2 - 2x + 1 + 2 = x^2 - 2x + 3$
	Jadi,  $(g \circ f)(x) = x^2 - 2x + 3$ .

4. Domain g ∘ f
	Domain  $g \circ f$  adalah irisan domain  f  dan domain  $g(f(x)$) .
	Karena  $f(x)$  dan  $g(x$)$  keduanya didefinisikan untuk semua  $x \in \mathbb{R}$ , maka domain  $g \circ f$  adalah  $\mathbb{R}$ .
	Sehingga :
	$D (g∘f) = R(f)∩D(g) = R∩R = R$


#### (b) Hitunglah  $(f \circ g)(x)$

1.	Definisi komposisi fungsi: $(f \circ g)(x) = f(g(x))$

2.	Langkah pertama: Substitusi  $g(x) = x^2 + 2$  ke dalam  $f(x)$ :
	$f(g(x)) = f(x^2 + 2) = (x^2 + 2) - 1 = x^2 + 1$
	Jadi,  $(f \circ g)(x) = x^2 + 1$ .

3. Domain  f \circ g :
	Domain  g(x)  adalah  $\{x \mid x \geq -2 \}$  karena  $g(x) = x^2 + 2$  hanya terdefinisi untuk  $x \geq -2$ .
	Domain  f(x)  adalah  $\mathbb{R}$ , sehingga domain  $f \circ g$  adalah  $[2, \infty)$.


### Contoh 2.1.10

Diketahui fungsi  $f(x) = 2x + 5$  dan  $g(x) = \sqrt{x - 1}$ , kita diminta menentukan:

#### (a)  $(g \circ f)(x)$

1.	Langkah pertama: Komposisi  $(g \circ f)(x)$ : 
	$g(f(x)) = g(2x + 5) = \sqrt{(2x + 5) - 1} = \sqrt{2x + 4}$
	Jadi,  $(g \circ f)(x) = \sqrt{2x + 4}$ .

2.	Langkah kedua: Domain  $g \circ f$  adalah irisan domain  $f$ dan  $g(f(x))$ .
	Agar  $\sqrt{2x + 4}$  terdefinisi, harus  $2x + 4 \geq 0$ , atau  $x \geq -2$ .
	Jadi, domain  $g \circ f$  adalah  $[ -2, \infty )$ .


#### (b)   $(f \circ g)(x)$

1.	Langkah pertama: Komposisi  $(f \circ g)(x)$ :
	$f(g(x)) = f(\sqrt{x - 1}) = 2\sqrt{x - 1} + 5$
	Jadi,  $(f \circ g)(x) = 2\sqrt{x - 1} + 5$ .

2.	Langkah kedua: Domain  $f \circ g$  adalah irisan domain  $g$  dan  $f(g(x))$ .
	Agar  $\sqrt{x - 1}$  terdefinisi, harus  $x \geq 1$ .
	Jadi, domain  $f \circ g$  adalah  $[1, \infty)$ .

### Kesimpulan

Pada kedua contoh ini, untuk menemukan komposisi fungsi  $(g \circ f)(x)$  dan  $(f \circ g)(x)$ , pertama-tama kita perlu melakukan substitusi fungsi sesuai urutan komposisi, lalu menyederhanakan hasilnya. Domain dari komposisi fungsi dihitung dengan memperhatikan domain masing-masing fungsi serta bagaimana operasi pada fungsi tersebut mempengaruhi hasil akhirnya.