# Hacktiv8 Phase 1: Graded Challenge 3

Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada konsep Ensemble.

---

By [Rifky Aliffa](https://github.com/Penzragon)

## Dataset

Dataset yang digunakan pada project ini adalah dataset yang berisi data pasien yang memiliki penyakit gagal jantung. Dataset ini berisi 299 baris dengan 13 kolom yang diantaranya adalah age, anaemia, creatinine_phosphokinase, diabetes, ejection_fraction, dan masih banyak lagi. dataset dapat dilihat di [Kaggle](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data).

Keterangan kolom pada dataset ini adalah:

| Feature                  | Description                                                            |
| ------------------------ | ---------------------------------------------------------------------- |
| age                      | Age                                                                    |
| anaemia                  | Decrease of red blood cells or hemoglobin (boolean)                    |
| creatinine_phosphokinase | Level of the CPK enzyme in the blood (mcg/L)                           |
| diabetes                 | If the patient has diabetes (boolean)                                  |
| ejection_fraction        | Percentage of blood leaving the heart at each contraction (percentage) |
| high_blood_pressure      | If the patient has hypertension (boolean)                              |
| platelets                | Platelets in the blood (kiloplatelets/mL)                              |
| serum_creatinine         | Level of serum creatinine in the blood (mg/dL)                         |
| serum_sodium             | Level of serum sodium in the blood (mEq/L)                             |
| sex                      | Woman or man (binary)                                                  |
| smoking                  | If the patient smokes or not (boolean)                                 |
| time                     | Follow-up period (days)                                                |
| DEATH_EVENT              | If the patient deceased during the follow-up period (boolean)          |

## Objectives

**Graded Challenge 3** ini dibuat guna mengevaluasi konsep Ensemble Learning sebagai berikut:

- Mampu memahami konsep Ensemble dan Boosting
- Mampu mempersiapkan data untuk digunakan dalam model Random Forest dan Boosting.
- Mampu mengimplementasikan Random Forest dan Boosting untuk membuat prediksi.
