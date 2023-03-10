# MechaCar_Statistical_Analysis
### Part 1: Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/111200771/215296608-13ff20bb-1541-4537-8784-a795be9e8bba.png)

   According the linear regression analysis in R, the strongest contributor of non-random variance seems to be teh vehicle weight with a P-value of 2.60e-12. Another strong contributor is ground clearance with a P-value of 5.21e-08. 

   The slope of this particular linear model is not zero. The slope coefficients contain significant non zero values for each variable, with p-values for vehicle length and ground clearance less than the significance level of p=0.05. 

   The r-squared value calculated for this linear model is 0.7149, meaning this model has good predictive power for the prediction on mpg of current and future vehicles.
    
### Part 2: Summary Statistics on Suspension Coils
   Total Summary   
![image](https://user-images.githubusercontent.com/111200771/215297836-1200c366-eeb5-4370-bd8b-71d3b37a5c97.png)

   Lot Summary    
![image](https://user-images.githubusercontent.com/111200771/215297833-198ef51e-be95-4b19-aa09-09fa205fa05e.png)


   For all manufacturing lots together the current design meets the variance specifications of 100 PSI with a total variance of 62.29 PSI. The contributor to the high PSI variance is Lot 3 which does not meet the variance specifications with a variance of 170.29 PSI. Lot 1 and Lot 2 both meet the specifications on their own with a variance of 0.98 PSI and 7.47 PSI respectively.

### Part 3: T-Test on Suspension Coils

All Lots :

![image](https://user-images.githubusercontent.com/111200771/215298993-e9d73d2c-8694-408c-bac4-23c44acc958f.png)

Lot 1 :
![image](https://user-images.githubusercontent.com/111200771/215298982-f6189362-9963-4c74-8e06-5218c6bc22b1.png)

Lot 2 :
![image](https://user-images.githubusercontent.com/111200771/215298900-cc5bc029-6954-4cf4-9253-76d94f2dcdbf.png)

Lot 3 :
![image](https://user-images.githubusercontent.com/111200771/215298905-93091f7f-91c8-4c5d-9156-00b14a4b2817.png)

   From the t-test for all the lots combined the coils are not statistically different from the population mean of 1500 PSI with a mean of 1498.78 PSI and a p-value of 0.06028. Each lot individually produce different results. Lot 1 and 2 are not statistically different from the population mean with means at 1500 and 1500.2 respectively and p-values of 1 and 0.6072 respectively. Lot 3 is statistically different with a mena of 1496.14 and a p-value of 0.04168. 
    
    
### Part 4: Design a Study Comparing the MechaCar to the Competition
   In order to compare the MechaCar to the competition additional testing will need to be performed. The metrics that need to be looked at when comparing MechaCar to the competition are cost, city and highway miles fuel efficiency, horse power, and safety rating. 

   The testing will be comprised of comparing the statistical variability of MechaCar to the competition in each metric. The null hypothesis would be that MechaCar is not statistical different from the competition. The alternative hypothesis is that MechaCar is statistically variable against the competition in each variable.

   The statistical tests that would be used to compare MechaCar against the competition, would be multiple t-tests to see if the MechaCar rates higher or lower statistically. The variables that MechaCar would want to score lower on are cost, and the variables it would want to score higher on are safety rating, fuel efficiency, and horsepower. 

   The data needed would be industry data reports on the safety rating, fuel efficiency, cost, and horsepower of the top vehicle make and models in the competition. 
