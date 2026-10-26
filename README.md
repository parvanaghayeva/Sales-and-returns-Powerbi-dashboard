# 📊 Sales and Returns Power BI Dashboard

An interactive **Power BI** dashboard built on the **AdventureWorks** sample data. It brings sales performance, product results, returns, and customer profiles together in a three-page report with category, region, and date filters.

📄 [Download the dashboard as PDF](AdventureWorks_Dashbord.pdf)

## 🎯 Project Goals

- Track sales performance against revenue, order, and return targets
- Find the best-selling categories, subcategories, and products
- Analyze a single product in detail (revenue, orders, returns, yearly trend)
- Understand the customer base by gender, status, occupation, and lifestyle profile

## 🖼️ Dashboard Pages

### 1. Sales Overview
Target KPIs (revenue, orders, returns), quantity by subcategory, top 10 products, and the category share of total quantity. Filter by category, region (Europe, North America, Pacific), and date range (1/1/2015 – 6/30/2017).

### 2. Products Result
A drill-down page for a selected product (example: **HL Mountain Tire**) showing total revenue, total orders, total returns, the quantity trend over time, and revenue and returns by year. A back button returns to the overview.

### 3. Customers
Customer-level order quantities, gender / status / occupation breakdowns, the monthly orders-vs-revenue trend, and a customer profile card (gender, marital status, home ownership, education). Includes category and region slicers and a **Clear all slicers** button.


## 📌 Key Metrics

| Metric | Actual | Target | Variance |
|---|---|---|---|
| Revenue | $1.83M | $1.95M | -6.08% |
| Orders | 2,146 | 2.38K | -9.89% |
| Returns | 167 | 185.90 | +10.17% (better than target) |

- **Total quantity sold:** 84,174
- **HL Mountain Tire:** $45.68K revenue, 1,305 orders, 49 returns

## 🔍 Key Insights

**Sales**
- **Accessories dominate sales:** 57,809 units (68.67%), followed by Bikes (13,929) and Clothing (12,436, 14.77%).
- **Tires and Tubes is the top subcategory,** followed by Bottles and Cages and Road Bikes.
- **Top 10 products** include Water Bottle - 30 oz. (9.01%), Road Tire Tube (6.50%), AWC Logo Cap (6.34%), Patch Kit/8 Patches (6.24%), and Touring Tire Tube (5.52%).
- Revenue and order targets were not fully met, while returns performed better than target.

**Product (HL Mountain Tire)**
- Quantity sold grew from July 2016 and peaked around May 2017.
- Revenue was higher in 2017 than in 2016, and returns were also higher in 2017.

**Customers**
- **Gender is nearly balanced:** about 42K male and 41K female records; the profile card shows 51% male and 49% female.
- **About 90% of customers are in the "Low" status group** (~76K); "Medium" is about 8.7%.
- **Professional is the largest occupation group** (~31%), followed by Skilled (~23.5%) and Management.
- **Customer profile:** 66% are homeowners, 51% are single, and 65% have no degree.
- **Orders and revenue peak in May–June** and drop sharply in July, which may be because the data range ends on 30 June 2017.

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
├── AdventureWorks_Dashbord.pdf
└── Screenshorts/
    ├── 01_sales_overview.png
    ├── 02_products_result.png
    └── 03_customers.png
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
- LinkedIn:(https://www.linkedin.com/in/parvana-aghayeva-90482a213/?isSelfProfile=true)
- GitHub: [@parvanaghayeva](https://github.com/parvanaghayeva)

## 📄 License

This project is for educational and portfolio purposes. Data source: Microsoft AdventureWorks sample database.
