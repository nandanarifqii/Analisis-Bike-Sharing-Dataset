# Proyek Analisis Data dengan Python : Analisis Bike Sharing Dataset - IDCamp 2023 x Dicoding
Mengerjakan Proyek Akhir dari "Belajar Analisis Data dengan Python" pada Platform Dicoding sebagai bagian dari Bootcamp IDCamp 2023 Indosat Ooredoo x Dicoding. 
Proyek analisis data ini membahas dataset tentang peminjaman sepeda, dengan fokus pada pemahaman pola penggunaan sepeda berdasarkan status hari dan variabel-variabel lain seperti jam, musim, suhu, kelembaban, dan kecepatan angin.
Dataset ini terdiri dari beberapa jenis data yang dapat diidentifikasi, antara lain:

Data Numerik:
- Temp (Suhu): Merupakan suhu yang dinormalisasi dalam skala Celsius. Nilainya dibagi menjadi 41 (maksimal).
- Atemp (Suhu Perasaan): Menyatakan suhu perasaan yang dinormalisasi dalam skala Celsius. Nilainya dibagi menjadi 50 (maksimal).
- Hum (Kelembaban): Merupakan tingkat kelembaban yang dinormalisasi. Nilainya dibagi menjadi 100 (maksimal).
- Windspeed (Kecepatan Angin): Menunjukkan kecepatan angin yang dinormalisasi. Nilainya dibagi menjadi 67 (maksimal).
- Casual (Pengguna Sepeda Sewaan Kasual): Menyatakan jumlah pengguna sepeda sewaan kasual.
- Registered (Pengguna Sepeda Sewaan Terdaftar): Menunjukkan jumlah pengguna sepeda sewaan yang terdaftar.
- Cnt (Total Peminjaman Sepeda): Merupakan jumlah total sepeda yang disewakan, termasuk pengguna kasual dan terdaftar.

Data Kategorikal:
- Season: Merupakan informasi tentang musim dalam tahun (1: musim semi, 2: musim panas, 3: musim gugur, 4: musim dingin).
- Year (Tahun): Menunjukkan tahun (0: 2011, 1: 2012).
- Month (Bulan): Memberikan informasi tentang bulan dalam setahun (1 hingga 12).
- Hour (Jam): Menunjukkan jam dalam sehari (0 hingga 23).
- Holiday (Hari Libur): Mengindikasikan apakah hari itu merupakan hari libur (1 jika ya, 0 jika tidak).
- Weekday (Hari dalam Seminggu): Menyatakan hari dalam seminggu.
- Workingday (Hari Kerja): Menunjukkan apakah hari itu merupakan hari kerja (1 jika ya, 0 jika tidak).
- Weathersit (Kondisi Cuaca): Memberikan informasi tentang kondisi cuaca (1: Cerah, sedikit awan, sebagian cerah, 2: Berkabut + mendung, berkabut + awan rusak, berkabut + sebagian cerah, berkabut, 3: Hujan ringan, petir, awan terpencar, hujan ringan + awan terpencar, 4: Hujan lebat, hujan es + petir + kabut, salju + kabut).

## Langkah Pengerjaan Proyek
- Menentukan Pertanyaan Bisnis
- Import Library
- Data Wrangling (Gathering, Assessing, Cleaning Data)
- Exploratory Data Analysis (EDA)
- Visualization & Explanatory Analysis
- Conclusion
- Membuat Dashboard sederhana dengan Streamlit (File dashboard.py)

## Documentation
![image](https://github.com/user-attachments/assets/35c2d4e9-04d5-4fa5-9cb9-6f0449ffdd51)

![image](https://github.com/user-attachments/assets/e74a9a72-b50b-4e54-ae30-1c08d6e52060)


## Kesimpulan
- Jumlah peminjaman sepeda cenderung lebih tinggi pada hari libur daripada pada hari kerja.
- Terdapat korelasi yang signifikan antara variabel seperti suhu, kelembaban, kecepatan angin, musim, dan kondisi cuaca dengan jumlah peminjaman sepeda.
- Analisis visual menunjukkan tren yang berbeda dalam peminjaman sepeda selama 24 jam dalam sehari, serta perubahan pola peminjaman sepeda selama musim yang berbeda dan dalam kondisi cuaca yang berbeda.
- Dengan pemahaman ini, perusahaan penyewaan sepeda dapat membuat keputusan yang lebih baik dalam merencanakan strategi pemasaran, alokasi sumber daya, dan peningkatan layanan untuk meningkatkan peminjaman sepeda dan meningkatkan keuntungan mereka.
