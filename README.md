# Project_People_Analytics
👥 People Analytics: Employee Job Satisfaction\
📖 Deskripsi\
Proyek ini bertujuan untuk menganalisis faktor-faktor yang mempengaruhi kepuasan kerja karyawan berdasarkan dataset People Analytics. Beberapa faktor utama yang dianalisis mencakup work-life balance, lingkungan kerja, beban kerja, tingkat stres, dan jumlah jam tidur.

🎯 Tujuan Analisis
✅ Menentukan faktor yang paling berpengaruh terhadap job satisfaction (rating 1-5).\
✅ Mengetahui karakteristik karyawan dengan tingkat kepuasan tinggi (4-5) dan rendah (1-3).\
✅ Memberikan wawasan tentang hubungan antara work-life balance, tingkat stres, dan job satisfaction.

📂 Dataset\
Dataset ini berisi informasi karyawan dengan atribut berikut:\
Demografi: Gender, usia, status pernikahan, tingkat pendidikan.\
Pekerjaan: Level pekerjaan, tipe pekerjaan, departemen, pengalaman kerja.\
Lingkungan Kerja: Work-life balance (wlb), kepuasan lingkungan kerja, beban kerja, tingkat stres.\
Kebiasaan Keseharian: Jam tidur, aktivitas fisik, moda transportasi ke kantor, jarak perjalanan.\
Faktor Organisasi: Jumlah anggota tim, jumlah laporan langsung, pelatihan per tahun.\
Target Variabel: Job satisfaction (skala 1-5).

🔍 Exploratory Data Analysis (EDA)\
Analisis yang dilakukan meliputi:
1. Pengecekan Data: Melihat missing values, outlier, dan deskripsi statistik dataset.
2. Korelasi Antar Variabel: Menggunakan matrix correlation untuk melihat hubungan antar fitur.

Visualisasi Data:
1. Boxplot untuk melihat distribusi job satisfaction berdasarkan work-life balance (wlb).
2. Heatmap untuk mengidentifikasi fitur yang berkorelasi kuat dengan job satisfaction.

📊 Hasil Analisis
1. Work-life balance memiliki korelasi positif dengan job satisfaction:
  Karyawan dengan work-life balance tinggi (rating 4-5) cenderung lebih puas dengan pekerjaannya.
2. Stres kerja yang tinggi berdampak negatif terhadap job satisfaction:
Karyawan dengan tingkat stres tinggi (rating 4-5) lebih banyak memiliki job satisfaction rendah.
3. Jam tidur berhubungan dengan kepuasan kerja:
Karyawan yang tidur lebih banyak cenderung memiliki job satisfaction lebih tinggi.

🛠 Teknologi yang Digunakan
1. Python
2. Pandas & NumPy (manipulasi data)
3. Matplotlib & Seaborn (visualisasi data)
4. Google Colab (eksekusi notebook)
