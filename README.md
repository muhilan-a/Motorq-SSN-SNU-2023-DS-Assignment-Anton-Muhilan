# Motorq-SSN-SNU-2023-DS-Assignment-Anton-Muhilan
# Telemetry Data and Ignition Events Dataset
This dataset contains telemetry data and ignition events collected from a fleet of vehicles. The dataset aims to provide insights into vehicle behavior,
including speed, battery level, and ignition status. It also includes artificial ignition off events for analysis purposes.


# Data Analysis Goals
Analyze vehicle speed, battery level, and ignition status trends over time.
Identify charging events and battery level behavior before and after charging.
Investigate ignition ON and OFF patterns and their correlations with other variable

 I started by preprocessing the given data by changing the timestamp and doing data visualisation to find the anamolies
 in the data

 since the data is too big there were many null values espeacially in the telemetry datset
1) So to reduce inaccuracies i dropped the rows whose rows showed null in more than 4 columns
2) This helped us in reducing data redundancy and inaccuracy
3) I also noticed that some values in the ev batteries where more than 100 percentage ,those rows where removed .
