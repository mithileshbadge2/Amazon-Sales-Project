Amazon Sales Report Analysis
This Jupyter Notebook contains a comprehensive analysis of an Amazon sales dataset. The notebook performs various operations on the data to explore and extract meaningful insights. Below is a summary of the steps and analysis performed:

1. Loading the Dataset
The dataset is loaded from a CSV file named Amazon_Sale_Report.csv.
The dataset contains 128,975 entries with 24 columns, including information such as Order ID, Date, Status, Fulfillment method, Sales Channel, SKU, Category, Amount, and other details related to the orders.


2. Initial Data Exploration
The first few rows of the dataset are displayed to understand the structure and contents.
A detailed summary of the dataset is provided using the df.info() method, which shows the data types, non-null counts, and memory usage.


3. Key Columns in the Dataset
Order ID: Unique identifier for each order.
Date: Date of the order.
Status: Order status (e.g., Cancelled, Shipped, Delivered).
Fulfillment: Method of fulfillment (e.g., Merchant, Amazon).
Sales Channel: Platform through which the sale was made (e.g., Amazon.in).
Amount: The total amount of the sale in the specified currency.
Ship-City, Ship-State, Ship-Country: Shipping details including city, state, and country.


4. Data Cleaning and Preprocessing
The notebook handles missing values, incorrect data types, and other data cleaning tasks to ensure the dataset is ready for analysis.


5. Data Analysis and Visualization
The notebook includes sections for data visualization, which help in understanding the distribution of sales, trends over time, and other key metrics.
Specific analysis such as sales by category, fulfillment methods, and geographical distribution of sales might be covered.


6. Insights and Conclusions
The notebook concludes with key insights derived from the data analysis, such as the most popular product categories, the performance of different fulfillment methods, and sales trends over time.
