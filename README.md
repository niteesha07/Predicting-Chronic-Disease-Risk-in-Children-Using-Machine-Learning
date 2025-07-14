# Predicting-Chronic-Disease-Risk-in-Children-Using-Machine-Learning
# Exploring the Impact of Individual, Clinical, and Family Factors on Neurodevelopmental Health Outcomes in Children

This project analyzes data from the **National Survey of Children's Health (NSCH)** to understand how individual, clinical, and family environmental factors affect the risk of **Neurodevelopmental Disabilities (NDD)** in children. The analysis employs advanced machine learning methods to uncover key predictors and provide actionable insights for public health interventions.

---

## 📁 Files Included

- `Final_Project.Rmd`: R Markdown source code for data preprocessing, modeling, visualization, and analysis.
- `Final_report.pdf`: A compiled PDF report detailing the study's background, methodology, results, discussion, and policy implications.

---

## 📊 Methods Used

- **Dataset**: NSCH dataset (50,212 records)
- **Model**: Random Forest Classifier
- **Data Preprocessing**:
  - Imputation of missing values
  - Encoding of categorical variables
- **Validation**: Accuracy, ROC-AUC, Confusion Matrix
- **Statistical Techniques**:
  - Feature Importance (Gini, MDA)
  - Correlation Matrix
  - Chi-square tests

---

## 🌟 Key Findings

- **Top Predictors**:
  - Early diagnosis of autism (K2Q35A_1_YEARS)
  - Child's current age (SC_AGE_YEARS)
  - Neighborhood safety (K10Q20)
  - Special education plan status (SESPLANYR)

- **Model Performance**:
  - Accuracy: **95%**
  - AUC: **1.0** (note: suggests possible overfitting)

- **Policy Recommendations**:
  - Invest in early and universal screening for NDD.
  - Improve neighborhood safety and family support services.
  - Tailor interventions based on sleep patterns, family structure, and socioeconomic status.

---

## 📌 Limitations

- AUC of 1.0 may indicate **overfitting** — validation with external datasets is advised.
- NSCH relies on **self-reported** data, which may introduce bias.

---

## 📚 References

1. National Survey of Children’s Health (NSCH) – HRSA
2. Lord et al. (2008) - Autism Spectrum Disorders, *The Lancet*
3. Evans & Kim (2013) - Childhood Poverty and Health, *Psychological Science*
4. Marmot & Wilkinson (2006) - *Social Determinants of Health*

---

## 👨‍💻 Author

**Niteesha Adapala**  
Email: niteesha.adapala@gmail.com

---

## 💡 Future Work

- Apply cross-validation and external test datasets for robustness.
- Analyze trends across multiple years of NSCH data.
- Investigate additional clinical and behavioral predictors.
