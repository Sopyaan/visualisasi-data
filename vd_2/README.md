# Proyek Analisis Udara 2 Stasiun

## Informasi Umum

**Nama**: Sopyan  
**Email**: sopyanwae60@gmail.com

## Deskripsi Projek

Projek ini berfokus pada analisis data penyewaan sepeda untuk mendapatkan wawasan mengenai korelasi antara konsentrasi CO dan NO2, serta distribusi konsentrasi O3 pada stasiun Aotizhongxin dan Changping. Dua dataset utama yang digunakan adalah PRSA_Data_Aotizhongxin_20130301-20170228.csv dan PRSA_Data_Changping_20130301-20170228.csv, yang berisi data untuk menjawab pertanyaan bisnis.
## Pertanyaan Bisnis

1. Bagaimana korelasi antara konsentrasi CO dan NO2 di kedua stasiun?
2. Bagaimana distribusi suhu udara di kedua lokasi selama periode waktu tersebut?
3. Bagaimana distribusi konsentrasi O3 di dua stasiun tersebut?

## Analisis Data

Analisis data dilakukan dengan menggunakan Python dan berbagai library seperti pandas, matplotlib, dan seaborn. Proses analisis meliputi eksplorasi data, visualisasi, dan interpretasi hasil untuk menjawab pertanyaan bisnis.


## Dashboard

Dashboard interaktif dibuat dengan menggunakan Streamlit untuk memvisualisasikan hasil analisis data secara interaktif. Dashboard dapat diakses [di sini](https://sopyanudara.streamlit.app/)

## Setup Environment
Anda perlu membuat environment khusus menggunakan Conda dan menginstall dependensi yang diperlukan. Ikuti langkah-langkah berikut:
```sh
conda create --name main-ds python=3.11
conda activate main-ds
pip install streamlit pandas numpy matplotlib seaborn
```
## Run steamlit app
```
streamlit run analisis_cuaca.py
```
