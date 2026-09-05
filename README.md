# 🛒 Flipkart Sales Dashboard | Microsoft Excel

## 🎯 Project Objective

The objective of this dashboard is to analyze Flipkart sales performance and provide interactive insights into sales trends, product categories, customer ratings, regional performance, discounts, and payment preferences to support data-driven business decisions.

---

## 📊 Dataset Description

The dataset contains **1,000 Flipkart sales transactions** covering the period from **January 2023 to September 2025**. Each row represents an individual order and includes sales, quantity, product category, customer rating, region, payment method, discount, and order date information.

### Dataset Columns

| **Column**           | **Description**                          |
| -------------------- | ---------------------------------------- |
| **Order_ID**         | Unique identifier for each order         |
| **Product Category** | Category of the product purchased        |
| **Sales Amount**     | Total sales amount for the order         |
| **Quantity Sold**    | Number of units sold                     |
| **Order Date**       | Date on which the order was placed       |
| **Region**           | Region from which the order originated   |
| **Customer Rating**  | Rating given by the customer             |
| **Payment Method**   | Payment method used for the order        |
| **Discount (%)**     | Percentage discount applied to the order |

---

## 🧮 Calculated Columns

* **Year** – Extracted from Order Date for yearly analysis.
* **Month** – Extracted from Order Date for monthly sales analysis.
* **Average Sales Amount** – Calculated to understand the average value of an order.
* **Average Customer Rating** – Calculated to measure overall customer satisfaction.
* **Average Discount (%)** – Calculated to analyze the average discount offered.

---

## 📈 Dashboard Features

### KPI Cards

* Total Sales
* Total Quantity Sold
* Average Sales per Order
* Average Customer Rating
* Average Discount (%)

### Charts

* 📊 Sales by Product Category
* 📈 Monthly Sales Trend
* 📊 Sales by Region
* 🥧 Payment Method Distribution
* ⭐ Average Customer Rating by Category
* 📊 Yearly Sales & Quantity
* 🏷️ Discount by Product Category

### Interactive Filters

* Year
* Month
* Product Category
* Region
* Payment Method

---

## 🔍 Key Insights

### Overall Performance

* **Total Sales:** ₹10.08M
* **Total Quantity Sold:** 4.92K units
* **Total Orders:** 1,000
* **Average Sales per Order:** ₹10.08K
* **Average Customer Rating:** 3.02
* **Average Discount:** 14.45%

### Regional Performance

* **South** is the highest-performing region by sales, generating approximately **₹2.15M**.
* **West** has the lowest sales among the five regions, at approximately **₹1.84M**.
* Sales are relatively close across regions, indicating a fairly balanced regional distribution.

### Category Performance

* **Grocery** is the highest-performing category by sales, generating approximately **₹1.59M**.
* **Electronics** follows with approximately **₹1.47M** in sales.
* **Toys & Baby** records the lowest sales at approximately **₹1.37M**.
* Overall, sales are fairly evenly distributed across the seven product categories.

### Customer Rating

* **Beauty & Health** has the highest average customer rating at approximately **3.18**.
* **Books** follows with an average rating of approximately **3.17**.
* **Grocery** has the lowest average rating at approximately **2.81**.
* The overall average customer rating is approximately **3.02**.

### Payment Method

* **COD** is the most-used payment method with approximately **22% of orders**.
* **Debit Card** follows at approximately **21%**.
* **Credit Card** and **UPI** each account for approximately **20%**.
* The distribution shows that customers use a mix of payment methods rather than relying heavily on one option.

### Monthly Sales Trend

* Sales fluctuate throughout the year rather than following a consistent upward or downward trend.
* **April** records the highest monthly sales at approximately **₹966.8K**.
* **November** records the lowest monthly sales at approximately **₹598.5K**.
* Sales remain relatively strong during months such as **January, May, and July**.

### Yearly Performance

* **2023** records approximately **₹3.70M** in sales.
* **2024** records approximately **₹3.68M** in sales.
* **2025** records approximately **₹2.70M**, with data available only up to September.
* Therefore, 2025 sales should not be directly compared with the complete 2023 and 2024 yearly totals.

### Discount Performance

* **Toys & Baby** has the highest average discount at approximately **15.28%**.
* **Fashion** follows with approximately **14.66%**.
* **Electronics** has the lowest average discount at approximately **13.93%**.
* Overall, discounts remain relatively consistent across categories.

---

## ❓ Business Questions Answered

* What are the total sales and quantity sold?
* What is the average sales value per order?
* Which product category generates the highest sales?
* Which region performs best in terms of sales?
* Which region has the lowest sales?
* How do sales change month by month?
* How does sales performance vary across years?
* Which category has the highest customer rating?
* Which category has the lowest customer rating?
* Which payment method is used the most?
* Which category receives the highest average discount?
* How are sales distributed across categories and regions?

---

## 📝 Conclusion

The Flipkart Sales Dashboard provides a consolidated view of sales performance, product categories, customer ratings, regional performance, discounts, and payment preferences.

The analysis shows **₹10.08M in total sales from 1,000 orders**, with **4.92K units sold** and an average customer rating of **3.02**. Grocery is the leading category by sales, while South is the highest-performing region.

Overall, the dashboard helps identify **sales trends, strong-performing categories and regions, customer preferences, and discount patterns**, making it easier to monitor business performance and support data-driven decisions.

---

## 🛠️ Tools & Techniques

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Slicers
* Excel Formulas
* Data Cleaning
* Data Analysis
* Dashboard Design
* Data Visualization
* Interactive Reporting
