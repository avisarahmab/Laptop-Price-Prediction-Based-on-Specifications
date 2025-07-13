# Judul Project
Prediksi Harga Laptop Berdasarkan Spesifikasinya


## Repository Outline

├── Conceptual.txt  : Permasalahan konseptual atau pertanyaan analisis yang ingin dijawab  
├── dataset_raw.csv : Data mentah yang diambil dari Kaggle sebelum diproses  
├── Main.ipynb      : Notebook utama berisi proses pengolahan data dan pemodelan  
├── Model_Inference.ipynb : Notebook untuk melakukan inferensi/prediksi menggunakan model  
├── README.md       : Dokumentasi utama yang menjelaskan proyek secara keseluruhan  


## Problem Background
1. Konsumen sering kesulitan menilai apakah harga laptop sesuai dengan spesifikasinya.
2. Memprediksi harga laptop berdasarkan spesifikasi dan fitur-fiturnya.

## Project Output

Output dari proyek ini berupa prediksi harga laptop berdasarkan input spesifikasi dan fitur-fitur yang dimiliki oleh laptop.


## Data

Sumber data dari kaggle: https://www.kaggle.com/datasets/owm4096/laptop-prices yang di mana terdapat 23 kolom dan 1275 baris dan tidak terdapat missing value.


## Method


Model Supervised Learning:
1. K-Nearest Neighbors (KNN) Regression
2. Support Vector Regression (SVR)
3. Decision Tree Regression
4. Random Forest Regreesion
5. GXBosst

Setelah explorasi dan evaluasi, untuk pemodelan menggunakan algoritma XGBoost.


## Stacks
Tools: 
- VSCode

Library: 
- Pandas
- Numpy
- Scipy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Pickle.

## Reference
Link Dataset: https://www.kaggle.com/datasets/owm4096/laptop-prices 
