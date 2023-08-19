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
# due to the constraints in the computing availability colab crashed several times 

# Question 1a)
![image](https://github.com/muhilan-a/Motorq-SSN-SNU-2023-DS-Assignment-Anton-Muhilan/assets/121476496/71aa72dd-986a-40a8-a35d-e004b682d799)
# Question 1b)
![image](https://github.com/muhilan-a/Motorq-SSN-SNU-2023-DS-Assignment-Anton-Muhilan/assets/121476496/5a4092cc-584e-4317-b733-381cb89b0336)

# Question 1c)
![image](https://github.com/muhilan-a/Motorq-SSN-SNU-2023-DS-Assignment-Anton-Muhilan/assets/121476496/c9aa411d-8db6-40e2-a93f-e268f5a3d7e3)


# Question 2)
![image](https://github.com/muhilan-a/Motorq-SSN-SNU-2023-DS-Assignment-Anton-Muhilan/assets/121476496/324b66c5-a262-4acb-9c14-b623f9764ce4)

# Question 3)
![image](https://github.com/muhilan-a/Motorq-SSN-SNU-2023-DS-Assignment-Anton-Muhilan/assets/121476496/b58ea9af-edda-4b09-8632-435d7fee74cd)




