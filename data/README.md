# Sumber Data dan Instruksi Unduhan

## 1. Informasi Dataset

- **Nama dataset:** IndonesiaAI Cleaned Data Split 0
- **Sumber:** [Hugging Face – IndonesiaAI/cleaned-data-split-0](https://huggingface.co/datasets/IndonesiaAI/cleaned-data-split-0)
- **Format:** Parquet
- **Split yang digunakan:** `train`
- **Perkiraan jumlah data:** 1.050.257 baris
- **Perkiraan ukuran:** 874 MB

Jumlah baris dan ukuran merupakan informasi yang perlu diverifikasi kembali berdasarkan file dataset yang berhasil diunduh.

## 2. Cara Mengunduh Dataset

1. Buka halaman dataset di Hugging Face:
   https://huggingface.co/datasets/IndonesiaAI/cleaned-data-split-0
2. Buka bagian **Files and versions**.
3. Unduh file Parquet yang diperlukan dari split `train`, atau gunakan metode pengunduhan melalui Python yang sesuai dengan struktur dataset.
4. Simpan file Parquet ke folder `data/raw/` pada direktori utama proyek.

Pastikan semua file Parquet yang dibutuhkan tersedia sebelum menjalankan notebook.

## 3. Struktur Penyimpanan

- `data/raw/`: menyimpan dataset asli.
- `data/processed/`: menyimpan dataset yang telah melalui proses pembersihan.

Dataset mentah dan hasil pemrosesan tidak disertakan dalam repository GitHub karena ukuran file yang besar. Pengguna dapat mengunduh kembali dataset dari sumber di atas dan menjalankan notebook secara berurutan untuk mereproduksi proses analisis.

## 4. Reproduksibilitas

Jalankan notebook dengan urutan berikut:

1. `notebooks/01_data_profiling.ipynb`
2. `notebooks/02_data_cleaning.ipynb`
3. `notebooks/03_eda_and_insights.ipynb`

Pastikan dependensi pada `requirements.txt` telah terpasang dan lokasi dataset sesuai dengan instruksi proyek.