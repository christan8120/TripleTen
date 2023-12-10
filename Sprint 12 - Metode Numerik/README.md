# Model Dengan Metode Gradient Boosting Untuk Memprediksi Harga Mobil

## Deskripsi
Sebuah perusahaan jual beli mobil bekas sedang mengembangkan aplikasi untuk menarik pembeli baru. Pada aplikasi tersebut, penjual mobil dapat dengan cepat mengetahui berapa nilai pasar dari mobil yang akan dijualnya. Oleh karena itu, mereka ingin sebuah model yang dapat memprediksi harga pasar sebuah mobil. 
Perusahaan meminta untuk memperhatikan kualitas, dan kecepatan model dalam menentukan prediksi dan pelatihan.

Pada proyek ini, saya mencoba istilah baru yang dipelajari saat prapemrosesan data. Seperti biasa dengan mengatasi nilai duplikat, nilai yang hilang, outlier, dan OHE dan feature scaling. Hal baru yang saya terapkan adalah feature extraction, atau menggabungkan fitur-fitur yang ada menjadi beberapa fitur atau dalam proyek ini menjadi 1 fitur. Tujuan dari feature extraction untuk mempercepat proses pelatihan model, dikarenakan banyaknya jumlah fitur setelah proses OHE dapat mempengaruhi waktu pelatihan. Proses feature extraction pada proyek ini menggunakan teknik PCA (Principal Component Analysis). 

Setelah itu, dilakukan proses pelatihan dan analisis model yang memiliki kualitas terbaik. Jumlah model yang dibuat diantaranya: 
- Linear Regression
- Decision Tree (dengan hyperparameter)
- Random Forest (dengan hyperparameter)
Dan dengan 3 algoritma gradient boosting berikut:
- LightGBM
- CatBoost
- XGBoost
Terakhir, adalah melakukan sanity check terhadap ke 6 model yang telah dibuat dengan menggunakan metrik RMSE untuk mengukur kualitas model.
