# Coursera_Capstone

### Introduction:
Car accidents are being a worldwide problem in our days, not only because they represent an economic problem and also, lifes are in game within these kind of events. However, now it is possible to detect all those conditions or factors that can decrease or increase the probability of an accident with the behaviour understanding of all the variables that participate. 

### Business problem:
To help people to confront this problem, within an effort to contribute on the management of these fatal events, an algorythm is going to be developed to predict car accidents and advertise a driver when conditions are wrong enough to represent a risk. 
This can bring some benefits as: saving lives of drivers (our target audience) and decrease costs for goverment (our stakeholders).

### Data
Our source, which belongs to reports from 2004 to 2020, is organized with 37 attributes and 194674 rows.
After some enough data analysis of this CSV file, our target or dependent variable is going to be "SEVERITYCODE", this field or attribute is used to measure the severity of a car accident with a range from 0 to 5. So, all the algorytm development is going to be focused on this variable, with the next values:
<ul>
  <li>0 : Little to no Probability</li>
<li>1 : Very Low Probablility - Chance or Property Damage</li>
<li>2 : Low Probability - Chance of Injury</li>
<li>3 : Mild Probability - Chance of Serious Injury</li>
<li>4 : High Probability - Chance of Fatality</li>
</ul>
By the other side, our independent variables or fields are going to be: WEATHER, ROADCOND, LIGHTCOND, WEATHER_CAT, ROADCOND_CAT and LIGHTCOND_CAT
The information is unbalanced by the difference in samples for every accident type. <br>
1 - 136485<br>
2 - 58188<br>
We can solve this issue by downsampling the majority class to balance data:<br>
1 - 58188<br>
2 - 58188<br>
