__

# ID

* Rules: Jika A>90, maka cumlaude, input=>rules=>output
* ML: input dan output=> rules
* Hasil dari rules adalah sebuah output, sedangkan hasil dari ML adalah rules, dimana rules tersebut untuk memahami pola/tren dari data
* Contohnya misal membedakan email spam/non-spam

ML dapat digunakan untuk memecahkan masalah pada studi email spam dengan langkah-langkah berikut:

1. Dapatkan data (Get data): Email dari folder spam dan kotak masuk pengguna memberikan contoh spam dan bukan spam.
2. Tentukan dan hitung fitur/karakter (Define and calculate features):
   
=>Aturan/karakteristik dari sistem berbasis aturan dapat digunakan sebagai titik awal untuk mendefinisikan fitur-fitur bagi model ML. 

=>Nilai variabel target untuk setiap email dapat ditentukan berdasarkan dari mana email tersebut diperoleh (folder spam atau kotak masuk). Setiap email dapat diubah (dikonversi) menjadi nilai-nilai fitur dan targetnya.

3. Latih dan gunakan model (Train and use the model):
   
Algoritma pembelajaran mesin (ML) kemudian dapat diterapkan pada email-email yang diubah menjadi nilai-nilai fitur untuk membangun model yang dapat memprediksi apakah email baru adalah spam atau bukan spam. Prediksinya berupa probabilitas, dan untuk membuat keputusan diperlukan menentukan ambang batas (threshold) untuk mengklasifikasikan email sebagai spam atau bukan spam.


Slide: https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-12-ml-vs-rulebased-systems





