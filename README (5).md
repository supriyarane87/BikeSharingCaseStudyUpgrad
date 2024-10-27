# BoomBikes-bike-sharing-assignment
## Built a linear regression model for the prediction of demand for shared bikes.

![image](https://user-images.githubusercontent.com/94171996/229351677-e11648e5-47d6-4465-a8a4-86b01c87014d.png)


## Problem Statement:  

A US bike-sharing provider BoomBikes a Mobility Services firm has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

Essentially the company wants :
- To understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19, by creating a linear model.
- To identify the variables affecting their revenues i.e. Which variables are significant in predicting the demand for shared bikes.
- To know the accuracy of the model, i.e. How well those variables describe the bike demands

They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## Business Goal:  

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.  


## <font color = 'red'> Insights: </font>

![image](https://user-images.githubusercontent.com/94171996/229470317-1fa462ee-f089-41e1-9731-0fdf98e9f85c.png)

Detailed attribute info [here](https://raw.githubusercontent.com/shinde-chandrakant/BoomBikes-bike-sharing-assignment/master/Feature%2BAttributes.txt).

- The graph clearly shows the qualitative distributions of the data, now if the model suggests the important predictors, using these graphs we can be more confident about the predictions of the model.
- For the variable season, we can clearly see that the category 3 : Fall, has the highest median, which shows that the demand was high during this season. It is least for 1: spring .
- The year 2019 had a higher count of users as compared to the year 2018
- The bike demand is almost constant throughout the week. there seems no trend in the weekday dataset thus we can leave this variable for the prediction.
- The count of total users is in between 4000 to 6000 (~5500) during clear weather
- From the "Mnth" boxplot we can see that the months are following a trend and could be a good predictor variable. The bookings in the mid-month are above 4000.
- The count is highest in the month of October
- The count of users is less during the holidays
- From the "Workingday" boxplot we can see that maximum bookings happening between 4000 and 6000. There is not much of difference in booking whether its working day or not.  


## <font color = 'red'> Recommendation</font>

- The months - Jan , Jul , Sep , Nov , Dec should be considered by the company as they have a higher demand as compared to other months.
- With an increase in temperature the demand also increases, hence it should keep track of the weather conditions.
- During the Winter season the demand rises, hence it should be well prepared to meet the high demand
