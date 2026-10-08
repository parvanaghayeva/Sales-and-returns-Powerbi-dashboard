


# 📊 Sales and Returns Power BI Dashboard

An interactive **Power BI** dashboard built on the **AdventureWorks** sample data. It analyzes customer segments, product performance, returns, and progress against sales targets in one place.

## 🎯 Project Goals

- Identify who orders the most (gender, status, occupation, age)
- Track monthly order and revenue trends
- Drill into individual products by revenue, orders, and returns
- Compare actual results against targets

## 🖼️ Dashboard Pages

### 1. Customer Analysis
Total order quantity per customer, gender / status / occupation breakdowns, an age treemap, and the monthly orders-vs-revenue trend.

### 2. Product Results
Total revenue, orders, and returns for a selected product (example: **HL Mountain Tire**), plus yearly quantity and revenue trends and daily returns.

### 3. Category and Targets
Sales by category and subcategory, a product-level table, date and continent filters, and target KPIs for revenue, orders, and returns.


## 📌 Key Metrics

| Metric | Actual | Target | Variance |
|---|---|---|---|
| Revenue | $1.83M | $1.95M | -6.08% |
| Orders | 2,146 | 2.38K | -9.89% |
| Returns | 167 | 185.90 | +10.17% (better than target) |

- **Total quantity sold:** 84,174
- **HL Mountain Tire:** $45.68K revenue, 1,305 orders, 49 returns

## 🔍 Key Insights

- **Gender split is nearly even:** about 42K male and 41K female customers.
- **Around 90% of customers are in the "Low" status group** (~76K), with "Medium" at about 8.7%.
- **Professional is the largest occupation group** (~31%), followed by Skilled and Management.
- **Seasonality:** orders and revenue peak in May–June and drop sharply in July (this may be because the data range ends on 30 June 2017).
- **Top-selling products:** Mountain Tire Tube (11.31%), AWC Logo Cap (8.19%), Fender Set - Mountain (7.85%), Mountain Bottle Cage (7.53%).
- **By category,** Accessories dominates sales, and Tires and Tubes is the top subcategory.
- Revenue and order targets were not fully met, while returns performed better than target.

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX** (measures such as total_orders, total_revenues, total_quantity, % all_orders)
- **Power Query** (data cleaning and transformation)
- Data model: AdventureWorks (Sales, Products, Customers, Returns, Territories)

## 📂 Repository Structure

```
Sales-and-returns-Powerbi-dashboard/
├── README.md
├── AdventureWorks_Dashboard.pbix
├── screenshots/
│   ├── 01_customer_analysis.png
│   ├── 02_product_results.png
│   └── 03_category_targets.png
└── data/
```

## ▶️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/parvanaghayeva/Sales-and-returns-Powerbi-dashboard.git
   ```
2. Open `AdventureWorks_Dashboard.pbix` with **Power BI Desktop**.
3. If needed, update the data source path under **Transform data → Data source settings**.

> Note: If the map visual is disabled, enable it in Power BI under **File → Options and settings → Options → Global → Security**.

## 👤 Author

**Your Name**
- LinkedIn: [(https://linkedin.com/in/parvanaaghayeva)](https://www.linkedin.com/in/parvana-aghayeva-90482a213?utm_source=share_via&utm_content=profile&utm_medium=member_ios)
- GitHub: [@parvanaghayeva](https://github.com/parvanaghayeva)

## 📄 License

This project is for educational and portfolio purposes. Data source: Microsoft AdventureWorks sample database.
