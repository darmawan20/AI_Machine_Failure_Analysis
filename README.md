# 🤖 AI Machine Failure Analysis

## Tujuan Project
Project ini bertujuan untuk **mendeteksi potensi kerusakan mesin** dengan mempelajari hubungan antara **tegangan (voltase)** dan **arus (ampere)** menggunakan model Machine Learning sederhana.

---

##  Deskripsi Singkat
Model AI ini belajar dari data tegangan dan arus mesin untuk memprediksi apakah mesin:
- ✅ **Normal**
- ⚠️ **Berpotensi Rusak**

Algoritma yang digunakan: **Decision Tree Classifier** dari pustaka `scikit-learn`.

---

## ⚙️ Teknologi yang Digunakan
- Python (Google Colab)
- Pandas (pengolahan data)
- NumPy
- Scikit-learn (Machine Learning)
- Matplotlib (visualisasi)

---

## 📊 Dataset
Dataset: **data_mesin.csv**

Kolom:
| Kolom | Deskripsi |
|--------|------------|
| `tegangan` | Nilai tegangan (Volt) |
| `arus` | Nilai arus (Ampere) |
| `status_mesin` | Label kondisi mesin (Normal / Rusak) |

---

## 🚀 Cara Menjalankan
1. Clone repository:
   ```bash
   git clone https://github.com/darmawan20/AI_Machine_Failure_Analysis.git
