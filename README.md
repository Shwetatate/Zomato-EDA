📊 Zomato Dataset – Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on the Zomato dataset to understand restaurant trends, ratings, location-based behavior, and online delivery patterns.

The analysis includes:
Data cleaning
Handling missing values
Visualizations (bar plots, pie charts, count plots, heatmaps, etc.)

🗂️ Dataset Description
The Zomato dataset contains information about restaurants across several countries, including:
'Restaurant ID', 'Restaurant Name', 'Country Code', 'City', 'Address',
       'Locality', 'Locality Verbose', 'Longitude', 'Latitude', 'Cuisines',
       'Average Cost for two', 'Currency', 'Has Table booking',
       'Has Online delivery', 'Is delivering now', 'Switch to order menu',
       'Price range', 'Aggregate rating', 'Rating color', 'Rating text',
       'Votes', 'Country'

⚙️ Steps Performed in the EDA
1. Importing libraries
pandas
numpy
matplotlib
seaborn

2. Loading the dataset
df = pd.read_csv("zomato.csv", encoding="latin1")

3. Data cleaning
Removing duplicates
Dropping unwanted columns
Handling missing values
Renaming columns

4. Data transformation
Mapping country codes to country names
Converting data types
Label grouping

5. Visualization & Insights
Using various plots to understand:
Most active countries
Rating distribution
Online delivery availability
Cost distribution
Top cuisines

📌 Key Insights & Observations
🌍 1. Country-wise Transactions

India accounts for 94.39% of all transactions, making it the most active region in the dataset.

USA and UK follow after India.

⭐ 2. Rating Categories (Based on Visualization)
Rating Range	Category
4.5 – 4.9	⭐ Excellent
4.0 – 4.4	⭐ Very Good
3.5 – 4.0	⭐ Good
2.5 – 3.4	⭐ Average
1.8 – 2.4	⭐ Poor

These categories help group restaurants for easier comparison and segmentation.

🍔 3. Online Delivery Availability
Online delivery is available only in India and UAE.
Other countries in the dataset do not offer online delivery through Zomato (as per given data).

🧠 Skills Demonstrated
Data Wrangling
Visualization (Matplotlib & Seaborn)
Insight Extraction
Categorization & Label Encoding
Business Understanding through Data

📁 Files Included
Zomato.ipynb – Notebook containing full analysis
zomato.csv – Dataset
Country-Code.xlse - Dataset
README.md – Project documentation

🚀 Conclusion

This EDA helps understand global food trends, customer ratings, and country-specific behaviors on Zomato. The insights extracted can be used for:
Customer engagement strategies
Market expansion planning
Improving restaurant services
Enhancing rating systems
