# udacity_data_visualization
The repository for my final submission in Udacity's Data Analyst Nanodegree.

# Intructions to start

1. To work on your data visualization, you will need to start a local server on your computer. To start a local web server, you will need to have Python 2.7.8 or higher installed on your machine.

2. Once you have Python installed, you can start a local web server and view your data visualization. Remember, you must start your web server in the top level directory to serve all code and data files. If you do not use this folder as the root directory for the web server, be aware that you will need to change the file paths.

# Summary

**Dataset:**
Baseball Data

**Reasoning:**		
I want to explore if there is any correlation between home runs, batting averages and the handedness, weight or height of a player.

**Data Story:**
The reader of the visualization which will be a viewer-driven narrative. The reader sees a scatterplot which shows the correlation between height and batting average. Through interactive buttons, the reader can choose also between other factors like weight and home runs.

# Design

**Initial design:**
First of all, I looked at the data available and decided that the dimensions available are continuous variables like height, weight, No. of Home Runs and the Batting Average. I wanted to compare height and weight against the performance of the player. Furthermore, I was interested if the handedness played a role. The continuous variables weight and height got displayed in the x-axis, the performance as a function of weight and height on the y-axis. The handedness, as a categorical variable, got colored.

The viewer-driven narrative is able to decide if he wants have the height or weight displayed against home runs or average batting score, as interactive buttons are added.

Lastly, the viewer can mouse-over specific data points and get more detailed information about the name and the specific score of each variable. In summary, the viewer should be possible to detect patterns based on the available visualization and further information.

**First Feedback Iteration:**
1. I included correlations in the vizualization to support the reader in the  discovery process of the data.

# Feedback
**Feedback 1. Person:**
* Add instructions to start a python server at README.me so the reader is able to understand how to render the visualization (included in final_index.html)
* Add correlation line to better support the findings of the viewer (included in final_index.html)
* Add R-Square calculation information to give the viewer a concrete number (included in final_index.html)

**Feedback 2. Person:**
* Add correlation line to better support the findings of the viewer (included in final_index.html)
* Add separate the correlation for handedness of the player (not included in the dataset)

**Feedback 3. Person:**
* Give the reader the option to separate by handedness via buttons (not included in the dataset)

**Reasoning:** A regression line got included, which updates automatically if the viewer switches the visualization. Moreover, if you mouse-over the visualization you can see the Pearson-correlation for the specific dimensions. The separation of the handedness was not included, as the results wouldn't differ significantly from the findings of the existing visualization.

# Ressources
* Scatterplot - https://bl.ocks.org/mbostock/3887118
* Simple Scatterplot - https://stackoverflow.com/questions/10440646/a-simple-scatterplot-example-in-d3-js
* mouseover-function - http://bl.ocks.org/d3noob/a22c42db65eb00d4e369
* regression-line - https://bl.ocks.org/nanu146/de5bd30782dfe18fa5efa0d8d299abce
* pearsonCorrelation - https://gist.github.com/matt-west/6500993
