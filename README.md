# 🛍️ Market Basket Analysis – Instacart Dataset

This project performs Market Basket Analysis using the Apriori algorithm on a synthetic supermarket dataset. The goal is to find product pairings that are frequently bought together and derive business insights for promotions and layout.

---

## 📂 Dataset Preview
- 500 orders, 30+ products
- Format: order_id, product_name

---

## 🧹 Preprocessing
- Grouped products per order
- Converted to one-hot encoded basket format

---

## ✅ Frequent Itemset Mining (Apriori)
- Mined frequent combinations with min support = 5%

---

## 🔗 Association Rule Mining
- Extracted rules with confidence & lift
- Filtered top 10 by lift

---

## 📊 Visualization
- Bar chart of top consequent items by lift

---

## 💡 Business Insights
- High lift for `bread → butter`, `pasta → sauce`, `shampoo → conditioner`
- Use these to optimize:
  - Product bundling
  - Aisle layout
  - Cross-selling promotions

---

## 👤 Author
**Suvathi Mariyappan Lakshmi**  
[LinkedIn](https://linkedin.com/in/suvathi-m) • [Tableau Portfolio](https://public.tableau.com/app/profile/suvathi.mariyappan.lakshmi/vizzes)
