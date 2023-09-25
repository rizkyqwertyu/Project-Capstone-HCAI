# Project-Capstone-HCAI

## Infinite Learning ##

|     Keterangan    |               Data               |
| ------------------|----------------------------------|
| Nama              | Lalu Rizky Danu Saputra          |
| Asal Provinsi     | Nusa Tenggara Barat              |
| Perguruan Tinggi  | Universitas Mataram              |
| Fakultas          | Teknik                           |
| Prodi             | Teknik Informatika               |


## Keterangan Projek ##

### Dataset Diabetes
Dataset ini diambil dari website kaggle, link = https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes

![architecture](Gambar/Dataset.png)

![architecture](Gambar/Informasi-dataset.png)

### Pattern yang dipakai dari IBM Developer AI
   
![architecture](Gambar/Pattern-dipakai.png)

### Flow

![architecture](Gambar/FLOWCHART.png)

1. Pengguna mengirimkan percobaan AutoAI menggunakan pengaturan default.
2. Beberapa model pipeline dihasilkan. Model pipeline pilihan dari papan peringkat disimpan sebagai buku catatan Jupyter.
3. Notebook Jupyter dijalankan dan model pipeline yang dimodifikasi dibuat di dalam notebook.
4. Model pipeline digunakan di Watson Machine Learning menggunakan API WML.

## Komponen

* [IBM Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) 
* [IBM Watson Machine Learning](https://cloud.ibm.com/catalog/services/machine-learning) 

## Hasil 

![architecture](Gambar/Relationship-map.png)

![architecture](Gambar/Pipeline-leaderboard.png)

![architecture](Gambar/Metric-chart.png)

![architecture](Gambar/ROC-curve.png)

![architecture](Gambar/Model-evaluation-measure.png)

![architecture](Gambar/Confusion-matrix.png)

## Kesimpulan 

Berdasarkan hasil Predict diabetes with pipeline models using AutoAI, dapat disimpulkan bahwa:

+ Algoritma yang digunakan adalah XGB Classifier. Algoritma ini telah terbukti efektif dalam memprediksi seseorang mengalami diabetes atau tidak.

+ Model yang dikembangkan dengan menggunakan algoritma tersebut mencapai tingkat akurasi sebesar 0.993 Angka ini menunjukkan bahwa model machine learning tersebut memiliki kemampuan yang baik dalam mengklasifikasikan pengidap diabetes tipe 2 atau tidak.

+ Dilakukan beberapa peningkatan (enhancements) pada model, yaitu 1st dan 2nd Hyperparameter Optimization serta Feature Engineering. Peningkatan ini membantu meningkatkan performa model dengan mengoptimalkan parameter dan mengubah fitur yang digunakan.

Dengan hasil tersebut, studi ini memberikan pemahaman yang lebih baik tentang hubungan antara BMI, Glucose, dan BloodPress. Model yang dikembangkan memiliki tingkat akurasi yang tinggi dan telah mengalami peningkatan melalui proses optimisasi parameter dan rekayasa fitur. Implikasinya, model ini dapat digunakan sebagai alat yang berguna dalam memprediksi dan memahami penyebab terbesar diabetes.
