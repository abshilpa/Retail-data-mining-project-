# 🛒 Retail Data Mining Project (SQLite + Python)

## 📌 Overview

This project demonstrates how to design and analyse a simulated retail database using SQLite and Python. The focus is on building an ethical, scalable, and realistic dataset without using real personal data.

The system models a retail environment with products, customers, and orders, enabling meaningful data analysis and business insights.

## 🎯 Objectives
Create a synthetic retail dataset using Python

Design a normalized relational database schema

Perform data analysis using SQL queries

Ensure ethical data practices (no real user data)

## 🧰 Tech Stack
Python

SQLite

Pandas

NumPy

Faker (for synthetic data generation)

## 🗂️ Database Schema

1. Products Table

Stores product-related information:

ProductID (Primary Key)
Category
Price
Stock Level
Rating
Sales Volume
Discount Rate
Discounted Price

2. Customers Table

Stores customer information:

CustomerID (Primary Key)
Name
Age
Gender
Membership Level
Sign-Up Date
Last Purchase Date
Total Spent

3. Orders Table

Captures transactional data:

OrderID (Primary Key)
CustomerID (Foreign Key)
ProductID (Foreign Key)
Quantity
Order Date
Shipping Method
Order Total

## 🔗 Relationships
Each order links customers and products
Foreign keys ensure data integrity
Supports many-to-many relationships

## ⚙️ Data Generation Process
Used Faker to generate realistic but fake data
Used NumPy for randomness and variability
Generated:
1000+ products
Multiple customers
Orders linking both

## 📊 Example Queries
🔍 Selection Queries
Retrieve all products in the Electronics category
Find customers with Gold membership

## 🔗 Join Queries
Combine orders with customer data to analyse:
Customer name
Membership level
Order value

## 📈 Aggregation Queries
Average order value by shipping method
Total sales by product category

## 💡 Key Features
✔️ Fully normalized database design
✔️ Realistic synthetic dataset
✔️ Supports complex SQL queries
✔️ Scalable structure for analysis

## 🔐 Ethics & Data Privacy

This project strictly avoids real personal data:

Uses synthetic data only
Aligns with GDPR principles
Ensures privacy and data protection

## 🚀 How to Run

Clone the repository:
git clone https://github.com/your-username/your-repo-name.git

Install dependencies:
pip install pandas numpy faker
Run the Python script to:
Generate data
Create SQLite database
Insert records

## 📌 Use Cases
Data analysis practice
SQL learning
Database design understanding
Retail analytics simulation

## 📈 Future Improvements
Add dashboards (Power BI / Tableau)
Integrate machine learning models
Build API for data access
Expand dataset complexity

## 👩‍💻 Author

Shilpa Abbugari
Data Analyst | Python | SQL | BI Tools
