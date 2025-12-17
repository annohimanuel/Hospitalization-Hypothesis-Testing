# 🏥 Hospitalization Hypothesis Testing (Statistical Inference)

🎯 **Goal:** Use hypothesis testing to determine whether key patient/clinical variables are significantly associated with hospitalization outcomes, and translate the results into clear, decision-relevant insights.

---

## 📊 Findings

✅ **Data validation**
- Loaded and inspected the dataset (shape, dtypes, summary stats)
- Checked for missing values and data integrity issues before analysis

📌 **Hypothesis testing framework**
- Defined **null vs alternative hypotheses** for each comparison
- Selected statistical tests based on variable type:
  - 📏 **Numeric vs group outcome:** two-sample *t-test* (or non-parametric alternative when assumptions fail)
  - 🧾 **Categorical vs group outcome:** *chi-square test of independence*
- Used a consistent significance threshold (α = 0.05)

🔎 **Assumptions + diagnostics**
- Checked distribution characteristics with plots (histograms/boxplots)
- Verified conditions (normality / variance considerations) to justify test choice
- Interpreted statistical significance alongside practical meaning (effect size / real-world impact)

📈 **Results interpretation**
- Identified variables that show statistically significant differences between groups
- Highlighted variables with non-significant results as likely not strong drivers of hospitalization differences in this dataset
- Summarized outcomes as decision-ready statements (what changed, direction, and why it matters)

📌 **Conclusion**
- Delivered a structured inference workflow: **EDA → test selection → hypothesis testing → interpretation**
- Produced evidence-based insights that can support operational decisions (risk screening, resource allocation, intervention targeting)

---

## 👤 Author

Imanuel Annoh
