# Predicting-Titanic-Survial-using-ANN-model
This project uses the famous Titanic dataset to build a machine learning model that predicts whether a passenger survived or not based on features like age, sex, ticket class, etc. The notebook walks through data exploration, visualization, preprocessing, and model building in a step-by-step manner.

##  Libraries Used
- `pandas` – for data manipulation
- `numpy` – for numerical operations
- `matplotlib` & `seaborn` – for data visualization
- `sklearn` – for machine learning modeling and evaluation
##  Model Used
- **Logistic Regression** from `sklearn.linear_model`
- Trained to predict the `Survived` column
- Evaluation via accuracy score and confusion matrix
##  Workflow Overview
1. Data Cleaning:
   - Handled missing values (`Age`, `Embarked`)
   - Converted categorical variables (`Sex`, `Embarked`) using one-hot encoding
2. Exploratory Data Analysis (EDA):
   - Correlation heatmap, bar plots for survival rates
3. Model Training:
   - Train-test split
   - Logistic Regression fitting
4. Model Evaluation:
   - Accuracy score
   - Confusion matrix visualization
##  Results
- Achieved ~80% accuracy on the test set (varies by split/random seed)
- Insights:
  - Women had a higher chance of survival
  - Higher ticket class (1st class) correlated with better survival rates

