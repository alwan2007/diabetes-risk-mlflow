# Diabetes Risk Prediction & Model Tracking with MLflow

## Project Overview
Proyek ini bertujuan untuk menganalisis data kesehatan dan membangun model Machine Learning untuk memprediksi tingkat risiko diabetes. Proyek mencakup alur *end-to-end* dari pemrosesan data, *feature engineering*, hingga pelatihan model dan *experiment tracking* menggunakan **MLflow**.

## Workflow & Methodology
1. **Data Preprocessing & Feature Engineering**:
   - Eksplorasi struktur dataset diabetes.
   - Pembuatan variabel biner `Risk` berbasis *threshold* persentil ke-75 dari variabel target.
2. **Model Training**:
   - **Linear Regression**: Memprediksi nilai skor kontinyu ($Y$).
   - **Logistic Regression**: Memprediksi kelas tingkat risiko (`Risk`).
3. **Experiment Tracking**:
   - Pencatatan otomatis metrik evaluasi, parameter, dan artefak model menggunakan `MLflow`.

## Tech Stack
- **Language**: Python
- **Libraries**: Pandas, Scikit-Learn, MLflow
- **Environment**: Google Colab / Jupyter Notebook
