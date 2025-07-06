# 📚 Bookstore SQL Analysis

This project involves data analysis on a **Bookstore** using SQL. It covers both **basic** and **advanced** SQL queries to derive business insights from customer, book, and order data.

---

## 🎯 Project Objective

The objective of this project is to perform comprehensive data analysis on a bookstore database using SQL. The analysis focuses on understanding customer behavior, sales performance, inventory management, and identifying trends across genres and authors. The ultimate goal is to provide actionable insights that could help optimize business operations and improve customer satisfaction.

---

## 🗃️ Dataset Description

Three CSV files were used to simulate the bookstore database:

- **Books.csv** — Contains book details (Book_ID, Title, Genre, Price, Author, Stock, etc.)
- **Customers.csv** — Contains customer information (Customer_ID, Name, Country, City, etc.)
- **Orders.csv** — Contains purchase records (Order_ID, Book_ID, Customer_ID, Quantity, Order_Date, Total_Amount, etc.)

> All files are joined using common keys: `Book_ID` and `Customer_ID`

---

## ❓ Key Business Questions

### 🔹 Some Basic Queries
1. Retrieve all books in the **Fiction** genre    
2. List customers from **Canada**  
3. Show orders placed in **November 2023**  
4. Calculate total **stock** available  
5. Get details of the **most expensive** book  

### 🔹Some Advanced Queries
1. Total number of books sold **per genre**  
2. Average price of books in the **Fantasy** genre  
3. Customers who have placed **at least 2 orders**  
4. Most **frequently ordered book**  
5. Top 3 **most expensive Fantasy books**  

---

## 🛠️ Process

1. **Data Cleaning**  
   - Ensured proper data types (dates, numeric fields)
   - Handled missing or inconsistent records

2. **Database Setup**  
   - Imported CSV files into SQL tables
   - Established foreign key relationships using `Book_ID` and `Customer_ID`

3. **Query Execution**  
   - Created and executed SQL queries to answer the listed business questions
   - Used functions like `JOIN`, `GROUP BY`, `ORDER BY`, `HAVING`, `COUNT()`, `SUM()`, `AVG()`, `MAX()`, `MIN()`

4. **Insight Extraction**  
   - Converted raw results into meaningful business insights

---

## 📊 Key Insights

### 🧩 Insights from Basic Queries

- **Genre Inventory**: The bookstore carries a notable number of **Fiction** books, suggesting strong availability in this popular genre.
- **Geographic Reach**: The customer base includes multiple countries, with several customers from **Canada**, showing international reach.
- **Inventory Levels**: The **total stock** across all books is quantified, enabling better management of inventory restocking decisions.
- **Premium Product Identification**: The **most expensive book** was identified, useful for upselling or special promotions.
- **Bulk Orders**: Some customers placed orders with **quantities greater than one**, showing potential for bulk or institutional buying.
- **High-Value Transactions**: Numerous orders had a **total amount exceeding $20**, indicating consistent medium-to-high transaction values.
- **Genre Diversity**: The bookstore offers a **diverse set of genres**, appealing to a broad spectrum of readers.
- **Stock Risks**: The book with the **lowest stock** was identified, helping to proactively prevent stockouts.
- **Revenue Calculation**: The bookstore has generated a quantifiable **total revenue**, offering a baseline for financial analysis.

### 🚀 Insights from Advanced Queries

- **Sales by Genre**: Sales distribution by genre shows which categories perform best in terms of **volume sold**, aiding in genre-based promotions and stocking.
- **Fantasy Pricing**: The **average price** of books in the **Fantasy** genre is identified, which helps evaluate genre pricing strategies.
- **Repeat Customers**: Several customers have placed **2 or more orders**, highlighting opportunities for loyalty and retention programs.
- **Best-Seller Detection**: The **most frequently ordered book** was identified, indicating top demand and potential for featured placements.
- **Premium Fantasy Titles**: The top **3 most expensive Fantasy books** were retrieved, useful for targeting niche, premium readers.
- **Author Performance**: The **quantity of books sold by each author** was calculated, allowing the business to identify popular authors and align marketing or stocking efforts accordingly.
- **High-Spending Locations**: Cities with customers spending **over $30** were pinpointed, enabling location-specific marketing.
- **Top Customer**: The **highest-spending customer** was identified, useful for VIP engagement or personalized incentives.
- **Post-Order Stock Levels**: Remaining **stock after fulfilling all orders** was calculated per book, making it easier to manage replenishment cycles and avoid overstock/understock issues.

---

## 🧩 Final Conclusion

This SQL analysis provides a foundational understanding of the bookstore's sales, inventory, and customer behavior. By leveraging simple and advanced SQL queries, we uncover valuable insights that can support business decisions such as inventory planning, marketing strategies, and customer targeting. With continued analysis and more granular data, this project can evolve into a full-scale analytics dashboard for an online bookstore.

---

## ✅ Skills and Tools Applied

- SQL (Basic & Advanced)
- Data Cleaning & Transformation
- Relational Database Design
- PostgreSQL

---



