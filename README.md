

# Customer Churn Predictor Dashboard

**Objective:**  
To predict customer churn in subscription-based businesses and uncover the key reasons behind it — empowering teams to act *before* users leave.

---

## 📊 Business Context  
In subscription models (SaaS, streaming, etc.), churn directly hits recurring revenue. Retaining customers is cheaper than acquiring new ones — but most teams react after the fact. This project solves that.

---

## 🚀 What This Project Does  
- Predicts **customer churn risk** using a trained classification model  
- Identifies **top features influencing churn**  
- Includes an **interactive simulation tool** to test churn probability across scenarios  
- Visualizes insights that are actionable for marketing, support, and product teams

---

## 🔍 Key Features  
| Module | What It Does |
|--------|---------------|
| **ML Model** | Uses Random Forest Classifier (with ROC-AUC ~0.91, pretty high huh) to detect churn risk |
| **Sim Tool** | Interactive sliders to simulate risk for different user profiles |
| **EDA Visuals** | Graphs highlighting churn by contract, support features, charges, tenure |
| **Business Impact** | Makes churn predictable and actionable, not reactive |

---

## 💡 Why This Matters  
- Reduce churn by identifying at-risk users early  
- Prioritize retention campaigns with data, not assumptions  
- Improve customer lifetime value with smarter engagement  
- Use real signals (like plan type, monthly billing, and support access) to take action

---

## 📌 Sample Insights  
- **Month-to-month users churn the most** — long-term contracts help retain  
- **Higher monthly charges = higher churn risk** if not backed by perceived value  
- **Lack of tech support or online security is a churn red flag**

---

## 📎 Tools Used  
- `Pandas`, `Scikit-learn`, `Seaborn`, `Matplotlib`, `Streamlit`

---

## 📂 Folder Structure  

Built by [Ishita Vasishth](https://www.linkedin.com/in/ishitavasishth/)  
Analytics | Predictive Insights | Curious Human
