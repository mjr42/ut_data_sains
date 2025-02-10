Apakah yang dimaksud dengan scalable, availability dan stability dalam membangun jaringan?

Berikan penjelasan dan contohnya.

---

Selamat Pagi,
Berikut adalah pemaparan saya mengenai topik diskusi kita kali ini:

**Scaleable**

Berdasarkan 4 Fundamental Tujuan Utama dalam Membangun sebuah Jaringan yang dibuat oleh CISCO. Scale, Scaleable atau Scaleability adalah kemampuan sebuah sistem jaringan untuk mengubah atau menambah ukuran sistem tersebut sesuai dengan kebutuhan yang diharapkan (“CCNA exploration course booklet. LAN switching and wireless version 4.0”, 2010, hal. 199). Berdasarkan pengertian tersebut, Sistem jaringan komunikasi yang akan dibangun memiliki kemampuan untuk diperbesar, ditambah atau dikembangkan sesuai dengan kebutuhan dan ketersediaan jaringan komunikasi yang terhubung dengan sistem tersebut, sehingga kemampuan (kapasitas, jangkauan, dan kecepatannya) dapat ditingkatkan tanpa perlu membongkar atau membuat sistem jaringan komunikasi dari awal lagi (Arifin, 2023). 

Scaleable berorientasi ke masa depan, yaitu dengan mengantisipasi kebutuhan jaringan dimasa depan, termasuk di dalamnya kebutuhan untuk meningkatkan traffic, penambahan layanan baru, atau ekspansi ke wilayah baru dengan coverage yang lebih luas lagi (Brightwood, 2024)

Contoh jaringan yang memiliki kemampuan Scaleable / Scaleability :

AWS Auto Scalling adalah salah satu layanan dari Amazon Web Service yang memungkinkan AWS user untuk menambah, mengubah, dan menyesuaikan resource untuk memopertahankan kinerja jaringan yang stabil secara otomatis (https://aws.amazon.com/id/autoscaling/?nc1=h_ls)


**Availability**

Konsep availability mengacu kepada jaminan ketersediaan jaringan dan layanan komunikasi ketika hendak digunakan, dengan meminimalisir atau mengurangi waktu disaat sistem tidak bisa digunakan atau tidak bisa di akses sehingga aktifitas mengirim dan menerima data/informasi tidak terganggu (Whitman & Mattord, 2017).

Selain itu Sayyad et al (2021) juga berpendapat bahwa dengan availability, aksesbilitas dan ketersediaan dari jaringan, service/layanan , dan data dapat digunakan setiap saat terutama ketika user yang memiliki akses kepada data / informasi yang terdapat dalam jaringan membutuhkannya.

Dengan semakin banyaknya bisnis yang bergantung kepada jaringan informasi, Availability jaringan menjadi sangat penting dalam kegiatan berbisnis. Redundancy menjadi salah satu solusi untuk meningkatkan availability dari suatu jaringan komunikasi.

Redundancy dapat meningkatkan Availability dari suatu sistem jaringan dengan melindungi sistem jaringan dari Single Point Failur seperti terkendalanya kabel atau switch dalam jaringan. Dengan redundancy, sistem jaringan memiliki backup sistem cadangan yang sama persis sehingga ketika sistem utama mengalami gangguan, sistem cadangan dapat digunakan saat itu juga. (“CCNA exploration course booklet. LAN switching and wireless version 4.0”, 2010, hal. 118).

Contoh jaringan yang memiliki kemampuan Availability :

salah satu penyedia layanan transportasi online menggunakan Data Center tier-4 yang memiliki kemampuan Zero Single Point failure, Redundansi 2N+1, serta desain yang memiliki tingkat toleransi yang sangat tinggi terhadap kesalahan sehingga memiliki 99.99% waktu uptime dengan downtime kurang dari 0,5 jam per tahun sehingga layanan transportasi online dapat terus diakses kapanpun tanpa gangguan.


**Stability**

Stability atau stabilitas dalam jaringan biasanya dikaitkan dengan upaya untuk menghindari adanya queue/delay dalam proses pertukaran informasi dalam suatu jaringan. Stabilitas juga bisa diartikan sebagai jaminan bahwa transmission rates / kecepatan transmisi data dapat terus berjalan dalam kecepatan maksimalnya (De Veciana et al., 2001, hal. 2). 

Berikut adalah penjelasan Queue, Delay, dan Loss dalam jaringan berdasarkan Koo et al., (2004, Hal. 321)

Queue dalam jaringan dapat dideskripsikan sebagai antrian paket data pada sistem jaringan yang mengakibatkan paket data harus menunggu paket data lainnya untuk ditransmisikan. Dengan adanya Queue ini, user harus menunggu terlebih dahulu hingga paket data siap dikirimkan.

Delay dapat diartikan sebagai lamanya waktu paket data berpindah dari suatu sistem ke sistem lainnya. Delay biasanya dipengaruhi dengan kualitas jaringan dan jarak fisik antara user dan server.

Loss dapat diartikan dengan hilangnya paket data yang di request oleh client. kehilangan data ini bisa terjadi saat queue dalam jaringan mengalami beban yang berat (overload) 

Contoh jaringan yang memiliki stabilitas tinggi

Suatu jaringan yang menggunakan Cloudflare CDN dan HTTP/3 Protocol memiliki kecepatan akses yang tinggi dan stabil dikarenakan dengan Cloudflare CDN, paket data dikirim melalui server yang memiliki lokasi fisik yang dekat dengan client serta protokol HTTP/3 memungkinkan untuk pengiriman paket data yang lebih besar bahkan saat high-traffict sekalipun sehingga akses mengirim dan menerima paket data dapat berjalan dengan stabil.



Sumber:

Arifin Z, Nugroho K. 2023. _Dasar Infrastruktur Teknologi Informasi_. Tanggerang Selatan: Penerbit Universitas Terbuka.

Brightwood N. 2024. Cisco Network Design 101: An Introduction for Beginners. [diunduh 2024 Okt 31]. Tersedia pada: https://netseccloud.com/cisco-network-design-101-an-introduction-for-beginners#:~:text=Scalability%20involves%20anticipating%20future%20network%20needs%2C%20including,accommodate%20new%20data%20types%2C%20or%20increase%20throughput.

Cisco Networking Academy Program, editor. 2010. _CCNA exploration course booklet. LAN switching and wireless version 4.0_. Indianapolis, IN: Cisco Press. (Cisco Networking Academy series).

De Veciana G, Tae-Jin Lee, Konstantopoulos T. 2001. Stability and performance analysis of networks supporting elastic services. _IEEE/ACM Trans. Networking_. 9(1):2–14.doi:10.1109/90.909020.

Koo J, Ahn S, Chung J. 2004. A Comparative Study of Queue, Delay, and Loss Characteristics of AQM Schemes in QoS-enabled Networks. _Computing and Informatics,_. 22:317–335.

Whitman ME, Mattord HJ. 2017. _Principles of information security_. Cengage Learning. Ed ke-Citation Key: whitman2017principles tex.lccn: 2017930059.