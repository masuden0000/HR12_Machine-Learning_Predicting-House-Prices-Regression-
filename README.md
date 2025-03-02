# Machine Learning Regression Project

Data source: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
Proyek ini merupakan implementasi model regresi menggunakan beberapa algoritma machine learning untuk memprediksi nilai berdasarkan dataset yang diberikan. Model yang digunakan dalam proyek ini meliputi:
- **LARS (Least Angle Regression)**
- **Linear Regression**
- **Gradient Boosting Regressor**

## 📌 Fitur
- Preprocessing data untuk memastikan kualitas data yang optimal sebelum training.
- Training dan evaluasi model regresi menggunakan metrik:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² Score**
- Perbandingan performa model berdasarkan hasil evaluasi.

## 🚀 Cara Menggunakan
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/repository-name.git
   cd repository-name
2. Instal dependensi yang diperlukan
   ```bash
   pip install -r requirements.txt
3. alankan notebook Jupyter
    ```bash
   jupyter notebook

## 📊 Hasil Evaluasi Model
Evaluasi model dilakukan dengan membandingkan beberapa algoritma regresi. Model yang digunakan antara lain:

- **LARS (Least Angle Regression)**
- **Linear Regression**
- **Gradient Boosting Regressor**

Masing-masing model diuji menggunakan dataset `x_test` dan `y_test`, kemudian dibandingkan menggunakan metrik evaluasi berikut:

```md
- **MAE (Mean Absolute Error)**: Mengukur rata-rata kesalahan absolut antara prediksi dan nilai sebenarnya.
- **MSE (Mean Squared Error)**: Mengukur rata-rata kuadrat dari kesalahan prediksi, memberikan penalti lebih besar pada kesalahan yang lebih besar.
- **R² Score**: Mengukur seberapa baik model menjelaskan variabilitas data, dengan nilai 1 menunjukkan model yang sempurna.

| Model                        | MAE       | MSE       | R² Score  |
|------------------------------|-----------|-----------|-----------|
| Least Angle Regression (LARS) | 0.720054  | 0.817625  | -0.018517 |
| Linear Regression            | 0.237356  | 0.095778  | 0.880690  |
| Gradient Boosting Regressor  | 0.217360  | 0.089055  | 0.889065  |

