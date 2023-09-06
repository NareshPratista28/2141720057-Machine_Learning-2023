## Pertemuan 1: Introduction to Machine Learning

### Relasi antara AI dan ML

Bedanya apah?

>> Artificial Intellegence, Sebuah teknik yang dapat mengaktifkan mesin untuk mengikuti perilaku manusia (vision, gesture, sense stuff). 

>> Machine Learning, Adalah satu model yang digunakan untuk melatih sebuah mesin agar dia dapat menyelesaikan suatu permasalahan yang spesifik. Butuh data untuk melatih prediksi yang akurasi. (ratio)

>> Deep Learning, model pembelajaran mesin yang lebih dalam sehingga menggunakan data yang jauh lebih banyak. (ratio square(kuadrat)) 

<img src = g1.png>

### Definisi Formal
"Computational methods using experience to improve performance or to make accurate predictions" - Mohri, et al., 2012

"Machine learning is the design and study of software artifacts that use past experience to inform future decisions; machine learning is the study of programs that learn from data" - Hackeling, 2017

"A program can be said to learn from experence 'E' with respect to some class of tasks 'T' and performance measure 'P', if its performance at tasks in 'T' as measured by 'P', improves with experience 'E''."  - Tom Mitchel

TOM MITCHELL'S ML CONCEPT

>> E - (Process) - T - (measure) -  P - (improve) - T

ML in real world 

1.Mail -> Spam Detector -> put it on spam or inbox

2.Car license Recognition -> Preprocessing (putih-hitam lbh recognizable)

3.Cart recommendation

4.ChatBot

### Tipe Pembelajaran Mesin

1. Unsupervised Learning (Pembelajaran tak-terbimbing) - tidak diberikan acuan
2. Supervised Learning (Pembelajaran Terbimbing) - diberikan sebuah acuan
3. Reinforcement Learning (Pembelajaran sendirinya) - diukur berdasarkan reward dan punishment melalui perulangan

#### Supervised 
- Klasifikasi = Butuh contoh (lables) jadi menebak dan mengklasifikasikan label
- Regresi = Butuh model (garis linear) seberapa dekat dengan garis atau model yang ditentukan.

#### Unsupervised
- Mencoba mengenali pola-pola datanya untuk kemudian dikelompokkan sesuai pola atau jenis yang telah ditemukan. Experience - Task - Performance.
- Dimencsional Reduction Tasks = apabila datanya mirip2 (bias) sehingga tidak perlu dipakai. 

#### Reinforcement
- Bener-bener melihat kondisi data yang ada disekitar
- Observation - action - environment - reward (ulang ampe pinter ampe ngancurin turret tengah)

### Tipe Data dalam konteks pembelajaran mesin
- Structured Data, cth: tanggal, nohp, nama kustomer, dsb. 
- Unstructured Data, cth: gambar (pixel), dokumen, pos-el dan pesan
- Semi-structured Data, log server, tweet terorganisir dengan hashtags, email yg diurutkan dengan folder(direktori).

### Pelatihan, pengujian, dan validasi data
- Pelatihan dibutuhkan untuk berlatih.
- Pengujian digunakan untuk memvalidasi apakah pembelajarannya telah sesuai atau belum.
- Validasi terdiri dari validasi silang (pemisahan dan langsung)


### Cara mengukur pembelajaras mesin
1. Indikator performa diukur berdasarkan jumlah dari kesalahan prodiksi
2. Overfitting(gabener, terlalu menghapal data), underfitting(gabener, tidak mengikuti pola data), Good balance(bener, tidak terlalu menghapal data, dan cukup mengikuti pola). Jadi harus bersifat menggeneralisir

### Menyiapkan alat untuk pembelajaran mesin
- Code editor
- Anaconda 






