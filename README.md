Used Python Pandas, Matplotlib and Seaborn to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I started by cleaning the data. Tasks during this include:

1. Drop null values from DataFrame.
2. Removing rows based on a condition.
3. Change the type of columns (to_numeric, to_datetime, astype)

Once I cleaned up the data, I moved to the visualization part.

1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4. What product sold the most?


To answer these questions I used many different pandas & matplotlib methods that includes:

1. Concatenating multiple csvs together to create a new DataFrame (pd.concat)
2. Adding columns.
3. Parsing cells as strings to make new columns (.str)
4. Using the .apply() method.
5. Using groupby to perform aggregate analysis.
6. Plotting bar charts and lines graphs to visualize our results.
7. Labeling our graphs.
