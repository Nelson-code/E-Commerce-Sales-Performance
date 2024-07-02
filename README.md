# E-Commerce-Sales-Performance

![image](https://github.com/Nelson-code/E-Commerce-Sales-Performance/assets/62516702/03efe7f8-5d48-414a-ba2a-e039414a706b)


Tech Stack: Python, PowerBI, DAX

Project Phases

1. Pre-Work Summary:

Collaborated with Ezekiel Aleke on this project. Using e-commerce dataset organized into fact and dimension tables, including 60,000+ customer transactions and 26 features. Fact tables contain customer transactions, while dimension tables hold related descriptions.


2. Data cleaning:
   
- Developed a k-medoids clustering model to fill missing categorical values in the color variable of the product dimension table.

 - Preprocessing for k-medoids included:

  - PCA to reduce dimensions, using scree plot to identify columns capturing 95% variance

  - Q-Q plots to check normal distribution of data

- Extracted size values from product descriptions using exception handling to fill missing product size attributes.


3. Explored data through queries, including:

- Impact of festival sales on overall sales

- Product color preference analysis

- Impact of tax amount on product purchases

- Revenue analysis of major product categories and subcategory contribution (e.g., revenue from 'XL' size apparel)

- Relationship between customer buying behavior and yearly income

- Predominant customer age group

- Customer spending as a portion of income

- Comparison of weekend vs. weekday sales


4. Solution Development:

- Solved queries using Python libraries like numpy, pandas, matplotlib, and sci-kit learn.

- Exported DataFrames to CSV for PowerBI visualization.


Visualization Agenda:

""Focused on user-friendly visuals, avoiding overuse or underuse of colors and information""

Process:

- Imported dataset to PowerBI and performed basic transformations using PowerQuery Editor.

- Modeled data with a star schema, linking fact and dimension tables.

- Used DAX language for creating measures, calculated columns, tables

- Organized measures in folders and subfolders.

- Formatted charts and added slicers for enhanced visual experience, including multi-layered donut charts without custom visuals.

- Identified key KPIs by considering product value, business understanding, and user goals.

- Developed a navigation page with icons from flaticons.com.


5. Knowledge Presentation (Takeaways from analysis)

1. Festival sales significantly contributed, especially from 2005-2007.

2. Luxury products (price >= $1200) sold the most throughout the years.

3. Products with lower tax amounts are favored; ~45k (75%) orders have tax < $38.

4. Middle-class customers spend 20-25% of their yearly income on our platform.

5. Organization sells both apparel and hardware products.

6. Predominant customers are aged 30-39, followed by 40-49.

7. Highest revenue year: 2007, followed by 2008 due to:

  - 8,000 new customers in 2007 (3x 2006)

  - Peak festival sales in 2007.

8. Hardware sales account for 98% of total revenue, apparel 2%.

9. Black-colored products are the most sold.

10. US ranks No.1 in sales territory by highest sales and customer count.
