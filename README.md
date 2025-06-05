## 📊 Video Game Sales Analysis

### 🎯 Project Description

Analisis data penjualan video game dari berbagai platform, genre, dan wilayah untuk menemukan insight penjualan, preferensi pasar, dan tren yang dapat dimanfaatkan oleh publisher atau developer.

### 👤 Author

I Gusti Agung Agastya Tarumawijaya
Batch: RMT-040

### 🔗 Dashboard Tableau

[Link ke Dashboard](https://public.tableau.com/app/profile/gusti.agung5677/viz/VideoGameSalesMilestone1/Dashboard1)

---

## 📁 Dataset

Dataset yang digunakan adalah **vg\_sales.csv**, yang berisi informasi penjualan video game dari berbagai wilayah seperti:

* North America (NA\_Sales)
* Europe (EU\_Sales)
* Japan (JP\_Sales)
* Other (Other\_Sales)
* Global Sales (Global\_Sales)

Kolom lainnya mencakup:

* Nama Game
* Platform
* Tahun Rilis
* Genre
* Publisher

---

## 🛠️ Tools & Libraries

* Python (Pandas, Matplotlib, Seaborn)
* Jupyter Notebook
* Tableau Public

---

## 🔍 Workflow Analisis

1. **Data Loading** – Membaca data dari file `vg_sales.csv`.
2. **Data Cleaning** – Menangani missing values, terutama pada kolom `Year`, `Publisher`, dan `Genre`.
3. **Exploratory Data Analysis (EDA)**:

   * Penjualan terbanyak per genre dan per platform.
   * Tren penjualan global dari waktu ke waktu.
   * Perbandingan preferensi pasar antar wilayah.
4. **Visualisasi** – Insight divisualisasikan di Tableau.

---

## 📈 Key Insights

* Genre **Action** dan **Sports** memiliki volume penjualan global tertinggi.
* Platform seperti **PS2** dan **X360** mendominasi penjualan di era 2000-an.
* Pasar Jepang menunjukkan preferensi berbeda dibandingkan NA/EU, terutama pada genre dan platform.

---

## ▶️ How to Run

1. Clone repositori ini.
2. Pastikan environment Python sudah memiliki library:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Jalankan notebook:

   ```bash
   jupyter notebook h8dsft_Milestone1_gusti_agung.ipynb
   ```

---

## 📌 Catatan Tambahan

* Insight lebih lanjut tersedia dalam dashboard Tableau interaktif.
* Notebook ini merupakan bagian dari Milestone 1 – Hacktiv8 Data Science Program.

---
