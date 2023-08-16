__

# ENG

**Which model to choose?**

* Logistic regression
* Decision tree
* Neural Network
* Or many others

The validation dataset is not used in training. There are feature matrices and y vectors for both training and validation datasets. 
The model is fitted with training data, and it is used to predict the y values of the validation feature matrix. 
Then, the predicted y values (probabilities) are compared with the actual y values.

Multiple comparisons problem (MCP): just by chance one model can be lucky and obtain good predictions because all of them are probabilistic.
The test set can help to avoid the MCP. Obtaining the best model is done with the training and validation datasets, while the test dataset is used for assuring that the proposed best model is the best.

1. Split datasets in training, validation, and test. E.g. 60%, 20% and 20% respectively
2. Train the models
3. Evaluate the models
4. Select the best model
5. Apply the best model to the test dataset
6. Compare the performance metrics of validation and test

__

# ID

**Model Mana yang Harus Dipilih?**

* Regresi Logistik
* Pohon Keputusan (Decision Tree)
* Jaringan Saraf Tiruan (Neural Network)
* Atau banyak model lainnya

Dataset validasi tidak digunakan dalam pelatihan. Terdapat matriks fitur dan vektor y untuk kedua dataset pelatihan dan validasi. 
Model disesuaikan dengan data pelatihan, dan digunakan untuk memprediksi nilai y dari matriks fitur validasi.
Kemudian, nilai y yang diprediksi (probabilitas) dibandingkan dengan nilai y aktual.

Masalah perbandingan ganda (MCP): hanya secara kebetulan satu model bisa beruntung dan mendapatkan prediksi yang baik karena semuanya bersifat probabilistik.
Set tes dapat membantu menghindari MCP. Mendapatkan model terbaik dilakukan dengan dataset pelatihan dan validasi, sedangkan dataset tes digunakan untuk memastikan bahwa model terbaik yang diusulkan adalah yang terbaik.

1. Bagi dataset menjadi pelatihan, validasi, dan tes. Misalnya, masing-masing 60%, 20%, dan 20%
2. Latih model-model
3. Evaluasi model-model
4. Pilih model terbaik
5. Terapkan model terbaik ke dataset tes
6. Bandingkan metrik kinerja validasi dan tes

Slide: https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-15-model-selection-process
