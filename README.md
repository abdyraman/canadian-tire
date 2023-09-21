# canadian-tire
File name: hot_sales.ipynb

Data Scraping and Processing:

Utilized web scraping libraries like BeautifulSoup and Splinter to extract product information from the Canadian Tire website.
Parsed product names, prices, old prices, star ratings, and review counts.
Data Cleaning:

Cleaned and structured the scraped data into lists for further processing and analysis.
Removed unwanted characters, converted prices to numeric format, and handled missing values.
Data Transformation:

Created a DataFrame from the scraped and cleaned data using Pandas.
Performed additional data transformations, such as calculating savings and discounts based on price information.
One-page vs. Multi-page Approach:

Presented two approaches: one for scraping data from a single page and another for scraping from multiple pages.
The multiple-page approach involved iterating through 31 pages to gather a comprehensive dataset.
Insights:

The extracted data includes product names, prices, old prices, star ratings, and review counts, providing a foundation for further analysis and insights into the promotions and products offered by Canadian Tire.
Overall, the script effectively demonstrates how to scrape, clean, and structure data from a website, enabling the analysis and visualization of product information for better decision-making.


File name: newprice_prediction_CanadianTire.ypunb
Data Preprocessing:

Loaded a dataset from "cantire_df.csv" and processed it by scaling relevant features using StandardScaler.
Clustering:

Utilized KMeans, AgglomerativeClustering, and Birch clustering algorithms to segment the data.
Principal Component Analysis (PCA):

Conducted PCA to reduce dimensionality and understand feature importance.
Outlier Detection:

Identified and handled outliers using the Interquartile Range (IQR) method.
Linear Regression:

Employed linear regression to predict new prices based on selected features.
Model Evaluation:

Assessed the regression model's performance using summary statistics and a scatter plot comparing predicted vs. actual values.
The script demonstrates a comprehensive analysis pipeline for price prediction, encompassing data preprocessing, clustering, dimensionality reduction, outlier handling, and predictive modeling.





