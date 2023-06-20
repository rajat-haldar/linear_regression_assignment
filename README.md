# Linear_Regression_Assignment_BikeDemand
> Linear Regression and Predictive Analytics performed on the Boombikes bike rental dataset as part of an assignment on Linear Regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Multiple linear regression is performed on the dataset.
- The project is done as part of coursework in the Machine Learning module. 
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc. 
- The Boombikes bike rental dataset is being used. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- All the positive coefficients like temp,season_Summer indicate that an increase in these values will lead to an increase in the value of cnt.
- All the negative coefficients indicate that an increase in these values will lead to a decrease in the value of cnt.
		From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 81% of bike demand.

		Coeffiencients of the variables explains the factors effecting the bike demand

		Based on final model top three features contributing significantly towards explaining the demand are:

		Temperature (0.437655)

		weathersit : Light Snow, Light Rain + Mist & Cloudy (-0.292892)

		year (0.234287)

- Hence, it can be clearly concluded that the variables temperature , season/ weather situation and month are significant in predicting the demand for shared bikes .

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@rajat-haldar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->