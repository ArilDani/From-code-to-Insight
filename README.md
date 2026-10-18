# Data Bridge 2 — From Code to Insight

Contoh simulasi praktik **Data Analyst menggunakan Python**, mulai dari *data cleaning*, *data analysis*, visualisasi data, hingga pembuatan dashboard sederhana.

Repositori ini disiapkan sebagai bahan belajar/workshop untuk menunjukkan alur kerja analisis data dari dataset mentah menjadi insight yang dapat membantu memahami kondisi bisnis.

## 🔗 Dashboard Online

**Link dashboard:** https://digimart.streamlit.app/

## 🎯 Tujuan Praktik

- Membersihkan data dari duplikasi, nilai kosong, format teks yang tidak konsisten, dan tanggal tidak valid.
- Melakukan analisis eksploratif (*Exploratory Data Analysis / EDA*) menggunakan Pandas dan NumPy.
- Menghitung metrik sederhana seperti pendapatan, jumlah unit terjual, dan jumlah transaksi.
- Membuat visualisasi menggunakan Matplotlib, Seaborn, dan Plotly.
- Menyajikan hasil analisis melalui dashboard interaktif sederhana.

## 🧰 Teknologi yang Digunakan

- **Python** — bahasa pemrograman utama.
- **Pandas & NumPy** — pengolahan dan analisis data.
- **Matplotlib & Seaborn** — visualisasi data.
- **Plotly** — visualisasi interaktif.
- **Streamlit** — pembuatan dashboard berbasis web.
- **Jupyter Notebook** — praktik dan dokumentasi proses analisis.

## 📂 Struktur Proyek

```text
data-bridge-from-code-to-insight/
├── data/
│   └── penjualan.csv              
├── notebooks/
│   └── data_analysis.ipynb       
├── app.py                         
├── requirements.txt               
└── README.md                 
```


## ⚙️ Instalasi dan Menjalankan Proyek

### 1. Clone repositori

```bash
git clone https://github.com/ArilDani/From-code-to-Insight
cd From-code-to-Insight
```

### 2. Buat virtual environment (opsional, tetapi disarankan)

Windows:

```bash
python -m venv env
env\Scripts\activate
```

macOS/Linux:

```bash
python3 -m venv env
source env/bin/activate
```

### 3. Install dependensi

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Jalankan notebook analisis

Buka notebook di VS Code atau Jupyter Notebook. Jalankan cell secara berurutan, mulai dari import library dan membaca dataset, dilanjutkan cleaning, analisis, lalu visualisasi.

### 5. Jalankan dashboard (jika file `app.py` tersedia)

```bash
streamlit run app.py
```

Dashboard akan terbuka di browser. Pastikan path dataset yang digunakan pada kode sesuai dengan lokasi file di repositori.

## 🔄 Alur Analisis

1. **Load data** — membaca dataset ke DataFrame Pandas.
2. **Data cleaning** — menangani duplikasi, nilai kosong, konsistensi teks, dan format tanggal.
3. **Data analysis** — menghitung metrik serta merangkum data berdasarkan produk, kategori, kota, atau metode pembayaran.
4. **Data visualization** — menyampaikan pola data dalam bentuk grafik.
5. **Dashboarding** — menggabungkan KPI, grafik, filter, dan tabel dalam satu antarmuka interaktif.
6. **Insight** — menuliskan temuan berdasarkan hasil analisis, tanpa menyimpulkan hubungan sebab-akibat yang tidak didukung data.

## 📊 Contoh Pertanyaan Analisis

- Produk apa yang memiliki jumlah unit terjual paling tinggi?
- Kategori mana yang menghasilkan pendapatan terbesar?
- Bagaimana tren pendapatan dari waktu ke waktu?
- Kota mana yang memberikan kontribusi penjualan terbesar?
- Apa insight yang dapat disampaikan berdasarkan hasil visualisasi?

## 📌 Catatan

- Pastikan nama kolom dan lokasi dataset sesuai dengan yang dipakai di notebook atau `app.py`.
- Sesuaikan isi README dengan file yang benar-benar tersedia di repositori.
- Jangan mengunggah data pribadi, rahasia, kredensial, token API, atau file environment (`env/`) ke GitHub.
- Hasil analisis merupakan simulasi pembelajaran dan bukan rekomendasi bisnis tanpa validasi lebih lanjut.

## 👤 Author

**M. Aril Ardani**  
Data Bridge — From Code to Insight
