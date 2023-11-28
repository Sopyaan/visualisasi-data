# Proyek Analisis Data Penyewaan Sepeda

## Informasi Umum

**Nama**: Sopyan  
**Email**: sopyanwae60@gmail.com
**Id Dicoding**: sopyan_wae

## Deskripsi Projek

Projek ini berfokus pada analisis data penyewaan sepeda untuk mendapatkan wawasan mengenai pola dan tren penyewaan sepeda berdasarkan cuaca, weekend dan weekdays serta pengguna casual dan registered. Dua dataset utama yang digunakan adalah `day.csv` dan `hour.csv`, yang berisi data harian, kondisi dan waktu penyewaan sepeda.

## Pertanyaan Bisnis

1. Bagaimana variasi ketersediaan sepeda berdasarkan kondisi cuaca (weathersit) pada hari-hari tertentu? Apakah cuaca yang baik memengaruhi peningkatan penyewaan?
2. Bagaimana hubungan antara suhu (temp) dan jumlah penyewaan sepeda harian? Apakah terdapat tren atau pola tertentu?
3. Apakah ada perbedaan antara distribusi penyewaan sepeda antara weekend dan weekdays?
4. Bagaimana kontribusi pengguna casual dan registered terhadap total penyewaan sepeda?

## Analisis Data

Analisis data dilakukan dengan menggunakan Python dan berbagai library seperti pandas, matplotlib, dan seaborn. Proses analisis meliputi eksplorasi data, visualisasi, dan interpretasi hasil untuk menjawab pertanyaan bisnis.


## Dashboard

Dashboard interaktif dibuat dengan menggunakan Streamlit untuk memvisualisasikan hasil analisis data secara interaktif. Dashboard dapat diakses [di sini](https://visualisasi-data-9qrpggkchskjzcyjpmqnte.streamlit.app/)

## Setup Environment
Anda perlu membuat environment khusus menggunakan Conda dan menginstall dependensi yang diperlukan. Ikuti langkah-langkah berikut:
```sh
conda create --name main-ds python=3.11
conda activate main-ds
pip install streamlit pandas numpy matplotlib seaborn
```
## Run steamlit app
```
streamlit run streamlit_app.py
```
