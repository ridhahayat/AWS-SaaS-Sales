# AWS-SaaS-Sales

## Deskripsi Proyek

Proyek ini bertujuan untuk melakukan analisis menyeluruh terhadap data penjualan, profit, dan strategi diskon pada perusahaan yang bergerak di industri Software as a Service (SaaS), dengan fokus khusus pada sektor Finance. Analisis ini dilakukan dengan pendekatan eksploratif dan visualisasi data untuk memberikan insight yang kuat bagi pengambilan keputusan bisnis, terutama terkait dengan produk, wilayah, dan strategi promosi.

## Struktur File

- `Capstone Project AWS by Ridha Hayat.ipynb` – Notebook utama berisi:
  - Eksplorasi dan pembersihan data
  - Visualisasi dan analisis distribusi
  - Uji hipotesis dan insight
- `README.md` – Dokumentasi proyek ini
- Gambar hasil visualisasi

## Deskripsi Kolom Dataset

| Kolom        | Deskripsi                                                    |
| ------------ | ------------------------------------------------------------ |
| Order ID     | ID unik untuk setiap transaksi penjualan                     |
| Customer ID  | ID unik untuk setiap pelanggan                               |
| Product Name | Nama produk yang dijual                                      |
| Category     | Kategori utama dari produk                                   |
| Sub-Category | Sub-kategori dari produk                                     |
| Sales        | Total nilai penjualan produk                                 |
| Quantity     | Jumlah produk yang dijual                                    |
| Discount     | Persentase diskon yang diberikan                             |
| Profit       | Laba yang dihasilkan dari penjualan produk                   |
| Region       | Wilayah geografis tempat penjualan dilakukan                 |
| Segment      | Tipe pelanggan (Consumer, Corporate, atau Home Office)       |
| Order Date   | Tanggal pemesanan dilakukan                                  |
| Ship Date    | Tanggal pengiriman                                           |
| Ship Mode    | Metode pengiriman yang dipilih                               |
| Country      | Negara tujuan pengiriman (difokuskan di US untuk proyek ini) |

## Fitur Analisis

- Pembersihan dan eksplorasi data awal (missing values, duplikasi, tipe data)
- Visualisasi distribusi profit, sales, dan discount
- Identifikasi produk-produk dengan margin tertinggi dan terendah
- Analisis pengaruh diskon terhadap penjualan dan profitabilitas
- Analisis tren waktu penjualan dan keuntungan
- Segmentasi wilayah (region) dan kategori market
- Analisis khusus untuk sektor Finance

## Tools & Teknologi

- **Bahasa Pemrograman:** Python
- **Library:**
  - Pandas & NumPy – manipulasi dan analisis data
  - Matplotlib & Seaborn – visualisasi data
  - Jupyter Notebook – pengembangan dan dokumentasi analisis

## Tujuan Analisis

- Menentukan produk mana yang paling dan paling tidak menguntungkan.
- Mengetahui pengaruh besar diskon terhadap peningkatan penjualan dan efeknya terhadap profit.
- Mengidentifikasi wilayah potensial untuk ekspansi pasar.
- Menyediakan strategi berbasis data untuk pricing dan promosi di sektor Finance.

## Hipotesis yang Diuji

1. Produk dengan diskon tinggi akan memiliki sales lebih tinggi, namun profit lebih rendah.
2. Sektor Finance memiliki performa penjualan dan profit yang konsisten dibandingkan sektor lain.
3. Wilayah tertentu menghasilkan margin profit yang lebih tinggi secara konsisten.
4. Produk dengan profit margin tinggi tidak selalu memiliki penjualan tertinggi.

## Hasil Utama (Insight)

- Diskon besar (>30%) cenderung meningkatkan penjualan namun menurunkan margin keuntungan.
- Produk tertentu di sektor Finance menyumbang profit tinggi meskipun volume sales tidak besar.
- Wilayah seperti Europe, Middle East, and Africa menjadi kontributor profit terbesar.
- Terdapat korelasi negatif antara discount dan profit setelah titik tertentu.

## Dataset

Dataset ini berasal dari [SaaS Sales] yang telah dimodifikasi dan difokuskan pada sektor Finance.

> Catatan: Data telah dibersihkan dan disesuaikan dalam notebook untuk keperluan eksplorasi dan visualisasi.

## Kontributor

**Ridha Hayat**

---
