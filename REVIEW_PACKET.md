# E-Commerce Sales & Profitability Analysis

## Project Overview

This project analyzes an e-commerce dataset to uncover trends in sales, profit, and customer segments. The goal is to identify high-performing categories, seasonal trends, and business inefficiencies.

---

## Dataset

* Source: Superstore Dataset
* Format: Excel (.xls)
* Contains:

  * Sales
  * Profit
  * Category and Sub-category
  * Customer Segment
  * Order Date

---

## Key Analysis Performed

### Monthly Profit Analysis

* Identified highest and lowest profit months
* Applied moving average to detect trends

### Monthly Sales Trend

* Analyzed sales peaks and dips across months
* November observed as peak sales period

### Profit by Sub-Category

* Best Performer: Copiers
* Worst Performer: Tables (loss)

### Profit Distribution

* Technology contributes the highest profit (~50%)
* Furniture contributes the least

### Sales by Sub-Category

* Phones and Chairs generate the highest revenue
* Fasteners and Labels are the lowest

### Sales to Profit Ratio

* Home Office segment is the most efficient
* Consumer segment has the lowest efficiency

---

## Key Insights

* High sales does not always mean high profit (e.g., Tables)
* Technology category drives overall profitability
* Seasonal spikes observed in Q4 (October to December)
* Certain categories require cost optimization

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Visualizations

### Monthly Profit Trend

![Profit](outputs/monthly_profit_analysis.png)

### Monthly Sales Trend

![Sales](outputs/monthly_sales_trend.png)

### Profit by Sub-category

![Profit Sub](outputs/profit_analysis_by_subcategory.png)

### Profit Distribution

![Category](outputs/profit_distribution_by_category.png)

### Sales by Sub-category

![Sales Sub](outputs/sales_by_subcategory.png)

### Sales to Profit Ratio

![Ratio](outputs/sales_to_profit_ratio.png)

---

## How to Run

```bash
git clone https://github.com/your-username/E-Commerce-Sales-Profit-Analysis.git
cd E-Commerce-Sales-Profit-Analysis
pip install -r requirements.txt
jupyter notebook
```

---

## Business Recommendations

* Reduce losses in Furniture, especially Tables
* Invest more in the Technology category
* Improve pricing or cost structure for low-margin products
* Focus marketing efforts during high-performing months (Q4)

---

## Contact

For queries or collaboration, feel free to connect.
