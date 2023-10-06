# Air-Pollution-and-Mental-Health-
This project utilised an air pollution and mental health database which took into account  environmental statistics, self-reported wellbeing statistics, and cognitive test results from people in  Barcelona, Spain. 
Dataset used: [CitieSHealth_BCN_DATA_PanelStudy_20220414.csv](https://github.com/ab4821/Air-Pollution-and-Mental-Health-/files/12834749/CitieSHealth_BCN_DATA_PanelStudy_20220414.csv)

Stress is a self-reported value on a scale of 1-10 in the given dataset. Air pollution can adversely affect the central nervous system, leading to mental health concerns such as stress and anxiety.

Originally, the self-reported stress levels was continuous on the scale of 1 to 10. In order to simplify the classification, the data was split into those with high stress levels above the 
mean and low stress levels below the mean. If the stress level was within 0 – 4.227, they were classified as 0 (low stress), otherwise they were classified as 1 (high stress).
Predicting stress levels based on environmental conditions can provide information useful to inform urban planning and policy decisions aimed at reducing air pollution and creating healthier environments. The aim of this analysis is to predict whether an individual living in Barcelona suffers from high or low stress levels using Support Vector Machines.
