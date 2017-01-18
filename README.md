Summary:

	I chose to create a visualization using a dataset on baseball statistics. The data tracks a players name, handedness (right, left, or both handed), height, weight, batting average, and home runs. The visualization helps to show that players with weights around average weight scored the most amount of home runs.

Design:

	The chart's x axis tracks weight in pounds, and the y axis tracks home run count. The size of each dot is relative to the players batting average, where a player with a higher batting average will have a larger dot. A scatterplot was chosen as it was found to show the spread of data most effectively. The data is color coded based on handedness and can be filtered using the interactive legend. 

Feedback:

	The feedback I received on my original chart focused on three main suggestions:

		1) The need for more interactivity
		2) A reference line or some other visual showing trend
		3) Improvements to stylistic elements in the code and css

	I was able to improve interactivity by adding buttons to the chart's legend, enabling a user to filter the data based on a players handedness. In addition, a tooltip appears when hovering over each dot, revealing the player's name and additional statistics. 

	In addition, I was able to add a reference line to the chart where the average players weight occurs. This is at 187 pounds.

	Improvements in stylistic elements were accomplished by ensuring uniformity in spacing throughout the code. 

Resources:

	1) https://github.com/PMSI-AlignAlytics/dimple/wiki
	2) http://dimplejs.org/examples_index.html
	3) http://dimplejs.org/advanced_examples_index.html
	4) https://bl.ocks.org/mbostock/3887118
	5) http://christopheviau.com/d3list/gallery.html