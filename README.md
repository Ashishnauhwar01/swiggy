# 🍔 Swiggy SQL Data Analysis Project

<p align="center">

![SQL](https://img.shields.io/badge/SQL-MySQL-blue?style=for-the-badge&logo=mysql)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

</p>

---

## 📖 About the Project

This project analyzes a **Swiggy restaurant dataset** using **SQL** to uncover meaningful business insights.

The project demonstrates how SQL can be used for real-world data analysis by performing filtering, sorting, aggregation, and analytical queries on restaurant data.

Whether you're a beginner learning SQL or someone preparing for interviews, this project provides practical examples of SQL queries applied to a real dataset.

---

## 📂 Project Structure

```
📦 Swiggy SQL Project
│
├── 📄 database swiggi.csv      # Restaurant Dataset
├── 📄 swiggy.sql               # SQL Queries
└── 📄 README.md                # Project Documentation
```

---

## 📊 Dataset Features

The dataset contains information such as:

- 🍽 Restaurant Name
- ⭐ Rating
- 👥 Rating Count
- 🍕 Cuisine
- 💰 Price
- 📍 City
- 🔗 Restaurant Link

---

## 🛠 Tech Stack

- MySQL
- SQL
- CSV Dataset
- MySQL Workbench

---

## 🎯 SQL Concepts Covered

✔ SELECT Statement

✔ WHERE Clause

✔ ORDER BY

✔ LIMIT

✔ Aggregate Functions

✔ Filtering Records

✔ Sorting Data

✔ Data Analysis Queries

✔ Business Insights

---

## 📌 Sample SQL Queries

### Top Rated Restaurants

```sql
SELECT *
FROM database
ORDER BY rating DESC
LIMIT 10;
```

### Restaurants with Rating Above 4.5

```sql
SELECT name, rating
FROM database
WHERE rating > 4.5;
```

### Affordable Restaurants

```sql
SELECT *
FROM database
WHERE cost < 300;
```

---

## 📈 Business Insights Generated

- ⭐ Highest-rated restaurants
- 💰 Budget-friendly restaurants
- 🍜 Cuisine-wise filtering
- 🏙 City-wise restaurant analysis
- 📊 Rating distribution
- 📉 Restaurant ranking

---

## 🚀 How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Ashishnauhwar01/swiggy.git
```

### 2️⃣ Open MySQL Workbench

Create a database

```sql
CREATE DATABASE swiggy;
USE swiggy;
```

### 3️⃣ Import CSV Dataset

Import

```
database swiggi.csv
```

into your SQL table.

### 4️⃣ Run

```
swiggy.sql
```

to execute all SQL queries.

---

## 📸 Project Preview

```
Dataset
   │
   ▼
Import into MySQL
   │
   ▼
Run SQL Queries
   │
   ▼
Generate Insights
```

---

## 🎓 Learning Outcomes

By completing this project, you'll learn:

- Writing SQL queries
- Data filtering
- Data sorting
- Aggregate functions
- Business analysis using SQL
- Working with real-world datasets

---

## 🌟 Future Improvements

- Add SQL Joins
- Create SQL Views
- Stored Procedures
- Window Functions
- Dashboard using Power BI/Tableau
- Advanced Analytics

---

## 👨‍💻 Author

### **Ashish Nauhwar**

💼 GitHub: https://github.com/Ashishnauhwar01

---

## ⭐ Support

If you found this project helpful,

🌟 **Please Star this Repository**

It motivates me to build more data analytics projects.

---

<p align="center">

### Made with ❤️ and SQL. Swiggy open dataset . INDIA



</p>
