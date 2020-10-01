# Baltimore City Circut Court Gross Pay in 2020
**Background**  
This project tries to predict the gross pay of employees from Baltimore City Circuit Court in 2020 given the information of years worked, historical annual salary and gross pay. It is going to predict by years worked only and then predict based on historical annual salary. Linear regression statistics will also be given to consider the validity of the predictions. 
**Business Question**  
What will the gross pay of employees from Baltimore City Circuit Court be in 2020?    

**Data Source**  
Baltimore City Employees Salaries:
i. https://data.baltimorecity.gov/browse?category=City+Government captures gross salary of Baltimore City employees from fiscal year 2011 through last fiscal year and includes employees who were employed on June 30 of last fiscal year. 


**Data Analysis**   
We’ll use Microsoft Excel to answer:  
- What is the Gross Pay of Baltimore City Circuit Court in 2020? Make a prediction based on the number of years an employee has worked.  
- What is the Gross Pay of Baltimore City Circuit Court in 2020? Make a prediction based on the number of years an employee has worked and the annual salary of each.   
- How reliable are the two predictions? Interpret their linear regression statistics to compare and contrast the two regressions.  

**Data Answer**  
- Prediction based on a simple linear regression analysis indicates a goodness of fit of %29.13. The function used to predict is y = 1226.7 * x + 35896, where y is the Gross Pay and x is the number of years worked by the employees. 
<img width="1268" alt="Screen Shot 2020-09-17 at 15 06 51" src="https://user-images.githubusercontent.com/70663111/93515992-6bf43b00-f8f7-11ea-8ff5-d176be0fe239.png">. 
- Los Angeles has a higher median and average income than Baltimore City. Understandable because Los Angeles has a higher state minimum salary and GDP in general. Both cities have a median income higher than average income because of outliers. 
<img width="361" alt="image" src="https://user-images.githubusercontent.com/70663111/93515405-8b3e9880-f8f6-11ea-9210-0e66497b4b8a.png">. 
- Los Angeles has larger economic inequality in individual income. Note that Baltimore City has areas where individual income is among the medium range.
<img width="962" alt="Screen Shot 2020-09-17 at 15 11 32" src="https://user-images.githubusercontent.com/70663111/93516472-13716d80-f8f8-11ea-8301-1f74c33ef47f.png">.  
- There are still individuals in Los Angeles that are not mobilized well enough that their individual income is too low for the lowest despite their chances of having a college degree is twice as those from the same socioeconomic class in Baltimore City. In Baltimore City, however, individuals have a higher rate of having higher individual income, and none of Baltimorians individual income is too low.  
<img width="406" alt="image" src="https://user-images.githubusercontent.com/70663111/93516646-56334580-f8f8-11ea-8edf-505625563b37.png">.  

**Recap**     
The initial question was assuming that there is a correlation between college graduation rate and individual income/ poverty rate for those whose parents have low income. Unfortunately, this data analysis failed to prove this seemingly “common-sense” assumption. Some additional data that might be helpful include comparing middle and lower income families in Baltimore and looking at the industries people work in. This is important because 1. college degrees’ effect can be undermined because of one’s original socio-economic class. 2. College degree is not the only way to mobilize. Blue-collar and people in business do not necessarily require college degrees.   

**Manipulation in Excel**
1. Use MEDIAN, AVERAGE, COUNTIF, algorithms to find median, average, low ourliers, high outliers, fraction of outliers for individual income of people in Baltimore City and Los Angeles.  
2. Build Pivot Table of median and average income of the two cities and create histogram to compare them.  
3. Build Pivot Table of individual income of each city and put them together to see outliers, genearl distribution.  
4. Build Pivot Table of fraction of low, high, general outliers of Baltimore City and Los Angeles and create a historam comparing these two.
