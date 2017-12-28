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

**Findings:**

**Comparison of height and batting average:**
There is a weak correlation between the batting average and the height, which indicates that smaller players reach on average a higher batting average. As the correlation is not significant, just cannot be interpreted as a causation. The highest batting averages by small players are achieved by right-handers, while the overall highest batting averages are achieved by left-handers of any size.


**Comparison of height and batting average:**
Same as for height, the heavier the players are the lower is the batting average. Also, this correlation is very low and cannot indicate a causation. Nevertheless, all players of any height have a batting average between 0.2 and 0.3. Below that is a significant amount of right-handers.

**Comparison Homeruns and Weight:**
There is a weak, but an almost significant correlation between weight and home runs. The heavier the players are the more home runs they scored in their career. The highest home runs are achieved as well as by left- and right handers of any weight.

**Comparison Homeruns and Height:**
There is also a positive relationship between home runs and height. The taller a player is, the more home runs he scored in his career. The maximum amount of homers are scored by left- and right handers of any height.

**Data Story:**
The reader of the visualization which will be a viewer-driven narrative. The reader sees a scatterplot which shows the correlation between height and batting average. Through interactive buttons, the reader can choose also between other factors like weight and home runs.

# Design

**Initial design:**
First of all, I looked at the data available and decided that the dimensions available are continuous variables like height, weight, No. of Home Runs and the Batting Average. I wanted to compare height and weight against the performance of the player. Furthermore, I was interested if the handedness played a role. The continuous variables weight and height got displayed in the x-axis, the performance as a function of weight and height on the y-axis. The handedness, as a categorical variable, got colored.

The viewer-driven narrative is able to decide if he wants have the height or weight displayed against home runs or average batting score, as interactive buttons are added.

Lastly, the viewer can mouse-over specific data points and get more detailed information about the name and the specific score of each variable. In summary, the viewer should be possible to detect patterns based on the available visualization and further information.

**First Feedback Iteration:**
1. I included a correlation line in the visualization to support the reader in the discovery process of the data.
2. I included further instructions in the README.me file to help the viewer.
3. I changed the update function so that the correlation will be updated by selected dimensions.
4. I calculated the Pearson-correlation and let it update if the viewer changes the dimensions of the visualization.
5. I included a mouse-over function to show the Pearson-correlation to the reader.

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
* Math.pow() documentation - https://www.w3schools.com/jsref/jsref_pow.asp
* Square elements of array - https://gist.github.com/Atlas7/b2d2e211da7cd45d4213a9bb7f4ed522
* calculate regression - http://www.statisticshowto.com/probability-and-statistics/regression-analysis/find-a-linear-regression-equation/
