# 🏦 AtliQo Bank Credit Card Launch – Phase 1

Unlocking the credit potential through data-driven insights and customer segmentation.

---

## 🎯 Objective

🔍 Analyze **customer**, **credit profile**, and **transaction** data  
📊 Identify optimal customer **segments** for credit card offerings  
🚀 Recommend a **pilot credit card** for underserved youth groups  

---

## 📁 Dataset Overview

| 📂 Dataset         | 📊 Records     | 🧩 Key Features                        |
|-------------------|----------------|----------------------------------------|
| 👤 Customers       | 1000           | `age`, `gender`, `income`, `location` |
| 🧾 Credit Profiles | 1004 → 1000    | `credit_score`, `credit_limit`        |
| 💳 Transactions    | 500,000        | `platform`, `product_category`, `amount` |

---

## 🔍 Key Analysis & Insights

✅ **Annual Income**  
Right-skewed → imputed using **occupation-wise median**

✅ **Age Outliers**  
Invalid ages `<15 or >80` replaced with **median age by occupation**

✅ **Credit Limit**  
Missing values filled using **mode** of `credit_score_range`

✅ **Transaction Data Cleaning**  
- Null `platform` → Imputed with **Amazon**  
- `Zero amount` transactions → Replaced with **group-wise median**

✅ **Outstanding Debt Fixes**  
Capped values to not exceed `credit_limit` for consistency

---

## 🎯 Target Group Opportunity

### 👥 Focus Segment: **Age Group 18–25**

| Metric         | Insight                                                   |
|----------------|-----------------------------------------------------------|
| 🧮 Market Share | ~24.6% of customer base                                   |
| 💳 Behavior     | Low credit card usage, low credit history                 |
| 🛒 Interests     | Electronics, Fashion, Beauty (Amazon, Flipkart, Alibaba) |
| 🎁 Strategy     | Launch **entry-level credit card** tailored to lifestyle |

---

## 🧠 Tech Stack

| Tool          | Purpose                          |
|---------------|----------------------------------|
| 🐍 **Python** | Data processing & analysis       |
| 📘 Pandas     | DataFrames, cleaning, imputation |
| 📊 Seaborn    | Visualizations, insights         |
| 📈 Matplotlib | Distribution plots               |
| 📓 Jupyter    | Interactive notebooks            |
| 🎞 python-pptx| Automated PowerPoint generation  |

---

## 🚀 Final Recommendations

🔸 **Launch a Trial Credit Card** program for the 18–25 age group  
🔸 Partner with e-commerce platforms for lifestyle perks  
🔸 Implement real-time credit scoring via data pipelines  
🔸 Focus on long-term relationship and credit education

## 🤝 Contributions

Want to improve this analysis or expand it further?  
Feel free to **fork**, **clone**, and send a **pull request**!

---

## 📄 License

Licensed under the [MIT License](LICENSE)

---
