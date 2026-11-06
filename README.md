# Analisis Pola Penyebaran COVID-19 di Indonesia Menggunakan Moran’s I dan Spatial Clustering

## 📌 Deskripsi Proyek

Project ini merupakan tugas UAS Data Mining yang bertujuan untuk menganalisis pola penyebaran COVID-19 di Indonesia dengan mempertimbangkan aspek spasial dan karakteristik wilayah.

Analisis dilakukan untuk mengetahui apakah terdapat autokorelasi spasial pada jumlah kasus COVID-19 antarprovinsi di Indonesia serta mengidentifikasi pola pengelompokan wilayah berdasarkan karakteristik kasusnya. Metode yang digunakan meliputi **Moran’s I** untuk analisis autokorelasi spasial global dan **Local Indicators of Spatial Association (LISA)** untuk mengidentifikasi pola pengelompokan secara lokal.

Selain analisis spasial, project ini mencakup eksplorasi data untuk melihat perkembangan kasus, jumlah kematian, tingkat pemulihan, serta hubungan antara karakteristik wilayah dan jumlah kasus COVID-19.

## 🎯 Tujuan

- Mengidentifikasi pola autokorelasi spasial jumlah kasus COVID-19 antarprovinsi di Indonesia.
- Menganalisis pengelompokan wilayah menggunakan metode LISA.
- Memvisualisasikan pola penyebaran COVID-19 melalui peta spasial.
- Mengeksplorasi perkembangan kasus, kematian, dan tingkat pemulihan COVID-19.
- Menganalisis hubungan antara karakteristik wilayah dengan jumlah kasus COVID-19.

## 📊 Dataset

Dataset yang digunakan berasal dari Kaggle:

[COVID-19 Indonesia Dataset](https://www.kaggle.com/datasets/hendratno/covid19-indonesia)

Data mencakup informasi perkembangan COVID-19 di Indonesia serta karakteristik wilayah yang digunakan dalam analisis.

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GeoPandas
- PySAL
- Libpysal
- ESDA
- splot

## 🔍 Metodologi

Tahapan analisis yang dilakukan dalam project ini meliputi:

1. **Data Loading** — Memuat dataset COVID-19 Indonesia dan data geografis provinsi.
2. **Exploratory Data Analysis (EDA)** — Melakukan eksplorasi data dan statistik deskriptif.
3. **Data Preprocessing** — Menyiapkan data agar dapat digunakan dalam analisis spasial.
4. **Data Aggregation** — Mengagregasikan data kasus COVID-19 berdasarkan provinsi.
5. **Spatial Weight Matrix** — Membentuk matriks bobot spasial menggunakan metode K-Nearest Neighbors (KNN) dengan jumlah tetangga sebanyak 4.
6. **Global Spatial Autocorrelation** — Menggunakan Moran’s I untuk mengidentifikasi autokorelasi spasial jumlah kasus COVID-19.
7. **Local Spatial Autocorrelation** — Menggunakan LISA untuk mengidentifikasi pola pengelompokan spasial pada tingkat provinsi.
8. **Spatial Visualization** — Memvisualisasikan hasil analisis dalam bentuk Moran Scatterplot dan peta cluster LISA.
9. **Additional Analysis** — Melakukan analisis perkembangan jumlah kematian, kasus baru, tingkat pemulihan, serta hubungan karakteristik wilayah dengan kasus COVID-19.

## 📈 Analisis yang Dilakukan

- Statistik deskriptif dan eksplorasi data COVID-19.
- Analisis autokorelasi spasial global menggunakan Moran’s I.
- Analisis pengelompokan lokal menggunakan LISA.
- Visualisasi peta cluster COVID-19 berdasarkan provinsi.
- Analisis korelasi karakteristik wilayah dengan total kasus.
- Analisis tren jumlah kematian COVID-19 per tahun.
- Perbandingan kasus baru dan tingkat pemulihan.
- Perbandingan jumlah kasus baru dan kematian.
- Analisis hubungan kepadatan penduduk dengan kasus COVID-19.

## 👥 Anggota Kelompok

- Dewanggi Erchinta Dwi Putri
- Nuri Maulidyatul Haliza
- Naila Alya Furqon

**Kelas:** 2024B  
**Kelompok:** 2

## 📚 Konteks Akademik

Project ini disusun untuk memenuhi tugas UAS mata kuliah Data Mining pada Program Studi Sains Data.

