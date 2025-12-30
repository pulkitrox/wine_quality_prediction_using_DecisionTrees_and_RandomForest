# 🍷 Wine Quality Analysis using Machine Learning & EDA

## 📌 Project Overview
This project presents a comprehensive **Exploratory Data Analysis (EDA)** and **Machine Learning–based classification** of red wine quality. The objective is to identify key physicochemical properties influencing wine quality and to build predictive models that can accurately classify wine quality ratings.

The project integrates statistical analysis, data visualization, and supervised learning models to extract actionable insights from real-world data.

---

## 🎯 Objectives
- Analyze the distribution of wine quality scores
- Identify chemical properties that significantly impact wine quality
- Visualize correlations between features and the target variable
- Build and compare classification models for wine quality prediction
- Evaluate model performance using accuracy and confusion matrices

---

## 📁 Dataset Description
- **Dataset:** Red Wine Quality Dataset
- **Features:** 11 physicochemical attributes
- **Target Variable:** Wine quality score (integer values from 3 to 8)

### Key Features Include:
- Alcohol
- Volatile acidity
- Fixed acidity
- Residual sugar
- Sulphates
- Free sulfur dioxide
- pH, density, chlorides, citric acid

---

## 🔍 Exploratory Data Analysis (EDA)

### 📊 Quality Distribution
- Majority of wines fall into **average quality categories**
- Fewer samples represent very low or very high quality wines
- This class imbalance impacts classification performance

### 🔗 Correlation Analysis
- **Alcohol:** Moderate positive correlation with quality (~0.48)
- **Volatile Acidity:** Strong negative correlation (~ -0.39)
- **Fixed Acidity:** Weak positive influence
- **Free Sulfur Dioxide:** Negligible correlation

### 📉 Key Visual Insights
- Higher volatile acidity is associated with lower quality wines
- Residual sugar shows minimal variation across quality levels, indicating low predictive power

---

## 🤖 Machine Learning Workflow

### 🧪 Data Preparation
- Train-test split for unbiased evaluation
- Feature scaling where necessary

### 🌳 Models Implemented
1. **Decision Tree Classifier**
   - Baseline model
   - Accuracy: **~60.5%**
   - Prone to overfitting

2. **Random Forest Classifier**
   - Ensemble learning approach
   - Accuracy: **~68.75%**
   - Better generalization and stability

### 📈 Evaluation Metrics
- Accuracy score
- Confusion matrices for detailed performance analysis

---

## 📂 Repository Structure
├── wine_quality.ipynb
├── Wine-Quality-Analysis.pptx
├── README.md
├── wine_data.csv

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📌 Key Takeaways
- Alcohol content is the strongest positive contributor to wine quality
- High volatile acidity negatively affects wine perception
- Random Forest significantly outperforms Decision Tree
- Combining EDA with ML leads to better interpretability and performance

---

## 🚀 Future Improvements
- Hyperparameter tuning (GridSearchCV)
- Address class imbalance (SMOTE)
- Try advanced models (XGBoost, SVM)
- Convert to regression-based quality prediction

---





## 📂 Repository Structure
