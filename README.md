# 📊 Amazon Sales Report Analysis

## 🔍 Overview

This project analyzes **Amazon Sales Data** to uncover trends, patterns, and insights that help in **understanding sales performance**. The goal is to perform **Exploratory Data Analysis (EDA)** and derive actionable insights using **Python, Pandas, Matplotlib, and Seaborn**.

## 🎯 Objective

- Perform **data cleaning** and preprocessing for accurate analysis.
- Conduct **Exploratory Data Analysis (EDA)** to identify trends in sales, revenue, and product performance.
- Visualize key metrics such as **sales trends, best-selling categories, revenue distribution, and customer purchasing behavior**.

## 📂 Dataset Overview

The dataset contains Amazon sales transactions with multiple attributes:

### **🛒 Order Details**

- **Order ID:** Unique identifier for each order.
- **Date:** Date of purchase
- **Status:** Current order status (shipped, pending, etc.)
- **Fulfilment:** Type of fulfillment (FBA, FBM)
- **Sales Channel:** Platform where the order was placed

### **🚚 Shipping Information**

- **ship-service-level:** Shipping priority (standard, expedited)
- **ship-city:** Destination city
- **ship-state:** Destination state
- **ship-postal-code:** Postal code of shipping address
- **ship-country:** Country where the order was shipped

### **📦 Product Details**

- **Category:** Product category (electronics, clothing, etc.)
- **Size:** Product size details
- **Qty:** Number of items ordered

### **💰 Financial Information**

- **currency:** Transaction currency (USD, EUR, etc.)
- **Amount:** Total revenue from the order
- **B2B:** Indicates whether the order was a Business-to-Business (B2B) sale

### **📌 Other Columns**

- **Courier Status:** Status of shipping carrier
- **fulfilled-by:** Whether Amazon or the seller fulfilled the order
- **New:** Additional column for classification
- **PendingS:** Indicates pending status

## 🛠️ Technologies Used

- **Programming Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Visualization Tools:** Matplotlib & Seaborn for interactive data visualization

## 📌 Steps Taken

1. **Data Cleaning & Preprocessing**

   - Removed missing or duplicate values
   - Converted data types (e.g., date formatting, numerical conversions)

2. **Exploratory Data Analysis (EDA)**

   - Identified **top-selling products**
   - Analyzed **seasonal sales trends**
   - Visualized **revenue distribution** across categories

3. **Key Findings & Insights**
   - 🔹 **Seasonal Trends:** Sales peak during certain months (e.g., holidays).
   - 🔹 **Top Revenue-Generating Products:** Identified best-selling items.
   - 🔹 **Customer Behavior:** Frequent purchases in certain categories.

## 📈 Key Visualizations

- 📌 **Sales Trends Over Time**
- 📌 **Revenue Distribution by Category**
- 📌 **Best-Selling Products**
- 📌 **Order Quantity vs. Revenue Analysis**

## 🔥 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/rishabhpancholi/amazon-sales-analysis.git
   cd amazon-sales-analysis
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Execute the notebook cells to analyze the sales data.

## 📌 Future Improvements

- Implement **machine learning models** to predict future sales trends.
- Integrate **interactive dashboards** using **Power BI** or **Tableau**.
- Perform **customer segmentation** for better targeting strategies.

## 📢 Contributing

Feel free to **fork this repo** and contribute! Open issues and pull requests are welcome.

---

⭐ If you found this project useful, give it a star! ⭐
