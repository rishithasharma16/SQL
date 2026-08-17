# SQL
# 🎬 BingePlay – Advanced SQL Analytics

![SQL](https://img.shields.io/badge/SQL-Advanced-blue)
![MySQL](https://img.shields.io/badge/MySQL-Workbench-orange)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Business%20Insights-purple)
![Internship](https://img.shields.io/badge/Unlox%20Academy-Minor%20Project-green)

## 📌 Project Overview

**BingePlay – Advanced SQL Analytics** is a SQL-based analytics project completed as part of my **Unlox Academy Minor Project – Week 4**.

The project uses a streaming-platform dataset to answer **12 real-world business questions** related to user behaviour, subscriptions, content performance, engagement, retention, and churn signals.

The analysis was performed using **MySQL Workbench** and focuses on applying advanced SQL concepts to convert raw database information into meaningful business insights.

## 🎯 Objectives

* Analyze active subscriptions and monthly revenue.
* Study user signup trends.
* Compare viewing behaviour across devices.
* Analyze ratings and content performance.
* Identify binge-watching behaviour.
* Find users who signed up but never watched content.
* Identify potential over-paying Premium/Family users.
* Analyze subscription upgrade success.
* Detect users returning after incomplete viewing sessions.
* Measure consecutive-week engagement.
* Identify users showing potential churn signals.

## 🗂️ Database Structure

The project works with the following main tables:

* `users`
* `subscriptions`
* `shows`
* `watch_sessions`
* `ratings`

## 📊 Business Questions Covered

### Q1 – Active Revenue

Identifies active subscriptions and calculates total monthly revenue.

### Q2 – Signup Momentum

Analyzes monthly user signups during January–June 2024 and identifies the month with the highest signup count.

### Q3 – Device Analytics

Compares total sessions, watch time, average watch time, and completion rate by device type.

### Q4 – Rating Distribution

Analyzes the distribution of ratings and calculates the percentage of users giving 4 or 5 stars.

### Q5 – Originals vs Acquired Content

Compares BingePlay Originals with acquired content based on the number of shows, average IMDb rating, and average release year.

### Q6 – Binge Day Detection

Identifies user/show/date combinations with at least five watch sessions in a day during April–June 2024.

### Q7 – Q1 Signups Who Never Watched

Identifies users who signed up during Q1 2024 but had no watch sessions.

### Q8 – Over-Paying Premium/Family Users

Identifies active Premium/Family users who have not watched content requiring Premium or Family plans.

### Q9 – Upgrade Success Cohort

Analyzes users who started with a Basic subscription and later upgraded to Premium or Family.

### Q10 – Cliffhanger Comebacks

Identifies users who returned to the same show within seven days after an incomplete viewing session.

### Q11 – Consecutive-Week Engagement

Measures weekly engagement streaks and identifies users with four or more consecutive active weeks.

### Q12 – Churn Signal Detection

Identifies users whose June watch time dropped to 50% or less of their May watch time.

## 🛠️ SQL Concepts Used

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `HAVING`
* `JOIN`
* `LEFT JOIN`
* `CASE WHEN`
* Aggregate Functions
* Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* `ROW_NUMBER()`
* `COUNT()`
* `SUM()`
* `AVG()`
* `ROUND()`
* `DATEDIFF()`
* `DATE_ADD()`
* `MONTH()`
* `MONTHNAME()`
* `YEAR()`
* `YEARWEEK()`
* `EXISTS / NOT EXISTS`

## 🔍 Key Areas of Analysis

### 💰 Revenue & Subscriptions

Analysis of active subscription plans and monthly revenue.

### 👥 User Behaviour

Analysis of signups, viewing activity, binge behaviour, and engagement streaks.

### 🎬 Content Analytics

Comparison of original and acquired shows, ratings, and viewing behaviour.

### 📱 Device Analytics

Evaluation of watch sessions and completion rates across device types.

### 📈 Retention & Engagement

Identification of upgrade behaviour, comeback users, and consecutive engagement.

### ⚠️ Churn Signals

Detection of users experiencing a significant decline in monthly watch time.

## 💻 Tools Used

| Tool                | Purpose                                     |
| ------------------- | ------------------------------------------- |
| **MySQL**           | Database querying and analysis              |
| **MySQL Workbench** | SQL development and execution               |
| **SQL**             | Data analysis and business-question solving |

## 📁 Project Structure

```text
BingePlay-Advanced-SQL/
│
├── README.md
├── bingeplay_setup.sql
└── BingePlay_SQL_Queries.sql
```

## 🚀 How to Run

1. Install **MySQL** and open **MySQL Workbench**.
2. Create or import the BingePlay database.
3. Run the database setup SQL script.
4. Select the BingePlay database:

```sql
USE bingeplay;
```

5. Execute the analysis queries.
6. Review the returned results for each of the 12 business questions.

## 📚 What I Learned

Through this project, I strengthened my practical understanding of:

* Writing advanced SQL queries.
* Translating business questions into SQL problems.
* Working with multiple relational tables.
* Using CTEs and window functions.
* Performing behavioural and cohort analysis.
* Working with dates and time-based data.
* Identifying engagement and churn signals.
* Thinking about SQL from a business-analysis perspective.

## 👨‍🏫 Mentor

A special thanks to my mentor **Girish Kumar** at **Unlox Academy** for his guidance and support throughout this project.

## 🏢 Internship

**Unlox Academy – Minor Project | Week 4**

## 👩‍💻 Author

**Rishitha Poornima**

---

⭐ If you find this project useful, feel free to explore the repository and connect with me on LinkedIn.

