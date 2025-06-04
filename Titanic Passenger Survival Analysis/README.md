# 🛳 Titanic EDA: Survival Analysis

## 📊 Overview
This project explores the Titanic dataset to uncover factors that influenced passenger survival during the disaster. Analysis includes data cleaning, univariate and bivariate visualization, and correlation analysis.

## 📁 Dataset
- Source: [Kaggle / Seaborn Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Features include: Age, Sex, Fare, Pclass, Embarked, SibSp, Parch

## 🔍 Key Insights
- Females had 74% survival rate; males only 19%
- 1st class passengers had much higher survival rates
- Fare and survival positively correlated (r = 0.26)
- Age is mildly negatively correlated with survival

## 📈 Techniques Used
- Pandas, Seaborn, Matplotlib
- Correlation matrix
- One-hot encoding
- Missing value imputation
- Boxplot and histogram visualizations

## 📄 Files
- `titanic.ipynb` → Main analysis notebook
- `titanic.csv` → Dataset
- `plots/` → Saved EDA charts
- `README.md` → Project summary (this file)

## 📌 Next Steps
- Feature engineering: `Title`, `FamilySize`
- Train classification models: Logistic Regression, Random Forest
- Hyperparameter tuning and cross-validation
