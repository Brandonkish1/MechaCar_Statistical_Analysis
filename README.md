# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

1. Vehicle Length, ground clearance and intercept provided a non-random amount of variance to the mpg values in the dataset.
2. The slope of the linear model is not considered 0 because the pvalue is less than .05. 
3. The linear model does predict mpg of MechaCar prototypes effectively because the r squared value is 0.7149, closer to 1.

![Challenge_Deliverable_1.png](https://github.com/Brandonkish1/MechaCar_Statistical_Analysis/blob/main/images/Challenge_Deliverable_1.png)

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.
Looking at the total summary it appears that the manufacturing data meets this specification as the variance is 62.29356 psi. 

![Deliverable_2_Total_Summary.png](https://github.com/Brandonkish1/MechaCar_Statistical_Analysis/blob/main/images/Deliverable_2_Total_Summary.png)

When we look at the data at a lot level. Lot1 and Lot2 meet the variance specification but Lot 3 does not. 

![Deliverable_2_Lot_Summary.png](https://github.com/Brandonkish1/MechaCar_Statistical_Analysis/blob/main/images/Deliverable_2_Lot_Summary.png)

## T-Tests on Suspension Coils

There is a statistical difference between the distribution means from Lot 3 and the population. The p value is high.

![Deliverable_3_Pop_T-Test.png](https://github.com/Brandonkish1/MechaCar_Statistical_Analysis/blob/main/images/Deliverable_3_Pop_T-Test.png)
![Deliverable_3_Lot_T-Tests.png](https://github.com/Brandonkish1/MechaCar_Statistical_Analysis/blob/main/images/Deliverable_3_Lot_T-Tests.png)

## Study Design: MechaCar vs Competition
To compare MechaCar to its competition the best test to use would be an ANOVA test. You could compare the means accross the samples in each of the falling categories cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating. If the p-value is greater than .05 then both MechaCar and its competition perform similarly. If the p-value is less than .05 then the categories above are statistically different. You would have to look at the averages in each category vs. the competitor to determine if MechaCar performs better or worse than the competition.
