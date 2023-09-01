__

# ID:

* CRISP-DM (Cross-industry standard process for data mining):
   * Business Understanding
   * Data Understanding
   * Data Preparation
   * Modeling
   * Evaluation
   * Deployment

* From problem understanding to deployment
* ML Project:
  * Understand the problem
  * Collect the data
  * Train the model
  * Use it
 
* [**Business Understanding**]:
    * Our user complain about spam
    * Analyze to what extent it is a problem
    * Will ML help?
    * If not: propose an alternative solution
    *  Define the goal:
        * Reduce the amount of spam messages, or
        * Reduce the amount of complains about spam
        * The goal has to be measurable: reduce the amount of spam by 50%
 

* [**Data Understanding**]:
  * We have a report spam button
  * Is the data behind this button good enough?
  * Is it realiable?
  * Do we track it correctly?
  * Is the dataset large enough?
  * Do we need to get more data?
  * Iterative process


* [**Data Preparation**]
  * Clean the data
  * Build the pipelines (Workflow)
  * Convert into tabular form




CRISP-DM, yang merupakan singkatan dari Cross-Industry Standard Process for Data Mining, adalah model proses standar terbuka yang menggambarkan pendekatan umum yang digunakan oleh para ahli data mining. 
Ini adalah model analitik yang paling banyak digunakan. Model ini dikonseptualisasikan pada tahun 1996 dan menjadi proyek Uni Eropa di bawah inisiatif pendanaan ESPRIT pada tahun 1997. 
Proyek ini dipimpin oleh lima perusahaan: Integral Solutions Ltd (ISL), Teradata, Daimler AG, NCR Corporation, dan OHRA, sebuah perusahaan asuransi:

1. **Pemahaman Bisnis**: Pertanyaan penting adalah apakah kita memerlukan Pembelajaran Mesin (ML) untuk proyek ini. Tujuan proyek harus dapat diukur.
2. **Pemahaman Data**: Menganalisis sumber data yang tersedia, dan memutuskan apakah lebih banyak data diperlukan.
3. **Persiapan Data**: Membersihkan data dan menghilangkan noise dengan menerapkan pipeline, dan data harus dikonversi ke dalam format tabular, sehingga dapat dimasukkan ke dalam ML.
4. **Modeling**: Melatih berbagai model dan memilih yang terbaik. Dengan mempertimbangkan hasil langkah ini, penting untuk memutuskan apakah perlu menambahkan fitur-fitur baru atau memperbaiki masalah data.
5. **Evaluasi**: Mengukur seberapa baik kinerja model dan apakah itu memecahkan masalah bisnis.
6. **Pengimplementasian**: Diluncurkan ke produksi untuk semua pengguna. Evaluasi dan pengimplementasian sering terjadi bersamaan - evaluasi secara online.


Penting untuk mempertimbangkan seberapa baik proyek ini dapat dipelihara.
Secara umum, proyek-proyek ML memerlukan banyak iterasi.

**Iterasi:**

* Mulai dengan yang sederhana
* Belajar dari umpan balik
* Meningkatkan segala aspek

  Slide: https://www.slideshare.net/AlexeyGrigorev/ml-zoomcamp-14-crispdm




