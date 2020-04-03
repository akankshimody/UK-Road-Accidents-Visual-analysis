# UK Road Accidents Exploratory Data Analysis
This project was implemented as part of the Data Analytics Programming course in the MS in Business Analytics Program at UT Austin.
Team Members: Akankshi Mody, Onyekachi Ugo, Rocco Lange and Sachin Balakrishnan

## Motivation
Nearly 1.25 million people die in road crashes each year, on average 3,287 deaths a day. An additional 20-50 million are injured or disabled. Road traffic crashes rank as the 9th leading cause of death and account for 2.2% of all deaths globally.
Road crashes cost USD $518 billion globally, costing individual countries from 1-2% of their annual GDP. Road crashes cost low and middle-income countries USD $65 billion annually, exceeding the total amount received in developmental assistance. Unless action is taken, road traffic injuries are predicted to become the fifth leading cause of death by 2030.<br>

Our team thus decided to quantitatively dive deeper into this issue.

## Goal of the project:
Perform Expolatory Data Analysis on a large dataset of UK traffic accidents to find interesting trends and insights and provide recommendations based on the same.

## Data Used:
The UK government amassed traffic data from 2000 and 2014, recording over 1.6 million accidents in the process and making this one of the most comprehensive traffic data sets out there. It's a huge picture of a country undergoing change. The Dataset can be found [here.](https://www.kaggle.com/daveianhickey/2000-16-traffic-flow-england-scotland-wales)<br><br>

The dataset comprises of comprehensive information regarding location, time, road and light conditions, etc.<br>
Some of our variables are: Accident_Severity, Number_of_Vehicles, Number_of_Casualties, Day_of_Week, Time, Road_Type, Speed_limit, Junction_Control, Pedestrian_Crossing-Human_Control, Pedestrian_Crossing-Physical_Facilities, Light_Conditions, Weather_Conditions, Special_Conditions_at_Site, Urban_or_Rural_Area

## Analysis:

### Effect of Time

**Number of accidents with respect to time of day:**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/Time1.png" alt="Image1" width="500"/><br><br>
Number of accidents are highest during peak hours on weekdays(15:00 to 18:00 and 8:00) when people are commuting to work. <br><br>
**Difference between Weekdays and Weekends:**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/Time2.png" alt="Image1" width="400"/><br><br>
High percentage of accidents during late-night and early morning hours on weekends. This could possibly involve drunk driving incidents.<br><br>
**Trend of accidents vs traffic over time**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/Trend%20over%20time.png" alt="Image1" width="400"/><br><br>
We observed a decrease in the % of accidents over the years even though there has been a very small increase in percentage of traffic over the years. <br><br>

### Effect of Junction Control

**Trends for different types of Junction Controls:**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/JunctionControl1.png" alt="Image1" width="400"/><br><br>
'Give-way or uncontrolled' is six times more probable than Automatic traffic signal. Even adding a basic form of junction control could reduce the number of accidents greatly. <br><br>
**Junction Control with respect to Speed Limit:**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/JunctionControl2.png" alt="Image1" width="400"/><br><br>
Highest number of accidents occur when it’s a giveway and speed limit is 30. Possibly people are overspeeding and hence, higher number of accidents.

### Effect of Predestrian Crossing - Physical Facilities

**Trends for different types of Pedestrian Crossings:**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/PedestrianCrossing1.png" alt="Image1" width="400"/><br><br>
The number of accidents where no crossing facility exists is 15 times as high as than where there is one. However, this could also mean that accidents involving pedestrians are low.

### Effect of Light Conditions

**Trends for different types of Light Conditions:**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/LightConditions1.png" alt="Image1" width="400"/><br><br>
Majority of serious (fatal and severe) accidents happened in the daylight or when streetlights were present and lit. Even though approx. 68% of serious accidents happened in daylight, only 7.5% of those are fatal. 11% of serious accidents that happen in darkness were fatal.<br>
<br>
**Light Conditions Percentages:**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/LightConditions2.png" alt="Image1" width="400"/><br><br>
The percentages stay constant year-to-year. Nearly 70% in daylight each year and more than 20% accidents with street lights on.<br>
<br>
**Percentage of Fatalities by Light Conditions**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/LightConditions3.png" alt="Image1" width="400"/><br><br>
Percentage of crashes in darkness with no streetlights that were fatal are more than double the percentage of fatal crashes in daylight.What makes these crashes in darkness so dangerous? Speed? Road Type? Area?<br>
<br>
**Speed Limit distribution in the dark**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/LightConditions4.png" alt="Image1" width="400"/><br><br>

### Effect of Road Type

**Trends for different types of Roads:**<br>
<img src="https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/images/SingleCarriageway.png" alt="Image1" width="400"/><br><br>
Single carriageway is the most common road with accidents at night and 60 MPH speed limit and most are rural roads with no divider.<br?
<br>

## Recommendations

Based on our analysis, our recommendations are as follows: <br>
1. Increase road safety measures for single carriageway roads to potentially reduce the number of accidents.<br>
2. Set up street lights in rural areas,  and cameras to discourage drivers from overspeeding.<br>
3.Improve Junction Control and Pedestrian Crossing Facilities such as traffic signals and crosswalks.<br><br>

Our detailed presentation can be found [here.](https://github.com/akankshimody/UK-Road-Accidents-Visual-analysis/blob/master/Data%20Analytics%20Project.pdf)
