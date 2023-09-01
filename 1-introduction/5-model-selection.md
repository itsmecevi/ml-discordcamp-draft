__

# ID

**Which Model?**

* Logistic regression
* Decision Tree
* Neural network
* etc

* Data training (60%)
* Data validation (data testing 1: 20%)
* Data testing (data testing 2: 20%)

* Multi comparison problem: the issue of conducting multiple statistical tests or comparisons on a dataset

Dataset validasi tidak digunakan dalam pelatihan. Terdapat matriks fitur dan vektor y untuk kedua dataset pelatihan dan validasi. 
Model disesuaikan dengan data pelatihan, dan digunakan untuk memprediksi nilai y dari matriks fitur validasi.
Kemudian, nilai y yang diprediksi (probabilitas) dibandingkan dengan nilai y aktual.

Masalah perbandingan ganda (MCP): hanya secara kebetulan satu model bisa beruntung dan mendapatkan prediksi yang baik karena semuanya bersifat probabilistik.
Set tes dapat membantu menghindari MCP. Mendapatkan model terbaik dilakukan dengan dataset pelatihan dan validasi, sedangkan dataset tes digunakan untuk memastikan bahwa model terbaik yang diusulkan adalah yang terbaik.

Dalam ilmu data dan pembelajaran mesin, membagi dataset menjadi set pelatihan, validasi, dan pengujian memiliki beberapa tujuan penting yang membantu dalam membangun dan mengevaluasi model yang andal dan kokoh. Meskipun benar bahwa set pelatihan dan pengujian sangat penting, penambahan set validasi memberikan manfaat tambahan:

-Pengembangan dan Pemilihan Model: Set pelatihan digunakan untuk melatih parameter-model, sedangkan set validasi digunakan untuk menyetel hiperparameter dan membandingkan performa model yang berbeda

-Mencegah Overfitting: Overfitting terjadi ketika model belajar berkinerja baik pada data pelatihan tetapi tidak bergeneralisasi dengan baik pada data baru yang belum pernah dilihat. Set validasi membantu memonitor performa model pada data yang belum pernah dilihat sebelumnya. Jika sebuah model berkinerja baik pada set pelatihan tetapi buruk pada set validasi, mungkin ada overfitting. Penyesuaian dapat dilakukan terhadap kompleksitas model atau regularisasi untuk mengurangi overfitting.

-Menghindari Kebocoran Data: Kebocoran data terjadi ketika informasi dari set pengujian tanpa disengaja mempengaruhi model selama pelatihan. Tanpa set validasi terpisah, ada risiko bahwa Anda mungkin menggunakan wawasan dari set pengujian untuk menyetel model Anda, yang dapat menyebabkan estimasi performa yang terlalu optimis. Set validasi terpisah memastikan Anda tidak menggunakan informasi apa pun dari set pengujian sampai evaluasi akhir.

-Penilaian Performa Tidak Bias: Set pengujian berfungsi sebagai dataset yang benar-benar independen yang belum pernah dilihat oleh model sebelumnya. Ini memberikan perkiraan kinerja model yang tidak bias. Tanpa set validasi, ada bahaya membuat keputusan tentang perbaikan model berdasarkan performanya pada set pengujian, yang mengarah pada ekspektasi yang terlalu optimis tentang performa.

-Pengembangan Iteratif: Proses berulang dari pelatihan, validasi, dan pengujian memungkinkan Anda untuk membuat perbaikan bertahap pada model Anda. Anda dapat menyesuaikan arsitektur model, fitur, dan hiperparameter berdasarkan performa set validasi, lalu akhirnya mengevaluasi model Anda pada set pengujian yang tidak tersentuh.

Ringkasnya, inklusi set validasi selain set pelatihan dan pengujian sangat penting untuk pengembangan model yang tepat, penyetelan hiperparameter, dan penilaian tanpa bias terhadap performa generalisasi. Ini membantu mencegah overfitting, kebocoran data, dan ekspektasi yang terlalu optimis, sehingga menghasilkan model ilmu data dan pembelajaran mesin yang lebih andal dan kokoh (robust).

1. Bagi dataset menjadi pelatihan, validasi, dan tes. Misalnya, masing-masing 60%, 20%, dan 20%
2. Latih model-model
3. Evaluasi model-model
4. Pilih model terbaik
5. Terapkan model terbaik ke dataset tes
6. Bandingkan metrik kinerja validasi dan tes

Slide: https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-15-model-selection-process
