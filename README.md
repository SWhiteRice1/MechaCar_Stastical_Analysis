# MechaCar_Stastical_Analysis

## Linear Regression to Predict MPG

To understand the impact of vehicle length, weight, spoiler angle, ground clearance, and AWD on miles per gallon, mulitple linear regression was run and the p values were provided to determine randomness. According to the statistics seen above, vehcile_length and ground_clearance are unlikely to provide random amounts of variance to the linear model. Additionaly, you see that the slope of the significant variables, vehicle_length and ground_clearance, are positive and not zero. Vehicle-length has a slope of 6.3 meaning that increasing the vehicle length by 6.3 will increase the mpg. Similarly, the slope of ground_clearance is 3.5, so as ground_clearance increasses, so does mpg.

Each of these variables, help predict the Mecha Car prototypes; however, the intercept shows as significant. This means that vehicle_length and ground_clearance need to be scaled for a better predictive model or there are other variables that contribute to the variability of the MechaCar prototype. Lastly, the r-squared value increased to .71 meaning that the multiple linear regression outperformed the linear regression by .03. Therefore, the multiple linear regression did support a more effective model.

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

Above you can see a total summary created with mean, median, variance, and standard deviation of the coils PSI and number of coils. Of the 150 coild, the variance of the coils is around 62 PSI which is within the 100 pounds per square inch of the MechaCar design specification.

## T-Tests on Suspension Coils
Perform t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

According to the above T tests of the total PSI across all manufacturing lots, they are all statstically similar to the population mean of 1500 pounds per square inch. This is obvious due to the p value being greater than .05 and the mean of x being defined as 1498.

Additionally, the t tests performed on lots 1-3 reveal that lot 1 and 2 are within the 1500 pounds means; however, lot 3 reveals a p value of less than .05 and a mean of 1496 being just sht of the 1500 population mean.
