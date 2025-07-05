# Starbucks Review Sentiment Analysis

Capstone Project — Klasifikasi Sentimen dan Identifikasi Fokus pada Ulasan Pelanggan Starbucks Dengan IBM Granite

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

Proyek ini menggunakan **IBM Granite 8B Instruct Model** melalui API Replicate.  
Model digunakan untuk:
- **Sentiment classification** → Memberi label: Positive, Negative, atau Mixed  
- **Aspect/focus extraction** → Menandai topik seperti employee, product, service, dll.

Prompt disusun untuk mendeteksi kontras semantik (mis. kata: *but, although, despite*) agar AI bisa mengenali *mixed sentiment*.  
Hasil disimpan dalam format terstruktur dan digunakan untuk visualisasi dan insight.


---

## 📁 File Contents

- `Capstone_Starbucks Classification_Dinar Fauziah.ipynb` – Google Colab untuk klasifikasi
- `README.md` – Deskripsi proyek  
- `reviews_data.csv` – Dataset mentah

---

## 🧑‍💻 Author

Nama: Dinar Fauziah [Data Batch 7]
Proyek ini dibuat sebagai bagian dari tugas Capstone IBM x Hacktiv8.

