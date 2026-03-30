# Retail Data EDA

This project performs a preliminary **Exploratory Data Analysis (EDA)** on a synthetic retail dataset to identify data quality issues and behavioral trends.

---

## 📊 Project Overview
The analysis focuses on cleaning and visualizing a dataset of 200 orders across four cities (**Mumbai, Delhi, Bangalore, Chennai**) and four categories (**Electronics, Clothing, Groceries, Furniture**).

### **Key Objectives**
* **Data Cleaning:** Identify and quantify missing values (NaNs).
* **Outlier Detection:** Spot extreme values in `order_value` (e.g., $95,000$ vs. a median of ~$2,934$).
* **Correlation:** Determine if order price impacts delivery speed.

---

## 🛠️ Technical Stack
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`

---

## 📈 Summary of Findings

| Metric | Observation |
| :--- | :--- |
| **Missing Data** | `rating` has the highest null rate (16%), followed by `order_value` (7%). |
| **Price Distribution** | Heavily right-skewed due to manual outliers ($87k$ and $95k$). |
| **Delivery Speed** | Uniformly distributed between 1–15 days with a mean of ~7.8 days. |
| **Correlation** | Near-zero correlation between value and delivery time ($r \approx 0$). |

---

THANK YOU
