# MechaCar_Stastical_Analysis

## Linear Regression to Predict MPG

To understand the impact of vehicle length, weight, spoiler angle, ground clearance, and AWD on miles per gallon, mulitple linear regression was run and the p values were provided to determine randomness. According to the statistics seen above, vehcile_length and ground_clearance are unlikely to provide random amounts of variance to the linear model. Additionaly, you see that the slope of the significant variables, vehicle_length and ground_clearance, are positive and not zero. Vehicle-length has a slope of 6.3 meaning that increasing the vehicle length by 6.3 will increase the mpg. Similarly, the slope of ground_clearance is 3.5, so as ground_clearance increasses, so does mpg.

Each of these variables, help predict the Mecha Car prototypes; however, the intercept shows as significant. This means that vehicle_length and ground_clearance need to be scaled for a better predictive model or there are other variables that contribute to the variability of the MechaCar prototype. Lastly, the r-squared value increased to .71 meaning that the multiple linear regression outperformed the linear regression by .03. Therefore, the multiple linear regression did support a more effective model.
