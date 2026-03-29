# 🌸 Task 1 — Iris Flower Classification

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-2ea44f?style=for-the-badge)

</div>

---

## 📌 Objective

Train and compare multiple ML models to classify Iris flowers into three species —
**Setosa**, **Versicolor**, and **Virginica** — based on sepal and petal measurements.

---

## 📁 Files in This Folder

| File | Description |
|---|---|
| `CodeAlpha_IrisFlowerClassification.ipynb` | Complete notebook — EDA, models, results |
| `Iris.csv` | Dataset — 150 samples, 4 features, 3 classes |
| `model_results.csv` | Exported accuracy comparison of all 4 models |

---

## 📊 Dataset

| Property | Value |
|---|---|
| Samples | 150 (50 per class) |
| Features | SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm |
| Target | Species — Setosa, Versicolor, Virginica |
| Missing Values | None |
| Class Balance | Perfectly balanced |

---

## 🤖 Models & Results

| Model | Test Accuracy | CV Score (5-fold) |
|---|---|---|
| KNN (k=5) | 96.67% | 95.83% |
| Decision Tree | 96.67% | 94.17% |
| Logistic Regression | 96.67% | 96.67% |
| **Random Forest** ⭐ | **100.00%** | **97.50%** |

---

## 💡 Key Insights

1. **Setosa** is perfectly separable from the other two species
2. **Petal Length & Width** contribute over 90% of predictive importance
3. **Random Forest** achieved 100% accuracy — best overall model
4. All models scored ≥96% — confirming Iris as a clean benchmark dataset

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Upload `CodeAlpha_IrisFlowerClassification.ipynb`
3. Click **Runtime → Run All**
4. Upload `Iris.csv` when prompted
5. Done — all charts and results appear automatically!

---

*Part of [codealpha_tasks](../README.md) | CodeAlpha Data Science Internship | Intern: Duvva Sruthika*
