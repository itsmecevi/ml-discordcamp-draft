__

# ID

Dalam Pembelajaran Mesin Terawasi / Supervised Machine Learning (SML), selalu ada label yang terkait dengan fitur-fitur tertentu. Model dilatih, dan kemudian dapat membuat prediksi pada fitur-fitur baru. Dengan cara ini, model diajari oleh fitur-fitur dan target-target tertentu.

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
