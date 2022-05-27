#Determination of Women’s Body Fat Percentage Rate Based on Anthropometric Variables by applying MLR
Group Project By
Naveen Morla
Sarath Madapana
Mehmet Tarık Atay

Objectives :
I.	To create a regression model of body-fat ratio with  6 different anthropometric variables,

II.	To understand which variables are associated with increases or decreases in body-fat ratio in 136 randomly selected women with various ages and to what extent
III.	To predict future body-fat ratio rates resulting from changes in the values of  certain anthropometric variables

Research Questions

How many variables are ther in the final model?
What anthropometric type variables are associated with body-fat ratio value?


Research data details  Model construction

Location of the data coming from

These data were obtained randomly in a polyclinic in a suburb ( 20 thousand population ) of a midsized Turkish city called (Trabzon with population is around 815 ,000  people) ,  northern part of Turkey. Data obtained from the patients-volunteers who have been having slightly extra weight problem for the time of data collection.

This is an analytical study on evaluation of some antropometric which are believed to have an effect regarding measurements obtained from   the women who have been experiencing of being overweight or obesity.
Methods:

Multiple Regression Method will be used for analysis of the given data.
We first fit a multiple linear regression model containing all explanatory variables.


Response variable ( ): what we are trying to model or predict (2018 under-five mortality).

Explanatory variables ( ): the variables that we are analyzing for their impact on the response variable (the under-five mortality rate). The explanatory variables are listed in section 3.1.
Regression Coefficients ( ): values computed in our regression analysis that reflect the direction (positive versus negative) and strength of each explanatory variable  to the dependent variable.
Error term ( ): the portion of the dependent variable that is not explained by the regression.


Dependence between independent variables, multiple linear relationships are searched for for their interdependencies.
For the case of independent variables are having interdependency relationship, multiple linear regression model type of analysis will be conducted to obtain an clear understanding.

The varibales to be used in this study to determine the level of body-fat ratio of the voluntiered subject women are given in the following table

Variables used in this model and their unit measurement scales 

Variable types	Variables	Measurement Units	Represent.
Dependent Variable	
	Body -Fat ratio	% (Percentage)	𝑌
Independent Variable
	Age				Yıl			𝑋1
	Height			cm			𝑋2
	Waist Circum.		cm			𝑋3
	Hip Circumference	cm			𝑋4
	Chest Circum.		cm			𝑋5
	Upper arm Circum 	cm			𝑋6

For 80 % power and   𝛼 = 0,05 are selected;

•	To obtain 𝑅2 = 0,23 (𝑟 =0,48) or more, sample size should be selected as 50 .
•	To obtain 𝑅2 = 0,12 (𝑟 =0.35) or more, sample size should be selected as  100.
 
•	In general, for every independent variable to be used in the study, number of subject to be used should be at least 5. But, what is desired is for each independent variable, that subject number should be 15-20 units. Bir başka görüş şöyledir (Pamukçu, 2010).

For our data collected case, if we call “n” as the collected sample unit size, and “m” stands for the number of independent variables to used in a model, in order to test the multiple corelation number,  the number “n” should satisfy 𝑛 >50+8𝑚 requirement. (m: number of independent variables)
6.	For testing the relationship between each of the independent variables and dependent variable, “n” should be taken as  𝑛 >140+𝑚 alınır. For testing the relationship between each of the independent variables and dependent variable
Based on these informationregarding sample size matter, n = 136 can be a reasonable size to conduct study on.


Use the following data source:
Data was collected from volunteer ladies in a small Turkish city in a specific recreational area in an inner-city park. The genuine data was collected from 136 women using a data sample set with the following variables.
Dependent variables: body fat percentage rate of women as the Y variable 
Independent variables: age, height, waist diameter, hip diameter, chest diameter, upper arm diameter, x1, x2, x3, x4, x5, x6 as age, height, waist diameter, hip diameter, chest diameter, upper arm diameter.
Analytical objectives:
In the previously described multiple linear regression analysis, the multiple linear connection problem emerges when explanatory variables are substantially connected with one another. In this study, utilizing basic R software applications to produce statistical descriptive analysis findings will provide us internal dynamics of the dependent and independent variables, which will be explored when the factors impacting the body fat ratio have multicollinearity concerns.
Language used in the tools:
R program will be used to examine the data of the variables, as well as a few visualization libraries such as car, StepReg, and MASS, many more other libraries which are not included in course.

