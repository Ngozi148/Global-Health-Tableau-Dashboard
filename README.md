### GLOBAL HEALTH AND ECONOMIC IMPACT ANALYSIS

#### 

#### PROJECT OVERVIEW



This project explores the critical factors influencing the global health outcomes. I wanted to investigate whether medical infrastructures(like the number of doctors and hospital beds) or a country's economic status(income and Education) has a greater impact on disease recovery and mortality rates.





##### 1\. Data Cleaning and Transformation(SQL)



I started with a large, raw global health dataset. I used MYSQL to:



Remove duplicates using ROW\_NUMBER AND CTE which came out with no duplicates showing all ones in the row\_num and handle missing values in the mortality and population columns.



I used CASE statements to create a new "Prevalence Level" feature.



I built a query to group countries by their medical resources. I categorized infrastructure as "Strong", "Moderate", or "Weak" based on the Doctors per 1000 metric.



I used GROUP BY and ORDER BY functions to calculate the average and maximum mortality rates for different diseases categories(Parasitic, Chronic, etc.), which helped me to decide which data to highlight in the final charts.



##### 2\. Exploratory Analysis(Excel)



Before moving to Tableau, I used Excel to perform initial calculations:



Trend Analysis: Used Pivot tables to look at Mortality Risks across different Disease Categories.



Demographics: Grouped the data by Gender and Age to see which Populations were most vulnerable.



##### 3\. 	Data Visualization



I built an Interactive Dashboard to present the final insights:



Global Distribution: A map showing the spread of population and mortality.



National Ranking: A bar chart ranking the countries by their average mortality rates.



Comparing Doctor Density and Per Capita Income against health outcomes.





TOOLS USED



Database: MYSQL(Data Cleaning)



Spreadsheet: Microsoft Excel( Initial Analysis and Pivot Tables)



Visualization: Tableau Public( Dashboard).



Data Source



the raw dataset used for this project is the Global Health Statistics dataset. Due to file size limit, the raw CSV is not hosted here.

