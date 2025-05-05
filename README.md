# Hospital Claims Analysis: Cost, Outcomes & Readmissions

This project analyzes a synthetic hospital claims dataset to uncover patterns in treatment costs, patient demographics, length of stay, and readmission rates. The goal is to simulate real-world workflows used by healthcare data analysts to generate actionable insights.

---

## 📁 Project Structure

```

hospital-claims-cost-outcomes/
├── data/                      
├── notebooks/                 
├── outputs/
│   ├── figures/               
│   └── summary\_tables/       
├── reports/                 
└── README.md

```

---

## 📌 Key Questions Addressed

- What are the most common and expensive diagnoses?
- Which conditions drive the highest readmission rates?
- How does length of stay relate to cost?
- Are certain insurance types associated with higher readmission?

---

## 📊 Methods Used

- Exploratory Data Analysis (EDA)
- ICD-10 code mapping
- Winsorization for outlier control (99th percentile)
- Grouped aggregations and pivot tables
- Visualization using `matplotlib` and `seaborn`

---

## 💡 Insights Summary

- **Dorsalgia**, **Asthma**, and **Type 2 Diabetes** were common and moderately costly.
- **GERD** had the highest average cost per case.
- **Mental health diagnoses** showed the highest readmission rates (~32%).
- **Uninsured patients** had the highest likelihood of readmission.

---

## ⚙️ Tech Stack

- Python (Pandas, Seaborn, NumPy, SciPy)
- Google Colab
- ICD-10-CM mapping via `icd10-cm` package

---

## 📄 Data Source

Synthetic healthcare data created for portfolio use. No real patient information used.

---

## 📬 Contact

Created by [Agnes Ekpo](https://agnesekpo.com) · [GitHub](https://github.com/TheAEkpo) · [LinkedIn](https://www.linkedin.com/in/agnesekpo)

```

---
