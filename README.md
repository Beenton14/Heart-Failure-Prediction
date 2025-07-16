# ❤️ Heart Failure Prediction using KNN and Decision Tree

This project applies exploratory data analysis (EDA), data preprocessing, and classification models to predict heart failure events based on patient clinical records.

## ✅ Project Overview
- **Dataset**: Clinical records of heart failure patients.
- **Objective**: Predict patient death events based on health measurements and patient conditions.
- **Techniques**:
  - Data Cleaning (handling missing values)
  - Exploratory Data Analysis (EDA)
  - Encoding categorical features
  - Classification models: **K-Nearest Neighbors (KNN)** and **Decision Tree**

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Seaborn, Matplotlib for visualization
- Scikit-learn for classification models and evaluation

## 📊 Key Steps
1. **EDA**: Analyzing data distribution, correlation between features, and visualizing class imbalance.
2. **Data Preprocessing**: Cleaning data, encoding categorical features, and splitting data into train/test sets.
3. **Modeling**:
   - **KNN Classifier**: Tested with multiple k-values and evaluated using cross-validation.
   - **Decision Tree Classifier**: Tuned using max_depth and cross-validation.
4. **Evaluation**: Models evaluated using **accuracy**, **precision**, **recall**, and **F1-score** metrics.

## 📌 Summary of Findings
- **KNN** showed competitive accuracy but was sensitive to k-values.
- **Decision Tree** provided interpretable results but showed potential for overfitting.
- Proper data preprocessing and model tuning improved overall classification performance.

## 💻 How to Run
1. Clone this repository
```bash
git clone https://github.com/yourname/heart-failure-classification-knn-decisiontree.git
