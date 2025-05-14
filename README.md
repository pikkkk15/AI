# Heart Disease Detection

Proyek ini bertujuan untuk memprediksi apakah seorang pasien memiliki penyakit jantung atau tidak berdasarkan data medis menggunakan algoritma klasifikasi.

## 📊 Jenis Masalah
Klasifikasi — Output berupa dua kelas: Mengidap penyakit jantung (1) atau tidak (0).

## 📁 Dataset
UCI Heart Disease Dataset

- Link Dataset: [UCI Repository](https://archive.ics.uci.edu/dataset/45/heart%2Bdisease)

## ⚙️ Tools dan Library
- Python
- Pandas
- Scikit-learn
- Matplotlib/Seaborn

## 🤖 Model yang Digunakan
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree Classifier

## 📉 Error Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

**Alasan Pemilihan Metric:**  
F1-score sangat penting pada kasus ini karena dataset bisa saja tidak seimbang. F1 menggabungkan precision dan recall menjadi satu metrik yang menunjukkan keseimbangan.

## 📈 Evaluasi dan Rekomendasi
Model Logistic Regression memiliki akurasi sekitar X% (ganti dengan nilai aktual).  
Rekomendasi:
- Lakukan cross-validation
- Imbangkan data jika imbalance (mis. SMOTE)
- Eksplorasi model seperti Random Forest atau XGBoost

## 📎 Link Notebook/Code
[Insert your GitHub Notebook URL here]
