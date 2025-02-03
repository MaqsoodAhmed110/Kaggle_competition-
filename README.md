# Titanic - Machine Learning from Disaster  

This repository contains a notebook for the Titanic Kaggle competition, where we predict passenger survival using machine learning techniques. The workflow includes data preprocessing, feature extraction, and modeling with Support Vector Machine (SVM) and Logistic Regression.  

## Dataset  

The dataset is obtained from the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic). It includes passenger details such as age, fare, class, and other relevant features.  

## Workflow  

### 1. Loading Data  
- The dataset is loaded using `pandas` and explored for missing values and data distribution.  

### 2. Data Preprocessing  
- Dropped irrelevant columns that do not contribute significantly to survival prediction.  
- Handled missing values:  
  - Numerical features were filled with the median value.  
  - Categorical feature `Embarked` was filled with `'U'` (Unknown).  

### 3. Feature Extraction  
- Converted categorical variables into numerical format using `LabelEncoder`.  
- Created meaningful features to enhance model performance.  

### 4. Modeling  
- **Support Vector Machine (SVM):** Achieved an accuracy of **68.01%**.  
- **Logistic Regression:** Achieved an accuracy of **81.00%**.  
- The final predictions were saved in `submission.csv`.  

## Results  
- Logistic Regression outperformed SVM in this competition.  
- The final predictions were submitted to Kaggle for evaluation.  

## Dependencies  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

## Submission  
The final predictions are stored in `submission.csv`.  

---

Feel free to improve the model further by experimenting with feature engineering, hyperparameter tuning, or advanced algorithms! 🚀  
