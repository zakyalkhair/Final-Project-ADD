🧬 Final Project ADD – Clustering Analysis of Diseases in South Korea (2022)

Final Project – Algorithms & Data Diagnostics (ADD)
Analisis clustering penyakit di Korea Selatan menggunakan algoritma K-Means untuk mengelompokkan negara berdasarkan indikator kesehatan global.

📌 Deskripsi Singkat

Proyek ini menganalisis dataset kesehatan global menggunakan metode unsupervised learning, yaitu K-Means Clustering, untuk mengidentifikasi pola epidemiologi dan perbedaan karakteristik penyakit antar negara. Seluruh proses dilakukan menggunakan R Markdown yang kemudian diekspor menjadi laporan praktikum akhir.

📂 Dataset

Dataset yang digunakan berasal dari Kaggle:

🔗 Global Health Statistics – Kaggle
https://www.kaggle.com/datasets/malaiarasugraj/global-health-statistics/data

Dataset ini berisi indikator kesehatan global seperti angka kematian, penyakit tidak menular, penyakit menular, faktor risiko, dan statistik kesehatan publik lainnya.

📂 Struktur Repository
Final-Project-ADD/
│
├── Laporan Praktikum.Rmd       # File analisis utama (R Markdown)
├── Laporan Praktikum.html      # (opsional) Output report
├── data/                       # Dataset mentah/olahan
├── output/                     # Grafik dan hasil clustering
└── README.md                   # Dokumentasi proyek

🛠️ Teknologi yang Digunakan

R / RStudio

Package utama:

tidyverse

cluster

factoextra

ggplot2

📥 Cara Menjalankan Proyek

Clone repository:

git clone https://github.com/zakyalkhair/Final-Project-ADD.git


Buka file:

Laporan Praktikum.Rmd


Install package yang diperlukan:

install.packages(c("tidyverse", "cluster", "factoextra", "ggplot2"))


Jalankan seluruh chunk atau tekan tombol Knit untuk menghasilkan laporan.



👤 Kontributor
Nama	Peran
Zaky Alkhair	Data preprocessing, clustering, visualisasi, dokumentasi
📜 Lisensi

Repositori ini dirilis menggunakan MIT License.
Silakan gunakan dan modifikasi sesuai kebutuhan akademik.
