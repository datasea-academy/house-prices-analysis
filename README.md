# 🏠 House Price Analysis (Data Processing & Insight)

![Datasea Badge](https://img.shields.io/badge/Unit-Datasea_Labs-blue?style=for-the-badge&logo=github)
![Division Badge](https://img.shields.io/badge/Division-MIDTECH-orange?style=for-the-badge)
![Batch Badge](https://img.shields.io/badge/Batch-1_2025-success?style=for-the-badge)

> **Project Eksanta Data Science**
> Repository ini berisi analisis faktor-faktor yang mempengaruhi harga properti residensial, disusun oleh **Kelompok 3 (Divisi MIDTECH)**.

---

## 👥 Anggota Tim (Kelompok 3)

| Nama Anggota | NIM | Username GitHub |
| :--- | :--- | :--- |
| **Naufa Sabrina** | 5251811008 | [@username](https://github.com/username) |
| **Ridwan Nur H** | 5251811017 | [@username](https://github.com/username) |
| **Alif Sultan Giri Taruna Jaya** | 5251811011 | [@username](https://github.com/username) |
| **Muhammad Fauzan Pratama N** | 525181102 | [@username](https://github.com/username) |
| **Aghniya Izzatul Azra** | 5251811015 | [@username](https://github.com/username) |

---

## 📖 Latar Belakang
Pasar properti dipengaruhi oleh banyak variabel kompleks, mulai dari luas tanah, kualitas material, hingga lokasi fisik. Project ini bertujuan membedah data spesifikasi rumah untuk memahami karakteristik apa yang paling signifikan dalam menentukan nilai jual sebuah properti.

### 🎯 Scope of Work (Lingkup Pengerjaan)
Fokus utama project ini adalah pengolahan data mentah yang kompleks menjadi *insight* yang bersih:

1.  **Data Cleaning:** Dataset ini memiliki banyak *missing values* (seperti fitur kolam renang atau pagar yang kosong). Tugas utama adalah menangani kekosongan ini secara logis dan membersihkan tipe data.
2.  **Data Normalization:** Melakukan transformasi pada harga rumah (*Log Transformation*) dan fitur numerik lainnya agar distribusinya normal dan siap dianalisis.
3.  **Visualization:** Membuat visualisasi mendalam (seperti *Correlation Heatmap* dan *Scatter Plot*) untuk melihat hubungan antara fitur fisik rumah dengan harga jual.
4.  **Interpretation:** Menarik kesimpulan bisnis tentang fitur apa yang paling "mahal" (misal: "Apakah renovasi dapur lebih berpengaruh daripada luas garasi?").

---

## 💾 Tentang Dataset
Dataset ini memuat 79 variabel penjelas yang mendeskripsikan aspek rumah hunian di Ames, Iowa.
* **Sumber:** [Kaggle - House Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
* **Target Utama:** `SalePrice` (Harga Jual).
* **Fitur Kunci:**
  * `OverallQual`: Kualitas material dan penyelesaian rumah.
  * `GrLivArea`: Luas area hunian (di atas tanah).
  * `YearBuilt`: Tahun rumah dibangun.
  * `GarageCars`: Kapasitas garasi.

---

## 📂 Struktur Folder

```text
├── 📂 data/
│   ├── 📂 raw/            # Dataset asli (house_prices.csv)
│   └── 📂 processed/      # Data bersih siap visualisasi
├── 📂 notebooks/
│   ├── 01_data_cleaning.ipynb       # Handling Missing Values (Complex)
│   ├── 02_data_normalization.ipynb  # Log Transform & Scaling
│   └── 03_visualization_insight.ipynb # Analisis Faktor Harga
├── 📄 .gitignore          # File sampah sistem
├── 📄 README.md           # Dokumentasi project
└── 📄 requirements.txt    # Library Python