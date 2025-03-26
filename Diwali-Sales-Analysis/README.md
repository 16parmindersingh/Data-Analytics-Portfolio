# Diwali Sales Data Analysis 🎇📈

## Project Overview
This project analyzes sales data from Diwali, a major Indian festival, to identify the most popular products based on order volume. Using **Python**, I performed data cleaning, preprocessing, and visualization to uncover insights from the dataset. The goal was to understand which products had the highest demand during the festive season, providing a foundation for further business analysis.

This project showcases my skills in **data cleaning**, **data manipulation**, and **data visualization** using Python libraries like Pandas and Matplotlib. It’s a great example of how I can work with real-world datasets to extract meaningful insights.

---

## Dataset Description
The dataset, `Diwali Sales Data.csv`, contains sales records from the Diwali season. It includes 11251 transactions with the following columns:

- **User_ID**: Unique identifier for each customer.
- **Cust_name**: Name of the customer.
- **Product_ID**: Unique identifier for each product.
- **Gender**: Customer gender (F/M).
- **Age Group**: Age group of the customer (e.g., 26-35, 0-17, 55+).
- **Age**: Exact age of the customer.
- **Marital_Status**: 0 (unmarried) or 1 (married).
- **State**: Customer's state in India (e.g., Maharashtra, Andhra Pradesh).
- **Zone**: Region in India (e.g., Western, Southern, Central).
- **Occupation**: Customer's occupation (e.g., Healthcare, Govt, IT Sector).
- **Product_Category**: Category of the product (e.g., Auto, Food, Clothing).
- **Orders**: Number of orders placed for the product.
- **Amount**: Total amount spent on the purchase.

### Data Insights
- The dataset initially had 11251 rows and 15 columns.
- Two columns, `Status` and `unnamed1`, were empty and removed during cleaning.
- The `Amount` column had 12 missing values, which were dropped, leaving 11239 rows for analysis.
- The data includes diverse customer demographics and geographic information, making it suitable for broader analysis in the future.

---

## Tools and Technologies
- **Python**: Core programming language for the analysis.
- **Pandas**: Used for data loading, cleaning, and manipulation.
- **Matplotlib**: Used for creating visualizations (bar chart).
- **Jupyter Notebook**: Environment for writing and running the code (`Diwali Sales Analysis.ipynb`).

---

## What I Did in This Project
This project follows a structured approach to data analysis, focusing on cleaning and visualizing the data. Here’s a detailed breakdown of the steps:

### 1. Data Loading
- Loaded the `Diwali Sales Data.csv` file into a Pandas DataFrame using `pd.read_csv()` with `unicode_escape` encoding to handle special characters.
- Checked the dataset's structure using `df.shape` (11251 rows, 15 columns) and `df.head(10)` to preview the first 10 rows.

### 2. Data Exploration
- Used `df.info()` to understand the data types and identify missing values.
- Found that the `Amount` column was a float, while `Status` and `unnamed1` were completely empty.

### 3. Data Cleaning
- **Dropped Unnecessary Columns**: Removed the `Status` and `unnamed1` columns using `df.drop()` since they had no data.
- **Handled Missing Values**: Identified 12 missing values in the `Amount` column using `pd.isnull(df).sum()`. Dropped these rows with `df.dropna()`, reducing the dataset to 11239 rows.
- **Data Type Conversion**: Converted the `Amount` column from float to integer using `df['Amount'].astype('int')` for consistency in analysis.

### 4. Data Visualization
- Created a bar chart to visualize the top 10 products by total orders.
- Used `df.groupby('Product_ID')['Orders'].sum().nlargest(10)` to calculate the total orders for each product and select the top 10.
- Plotted the results using Matplotlib with `plot(kind='bar')`, setting the figure size to 12x7 for better readability.

### Key Output
The bar chart highlights the 10 products with the highest number of orders, providing a clear view of which products were most popular during Diwali sales.

---

## Results and Insights
- **Top Products**: The bar chart shows the top 10 products by order volume, helping identify which products were in high demand during Diwali.
- **Data Quality**: After cleaning, the dataset is more reliable for analysis, with no missing values and consistent data types.
- **Potential for Further Analysis**: The dataset includes customer demographics (age, gender, occupation) and geographic data (state, zone), which could be explored further to understand purchasing patterns across different groups.

---

## Project Structure
- `Diwali Sales Data.csv`: The raw dataset used for analysis.
- `Diwali Sales Analysis.ipynb`: The Jupyter Notebook containing the Python code, data cleaning, and visualization.

---

## Skills Demonstrated
This project highlights my ability to:
- Work with real-world datasets and handle common data issues like missing values.
- Use Python libraries (Pandas, Matplotlib) for data analysis and visualization.
- Present findings in a clear and visual format using bar charts.
- Write clean, documented code in a Jupyter Notebook for reproducibility.

---

## Why This Project Matters
For recruiters, this project demonstrates my foundational skills in data analysis using Python, which are valuable for roles in data analytics, business intelligence, or data science. For others, it provides a clear example of how to perform basic data cleaning and visualization on a sales dataset, with potential applications in retail, e-commerce, or marketing analysis.

---

## Contact Me
- **LinkedIn:** [16parmindersingh](www.linkedin/in/16parmindersingh)
- **GitHub**: [16parmindersingh](https://github.com/16parmindersingh)
- **Email**: sparminder1608@gmail.com
## Feel free to reach out for collaboration or questions!

---

Thank you for checking out my project! I’m excited to continue growing my data analytics skills and applying them to real-world problems.
