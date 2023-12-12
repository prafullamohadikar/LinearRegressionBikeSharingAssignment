# Bike Sharing Assignment
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
    A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. 
    A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. To come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- What is the background of your project?
    A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- What is the business probem that your project is trying to solve?
    Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
- What is the dataset that is being used?
    Bike Sharing historic database ok year 2018 and 2019


## Conclusions
- Conclusion 1:
    F-Statistic
    -----------
    Train R-squared: 0.831
    Train Adjusted R-squared: 0.828
    Test R-squared: 0.803
    Test Adjusted R-squared: 0.794
    The model is Good based on the R-squared and Adj. R-squared metrics.
- Conclusion 2:
    Equation of Best-Fit Line
        cnt = 0.1976 + (yr x 0.2339) + (temp x 0.4925) + (windspeed x -0.1497) + (Jul x -0.0513) + (Sep x 0.0732) + (season_spring x -0.0693) + (season_summer x 0.0457) + (season_winter x 0.0805) + (weather_light x -0.2810) + (weather_mist x -0.0799)
- Conclusion 3:
    Top 3 predictor variables on which influence the bike booking:¶
    - Temperature(temp): The bike hire quantity will increase by 0.4925 units for a unit increase of temperature.
    - Year(yr): Every year the bike hire quanitiy will increase by 0.2339 units.
    - weather_light: Every time the weather is Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds the bike hire quantity is reduced by 0.2810 units.
- Conclusion 4:
    Other predictor variables on which influence the bike booking based on impact type and highest correlation:
    - Winter Season (season_winter): In Winter season there is increase of 0.0805 units of bike hire.
    - Month of September(Sep): In September month there is increase of 0.0732 units of bike hire.
    - Summer Season (season_summer): In summer season there is increase of 0.0457 units of bike hire.
    - windspeed: For unit increase in windspeed there is decrease of 0.1497 units in the bike hire quantity.
    - weather_mist: Whenever weather is Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist there is decrease of 0.0799 units in the bike hire quantity.
    - Spring Season (season_spring): In spring season there is decrease of 0.0693 units of bike hire.
    - Month of July (Jul): In July month there is decrease of 0.0513 units of bike hire.


## Technologies Used
- pandas library - version 1.5.3
- numpy - version 1.24.3
- seaborn library - version 0.12.2
- matplotlib library - version 3.7.1
- plotly library - version 5.9.0
- sklearn library - version 1.2.2
- statsmodel library - version 0.13.5


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad's Linear Regression Assignment


## Contact
Created by Prafulla P. Mohadikar [prafulla.mohadikar@gmail.com] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->