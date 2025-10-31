# 📊 Sales-and-Customer-Insights Analysis

This repository presents a comprehensive analysis of sales performance, customer behavior, and product trends across multiple categories, regions and countries. 
## Dataset descriptions
| Dataset       | Fields                                           |
|---------------|--------------------------------------------------|
| Sales         | Transactions;Revenue;Date;Discount;Region        |
| Products      | Products;Categories;Subcaetgories;Supplier       |
| Customer      | Demographics;Loyalty Status;Country;Revenue      |


The insights are drawn from a finalized dataset covering six months of operations, and are intended to guide strategic decisions in procurement, marketing, and inventory planning.

The objective is to create an interactive Sales & Customer Performance Dashboard in Power BI that answers:

* Which products generate the most revenue?
* Who are our top customers by sales and loyalty status?
* How do sales trends vary across regions and over time?
* Which product categories contribute the most to business growth?
---

## Methodology

### 1. Data Cleaning (Power Query)
### 2. Feature Engineering (Power Query)
- **Discount Amount**=Discount/100*Raw Revenue
- **Net Revenue**=Raw Revenue-Discout Amount
### 3. Data Analysis (Power BI)
- **Relationship Modelling**
     - Sales<->Products(ProductID)
     - Sales<->Customers(CustomerID)

- **Calculated Measures(DAX)**
     - Total Revenue
     - Total Quantity
     - Top Customer
     - Avg Customer
     - Avg Discount

### 3. Visualization (Power BI)
   - Dashboard( Revenue)
   - Dashboard (Products)
   - Dashboard (Customers)
## 🧾 Summary

- **Total Revenue:** $106.44K  
- **Total Quantity Sold:** 220 units  
- **Average Order Value:** $2.13K  
- **Average Discount:** $280  

---

## 🛍️ Product Performance

- **Top Product by Revenue:** Product 12 ($14.3K)  
- **Top Product Subcategory by Revenue:** Laptop ($29.9K)  
- **Top Product Category by Revenue:** Furniture ($65.4K)  
- **Top Supplier by Count:** Supplier A (8 products)  

### 🔢 Quantity Sold by Subcategory
| Subcategory | Quantity |
|------------|----------|
| Laptop     | 62       |
| Table      | 57       |
| Mobile     | 46       |
| Sofa       | 29       |
| Shirt      | 26       |

---

## 📅 Monthly Trends

- **Peak Revenue Months:** April($35k) and June($21K)  
- **Quantity Sold Monthly:** Highest in April (53 units), followed by May (42 units)  
- **Revenue by Month:** Stedy rise from March and a dip in May by 65.7% against June.

---

## 🌍 Regional & Gender Insights

### Revenue by Region
| Region | Revenue |
|--------|---------|
| North  | $29K    |
| East   | $28K    |
| West   | $25K    |
| South  | $24K    |


### Revenue by Gender
| Gender | Revenue |
|--------|---------|
| Male   | $96.75K |
| Female | $9.68K  |

---

## 👥 Customer Overview

- **Top Customer by Revenue:** CUST001 ($20.4K)  
- **Average Customer Age:** 38  
- **Top Country by Customer Count:** France  
- **Top Loyalty Status:** Bronze (8 customers)  

---

## 📁 Dashboard Overview

<img width="850" height="489" alt="Screenshot 2025-10-31 013614" src="https://github.com/user-attachments/assets/ffda83a9-556d-4083-872e-72755fc155ec" />

---

<img width="855" height="490" alt="Screenshot 2025-10-31 013643" src="https://github.com/user-attachments/assets/a12e623d-b866-4e5e-b8e8-5cf218aea48f" />

---

<img width="841" height="491" alt="Screenshot 2025-10-31 013555" src="https://github.com/user-attachments/assets/0aa703dd-21a6-421e-b91e-46f9603877e1" />


---


## Recommendations

### 1. Prioritize High-Performing Categories
- Focus on furniture and electronics, especially laptops and tables.
- Strengthen supplier relationships and ensure stock availability for fast-moving items.

### 2. Address Revenue Decline
- Investigate causes of the 65.7% drop from June to May.
- Launch mid-year campaigns and loyalty incentives to boost Q3 performance.

### 3. Optimize Regional Strategy
- Tailor promotions and inventory to top-performing regions: North, East, and West.
- Consider localized marketing and regional bundles.

### 4. Refine Customer Targeting
- Explore why female engagement is low and adjust product mix or messaging.
- Identify and reward high-value customers with exclusive perks.

### 5. Enhance Loyalty Program
- Encourage progression from Bronze to Silver and Gold tiers.
- Offer tiered benefits such as discounts, free shipping, and priority access.

### 6. Improve Inventory Planning
- Use subcategory trends to guide reorder points and safety stock levels.
- Implement automated alerts for fast-moving items.

### 7. Reassess Discount Strategy
- Evaluate the impact of $280 average discounts on margins.
- Shift toward value-added promotions like bundles or loyalty rewards.

---


## Explore Dashboard
https://app.powerbi.com/view?r=eyJrIjoiY2E4ZjQ2MmYtNzU2MS00ZDZlLWI2YTMtNjFhNmVlNzEyZDcwIiwidCI6IjFlNTZjNTMwLWI0NzUtNGY5OC1hN2E4LWQwYWVhODc4OTJhMSJ9



