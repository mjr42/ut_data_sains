---
tags:
  - sains_data
  - materi_18_PSD
---
Mata manusia sangat mudah dalam mengenali dan membedakan objek di dunia nyata. Manusia juga dapat dengan mudah membaca dan memahami arti dari suatu teks dalam kalimat. Hal ini dikarenakan manusia memiliki sensor dan perangkat pengolah data yang lengkap, seperti mata dan otak.

Mata berfungsi untuk mengenali objek, kemudian informasi mengenai objek ini dikirimkan ke otak untuk diolah dengan sangat cepat. Namun, akan sangat berbeda dengan komputer, sesuatu yang terlihat sangat sederhana dilakukan oleh manusia akan menjadi sangat sulit dilakukan oleh komputer.

Namun, komputer memiliki kemampuan mengolah proses perhi-tungan matematis yang kompleks dengan sangat cepat, sementara manusia tidak. Hal ini menjadi sangat menarik, mengingat kemampuan manusia dan komputer ternyata saling berbanding terbalik namun juga dapat saling menggantikan. Di masa depan akan semakin sulit membedakan apakah suatu pekerjaan dikerjakan oleh manusia atau oleh komputer.

Salah satu metode yang diklaim meniru cara kerja otak manusia dalam mengenali sesuatu adalah algoritme jaringan saraf tiruan (JST) atau dike-nal juga dengan istilah artificial neural networks (ANN). Otak manusia bekerja dengan memanfaatkan kemampuan neuron menerima sinyal dari sensor, mengolahnya, dan mengirimkan kembali hasilnya. Neuron satu dengan yang lain terhubung oleh sinapsis, dan jumlahnya dapat mencapai lebih dari miliaran. Namun, metode ini tidaklah sepenuhnya meniru cara kerja otak manusia, dikarenakan otak memiliki peta yang sangat kom-pleks, sementara komputer tidak. Otak manusia senantiasa mengalami perubahan seiring dengan bertambahnya usia dan pengetahuan. Semakin sering digunakan, maka jumlah neuron dan sinapsis akan terus bertambah.

Sebaliknya, semakin jarang digunakan, maka jumlah neuron dan sinapsis akan terus berkurang. Berbeda dengan komputer, di mana jumlah neuron dan node hanya bisa ditentukan oleh peneliti.

Pada algoritme ANN, selalu dimulai dari variabel masukan pada layer input, kemudian layer ini akan dihubungkan dengan "hidden layer", dan terakhir adalah layer output di mana proses perhitungan dapat dilakukan secara berulang untuk mendapatkan model yang terbaik. Algoritme ANN bekerja mirip dengan supervised learning, di mana data latih harus terlebih dahulu ditentukan oleh peneliti. Data latih ini kemudian digunakan untuk melatih komputer dalam mengenali data. Lalu, berdasarkan data latih tersebut komputer kemudian akan mampu mengenali dan membedakan suatu objek. Aplikasinya seperti mengenali gambar, teks, suara, atau ber-bagai jenis data lainnya.

Akurasi yang dihasilkan oleh algoritme ANN akan sangat bergantung pada kualitas dan kuantitas data yang dimiliki oleh peneliti. Kita mengenal istilah Garbage In Garbage Out, yaitu suatu istilah yang menggambarkan bahwa jika input data latih yang digunakan memiliki kualitas yang buruk, maka akan menghasilkan luaran (output) yang buruk pula. Sebaliknya, jika input data latih yang digunakan memiliki kualitas yang baik maka akan menghasilkan luaran (output) yang baik pula. Kualitas data input dapat diperbaiki dengan cara pemilihan fitur yang tepat, mengubah parameter seperti learning rate, dan regularization.

Learning rate adalah salah satu parameter yang digunakan dalam proses pelatihan untuk melakukan koreksi nilai bobot. Rentang nilai lear-ning rate biasanya antara 0 hingga 1, di mana semakin besar nilainya akan semakin cepat proses komputasi. Sebaliknya, semakin kecil nilai learning rate maka akan semakin lambat proses komputasinya. Ketelitian algoritme ANN dalam belajar juga akan bergantung kepada nilai learning rate yang diberikan. Semakin besar nilai learning rate maka akan semakin kecil ketelitiannya, sebaliknya semakin kecil nilai learning rate maka akan semakin tinggi tingkat ketelitiannya.

## [[01. Multi Layer Perceptron]]

Multi-layer perceptron adalah satu bentuk algoritme ANN yang paling mudah dipahami dan diimplementasikan. Seperti pada Gambar 18.1, mem-visualisasikan arsitektur MLP yang terdiri atas tiga layer (input, hidden, dan output). Pada input layer terdapat tiga neuron (node), sementara pada hidden layer terdapat lima neuron, dan output layer terdapat tujuh layer. Hidden layer sangat penting keberadannya karena berfungsi untuk mengatur dari ML.P, tanpa hidden layer maka MLP tidak mampu melakukan proses pembelajaran. Terlalu sedikit jumlah data latih, dan terlalu banyak jumlah iterasi akan membuat MLP terjebak pada kondisi overfitting.

![[Pasted image 20241124144556.png]]

Pada MLP, perhitungan dan perbaikan bobot nilai menggunakan algoritme back propagation, yaitu perhitungan dan penyesuaian bobot secara iterative, maju-mundur secara berulang-ulang hingga mencapai nilai bobot yang paling optimal. MLP termasuk ke dalam analisis statistik bebas distribusi, artinya tidak menghiraukan distribusi data atau non-parametris.

MLP dapat digunakan untuk analisis non-linear seperti fungsi matematis yang kompleks untuk mengubah nilai masukan (input) seperti citra satelit untuk menghasilkan nilai luaran berupa kelas tutupan dan penggunaan lahan.





## [[02. Radial Basis Function Neural Network (RBFNN)]]

Radial basis function (RBF) termasuk ke dalam metode supervised learning, di mana pada hidden layer memanfaatkan metode radial basis function seperti fungsi Gaussian (Gambar 182). Jika pada MLP berlaku proses maju-mundur (back propagation), maka pada RBFNN hanya berlaku proses maju saja (feed forward). Proses perhitungan dan penyesuaian nilai bobot dilakukan pada hidden layer dengan menggunakan fungsi transformasi statistik seperti Gaussian.

![[Pasted image 20241124144717.png]]

Hidden layer bertugas untuk mengukur jarak antara data input dengan nilai pusat dari RBF: Nilai RBF akan mencapai puncak atau nilai tertinggi Ketika jarak antara pusat dengan data input bernilai nol dan berkurang secara bertahap, dengan semakin jauhnya jarak. Output akan bernilai 1 jika data input pada pusat fungsi, tetapi akan terus menurun seiring dengan semakin besarnya jarak antara input dan pusat, jarak terjauh berarti memi-liki nilai 0.

Seperti halnya MLP, RBENN juga dapat digunakan untuk analisis kasus-kasus non-linear yang kompleks. RBFNN membutuhkan waktu komputasi yang lebih lama dibandingkan dengan MLP meskipun menggunakan nilai learning rate dan arsitektur jaringan yang sama. Namun, algoritme RBFNN dapat memberikan hasil dengan akurasi yang lebih tinggi dibandingkan algoritme MLP (Ramdani, Furqon, Setiawan, & Rusydi (2020)).



## [[Semester 1/Pengantar Sains Data STDA4101/Modul 18/03. Kelebihan dan Kekurangan]]

Algoritme JST bukanlah sebuah ide baru, hal ini sudah lama muncul dan dikenalkan oleh peneliti. Saat ini topik mengenai algoritme JST kembali ramai diperbincangkan oleh khalayak karena varian dan volume data serta permasalahan modern yang muncul semakin kompleks.

Ketersediaan teknologi dan perkembangan kemampuan komputer juga telah menyebabkan algoritme JST menjadi semakin populer. Dahulu, amat sulit membuat dan mengimplementasikan algoritme IST karena membutuhkan waktu komputasi yang tidak sebentar serta sumber daya komputer yang mumpuni.

Kini, peneliti mampu memanfaatkan algoritme JST, bahkan dengan spesifikasi komputer yang rendah. Bahkan, proses komputasi juga dapat berjalan di dalam jaringan dengan bantuan layanan berbasis cloud seperti Jupyter Notebook, Visual Studio Code (VS Code), nteract, Jupyterlite, dan Google Colaboratory atau lebih dikenal dengan istilah Google Colab.

Namun, dibalik semua kelebihan tersebut terdapat juga banyak kele-mahan dari algoritme JST di antaranya adalah membutuhkan banyak sekali data latih yang belum tentu tersedia dan jikapun tersedia belum tentu berkualitas. Algoritme IST juga dikenal membutuhkan waktu komputasi yang lama (computationally expensive) karena proses pelatihan dapat ber-jam-jam hingga berhari-hari tergantung pada ukuran, kedalaman, dan kompleksitas dari arsitektur jaringan yang digunakan.

Tidak terdapat aturan baku yang mengikat mengenai arsitektur jaringan (misal, penentuan jumlah hidden layer dan node) sehingga arsitektur yang sesuai diperoleh melalui proses trial and error. Algoritme JST juga merupakan model black-box, membutuhkan optimasi tambahan dan penentuan para - meter yang banyak seperti learning rate, momentum factor, sigmoid constant, dan jumlah iterasi (epoch). Algoritme juga mudah terjebak pada kondisi overfitting jika data latih yang digunakan tidak cukup banyak atau tidak sesuai.



