---
tags:
  - dasar_infrastruktur_teknologi_informasi
---

Praktik merancang dan membangun jaringan menggunakan tool simulator Packet Tracert. Kegiatan praktik ini diawali dengan tahapan perencanaan, perancangan, implementasi dengan cara mengkonfigurasikan perangkat perangkat yang digunakan 

## [[05. Skenario 1]]

Pada skenario 1, mengkonfigurasi perangkat perangkat jaringan berdasarkan topologi dibawah ini

![[Screenshot 2024-09-30 at 20.14.58.png]]

#### Prangkat yang digunakan antara lain:

- 2 unit Switch 2960
- 2 unit router 1941
- 6 unit PC
- Kabel UTP (Straight Through dan Cross Over)

#### Pengalamatan IP yang terpasang direncanakan seperti yang terlihat pada tabel berikut:

![[Screenshot 2024-09-30 at 20.16.20.png]]

#### Tahapan Tahapannya

1. Buka aplikasi packet tracert kemudian susun perangkat perangkat jaringan seperti gambar di atas
   
2. Lakukan pemasangan alamat IP pada perangkat perangkat rtersebut sesuai dengan daftar alamat IP yang terdapat pada tabel diatas.
   
   Untuk memasang alamap pada perangkat PC contohnya sebagai berikut:
   
   - Masuk ke menu IP Configuration dan isikan parameter IP address, subnet mask dan default gateway seperti berikut ini
     
    ![[Screenshot 2024-09-30 at 20.18.28.png]]

- Lakukan verifikasi terhadap konfigurasi alamat IP pada PC0 dengan masuk ke Command Prompt dan ketikan ipconfig sehingga muncul tampilan berikut
	![[Screenshot 2024-09-30 at 20.19.34.png]]

- Perhatikan amalat yang terpasang, pastikan kesesuaiannya dengan alamat IP yang sudah direncanakan
- Dengan cara yang sama pada langkah sebelumnya. Pasangkan alamat IP dan parameter lainnya yang diperlukan pada PC 6 sampai 6 sesuai tabel diatas

3. Lakukan konfigurasi terhadap Router 1 seperti berikut:
   
- Pilih dan klik Router1
  
- Melalui tab CLUI, masuk ke console Router 1, seperti gambar berikut
	  ![[Screenshot 2024-09-30 at 20.21.41.png]]

- Jawab "No" pada pertanyaan " COntinue with coinfiguration dialog?". Kemudian tekan ENTER sehingga muncul promp Router>
  
- Beri nama perangkan router dengan nama R1 seperti bambar berikut
	  ![[Screenshot 2024-09-30 at 20.22.58.png]]

- Lanjutkan dengan mengkonfigurasi alamat IP beserta subnet mask dan aktifkan interface G0/0 dan G0/1 di Router1 seperti gambar berikut
	  ![[Screenshot 2024-09-30 at 20.23.41.png]]

- Verifikasi hasil konfigurasi alamat yang didefinisikan pada Router1 menggunakan perintah # show run
	  ![[Screenshot 2024-09-30 at 20.24.27.png]]

4. Lakukan konfigurasi terhadap Router2

- Pilih dan klik Router2
  
- Melalui tab CLI, masuk ke konsole Router2, sehingga muncul tampilan seperti pada gambar berikut:
	![[Screenshot 2024-09-30 at 20.26.13.png]]

- Jawab "no" pada pertanyaan "Continue with configuration dialog?" kemudian tekan ENTER sehingga muncul promp Router>
  
- Beri nama perangkat router dengan nama R2, dilakukan dengan cara berikut:
	![[Screenshot 2024-09-30 at 20.28.55.png]]

- Lanjutkan dengan mengkonfigurasi alamat IP beserta subnet mask dan aktifkan interface G0/0 dan G0/1 di Router2 seperti gambar berikut:
	![[Screenshot 2024-09-30 at 20.30.33.png]]

- Verifikasi hasil konfigurasi alamat yang didefinisikan pada router 2 menggunakan perintah # show run
	  ![[Screenshot 2024-09-30 at 20.31.11.png]]

 
 5. Untuk menghubungkan dua jaringan yang berbeda alamat network diantara dua atau beberapa router maka diperlukan routing protokol. Maka pada langkah berikutnya kita akan mengkonfigurasi routing protokol pada kedua router. Berikut caranya:
	![[Screenshot 2024-09-30 at 20.32.26.png]]

6. Hasil konfigurasi routing protokol RIP pada kedua router dengan menggunakan keywork "show ip route"
	![[Screenshot 2024-09-30 at 20.33.02.png]]
	 Dari tabel routing nempak alamat network 192.168.3.0 yang dapat dijangkau dengan jarak 1 hop melalui interface G0/0 begitu pula pada tabel routing yang terdapat di R2, tampak bahwa alamat jaringan 192.168.1.0 dapat dijangkauy dari r2 melalui interface G0/0 dengan jarak 1 hop


7.  Simpan hasil konfiguirasi ke R1 dan R2 ke NVRAM dengan menggunakan keyword copy run start di masing-masing router agar konfigurasi yang sudah dilakukan tidak hilang ketika router dimatikan
	   ![[Screenshot 2024-09-30 at 20.35.32.png]]

8. Untuk melihat hasil proses penyimpanan, dapat dilakukan dengan menggunakan keyword show start, pandingkan isinya dengan isi konfigurasi yang terdapat di RAM yang bisa kita lihat dengan keyword sh run.
   
9. Setelah selesai mengkonfigurasi jaringan, sehingga PC yang terdapat di jaringan 192.168.1.0 dapat berkomunikasi dengan PC yang berada di jaringan 192.168.3.0. Hal tersebut dapat dibuktikan dengan menggunakan tool ping melalui Command Prompt PC1. ketikan ping 192.168.3.12 untuk memastikan konektivitas sudah terbentuk antara PC1 ke PC4
	   ![[Screenshot 2024-09-30 at 20.38.03.png]]

10. Untuk mengetahui jalur yang dilalui dapat diverifikasi dengan menggunakan perintah tracert 192.168.3.2

11. Terakhir jangan lupa menyimpan hasil konfigurasi dengan menggunakan keyword copy run start di kedua router.
	![[Screenshot 2024-09-30 at 20.39.26.png]]

Pada gambar terlihat untuk menjangkau 192.168.3.12 dari PC1 dapat melalui 192.168.1.1 -> 192.168.2.2 -> dan akhirnya sampai di 192.168.2.13


## [[06. Skenario 2]]

Pada skenario ini akan dikonfigurasikan perangkat. perangkat jaringan berdasarkan topologi VLAN (Virtual Local area Network). VLAn merupakan jaringan LAN yang dapat melakukan sergemtasi jaringan berbasis player pada layer 2 secara logik sehingga pemisahan jaringan tidak berdasarkan lokasi fisik.

Praktik ini disimulasikan untuk 3 lantai dalam satu gedung yang terdiri dari 3 departemen yakni: marketing, education, dan engineering. Antar departemen memiliki alamat jaringan yang berbeda

![[Screenshot 2024-09-30 at 21.23.31.png]]

#### Prangkat yang digunakan antara lain:

- 1 unit Switch L3 3560
- 8 unit PC
- Kabel UTP (Straight Through dan Cross Over)


#### Pengalamatan IP yang terpasang direncanakan seperti yang terlihat pada tabel berikut:

![[Screenshot 2024-09-30 at 21.24.07.png]]

![[Screenshot 2024-09-30 at 21.24.16.png]]

![[Screenshot 2024-09-30 at 21.24.26.png]]

#### Ikuti tahapan-tahapan berikut :

1. Buka aplikasi packet tracert kemudian susun perangkat-perangkat jaringan seperti pada Gambar 3.22 dan berdasarkan Tabel 3.2, 3.3 serta 3.4
   
2. Lakukan pemasangan alamat IP pada perangkat-perangkat tersebut sesuai dengan daftar alamat IP yang terdapat pada Tabel 3.4. Untuk pemasangan alamat pada perangkat PC contohnya sebagai berikut:
   
- Masuk ke menu IP Configuration,  isikan parameter-parameter IP address, subnet mask dan default gateway seperti pada Gambar 3.23 berikut:
	![[Screenshot 2024-09-30 at 21.25.30.png]]

- Lakukan verifikasi terhadap konfigurasi alamat IP pada PC0 dengan masuk ke Command Prompt dan ketikan “ipconfig”
	![[Screenshot 2024-09-30 at 21.25.51.png]]

- Perhatikan alamat yang terpasang, pastikan sesuai dengan yang direncanakan.
  
- Dengan cara yang sama pada langkah sebelumnya, pasangkan alamat IP dan parameter lainnya yang diperlukan pada PC 2 s/d 8 sesuai dengan Tabel 3.4

3. Berikutnya kita akan membuat database VLAN di Switch MLS1, pembuatan database VLAN dilakukan pada suatu switch yang berstatus sebagai VTP server sedangkan switch lainnya berstatus sebagai VTP client. Database VLAN yang dibuat di VTP server secara periodik akan didistribusikan ke switch lainnya yang berstatus sebagai VTP Client dan berada dalam 1 domain dengan VTP server
   
   Cara mendefinisikan status VTP server dan database VLAN pada switch MLS1 dapat dilihat pada Gambar 3.24
	![[Screenshot 2024-09-30 at 21.26.54.png]]
	Pada konfigurasi yang terdapat pada Gambar 3.24 mendefinisikan status VTP dari switch MLS1 adalah VTP server sehingga MLS1 secara periodik akan menginformasikan VTP message (salah satunya informasi database VLAN) ke VTP client secara periodik. Selain status VTP, pada konfigurasi tersebut mendefinisikan juga nama domain bernama UniversitasTerbuka. Nama domain bersifat case-sensitif sehingga penggunaan huruf perlu diperhatikan pada saat mendefinisikan nama domain di switch yang berstatus VTP Client

4. Lakukan verifikasi daftar vlan yang terbentuk dengan menggunakan keyword show vlan
	![[Screenshot 2024-09-30 at 21.29.35.png]]
	Perhatikan daftar vlan yang terdapat di Gambar 3.25, nampak terdapat 3 VLAN yang sebelumnya telah didefinisikan yakni VLAN Marketing, Education dan Engineering akan tetapi saat ini belum memiliki anggota VLAN. Semua port yang terdapat pada MLS1 secara default merupakan anggota dari VLAN 1

5. Tahap berikutnya, mendefinisikan port trunking pada MLS1, dengan cara berikut:
	![[Screenshot 2024-09-30 at 21.30.35.png]]
	Pada konfigurasi yang terdapat pada Gambar 3.26 port trunking didefinisikan pada interface G0/1 dengan menggunakan protokol 802.1Q. Protokol ini didefinisikan pada jalur trunking agar dapat melewatkan trafik yang berasal dari beberapa VLAN berbeda pada jalur yang sama. Protokol 802.1Q merupakan protokol open standard

6. Agar vlan database yang sudah didefinisikan di MLS1 dapat didistribusikan ke switch lainnya, maka kita perlu mendefinisikan port trunking pada SW1 dan juga memberi domain yang sama dengan MLS1 serta menetapkan status sebagai VTP client, dengan cara berikut:
	![[Screenshot 2024-09-30 at 21.31.11.png]]

7. Lakukan perintah show vlan untuk melakukan verifikasi terhadap distribusi database vlan yang dilakukan oleh MLS1 ke SW1 sudah diterima melewati jalur trunking
	![[Screenshot 2024-09-30 at 21.31.34.png]]

8. Lakukan hal yang sama terhadap SW2 dan SW3 dengan cara yang sama seperti yang dilakukan pada SW1 (konfigurasi domain, vtp client dan port trunking). Sehingga SW2 dan SW3 juga memiliki daftar vlan yang sama seperti yang dimiliki SW1 dan MLS1.

9. Tahap berikutnya adalah menetapkan keanggotaan VLAN berbasis port pada masing-masing switch (SW1, SW2 dan SW3). Berikut konfigurasi yang dilakukan untuk menetapkan keanggotaan VLAN pada SW1 dengan ketentuan sebagai berikut:
	1. Anggota VLAN 2 terdiri dari port F0/1 sd F0/10
	2. Anggota VLAN 3 terdiri dari port F0/11 sd F0/20
	3. Anggota VLAN 4 terdiri dari port F0/21 sd F0/24
	![[Screenshot 2024-09-30 at 21.32.32.png]]

10. Lakukan verifikasi terhadap konfigurasi keanggotaan VLAN pada SW1 dengan menggunakan keyword sh vlan, seperti pada Gambar 3.30
	![[Screenshot 2024-09-30 at 21.33.30.png]]
	Lakukan verifikasi terhadap konfigurasi keanggotaan VLAN pada SW1 dengan menggunakan keyword sh vlan, seperti pada Gambar 3.30

11. Lanjutkan konfigurasi untuk menetapkan keanggotaan Vlan pada SW2 dan SW3. Lakukan dengan konfigurasi yang sama seperti yang dilakukan pada SW1. Sehingga Vlan yang terdapat pada SW2 dan SW3 memiliki anggota berupa port-port sebagai berikut:
	1. Anggota VLAN 2 terdiri dari port F0/1 sd F0/10
	2. Anggota VLAN 3 terdiri dari port F0/11 sd F0/20
	3. Anggota VLAN 4 terdiri dari port F0/21 sd F0/24

12. Setelah selesai menetapkan keanggotaan Vlan pada SW2 dan SW3, PC yang terhubung dalam Vlan yang sama sudah bisa saling berkomunikasi. Misalkan PC0 dengan PC2
	![[Screenshot 2024-09-30 at 21.34.39.png]]

13. Anggota Vlan yang berbeda belum bisa saling terhubung secara logik walaupun kedua host tersebut terhubung secara fisik pada switch yang sama. Misalkan antara PC0 dengan PC1
	![[Screenshot 2024-09-30 at 21.35.02.png]]
	Hal tersebut dikarenakan PC0 dan PC1 berada dalam vlan berbeda yang secara logic terpisah dan tidak saling terhubung

14. Anggota vlan yang berbeda dapat saling terhubung/berkomunikasi dengan melalui router atau switch layer 3. Pada topologi yang sedang kita gunakan dapat memanfaatkan kemampuan Switch MLS1 untuk menghubungkan antara Vlan dengan mengaktifkan kemampuan routing dan mengaktivasi dan memberi alamat pada interface virtual VLAN 2, 3 dan 4, seperti pada konfigurasi di Gambar 3.34 
	![[Screenshot 2024-09-30 at 21.35.45.png]]

15. Lakukan verifikasi hasil aktivasi routing dengan melihat isi tabel routing menggunakan keyword show ip route, seperti pada Gambar 3.34 
	![[Screenshot 2024-09-30 at 21.36.13.png]]

16. Aktivasi routing dan interface Vlan pada MLS1 menyebabkan seluruh anggota Vlan yang berbeda sudah dapat saling terhubung. Lakukan verifikasi menggunakan tool ping untuk menguji konektivitas antara PC0 yang merupakan anggota Vlan Marketing dapat berkomunikasi dengan PC1 yang merupakan anggota Vlan Education, seperti pada Gambar 3.35
	![[Screenshot 2024-09-30 at 21.36.41.png]]

17. Anda telah berhasil membangun jaringan Vlan, simpan hasil konfigurasi dengan menggunakan keyword copy run start pada setiap perangkat MLS1, SW1, SW2 dan SW3, agar konfigurasi tidak hilang ketika perangkat-perangkat tersebut dimatikan


