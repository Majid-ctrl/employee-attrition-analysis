# employee-attrition-analysis
Developed predictive models for employee attrition using the IBM HR dataset. Compared probabilistic methods against Machine Learning algorithms, achieving ~86% accuracy with an optimized Random Forest model.

## 🛠️ Tech Stack
* **Language:** R (RMarkdown)
* **Libraries:** `caret`, `pROC`, `randomForest`, `MASS`, `class`
* **Techniques:** SMOTE (handling imbalance), Cross-Validation, Stepwise Regression, Hyperparameter Tuning.

## 📊 Key Results
* **Random Forest:** Achieved best performance with **~86% Accuracy**, robustly identifying at-risk employees.
* **KNN:** Optimized at **k=13** via cross-validation, achieving competitive accuracy (~84.3%).
* **Logistic Regression:** Identified **OverTime** and **MonthlyIncome** as the strongest statistical drivers of attrition.

## 📄 Project Files
* [View Full PDF Report](HR_attrition_report.pdf)
* [View R Code](HR_Attrition.Rmd)
