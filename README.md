# LinearRegression CaseStudy
> Built a linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
	-The project aims to predict bike rentals using a linear regression model by analyzing various environmental and seasonal factors. The focus is on identifying the key predictors that influence bike demand and optimizing operational strategies for BoomBikes, a bike-sharing company. The dataset includes features such as temperature, year, weather conditions, and seasons. The goal is to enhance bike rental predictions and support data-driven decision-making.
- What is the background of your project?
	-BoomBikes, a bike-sharing company, seeks to understand the factors driving bike rentals. With data on bike rentals over multiple years, the company aims to leverage this information to optimize operations and marketing strategies. By analyzing historical data, the project identifies patterns and trends that influence bike demand, providing valuable insights for the company's growth and service improvement.
- What is the business probem that your project is trying to solve?
	-The project addresses the business problem of accurately predicting bike demand to improve resource allocation, customer satisfaction, and overall efficiency. By understanding the key factors influencing bike rentals, BoomBikes can tailor marketing campaigns, manage inventory, and implement strategies to boost rentals during peak times and mitigate losses during adverse weather conditions.
- What is the dataset that is being used?
	-The dataset used in this project contains records of bike rentals along with various features:
		Year (yr): Year of the rental data (2018, 2019).
		Holiday: Indicator of whether the day is a holiday.
		Temperature (temp): Temperature in Celsius.
		Wind Speed (windspeed): Wind speed at the time of rental.
		Season: Season of the year (spring, summer, fall, winter).
		Weather: Weather conditions during the rental.
		Month (mnth): Month of the rental.
		Weekday: Day of the week.
		Working Day (workingday): Indicator of whether the day is a working day.
		Count (cnt): Number of bike rentals (target variable).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- our linear regression model (lr_model_7) demonstrates strong predictive power with an R-squared score of 0.804 on the test set, indicating that approximately 80.4% of the variance in bike rentals (cnt) can be explained by the selected features. The adjusted R-squared score of 0.795 confirms that the model remains robust even after adjusting for the number of predictors.

## Key Insights:
	-Temperature (temp) has the highest positive impact on bike rentals, suggesting that warmer weather encourages more bike usage.
	-Year (yr) also shows a positive trend, indicating increasing bike rentals over the years.
	-Winter and September (Sep) have positive coefficients, suggesting higher bike usage during these periods.
	-Light Rain and Windspeed have negative impacts, indicating that adverse weather conditions reduce bike rentals.
	-Holidays have a slight negative impact on bike rentals, possibly due to reduced commuting needs.
	-Seasonal Effects: Summer has a positive impact, while Spring has a slight negative impact on bike rentals.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.2.2
- matplotlib - version 3.8.4
- seaborn - version 0.13.2
- statsmodels - version 0.14.2
- sklearn - version 1.4.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@sharma-kashish] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->