📊 Customer Churn Analysis | Machine Learning + Power BI Dashboard
🔍 Predicting customer churn & building an interactive BI dashboard

This project analyzes telecom customer behavior to identify why customers leave and predict churn using machine learning.
It also includes a professional Power BI interactive dashboard to visualize churn KPIs and insights.

🚀 Project Features
1️⃣ Data Engineering

Raw data ingestion from Excel/CSV

Data cleaning & preprocessing

Handling missing values

Feature encoding & transformation

Saving cleaned dataset (clean_telco.csv)

2️⃣ Exploratory Data Analysis (EDA)

Churn distribution

Demographics (gender, senior citizen, dependents)

Contract patterns

Internet service trends

Correlation heatmaps

Visual insights exported as PNGs

3️⃣ Machine Learning

Trained multiple models to predict churn:

Logistic Regression

Random Forest

XGBoost

Support Vector Classifier

The best model was selected based on accuracy, ROC-AUC, and classification metrics.

✔ Final ML model saved as: churn_model.pkl

4️⃣ Power BI Dashboard

Includes:

KPI Cards (Churn Rate, Predicted Churn Rate, Avg Churn Probability, High-Risk Customers)

Segmented insights by:

Gender

Contract Type

Internet Service

Churn Trend over Customer Tenure

AI-powered predictions loaded from Python ML model

Clean, dark-themed layout for professional presentation

Dashboard file: dashboard.pbix

Screenshots included in the repo:

dashboard_overview.png

churn_kpi_cards.png

churn_charts.png

📦 Repository Structure
├── data/
│   ├── clean_telco.csv
│   ├── WA_Telco_Churn.csv
│   └── telco_for_powerbi.xlsx
│
├── notebooks/
│   ├── 01_data_ingestion.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_model_evaluation.ipynb
│
├── models/
│   └── churn_model.pkl
│
├── dashboard/
│   ├── dashboard.pbix
│   ├── dashboard_overview.png
│   ├── churn_kpi_cards.png
│   └── churn_charts.png
│
├── README.md
└── requirements.txt (optional)

🧠 AI/ML in This Project
✔ Predictive Modeling

A trained ML model predicts:

Probability of each customer churning

High-risk customer segments

Insights used inside Power BI

✔ Power BI + AI Integration

The model outputs were exported and merged into Power BI as:

Predicted churn values

Churn probability score

These AI-driven outputs power:

KPI cards

Ranking of high-risk customers

Trend analysis

Contract-based risk segmentation

📈 Dashboard Preview
Overview	KPI Cards	Charts

	
	
🛠 Tech Stack
Languages: Python, DAX
Libraries: Pandas, NumPy, Seaborn, Scikit-learn, XGBoost
BI Tools: Power BI
Version Control: Git + GitHub
▶️ How to Run the Project
Clone the repo
git clone https://github.com/yourusername/customer-churn-analysis-powerbi.git
cd customer-churn-analysis-powerbi

Open notebooks

Run each notebook in the notebooks/ folder in order.

Load Power BI Dashboard

Open:

dashboard/dashboard.pbix

📬 Contact

If you'd like help setting this up or want to collaborate:

Moin Hasan
💼 LinkedIn:  https://www.linkedin.com/in/moinhhasan/
