# E-Commerce Sales Analysis

## Project Overview

This project analyzes an e-commerce sales dataset to understand overall sales performance, product performance, customer demand patterns, geographical sales distribution, and order operations.

The analysis was performed using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.

---

## Data Cleaning and Preparation

The dataset contained **128,949 records**. Before performing the analysis, the following data-cleaning steps were completed:

- Checked for missing values and duplicate records.
- Filled missing values in the **currency** column with `INR`.
- Replaced missing values in **Courier Status** with `Not Available`.
- Investigated missing values in the **Amount** column.
- Created an `Amount_clean` column for cleaning and analysis purposes.
- Replaced missing amounts for cancelled orders with `0`.
- Created a **Promotion_Status** column to identify orders associated with promotions.
- Removed the `fulfilled-by` column because approximately **69.55%** of its values were missing and it provided limited analytical value.
- Removed the `Unnamed: 22` column because it contained only missing values and `0`.

---

## Key Performance Indicators (KPIs)

- **Total Revenue:** ₹78.58 Million
- **Total Quantity Sold:** 116,651 units
- **Total Unique Orders:** 120,352
- **Average Order Value (AOV):** ₹652.88
- **Average Quantity per Order:** 0.97 units

---

## Key Business Insights

### 1. Sales Trend

The dataset covers sales primarily from **March to June 2022**.

- **April 2022** generated the highest monthly sales.
- Highest monthly revenue was approximately **₹28.83 Million**.
- Sales declined after April:
  - April: ₹28.83 Million
  - May: ₹26.22 Million
  - June: ₹23.42 Million

This indicates that April was the strongest recorded month, followed by a gradual decline in sales during the following months.

---

### 2. Category Performance

The **Set** category was the strongest-performing product category.

- **Highest Revenue Category:** Set
- **Revenue Generated:** Approximately ₹39.20 Million
- **Highest Quantity Sold:** Set — 45,288 units
- **Highest Number of Orders:** Set — 47,836 unique orders

Revenue contribution by major categories:

- **Set:** 49.88%
- **kurta:** 27.10%
- **Western Dress:** 14.27%
- **Top:** 6.81%

Together, the **Set and kurta categories contribute nearly 77% of total revenue**, showing that these categories are the major drivers of business sales.

The category with the lowest sales was **Dupatta**, generating only approximately ₹915 in recorded revenue.

---

### 3. Product Performance

The best-performing product based on quantity and number of orders was:

- **Product/Style:** JNE3797
- **Highest Quantity Sold:** 3,693 units
- **Highest Number of Orders:** 4,205
- **Highest Revenue Contribution:** JNE3797
- **Contribution to Total Revenue:** Approximately 3.73%

This product appears to be one of the most important individual products in the dataset.

---

### 4. Size Analysis

The most popular size was **M**.

- **Most Sold Size:** M
- **Number of Records/Sales:** 22,705
- **Highest Revenue Generating Size:** M
- **Revenue Generated:** Approximately ₹13.90 Million
- **Revenue Contribution:** Approximately 17.70%

Other major revenue-generating sizes include **L, XL, XXL, and S**.

This suggests that inventory planning should prioritize medium and commonly purchased sizes.

---

### 5. Geographic Analysis

**Maharashtra** was the strongest-performing state.

- **Highest Sales Revenue State:** Maharashtra
- **Revenue Generated:** Approximately ₹13.33 Million
- **Highest Number of Orders:** 20,777

**Bengaluru** was the strongest-performing city.

- **Highest City Revenue:** Approximately ₹6.85 Million
- **Highest Number of Orders:** 10,452
- **Highest Quantity Sold:** 10,420 units

These locations represent important markets for the business and could be prioritized for inventory, marketing, and customer retention strategies.

---

### 6. Order and Operational Analysis

The analysis identified:

- **Shipped Orders:** 72,789
- **Cancelled Orders:** 17,196
- **Returned to Seller Orders:** 1,851

The notebook calculated a cancellation rate of approximately **13.34%**.

A relatively high number of cancelled orders indicates an area that could be investigated further to understand possible reasons such as product availability, payment issues, delivery problems, or customer behavior.

---

## Business Recommendations

Based on the analysis, the following actions could help improve business performance:

1. **Prioritize high-performing categories** such as Set and kurta, as they generate the majority of revenue.
2. **Maintain sufficient inventory for popular sizes**, especially M, L, and XL.
3. **Focus marketing efforts on high-performing markets** such as Maharashtra and Bengaluru.
4. **Investigate the decline in sales after April** to identify potential seasonal or operational factors.
5. **Analyze cancellation reasons** to reduce the cancellation rate and improve order conversion.
6. **Promote high-performing products**, particularly JNE3797 and other top revenue-generating styles.
7. **Review low-performing categories** to determine whether they require improved marketing, pricing changes, or reduced inventory.

---

## Conclusion

This project demonstrates an end-to-end exploratory data analysis workflow, including **data cleaning, KPI calculation, sales trend analysis, product analysis, size analysis, geographic analysis, and operational analysis**.

The analysis shows that the business is strongly driven by a small number of product categories, particularly **Set and kurta**, while **Maharashtra and Bengaluru** are key geographical markets. The results can help support data-driven decisions related to inventory management, product strategy, marketing, and operational improvement.

## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Excel
