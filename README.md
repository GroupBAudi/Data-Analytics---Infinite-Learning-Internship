# Data-Engineering & Analytics — EnviroReport Pipeline

## Deskripsi
Repositori ini memuat *pipeline* data engineering dan analisis eksploratif untuk proyek **EnviroReport** (Website Pelaporan Isu Lingkungan Berbasis AI). Menggunakan dataset layanan publik metropolitan sebagai data proksi operasional untuk mensimulasikan pencatatan, kategorisasi standar, validasi spasial-temporal, dan penyediaan fitur (*feature engineering*) guna menyuplai kebutuhan *endpoint API* model AI *duplicate detection*.

## Dataset
*   **Sumber Utama**: [Open Data DC — 311 City Service Requests in 2024](https://opendata.dc.gov/datasets/DCGIS::311-city-service-requests-in-2024/about)
*   **File Mentah**: `All_Service_Requests_-_2024.csv`
*   **Dimensi Data Mentah**: 422.321 baris × 34 kolom
*   **Dimensi Unified Ready Dataset (Final)**: 315.717 baris × 19 kolom

---

Note: `preprocess.ipynb` gunakan dataset ini [Washington DC 311 Open Data](https://opendata.dc.gov/search?q=city%20works)
