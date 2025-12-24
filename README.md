# Proyek Data Warehouse & ETL - Business Intelligence
**Kelompok 7 - Kelas TI 3A**
**Program Studi D-IV Teknik Informatika**
**Jurusan Teknologi Informasi - Politeknik Negeri Malang**

## 📝 Deskripsi Proyek
Proyek ini merupakan tugas besar (UAS) mata kuliah Business Intelligence yang berfokus pada pembangunan infrastruktur Data Warehouse menggunakan metode ETL (Extract, Transform, Load). Kami menggunakan studi kasus pengelolaan data Customer Purchase History untuk menghasilkan insight melalui skema bintang (Star Schema).

## 📂 Struktur Repositori
Repositori ini terdiri dari beberapa komponen utama sesuai instruksi tugas:
* **File Pentaho (.ktr/.kjb):** Pipeline ETL untuk ekstraksi dan transformasi data.
* **SQL Scripts:** Query untuk pembuatan database (DDL), tabel dimensi, tabel fakta, dan pengujian data.
* **File Visualisasi:** Link atau screenshot dashboard visualisasi/KPI.
* **File Laporan (PDF):** Dokumentasi lengkap proses proyek.
* **Dataset:** Sumber data dummy (CSV/Excel) yang digunakan.

## 🏗️ Perancangan Skema Bintang (Star Schema)
Berdasarkan data yang diolah, kami merancang skema sebagai berikut:
* **Tabel Fakta:** `Fact_Penjualan` 
* **Tabel Dimensi:** 
    * `Dim_Waktu`
    * `Dim_Produk`
    * `Dim_Pelanggan`
    * `Dim_Pembayaran`

## ⚙️ Proses ETL
Proses ETL dilakukan dengan tahapan:
1.  **Extract:** Mengambil data dari sumber dummy.
2.  **Transform:** Pembersihan data, normalisasi format tanggal, penghapusan duplikat, dan penyesuaian tipe data agar sesuai dengan skema bintang.
3.  **Load:** Memasukkan data ke dalam tabel dimensi dan fakta di Data Warehouse dengan menjaga integritas data.

## 📊 Analisis KPI
Beberapa indikator performa utama yang ditampilkan dalam visualisasi meliputi:
1.  Total penjualan.
2.  Penjualan Terbanyak per Produk  (Paling Sering Dipakai).
3.  Penjualan per Bulan (Trend Waktu). 
4.  Penjualan per Kategori Produk.
5.  Metode Pembayaran yang Paling Sering Digunakan.
6.  TOP 5 Pelanggan Berdasarkan Nilai Belanja.
7.  Rata-Rata Rating dari Setiap Produk.
8.  Penjualan per Kuartal (Level Executive).

## 👥 Anggota Kelompok
1. Alvino Valerian D.R - 2341720027
2. Anugerah Rachmadani - 244107023012
3. Ilham Faturachman - 244107023001
3. Muhammad Adityo Rahman - 2341720177

---
*Proyek ini disusun untuk memenuhi tugas besar mata kuliah Business Intelligence.*