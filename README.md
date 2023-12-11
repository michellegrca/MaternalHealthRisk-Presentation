# MaternalHealthRisk-Presentation
In this presentation Logistic Regression is used in the "Maternal Health Risk Data" dataset to find the variables that can identify a persons Risk Level. 
The independent variables are: Age, SystolicBP (Blood Pressure), DiastolicBP (Blood Pressure),BS (Blood Sugar), Body Temp, and Heart Rate. 
The Target/Dependent Variable is Risk Level, either High or Low. 
The data is then prepared by making sure there are no incorrect values, checking for outliers and missing values. 
After that is done, we create the Model 1, that consists of variables: Age, SysolicBP, DiastolicBP, BS, and BodyTemp.
Based on this model, SystolicBP, DiastolicBP, BS, and BodyTemp have high coefficients meaning that there is a high correlation. 
The accuracy is 0.89 and AUROC is .8277
For model 2, the variables that are used are: Age, SystolicBP, DiastolicBP, and BS.
Based on this model only SystolicBP and BS have high coefficients. 
The accuracy is .89 and AUROC is .72
For modeling, I will use Model 1. 
In order to predict whether a persons risk level you will use this equation: 
Logit(P(RiskLevel))=intercept+(.86*SystolicBP)+(.57*DiastolicBP)+(.63*BS)+(1*BodyTemp)
P (RiskLevel) = (e^(RiskLevel)/1 + e^(RiskLevel))
 Thank you!
