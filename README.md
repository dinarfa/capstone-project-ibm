# Starbucks Review Classification

Capstone Project — Sentiment Analysis with IBM Granite

---

## 📝 Project Overview

Ulasan pelanggan Starbucks menyimpan insight penting, namun jumlah dan ragamnya sulit dianalisis secara manual.  
Proyek ini bertujuan untuk mengklasifikasikan sentimen (Positive, Negative, Mixed) dan mengidentifikasi fokus ulasan menggunakan model AI IBM Granite.

---

## 🔗 Raw Dataset

Dataset diambil dari sumber Kaggle berikut:  
📂 [Raw Dataset CSV](https://www.kaggle.com/datasets/harshalhonde/starbucks-reviews-dataset)

---

## 📊 Insight & Findings

- Sekitar **80% review bersentimen negatif**, menunjukkan dominasi keluhan dari pelanggan.  
- Fokus utama mencakup **pegawai** (tidak ramah, dugaan rasisme), **produk** (rasa, tekstur, salah pesanan), dan **layanan pelanggan**.  
- Beberapa review positif menyoroti **staf yang ramah** dan **minuman yang enak**,  
  sementara review mixed muncul karena **ketidakkonsistenan antar gerai** atau kombinasi pengalaman positif dan negatif.  

---

## 🤖 AI Support Explanation

- Menggunakan model **IBM Granite 3.3-8b Instruct** melalui API Replicate  
- Prompt dirancang dua tahap: klasifikasi sentimen dan identifikasi fokus  
- AI cukup akurat memahami review dengan konteks kontras (kata “but”, “although”, dsb.)  
- Output terstruktur dan digunakan untuk analisis lanjutan (visualisasi & insight)

---

## 📁 File Contents

- `Capstone_Starbucks Classification_Dinar Fauziah.ipynb` – Google Colab untuk klasifikasi
- `README.md` – Deskripsi proyek  
- `reviews_data.csv` – Dataset mentah

---

## 🧑‍💻 Author

Nama: Dinar Fauziah  
Proyek ini dibuat sebagai bagian dari tugas Capstone IBM x Hacktiv8.
