# Model Klasifikasi Untuk Rekomendasi Paket  

## Deskripsi
Sebuah perusahaan telekomunikasi memiliki data perilaku pelanggan, dan paket yang mereka gunakan. Karena perusahaan melihat banyak pengguna yang masih menggunakan paket lama, maka mereka ingin membuat sebuah model klasifikasi sederhana yang dapat merekomendasikan paket bulanan yang bisa dipakai oleh pengguna. 

Perusahaan menentukan ambang batas dimana model yang dibuat harus memiliki akurasi minimal 0.75. Untuk bisa membuat model dengan akurasi ideal, perlu membagi dataset menjadi 3 bagian yaitu 60% data train, 20% data validasi dan 20% data test. Berikutnya menentukan fitur dan target. Setelah itu, baru dilakukan pelatihan model dengan 3 algoritma yang berbeda, yaitu: 
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Dengan pengujian menggunakan data test, langkah terakhir adalah membuat kesimpulan model yang memiliki hasil akurasi terbaik dengan data test.