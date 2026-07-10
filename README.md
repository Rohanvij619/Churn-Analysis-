# 📊 Customer Churn Analysis

A comprehensive data analytics project focused on understanding customer churn behavior for a subscription-based OTT platform. The project combines SQL, Python, data visualization, and business intelligence techniques to identify churn patterns, measure revenue impact, and provide actionable retention strategies.

---

## 🎯 Project Objective

Customer retention is a key driver of growth for subscription businesses. This project aims to:

* Identify customers at risk of churning
* Analyze factors influencing churn
* Measure the financial impact of customer attrition
* Discover behavioral patterns across customer segments
* Recommend data-driven retention strategies

---

## 🛠️ Tech Stack

* Python
* SQL (SQLite)
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Dataset Overview

The project integrates data from three relational tables:

### Customer Table

* Customer ID
* Demographics
* Location
* Interests

### Subscription Table

* Subscription Type
* Plan Type
* Contract Type
* Monthly Charges
* Churn Score
* CLTV
* Cancellation Details

### Support Table

* Complaints
* Escalations
* CSAT Scores
* Customer Feedback

---

## 🔄 Project Workflow

### 1. Data Extraction

* Connected SQLite database with Python
* Imported data using SQL queries

### 2. Data Cleaning

* Removed inconsistencies
* Handled missing values
* Corrected data types

### 3. Feature Engineering

* Customer tenure calculation
* Churn indicators
* Revenue metrics
* Retention KPIs

### 4. Exploratory Data Analysis (EDA)

* Churn analysis
* Customer segmentation
* Revenue impact analysis
* Contract-type comparison
* Regional analysis

### 5. Data Visualization

* Churn distribution
* Revenue impact charts
* Plan-wise churn analysis
* State-wise churn trends
* Risk segmentation visuals

---

## 📈 Key KPIs

* Churn Rate
* Retention Rate
* ARPU (Average Revenue Per User)
* Customer Lifetime Value (CLTV)
* Revenue at Risk
* Customer Tenure
* Escalation Rate
* Complaint Analysis

---

## 🔍 Key Findings

* Overall Churn Rate: **28.6%**
* Retention Rate: **71.4%**
* Monthly Contract Churn: **55.6%**
* Annual Contract Churn: **8.3%**
* Revenue Loss Due to Churn: **18%**
* Karnataka recorded the highest churn concentration.
* Customers with support escalations were significantly more likely to churn.
* Basic subscription plans contributed the highest volume of churned users.

---

## 💡 Business Recommendations

* Prioritize retention efforts for high-value customers.
* Encourage migration from monthly to annual subscriptions.
* Improve customer support response and issue resolution.
* Investigate churn spikes in high-risk regions.
* Launch targeted campaigns for customers with elevated churn scores.

---

## 📸 Project Screenshots

### Importing Database

<img width="733" height="612" alt="Screenshot 2026-07-10 182240" src="https://github.com/user-attachments/assets/bb5f3964-6320-4f92-bc2d-56c229153a86" />

### Data Cleaning

<img width="733" height="797" alt="Screenshot 2026-07-10 182308" src="https://github.com/user-attachments/assets/c57a91a9-d079-483f-93ce-4b060b84d70d" />

### Fetaure Engineering And Data Analysis

<img width="732" height="576" alt="Screenshot 2026-07-10 182337" src="https://github.com/user-attachments/assets/c1e7803b-30ad-4199-9a18-d090918db5bb" />


### Data Visualization 

<img width="735" height="497" alt="Screenshot 2026-07-10 182212" src="https://github.com/user-attachments/assets/3bb4b41e-fad9-443d-a985-7646ab13e674" />

<img width="735" height="452" alt="Screenshot 2026-07-10 182150" src="https://github.com/user-attachments/assets/5c64c76f-49c1-4fa6-b3da-5553f2dfe2db" />

<img width="735" height="731" alt="Screenshot 2026-07-10 182127" src="https://github.com/user-attachments/assets/dd539b7a-3928-4068-b5b3-ee49a71a800f" />

<img width="735" height="723" alt="Screenshot 2026-07-10 182056" src="https://github.com/user-attachments/assets/8f7e3413-d268-4203-ba89-f784b98536cb" />


---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/customer-churn-analysis.git
cd customer-churn-analysis
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file and run all cells sequentially.

---

## 📁 Project Structure

```text
Customer-Churn-Analysis/
│
├── Customer_Churn_Analysis.ipynb
├── customer_churn.db
├── screenshots/
│   ├── churn_chart.png
│   ├── revenue_analysis.png
│   ├── eda_table.png
│   └── code_screenshot.png
├── README.md
└── requirements.txt
```

---

## 🎓 Skills Demonstrated

* SQL Querying
* Data Cleaning
* Data Transformation
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Customer Analytics
* Business Intelligence
* KPI Development
* Revenue Analysis
* Insight Generation

---

## 👨‍💻 Author

**Rohan Vij**

If you found this project useful, consider giving it a ⭐ on GitHub.
