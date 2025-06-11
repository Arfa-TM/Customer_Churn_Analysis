# Customer Churn Analysis and Prediction

## 📌 Objective
This project aims to analyze customer behavior and predict churn in a telecom company using machine learning techniques.

Understanding churn helps businesses identify why customers leave and what strategies can reduce attrition.

---

## 📂 Dataset
- **Name:** Telco Customer Churn Dataset
- **Source:** IBM Sample Data / Kaggle
- **Records:** ~7,000 customer records
- **Target Variable:** `Churn` (Yes/No)

---

## 🧰 Tools & Libraries
- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🔍 Workflow

### 1. Data Preprocessing
- Checked for missing values
- Converted `TotalCharges` to numeric
- Encoded categorical features using `LabelEncoder` and `OneHotEncoding`
- Converted `Churn` column to binary (Yes → 1, No → 0)
- Feature scaling using `StandardScaler`

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn by contract type, payment method, tenure, and monthly charges
- Plotted churn distribution using bar plots and pie charts
- Generated correlation heatmap for numeric variables

### 3. Model Building
- Splitted data into training and testing sets
- Applied classification models:
  - Logistic Regression
  - Random Forest Classifier
  - Support Vector Machine (SVM)
- Evaluated using accuracy, precision, recall, and F1-score

### 4. Feature Importance
- Used Random Forest's feature importance
- Identified key churn drivers:
  - `Contract`, `MonthlyCharges`, `Tenure`, `TechSupport`, `OnlineSecurity`

---

## 📈 Results
- Best-performing model: **Random Forest Classifier**
- Achieved an accuracy of **~80%**
- Feature importance highlighted contract type and monthly charges as top predictors

---

## 📊 Key Insights
- Customers with **month-to-month contracts** and **high monthly charges** are more likely to churn.
- Providing services like **Tech Support** and **Online Security** reduces churn likelihood.
- Long-term customers tend to stay.

---

## 💡 Business Recommendation
- Offer incentives to convert monthly subscribers to yearly contracts
- Target high-risk churn segments with personalized offers
- Improve accessibility to support services

---

## 🏁 How to Run This Project

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/Customer_Churn_Analysis.git
