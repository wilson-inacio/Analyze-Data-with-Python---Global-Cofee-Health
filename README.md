# Analyze Data with Python
Codecademy Portfolio project

![image](Coffee.png)

#### Overview
This project is part of the Codecademy Portfolio Project "Analyze Data with Python", where I'll be using the Global Coffee Health Dataset, which contains information on coffee consumption, sleep patterns, and health outcomes worldwide.
I hope to answer some questions such as:
 - How are sleep patterns affected by coffee consumption?
 - Is there a link between coffee intake and health risks?
 - Is there a link between drinking coffee and smoking?

Library dependencies used:<br>
Python (3.13.5)<br>
numpy: 2.3.2<br>
pandas: 2.3.2<br>
scipy: 1.16.2<br>
matplotlib: 1.17.0
   
#### Project Objectives
 - Create a project for a data science portfolio using Jupyter Notebook
 - Clean and prepare data using pandas for exploration and analysis
 - Create meaningful visualizations using MatPlotLib
 - Use hypothesis tests to statistically support your findings
 - Report key findings and actionable insights

#### Dataset
The dataset is available on [kaggle](https://www.kaggle.com/datasets/uom190346a/global-coffee-health-dataset/data)
It contains 10000 records about coffee consumption, sleep behaviour, and health outcomes across 20 countries.

#### About the Dataset
The Dataset consists of 16 columns and 10000 rows.
The columns are:
|Column|Type|Description|
|---|---|---|
|ID|Integer|Unique record ID (1–10000)|
|Age|Integer|Age of participant (18–80 years)|
|Gender|Categorical|Male, Female, Other|
|Country|Categorical|Country of residence (20 countries)|
|Coffee_Intake|Float|Daily coffee consumption in cups (0–10)|
|Caffeine_mg|Float|Estimated daily caffeine intake in mg (1 cup ≈ 95 mg)|
|Sleep_Hours|Float|Average hours of sleep per night (3–10 hours)|
|Sleep_Quality|Categorical|Poor, Fair, Good, Excellent (based on sleep hours)|
|BMI|Float|Body Mass Index (15–40)|
|Heart_Rate|Integer|Resting heart rate (50–110 bpm)|
|Stress_Level|Categorical|Low, Medium, High (based on sleep hours and lifestyle)|
|Physical_Activity_Hours|Float|Weekly physical activity (0–15 hours)|
|Health_Issues|Categorical|None, Mild, Moderate, Severe (based on age, BMI, and sleep)|
|Occupation|Categorical|Office, Healthcare, Student, Service, Other|
|Smoking|Boolean|0 = No, 1 = Yes|
|Alcohol_Consumption|Boolean|0 = No, 1 = Yes|
