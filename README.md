## World Happiness Report
This study analysed world happiness for a period of 5yrs, the study was conducted to assertain the influence of socio-economic variables on world happiness and vice versa 
the study was conducted using visual analysis with powerbi standing as the analytical tool. the study used power query, power view and power pivot together
with dax(data analysis expression)
  
# Data Source
The data was sourced from kaggle.com consisting of 11 columns and 180 rows across all csv files.

# Data Cleaning/transformation
The csv data across 5yrs 2020-2024 was loaded into powerbi and transfomed using power query. A custom column was added to each table using the formula Data.FromText("1/1/2020"). The appropriate data type was selected as date and loaded into powebi.
DAX was used to combine all tables into a single table using the function =Union("2020","2021","2022","2023","2024").


# Rearch questions
1. What role does social support play in determining happiness across different continents? 
2. Is there a relationship between GDP per capital and happiness score across different regions?
3. How has the global happiness score changed over the years?

Findings and Recommendations
# question 1
Social support was observed to influence happines across different countries. Higher Social support correlated with higer happines scores globally.
# question 2
A positive relationship exist between GDP per capital and happiness score. Increase in GDP influences increase in happiness score for both developed and developing nations.
# question 3
Globally, world happiness have experience a slight decline and may be due to factors including a reduction in GDP globally amongst others such as perception of corruption.

Conclusion
World Happiness is influenced by GDP, perception of corruption and social support. These factors were baring on the happiness recorded globally. Over the past few years, awareness of corruption and slight decline of GDP have reduced the world happiness levels. It is hence recommended for countries to implement measures to increase GDP, tackle corruption and encourage social support.


