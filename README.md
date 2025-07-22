# 🏢 Bankruptcy Prediction using Machine Learning
## 📌 Project Overview
A capstone project for MS in Business Analytics focused on predicting corporate bankruptcy using financial ratios from the Taiwan Economic Journal (1999–2009). Implemented supervised ML models with resampling and feature selection strategies.

## 📂 Dataset
- **Source**: Taiwan Economic Journal
- **Records**: 6,819 companies (96 financial variables)
- **Target**: Bankruptcy status (1 = bankrupt, 0 = not bankrupt)

## ⚙️ Tools & Technologies
- Python (Pandas, Scikit-learn, Imbalanced-learn)
- Jupyter Notebook
- Tableau (for data visualization)
- SMOTE & Random Undersampling
- Feature Selection: Lasso, Random Forest

## 📊 Models & Scenarios
Tested 12 scenarios combining:
- Models: Logistic Regression, Random Forest, Gradient Boosting
- Resampling: SMOTE, Random Undersampling
- Feature Selection: Lasso, Random Forest

## ✅ Evaluation Metrics
- Accuracy, Precision, Recall
- AUC Score
- G-Mean, Specificity, Sensitivity

## 📈 Key Insights
- Lasso + Random Forest + SMOTE yielded highest AUC.
- Financial ratios like Net Income to Total Assets were key predictors.
- Class imbalance required strong resampling strategies.

## 📎 Files Included
- `bankruptcy_model.ipynb`: Notebook with all model runs
- `feature_selection.py`: Code for Lasso and RF feature selection
- `tableau_dashboard.png`: Visualization of key variable correlation

## 🔚 Outcome
The model helps in early warning detection of financial distress, aiding financial institutions and investors in risk analysis.

---

## 🤝 Author
**Venkata Reddy Naru**  
Graduate Research Assistant | MS Business Analytics  
[LinkedIn](https://www.linkedin.com/in/venkatareddy-naru-a0b2a4264)
