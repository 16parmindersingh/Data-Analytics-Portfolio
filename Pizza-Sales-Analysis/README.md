# Pizza Sales Analysis (SQL)

## Overview
This project analyzes 12 months of pizza sales data to optimize menu offerings, pricing strategies, and inventory management. The analysis was performed using MySQL by integrating data from multiple CSV files.

## Project Structure
- **data/**: Contains the raw data files.
  - `orders.csv` – Order-level data.
  - `order_details.csv` – Detailed order information.
  - `pizzas.csv` – Pizza menu details.
  - `pizza_types.csv` – Categories and types of pizzas.
- **sql/**: Contains SQL scripts that answer the project questions.
  - `query1.sql` to `query13.sql` address the following questions:
      1. Retrieve the total number of orders placed.
      2. Calculate the total revenue generated from pizza sales.
      3. Identify the highest-priced pizza.
      4. Identify the most common pizza size ordered.
      5. List the top 5 most ordered pizza types along with their quantities.
      6. Join the necessary tables to find the total quantity of each pizza category ordered.
      7. Determine the distribution of orders by hour of the day.
      8. Join relevant tables to find the category-wise distribution of pizzas.
      9. Group the orders by date and calculate the average number of pizzas ordered per day.
      10. Determine the top 3 most ordered pizza types based on revenue.
      11. Calculate the percentage contribution of each pizza type to total revenue.
      12. Analyze the cumulative revenue generated over time.
      13. Determine the top 3 most ordered pizza types based on revenue for each pizza category.
- **docs/**: Contains supporting documents.
  - `Pizza Sales SQL Project.pdf` – A presentation summarizing the queries and results.
  - `Questions.txt` – The list of questions solved by the queries.
- **README.md**: Provides an overview and instructions for the project.

## Data & Analysis
- **Data Import & Cleaning:**  
  Imported four CSV files into SQL tables and ensured data integrity by handling missing/inconsistent data.
- **SQL Queries:**  
  Developed a series of queries to extract insights such as:
  - Total number of orders and revenue.
  - Highest-priced pizza and most common pizza size.
  - Top-selling pizza types and revenue analysis.
  - Distribution of orders by hour and cumulative revenue trends.
- **Results:**  
  The analysis provided actionable insights on peak sales hours, customer preferences, and revenue contributions by pizza type.

## How to Replicate the Analysis
1. **Data Import:**  
   Import the CSV files from the **data/** folder into your MySQL database.
2. **Execute SQL Scripts:**  
   Run the SQL scripts in the **sql/** folder in numerical order to replicate the analysis.
3. **Review Presentation:**  
   Check the **docs/Pizza Sales SQL Project.pdf** for a detailed explanation of the queries and results.

## Key Insights
- Identified overall revenue generation and top revenue-contributing pizza types.
- Determined peak ordering hours and customer preferences.
- Findings support optimized menu offerings and targeted promotions.

## Contact
For any questions or collaboration opportunities, please reach out to:
- **Email:** [sparminder1608@gmail.com](mailto:sparminder1608@gmail.com)
- **LinkedIn:** [Parminder Singh](https://www.linkedin.com/in/16parmindersingh)
