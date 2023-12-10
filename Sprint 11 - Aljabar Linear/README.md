# Evaluasi Masalah Pada Salah Satu Perusahaan Asuransi

## Deskripsi
Sebuah perusahaan asuransi ingin menggunakan machine learning untuk menyelesaikan beberapa masalah berikut: 
- Temukan klien yang mirip dengan kriteria klien tertentu. Tugas ini akan memudahkan perusahaan untuk melakukan pemasaran.
- Prediksi apakah klien baru kemungkinan akan mengambil klaim asuransi. Apakah prediksi model lebih baik daripada prediksi model dummy?
- Prediksi besaran klaim asuransi yang mungkin diterima klien baru menggunakan model regresi linear.

Pada projek ini, untuk menemukan klien yang mirip akan menggunakan algoritma KNN (K-Nearest Neighbor). Dengan memperhatikan feature scaling dan penggunaan metrik jarak Euclidean dan Manhattan. Serta membedakan hasil dari ke 4 kombinasi tersebut.

Selanjutnya, untuk menjawab masalah kedua, yaitu probabilitas klien baru akan mengambil asuransi juga menggunakan algoritma KNeighborsClassifier dengan 2 kombinasi yaitu tanpa feature scaling dan dengan feature scaling. 

Terakhir adalah pembuatan model dengan regresi linear. Proses pembuatan model pada kali ini harus memperhatikan data yang digunakan untuk pelatihan. Sehingga untuk sebelum proses pelatihan model dilakukan, perlu adanya proses data masking. Sebagai tambahan bahwa data masking tidak boleh mempengaruhi hasil dari kualitas model. Sehingga akan dibuat 2 model yang pertama adalah model tanpa data masking, dan kedua model dengan data masking untuk membandingkan 2 hasil tersebut apakah dengan melakukan data masking akan mempengaruhi kualitas dari model.