# 🚀 Proyek Machine Learning: Implementasi Generative Adversarial Network (GAN)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) 
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue)
![License](https://img.shields.io/badge/License-Academic-yellow)

---

## 🎯 Deskripsi
Proyek ini mengimplementasikan **Generative Adversarial Network (GAN)** sederhana menggunakan **PyTorch**, untuk menghasilkan gambar dari dataset publik Kaggle.  
Dibuat sebagai bagian dari tugas kelompok mata kuliah Machine Learning.

**Fitur utama:**
- ✅ Arsitektur Generator & Discriminator lengkap
- ✅ Visualisasi loss selama training
- ✅ Hasil gambar generator tiap epoch
- ✅ Penyimpanan model (.pth) dan output gambar

---

## 👥 Anggota Kelompok
| No | Nama                              | Tanggung Jawab                                       |
|----|-----------------------------------|------------------------------------------------------|
| 1  | Atha Fathur Adz Dzikri            | Konsep GAN, penjelasan awal notebook, setup folder   |
| 2  | Farid Fajar Abdillah              | Implementasi Generator & dokumentasi layer          |
| 3  | Iqbal Maulana                     | Implementasi Discriminator & dokumentasi layer      |
| 4  | Abdullah Sukma Jati               | Training loop, visualisasi loss, simpan model       |
| 5  | Ahmad Nugrahadi                   | Visualisasi hasil gambar, simpan gambar tiap epoch  |
| 6  | Gusti Ahmad Muttahid Bilhaq       | Testing keseluruhan, dokumentasi akhir & README     |

---

## 📂 Struktur Direktori
├── generated_images/ # Gambar hasil training tiap epoch
├── models/ # Model GAN yang sudah dilatih (.pth)
├── generator-ml.ipynb # Notebook utama
└── README.md # Dokumentasi proyek ini

## 🚀 Cara Menjalankan
1. **Clone repository ini**
   ```bash
   git clone https://github.com/<username>/<repo>.git
   cd <repo>

2. **Install dependency (misalnya via pip)**
    ```bash
    pip install torch torchvision matplotlib numpy

3. **Jalankan notebook**
    ```bash
    jupyter notebook generator-ml.ipynb

## Fitur
- Pelatihan model GAN
- Visualisasi gambar hasil setiap epoch
- Penyimpanan model (.pth)



