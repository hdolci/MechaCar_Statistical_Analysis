# MechaCar Statistical Analysis

## Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Spoiler_angle , vehicle weight, & AWD provided a non-random amount of variance.

Is the slope of the linear model considered to be zero? Why or why not?

No, due to the p-value (screenshot below)

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Yes, with the limited scope of variables, it was still able to correctly forecast roughy 71%(R-Square) of the time.

<img src="https://raw.githubusercontent.com/hdolci/MechaCar_Statistical_Analysis/main/Screenshots/Part%201%20Summary.png" width="50%" height="50%">

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? 

Why or why not?

Lot 1 and Lot 2 are within specifications and have little variance with mean and median. Lot 3  not exceeds the manufacturers specs but does so with the most variance between the mean and median. 


<img src="https://raw.githubusercontent.com/hdolci/MechaCar_Statistical_Analysis/main/Screenshots/Part%202%20Summary.png" width="50%" height="50%">
 









## T-Tests on Suspension Coils
Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

I was able to find that Lot 1 and Lot 3 the PSI values are the same as the population mean. Lot 2 p-value is .6072 which could mean it will differ from the population mean.

<img src="https://raw.githubusercontent.com/hdolci/MechaCar_Statistical_Analysis/main/Screenshots/Part%203a%20Summary.png" width="50%" height="50%">
<img src="https://raw.githubusercontent.com/hdolci/MechaCar_Statistical_Analysis/main/Screenshots/Part%203b%20Summary.png" width="50%" height="50%">
<img src="https://raw.githubusercontent.com/hdolci/MechaCar_Statistical_Analysis/main/Screenshots/Part%203c%20Summary.png" width="50%" height="50%">

## Study Design: MechaCar vs Competition


The major considerations to buying a new car I suspect to be are MPG, horsepower, and engine size. With the data we are given, this can be test. The null hypothesis is to indicate MechaCar is little to no difference from its peers. I would use t-testing to compare the population among the different cars.






