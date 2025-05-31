PREDIKSI KARIR BERDASARKAN KEAHLIAN

Proyek ini merupakan implementasi sistem prediksi karir menggunakan algoritma Decision Tree. Sistem ini menerima input berupa skor berbagai keahlian pengguna (seperti programming, komunikasi, kreativitas, dll), lalu memberikan prediksi karir yang cocok berdasarkan dataset pelatihan.

Dataset yang digunakan merupakan data simulasi dengan skor berbagai keahlian dari individu fiktif, serta karir yang sesuai.

-- Cara Menjalankan Kode --
1. Buka Google Colab (https://colab.research.google.com/)

2. Upload file PrediksiKarirAi.ipynb

3. Jalankan sel kode satu per satu dari atas ke bawah

4. Anda dapat memasukkan nilai skor keahlian Anda secara manual saat diminta input.Sistem akan menampilkan prediksi karir Anda

Atau jika menggunakan file CSV eksternal:

1. Pastikan file sample_dataset_career.csv tersedia

2. Gunakan pd.read_csv("sample_dataset_career.csv") untuk memuat data

-- Fitur Utama --
✅ Training model Decision Tree dari dataset keahlian-karir
✅ Input skor keahlian dari user
✅ Prediksi karir berdasarkan input user
✅ Dataset disertai dengan nama untuk identifikasi individu

-- Contoh Penggunaan --
Misalnya, pengguna memasukkan skor keahlian berikut:
programming: 8
design: 3
communication: 6
analysis: 9
leadership: 7
creativity: 4
math: 8

Output dari sistem:
Prediksi karir untuk Anda: Data Scientist
