# 📊 Telecom Customer Churn Analysis

An end-to-end Exploratory Data Analysis (EDA) project on the IBM Telco Customer Churn dataset, 
built to identify why customers leave a telecom service and what the business can do to retain them.

---

## 🔍 Problem Statement

Customer churn is one of the biggest challenges in the telecom industry. 
Losing a customer costs significantly more than retaining one. 
This project analyzes 7,043 customer records to uncover patterns and 
risk factors associated with churn, and translates them into actionable business insights.

---

## 📁 Dataset

- **Source:** [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Records:** 7,043 customers
- **Features:** 21 columns including demographics, services subscribed, contract type, payment method, and churn status

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Base visualizations |
| Seaborn | Statistical plots |
| Jupyter Notebook | Development environment |

---

## 📌 Project Structure
```
telecom-customer-churn-analysis/
│
├── Telecom_Customer_Churn_Analysis.ipynb   # Main analysis notebook
├── Customer Churn.csv                       # Dataset
└── README.md                                # Project documentation
```

---

## 🔄 Analysis Workflow

1. **Data Loading & Inspection** — shape, dtypes, sample rows
2. **Data Cleaning** — fix TotalCharges dtype, map SeniorCitizen to Yes/No
3. **Churn Overview** — overall churn rate with count and pie chart
4. **Demographic Analysis** — churn by gender, senior citizen, partner, dependents
5. **Contract & Payment Analysis** — churn by contract type and payment method
6. **Internet Services Analysis** — churn by internet service and add-ons
7. **Tenure & Charges Distribution** — numerical feature distributions by churn
8. **Heatmap Analysis** — churn rate by contract × internet service
9. **Correlation Analysis** — feature correlations with churn
10. **Tenure Segmentation** — churn rate across customer age cohorts
11. **Business Recommendations** — actionable insights for retention

---

## 📊 Key Findings

- ⚠️ **26.5% overall churn rate** — roughly 1 in 4 customers is leaving
- 📄 **Month-to-month contracts** have ~43% churn vs ~11% for one-year and ~3% for two-year contracts
- 🌐 **Fiber optic internet** customers churn more than DSL or no-internet customers
- 🔒 Customers **without OnlineSecurity or TechSupport** are significantly more likely to churn
- 💳 **Electronic check** payment users show the highest churn among all payment methods
- 🕐 **New customers (0–12 months)** churn at the highest rate — early retention is critical
- 👴 **Senior citizens** churn at a higher rate than non-senior customers

---

## ✅ Business Recommendations

1. **Incentivize long-term contracts** — offer discounts or perks for switching from month-to-month to annual plans
2. **Launch an onboarding program** for the first 6 months to reduce early churn
3. **Bundle OnlineSecurity & TechSupport** into base plans or offer them at a discounted rate
4. **Investigate Fiber optic** service quality or pricing — run customer satisfaction surveys
5. **Create senior citizen loyalty programs** with dedicated support channels
6. **Encourage auto-pay** (bank transfer/credit card) with small billing discounts to reduce electronic check usage

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/your-username/telecom-customer-churn-analysis.git
cd telecom-customer-churn-analysis
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

4. Open `Telecom_Customer_Churn_Analysis.ipynb` and run all cells

---

## 🔮 Future Scope

- [ ] Build a **Logistic Regression / Random Forest** model to predict churn probability
- [ ] Handle class imbalance using **SMOTE**
- [ ] Create an **interactive dashboard** using Plotly or Power BI
- [ ] Add **feature engineering** (e.g., Avg Revenue Per User, charge-to-tenure ratio)
- [ ] Use **automated EDA tools** like ydata-profiling or Sweetviz

---

## 👤 Author

**Your Name**  
[LinkedIn](https://www.linkedin.com/in/ghanashyam-auti-6ab1b7398/) • [GitHub](https://github.com/ghanashyamauti)
