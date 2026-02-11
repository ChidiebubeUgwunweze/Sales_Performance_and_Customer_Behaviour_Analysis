# 📊 Sales Performance and Customer Behaviour Analysis

## 📌 Project Overview

This project analyzes sales data to uncover key business insights that can help drive informed decision-making. Through exploratory data analysis (EDA) and visualization, we examine trends in sales performance, customer segments, product performance, and regional distribution.

The goal is to identify patterns, peak sales periods, top-performing products, and high-value customer segments to support strategic business planning.

---

## 🎯 Objectives

- Analyze monthly sales trends
- Identify top-performing products
- Examine sales distribution by region
- Determine the most valuable customer segments
- Generate actionable business recommendations

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Enhanced visualizations
- **Jupyter Notebook**

---

## 📂 Dataset

The dataset used in this project:

`sales_data.csv`

It contains transactional sales data including:

- Order dates  
- Product information  
- Sales values  
- Customer segments  
- Regional data  

---

## 🔎 Project Workflow

### 1️⃣ Data Preparation

- Imported necessary libraries  
- Loaded CSV data into a Pandas DataFrame  
- Created a backup copy of the dataset  
- Checked for missing values  
- Converted date columns to standard datetime format  

---

### 2️⃣ Exploratory Data Analysis (EDA)

#### 📈 Total Sales by Month

- Sales peak in **September, November, and December**
- **November** is the highest-performing month
- **January and February** show the lowest sales

#### 🏆 Top 10 Products

- The **Canon imageCLASS 2200 Advanced Copier** generates the highest sales
- It surpasses the second-highest product by over **34,000** in sales
- It contributes roughly **2% of total sales**, indicating diversified revenue streams

#### 🌍 Sales by Region

- The **West and East regions** account for **61% of total sales**
- Sales are geographically concentrated in these regions

#### 👥 Customer Segments

- **Consumers contribute 51%** of total sales
- **Corporate segment contributes 30%**
- Consumer segment is the primary revenue driver

---

## 💡 Key Business Insights

- Sales demonstrate **seasonal patterns**, peaking towards year-end.
- There is a **post-holiday slowdown** in January.
- Revenue is heavily driven by the **Consumer segment**.
- Regional sales are concentrated in **West and East regions**.
- Certain high-value products significantly outperform others.

---

## 🚀 Business Recommendations

- Focus marketing and inventory efforts during peak months (September–December).
- Introduce promotions in January to boost low-season sales.
- Implement loyalty programs for the Consumer segment.
- Expand B2B promotions to grow the Corporate segment.
- Ensure consistent stock and marketing support for top-performing products.
- Strategically allocate resources to high-performing regions while developing underperforming ones.

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone <your-repository-link>
   ```

2. Install required libraries:

    ```bash
    pip install pandas matplotlib seaborn
    ```

3. Ensure ```sales_data.csv``` is in the project directory.

4. Open the Jupyter Notebook:

    ```bash
        jupyter notebook
    ```

5. Run all cells to reproduce the analysis and visualizations.

---

## 📊 Visualizations Included

- Monthly Sales Line Chart
- Top 10 Products Bar Chart
- Customer Segment Pie Chart
- Regional Sales Analysis

## 📁 Project Structure

<pre>
├── Sales Analysis and Formatting.ipynb
├── sales_data.csv
└── README.md
</pre>


## ✍️ Author

**Eze Ugwunweze**