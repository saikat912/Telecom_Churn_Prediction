# Telecom Customer Churn Prediction Project

## Overview

This project focuses on predicting customer churn in the telecom domain using machine learning techniques. The dataset contains customer information, including demographic details, service usage, and payment methods, which are used to analyze and predict whether a customer is likely to leave the service (churn).

## Dataset

The dataset consists of **7043 rows** and **21 columns**. Key features include:

- **Demographics**: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- **Service Information**: `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`
- **Account Details**: `Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`
- **Target Variable**: `Churn` (indicates if the customer has churned)

## Objectives

The primary goal of this project is to:

1. Perform exploratory data analysis (EDA) to understand patterns and trends in customer behavior.
2. Preprocess the data for machine learning (handling missing values, encoding categorical variables, etc.).
3. Build predictive models to classify customers as likely to churn or not.
4. Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

## Tools and Libraries

The following tools and libraries are used:

- **Python**: Programming language for data manipulation and analysis.
- **Libraries**:
  - `numpy` and `pandas`: For data manipulation.
  - `matplotlib` and `seaborn`: For visualization.
  - Machine learning libraries (e.g., scikit-learn).

## Data Preprocessing Steps

1. **Handling Missing Values**: Address missing or invalid entries in the dataset.
2. **Feature Engineering**:
   - Encoding categorical variables into numerical formats.
   - Creating new features if necessary.
3. **Normalization/Scaling**: Normalize numerical features like `MonthlyCharges` and `TotalCharges`.
4. **Splitting Data**: Divide the dataset into training and testing sets.

## Exploratory Data Analysis (EDA)

Key insights derived from EDA include:

- Distribution of churn across demographics (e.g., gender, senior citizens).
- Correlation between tenure and churn likelihood.
- Impact of payment methods and contract types on churn.

Visualizations such as histograms, box plots, heatmaps, and scatter plots are used to uncover patterns.

## Predictive Modeling

Several machine learning algorithms are applied to predict churn:

1. Logistic Regression
2. Decision Trees
3. Random Forest
4. Gradient Boosting (e.g., XGBoost)

Models are evaluated using cross-validation techniques, ensuring robust performance metrics.

## Results

The best-performing model achieves high accuracy in predicting churn, with detailed metrics provided for precision, recall, and F1-score.

## Conclusion

This project provides actionable insights into customer behavior in the telecom industry. By identifying factors contributing to churn, businesses can implement strategies to retain customers effectively.

---

### How to Run the Project

1. Clone the repository:
   ```bash
   git clone 
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Telecom_Domain_Project.ipynb
   ```

### Future Work

Potential enhancements include:

- Incorporating additional datasets for more robust predictions.
- Using deep learning techniques for improved accuracy.
- Developing a dashboard for real-time churn monitoring.

---

### Contact

For questions or collaboration opportunities, please reach out via [saikatpal912@gmail.com].

