# Model Regresi Untuk Prediksi Potensi Nasabah Akan Meninggalkan Bank  

## Deskripsi
Nasabah baru dari sebuah bank sedikit demi sedikit meninggalkan bank mereka setiap bulannya. Hal ini membuat pegawai dari bank tersebut memilih untuk mempertahankan nasabah lama. Dalam hal ini, mereka ingin sebuah model yang dapat memprediksi potensi seorang nasabah untuk meninggalkan bank dalam waktu dekat atau tidak. Bank memiliki data nasabah yang dapat digunakan sebagai bahan untuk membuat model regresi. 

Perusahaan menetapkan ambang batas dari kualitas model regresi yang harus dicapai adalah nilai F1 minimal 0,59. Sebelum memulai pembuatan model, perlu dilakukan pengecekan pada data yang dimiliki, atau prapemrosesan data yang meliputi pengecekan nilai duplikat, nilai yang hilang, dan tipe data yang tidak sesuai. Pada pembuatan model kali ini, dan masih dalam tahap prapemrosesan data, perlu dilakukan penyesuaian pada data kategorikal dengan menggunakan OHE (One Hot Encoding), dan penskalaan fitur (Feature Scaling) untuk menyeimbangkan kepentingan pada masing-masing fitur numerikal. 

Setelah prapemrosesan data selesai, langkah berikutnya adalah membagi dataset menjadi 3 bagian yaitu data train, data validasi dan data test. Lalu, pembuatan dan pelatihan model akan dilakukan dengan 2 langkah. Pertama pelatihan model tanpa memperhatikan ketidakseimbangan kelas (Imbalance Class) dan kedua pelatihan model setelah mengatasi ketidakseimbangan kelas. Untuk mengatasi ketidakseimbangan kelas, dilakukan 2 metode berikut:
- Upsampling
- Downsampling

Terakhir, dibuat perbandingan dari masing-masing model dengan menggunakan metrik F1 Skor. Setelah itu barulah sebuah kesimpulan dari model yang memiliki hasil F1 skor terbaik dengan dataset.

