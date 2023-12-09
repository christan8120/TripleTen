# Analisa Perilaku Pengguna Paket Prabayar

## Tujuan
Sebuah perusahaan telekomunikasi menyediakan 2 paket prabayar, yaitu paket Surf dan Ultimate. Mereka ingin mengetahui paket mana yang menghasilkan lebih banyak pendapatan untuk mereka. 

Perusahaan tersebut menyediakan 5 data untuk dianalisa. Proses ini menggunakan bahasa Python. Pertama, dilakukan pra pemrosesan data yaitu mengecek dan mengatasi nilai duplikat dan nilai yang hilang bila ada, mengubah tipe data, dan menambah data yang diperlukan untuk keperluan analisa.

Setelah pra pemrosesan selesai, berikutnya adalah proses analisa data dengan visualisasi data seperti histogram, bar chart, dan melihat total pendapatan dari masing-masing paket di setiap bulannya. Dengan membandingkan beberapa point tersebut, dapat dibuat kesimpulan terkait paket mana yang memberikan jumlah keuntungan yang lebih banyak. 

Catatan tambahan, untuk menemukan total pendapatan, perlu dilakukan beberapa perhitungan karena setiap paket ada dikenakan biaya berikut:
- Paket Surf
  - Biaya bulanan: $20
  - 500 menit durasi panggilan per bulan, 50 SMS, dan 15 GB data
  - Setelah melebihi batas paket, akan dikenakan:
    - 1 menit: 3 sen
    - 1 SMS: 3 sen
    - 1 GB data: $10
- Paket Ultimate
  - Biaya bulanan: $70
  - 3000 menit durasi panggilan per bulan, 1000 SMS, dan 30 GB data
  - Setelah melebihi batas paket, akan dikenakan:
    - 1 menit: 1 sen
    - 1 SMS: 1 sen
    - 1 GB data: $7
   
Setelah semua data dieksplorasi, terakhir adalah menguji hipotesis berikut: 
- Rata-rata pendapatan dari pengguna paket telepon Ultimate dan Surf berbeda.
- Rata-rata pendapatan dari pengguna di wilayah NY-NJ berbeda dengan pendapatan pengguna dari wilayah lain.
