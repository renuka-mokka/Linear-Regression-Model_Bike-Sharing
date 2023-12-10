# Modeling the Demand for Shared Bike using Multiple Linear Regression
> We have to model the demand for shared bikes with the available independent variables Using Multiple Linear Regression. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background:
  A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the 
  current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy 
  restores to a healthy state. 
  BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to 
  prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

  
- Business Problem:
  We need to understand the factors on which the demand for these shared bikes depends. Specifically,we want to understand the factors affecting the demand for these shared bikes in the 
  American market. The company wants to know:
   1. Which variables are significant in predicting the demand for shared bikes.
   2. How well those variables describe the bike demands


- Dataset:
  Bike Sharing dataset for year 2018 and 2019 has been given to prepare teh model and predict the demand for future.
  
## Conclusions

Significant variables to predict the demand for shared bikes:

1. temp  - directly related with demand
2. Year (2019) - demand increasing in 2019
3. windspeed  - inversly related with demand
4. weathersit( Clear ) -> has increasing demand , weather situation (Light snow/Light Rain) --> has decreasing demand for bikes
5. holiday - inversly related with demand
6.  Season(Spring)  -  inversly related, season_winter directly related

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook
- Python 
- Libraries used: Scikit-learn, Statsmodel, numpy, pandas, matplotlib, seaborn etc

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@renuka-mokka] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
