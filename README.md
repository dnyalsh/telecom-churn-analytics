# 📉 Telecom Customer Churn Analytics

Statistical analysis and machine learning pipeline to identify and predict customer churn for a telecom provider.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success)

---

## 📊 Results

| Metric | Score |
|---|---|
| ROC AUC | **0.841** |
| Recall (churn class) | **78%** |
| Key churn drivers identified | **4** |

---

## 🔍 Project overview

Customer churn is one of the most costly challenges in the telecom industry — acquiring a new customer costs 5–25× more than retaining an existing one. This project:

1. Performs exploratory data analysis on telecom customer behaviour
2. Uses chi-squared statistical tests to validate key churn drivers
3. Builds and evaluates a Logistic Regression churn classifier
4. Translates findings into retention strategy recommendations

---

## 🔑 Key findings

**Statistically validated churn drivers (chi-squared tests):**
- **Contract type** — month-to-month customers churn at 3× the rate of annual contract holders
- **Payment method** — electronic check users show the highest churn rate
- **Internet service** — fibre optic users churn more than DSL users
- **Tenure** — customers in their first 12 months are the highest-risk segment

---

## 🗂 Repository structure

```
telecom-churn-analytics/
├── notebooks/
│   └── churn_analytics.ipynb    ← full analysis pipeline
├── data/
│   └── README.md                ← dataset source & instructions
├── results/
│   ├── roc_curve.png
│   ├── confusion_matrix.png
│   └── churn_drivers.png
├── requirements.txt
└── README.md
```

---

## 🛠 Tech stack

| Tool | Purpose |
|---|---|
| Python 3.10+ | Core language |
| pandas, numpy | Data manipulation |
| scikit-learn | Modelling & evaluation |
| scipy | Chi-squared statistical tests |
| matplotlib, seaborn | Visualisation |

---

## ⚙️ Setup & usage

```bash
git clone https://github.com/dnyalsh/telecom-churn-analytics.git
cd telecom-churn-analytics
pip install -r requirements.txt
jupyter notebook notebooks/churn_analytics.ipynb
```

---

## 👤 Author

**Danial Shariati** · [LinkedIn](https://linkedin.com/in/shariatidanial) · shariatidani@gmail.com
