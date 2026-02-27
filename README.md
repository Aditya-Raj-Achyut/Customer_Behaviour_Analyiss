# 🚀 Customer Behavior Analysis | End-to-End Data Project

## 📌 Project Overview

The primary goal of this project is to analyze a retail dataset to identify **Customer Purchasing Patterns**. This project covers the complete end-to-end data lifecycle: extracting raw data, cleaning and analyzing it using SQL and Python, and finally building an interactive Power BI dashboard to support data-driven business decisions.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy, Matplotlib, Seaborn) | Data Cleaning & EDA |
| SQL (MySQL / SQLite) | KPI Queries & Aggregations |
| Power BI | Interactive Dashboard |
| Jupyter Notebook | Analysis Environment |

---

## 📁 Project Structure

```
Customer_Behaviour_Analysis/
│
├── Customer_Behavior_Analysis.ipynb       # Main Python EDA notebook
├── customer_behavior_sql_queries.sql      # SQL queries for KPI analysis
├── customer_shopping_behavior.csv         # Raw dataset
├── Customer_Behavior_Dashboard_view.pbix  # Power BI dashboard file
├── Screenshot 2026-02-12 175138.png       # Dashboard preview
├── requirements.txt                       # Python dependencies
└── README.md
```

---

## 📊 Project Workflow

1. **Data Extraction** — Raw dataset included in this repo: [customer_shopping_behavior.csv](customer_shopping_behavior.csv)
2. **SQL Analysis** — Loaded data into a database to calculate KPIs like Revenue per Customer and Churn Rate
3. **Python EDA** — Exploratory Data Analysis to detect outliers, handle missing values, and analyze correlations
4. **Dashboarding** — Designed an interactive Power BI dashboard to visualize high-level business insights

---

## 🔍 Key Insights

- **Customer Segmentation:** The 35–50 age demographic contributes ~45% of total revenue
- **Retention Issues:** ~20% of customers have not made a purchase in the last 6 months (High Churn Risk)
- **Category Performance:** The "Clothing" category has the highest profit margin (~12%) but also the highest return rate

---

## 📸 Dashboard Preview

![Customer Behavior Dashboard](Screenshot%202026-02-12%20175138.png)

> *Open the `.pbix` file in Power BI Desktop for the full interactive experience*

---

## ▶️ How to Run This Project

### 1. Clone the Repository
```bash
git clone https://github.com/Aditya-Raj-Achyut/Customer_Behaviour_Analyiss.git
cd Customer_Behaviour_Analyiss
```

### 2. Install Python Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the Jupyter Notebook
```bash
jupyter notebook Customer_Behavior_Analysis.ipynb
```

### 4. View the SQL Queries
Open `customer_behavior_sql_queries.sql` in any SQL client (MySQL Workbench, DBeaver, SQLite Browser, etc.)

### 5. View the Dashboard
Open `Customer_Behavior_Dashboard_view.pbix` using **Power BI Desktop** (free download from Microsoft)

---

## 💡 Business Recommendations

- **Loyalty Program:** Implement a reward system for high-spending segments (35–50 age group) to reduce churn
- **Marketing Strategy:** Focus social media ad spend on the 18–24 age group — they show high engagement despite lower current spending
- **Return Rate Management:** Investigate quality or sizing issues in the Clothing category to reduce return rates despite high profit margins

---

## 📦 Dataset

- **Source:** [customer_shopping_behavior.csv](customer_shopping_behavior.csv) (included in this repository)
- **File:** `customer_shopping_behavior.csv`

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋 Author

**Aditya Raj Achyut**  
[GitHub Profile](https://github.com/Aditya-Raj-Achyut)
