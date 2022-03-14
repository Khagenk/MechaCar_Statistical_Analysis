# MechaCar_Statistical_Analysis
## Resources
-  R
- Dependency
- dplyr
- RStudio
Datasets
     - MechaCar_mpg.csv
     - Suspension_Coil.csv


## Linear Regression to Predict MPG

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
￼![Im(formula = mpg vehicle_length + vehicle_weight + spoiler_angle](https://user-images.githubusercontent.com/94031446/158091948-b666743f-307b-4911-b1b9-149324593f8a.png)

    * Following Coefficients provide a non- random amount of variance to the mpg value:
        * vehicle_length    
        * vehicle_weight 
        *  spoiler_angle  
        * ground_clearance
        * AWD
* Is the slope of the linear model considered to be zero? Why or why not?
    * The slop of this linear model is not zero because the p-Value for the model is, p-Value: 5.35e-11. Therefore, data indicates there is sufficient evidence to reject the null hypothesis.
* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
    * The linear model does predict mpg of MechaCar prototypes effectively, because the linear model has a R-Squared value of .7149.
￼![Residuals](https://user-images.githubusercontent.com/94031446/158091983-0a73495b-3e29-46b8-bd92-a1e5c7a71267.png)

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 

* Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
    * The current manufacturing data does meet the design specification for manufacturing lots since the variance of the coils is 62.29 PSI.
￼![Packages](https://user-images.githubusercontent.com/94031446/158092000-8b17b231-d1fb-4a79-bb1c-2792c43af525.png)

## T-Tests on Suspension Coils
one-sample t-test was used to determine whether or not if PSI across all manufacturing lots was statistically different from the population mean of 1500 PSI.
* The true mean of the sample is 1498.78 with the p-value of .06, which is higher then the common significance level of .05, thus there is NOT enough evidence to support rejecting the null hypothesis. 

![95 percent confidence interval](https://user-images.githubusercontent.com/94031446/158092132-2915ead2-8a39-4503-805d-579596f7da23.png)




  
￼
