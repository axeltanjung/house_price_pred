Statistics for Business - House Price Prediction

A.	Introduction & Background

House price prediction is a significant task in the real estate industry, where accurate predictions can help homeowners, buyers, and sellers to make informed decisions. Linear regression is a widely used statistical technique that helps to estimate the relationship between a dependent variable (in this case, house prices) and one or more independent variables (such as the size of the house, location, number of rooms, etc.). In this context, linear regression models can be used to predict the house prices based on the available data.

The housing market is one of the most important sectors of the economy, with a significant impact on the overall financial well-being of individuals and society as a whole. Accurately predicting the housing prices can help various stakeholders, including homebuyers, sellers, investors, and real estate agents, to make informed decisions. The traditional approach to house price prediction involves analyzing various factors such as the size of the property, location, the number of rooms, and other amenities to estimate the price. However, with the advent of big data and machine learning techniques, it has become possible to develop more accurate and reliable predictive models.

B. Dataset
There are 18 feature on dataset House Prediction Price, with 4.600 record as follows:
•	Date		: from May 2nd, 2014 to July 10th, 2014
•	Price		: the price of the house for sale
•	bedrooms	: total number of bedrooms in a house
•	bathrooms	: total number of bathrooms in a house
•	sqft_living	: size of the house in square feet
•	sqft_lot		: size of the land in square feet
•	floors		: number of floors in a house
•	waterfront	: a house bordering water (river, lake, etc)
•	view		: a house with an attractive view
•	condition	: the condition of the building (scale 1-5)
•	sqft_above	: size of housing above basement in square feet
•	sqft_basement	: size of the basement in square feet
•	yr_built		: year the house was built
•	yr_renovated	: year the house was last renovated
•	street		: address of the house
•	city		: city where the house is located
•	statezip		: zip code
•	country		: country

C. Setting Up Problem
1.	Project Goal
To develop a linear regression model that accurately predicts house prices based on various features such as location, square footage, number of bedrooms and bathrooms, and other relevant factors.
Objectives:
•	Collect and clean a large dataset of house prices and related features.
•	Explore the data to identify any correlations and patterns.
•	Choose appropriate features and build a linear regression model using the dataset.
•	Evaluate the model's performance using appropriate metrics such as mean squared error (MSE) and coefficient of determination (R-squared).
•	Fine-tune the model and re-evaluate its performance until a satisfactory level of accuracy is achieved.
•	Use the model to predict the prices of new houses and validate its accuracy using real-world data.
•	Document the project and share the findings with stakeholders, including recommendations for improving the model's accuracy and potential applications for the insights gained.
Deliverables:
•	A clean dataset of house prices and relevant features.
•	A Jupyter notebook or Python script that contains the code used to build and evaluate the linear regression model.
•	A report that summarizes the findings of the project, including the model's accuracy, insights gained, and potential applications.
•	A presentation that highlights the key findings and recommendations for stakeholders.
What we want to know:
Assume we want to make report about the data to inform these:
•	Average, maximum, minimum price of house
•	Which transaction that have the highest price purchased?
•	Distribution of price, sqft_living, sqft_lot, sqft_above, and sqft_basement
•	Association between price and condition
•	Association between price and yr built/yr renovated
•	Association between price and sqft_living, sqft_lot, sqft_above, and sqft_basement
•	Association between price and bedrooms, bathrooms, floors, waterfont, and view
•	What are the most frequently purchased houses?
•	Which city that give highest and lowest price?
We can answer these question by doing exploration in the data

