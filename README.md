# Simulasi Monte Carlo: Kebiasaan Belajar Mahasiswa

## Tentang Proyek
Repositori ini berisi implementasi **Simulasi Monte Carlo** untuk memodelkan probabilitas dan distribusi frekuensi dari kebiasaan belajar mahasiswa (n = 30). 

Simulasi ini dijalankan sebanyak **10.000 iterasi** untuk melihat kecenderungan jangka panjang, mengestimasi probabilitas kejadian tertentu (seperti peluang mahasiswa belajar lebih dari 4 jam per hari), dan memvisualisasikan distribusi hasil yang mungkin terjadi.

## Struktur Repositori
- `simulasi_monte_carlo_kebiasaan_belajar.ipynb` : File Jupyter Notebook utama yang berisi kode simulasi, perhitungan probabilitas, dan visualisasi grafik distribusi.
- `Rekap Data Wawancara.xlsx` : Dataset mentah yang digunakan sebagai dasar parameter simulasi.

## Library Python yang Digunakan
- `pandas` dan `numpy` : Manipulasi data dan pembangkitan angka acak (random sampling).
- `matplotlib` dan `seaborn` : Visualisasi grafik distribusi probabilitas dan frekuensi.
- `scipy.stats` : Analisis distribusi statistik.

## Cara Menjalankan Proyek
1. Unduh file `.ipynb` dan `.xlsx` dari repositori ini.
2. Buka file `.ipynb` menggunakan Google Colab atau Jupyter Notebook lokal.
3. Pastikan file `.xlsx` berada di direktori yang sama.
4. Klik menu Runtime > Restart and Run All untuk menjalankan simulasi 10.000 iterasi.
