# MechaCar_Statistical_Analysis
### Background
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, you’ll help Jeremy and the data analytics team do the following:

Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
Run t-tests to determine if the manufacturing lots are statistically different from the mean population
Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict MPG

### Linear Regression
![](https://github.com/Aitorgoyare/MechaCar_Statistical_Analysis/blob/main/Images/linear%20regression.png)

### Linear Regression Summary
![](https://github.com/Aitorgoyare/MechaCar_Statistical_Analysis/blob/main/Images/summary.png)

* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle Weight - 0.0776

Spoiler Angle - 0.3069

AWD - 0.1852

* Is the slope of the linear model considered to be zero? Why or why not?

slope of the linear model is not considered to be zero because the p-value (p-Value: 5.35e-11 ) is less than 0.05 

* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The model predict that 71% precision (r-squared 0.7149) which means that the model predicts MPG of MechaCar effectively.

## Summary Statistics on Suspension Coils

### Manufacturing Lot Summary
![](https://github.com/Aitorgoyare/MechaCar_Statistical_Analysis/blob/main/Images/Total%20summary.png)

### Manufacturing Lot Number Summary
![](https://github.com/Aitorgoyare/MechaCar_Statistical_Analysis/blob/main/Images/lot%20summary.png)

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Although the deviation overall is under 100 psi and in compliance with the specifications, there is a problem with one of the individual lots. As displayed in the batch summary statistics, the lot 3 deviation is well above the acceptable limit, at 170.28.

## T-Tests on Suspension Coils

### T-test Lots
![](https://github.com/Aitorgoyare/MechaCar_Statistical_Analysis/blob/main/Images/Test%20lots.png)

### T-test Lot 1
![](https://github.com/Aitorgoyare/MechaCar_Statistical_Analysis/blob/main/Images/Test%20lot%201.png)

### T-test Lot 2
![](https://github.com/Aitorgoyare/MechaCar_Statistical_Analysis/blob/main/Images/Test%20lot%202.png)

### T-test Lot 3
![](https://github.com/Aitorgoyare/MechaCar_Statistical_Analysis/blob/main/Images/Test%20lot%203.png)

The total manufacturing, batch 1 and batch 2 indicates a normal distribution. Consequently, there is not enough proof to reject the null hypothesis, which states that the two means are statistically similar.

## Study Design: MechaCar vs Competition

* What metric or metrics are you going to test?

When comparing theMechaCar with the competition, many factors can be taken into consideration:

1) Starting with one of the most determining factors in vehicles, which is fuel efficiency.
2) Cost of Insurance
3) Space

* What is the null hypothesis or alternative hypothesis?

We can make a null hypothesis stating that there is no difference between MechaCar and the competition and our Alternative would be the contrary. 

* What statistical test would you use to test the hypothesis? And why?

T-test. Because it allows us to compare each metric of the MechaCar against the metrics of any competing vehicle.

* What data is needed to run the statistical test?

We would need to have information on fuel consumption (liters/kilometers), insurance price (dollars) and space (cubic meters) to be able to compare them with those of the competition.


