# 📊 Student Performance Prediction using Machine Learning

## 🔍 Problem Statement

This project aims to predict students' academic performance using various demographic and academic features. The goal is to understand how factors like gender, ethnicity, parental education, lunch type, and test preparation courses impact students' test scores in Math, Reading, and Writing.

---


## 🧪 Project Pipeline

### 1. 📥 Data Collection
- Loaded the dataset from the Kaggle source.
- Verified data types and missing values.

### 2. 🧹 Data Preprocessing
- Checked for and handled missing/null values.
- Converted categorical features using **Label Encoding**.
- Split the dataset into features (X) and target variable (Y).
- Scaled the numerical data using **StandardScaler**.

### 3. 📊 Exploratory Data Analysis
- Performed visualization on:
  - Score distributions
  - Correlation heatmaps
  - Grouped means by categories

### 4. 🧠 Model Building
- Tried multiple regression models:
  - **Linear Regression**
  - **Decision Tree Regressor**
  - **Random Forest Regressor**
- Used a loop to train and evaluate each model.

### 5. 📈 Evaluation Metrics
A custom function `evaluate_model(y_true, y_pred)` was used to compute:
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

### OUTPUTS:

![](Results/1.png)
![](Results/2.png)
![](Results/3A.png)
![](Results/3.png)
![](Results/4.png)

### PLOTTED GRAPHS:

![](Results/output.png)
![](Results/output2.png)


## 🎓 Conclusion

This project was developed as part of my internship completion at **Internship Studio**. It reflects my understanding of the complete machine learning workflow, from data preprocessing and exploratory data analysis to model training, evaluation, and result visualization.

Through this project, I have gained valuable hands-on experience in implementing supervised learning techniques and interpreting model performance using key metrics. I am confident that the skills applied here will serve as a strong foundation for future data science and machine learning challenges.
