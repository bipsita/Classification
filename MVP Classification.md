# MVP: NHTSA Traffic Fatalities Data 2016 (Person table)

The objective of the project is to predict the probability of a fatality (target: fatal or serious injury/minor injury or no apparent injury). The features selected are age, gender, role of person (vehicle occupant, pedestrian etc.), make of vehicle, body type of vehicle, day of week, season, surrounding (urban/rural), type of street (arterial, local, collector), state. 

The initial model is a logistic regression model with age and male dummy as the features. The fit score is 0.55. 

After including the other features, I would like to use the Lasso model to narrow down the number of features. While the aim is to build an interpretive model for use in policy making, I would like to try the random forest model to record the improvement in accuracy.  