# MechaCar_Statistical_Analysis

# Background 

A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, you’ll help Jeremy and the data analytics team do the following:

Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
Run t-tests to determine if the manufacturing lots are statistically different from the mean population
Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

# Results

## Linear Regression to Predict MPG

![Deliverable 1](https://user-images.githubusercontent.com/107447648/205458881-727b30b4-d70d-4539-83aa-5d0f57da16d7.png)

1.) Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

 both ground_clearance and vehicle_length provided a non-random amount of variance to the mpg values hey both have significant to the model.
 
 2.) Is the slope of the linear model considered to be zero? Why or why not?
 
 The slope of the linear model can not be considered to be zero, because the p-value is lower than an extreme level of significance, so the null hypothesis must be rejectected.
 
 3.) Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 
 Yes, the linear model predict mpg of MechaCar prototypes is effective because the r-squared is 0.7149 meaning that 71% of the variability observed is explained by the regression model.

## Summary Statistics on Suspension Coils
![total_summary](https://user-images.githubusercontent.com/107447648/205460842-99d9ef5c-d607-4220-9354-68bcb6d9efd9.png)
![lot_summary](https://user-images.githubusercontent.com/107447648/205460853-c40f1f73-e233-4968-b4d0-45e003fd40f7.png)
 
 total_summary variance meets the the specificatios but if we look at the lot_summary we will see that lot 1 and 2 also meets those specifications but 3 is over the requirements.


## T-Tests on Suspension Coils

![Deliverable 1](https://user-images.githubusercontent.com/107447648/205461833-bd22ea35-db75-4600-b1c5-2f3217ba9b37.png)

This is the p-value for the lots combined, it came out to be 0.06028 which is higher than the critical value meaning it fail to reject the null hypothesis that there is a statistical difference between the different lots and the population mean of 1,500.

![t1](https://user-images.githubusercontent.com/107447648/205461856-a87dc4f0-1b8d-4572-ac78-c72ff4ebcee8.png)

The result for lot 1 shows they are statistically different from the population mean, also the p-value is not low enough to reject the null hypothesis.

![t2](https://user-images.githubusercontent.com/107447648/205461861-740a5f8d-02a0-4da1-9e81-f70bbbe0b761.png)

For lot 2 we got the same result as lot 1

![t3](https://user-images.githubusercontent.com/107447648/205461869-9154c777-8780-4d79-9e03-24df77478cb8.png)

Lot 2 shows that it is just a bit statistically different also the p-value is low enough to reject the null hypothesis.

## Study Design: MechaCar vs Competition

In a world where ridesharing is becoming more common and it is made easily accessable, people looking to purchase a car will want to go for horse power. 

What metric or metrics are you going to test?

We should test MechaCar's carrying capacity, in cubic inches.

What is the null hypothesis or alternative hypothesis?

Null hypothesis is that all cars have the same horse power regardless of the class or make. Alternative hypothesis is that it's not the same for all cars.

What statistical test would you use to test the hypothesis? And why?

 two sample t-tests
 
What data is needed to run the statistical test?

we would need to collect horsepower data of both Mecha cars and competitor cars in order to complete this analysis.
