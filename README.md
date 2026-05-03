# Perbandingan Performa Algoritma Machine Learning dalam Prediksi Harga Retail

## Overview
Proyek ini bertujuan untuk mengevaluasi efektivitas model *machine learning* dalam memprediksi harga produk retail hanya berdasarkan atribut produk seperti *brand*, *category*, *color*, *size*, dan *material*.

Fokus utama bukan hanya pada performa model, tetapi juga untuk memahami apakah dataset memiliki *predictive signal* yang cukup.

---

##  Key Findings
- Performa model hampir sama dengan baseline (*Dummy Regressor*)
- Tidak ada fitur yang berpengaruh signifikan terhadap harga
- Model kompleks (*Random Forest, LightGBM*) tidak meningkatkan performa
- Data menunjukkan hubungan yang lemah antara fitur dan target

---

##  Model yang Digunakan
- Dummy Regressor  
- ElasticNet  
- Random Forest  
- LightGBM  
- Stacking  

---

## Ringkasan Hasil

| Model | RMSE | MAE | R² |
|------|------|-----|----|
| Dummy | 54.16 | 46.18 | -0.0010 |
| ElasticNet | 54.05 | 46.18 | 0.0031 |
| Random Forest | 57.48 | 48.07 | -0.1275 |
| LightGBM | 56.79 | 47.80 | -0.1004 |
| Stacking | 54.13 | 46.15 | 0.0000 |

