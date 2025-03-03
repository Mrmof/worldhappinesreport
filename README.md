# worldhappinesreport
Analysis of world happiness

This study analyse world happiness for a period of 5yrs, the study was conducted to assertain the influence of socio-economic variables on world happiness and vice versa 
the study was conducted using visual analysis with powerbi standing as the analytical tool. the study used power query, power view and power pivot together
with dax(data analysis expression)
  
Data source
The data was sourced from kaggle.com. the consists of 11 columns and 180 rows

Data cleaning/transformation
The csv data across 5yrs 2020-2024 was loaded into powerbi and transfomed using power query. A custom column was added to each table using the formula Data.FromText("1/1/2020"). The appropriate data type was selected as date and loaded into powebi.
DAX was used to combine all tables into a single table using the function Union("2020","2021","2022","2023","2024").



Rearch questions
What role does social support play in determining happiness across different continents 
How does happiness score vary between developed countries and developing countries?
Is there a relationship between GDP per capital and happiness score across different regions
How has the global happiness score changed over the years 
  


