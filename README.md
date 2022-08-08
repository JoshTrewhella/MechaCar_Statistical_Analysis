# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![Alt text](https://github.com/JoshTrewhella/MechaCar_Statistical_Analysis/blob/main/Images/D1_LR.PNG)

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
According to the data, the vehicle length and vehicle ground clearing metrics are non-random. This implies these have a significant impact on the MPG.

2. Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is not zero. We can determine this by looking at the p-Value, which is 5.35e-11 (smaller than the significance level of 0.05%). 

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The multiple r-squared value of 0.7149 implies that 71% of the mpg can be determined by the metrics included in this model. We can say that this model does predict the MPG of the prototypes effectively. 

## Summary Statistics on Suspension Coils
Total Summary

![Total Summary](https://github.com/JoshTrewhella/MechaCar_Statistical_Analysis/blob/main/Images/D2_TS.PNG)

Lot Summary

![Lot Summary](https://github.com/JoshTrewhella/MechaCar_Statistical_Analysis/blob/main/Images/D2_LS.PNG)

According to the total summary, as a whole the design specifications do meet the 100 pounds per square inch requirement for PSI. However, when you look at the lot summary, the third lot does not meet the requirements with a variance of over 100.

## T-Tests on Suspension Coils
Overall Suspension Coil T-Test

![TT](https://github.com/JoshTrewhella/MechaCar_Statistical_Analysis/blob/main/Images/D3_TT.PNG)

Due to the p-value of the overall T-Test being higher than 0.05 we can say that there is no difference between the population mean of the PSI and the manufacturing lot sample. 

Lot 1 T-Test

![TT1](https://github.com/JoshTrewhella/MechaCar_Statistical_Analysis/blob/main/Images/D3_Lot1TT.PNG)

The p-value being 1 tells us that the lot1 sample is exactly the same as the population mean.

Lot 2 T-Test

![TT2](https://github.com/JoshTrewhella/MechaCar_Statistical_Analysis/blob/main/Images/D3_Lot2TT.PNG)

The p-value of 0.6072 tell us that there is no difference between the population mean of the PSI and the manufacturing lot sample and the null hypothesis should be accepted.

Lot 3 T-Test

![TT3](https://github.com/JoshTrewhella/MechaCar_Statistical_Analysis/blob/main/Images/D3_Lot3TT.PNG)

The p-value of 0.04168 tells us that there is a difference between the population mean of the PSI and the manufacturing lot sample and the null hypothesis should be rejected.
