# Baltimore City Circut Court Gross Pay in 2020
**Background**  
This project tries to predict the gross pay of employees from Baltimore City Circuit Court in 2020 given the information of years worked, historical annual salary and gross pay. It is going to predict by years worked only and then predict based on historical annual salary. Linear regression statistics will also be given to consider the validity of the predictions.   
- Years worked: The original csv file was uploaded with the report of gross pay and annual pay in fiscal year 2011, 2012, 2013. I use all three years to form my linear regressoin.  

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
<img width="310" alt="Screen Shot 2020-10-01 at 16 18 03" src="https://user-images.githubusercontent.com/70663111/94858884-b3072380-0401-11eb-8dfb-47e722893873.png">  
- Prediction based on a multiple linear regression analysis indicates a goodness of fit of %78.22. The function used to predict is y = 0.92 * x1 + 406.22 * x2 - 6276.6835, where y is the Gross Pay, x1 is the amount of annual salary and  x2 is the number of years worked by the employees.  
<img width="626" alt="Screen Shot 2020-10-01 at 16 18 19" src="https://user-images.githubusercontent.com/70663111/94858918-bc908b80-0401-11eb-94ab-5b795624bcb4.png">  
- The multiple linear regression is a more reliable prediction. Its higher R indicates a stronger positive linear relationship, and its goodness fit has reached 78.22%, which is around 2.5 times better than a single linear regression. The standard error of the multiple is also smaller. 
<img width="573" alt="Screen Shot 2020-10-01 at 16 18 38" src="https://user-images.githubusercontent.com/70663111/94858947-c87c4d80-0401-11eb-8d86-39e907abc8c2.png">   
Statistically speaking, both linear regression models are statistically significant because both Significance F are smaller than 0.05. 
<img width="632" alt="Screen Shot 2020-10-01 at 17 06 43" src="https://user-images.githubusercontent.com/70663111/94863484-86a2d580-0408-11eb-9b41-73515e0a7cbc.png">




**Recap**     
Both linear regression models seem to work well considering the significance F. The prediction of the employee’s gross pay in 2020 are in the attached excel files for each employee. Additional steps that might be helpful to have better predictions are: 1. Filter the data according to different job titles. 2. Use non-linear regression models if the only dependent variable is the number of years worked. 3. Group different employees according to bonus or commissions etc.  



**Manipulation in Excel**
1. Simple linear regression: create a scatter plot then fit a line. Use trendline -> linear.  
2. Calculate the error that this gives for each dependent datapoint.  
3. Calculate standard error of the simple linear regression.  
4. Use Data Analysis -> regression to do linear regressions on simple linear regression (again) for regression statistics.  
5. Use Data Analysis -> regression to do multiple linear regression adding an independent variable of annual salary.  
