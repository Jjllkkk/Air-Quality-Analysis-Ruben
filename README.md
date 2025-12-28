  🌬️ Air Quality Analysis: Beijing Dataset

   📝 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis kualitas udara di Beijing selama periode 2013-2017. Fokus utama analisis adalah mengidentifikasi hubungan antara polutan partikel halus (PM2.5) dengan polutan gas (CO & NO2), serta memetakan wilayah dengan tingkat polusi paling kritis. Analisis ini menggunakan pendekatan   Exploratory Data Analysis (EDA)   dan diperkuat dengan model   Machine Learning (Linear Regression)   untuk mendukung pengambilan keputusan berbasis data.

   📊 Pertanyaan Bisnis
1. Bagaimana hubungan (korelasi) antara kadar PM2.5 dengan gas polutan lainnya seperti NO2 dan CO?
2. Stasiun/wilayah mana di Beijing yang memiliki tingkat polusi udara tertinggi secara rata-rata?

   🚀 Fitur Utama Dashboard
    Ringkasan Statistik:   Menampilkan rata-rata polutan secara real-time.
    Analisis Korelasi:   Visualisasi interaktif hubungan antar polutan.
    Pemetaan Wilayah:   Ranking stasiun pemantau berdasarkan tingkat bahaya PM2.5.
    Prediksi Sederhana:   Menggunakan model ML untuk mengestimasi PM2.5.

   📁 Struktur Folder
```text
📂 proyek_analisis_data
 ├── 📂 data                  Dataset mentah (PRSA_Data_ .csv)
 ├── 📂 dashboard             File untuk deployment Streamlit
 │    └── dashboard.py
 ├── notebook.ipynb           Dokumentasi lengkap proses analisis
 ├── README.md                Panduan proyek
 └── requirements.txt         Daftar library yang dibutuhkan
