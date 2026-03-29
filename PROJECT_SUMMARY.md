# 📋 Project Summary — CodeAlpha Data Science Internship

| | |
|---|---|
| **Intern** | Duvva Sruthika |
| **Domain** | Data Science |
| **Repository** | codealpha_tasks |
| **Tasks Completed** | Task 1 — Iris Flower Classification · Task 2 — Unemployment Analysis |
| **Tools** | Python, Scikit-learn, Pandas, Matplotlib, Seaborn, Google Colab |

---

## 🌸 Task 1 — Iris Flower Classification

### Problem
Given sepal and petal measurements, classify each Iris flower into one of 3 species:
Setosa, Versicolor, or Virginica.

### Approach
- Loaded `Iris.csv` (150 samples, 4 features, 3 balanced classes)
- Performed EDA: class distribution, pairplots, correlation heatmap, boxplots, violin plots
- Preprocessed: dropped Id column, label encoding, 80/20 stratified split, StandardScaler
- Trained 4 models: KNN, Decision Tree, Logistic Regression, Random Forest
- Evaluated: accuracy, 5-fold CV, confusion matrices, feature importance

### Results

| Model | Test Accuracy | CV Score |
|---|---|---|
| KNN (k=5) | 96.67% | 95.83% |
| Decision Tree | 96.67% | 94.17% |
| Logistic Regression | 96.67% | 96.67% |
| **Random Forest** ⭐ | **100.00%** | **97.50%** |

### Key Finding
Petal Length & Width are the dominant features (>90% importance).
Random Forest achieved perfect accuracy with the highest cross-validation robustness.

---

## 📊 Task 2 — Unemployment Analysis

### Problem
Analyze unemployment trends across Indian states and regions, with focus on
COVID-19 impact, rural vs urban differences, and region-wise disparities.

### Datasets
- `Unemployment_in_India.csv` — 768 records, 28 states, Rural/Urban split, 2019–2020
- `Unemployment_Rate_upto_11_2020.csv` — 267 records, with region classification and coordinates

### Approach
- Cleaned and standardized both datasets (stripped spaces, parsed dates, renamed columns)
- National trend analysis with COVID-19 period highlighted
- Rural vs Urban comparison over time
- Region-wise and state-wise bar charts and heatmaps
- COVID impact analysis: Pre vs During vs Post
- Labour participation scatter plot by state and region
- Monthly seasonality analysis

### Key Findings

| Finding | Insight |
|---|---|
| COVID spike | Unemployment rose from ~8% to 23%+ in Apr–May 2020 |
| Rural vs Urban | Urban unemployment spiked more sharply during lockdown |
| Worst regions | North & East India — consistently highest rates |
| Best regions | South & West India — Gujarat, Goa, Tamil Nadu lowest |
| Hidden unemployment | States with low labour participation mask true joblessness |

---

## 🎓 Internship Benefits

1. **Hands-On ML Experience** — Applied real classification algorithms on industry datasets
2. **Data Storytelling** — Derived insights through EDA, trend analysis, and visualizations
3. **Professional Standards** — Clean code, documentation, exported results, proper project structure

---

*Completed as part of CodeAlpha Data Science Internship | Intern: Duvva Sruthika*
