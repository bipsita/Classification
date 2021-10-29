# Vision Zero: Let's Eliminate Traffic Deaths

#### Abstract

Through Vision Zero, the authorities take responsibility for fatal crashes, knowing that they are preventable, and implementing policies and measures to prevent them. In this project, a logistic regression model is trained on data from the 2016 Persons table in National Highway Traffic Safety Administration's Fatalities data, available in BigQuery public data. The model identifies lack of wearing seatbelts, crashes in which motorcycles were involved, and not being an occupant of the vehicle as the top features characterizing fatal crashes. It indicates that enforcement and increase in safety measures for motorcyclists and other vulnerable road users would help prevent fatalities and severe injuries in road crashes.

#### Design

The aim of the project is to build an interpretable model to identify key features that characterize fatal crashes. 

#### Data

BigQuery public data is used of traffic fatalities in the US in 2016. The data contains 86,000 rows and 91 columns. From these. 10 key features were identified by a combination of EDA and the feature importance of a RandomForestClassifier. 

#### Algorithms

The target was binary with the positive class being fatalities or severe injuries. The final ten features selected were age as the only continuous variable, gender (Male), person type (Pedestrian), road category, land use (urban), day of the week, season, time of the day, vehicle make, vehicle body type, and state as the categorical ones. A logistic regression model was trained on these features.  

#### Tools

Pandas and Numpy were used for data cleaning; ScikitLearn and StatsModel were used for training models; Seaborn and Matplotlib were used for visualization. 

#### Communication

In addition to the slides presented, the project will be posted on my Github. 

