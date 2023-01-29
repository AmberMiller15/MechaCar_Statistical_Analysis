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

### Part 4: Design a Study Comparing the MechaCar to the Competition
