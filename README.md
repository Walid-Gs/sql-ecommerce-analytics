# SQL E-Commerce Analytics & Power BI Dashboard

## Project Overview

This project is a complete end-to-end Business Intelligence and Analytics solution built using PostgreSQL and Power BI on the Brazilian Olist E-Commerce dataset.

The objective was to simulate a real-world analytics workflow used by Data Analysts and Business Intelligence professionals, starting from raw transactional data and ending with executive-level dashboards and business recommendations.

The project covers:

* Database design and schema creation
* Data loading and validation
* Exploratory SQL Analysis
* Customer Analytics
* Product Analytics
* Seller Analytics
* Advanced Business Analytics
* Data Mart creation using SQL Views
* Interactive Power BI dashboards

---

## Business Objectives

The goal of this project is to answer key business questions such as:

* How is the company performing over time?
* Which products generate the most revenue?
* Which customers contribute the most value?
* Who are the best-performing sellers?
* What drives customer satisfaction?
* How efficient is the delivery process?
* Which business areas should management focus on?

---

## Dataset

Dataset: Olist Brazilian E-Commerce Dataset

The dataset contains information about:

* Customers
* Orders
* Payments
* Products
* Sellers
* Reviews
* Geolocation
* Product Categories

Total records: 100,000+ orders

---

## Database Design

The project was built in PostgreSQL using a relational data model.

Main Tables:

* customers
* orders
* order_items
* order_payments
* order_reviews
* products
* sellers
* geolocation
* product_category_translation

Relationships were implemented using primary keys and foreign keys to ensure data integrity.

---

## SQL Analysis

### Business EDA

Key metrics analyzed:

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value
* Revenue by State
* Revenue by Payment Type
* Monthly Performance

### Customer Analytics

Analysis included:

* Top Customers
* Customer Lifetime Value
* Customer Segmentation
* Geographic Distribution
* Customer Purchase Behavior

### Product Analytics

Analysis included:

* Top Categories by Revenue
* Best-Selling Products
* Category Revenue Contribution
* Product Satisfaction Analysis
* Revenue vs Customer Ratings

### Seller Analytics

Analysis included:

* Top Sellers by Revenue
* Top Sellers by Order Volume
* Revenue Share Analysis
* Seller Rankings
* Seller Review Performance
* Delivery Performance Analysis

### Advanced Business Analytics

Advanced SQL techniques used:

* CTEs
* Window Functions
* Ranking Functions
* Running Totals
* Moving Averages
* Month-over-Month Growth
* Revenue Trends

---

## Data Mart Creation

To optimize dashboard development, multiple analytical views were created:

* vw_monthly_revenue
* vw_customer_summary
* vw_product_performance
* vw_seller_performance
* vw_delivery_performance
* vw_category_performance

These views act as a reporting layer between the database and Power BI.

---

## Power BI Dashboard

The dashboard consists of:

### Executive Overview

High-level KPIs and business performance.

### Customer Analytics

Customer value, segmentation, and geographic distribution.

### Product Analytics

Category performance, revenue contribution, and customer satisfaction.

### Seller Analytics

Seller performance, rankings, revenue share, and review quality.


---

## Key Insights

* Revenue is concentrated among a limited number of product categories.
* Several high-revenue categories maintain strong customer satisfaction.
* Some categories generate substantial revenue despite low review scores, representing operational risk.
* Seller performance varies significantly across regions.
* Faster delivery performance is generally associated with better customer ratings.
* Business growth trends indicate strong scalability opportunities.

---

## Technologies Used

* PostgreSQL
* SQL
* pgAdmin
* Power BI
* DAX
* Git
* GitHub

---

## Skills Demonstrated

* SQL Querying
* Data Cleaning
* Data Validation
* Joins
* Aggregations
* CTEs
* Window Functions
* Ranking
* Business Analytics
* KPI Development
* Data Modeling
* Dashboard Design
* Data Storytelling

---

## Future Improvements

* Customer Segmentation using RFM Analysis
* Forecasting Models
* Churn Prediction
* Recommendation Systems
* Real-Time Dashboard Integration

---

## Author

Oualid GASMI

Aspiring Data Analyst & Data Scientist

