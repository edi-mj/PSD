# Proyek Data Sains

![Jupyter Book](https://img.shields.io/badge/Jupyter%20Book-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![KNIME](https://img.shields.io/badge/KNIME-FFC800?style=for-the-badge&logo=knime&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

Dokumentasi pembelajaran dan implementasi berbagai metode data science dalam format Jupyter Book. Proyek ini dibuat sebagai bagian dari mata kuliah Proyek Data Sains di Program Studi Teknik Informatika, Universitas Trunojoyo Madura.

## Deskripsi Proyek

Proyek ini merupakan kumpulan dokumentasi dan implementasi praktis dari berbagai teknik dan metodologi dalam bidang data science. Dikembangkan menggunakan Jupyter Book, proyek ini menggabungkan penjelasan teoritis dengan implementasi kode yang dapat langsung dijalankan, sehingga memudahkan proses pembelajaran dan referensi.

Konten pembelajaran mencakup beberapa studi kasus nyata, dengan menggunakan berbagai teknik machine learning untuk klasifikasi dan forecasting.

## Topik Pembahasan

Proyek ini mencakup berbagai topik penting dalam data science:

### 1. Data Understanding

Pemahaman data menggunakan framework CRISP-DM, meliputi pengumpulan data, eksplorasi, dan verifikasi kualitas data menggunakan Power BI dengan integrasi database MySQL dan PostgreSQL.

### 2. Pre-processing

Teknik persiapan data sebelum pemodelan, termasuk:

- Data balancing untuk mengatasi ketidakseimbangan kelas
- Cleaning dan transformasi data
- Feature engineering

### 3. Classification

Implementasi berbagai algoritma klasifikasi untuk menyelesaikan masalah supervised learning, termasuk evaluasi model dan perbandingan performa.

### 4. Analisis Data dengan KNIME

Eksplorasi dan analisis data menggunakan platform KNIME Analytics Platform untuk workflow visual tanpa kode.

### 5. Time Series Forecasting

Teknik dan metode forecasting untuk data deret waktu, termasuk analisis tren, seasonality, dan prediksi nilai masa depan.

### 6. Dynamic Time Warping (DTW)

Implementasi algoritma DTW untuk mengukur kesamaan antara dua sequence temporal yang mungkin berbeda dalam kecepatan.

### 7. Time Series Classification

Metode klasifikasi khusus untuk data time series, menggabungkan teknik preprocessing time series dengan algoritma machine learning.

## Struktur Proyek

```
psd/
├── _config.yml              # Konfigurasi Jupyter Book
├── _toc.yml                 # Table of Contents
├── requirements.txt         # Dependencies Python
├── references.bib           # Referensi bibliografi
├── content/                 # Konten pembelajaran
│   ├── intro.md
│   ├── data-understanding.md
│   ├── pre-processing.md
│   ├── classification.ipynb
│   ├── data-balancing.ipynb
│   ├── time-series-forecasting.ipynb
│   ├── dtw.ipynb
│   ├── time-series-classification.ipynb
│   ├── analisis-data-knime.md
│   └── img/                 # Aset gambar
├── datasets/                # Dataset untuk analisis
└── _build/                  # Output build Jupyter Book
```

## Tech Stack

### Core Framework

- **Jupyter Book**: Framework untuk membuat dokumentasi interaktif dan publikasi berbasis Jupyter Notebook
- **MyST Markdown**: Syntax markdown yang diperluas untuk penulisan konten teknis

### Python Libraries

- **NumPy & Pandas**: Manipulasi dan analisis data
- **scikit-learn**: Machine learning dan modeling
- **Matplotlib**: Visualisasi data
- **Sphinx**: Generator dokumentasi

### Tools & Platforms

- **Power BI**: Business intelligence dan visualisasi data
- **KNIME**: Platform analitik visual untuk data science
- **MySQL & PostgreSQL**: Database management systems

## Instalasi dan Penggunaan

### Prerequisites

- Python 3.8 atau lebih tinggi
- pip (Python package manager)

### Langkah Instalasi

1. Clone repository ini:

```bash
git clone https://github.com/edi-mj/psd.git
cd psd
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Build Jupyter Book:

```bash
jupyter-book build .
```

4. Buka hasil build di browser:

```bash
# Windows
start _build/html/index.html

# Linux/Mac
open _build/html/index.html
```

### Menjalankan Notebook

Untuk menjalankan notebook secara interaktif:

```bash
jupyter notebook content/
```

## Kontribusi

Proyek ini merupakan bagian dari tugas akademik. Saran dan masukan dapat disampaikan melalui GitHub Issues atau Pull Requests.

## Lisensi

Proyek ini dibuat untuk keperluan pendidikan dan pembelajaran.

## Kontak

**Muhammad Junaidi (Edi)**

- GitHub: [@edi-mj](https://github.com/edi-mj)
- Repository: [PSD](https://github.com/edi-mj/psd)

---

Dibuat dengan Jupyter Book untuk mata kuliah Proyek Data Sains, Teknik Informatika, Universitas Trunojoyo Madura.
