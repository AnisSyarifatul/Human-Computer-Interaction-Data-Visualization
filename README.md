# Dashboard Visualisasi Data Pengunjung Perpustakaan

## Studi Kasus

Data kunjungan perpustakaan dapat digunakan untuk memahami pola kunjungan siswa berdasarkan tanggal, kelas, dan gender. Namun, data dalam bentuk tabel sering kali membutuhkan waktu lebih lama untuk dibaca dan dibandingkan. Oleh karena itu, proyek ini mengembangkan dashboard visualisasi data interaktif berbasis web menggunakan Python, Streamlit, Pandas, dan Plotly. Dashboard menyajikan ringkasan kunjungan, grafik tren harian, perbandingan kunjungan berdasarkan kelas, serta proporsi gender. Proyek ini menerapkan konsep Human-Computer Interaction (HCI), User-Centered Design (UCD), dan Data Visualization agar informasi dapat dipahami dengan lebih mudah.

## Tujuan

- Menampilkan data dalam bentuk visual yang mudah dipahami.
- Membantu pengguna membandingkan data kunjungan.
- Menerapkan prinsip dasar desain antarmuka yang berfokus pada pengguna.
- Memahami penggunaan grafik sesuai dengan jenis data.

## Teknologi

- Python
- Streamlit
- Pandas
- Plotly

## Fitur

- Ringkasan total kunjungan.
- Informasi jumlah pengunjung berdasarkan gender.
- Informasi kelas dengan jumlah kunjungan terbanyak.
- Grafik tren kunjungan harian menggunakan Line Chart.
- Grafik perbandingan kunjungan berdasarkan kelas menggunakan Bar Chart.
- Donut Chart untuk menampilkan proporsi gender.
- Filter data berdasarkan kelas dan gender.
- Tabel data kunjungan.
- Unduhan data hasil filter dalam format CSV.

## Struktur Proyek

```text
Dashboard-Visualisasi-Data/
├── main.py
├── dataset.csv
├── requirements.txt
├── README.md
└── .gitignore
```

## Persyaratan

Pastikan Python sudah terinstal di komputer.

## Cara Menjalankan

1. Buka folder proyek di VS Code.
2. Buka terminal dan buat virtual environment:

   ```bash
   python -m venv .venv
   ```

3. Instal semua library yang diperlukan:

   ```powershell
   .\.venv\Scripts\python.exe -m pip install -r requirements.txt
   ```

4. Jalankan aplikasi:

   ```powershell
   .\.venv\Scripts\python.exe -m streamlit run main.py
   ```

5. Buka alamat lokal yang ditampilkan pada terminal untuk menggunakan dashboard.

## Penerapan Materi Webinar

Proyek ini menerapkan beberapa konsep dari webinar Human-Computer Interaction & Data Visualization:

- **User-Centered Design (UCD):** menyajikan informasi utama agar mudah ditemukan pengguna.
- **Cognitive Load Theory:** menggunakan ringkasan dan grafik untuk mempermudah pemahaman data.
- **Recognition over Recall:** menyediakan label dan filter yang membantu pengguna mengenali informasi.
- **Data Visualization:** memilih grafik sesuai tujuan, yaitu Line Chart untuk tren, Bar Chart untuk perbandingan, dan Donut Chart untuk proporsi.
- **Ethical Design:** memberikan keterangan bahwa dataset yang digunakan merupakan data simulasi.