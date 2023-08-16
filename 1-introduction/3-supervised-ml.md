__

**ENG:**

In Supervised Machine Learning (SML) there are always labels associated with certain features. The model is trained, and then it can make predictions on new features. In this way, the model is taught by certain features and targets.

* Feature matrix (X): made of observations or objects (rows) and features (columns).
* Target variable (y): a vector with the target information we want to predict. For each row of X there's a value in y.

The model can be represented as a function g that takes the X matrix as a parameter and tries to predict values as close as possible to y targets. The obtention of the g function is what it is called training.

### Types of SML problems

* Regression: the output is a number (car's price)
* Classification: the output is a category (spam example).
    * Binary: there are two categories.
    * Multiclass problems: there are more than two categories.
* Ranking (Ordinal): the output is the big scores associated with certain items. It is applied in recommender systems.

In summary, SML is about teaching the model by showing different examples, and the goal is to come up with a function that takes the feature matrix as a parameter and makes predictions as close as possible to the y targets.

__

**ID:**

Dalam Pembelajaran Mesin Terawasi / Supervised Machine Learning (SML), selalu ada label yang terkait dengan fitur-fitur tertentu. Model dilatih, dan kemudian dapat membuat prediksi pada fitur-fitur baru. Dengan cara ini, model diajari oleh fitur-fitur dan target-target tertentu.

* Matriks Fitur (X): terdiri dari pengamatan atau objek (baris) dan fitur-fitur (kolom).
* Variabel Target (y): vektor dengan informasi target yang ingin kita prediksi. Untuk setiap baris X, terdapat nilai di y.

Model dapat diwakili sebagai fungsi g yang mengambil matriks X sebagai parameter dan mencoba untuk memprediksi nilai-nilai yang sesuai dengan target y. Perolehan fungsi g itulah yang disebut pelatihan atau training.

### Jenis-Jenis Masalah SML
* Regresi: keluarannya adalah angka (harga mobil)
* Klasifikasi: keluarannya adalah kategori (contoh spam).
      * Binary: terdapat dua kategori.
      * Masalah multikelas: terdapat lebih dari dua kategori.
* Perankingan (Ordinal): keluarannya adalah skor besar yang terkait dengan item-item tertentu. Ini diterapkan dalam sistem rekomendasi.

Secara ringkas, PMB berkaitan dengan mengajari model dengan menunjukkan contoh-contoh berbeda, dan tujuannya adalah untuk menciptakan fungsi yang mengambil matriks fitur sebagai parameter dan membuat prediksi yang sesuai mungkin dengan target-target y.
