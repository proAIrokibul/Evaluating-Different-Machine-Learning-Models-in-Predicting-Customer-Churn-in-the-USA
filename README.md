# Evaluating-Different-Machine-Learning-Models-in-Predicting-Customer-Churn-in-the-USA

## Project Overview
Customer churn is a critical concern for businesses across industries. This project focuses on predicting customer churn using machine learning models based on customer demographic, service, and payment details. By leveraging data-driven insights, businesses can identify at-risk customers and implement effective retention strategies. 

Three machine learning models were evaluated and compared:  
1. **Logistic Regression**  
2. **Random Forest Classifier**  
3. **Support Vector Machine (SVM)**  

The project involves preprocessing, exploratory data analysis, model training, and evaluation to determine the best-performing model for churn prediction.

---

## Key Features

### 1. Data Preprocessing
- **Handling Missing Values**:  
  Missing values in the `TotalCharges` column were imputed with appropriate values.
- **Encoding Categorical Variables**:  
  Transformed categorical features (e.g., gender, contract type) into numerical formats for compatibility with machine learning models.
- **Feature Scaling**:  
  Standardized numerical variables (e.g., tenure, monthly charges) to ensure consistent model performance.

### 2. Exploratory Data Analysis (EDA)
Visualizations provided insights into factors influencing churn:
- Customers with month-to-month contracts showed the highest churn rates.
- Electronic check payment method correlated strongly with churn.
- Senior citizens were more likely to churn than younger customers.
- High monthly charges increased the likelihood of churn.

### 3. Machine Learning Models
- Logistic Regression, Random Forest, and Support Vector Machine (SVM) were trained and evaluated.
- Models were assessed using accuracy, precision, recall, and F1-score.
- Comparative analysis was performed to determine the most effective model.

---

## Model Results and Comparison

### Logistic Regression Results
          precision    recall  f1-score   support

       0       0.51      0.60      0.55       596
       1       0.49      0.40      0.44       580
       accuracy                           0.50      1176


### Random Forest Results
          precision    recall  f1-score   support

       0       0.50      0.54      0.52       596
       1       0.49      0.45      0.47       580
       accuracy                           0.50      1176



### SVM Results
          precision    recall  f1-score   support

       0       0.50      0.67      0.57       596
       1       0.48      0.32      0.38       580
       accuracy                           0.49      1176


## Business Impacts

1. **Retention Strategies**:  
   By identifying at-risk customers, businesses can implement targeted retention strategies such as personalized offers, loyalty programs, and improved customer support.

2. **Cost Reduction**:  
   Reducing churn minimizes the high costs associated with acquiring new customers, improving operational efficiency.

3. **Revenue Growth**:  
   Preventing churn increases customer lifetime value (LTV), enhancing revenue streams and profitability.

4. **Data-Driven Decision Making**:  
   Insights from churn analysis help businesses prioritize critical areas like payment methods, contract types, and customer satisfaction improvements.

---

## Conclusion
This project successfully demonstrated the application of machine learning to predict customer churn and provided actionable insights for business improvement. While the models achieved moderate accuracy, further optimization and the use of advanced techniques like deep learning or ensemble methods could enhance predictive performance.


