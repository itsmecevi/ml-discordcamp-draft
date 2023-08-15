__

**ENG:**

The differences between ML and Rule-Based systems is explained with the example of a spam filter.

Traditional Rule-Based systems are based on a set of characteristics (keywords, email length, etc.) that identify an email as spam or not. As spam emails keep changing over time the system needs to be upgraded making the process untractable due to the complexity of code maintenance as the system grows.

ML can be used to solve this problem with the following steps:
### 1. Get data
Emails from the user's spam folder and inbox gives examples of spam and non-spam.

### 2. Define and calculate features
Rules/characteristics from rule-based systems can be used as a starting point to define features for the ML model. The value of the target variable for each email can be defined based on where the email was obtained from (spam folder or inbox).

Each email can be encoded (converted) to the values of it's features and target.

### 3. Train and use the model
A machine learning algorithm can then be applied to the encoded emails to build a model that can predict whether a new email is spam or not spam. The predictions are probabilities, and to make a decision it is necessary to define a threshold to classify emails as spam or not spam.

__

**ID:**

Perbedaan antara sistem Pembelajaran Mesin (ML) dan sistem berbasis Aturan dijelaskan dengan contoh spam filter.

Sistem Berbasis Aturan tradisional didasarkan pada serangkaian karakteristik (kata kunci, panjang email, dll.) yang mengidentifikasi sebuah email sebagai spam atau bukan. Karena email spam terus berubah seiring waktu, sistem ini perlu ditingkatkan yang membuat prosesnya sulit seiring berkembangnya jenis spam dan karakteristiknya.

ML dapat digunakan untuk memecahkan masalah ini dengan langkah-langkah berikut:

1. Dapatkan data
Email dari folder spam dan kotak masuk pengguna memberikan contoh spam dan bukan spam.

2. Tentukan dan hitung fitur/karakter
Aturan/karakteristik dari sistem berbasis aturan dapat digunakan sebagai titik awal untuk mendefinisikan fitur-fitur bagi model ML. Nilai variabel target untuk setiap email dapat ditentukan berdasarkan dari mana email tersebut diperoleh (folder spam atau kotak masuk).

Setiap email dapat diubah (dikonversi) menjadi nilai-nilai fitur dan targetnya.

3. Latih dan gunakan model
Algoritma pembelajaran mesin (ML) kemudian dapat diterapkan pada email-email yang diubah menjadi nilai-nilai fitur untuk membangun model yang dapat memprediksi apakah email baru adalah spam atau bukan spam. Prediksinya berupa probabilitas, dan untuk membuat keputusan diperlukan untuk menentukan ambang batas (threshold) untuk mengklasifikasikan email sebagai spam atau bukan spam.


Slide: https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-12-ml-vs-rulebased-systems





