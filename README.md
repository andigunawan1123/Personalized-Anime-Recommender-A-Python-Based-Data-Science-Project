# Anime Recommendation System Using Python: Building a Content-Based Filtering Model

## Overview
Proyek ini bertujuan untuk membangun sistem rekomendasi anime menggunakan pendekatan **Content-Based Filtering**. Sistem ini memberikan rekomendasi anime kepada pengguna berdasarkan kesamaan fitur (genre) antara anime yang mereka sukai. Proyek ini ditulis dalam bahasa pemrograman Python dan menggunakan berbagai pustaka seperti Pandas, Scikit-Learn, dan lainnya untuk analisis data dan pembelajaran mesin.

## Features
- **Content-Based Filtering**: Memberikan rekomendasi berdasarkan kemiripan fitur anime.
- **Analisis Data**: Memanfaatkan eksplorasi data untuk memahami pola dan preferensi pengguna.
- **Preprocessing Data**: Menggunakan teknik pra-pemrosesan untuk membersihkan dan menyiapkan data.
- **Visualisasi**: Visualisasi data menggunakan Matplotlib untuk pemahaman yang lebih baik.

## Dataset
Dataset yang digunakan dalam proyek ini berasal dari [MyAnimeList](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database?select=anime.csv). Dataset ini mencakup informasi tentang berbagai anime seperti judul, genre, rating, dan jumlah episode.

## Installation
Untuk menjalankan proyek ini secara lokal, ikuti langkah-langkah berikut:

1. Clone repositori ini:
   ```bash
   git clone https://github.com/andigunawan1123/Anime-Recommendation-System-Using-Python-Building-a-Content-Based-Filtering-Model.git
   ```
   
2. Navigasi ke direktori proyek:
   ```bash
   cd Anime-Recommendation-System-Using-Python-Building-a-Content-Based-Filtering-Model
   ```
   
3. Buat dan aktifkan environment virtual (opsional tapi disarankan):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Untuk MacOS/Linux
   .\venv\Scripts\activate   # Untuk Windows
   ```

4. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Pastikan semua dependensi telah terinstal.
2. Jalankan notebook Jupyter (`Anime-Recommendation-System-Using-Python-Building-a-Content-Based-Filtering-Model.ipynb`) untuk melihat langkah-langkah pembuatan model rekomendasi.
3. Anda bisa mencoba menambahkan anime yang Anda sukai untuk mendapatkan rekomendasi yang dipersonalisasi.

## Project Structure
```
Anime-Recommendation-System-Using-Python-Building-a-Content-Based-Filtering-Model/
│
├── data/                    # Folder untuk menyimpan dataset
├── notebooks/               # Folder untuk notebook Jupyter
│   └── Anime-Recommendation-System-Using-Python-Building-a-Content-Based-Filtering-Model.ipynb
├── src/                     # Folder untuk skrip Python
│   └── Anime-Recommendation-System-Using-Python-Building-a-Content-Based-Filtering-Model.py
├── image/                  # Folder untuk menyimpan visualisasi
├── README.md                # Dokumentasi proyek ini
└── requirements.txt         # Daftar dependensi
```

## Results
- Model rekomendasi ini mampu memberikan rekomendasi anime yang relevan berdasarkan genre.
- Visualisasi yang dihasilkan membantu memahami distribusi data dan hubungan antar fitur.

## Contributing
Kontribusi sangat disambut! Silakan buat "Issue" untuk mengusulkan fitur baru atau melaporkan bug. Jika Anda ingin berkontribusi, buatlah "Pull Request" dengan perubahan yang Anda ajukan.

## License
Proyek ini dilisensikan di bawah lisensi MIT - lihat file [LICENSE](LICENSE) untuk detailnya.

## Acknowledgements
- [Kaggle](https://www.kaggle.com/) untuk dataset yang digunakan dalam proyek ini.
- Tim di balik pustaka Python seperti Pandas, NumPy, Scikit-Learn, dan lainnya.
