# UAS Citra Digital
## Klasifikasi Pengenalan Citra Batik dari Provinsi Jawa Barat

## Anggota Kelompok
Nama    : Endang Prayoga Hidayatulloh <br/>
NIM     : 2006189 <br/>
<br/>
Nama    : Vini Oktapiani <br/> 
NIM     : 2006059 <br/> 

## Referensi Jurnal Penelitian
Projek ini adalah hasil dari pengembangan yang merujuk pada jurnal yang berjudul "KLASIFIKASI CITRA MOTIF BATIK BANYUWANGI MENGGUNAKAN CONVOLUTIONAL NEURAL NETWORK". Berikut adalah deskripsi dari jurnal yang dirujuk :
* Nama Jurnal     : Jurnal Teknoinfo
* Judul           : KLASIFIKASI CITRA MOTIF BATIK BANYUWANGI MENGGUNAKAN CONVOLUTIONAL NEURAL NETWORK
* Author          : Lutfi Hakim, Hadi Rizaldi Rahmanto, Sepyan Purnama Kristanto, Dianni Yusuf
* DOI             : [https://doi.org/10.33365/jti.v17i1.2342](https://doi.org/10.33365/jti.v17i1.2342)
### Hasil analisis jurnal
Sistem pada jurnal tesebut dapat mengenali 7 macam motif batik Banyuwangi yaitu diantaranya Gajah Oling, Gedegan, Kopi Pecah, Moto Pitik, Beras Kutah, Paras Gempal dan Sisikan. Sistem ini menggunakan metode Convolutional Neural Network (CNN) dan untuk evaluasi digunakan metode confusion matrix untuk mengukur nilai akurasi. Penelitian menggunakan model CNN dengan arsitektur yang diberi nama MyCustomModel. Data yang digunakan pada penelitian sebanyak 120 citra untuk masing masing motif batik dan hasil prediksi mendapatkan nilai akurasi sebesar 63%.

## Hasil dan Pembahasan
Dengan menggunakan metode kecerdasan buatan yang sama yaitu Convolutional Neural Network kami bisa mengembangkan suatu aplikasi kecerdasan buatan yang sama, tetapi dengan dataset yang berbeda yakni dengan menggunakan dataset batik jabar yang diperoleh dari kaggle. data yang terdapat dalam dataset tersebut terdiri dari data kelas batik jawa barat yang berbeda, diantaranya Batik Cendrawasih, Dayak, Ikat Celup, Insang, Kawung, Megamendung, Parang, Poleng, Sekar Jagad dan Tambal. Dataset tesebut keseluruhan berjumlah 200 data foto batik jawa barat untuk data training. <br/>
Link Dataset    : [Batik Jawa Barat](https://www.kaggle.com/datasets/panduagas/batik-jawa-barat) <br/>
Lalu untuk tahap pelatihan kami membagi dataset menjadi 2 kelas, yaitu data Training dan Testing, setiap kelas mempunyai 10 kelas yakni kelas-kelas dari pembagian batik Jawa Barat. Lalu setelah itu dilakukannya pemodelan, pemodelan dilakukan dengan jumlah epoch 150 dan dengan optimasi adam. Hasil dari pemodelan didapatkan akurasi terbaik yaitu diangka 75%.

## Kesimpulan
Dari hasil pengembangan yang dilakukan yaitu merubah struktur dataset menjadi batik Jawa Barat kemudian di ubahnya struktur jaringan pada pemodelan. Dari hasil tersebut kami mendapatkan akurasi sebesar 75%, yakni sedikit lebih besar dibandingkan dengan penelitian yang telah kami rujuk yaitu dengan akurasi 63%. <br/>
Tidak hanya itu, selesai UAS ini mungkin kami akan tetap berusaha untuk menemukan hasil yang lebih baik lagi supaya projek ini bisa lebih bermanfaat dari yang kami bayangkan.
