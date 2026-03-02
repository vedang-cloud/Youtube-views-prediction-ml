# Youtube-views-prediction-ml
Multiple linear regression model to predict youtube video views

# YouTube Views Prediction using Multiple Linear Regression

## 📖 Problem Statement
The objective of this project is to predict YouTube video views based on engagement features such as comment count, like rate, video length, upload hour, and number of hashtags.

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

1. Data Cleaning
   - Checked for missing values
   - Filled null values using mean
   - Verified dataset integrity

2. Exploratory Data Analysis (EDA)
   - Scatter plots between features and views
   - Correlation heatmap
   - Feature relationship analysis

3. Model Building
   - Multiple Linear Regression
   - Train-Test Split (80:20)
   - random_state = 42 for reproducibility

4. Model Evaluation
   - Training R²: 0.83
   - Testing R²: 0.73
   - RMSE: 2848

---

## 📈 Results

The model explains approximately 73% of the variance in YouTube views.  
The RMSE value indicates an average prediction error of about 21% relative to the average views, which is reasonable for social media data.

---

## 📌 Conclusion

The model performs well with minor overfitting and demonstrates a structured machine learning workflow including preprocessing, visualization, training, and evaluation.

---

## 🚀 Future Improvements
- Feature scaling
- Regularization (Ridge/Lasso)
- More feature engineering
- Larger dataset
