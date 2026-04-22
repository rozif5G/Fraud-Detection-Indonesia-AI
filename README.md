# 💳 Credit Card Fraud Detection (Machine Learning)
## 📌 Deskripsi
Proyek ini mengembangkan sistem deteksi fraud pada transaksi kartu kredit menggunakan machine learning. Fokus utama adalah menangani data tidak seimbang, melakukan preprocessing, serta membangun model seperti Logistic Regression dan Random Forest serta Adaboost
## 🎯 Tujuan
- Mendeteksi transaksi fraud secara akurat
- Feature Enginering 
- Mengevaluasi performa model dengan metrik yang relevan
## ⚙️ Fitur Utama
- Data train dari file CSV
- Exploratory Data Analysis (EDA) menggunakan visualisasi
- Data preprocessing dan cleaning
- Training model Logistik Regression, Random Forest dan Adaboost
- Analisis feature importance
- Evaluasi model menggunakan metrik klasifikasi
## 📊 Dataset
Dataset berisi data transaksi kartu kredit (fraudTrain.csv) dengan berbagai fitur numerik dan kategorikal.
  
Beberapa fitur penting:
- Amount transaksi
- Informasi pelanggan
- Waktu transaksi
- Label fraud (target)
## 📊 Model Performance
| No | Model                | Macro Avg F1-score | Accuracy |
|----|---------------------|-------------------|----------|
| 1  | Logistic Regression | 0.513558          | 0.993754 |
| 2  | **🔥 Random Forest** | **0.917899**      | **0.998305** |
| 3  | AdaBoost            | 0.738575          | 0.995465 |

### 🔍 Insight
- 🔥 Random Forest memberikan performa terbaik dengan Macro F1-score tertinggi
- Model ensemble terbukti lebih efektif dibandingkan model linear
- Logistic Regression kurang optimal untuk dataset yang tidak seimbang

## 🛠️ Teknologi yang Digunakan
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
## 🚀 Cara Menjalankan
- Upload dataset ke environment (Google Colab / lokal)
- Pastikan path dataset sesuai:
