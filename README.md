# AdventureWorks Sales Overview Dashboard

**An interactive Power BI dashboard that analyzes multi-year sales performance using the AdventureWorks dataset.**  
It provides insight into revenue, cost, and profit trends by product, region, customer type, and sales channel.

---
## Dataset Overview
- Based on the AdventureWorks dataset (publicly available)
- Includes multiple worksheets (Sales, Products, Customers, Territories, etc.)
- Modeled and cleaned using Power Query
  
---

## Dashboard Highlights

| KPI                        | Value        |
|----------------------------|--------------|
| **Total Revenue**          | $102.6M      |
| **Total Cost**             | $102.0M      |
| **Total Profit**           | $441.9K      |
| **Profit Margin**          | 0.43%        |
| **Total Orders**           | 31K          |
| **Total Products**         | 350          |
| **Online Customers**       | 18K          |
| **Resellers**              | 635          |

---

## Key Insights

1. **Sales Channels**:
   - **Internet** contributed **74.59%** of total revenue.
   - **Reseller channel** accounted for the remaining **25.41%** but posted a **net loss of -$7.6M**.

2. **Top Product Categories by Revenue**:
   - **Road Bikes** ($41M), **Mountain Bikes** ($34M), and **Touring Bikes** ($13M) were the top-performing subcategories.

3. **Regional Performance**:
   - **North America** dominated sales (71.85% of total revenue).
   - **Europe** followed with 22.44%, and **Pacific** regions contributed 5.71%.
   - Profit by country varied sharply, with the **United States** leading and **Germany** and **Australia** reporting losses.

4. **Profitability by Product**:
   - Some Road Bike models (e.g. *Road-150 Red*) posted strong margins (up to 19.2%).
   - Others (e.g. *Road-250 Red*) operated at a loss (up to -4.9%), indicating potential overpricing or high cost structure.

5. **Year-over-Year Performance**:
   - Profit improved significantly in **2013**, but dropped sharply in **2014** due to a collapse in revenue and order volume.

---

## Visuals Included

- **KPI Cards** for sales, profit, margin, and customer counts
- **Line Chart**: Revenue and profit trends over time
- **Bar Chart**: Top and Bottom 10 subcategories by revenue
- **Pie/Donut Charts**: Revenue by channel and region, Expense Breakdown
- **Map**: Profit by country
- **YoY Summary Table**: Revenue, expense, profit, and margin by year

---

## Tools Used

- **Power BI Desktop** – data modeling, visualization, DAX
- **Excel** – data import, table preparation
- **DAX Measures** - Revenue, Profit, Cost, Profit Margin, YoY comparisons

---

## Dashboard Preview

![image alt](https://github.com/hoaiphuongpham/sales-overview-analysis/blob/51fd0bb2fd1fdc8c445f2a0e0721ed23571204bb/Screenshot_page01.jpg)

---

## How to Use

1. Download or clone the repository.
2. Open `Dashboard.pbix` in Power BI Desktop.
3. Review the PDF dashboard or screenshots to explore key metrics.
4. Filter and explore: region, year, product category, channel.

---

## License & Attribution

- Dataset sourced from Microsoft’s **AdventureWorks** (available via [Kaggle](https://www.kaggle.com/datasets/algorismus/adventure-works-in-excel-tables)).
- Dashboard created for educational and portfolio purposes.

---

## File Structure

