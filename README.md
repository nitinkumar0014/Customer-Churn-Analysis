# Customer Churn Analysis

## Project Overview
This project focuses on analyzing customer churn behavior in a telecom company using Python data analysis libraries and visualization techniques. The main objective is to identify the key factors influencing customer churn and provide actionable business recommendations to improve customer retention.

---

## Dataset Information
The dataset contains customer demographic details, account information, subscribed services, payment methods, and churn status.

### Key Features
- Gender
- SeniorCitizen
- Tenure
- Contract Type
- Internet Service
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Preprocessing
The following preprocessing steps were performed:
- Handled missing values in `TotalCharges`
- Converted data types
- Checked duplicate values
- Performed exploratory data analysis (EDA)

---

## Exploratory Data Analysis
The analysis included:
- Churn distribution analysis
- Senior citizen churn analysis
- Tenure vs churn analysis
- Contract type analysis
- Payment method analysis
- Internet service analysis
- Service-based churn analysis

### Important Findings
- Around **26.5% customers churned** from the telecom service.
- Customers with **month-to-month contracts** showed the highest churn.
- Customers with **short tenure** were more likely to leave.
- **Fiber optic internet users** had higher churn rates.
- Customers without **OnlineSecurity** and **TechSupport** services showed higher churn behavior.
- Customers using **Electronic Check** payment methods had increased churn probability.

---

## Business Recommendations
- Encourage long-term contracts through discounts and loyalty programs.
- Improve customer support and security-related services.
- Focus on retaining new customers during their early subscription period.
- Improve service quality for Fiber optic internet users.
- Promote automatic payment methods to reduce churn risk.

---

## How to Run the Project

1. Clone the repository:
```bash
git clone <your-github-repo-link>
```

2. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the Jupyter Notebook:
```bash
jupyter notebook
```

---

## Conclusion
This project demonstrates how exploratory data analysis can help identify major factors affecting customer churn and support data-driven business decisions for improving customer retention.

---

## Author
Nitin Kumar
