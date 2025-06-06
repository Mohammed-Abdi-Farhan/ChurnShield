# 🚀 ChurnShield – My Unique Approach to Retaining SyriaTel Customers

**Personal Vision**  
This project is my personal take on solving a real-world telecom challenge. With ChurnShield, I applied my analytical skills to predict customer churn at SyriaTel using data science. The result? A model that doesn’t just crunch numbers—it helps people make better business decisions.

---

##  Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Tools & Technologies](#tools--technologies)  
- [Approach & Methodology](#approach--methodology)  
- [Key Visual Insights](#key-visual-insights)  
- [Model Results](#model-results)  
- [Business Insights](#business-insights)  
 

---

##  Overview

Churn is one of the biggest threats in telecom, and I wanted to tackle it using predictive analytics. This project allowed me to explore data deeply, find patterns, build a high-performing model, and translate insights into business language.

---

##  Dataset

| Attribute   | Description                                  |
|-------------|----------------------------------------------|
| Source      | SyriaTel Churn Dataset (Kaggle)              |
| Records     | ~3,300 customers                             |
| Key Columns | Plan types, minutes used, charges, support calls, churn outcome |

---

##  Tools & Technologies

| Category       | Tools                                         |
|----------------|-----------------------------------------------|
| Language       | Python (Jupyter Notebook)                    |
| Libraries      | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| Visualization  | Tableau                                       |
| Version Control| Git & GitHub                                  |

---

##  Approach & Methodology

- Data Cleaning: Removed duplicates, handled missing values, balanced classes (SMOTE)  
- EDA: Identified trends and visual correlations related to churn  
- Modeling: Tested Logistic Regression, Random Forest, and Gradient Boosting  
- Evaluation: Measured accuracy, precision, recall, feature importance  

---

##  Key Visual Insights

- **More than 3 service calls → higher churn risk**  
  ![Customer Service Calls](images/customer_service_calls_vs_churn.png)

- **Customers with international plans tend to leave**  
  ![International Plan](images/international_plan_vs_churn.png)

- **High charges often lead to customer dissatisfaction**  
  ![Total Charges](images/total_charges_vs_churn.png)

- **Voice mail users are more loyal**  
  ![Voicemail](images/voicemail_vs_churn.png)

---

##  Model Results

| Metric     | Score  |
|------------|--------|
| Accuracy   | 92%    |
| Precision  | 90%    |
| Recall     | 94%    |

**Top 5 Influential Features**:

- Customer service calls  
- International plan  
- Total day charges  
- Evening minutes  
- Voice mail plan  

---

##  Business Insights

| Insight                                   | Action                                              |
|-------------------------------------------|-----------------------------------------------------|
| High number of service calls = higher churn | Trigger support intervention after 3+ calls       |
| International plan customers churn more     | Offer retention-focused bundles                     |
| High charges lead to churn                   | Review billing transparency & offer discounts      |
| Voice mail users churn less                  | Promote voice mail plan as loyalty add-on           |
| Early churn risk detection improves campaigns | Use model scores in targeted outreach strategies  |

---


 🔗 **Email**: [Abdimohammedfarhan@gmail.com]
 

> *Built with curiosity, creativity, and a drive to solve real problems.*

