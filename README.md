# 🔊 Smart SOS System: Deteksi Audio untuk Situasi Darurat

Sistem **Smart SOS** adalah proyek berbasis Artificial Intelligence (AI) yang dirancang untuk mendeteksi suara pengguna dalam kondisi darurat dan secara otomatis mengirimkan sinyal SOS ke kontak darurat terdekat. Proyek ini memanfaatkan teknologi *speech-to-text* dan *Natural Language Processing (NLP)* untuk meminimalkan waktu respon dalam keadaan bahaya, seperti perampokan, kebakaran, atau ancaman fisik.

## 🚨 Latar Belakang
Dengan meningkatnya angka kriminalitas dan kondisi darurat di beberapa wilayah, kebutuhan akan solusi keamanan pribadi yang responsif menjadi sangat penting. Sementara itu, tren penggunaan smartphone yang selalu dibawa ke mana-mana membuka peluang untuk menjadikan perangkat tersebut sebagai alat penyelamat yang efektif. Namun, aplikasi SOS bawaan pada smartphone saat ini masih memiliki kekurangan, seperti harus diaktifkan manual, tidak hands-free, dan lambat dalam mengenali situasi kritis.

## 🛠️ Fitur Utama
- 🎤 **Deteksi Audio Real-Time**
  - Menggunakan model **Whisper (OpenAI)** untuk mengonversi suara pengguna menjadi teks secara langsung.
- 🗝️ **Keyword Spotting**
  - Mendeteksi kata kunci darurat seperti *"tolong"*, *"bantu saya"*, *"panggil polisi"* dengan cepat.
- 🧠 **Analisis Konteks**
  - Menggunakan model NLP untuk memahami konteks kalimat panjang, bahkan jika tidak ada kata kunci eksplisit.
- 📡 **Sinyal SOS Otomatis**
  - Mengirimkan pesan darurat ke kontak terdekat beserta lokasi GPS pengguna.

## 📂 Dataset
Dataset Bahasa Indonesia dengan total **1.000 kalimat**:
- ✅ 500 kalimat **darurat** (*"Tolong cepat, ada orang mencoba masuk rumah saya!"*).
- ✅ 500 kalimat **aman** (*"Saya sedang makan siang di kafe."*).
- Dataset ini bebas dari kalimat ambigu untuk memastikan akurasi model.

## 🛠️ Teknologi
- **Bahasa Pemrograman:** Python
- **Library ML:** Whisper And TensorFlow

## 🎯 Tujuan Proyek
Membantu pengguna smartphone agar dapat:
1. Memberikan **perlindungan diri** melalui deteksi suara hands-free.
2. Mempercepat respon dalam kondisi darurat.
3. Mengintegrasikan teknologi ini sebagai solusi keamanan berbasis AI untuk perangkat mobile.
