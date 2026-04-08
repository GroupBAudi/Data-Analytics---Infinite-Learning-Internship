# Data-Analytics---Infinite-Learning-Internship

## Deskripsi
Analisis data laporan layanan publik menggunakan dataset Washington DC 311 
sebagai referensi untuk pengembangan sistem pelaporan komunitas RT/RW berbasis AI.

## Struktur Folder
- `notebooks/` — Jupyter notebook preprocessing, EDA, dan analisis
- `reports/` — Laporan PDF sprint review
- `charts/` — Visualisasi hasil EDA (Chart 1–9)
- `data/` — Dataset final (Xfinal.csv)

## Dataset
- **Sumber**: [Washington DC 311 Open Data](https://opendata.dc.gov/search?q=city%20works)
- **Ukuran awal**: 1.466.152 baris × 56 kolom
- **Dataset final (Xfinal)**: 656.836 baris × 11 kolom

## Pipeline
1. Data Collection
2. Data Preprocessing (cleaning, near-duplicate removal, IQR outlier)
3. EDA — Univariat, Bivariat, Multivariat
4. Visualisasi (Chart 1–9)
5. Finalisasi → X_final.csv