# 🍕 Pizza Sales Analysis – Business Insights

## 📌 Overview
This project analyzes the sales data of a pizza restaurant to uncover **key business insights and patterns**.  
The goal is to understand customer behavior, identify top-performing products, and highlight trends that can drive smarter business decisions.

The analysis covers:
- 📊 Headline KPIs (total sales, revenue, AOV, items per order)  
- 🥇 Top-selling pizzas and revenue concentration  
- 📏 Distribution of pizza sizes sold  
- 🧄 Ingredient analysis (most common ingredients across the menu)  
- 📅 Trends by day of week and time of day  

---

## 📂 Dataset
The dataset contains **one year of sales records**, split into 4 tables:
- **orders** – order-level information (order_id, date, time)  
- **order_details** – mapping of orders to pizzas with quantities  
- **pizzas** – pizza variants (size, price)  
- **pizza_types** – broader pizza categories and ingredient lists  

👉 Total: ~40k pizzas sold, ~4k orders, 65 pizza variants, 32 pizza types.  

---

## ⚙️ Tech Stack
- **Python** (Pandas, NumPy)  
- **Visualization**: Matplotlib, Seaborn  
- **Jupyter Notebook**  

---

## 📊 Key Analyses & Insights

### 1. Headline KPIs
- **Total Pizzas Sold:** ~40,000  
- **Total Revenue:** ~$800,000  
- **Total Orders:** ~4,000  
- **Average Order Value (AOV):** ~$38  
- **Average Items per Order:** 2.7  
- **Concentration:** Top 6 pizzas account for **50%+ of all sales**  

---

### 2. Top-Selling Pizzas
- *Classic Deluxe*, *Barbecue Chicken*, and *Hawaiian* are the clear leaders.  
- Strong sales concentration → menu optimization opportunities.  

*(Example visualization in notebook: Top 10 pizzas bar chart)*  

---

### 3. Pizza Sizes
- **Large (L)** is the most popular size, followed by **Medium (M)**.  
- XL/XXL sizes underperform – but they are available for only one pizza type.  

---

### 4. Ingredients Analysis
- Most common ingredients: **Mozzarella, Tomatoes, Red onions, Mushrooms**.  
- Ingredient frequency helps understand customer preferences and cross-sell opportunities.  

---

### 5. Time-Based Trends
- Peak demand during **weekend evenings** (Fri–Sun, 6–9 PM).  
- Weekdays show steady but lower volume.  
- Clear opportunities for **staff scheduling and targeted promotions**.  

---

## ✅ Business Recommendations
1. **Focus marketing on top 6 pizzas** that already drive >50% of sales.  
2. **Upsell during peak hours** (weekend evenings) → bundles or meal deals.  
3. **Reevaluate XL/XXL offerings** – low sales suggest limited appeal.  
4. **Promote ingredient-based specials** around popular items (mozzarella, mushrooms).  

---

## 📸 Example Outputs



---

## 🚀 How to Run
1. Clone this repo  
2. Open `Pizza_Analysis_Notebook.ipynb` in Jupyter Notebook or JupyterLab  
3. Run all cells – datasets should be placed in the same folder (`orders.parquet`, `order_details.parquet`, `pizzas.csv`, `pizza_types.csv`)  

---

## 🧑‍💻 Author
Project by **Tomasz Cielepak** – Data Analyst / Data Enthusiast.  
Feel free to check out more projects on [GitHub]((https://github.com/TomaszCielepak/)).  
