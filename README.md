
# 📊 Tableau Dashboard Project – Business Overview (Superstore Dataset)

## 🎯 Objective:
To create an **interactive Tableau dashboard** that allows business stakeholders to monitor **sales, orders, and profit trends** across time, product categories, and sub-categories using the **Superstore dataset**.

---

## 🛠 Tools Used:
- **Tool:** Tableau Public (Desktop Edition)  
- **Dataset:** Superstore CSV Dataset

---

## 📂 Dashboard Features (Sheets Used):

### 1️⃣ **Key Metrics Card – `KEYMETRICS`**
Displays high-level KPIs to provide a quick business snapshot.

| Metric         | Value         |
|----------------|---------------|
| Total Sales    | $2,297,201   |
| Total Profit   | $286,397     |
| Total Orders   | 9,994         |

✔ Used SUM and COUNT aggregations  
✔ Clean formatting for executive reporting

---

### 2️⃣ **Sales Over Time – `SALES OVER TIME`**
Line chart showing **year-over-year sales** performance.

| Year | Total Sales (USD) |
|------|-------------------|
| 2018 | $484,247         |
| 2019 | $609,206         |
| 2020 | $470,533         |
| 2021 | $733,215         |

✔ Time-series analysis using `YEAR(Order Date)`  
✔ Visual insights into growth or dips in sales

---

### 3️⃣ **Sales by Product – `SALES BY PRODUCT`**
Bar chart comparing **total sales by product category**.

| Category         | Sales (USD) |
|------------------|-------------|
| Technology       | $836,154   |
| Furniture        | $742,000   |
| Office Supplies  | (approximate based on chart) |

✔ Easy comparison of product category performance  
✔ Helpful for inventory and marketing strategies

---

### 4️⃣ **Profit by Sub-Category – `PROFIT BY SUB CATEGORY`**
Visual breakdown of **profitability per sub-category**.

| Sub-Category     | Profit (USD) |
|------------------|--------------|
| Copiers          | $55,618     |
| Phones           | $44,516     |
| Accessories      | $34,054     |
| Bookcases        | –$17,725    |
| Supplies         | –$12,725    |

✔ Color-coded (green = profit, red = loss)  
✔ Identifies top profit and loss-making areas

---

### 5️⃣ **Business Overview Dashboard – `BUSINESS OVERVIEW DASH`**
Integrated dashboard combining:
- `Key Metrics`
- `Sales Over Time`
- `Sales by Product`
- `Profit by Sub-Category`

🧩 Filters available:
- Year of Order Date
- Category (Furniture, Office Supplies, Technology)
- Sales Range
- Profit Range

✔ Summary view for quick decision-making  
✔ Filter-enabled for deep-dive exploration

---

### 6️⃣ **Final Summary – `SUMMARY`**
#### ✅ Conclusion:
The Business Overview Dashboard presents a **clean, interactive summary** of sales and profit performance. It enables stakeholders to:
- Spot trends
- Compare product performance
- Recognize areas needing attention

#### 💡 Recommendations:
- Invest more in profitable, high-growth products (e.g., Technology, Copiers).
- Investigate and optimize loss-making sub-categories (e.g., Bookcases, Supplies).

---

## 🧭 Navigation Guide:
Use the tabs at the bottom of the Tableau workbook:
- `KEYMETRICS`
- `SALES OVER TIME`
- `SALES BY PRODUCT`
- `PROFIT BY SUB CATEGORY`
- `BUSINESS OVERVIEW DASH`
- `SUMMARY`
