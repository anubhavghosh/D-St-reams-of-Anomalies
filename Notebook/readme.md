# D-St-reams-of-Anomalies
Anomaly detection models to determine the anomalies 

## Project Requirements
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the benchmark data set from
https://www.kaggle.com/boltzmannbrain/nab or
https://github.com/numenta/NAB/tree/master/data 
3. Load the one of the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more anomaly detection models to determine the anomalies using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

## Dataset
The source of data is:
https://github.com/numenta/NAB/tree/master/data 
I have used: machine_temperature_system_failure.csv

## Project Delivery steps:
(For more information, please check the jupyter notebook or the report)
1. Get the data: 
About the Data
Temperature sensor data of an internal component of a large, industrial mahcine. The first anomaly is a planned shutdown of the machine. The second anomaly is difficult to detect and directly led to the third anomaly, a catastrophic failure of the machine.
2. Format the Timestamp
3. Plot the data: Lets see how the machine's temperature is varying with time
4. Feature Engineering - Create additional Columns
Hours - Denote hour of day
DayLight - Denote Day and Night
Day of The Week - MTWRFSS
WeekDay - To denote Weekday or Weekend
5. Create Categories - Feature Engineering
WeekEndNight - Denotes weekend night
WeekEndDay - Denotes weekend day
WeekDayNight - Denotes weekday night
WeekDayDay - Denotes weekday day
6. Analyse the temperature all through the 4 categories created above
7. Anomaly Detection - Isolation Forest
8. Visualisation of anomaly with temperature repartition (viz 2)
9. Anomaly Detection - OneClassSVM
10. Visualisation of anomaly - OneClass SVM

