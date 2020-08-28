Identifying short-term risks and long-term opportunities across Emerging Market economies

Completed on 28th of August as a final project for "Data Science" course at SoftUni 
(course 2 of 4 of "Artificial Intelligence" specialization)

Along with an in-depth economic analysis of factors that drive risk and growth in Emerging Markets, this project utilizes the following DataScience techniques in Python language to quantify the factors and draw useful conclusions across different countries and regions:

- Data Acquisition: more than 30 economic & political indicators are acquired from 7 different official data sources - including DBnomics API, United Nations API, online excel files on World Justice Project and IMF websites, and web-scrapping websites of The Observatory of Economic Complexity (OEC), Freedom House and CEIC using BeautifulSoup.

- Data Tidying and Cleaning: defining own functions based on pandas' pivot_table and "country_converter" library for cleaning the messy raw data and creating a single country key across all dataframes (ISO3 code)

- Data Transformation: performing and comparing three methods of rescaling data - Z-score standardization, min-max normalization and quantile transformation into UPD

- Data Visualization: world map using Basemap library, bar and scatter plot charts with annotations and conditional formatting using matplotlib & seaborn libraries, conditional formatting on DataFrames, visualizations by MultiIndex slicing
