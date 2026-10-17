# Analisis dan Visualisasi Data Sampah Kampus Menggunakan Python

## Deskripsi Proyek

Proyek ini membahas pengolahan dan visualisasi data sampah di lingkungan
kampus menggunakan Python. Analisis dilakukan untuk melihat jumlah dan
berat sampah berdasarkan lokasi, jenis sampah, tanggal, cuaca,
aktivitas, serta kondisi tempat sampah. Hasil analisis disajikan dalam
bentuk grafik agar informasi dari data lebih mudah dipahami dan dapat
digunakan sebagai bahan evaluasi pengelolaan sampah di kampus.

## Tujuan

Tujuan proyek ini adalah: - Mengolah data sampah agar lebih terstruktur
dan siap dianalisis. - Mengetahui jenis sampah yang paling banyak
ditemukan. - Membandingkan jumlah sampah pada beberapa lokasi kampus. -
Mengamati perubahan berat sampah berdasarkan tanggal, cuaca, dan
aktivitas. - Menyajikan hasil analisis melalui visualisasi yang mudah
dibaca.

## Data yang Digunakan

Dataset berisi 150 catatan pengamatan pada periode 20 September sampai 9
Oktober 2026. Data memuat informasi mengenai tanggal, lokasi, jenis
sampah, berat, jumlah, cuaca, aktivitas, dan kondisi tempat sampah.
Pengolahan awal menunjukkan bahwa data yang dianalisis tidak memiliki
nilai kosong.

## Teknologi dan Library

Proyek ini menggunakan: - Python sebagai bahasa pemrograman. - pandas
untuk membaca dan mengolah data. - NumPy untuk mendukung operasi
numerik. - Matplotlib dan Seaborn untuk membuat visualisasi. - Jupyter
Notebook atau Google Colab sebagai lingkungan pengerjaan. - Microsoft
Excel sebagai sumber dataset.

## Persiapan

Pastikan Python atau Google Colab sudah tersedia. Jika menggunakan
lingkungan lokal, instal library yang diperlukan dengan perintah
berikut:

``` bash
pip install pandas numpy matplotlib seaborn openpyxl
```

Simpan file dataset di lokasi yang mudah diakses, lalu sesuaikan nama
file dan lokasi penyimpanannya pada kode program.

## Cara Menjalankan

1.  Buka notebook proyek melalui Jupyter Notebook atau Google Colab.
2.  Impor library yang digunakan.
3.  Baca dataset dari file Excel, khususnya lembar kerja `Data Bersih`.
4.  Periksa struktur data, tipe kolom, dan nilai kosong.
5.  Lakukan analisis sesuai kebutuhan.
6.  Jalankan kode visualisasi dan amati hasil grafik yang dihasilkan.

## Tahapan Analisis

Analisis dilakukan melalui beberapa tahap: 1. Membaca dan memahami
struktur dataset. 2. Memeriksa kelengkapan data serta memastikan kolom
dapat digunakan. 3. Menghitung ringkasan statistik, seperti jumlah
catatan, berat sampah, dan jumlah sampah. 4. Membandingkan berat sampah
berdasarkan lokasi dan jenisnya. 5. Mengamati perubahan berat sampah
berdasarkan tanggal, cuaca, aktivitas, dan kondisi tempat sampah. 6.
Membuat grafik untuk membantu membaca pola yang muncul dari data.

## Hasil dan Temuan Utama

Berdasarkan hasil pengolahan data: - Dataset terdiri dari 150 catatan
dengan total berat sampah sebesar 685,3 kg dan jumlah 9.710 item. -
Rata-rata berat sampah per catatan sekitar 4,57 kg. - Kantin menjadi
lokasi dengan berat sampah tertinggi, yaitu 316,6 kg. Lokasi berikutnya
adalah Lapangan sebesar 103,6 kg dan Gedung B sebesar 96,5 kg. - Sampah
plastik memiliki berat terbesar, yaitu 305,3 kg, diikuti sampah organik
sebesar 275,6 kg. Kedua jenis tersebut mencakup sekitar 84,7% dari total
berat sampah. - Berat sampah harian tertinggi tercatat pada 30 September
2026 sebesar 66,45 kg, sedangkan yang terendah tercatat pada 5 Oktober
2026 sebesar 15,07 kg. - Data menunjukkan korelasi Pearson sekitar 0,675
antara berat sampah dan jumlah item. Artinya, pada dataset ini, jumlah
item yang lebih besar cenderung berkaitan dengan berat sampah yang lebih
tinggi. - Kondisi tempat sampah yang tercatat penuh atau meluber cukup
sering ditemukan. Hal ini dapat menjadi perhatian dalam evaluasi jadwal
pemeriksaan dan pengangkutan sampah.

Temuan tersebut menggambarkan pola pada dataset yang digunakan. Hasil
ini tidak secara langsung membuktikan penyebab meningkatnya sampah,
sehingga diperlukan pengamatan tambahan apabila akan digunakan untuk
mengambil keputusan operasional.

## Kesimpulan

Analisis menunjukkan bahwa kantin merupakan lokasi dengan kontribusi
berat sampah terbesar, sementara plastik dan sampah organik menjadi
jenis sampah yang paling dominan. Visualisasi membantu memperlihatkan
perbedaan antar lokasi, jenis sampah, serta perubahan dari waktu ke
waktu. Hasil ini dapat menjadi dasar awal untuk menentukan lokasi yang
perlu mendapat perhatian lebih, memperbaiki pemantauan kondisi tempat
sampah, dan mempertimbangkan pemilahan sampah plastik serta organik.

## Informasi Proyek

**Nama:** Muhammad Revaldo Andiuka\
**NIM:** 2418034\
**Program Studi:** Teknik Informatika\
**Institusi:** Institut Teknologi Nasional Malang
