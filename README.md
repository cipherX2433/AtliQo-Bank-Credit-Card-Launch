# AtliQo-Bank-Credit-Card-Launch
🏦 AtliQo Bank Credit Card Launch

🎯 Objective

Analyze customer, credit profile, and transaction data
Identify potential segments for new credit card offerings
Recommend a pilot credit product strategy for underserved groups

| Dataset         | Records     | Key Features                  |
| --------------- | ----------- | ----------------------------- |
| Customers       | 1000        | age, gender, income, location |
| Credit Profiles | 1004 → 1000 | credit\_score, credit\_limit  |
| Transactions    | 500,000     | platform, category, amount    |

🔍 Key Analysis & Insights

Annual Income: Right-skewed, cleaned using occupation-wise median
Age Outliers: Ages <15 or >80 replaced with median per occupation
Credit Limit: Imputed using credit_score_range with mode
Transaction Cleaning: Null platform → Amazon, zero amounts → median
Outstanding Debt: Constrained to not exceed credit limit
📌 Target Group Opportunity

🎯 Focus Segment: Age Group 18–25
Market Share: ~24.6% of customer base
Behavior:
Lower credit card usage
Prefers Amazon, Flipkart, Alibaba
Shops primarily for Electronics, Fashion, and Beauty
Proposal: Launch a youth-focused credit card with entry-level limits and lifestyle rewards
🧠 Technologies Used

Python (Pandas, NumPy, Seaborn, Matplotlib)
Jupyter Notebooks
PowerPoint (via python-pptx for automation)
Data Imputation, Binning, and EDA Techniques

🚀 Recommendations

Launch Trial Credit Card Program for the 18–25 group
Promote through popular platforms and lifestyle categories
Use data pipelines for real-time credit scoring and risk control
