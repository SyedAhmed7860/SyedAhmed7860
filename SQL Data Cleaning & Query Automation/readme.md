# 📊 Corporate Sales Data Analysis

A complete data analytics project using **Python, Pandas, SQLite, and Seaborn**, analyzing corporate sales performance across regions, clients, and product categories.

---

## 🧠 Project Overview

This project explores and visualizes a corporate sales dataset to uncover insights such as:
- Regional sales performance  
- Top-performing clients  
- Category-wise revenue contribution  
- Payment method trends  
- Monthly sales growth  

The project uses **SQLite** for data storage and **Python (Pandas + Seaborn + Matplotlib)** for visualization.

---

## 🗂 Folder Structure

Corporate_Sales_Analysis/
│
├── Corporate_Sales_Project.ipynb # Main project notebook
├── corporate_sales.csv # Dataset
├── corporate_sales.db # SQLite database
├── images/ # Visualization charts (generated)
│ ├── Monthly Sales Trend.png
│ ├── Payment Method Distribution.png
│ ├── Top 10 Clint s by Total Sales.png
│ ├── Total Sales by Product Category.png
│ └── Total Sales by Region.png
└── README.md # Documentation

yaml
Copy code

> 🚨 Note: The image filenames above are exactly as generated and present in the project folder.  
> If you prefer cleaner names (recommended for professionalism), see the “Rename files” tip below.

---

## 📈 Key Insights
- **Top Region:** Identifies which region generated the highest total revenue.  
- **Top Clients:** Highlights the top 10 clients by sales volume.  
- **Product Category Performance:** Shows which product categories dominate the market.  
- **Payment Trends:** Visualizes customer payment preferences.  
- **Monthly Growth:** Displays the company’s sales trend over time.

---

## 🗄️ Database Integration

The dataset was stored in an **SQLite database** using the following code:

```python
import sqlite3
conn = sqlite3.connect("corporate_sales.db")
data.to_sql("sales_data", conn, if_exists="replace", index=False)
conn.close()
This allows smooth data retrieval and scalability for future integration with dashboards.

📊 Visualizations (files in /images)
Chart filename	Description
Monthly Sales Trend.png	Time-series of monthly total sales
Payment Method Distribution.png	Share of payment methods used (pie chart)
Top 10 Clint s by Total Sales.png	Top 10 clients by revenue
Total Sales by Product Category.png	Revenue per product category
Total Sales by Region.png	Regional revenue comparison

⚙️ How to run
Clone or download the repository.

Install requirements (see requirements.txt) or run in Colab.

Open Corporate_Sales_Project.ipynb and run cells sequentially.

Generated charts are saved to the images/ folder.

👤 Author
Syed Ahmed
📧 syedahmed.sa43@gmail.com
🌐 github.com/SyedAhmed7860
💼 linkedin.com/in/syedahmedpro
