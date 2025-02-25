# E-commerce Sales Data Analysis

## Project Overview

This project focuses on analyzing an E-commerce sales dataset to extract valuable insights that can help improve business performance. By leveraging data analytics techniques, we aim to understand trends, identify profitable categories, and optimize sales strategies. The project involves data preprocessing, exploratory data analysis (EDA), and visualization using various Python libraries.

## Technologies Used

- **Python**: Programming language used for analysis.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Plotly**: For interactive plots.

## Dataset

- The dataset contains **9,994 rows** and **21 columns**.
- It includes details such as **Order Date, Sales, Profit, Category, and Sub-Category**.

## Steps Performed

### 1. Understanding the Business Problem

Before diving into data analysis, we first define business questions that can help optimize sales and profits.

### 2. Data Preprocessing

- Loaded the dataset into a Pandas DataFrame.
- Checked for missing values (None found).
- Dropped unnecessary columns to reduce noise.
- Used the `.describe()` method to get insights into numerical columns.
- Converted data types where necessary.
- Extracted new features from the **Order Date** column:
  - **Month, Year, and Week** were extracted to analyze sales trends over time.

### 3. Exploratory Data Analysis (EDA)

We performed several analyses and visualizations to derive insights:

#### Monthly Sales Analysis

- Used the `groupby` method to aggregate sales per month.
- Found that **November had the highest sales**, while **February had the lowest sales**.
- Visualized using a **line chart**.

#### Category-wise Sales Analysis

- Grouped data by **Category** and **Sales**.
- **Technology** had the highest sales, while **Office Supplies** had the lowest.
- Used **bar charts** for visualization.

#### Sub-category Sales Analysis

- Analyzed sales across different sub-categories.
- **Phones and Chairs had the highest sales**, whereas **Fasteners had the lowest sales**.
- Visualized using a **bar chart**.

#### Monthly Profit Analysis

- Grouped data by **Order Month and Profit**.
- Found that **January had the lowest profit**, while **September and December had the highest profit**.
- Visualized using a **line chart**.

#### Category-wise Profit Analysis

- Grouped data by **Category** and **Profit**.
- **Technology and Office Supplies were the most profitable**, while **Furniture had the lowest profit**.
- Visualized using **bar charts**.

#### Sub-category Profit Analysis

- Grouped data by **Sub-category and Profit**.
- Found that **Tables were in loss**, while **Copiers were the most profitable**.
- Visualized using **bar charts**.

### 4. Sales-to-Profit Ratio Analysis

- Calculated the **sales-to-profit ratio** for different customer segments:
  - **Consumer**: 8.66
  - **Corporate**: 7.68
  - **Home Office**: 7.13
- Helps understand how much sales contribute to profit in different customer segments.

## Key Insights

- **November** has the highest sales, while **February** has the lowest.
- **Technology products** contribute the most to revenue.
- **Phones and Chairs** are the best-selling sub-categories, whereas **Fasteners** have the lowest sales.
- **Tables** generate losses, while **Copiers** yield the highest profits.
- **Consumer segment** has the highest sales-to-profit ratio.

## Conclusion

This analysis provides useful business insights that can help improve marketing strategies, optimize product categories, and enhance profitability. Future work can include predictive modeling to forecast sales trends.

## How to Use This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Ayankhan404/ecommerce-sales-analysis.git
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```
3. Run the Jupyter Notebook or Python script to perform the analysis.

## Author

Ayan Khan

## Connect with Me

[LinkedIn](https://www.linkedin.com/in/ayan-khan-917611250/)
