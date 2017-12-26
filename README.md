# udacity_data_visualization
The repository for my final submission in Udacity's Data Analyst Nanodegree.

# Summary

**Dataset:**
Baseball Data

**Reasoning:**		
I want to explore if there is any correlation between home runs, batting averages and the handedness, weight or height of a player.

**Data Story:**
The reader of the visualization which will be a viewer-driven narrative. The reader sees a scatterplot which shows the correlation between height and batting average. Through interactive buttons, the reader can choose also between other factors like weight and home runs.

# Design
First of all, I looked at the data available and decided that the dimensions available are continuous variables like height, weight, No. of Home Runs and the Batting Average. I wanted to compare height and weight against the performance of the player. Furthermore, I was interested if the handedness played a role. The continuous variables weight and height got displayed in the x-axis, the performance as a function of weight and height on the y-axis. The handedness, as a categorical variable, got colored.

The viewer-driven narrative is able to decide if he wants have the height or weight displayed against home runs or average batting score, as interactive buttons are added.

Lastly, the viewer can mouse-over specific data points and get more detailed information about the name and the specific score of each variable. In summary, the viewer should be possible to detect patterns based on the available visualization and further information.

# Feedback
**Feedback 1. Person:**
* Add instructions to start a python server at README.me so the reader is able to understand how to render the visualization
* Add correlation line to better support the findings of the viewer
* Add R-Square calculation information to give the viewer a concrete number

**Feedback 2. Person:**
* Add correlation line to better support the findings of the viewer
* Add separate the correlation for handedness of the player

**Feedback 3. Person:**
* Give the reader the option to separate by handedness via buttons

# Ressources
* Scatterplot - https://bl.ocks.org/mbostock/3887118
* Simple Scatterplot - https://stackoverflow.com/questions/10440646/a-simple-scatterplot-example-in-d3-js
* mouseover-function - http://bl.ocks.org/d3noob/a22c42db65eb00d4e369
