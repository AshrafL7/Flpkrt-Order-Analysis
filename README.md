# 🛒 E-commerce Order Data Analysis Dashboard (Excel)

This project is an interactive **Excel Dashboard** built to analyze a synthetic e-commerce dataset inspired by platforms like **Flipkart**. The aim is to derive actionable insights from order data, such as customer preferences, city-wise performance, product category trends, and delivery effectiveness. The dashboard is fully interactive using **PivotTables**, **PivotCharts**, and **Slicers**, with a professional visual design.

---

## 📌 Project Objective

To design an intuitive and insightful **Excel-based dashboard** that allows users to explore large-scale e-commerce order data and identify key performance indicators (KPIs) such as:

- Top ordering cities
- Most valuable and popular product categories
- Agent-wise performance metrics
- Delivery status analysis
- Payment method preferences
- Customer satisfaction trends

The dashboard provides real-time filtering capabilities, making it easy for stakeholders to analyze the data based on cities, categories, and more.

---

## 🧾 Dataset Overview

The dataset is contained in `Flipkart_Order_Dataset.xlsx` and includes the following fields:

| Column Name         | Description                                  |
|---------------------|----------------------------------------------|
| Order ID            | Unique identifier for each order             |
| City                | City where the order was placed              |
| Category            | Product category (e.g., Fashion, Grocery)    |
| Order Agent         | Agent who handled the delivery               |
| Order Status        | Current status (Delivered, In Transit, etc.) |
| Payment Method      | Mode of payment used                         |
| Order Value         | Total value of the order                     |
| Customer Rating     | Satisfaction rating (out of 5)               |

> ✅ The dataset supports multiple pivoting dimensions, making it perfect for dashboarding in Excel.

---

## 📊 Dashboard Features

Here’s a breakdown of the key visualizations and insights included in the dashboard:

### 🏙️ 1. **Top Orders by City**
- A vertical bar chart showing cities with the highest number of orders.
- Helps identify high-demand zones and business hotspots.

### 👤 2. **Top 10 Order Agents**
- Shows the most active agents based on the number of deliveries.
- Supports performance evaluation and workforce planning.

### 🚚 3. **Transit Status Analysis**
- A stacked column chart representing the distribution of order statuses.
- Categories: Delivered, In Transit, Cancelled, Returned.

### 😊 4. **Happy Customer’s Category**
- A line graph highlighting categories with the best average customer ratings.
- Helps understand customer satisfaction across segments.

### 💰 5. **Most Valuable Category**
- A column chart showing the revenue generated per category.
- Useful for inventory and marketing focus.

### 💳 6. **Preferred Payment Methods**
- A pie chart showing the breakdown of payment method preferences.
- Options include UPI, COD, Wallets, Debit/Credit Cards.

### 🔁 7. **Popular Categories (Donut Chart)**
- Visualizes which categories have the highest order count.

### 🎛️ Filters (Slicers)
- **Category & City slicers** allow dynamic filtering across all visuals.

---

## 🖼️ Screenshot Preview

![Dashboard Screenshot]
![Screenshot 2025-04-21 223318](https://github.com/user-attachments/assets/4916b4e8-f252-4006-9e70-436de4a1216c)

---

## 🛠 Tools & Technologies Used

| Tool        | Purpose                                           |
|-------------|---------------------------------------------------|
| Microsoft Excel | Data transformation, analysis, and visualization |
| PivotTables   | Summarizing and aggregating data efficiently     |
| PivotCharts   | Creating interactive charts                      |
| Slicers       | Adding interactivity to dashboards               |
| Excel Formulas | Custom calculations (e.g., totals, averages)   |

---

## 🔍 Key Business Insights

- **Bangalore** leads in number of orders, followed by **Pune** and **Chennai**.
- **Fashion** is both the most popular and most valuable product category.
- **UPI** is the most preferred payment method, closely followed by Credit/Debit Cards.
- Agent `Agent_7` and `Agent_3` are top performers.
- Highest customer satisfaction is observed in **Fashion** and **Books** categories.

---

## 📁 Project Structure

Flpkrt-Order-Analysis/ 
  |── Flipkart_Order_Dataset.xlsx # Excel file with raw data and dashboard 
  ├── Screenshot.png # Image preview of the dashboard 
  |── README.md # This project documentation file

---

## 📌 How to Use

1. Clone or download this repository:
git clone https://github.com/your-username/Flpkrt-Order-Analysis.git


2. Open `Flipkart_Order_Dataset.xlsx` in Microsoft Excel (Office 365 recommended).

3. Use the slicers to interact with the dashboard and explore:
- City-specific performance
- Category-wise trends
- Delivery efficiency
- Agent analysis

---

## 📝 Resume Project Description

**E-commerce Order Data Analysis (Excel Dashboard)**  
Developed an interactive dashboard using Excel to analyze e-commerce order data by city, category, and agent. Leveraged PivotTables, slicers, and advanced charts to identify key business insights such as top-selling categories, customer satisfaction, payment trends, and delivery status distribution.

---

## 🚀 Future Enhancements

- Connect Excel to a live Power Query or SQL data source.
- Implement Power BI & Tableau versions of the same dashboard.
- Add KPI indicators with traffic light visuals and trend arrows.

---

## 📬 Contact

Have questions or feedback? Feel free to connect:

- 📧 Email: ashraf151002@gmail.com
- 💼 LinkedIn: [linkedin.com/in/your-profile](https://linkedin.com/in/ashraf-sm)

---

## 🏷️ Tags

`#ExcelDashboard` `#DataAnalysis` `#Ecommerce` `#Visualization` `#Flipkart` `#PivotTables` `#Slicers` `#OrderData`




