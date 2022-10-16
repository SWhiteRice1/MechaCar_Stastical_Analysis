# MechaCar_Stastical_Analysis

## Linear Regression to Predict MPG
![Screen Shot 2022-10-15 at 3 26 46 PM](https://user-images.githubusercontent.com/106640154/196055356-2650777d-5486-4ea7-8597-c16819bcb5e8.png)

To understand the impact of vehicle length, weight, spoiler angle, ground clearance, and AWD on miles per gallon, mulitple linear regression was run and the p values were provided to determine randomness. According to the statistics seen above, vehcile_length and ground_clearance are unlikely to provide random amounts of variance to the linear model. Additionaly, you see that the slope of the significant variables, vehicle_length and ground_clearance, are positive and not zero. Vehicle-length has a slope of 6.3 meaning that increasing the vehicle length by 6.3 will increase the mpg. Similarly, the slope of ground_clearance is 3.5, so as ground_clearance increasses, so does mpg.

Each of these variables, help predict the Mecha Car prototypes; however, the intercept shows as significant. This means that vehicle_length and ground_clearance need to be scaled for a better predictive model or there are other variables that contribute to the variability of the MechaCar prototype. Lastly, the r-squared value increased to .71 meaning that the multiple linear regression outperformed the linear regression by .03. Therefore, the multiple linear regression did support a more effective model.

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.
![Screen Shot 2022-10-15 at 3 32 28 PM](https://user-images.githubusercontent.com/106640154/196055363-e5036829-bc94-4498-8618-244901ec733a.png)

Above you can see a total summary created with mean, median, variance, and standard deviation of the coils PSI and number of coils. Of the 150 coild, the variance of the coils is around 62 PSI which is within the 100 pounds per square inch of the MechaCar design specification.

## T-Tests on Suspension Coils
Perform t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.
![ttest](https://user-images.githubusercontent.com/106640154/196055369-87e4da7f-1798-4db8-91cc-b9ca356f6ccc.png)

According to the above T tests of the total PSI across all manufacturing lots, they are all statstically similar to the population mean of 1500 pounds per square inch. This is obvious due to the p value being greater than .05 and the mean of x being defined as 1498.
![lot1_ttest](https://user-images.githubusercontent.com/106640154/196055372-fbd05162-a74d-4c2e-a29c-be9d45141a0d.png)
![lot2_ttest](https://user-images.githubusercontent.com/106640154/196055375-fccd03f7-3879-400a-8644-732d85e8842f.png)
![lot3_ttest](https://user-images.githubusercontent.com/106640154/196055384-a2479e7c-4fb5-484c-bede-610a6a7569b0.png)

Additionally, the t tests performed on lots 1-3 reveal that lot 1 and 2 are within the 1500 pounds means; however, lot 3 reveals a p value of less than .05 and a mean of 1496 being just sht of the 1500 population mean.

## Study Design: MechaCar vs Competition
