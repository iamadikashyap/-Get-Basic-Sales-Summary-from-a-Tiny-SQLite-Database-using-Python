# 🧾 Basic Sales Summary using SQLite & Python

## 🎯 Objective
Create a simple Python script that connects to a **SQLite database**, runs **SQL queries** to summarize sales data, and visualizes the results with a **bar chart**.  
This project helps you learn how to combine **SQL**, **Pandas**, and **Matplotlib** to analyze and visualize data.

---

## 🛠 Tools & Libraries
- **Python 3**
- **SQLite3** (built-in — no setup needed)
- **Pandas**
- **Matplotlib**

---

## 📁 Dataset
A small SQLite database: `sales_data.db`  
Contains one table: **sales**

| Column   | Type    | Description              |
|-----------|----------|--------------------------|
| id        | INTEGER  | Auto-increment primary key |
| product   | TEXT     | Product name             |
| quantity  | INTEGER  | Quantity sold            |
| price     | REAL     | Price per unit           |

Sample Data:
| Product     | Quantity | Price |
|--------------|-----------|-------|
| Laptop       | 5         | 800.0 |
| Phone        | 10        | 500.0 |
| Tablet       | 7         | 300.0 |
| Headphones   | 15        | 50.0  |
| Monitor      | 6         | 200.0 |

---

## ⚙️ Steps to Run

### 1️⃣ Clone or download the project
```bash
git clone https://github.com/your-username/basic-sales-summary.git
cd basic-sales-summary
