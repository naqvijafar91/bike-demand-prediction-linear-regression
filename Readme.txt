=========================================
Dataset characteristics
=========================================	
day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered
	
=========================================
License
=========================================
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}

=========================================
Contact
=========================================
	
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)




Linear regression is a fundamental statistical and machine learning algorithm used for modeling the relationship between a dependent variable (target) and one or more independent variables (features). It is often employed for predicting a continuous numeric outcome. Here's a detailed explanation of the linear regression algorithm:

1. Objective:
Linear regression aims to find the linear relationship between the independent variables and the dependent variable. It seeks to create a linear equation that best fits the data, allowing us to make predictions based on this equation.

2. Linear Model:
The core of linear regression is a linear model, expressed as:

Y = β₀ + β₁X₁ + β₂X₂ + ... + βₙXₙ + ε

Y is the dependent variable.
X₁, X₂, ..., Xₙ are the independent variables.
β₀, β₁, β₂, ..., βₙ are the coefficients (parameters) that we want to estimate.
ε represents the error term, which accounts for the variability not explained by the model.
3. Estimating Coefficients:
The goal is to determine the coefficients (β₀, β₁, β₂, ...) that minimize the sum of squared differences between the predicted values (Ŷ) and the actual values (Y) in the training dataset. This is usually done using a method like Ordinary Least Squares (OLS).

4. Assumptions:
Linear regression relies on several key assumptions, including:

Linearity: The relationship between independent and dependent variables is assumed to be linear.
Independence: Errors (ε) are independent of each other.
Homoscedasticity: The variance of errors is constant across all values of the independent variables.
Normality: The errors follow a normal distribution.
5. Types of Linear Regression:

Simple Linear Regression: Involves a single independent variable.
Multiple Linear Regression: Uses multiple independent variables.
Polynomial Regression: Allows for polynomial relationships between variables.
Ridge and Lasso Regression: Regularized linear regression methods to prevent overfitting.
Logistic Regression: Used for binary classification.
6. Model Evaluation:
Various metrics like Mean Squared Error (MSE), R-squared (R²), and adjusted R-squared are used to evaluate the performance of the linear regression model. These metrics help assess the goodness of fit and predictive accuracy.
