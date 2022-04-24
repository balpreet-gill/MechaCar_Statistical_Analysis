# MechaCar_Statistical_Analysis
## Overview 

- AutosRUs' upper management has called on Jeremy and the data analytics team to review the production for insights that may help the manufacturing team. In this analysis, multiple regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes, then summary statistics are performed on the pounds per square inch (PSI) of the suspension coils from  the manufacturing lots, t-tests are ran to determine if the manufacturing lots are statistically different from the mean population, at last a statistical study is deisgned to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. 

## Linear Regression to Predict MPG 
![1](https://user-images.githubusercontent.com/95098281/164988028-bb3d66f6-20e9-4ea4-b452-bb08b42e9695.png)

### Results:
- Length and ground clearance provided a non-random amount of variance to the mpg values in the dataset. 
- The slope of the linear model is not considered to be zero, as some of the independanct variables were statistically significant. The three asterisks denote a highly significant p-value for vehicle length and ground clearance have a Pr(>t) of about 0. 
- The linear model predicts mpg of MechaCar prototypes effectively 71% of the time, as the R-squared value is 0.7149. 

## Summary Statistics on Suspension Coils 
### PSI Metrics for all Manufacturing Lots
- A summary statistics table was created to show the suspension coil's PSI continuous variable across all manufacturing lots. 
![2](https://user-images.githubusercontent.com/95098281/164988043-83b77283-589a-4c2a-aee1-9b8bf71ca786.png)

### PSI Metrics for Each Lot
- A summary statistics table was created to show the following PSI metrics for each lot: mean, median, variance, and standard deviation. 
![3](https://user-images.githubusercontent.com/95098281/164988047-dcf36cf0-1f13-4b4d-a343-c7ecadb4b53f.png)

### Results:
- The variance of PSI for all manufacturing lots does not exceed the 100 pounds per square inch limit. 
- The variance for Lot 1 and Lot 2 meets the deisgn specifications as their representative variance, falls within range. However, Lot 3 does not meet the design specificationa as the variance is 170.2861224 and therefore exceeds the 100 pounds per sqaure inch limit. As such, suspension coils from Lot 1 and Lot 2 should be used. 

## T-tests on Suspension Coils 
![5](https://user-images.githubusercontent.com/95098281/164988055-87f5f0a1-b2c9-45a5-88f9-250e2bba85f9.png)
![6](https://user-images.githubusercontent.com/95098281/164988056-fa44e055-91bd-463d-b595-1ae533b81b94.png)

### Results:
- Across all manufacturing lots, PSI is not statistically different from the population mean of 1,500 pounds per square inch, as the p value of 0.06028 is higher than 0.05, which indicates strong evidence for mainataining the null hypothesis. 
- The PSI for manufacturing Lots 1 and 2 are not statistically different, as the respective p-values of 1 and 0.06072 are higher than 0.05. The PSI for Lot 3 is statisticallly different, as P value is below 0.05, which means we will reject the null hypothesis. 

## Study Design: MechaCar vs Competition 
- A metric to be tested is mentioned: fuel efficieny and vehicle type (different types such as convertible, coupe, crossover, diesel engine, hybrid, luxury, minivan, van, pickup truck, sedan, sports car, SUV, wagon)
- A null hypothesis or an alternative hypothesis is described: Null hypothesis will state that MechaCar's vehicle have similar fuel efficieny to those from other manufacturers. 
- A statistical test is described to test the hypothesis: For this AVONO test will work best because that will validate the hypothesis and determine whether the differences are statistically significant. 
- The data for the statistical test is described: The data needed will be all the vehicle reports from different manufacturers, a sample size will be decided and the fuel economy will be considered. 
