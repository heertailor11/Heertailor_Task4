# Credit Card Fraud Detection Using Machine Learning

## Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. The system analyzes transaction patterns and classifies transactions as either genuine or fraudulent.

Fraud detection is a crucial application in the financial sector, helping organizations minimize financial losses and improve security.

---

## Dataset

The project uses the Credit Card Fraud Detection dataset containing anonymized transaction records.

### Features

* **Time**: Time elapsed between transactions.
* **V1 – V28**: PCA-transformed features.
* **Amount**: Transaction amount.
* **Class**:

  * 0 → Genuine Transaction
  * 1 → Fraudulent Transaction

### Dataset Information

* Total Transactions: 284,807
* Genuine Transactions: 284,315
* Fraudulent Transactions: 492

This dataset is highly imbalanced, making fraud detection a challenging classification problem.

---

## Objectives

* Detect fraudulent transactions accurately.
* Analyze transaction patterns.
* Handle class imbalance.
* Build and evaluate machine learning models.
* Improve financial transaction security.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

### 1. Data Collection

Load the credit card transaction dataset.

### 2. Data Preprocessing

* Check for missing values
* Scale transaction amounts
* Remove unnecessary columns
* Handle class imbalance

### 3. Exploratory Data Analysis (EDA)

* Distribution of fraud and genuine transactions
* Correlation analysis
* Data visualization

### 4. Feature Engineering

* Feature selection
* Data transformation
* Data scaling

### 5. Model Training

Implemented machine learning algorithms such as:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

### 6. Model Evaluation

Performance measured using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── creditcard.csv
├── Fraud_Detection.ipynb
└── README.md
```

---

## How to Run

1. Open Google Colab.
2. Upload the dataset (`creditcard.csv`).
3. Upload or open the notebook (`Fraud_Detection.ipynb`).
4. Run all cells sequentially.
5. Review model evaluation metrics and visualizations.

---

## Results

The machine learning model successfully identifies fraudulent transactions by learning patterns from historical transaction data.

Key evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Random Forest generally provides better performance for this dataset due to its ability to capture complex transaction patterns.

---

## Challenges

* Highly imbalanced dataset
* Large volume of transactions
* Detecting rare fraud cases
* Reducing false positives

---

## Future Enhancements

* Apply SMOTE for advanced balancing.
* Implement Deep Learning models.
* Deploy the model using Flask or Streamlit.
* Enable real-time fraud monitoring.
* Create an interactive dashboard.

---

## Conclusion

This project demonstrates the application of machine learning in fraud detection. By leveraging data preprocessing, feature engineering, and classification algorithms, the model can effectively identify suspicious transactions and support financial institutions in preventing fraud.

---

## Author
 Credit Card Fraud Detection Using Machine Learning
