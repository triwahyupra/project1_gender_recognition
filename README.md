# Project 1: Face Recognition (Gender Classification)

Proyek ini menampilkan beragam percobaan arsitektur dan algoritma Convolitional Neural Network (CNN) dalam Computer Vision melalui implementasi klasifikasi gender menggunakan dataset CelebA. Dengan memanfaatkan teknik deep learning, model ini dilatih untuk memprediksi gender dengan akurasi berdasarkan atribut wajah.

## 🚀 Sorotan Utama:

    Teknik: Menggunakan teknik computer vision dengan library Tensorflow dan Keras.
    Model: Menggunakan arsitektur model deep learning VGG16, VGG19, GoogleNet, ResNet50 dan ResNet101.
    Kinerja: Mencapai prediksi gender terbaik dan akurat pada arsitektur ResNet50 dan ResNet101.

Jelajahi kode dan hasil untuk mendapatkan wawasan tentang dunia pengenalan wajah dan klasifikasi gender!

📝 Catatan: Proyek ini merupakan bagian dari Bootcamp Computer Vision oleh Indonesia AI.

## ★ Introduction

### Background

Identifikasi gender dari data pengguna menjadi semakin penting dalam berbagai bidng, termasuk dalam bisnis dan privasi. Pemodelan deep learning menawarkan pendekatan yang kuat dan adaptif untuk mengatasi tantangan ini, memungkinkan sebuah sistem untuk belajar pola yang kompleks dari data yang besar dan bervariasi.

### Problem Statement

Pemodelan deep learning menjanjikan solusi kuat untuk klasifikasi gender, namun terdapat tantangan dari ketidakpastian representasi gender dan ketidakseimbangan dataset. Terdapat variasi budaya/ras cukup sulit untuk dikenali, sementara ketidakseimbangan dataset dapat menyebabkan bias. Pada repositori ini, kita akan mengeksplorasi upaya untuk mencapai klasifikasi gender yang lebih akurat melalui pemodelan deep learning.
  
## ★ Getting Started

### 1. Data collection & Preparation

#### 🔍 Dataset : [CelebA (Celebrity Faces Attributes)](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

<img align="left" src="https://mmlab.ie.cuhk.edu.hk/projects/CelebA/intro.png" alt="Deskripsi Gambar" width="200" height="120">
Dataset diambil dari CelebA (Celebrity Faces Attributes), Dataset merupakan kumpulan data gambar wajah selebriti yang terdiri dari 200 ribu gambar wajah dari kurang lebih 10 ribu selebriti yang berbeda dengan 40 list attribute menjadi dasar proyek ini. Dalam pemrosesan kami menyaring data sebanyak 5000 gambar dengan attribute ‘Male’ yang merepresentasikan kelas Male dan Female. Kemudian menganalisis jumlah sebaran data dan melakukan split data menjadi data training, validation dan testing.


![Grafik Sebaran Data](path/to/gambar1.png) ![Data Split](path/to/gambar2.png)

### 1. Data Augmentation :

Untuk meningkatkan keragaman dataset pelatihan dan meningkatkan ketangguhan model, teknik augmentasi data berikut diterapkan selama pra-pemrosesan gambar:

    rescale=1.0 / 255 (Normalization)
    rotation_range=20
    width_shift_range=0.2
    height_shift_range=0.2
    horizontal_flip=True
    validation_split=0.2

Strategi augmentasi ini berkontribusi pada dataset pelatihan yang lebih beragam dan umum, meningkatkan kemampuan model untuk belajar dan berperforma baik pada berbagai input.


## ★ The Result

Pada bagian ini, silahkan sampaikan result atau hasil dari apa yang sudah kamu kerjakan.
Beberapa hal yang mungkin bisa kamu muat yaitu:
1. Informasi performa final accuracy dari model yang kamu bangun

2. Visualisasi gambar-gambar yang berhasil diprediksi oleh model kamu
3. Grafik-grafik yang relevan seperti performa model kamu saat proses training
4. Gambar confusion matrix dan lain sebagainya

## 📧 Contact

Last but not least, jangan lupa tinggalkan informasi kontak kamu seperti email atau link website
pribadi, dimana pengunjung bisa menghubungi kamu ketika tertarik untuk bertanya lebih jauh
apa yang sudah kamu kerjakan di project tersebut, atau bahkan ketika recruiters tertarik dengan
potensi kamu! 😊

