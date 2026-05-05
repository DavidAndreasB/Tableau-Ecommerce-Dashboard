# 📊 E-Commerce Sales & Operations Performance Analysis

**Live Interactive Dashboard:** [Klik di sini untuk melihat Dashboard di Tableau Public](https://public.tableau.com/app/profile/david.fam2141/viz/Book1_17779636601020/E-CommerceOperationsDashboard#1)

## 📝 Deskripsi Project
Project ini bertujuan untuk menganalisis performa penjualan dan efisiensi operasional dari sebuah perusahaan E-Commerce fiktif (Superstore). Fokus utama dari analisis ini bukan hanya pada pelaporan pendapatan, tetapi juga pada identifikasi kebocoran profit dan evaluasi *Service Level Agreement* (SLA) pada sistem logistik/pengiriman barang.

## 🎯 Pertanyaan Bisnis (Business Questions)
Dashboard ini dibangun untuk menjawab pertanyaan strategis berikut:
1. Bagaimana tren pertumbuhan penjualan dari waktu ke waktu? Apakah terdapat pola musiman (*seasonality*)?
2. Wilayah/Negara bagian mana yang menyumbang pendapatan terbesar?
3. Sub-kategori produk apa yang sebenarnya menggerus keuntungan perusahaan (menghasilkan profit negatif)?
4. Bagaimana performa efisiensi waktu logistik (dari pesanan dibuat hingga barang dikirim) di berbagai kelas pengiriman?

## 🛠️ Tools & Metodologi
- **Data Visualization & Analytics:** Tableau Public
- **Data Source:** Global Superstore Dataset (.csv)
- **Teknik yang Digunakan:**
  - *Data Aggregation & Time-Series Analysis*
  - *Geospatial Mapping* (Choropleth Map)
  - *Calculated Fields* (Membuat formula matematika kustom untuk mengukur selisih hari operasional).

## 💡 Temuan Utama (Key Insights)

*   **Pola Musiman Penjualan (Seasonality):** Terdapat tren lonjakan transaksi yang konsisten pada Kuartal 4 (Q4), secara spesifik pada bulan November dan Desember. Ini mengindikasikan tingginya aktivitas belanja akhir tahun.
*   **Identifikasi Kebocoran Profit:** Meskipun menghasilkan angka penjualan bulanan yang ada, sub-kategori **Tables** dan **Bookcases** merupakan penyumbang kerugian bersih (*net loss*) terbesar bagi perusahaan. Strategi harga atau struktur diskon pada kategori ini perlu dievaluasi ulang secara mendesak.
*   **Performa Sistem Operasional Logistik:** Berdasarkan perhitungan *Order-to-Ship Lead Time*, pengiriman *Standard Class* memakan waktu rata-rata **5 hari**, *Second Class* sekitar **3.2 hari**, dan *First Class* sekitar **2.1 hari**. Metrik ini dapat digunakan sebagai landasan dasar (*baseline*) untuk mengukur target KPI logistik di masa depan.

## 🖼️ Tampilan Dashboard
![Dashboard Preview](<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b59534c9-db33-44a8-8e3d-c99b48acbab1" />
)

## 📂 Cara Menjalankan Project
1. Kunjungi tautan Tableau Public di atas untuk berinteraksi langsung dengan dashboard.
2. Gunakan filter interaktif dengan mengklik pada visualisasi peta (*Sales by Location*) atau pada bar chart (*Profit by Sub-Category*) untuk melihat data secara terpusat (*drill-down*).
3. File dataset mentah (`Sample - Superstore.csv`) telah disertakan dalam repositori ini bagi yang ingin melihat struktur asal datanya.
