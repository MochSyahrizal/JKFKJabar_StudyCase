# JKFKJabar_StudyCase

### Table of Contents
- [Study Case Overview](#Study-Case_Overview)
- [Tools](#Tools)
- [Key Questions](#Key_Questions)
- [Findings](#Findings)
- [Recommendations](#Recommendations)
- [Creating Dashboard](#Creating-Dashboard)


### Study Case Overview

Ini adalah repositori pertama saya di Github dan saya baru mencoba platform ini pertama kali. Study case ini diberikan oleh platfrom pembelajaran online yaitu RevoU. Dalam study case ini aaya diberikan brief sebagai berikut, Anda adalah seorang Analis Data di Pemerintah Provinsi Jawa Barat. Anda diminta untuk membuat dashboard tentang Jaminan dan Jumlah Fasilitas Kesehatan di Jawa Barat untuk mengevaluasi kondisi fasilitas kesehatan dan layanan kesehatan di setiap Kabupaten/Kota di Jawa Barat. Buatlah dashboard menggunakan dataset di bawah ini:

Jumlah Fasilitas Kesehatan di Jawa Barat: [Jumlah Faskes Jabar.xlsx](https://github.com/user-attachments/files/16490270/Jumlah.Faskes.Jabar.xlsx)

Jaminan Kesehatan di Jawa Barat:[Jaminan Kesehatan Jabar.xlsx](https://github.com/user-attachments/files/16490273/Jaminan.Kesehatan.Jabar.xlsx)


### Tools

- Google Spreadsheets - Data Checking / Overview
- Tableau Public - Exploratory Data Analysis, Visualization, Creating Dashboard
- Canva - Designing Presentation


### Key Questions
1. Berapa total fasilitas kesehatan di Provinsi Jawa Barat?
2. Berapa total penduduk yang memiliki jaminan kesehatan di Provinsi Jawa Barat?
3. Bagaimana perbandingan keseluruhan fasilitas kesehatan di setiap jenisnya?
4. Bagaimana perbandingan keseluruhan jenis jaminan kesehatan di setiap jenisnya?
5. Bagaimana korelasi antara jumlah jaminan kesehatan dengan fasilitas kesehatan di Provinsi Jawa Barat?


### Findings

![scatter plot](https://github.com/user-attachments/assets/297c90f5-7435-4244-ae9d-edb2ac67f239)

- Trend line menunjukan setingkat dengan banyaknya jumlah pemegang jaminan kesehatan, maka jumlah fasilitas kesehatan pun semakin banyak (secara keseluruhan) di Provinsi Jawa Barat
- Ada banyak perbedaan signifikan dari jumlah penduduk dengan jaminan kesehatan dan juga jumlah fasilitas kesehatan antara beberapa kab/kota di Jawa Barat
- Kabupaten Bogor menjadi daerah dengan jumlah penduduk dengan jaminan kesehatan dan juga fasilitas kesehatan terbanyak di Provinsi Jawa Barat (Menurut Datasets)
- PENERIMA BANTUAN IURAN (PBI) APBN menjadi jumlah jenis jaminan kesehatan terbanyak di Jawa Barat dengan total 15.363.531 (43.4%) jiwa pemegang jaminan kesehatan

### Recommendations
- Perlunya menganalisa lebih lanjut antara pemegang jaminan kesehatan dengan keseluruhan jumlah penduduk di setiap Kab/Kota di Jawa Barat
- Perlu mengidentifikasi bagaimana kemampuan menampung dan menangani rata-rata pasien semua fasilitas kesehatan, untuk memastikan standar jumlah fasilitas kesehatan dengan jumlah penduduknya baik dengan pemegang jaminan kesehatan atau bukan
- Mencoba mengidentifikasi lebih lanjut apakah ketimpangan pemegang jenis jaminan kesehatan adalah hal yang wajar atau tidak dengan menganalisa lebih dalam setiap jenis jaminan juga data demografis penduduk secara keseluruhan
- Perlunya menindaklanjuti mengapa di daerah tertentu cenderung memiliki jumlah sedikit penduduk dengan jaminan kesehatan dan juga fasilitas kesehatan


### Creating Dashboard

![Diagram Tanpa Judul drawio](https://github.com/user-attachments/assets/31eec1fb-bcb6-4c9d-a16c-469eed48ca48)

Dashboard ingin saya buat simple, clean dan to the point menampilkan jumlah penduduk per jenis jaminan kesehatan dan juga jumlah fasilitas kesehatan per daerah. Penjelasan singkat mengenai dashboard :
- Disertai fitur filter agar user dapat memilih data berdasarkan daerah kab/kota, jenis jaminan kesehatan dan jenis fasilitas kesehatan
- Score card total keseluruhan kab/kota, jumlah penduduk dan jumlah faskes yang ditampilkan
- Map memberikan gambaran besaran kuantitas per daerah
- Diagram bar chart perbandingan untuk mempermudah visual perbandingan antara jenis

[Link to dashboard at tableau public](https://public.tableau.com/views/JaminanKesehatandanFasilitasKesehatanProvinsiJawaBarat_17219631108560/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
