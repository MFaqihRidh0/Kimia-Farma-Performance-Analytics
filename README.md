# 💊 Kimia Farma Performance Analytics (2020-2023)

---

## 📋 Project Overview
Proyek ini adalah bagian dari tantangan **Big Data Analytics Intern** di Kimia Farma. Fokus utamanya adalah menganalisis kinerja bisnis perusahaan selama periode 2020-2023. Analisis ini mencakup integrasi data dari berbagai sumber (Transaksi, Produk, Cabang, dan Inventori) untuk menghasilkan wawasan strategis mengenai profitabilitas dan tren penjualan.

## 🛠️ Tech Stack
* **BigQuery (Google Cloud Platform)**: Untuk pemrosesan data skala besar dan pembuatan tabel analisa menggunakan SQL.
* **Google Looker Studio**: Untuk visualisasi data dan pembuatan dashboard interaktif.
* **GitHub**: Sebagai repositori kode dan dokumentasi proyek.

---

## 📊 Dataset Description
Analisis ini menggunakan empat dataset utama:
1. **kf_final_transaction**: Detail setiap transaksi pelanggan.
2. **kf_inventory**: Status stok produk di berbagai cabang.
3. **kf_kantor_cabang**: Informasi geografis dan rating kantor cabang.
4. **kf_product**: Katalog produk beserta harga satuannya.

## 🧠 Business Logic (SQL)
Dalam pembuatan tabel analisa, diterapkan logika perhitungan profit sebagai berikut:
* **Gross Profit Percentage**: Ditentukan berdasarkan kategori harga produk (<= 50k, <= 100k, <= 300k, <= 500k, > 500k).
* **Nett Sales**: Harga setelah dikurangi diskon.
* **Nett Profit**: Keuntungan bersih yang diperoleh dari penjualan setelah dikurangi persentase laba kotor.

---

## 📈 Dashboard Features
Dashboard Performance Analytics mencakup beberapa metrik kunci:
* **Revenue Growth**: Perbandingan pendapatan tahun ke tahun.
* **Geographical Analysis**: Peta sebaran profit per provinsi di Indonesia.
* **Top Performance**: Daftar 10 provinsi dengan total transaksi dan nett sales tertinggi.
* **Branch Health**: Analisis cabang dengan rating tinggi namun rating transaksi rendah.

---

## 📂 Repository Structure
```text
.
├── sql_syntax/
│   └── tabel_analisa.sql   # Script SQL untuk transformasi data di BigQuery
├── README.md               # Dokumentasi proyek
└── (link_dashboard.txt)    # Link menuju Google Looker Studio
```

Disusun Oleh:
M. Faqih Ridho – Big Data Analytics Intern
