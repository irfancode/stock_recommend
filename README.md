Case Study
Abstract:
This case study aims to demonstrate how a combination of SQL, Python, and Tableau can be utilized to optimize the selection of stocks from a dataset. The dataset consists of over 4500+ stocks, and the task is to identify and recommend 5 stocks and the focus is on selecting stocks from a specific subsector within the dataset. The study showcases how these three tools can be integrated to effectively explore, analyse, and present stock market data.

Introduction:
The stock market dataset used in this case study contains historical stock close prices, Market Capital, PE Ratio and other relevant attributes for various Companies. The objective is to gain insights into the performance, trends, and relationships within the dataset and present them visually using Tableau.

Approach:
Step 1: Data Cleaning with SQL
•	Import the stock dataset into a SQL database.
•	Use SQL queries to clean the data by removing duplicates, handling missing values, and ensuring data consistency.
•	Filter out irrelevant data and ensure data integrity and consistency.

Step 2: Extracting Insights with Python:
•	Retrieve the cleaned dataset from the SQL database into CSV Format
•	Ioad the dataset into python
•	Utilize Python's data manipulation libraries, such as Pandas, to perform further data transformation and analysis.
•	Calculate stock returns, identify trends, and perform statistical calculations using libraries like NumPy, Matplotlib, or Seaborn.
•	Extract key insights, such as PE ratio, Profit after Tax, Profit Margin etc. to gain a deeper understanding of the stock market data.

Step 3: Visualization with Tableau:
•	Export the cleaned and analysed dataset from Python to a compatible format, such as CSV or Excel.
•	Open Tableau and connect it to the exported dataset.
•	Leverage Tableau's intuitive interface to create interactive visualizations, such as line charts, bar graphs, scatter plots, or heatmaps.
•	Utilize filters, parameters, and calculated fields in Tableau to further explore the data and identify meaningful patterns.
•	Develop dashboards and stories in Tableau to present the insights in a structured and visually appealing manner.
•	Customize the visualizations with colors, labels, and tooltips to enhance clarity and user experience.
•	Incorporate interactive features in Tableau to allow users to explore the data on their own.
