# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

1) Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle length 
- Ground clearance 
2) Is the slope of the linear model considered to be zero? Why or why not?
- The slope of the linear model is not zero because there was a significant linear relationship between the dependent and some of the independent variables. 
3) Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- Yes. P-value is much smaller than required 0.05

![summary_lm.png](https://github.com/Emmagrace878/MechaCar_Statistical_Analysis/blob/main/images/summary_lm.png)


## Summary Statistics on Suspension Coils


1) The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

- Across all manufacturing lots, the data does meet design specifications. This is because an average of all lots is taken and lot 1 and 2 compensate for lot 3 

![PSI_summary.png](https://github.com/Emmagrace878/MechaCar_Statistical_Analysis/blob/main/images/PSI_summary.png)

- For each lot individually, all lots do not meet design specifications. This is becuase lot 3 has a higher variance

![lot_summary.png](https://github.com/Emmagrace878/MechaCar_Statistical_Analysis/blob/main/images/lot_summary.png)


## T-Tests on Suspension Coils

Evualtation of the t-test results show that there is a normal to low significant relationship between MechaCar's coil PSI and the population mean. 

![t.test.png](https://github.com/Emmagrace878/MechaCar_Statistical_Analysis/blob/main/images/t.test.png)


## Study Design: MechaCar vs Competition

1) What metric or metrics are you going to test?
- Cubic square feet of trunk size for MechaCar vs. competitors' cars
2) What is the null hypothesis or alternative hypothesis?
- Null Hypothesis 
There is no significant difference between MechaCar trunk space and the average trunk space of the competition
- Alternative Hypothesis
There is a significant difference between MechaCar trunk space and the average trunk space of the competition
3) What statistical test would you use to test the hypothesis? And why?
- ANOVA to compare the MechaCar mean trunk size against the mean trunk sizes of various other similar competitor vehicles. I would use ANOVA becuase I am comparing many different samples. 
4) What data is needed to run the statistical test?
I would need the mean trunk size of Mechcar vehicles and the mean trunk sizes of competitor vehicles 
