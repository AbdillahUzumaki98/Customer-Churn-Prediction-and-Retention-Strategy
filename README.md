# Customer Churn Prediction & Retention Strategy

## 📌 Project Overview
Proyek *data analytics end-to-end* ini bertujuan untuk mengatasi tingginya tingkat *customer churn* (55,4%) pada DhahanapuraNet, sebuah perusahaan penyedia layanan internet fiktif. Tingginya angka *churn* berdampak negatif pada penurunan pendapatan dan peningkatan biaya akuisisi pelanggan. 

**Objective:** Menurunkan *churn rate* sebesar 10% pada kuartal berikutnya melalui strategi retensi berbasis data.

## 🛠️ Tools & Technologies
* **Programming & Analysis:** Python (Pandas, Scikit-Learn) via Google Colab
* **Data Visualization:** Tableau
* **Machine Learning Model:** Logistic Regression

## 📊 Methodology
1. **Business Understanding:** Mendefinisikan masalah bisnis dan metrik evaluasi.
2. **Data Preparation:** Melakukan *data cleaning* dari *dataset* berisi >72.000 riwayat pelanggan.
3. **Exploratory Data Analysis (EDA):** Menganalisis korelasi antar variabel (seperti sisa kontrak, tagihan, dan penggunaan data) terhadap probabilitas *churn*.
4. **Predictive Modeling:** Membangun model **Logistic Regression** untuk memprediksi pelanggan yang berisiko.
5. **Recommendation:** Menyusun strategi retensi berdasarkan segmentasi tingkat risiko pelanggan.

## 📈 Key Results
* Model berhasil memprediksi *churn* dengan **Accuracy 88%** dan **Recall 90%**.
* Pelanggan **tanpa sisa kontrak (0 tahun)** memiliki *churn rate* yang sangat kritis (99,6%).
* Pelanggan berhasil diklasifikasikan menjadi tiga segmen risiko: **Aman (<50%), Waspada (50-80%), dan Bahaya (>80%)**.

## 💡 Business Recommendations
1. **Early Renewal Program:** Menawarkan perpanjangan kontrak lebih awal khusus untuk pelanggan dengan probabilitas *churn* >80% (Segmen Bahaya).
2. **Promo Bundling:** Memberikan penawaran paket *Internet + TV/Movie* kepada pelanggan segmen risiko tinggi yang saat ini hanya berlangganan paket internet dasar.
