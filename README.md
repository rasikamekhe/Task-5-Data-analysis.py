In this task, I performed data analysis on a sales dataset using Python, Pandas, and Matplotlib in Jupyter Notebook.
The main goal was to load a CSV file, analyze total sales for each product, and visualize the results using a bar chart.

Steps I Performed:
Set up the environment – Opened and executed the code in Jupyter Notebook.

Imported necessary libraries – Used pandas for reading and analyzing the data, and matplotlib.pyplot for visualization.

Loaded the CSV file – Read the sales_data.csv file using pd.read_csv() to bring the sales data into a DataFrame.

Verified the dataset – Displayed the first few rows with df.head() to check if the data was loaded correctly.

Analyzed the data – Used groupby('Product')['Sales'].sum() to calculate total sales for each product.

Displayed the analysis – Printed the grouped sales data to view each product’s total sales value.

Created a bar chart – Plotted the total sales by product using plot(kind='bar') with customized labels, title, and color.

Visualized the results – Displayed a clear bar graph representing which products generated higher sales.
