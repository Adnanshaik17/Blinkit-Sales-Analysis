# 📊 Blinkit Sales Analysis 

## 📌 1. Project Title
**Blinkit Sales Analysis – Python-Based Business Intelligence Project**

---

## 📝 2. Description
This project explores sales data from Blinkit, a leading Indian quick commerce platform. It aims to deliver actionable business insights by analyzing sales trends across product categories, outlet types, item features, and customer preferences. The project is developed using core Python data analysis libraries like Pandas, Matplotlib, and Seaborn to simulate a real-world business case suitable for portfolio and interview demonstration.

---

## 🔗 3. Data Source & Information
- **Source**: This dataset available on kaggle
- **Key Fields**:
  - `Item_Identifier`, `Item_Type`, `Item_Weight`, `Item_Fat_Content`
  - `Outlet_Identifier`, `Outlet_Size`, `Outlet_Location_Type`, `Outlet_Establishment_Year`
  - `Item_Visibility`, `Item_MRP`, `Sales`, `Rating`

The data provides product-level sales transactions across multiple retail outlets with descriptive item and outlet features.

---

## 🛠️ 4. Tech Stack Used
- **Language**: Python
- **Libraries**:
  - `pandas` – data wrangling
  - `numpy` – statistical operations
  - `matplotlib` & `seaborn` – data visualization
- **Environment**: Jupyter Notebook / Google Colab / VS Code

---

## 🌟 5. Features & Highlights

### A. Business Problem
To identify top-performing products, analyze outlet-level sales, and determine how product characteristics (like fat content, weight, and visibility) influence sales across Blinkit's distribution network.

### B. Goal of the Python Analysis
- Uncover patterns in product demand and store efficiency
- Visualize KPIs using basic Python libraries (no Power BI or SQL used)
- Generate business insights to guide decision-making in inventory, promotion, and regional expansion

### C. KPIs & Chart Requirements
- **KPIs**
  - Total Sales
  - Average Sales per Item
  - Number of Unique Items Sold
  - Average Customer Rating
  - Average Sales per Item Type
  - Average Rating per Product Category
- **Chart Types**
  - Bar Charts: Total Sales by Item Type, Outlet, Fat Content
  - Pie Chart: Sales share by Fat Content
  - Box Plot: Sales distribution across outlets
  - Scatter Plot: Sales vs. Visibility
  - Heatmap: Sales by Outlet Size & Type
  - Grouped Bar Chart: Sales by Outlet Location Type
  - Horizontal Bar Chart: Top 10 Highest-Selling Products

### D. Walkthrough of Key Visuals
- **Top-Selling Product Categories**: Bar chart showing revenue leaders like Fruits & Vegetables, Snack Foods
- **Sales by Fat Content**: Pie chart showing customer preference
- **Sales by Outlet Type**: Grouped bar chart indicating Tier 3 outlets as top performers
- **Heatmap for Outlet Size/Type**: Identifies combinations with highest revenue contribution
- **Visibility vs. Sales**: Scatter plot shows weak positive correlation

### E. Business Impact & Key Insights
- 🌟 Top 3 product types generate over **60%** of total revenue
- 🌍 Tier 3 outlets outperform Tier 1/2, contributing over **₹4.7L** in sales
- 📦 Items with regular fat content slightly outperform low fat in sales
- 🏪 Older outlets (8+ years) have **higher average sales**
- 📈 Visibility has limited impact alone—suggests combined feature importance in product placement

---

## 📁 Project Structure
