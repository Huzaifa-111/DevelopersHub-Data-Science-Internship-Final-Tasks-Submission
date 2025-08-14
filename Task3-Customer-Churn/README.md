# Task 3 - Customer Churn Prediction

## 🎯 Objective
To predict whether a customer will leave the bank (churn) based on features like age, balance, credit score, gender, and location.

## 📁 Dataset
The dataset contains information about 10,000 bank customers:
- Features include: CreditScore, Geography, Gender, Age, Tenure, Balance, etc.
- Target: `Exited` (1 = Churned, 0 = Stayed)

## 🧪 Steps Performed
1. **Data Cleaning**:
   - Removed irrelevant identifiers (RowNumber, CustomerId, Surname)

2. **Encoding**:
   - LabelEncoded Gender
   - One-hot encoded Geography

3. **Exploratory Analysis**:
   - Churn patterns by gender and age
   - Boxplots to highlight influence of features

4. **Model Building**:
   - Used Random Forest Classifier
   - Evaluated using accuracy, confusion matrix, and classification report

5. **Feature Importance**:
   - Identified Age, Balance, and Credit Score as top churn indicators

## 📊 Key Insights
- Older customers and customers with high balances tend to churn more.
- Geography plays a role: German customers churn more than French/Spanish.
- Gender has a smaller effect compared to financial variables.

## 🛠 Tools Used
- Python, Pandas, Seaborn, Matplotlib
- scikit-learn (RandomForest, Metrics)

## 📂 Files Included
- `Customer_Churn_Prediction.ipynb`: Code and output notebook
- `Churn_Modelling.csv`: Input dataset
- `README.md`: Project description

## ✅ Conclusion
This churn prediction model can help the bank proactively retain at-risk customers using targeted outreach and benefits.
