# Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

Welcome to the newsroom! For a major metro paper, analyze the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand all the findings.

The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on you to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml). The current data set incldes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."


### D3 Dabbler

![4-scatter](Images/4-scatter.jpg)

* Create a scatter plot between two of the data variables such as `Healthcare vs. Poverty`.

* Create a scatter plot using D3 that represents each state with circle elements. 

* Include state abbreviations in the circles.

* Create and situate axes and labels to the left and bottom of the chart.

* Use `python -m http.server` to run the visualization as data is being read from csv placed in local directory and  `localhost:8000` is used to view the page in browser.

- - -

### Interactive plot with Multiple X-axes and Y-axes

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics
Include more demographics and more risk factors. Place additional labels for the axes in scatter plot and make interactive using click events so that your users can decide which data to display. Animate the transitions for circles' locations as well as the range of the axes.


#### 2. Incorporate d3-tip
 Add tooltips to your circles and display each tooltip with the data that the user has selected. 
 
![8-tooltip](Images/8-tooltip.gif)

