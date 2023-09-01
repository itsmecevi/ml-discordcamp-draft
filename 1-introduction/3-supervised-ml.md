__

# ID

* Supervised Machine Learning (SML): Data + Output => Model
* SML: Classification, Regression, Ranking
* Contoh:

  | Index | Tahun Produksi | Merk      | Speedometer | Warna   | Harga   |
|-------|----------------|-----------|-------------|---------|---------|
| 1     | 2020           | Toyota    | 30,000 km   | Hitam   | $25,000 |
| 2     | 2018           | Honda     | 45,000 km   | Putih   | $20,500 |


* Matriks Fitur (X): terdiri dari pengamatan atau objek (baris) dan fitur-fitur (kolom).
* Variabel Target (y): vektor dengan informasi target yang ingin kita prediksi. Untuk setiap baris X, terdapat nilai di y.

Model dapat diwakili sebagai fungsi g yang mengambil matriks X sebagai parameter dan mencoba untuk memprediksi nilai-nilai yang sesuai dengan target y. Perolehan fungsi g itulah yang disebut pelatihan atau training.

**Jenis-Jenis Masalah SML**
* Regresi: keluarannya adalah angka (harga mobil)
* Klasifikasi: keluarannya adalah kategori (contoh spam).
      * Binary: terdapat dua kategori.
      * Masalah multikelas: terdapat lebih dari dua kategori.
* Perankingan (Ordinal): keluarannya adalah skor besar yang terkait dengan item-item tertentu. Ini diterapkan dalam sistem rekomendasi.

Secara ringkas, PMB berkaitan dengan mengajari model dengan menunjukkan contoh-contoh berbeda, dan tujuannya adalah untuk menciptakan fungsi yang mengambil matriks fitur sebagai parameter dan membuat prediksi yang sesuai mungkin dengan target-target y.


Slide: https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-13-supervised-machine-learning
