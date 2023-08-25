## Overview

A new aviation company is looking to purchase airplanes which they can operate for commercial and private enterprises. Our goal was to distinguish which airplanes would be the least risk for this new aviation company. 

Included in their aviation data set was information relating to a series of aviation enterprises with detailed explanations about flight locations, design specifications, and crash reports, along with fatality rates for those companies. Through all of that information our team was able to distinguish certain parameters for which best airplanes to invest in.

## Business Understanding

Our biggest deciding factor behind our analysis was selecting a plane that exhibited signs of safety and reliability, while also revealing enough data to confirm that it was indeed safe.

The stakeholders wanted to look at airplanes for both commercial and personal travel and assess which kind of travel was safer. We also looked at the data on destruction of planes and fatality rates and took into account what manufacturers were producing the planes which had the highest and lowest fatality rates and which planes had the highest and lowest instances of destruction.

Another important factor that we looked into was where are the safest and least safe locations for flying. We distinguished areas in both the eastern and western hemisphere.

## Data Understanding and Analysis

The data that was given to our team contained a large amount of information, which contained detailed descriptions of the make, model, and manufacturing of each plane. Our data team decided to focus on airlines that contained a large enough amount of information on individual flights, for reliability purposes. Technological advancements have been implemented by the FAA and the most recent improvement came with the digitization and implementation of anti-collision and terrain warning sensors used by Air Traffic Control (ATC) in 1980, therefore we only took into account data past that date.

The scatterplot below compares Average Total Passengers to Average Fatality Rate. We see a cluster of orange data points towards the low end of either axis. If you were to mouse over them in Tableau, you would see that they are planes with reciprocating engines. This plot tells us that reciprocating engines are associated with the lowerst average fatality rate of the various engine types present in the data.

![scatter.png](https://github.com/jacobserfaty/phase-1-aviation-data/blob/master/Images/bar.png)

The bar chart below compares the Make of each flight and the Average Fatality Rate. Since the chart is in ascending order of the fatality rates, the lower the better as far as safety goes. Boeing is associated with the lowest average fatality rate. The shading of the bars indicate the level of overall destruction severity seen within these makes.

The combination of higher destruction severity with a lower fatality rate, suggest that the design of the plane by that particular make is safer and more durable.

![bar.png](https://github.com/jacobserfaty/phase-1-aviation-data/blob/master/Images/bar.png)

The map below shows the average level of damage aircrafts sustained by country. Flights originating from the United States on average sustain minor damage, while other countries with a sufficient amount of data list more severe levels of damage. The intensity of the color in each country indicate higher fatality rates.

In other areas of the world places such as Brazil are least safe to fly from, as well as Canada, Mexico, and France. Other areas which are safest to fly from are many of the Scandinavian countries and countries within Oceania.

![map.png](https://github.com/jacobserfaty/phase-1-aviation-data/blob/master/Images/map.png)

Two Weather protocols for flight controllers are IMC (Instrument Meteorological Conditions) and VMC (Visual Meteorological Conditions). Fatality rates rise significantly under IMC conditions Personal flights seem to be the only airplanes that fly under IMC conditions

![weather.png](https://github.com/jacobserfaty/phase-1-aviation-data/blob/master/Images/weather.png)

## Conclusion

The first visualization included pointed us in the direction of planes with a reciprocating engine. The second visualization let us know that Boeing was going to be the safest make to recommend. Finally, the third visualization confirms the second point. Based on our analysis it would seem that the best recommendations for Makes to invest in would be Boeing, Stinson, Aviat, Maule, and Taylorcraft. The best models to invest in would be planes that use reciprocating engines. The safest locations to travel from are the United States, Scandinavia, and Oceania.
 


```python

```
