# UpGrad: BoomBikes - Bike sharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

> ### Overview:
> This project involve building a multiple linear regression model for prediction of demand of shared bike. and object is find key factors which affect the bike demand.
>
> ### Background:
> Boom Bikes, A U.S.- base bike sharing company has experience in drop in revenue because of pandemic, so company wants to learn a factor which can help them to define strategies.
>
> ### Business Problem:
> The objective of this project is to help Boom Bike to identify the key factor which affect the demands of bike and create suitable strategies to overcome by understanding relation between them.
>
> ### Dataset:
> The dependant variable is count 'cnt' of bike shared, data recorded on day basis. and independent variables are as follow
> - **'yr'** (year)
> - **'workingday'** (if day is working day)
> - **'windspeed'** (wind speed)
> - **'casual'** (if rider is registered or casual rider)
> - **'fall'** (Seasonal Indicator)
> - **'Winter'** (Seasonal Indicator)
> - **'mist'** (Ambience Indicator)


## Conclusions
> Count of shared bikes ('cnt') is based on following equation

> `cnt = 0.0520 + (0.1690 * yr) + (0.2250 * workingday) - (0.0656 * windspeed) + (0.8328 * casual) + (0.0731 * fall) + (0.0948 * winter - (0.0298 * mist)`


## Technologies Used
> - **Python** - Version 3.17
> - **Pandas** - Version 2.1.4
> - **NumPy** - Version 1.26.4
> - **Matplotlib** - Version 3.8.0
> - **Seaborn** - Version 0.13.2
> - **Jupyter Notebook** - Version 7.0.8


## Acknowledgements
> - **Data Source**: The day.csv dataset provided for this analysis from UpGrad.
> - **Educational Resources**: Various online resources and courses that helped in learning EDA, Linear Regression.


## Contact
Created by [@sandip5002] - feel free to contact me!