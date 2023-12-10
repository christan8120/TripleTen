# Prediksi Permintaan Taxi

## Deskripsi
Sebuah perusahaan taxi memiliki data jumlah pesanan taxi dalam setiap 10 menit. Mereka bertujuan untuk mengumpulkan lebih banyak pengemudi pada jam-jam sibuk untuk menerima pelanggan. Oleh sebab itu, mereka mau membuat sebuah model yang dapat memprediksi jumlah pesanan taxi untuk 1 jam kedepan. 

Karena data yang dimiliki tersedia dalam waktu jumlah pemesanan setiap 10 menit, perlu dilakukan proses resample pada data tersebut agar menampilkan total pesanan dalam setiap 1 jam. Berikutnya, kita perlu melakukan analisa data tersebut untuk melihat tren pemesanan taxi. Tujuannya untuk mengetahui apakah ada pola tertentu seperti jam-jam tertentu dimana pemesanan taksi memiliki peningkatan. 

Setelah proses analisa, karena hanya terdapat data tanggal dan jumlah order, dimana jumlah order sendiri adalah target, maka perlu dibuat beberapa fitur yang bisa memprediksi jumlah order tersebut. Fitur tersebut diawali dengan membagi data tanggal menjadi beberapa bagian yaitu tahun, bulan, tanggal, hari dan jam. Lalu, melihat jumlah pemesanan taxi dari beberapa jam sebelumnya. Dan terakhir menentukan rata-rata dan jumlah pemesanan taxi dari beberapa jam sebelumnya. Pada proyek ini, saya melihat jumlah dan rata-rata pemesanan taxi dari 4 jam sebelumnya, sehingga total terdapat 11 fitur untuk memprediksi jumlah pemesanan di jam berikutnya. 

Sebelum melakukan proses pelatihan model, sedikit berbeda dari sebelumnya, karena data yang kita miliki merupakan waktu yang berurutan, maka proses pemisahan data train (90%) dan test (10%) haruslah berurutan. Setelah itu, pembuatan model dilakukan dengan menggunakan 6 model diantaranya: 
- Linear Regression
- Decision Tree
- Random Forest 
- LightGBM
- CatBoost
- XGBoost
Terakhir adalah menyimpulkan model mana yang memiliki nilai RMSE paling rendah, dengan menampilkan grafik hasil sanity check untuk membandingkan nilai sebenarnya dengan nilai prediksi. 