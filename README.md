### [Emerging Markets – short-term risks and long-term opportunities](https://github.com/pmikov/Emerging-Markets---Risks-Opportunities/blob/master/EM%20Risks%20%26%20Opportunities.ipynb)
Identifying short-term risks and long-term opportunities across Emerging Market economies

Completed on 28th of August as a final project for "Data Science" course at Software University (June - August 2020)
- course 2 of 4 of "Artificial Intelligence" specialization

**The project consists of the following chapters:**
1. Introduction
2. Data Selection - selecting group of factors for evaluating: 
  - Macro Stability (risk of economic crisis) 
  - External Vulnerability (risk of Balance of Payments crisis)
  - Institutional Strength, 
  - Long-term Economic Growth
3. Data Acquistion and cleaning -  more than 30 economic & political indicators are acquired from 7 different official data sources by:
  - connecting to official APIs of DBnomics and United Nations
  - connecting to online Excel databases on World Justice Project and IMF websites
  - using BeautifulSoup for web-scrapping websites of The Observatory of Economic Complexity (OEC), Freedom House and CEIC
4. Combining all data into one dataframe - formatting the data and dealing with missing values
5. Data Transformation - performing and comparing three methods of rescaling data:
  - Z-score standardization
  - min-max normalization 
  - quantile transformation into UPD
6. Deriving the Final Scores and Visualizations - methods deployed:
  - bar and scatter plot charts with annotations and conditional formatting using matplotlib & seaborn libraries
  - conditional formatting on DataFrames
  - visualizations by MultiIndex slicing
  - world map using Basemap library
7. Conclusion & Further Research
