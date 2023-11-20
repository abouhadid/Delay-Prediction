# Delay-Prediction
Advanced ML Techniques Final Project @ Dauphine University

-------------------------------------------------------------
**INTRODUCTION:**

In the dynamic landscape of air travel, the challenge of flight delays remains a critical concern, impacting passenger experience and airline operations. This project employs machine learning techniques to develop predictive models for anticipating flight delays in departure and arrival times. By analyzing historical flight data and relevant features, our aim is to enhance the aviation sector's ability to proactively address delays, ultimately improving overall efficiency and passenger satisfaction.

This project aims to predict flight delays during takeoff and landing with minute-level precision.

-------------------------------------------------------------
**DATA:**

The dataset, sourced from Kaggle, originates from the U.S. Department of Transportation and tracks the performance of domestic flights within the United States. This dataset, encompassing flights between 2015 and 2017.

The two target variables we are trying to predict are: 
* *'delay_departure'*: represents the time by which a flight departs later than the originally scheduled departure time. It is calculated as the difference between the actual departure time and the scheduled departure time. A positive value indicates a delay, while a negative value indicates an early departure.
* *'delay_arrival'*: represents the time by which a flight arrives later than the originally scheduled arrival time. It is calculated as the difference between the actual arrival time and the scheduled arrival time. Similar to 'delay_departure', a positive value indicates a delay, while a negative value indicates an early arrival.

-------------------------------------------------------------
**MODELS:**

The models used to tackle this supervised learning task are:
1. Linear Regression: it  is a simple and widely used regression model that establishes a linear relationship between the input features and the target variable. In the context of predicting flight delays, linear regression can be employed to model the relationship between various factors (such as departure time, airline, weather conditions) and the delay in departure or arrival.
2. Random Forest Regressor: it is an ensemble learning method that combines multiple decision trees to make more accurate and robust predictions. Each tree in the forest is trained on a random subset of the data and provides a vote for the final prediction. In the context of flight delays, a random forest can capture non-linear relationships and interactions between features.
3. Gradient Boosting Regressor: another ensemble technique that builds a sequence of weak learners (usually decision trees) in a sequential manner. Each tree corrects the errors of the previous one, leading to a strong predictive model. In the context of flight delays, Gradient Boosting Regressor can effectively capture complex relationships and provide high predictive accuracy.

-------------------------------------------------------------
**RESULTS:**

The accuracies of the models used can be found in the following table:

![Results](https://github.com/abouhadid/Delay-Prediction/blob/main/results.png)
