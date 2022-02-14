# MechaCarChallenge
## Linear Regression to Predict MPG

<img width="470" alt="Screen Shot 2022-02-13 at 8 05 26 AM" src="https://user-images.githubusercontent.com/92963227/153789002-fbdb8a58-6a20-46fb-a4c1-e4364422c59b.png">

 * Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The vehicle length and the vehicle ground clearance provide non-random amounts of variance to the model.

 * Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is is not zero. This is because the p-value is 5.35e-11 which is much smaller than the 0.05% significance level, indicating a rejection of the null hypothesis meaning that the slope is not zero.

 * Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

This linear model does predict the mpg effectively because the R^2 value is 0.7149, meaning the amount of predictions that will be determined by the model is 71%.

## Summary Statistics on Suspension Coils

<img width="408" alt="Screen Shot 2022-02-13 at 8 11 45 AM" src="https://user-images.githubusercontent.com/92963227/153789618-c7ae72fe-124f-414e-a113-54ed4364a671.png">

<img width="556" alt="Screen Shot 2022-02-13 at 8 11 56 AM" src="https://user-images.githubusercontent.com/92963227/153789621-c544d2c5-c103-4a25-b5d0-e2c1d730b957.png">


The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. 

 * Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Using the above tables, it is clear that for the manufacturing data for all lots combined, the variance of the coils is 62.29 PSI. The variance requirement is 100 PSI, which means that the data for all the lots meets the design specification. For the individual lots, 

## T-Tests on Suspension Coils
then briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

## Study Design: MechaCar vs Competition
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

What metric or metrics are you going to test?

What is the null hypothesis or alternative hypothesis?

What statistical test would you use to test the hypothesis? And why?

What data is needed to run the statistical test?
