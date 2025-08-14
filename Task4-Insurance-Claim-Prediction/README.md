# Task 4 - Predicting Insurance Claim Amounts

## 🎯 Objective
Estimate medical insurance charges based on a customer's age, BMI, smoking status, and other personal data using a regression model.

## 📁 Dataset
The dataset includes:
- Age, Sex, BMI, Number of Children, Smoker Status, Region
- Target variable: `charges` (medical insurance cost)

## 🧪 Steps Performed
1. **Data Cleaning**:
   - Checked and confirmed no missing values

2. **Encoding**:
   - Label Encoded categorical columns (`sex`, `smoker`)
   - One-hot encoded `region`

3. **Exploratory Analysis**:
   - Visualized relationship between `charges` and features like `age`, `bmi`, `smoker`
   - Created correlation heatmap

4. **Model Building**:
   - Trained a Linear Regression model
   - Evaluated using MAE and RMSE

## 📊 Key Insights
- Smoking has a large impact on insurance charges
- BMI and age also significantly affect costs
- Non-linear models could potentially improve performance

## 🛠 Tools Used
- Python, Pandas, Seaborn, Matplotlib
- scikit-learn (LinearRegression, Metrics)

## 📂 Files Included
- `Insurance_Claim_Prediction.ipynb`: Code notebook
- `insurance.csv`: Dataset used
- `README.md`: Summary of project

## ✅ Conclusion
This task illustrates how regression modeling can predict financial outcomes and be applied in healthcare cost estimation, insurance pricing, and risk analysis.
