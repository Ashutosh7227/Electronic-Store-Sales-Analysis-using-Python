# Data_Analysis_Using_Python
Performing data cleaning, analysis, visualization of store sales data using python.

Task 1: Cleaning the data.
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Task 2: Data exploration and processing. Followed by 5 business level questions that is to be answered by the data:
- What was the best month for sales? How much was earned that month?
- Which city sold the most product?
- What time advertisements should be displayed to maximize the likelihood of customer’s buying a product?
- What products are most often sold together?
- What product sold the most? Why was the reason it was sold the most?

To answer these questions I've used many different pandas & matplotlib methods:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
