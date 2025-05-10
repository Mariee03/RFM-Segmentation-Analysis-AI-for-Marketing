# RFM Segmentation Analysis – AI for Marketing 📊🛍️

This project uses **RFM (Recency, Frequency, Monetary)** analysis to segment customers based on their purchasing behavior. The goal is to enable data-driven marketing strategies by identifying high-value customer groups and tailoring campaigns accordingly.

> Project by: Marie Elyse Bassil – AI for Communication and Marketing, Module 1

---

## 🎯 Objective

Understanding customer behavior is essential to improving retention and boosting revenue. RFM analysis segments customers into actionable groups, and this project also explores how **AI techniques** can support automation and prediction in customer behavior analysis.

---

## 📊 Dataset Overview

The dataset is based on the Brazilian e-commerce platform **Olist**, containing **100k+ orders** between 2016 and 2018. It merges multiple datasets related to:
- Orders
- Customers
- Products
- Payments
- Deliveries

### 🔑 Key Variables
| Column | Description |
|--------|-------------|
| `customer_unique_id` | Unique customer identifier |
| `order_purchase_timestamp` | Purchase date used to calculate recency |
| `payment_value` | Used to calculate total spend (monetary value) |
| `order_id` | Used to calculate purchase frequency |
| `product_category_name_english` | Used for product performance insights |

---

## 🔍 RFM Model Development

- **Recency**: Days since last purchase
- **Frequency**: Number of unique orders
- **Monetary**: Total spending value

Each metric was scored on a **1–4 quartile scale**. The combined RFM score was used for segmentation.

### 🎯 Segments Identified

| Segment | Description |
|---------|-------------|
| 🟣 Diamond | Most valuable: recent, frequent, high spenders |
| 🟡 Gold | Valuable and engaged customers |
| ⚪ Silver | Moderately engaged with average spend |
| 🟤 Bronze | Occasional buyers, low spend |
| ⚫ Steel | Infrequent and low-value customers |

---

## 📈 EDA Highlights

- **Price Distribution**: Highly skewed; some orders over 13,000 units
- **Order Timing**: Peak order activity on Mondays and afternoons
- **Product Performance**: Identified top and underperforming categories
- **Customer Distribution**: Majority in Bronze/Steel; small high-value Diamond group

---

## 🤖 AI Support

- AI techniques can automate segmentation
- Predictive models can anticipate future customer behavior
- Supports scalable personalization and retention strategies

---

## 💼 Business Implications

### 🎯 Targeted Marketing
- Personalize loyalty programs for **Diamond/Gold**
- Re-engage **Steel/Bronze** with promotions and reminders

### 📦 Inventory & Operations
- Align stock with high-performing categories
- Focus support around peak order times for efficiency

---

## 🧠 Recommendations

- Update RFM segments **regularly** to track behavior shifts
- Leverage insights for **cross-selling** and **upselling**
- Integrate predictive modeling to anticipate churn and growth opportunities

---

## 📬 Author

Created by [Marie Elyse Bassil](https://github.com/Mariee03)  
Feel free to fork, explore, or connect!
