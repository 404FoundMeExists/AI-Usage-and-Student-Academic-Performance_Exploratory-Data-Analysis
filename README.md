Analisis Penggunaan AI dan Kinerja Akademik Siswa

* Deskripsi Proyek
proyek ini dibuat untuk menganalisis pengaruh penggunaan Artificial Intelligence (AI)
terhadap kinerja akademik siswa menggunakan dataset publik dari kaggle. analisis ini
difokuskan pada perbandingan nilai akademik sebelum dan sesudah penggunaan AI, serta
ekspolaris pola berdasarkan tujuan penggunaan AI dan durasi penggunaan harian.
pendekatan yang digunakan dalam proyek ini adalah analisis deskriptif eksploratif
(Exploratory Data Analysis / EDA).

* Sumber Data
https://www.kaggle.com/datasets/aminasalamt/students-ai-usage-and-academic-performance

* Tujuan Analisis
  1. membandingkan nilai akademik sebelum dan sesudah penggunaan AI
  2. mengukur rata-rata kenaikan nilai setelah penggunaan AI
  3. perbedaan kenaikan nilai berdasarkan tujuan penggunaan AI

* Data Preparation
  1. penamaan ulang kolom agar lebih konsisten dan mudah dipahami
  2. pengecekan tipe data dan missing values
  3. pemisahaan data siswa yang mengenakan AI
Jumlah data yang dianalisis pada tahap utama
- 40 siswa pengguna AI

* Ringkasan Analisis
  1. Perbandingan nilai sebelum dan sesudah menggunakan AI
     - Rata-rata nilai sebelum AI : 65,33
     - Rata-rata sesudah AI : 75,15
     - Rata-rata kenaikan nilai : 9,83 point
     ! seluruh siswa pengguna AI mengalami kenaikan nilai
  2. Analisis berdasarkan tujuan penggunaan AI
     - 14 siswa untuk tujuan penggunaan Ai untuk Research rerata kenaikan nilai : 10,29
     - 13 siswa pengunaan Ai untuk coding rerata kenaikan nilai : 10,00
     - 13 siswa untuk Homework dengan rerata kenaikan nilai : 9,15
     ! penggunaan AI untuk Research dan Coding menunjukan rerata kenaikan nilai yang sedikit lebih tinggi, sedangkan
     ! penggunaan AI untuk Homework cenderung lebih konsisten, namun dengan kenaikan nilai yang lebih rendah
  3. Durasi penggunaan AI dan waktu layar harian
     - rerata penggunaan perhari : 2,83 jam
     - rerata waktu layar harian : 4,48 jam
     ! kenaikan nilai tidak menunjukkan hubungan linear dengan durasi penggunaan AI.
     ! Waktu layar harian yang lebih tinggi tidak selalu diikuti oleh peningkatan nilai.

* Insight Utama
  - penggunaan AI cenderung berkaitan dengan oeningkatan nilai akademik
  - tujuan penggunaan AI berpengaruh terhadap besarnya kenaikan nilai

* Tools & Teknologi
  - Python
  - Pandas
  - Google Colab
