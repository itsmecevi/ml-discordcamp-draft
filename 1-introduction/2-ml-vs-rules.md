__

# ID

Perbedaan antara sistem Pembelajaran Mesin (ML) dan sistem berbasis Aturan dijelaskan dengan contoh spam filter.

Sistem Berbasis Aturan tradisional didasarkan pada serangkaian karakteristik (kata kunci, panjang email, dll.) yang mengidentifikasi sebuah email sebagai spam atau bukan. Karena email spam terus berubah seiring waktu, sistem ini perlu ditingkatkan yang membuat prosesnya sulit seiring berkembangnya jenis spam dan karakteristiknya.

ML dapat digunakan untuk memecahkan masalah ini dengan langkah-langkah berikut:

1. Dapatkan data (Get data):
   
Email dari folder spam dan kotak masuk pengguna memberikan contoh spam dan bukan spam.

2. Tentukan dan hitung fitur/karakter (Define and calculate features):
   
Aturan/karakteristik dari sistem berbasis aturan dapat digunakan sebagai titik awal untuk mendefinisikan fitur-fitur bagi model ML. Nilai variabel target untuk setiap email dapat ditentukan berdasarkan dari mana email tersebut diperoleh (folder spam atau kotak masuk). Setiap email dapat diubah (dikonversi) menjadi nilai-nilai fitur dan targetnya.

3. Latih dan gunakan model (Train and use the model):
   
Algoritma pembelajaran mesin (ML) kemudian dapat diterapkan pada email-email yang diubah menjadi nilai-nilai fitur untuk membangun model yang dapat memprediksi apakah email baru adalah spam atau bukan spam. Prediksinya berupa probabilitas, dan untuk membuat keputusan diperlukan untuk menentukan ambang batas (threshold) untuk mengklasifikasikan email sebagai spam atau bukan spam.


Slide: https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-12-ml-vs-rulebased-systems





