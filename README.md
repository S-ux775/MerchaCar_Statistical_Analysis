<<<<<<< HEAD
# MerchaCar_Statisticall_Analysis

## 1) Linear Regression to Predict MPG,

A linear regression model was perfomed on six variables for vehicle analysis. Under null hypothesis, we would expect no significancant difference between sets of population.

In this model, we observe some variables to have more impact than others.

dependent variable (Y): mpg
independent variables (X1 to X5): 
vehicle_length, vehicle_weight, spoiler_angle, ground_clearance, AWD

The outcome showed that: vehicle weight and ground clearance had the most correlation to mpg: 69.9% and 32.9%, respectively. 

Analysis of these two variables to mpg showed:
* vehicle_length
p= 2.63 e-06
R2= 0.3584

* ground_clearance
p= 0.01975
R2= 0.089

p values for both variables are lower than significance threshold of p<0.05. Therefore, the null hyoothesis may be rejected.

R2 values are > 0 for these two variables while the other dependent variables showed negative R2 values that indicate linear regression model for those variables relate poorly to mpg.

For the combined analysis:
p-value < 0.05
Adjusted R2 of 68.25%. The model predicts mpg variability to this degree.

Coefficients:
An Intercept is reported: -1.040e+02

D1_Summary_model.png

## 2) Summary Statistics on Suspension Coils,
## comments

The Suspension_Coil.csv file was used as raw data to create two dataframes and display the appropiate data.

a) total_summary table was created from the dataframe with the same name that was created using the summarize function to get the statistics of the suspension coil PSI column from the raw data.

b) lot_summary table was created from the dataframe with the same name that was created using groupby and summarize functions.

## 3) T-Tests on Suspension Coils 

We use T-Test to see if there is statistical difference under 4 scenarios:

a) All manufacturing lots
All manufacturing lots vs. the presumed population mean of 1500 psi.
When performing the t-test, we get:
p=1
mean= 1,498.78

b) Lot 1
Comparison of Lot 1 vs. the presumed population mean of 1500 psi:
p=1
mean= 1,500

c) Lot 2
Comparison of Lot 2 vs. the presumed population mean of 1500 psi:
p= 0.6072
mean= 1500.2

d) Lot 3
Comparison of Lot 3 vs. the presumed population mean of 1,500:
p= 0.04168
mean= 1,496.14

ONLY in this last case p < 0.05 (significance level), therefore THERE IS an statistical difference vs. average population mean of 1,500 psi.

Plese refer to images folder.

## 4) Study Design: MechaCar vs Comtentio.

Another potential Study consider could compare mpg efficency of MerchaCar vs. Competition.

Dependent variable: mpg
Independent variable: hp
Car size categories: A) Small B) Mid Size C) Large

Data: mpg records per carmaker and model type
Assumptions: Data is normally distributed

H0: mpg is independent of car manufacturer. There is no significant statistidcal difference in avg mpg.
Ha: There is significant stastical difference (p ≤ 0.05) among car maker and car category.

Statistical Analysis: Perform an ANOVA T-Test for each category and determine if there is statistical difference in the avg mpg for each category and car maker.






=======
# MerchaCar_Statistical_Anallysis
>>>>>>> 5a327a435b4a16df64745e4e7522d20b379b2dae
