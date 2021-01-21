Data Journalism and D3
http://i.giphy.com/v2xIous7mnEYg.gif

In this Data Driven Document (D3), I have explored certain associations between demographics and behavioral risk factors using survey data collected from the American Community Survey (ACS) and the Behavioral Risk Factor Surveillance System (BRFSS) during the year 2014. Each marker represents an individual state in The USA.

This document was created using D3, the JavaScript library for visualizing data with HTML, SVG, and CSS.

Description:
This project uses D3.js to visualize some state-level data about population health based on 2014 U.S. Census data. It similates an on-line newpaper article with an interactive visualization. Three risk factors (obesity, smoking, and uninsurance rates) are plotted against three perhaps underlying factors (income, poverty rate, and age).

File Structure:

•	The base webpage template is index.html.
•	The assets folder contains everything else of relevance
•	assets/css holds two styling files, styles.css and d3style.css
•	assets/data holds the data set in data.csv
•	assets/js holds .eslintrc.json and app.js, the latter of which runs the javascript code that contains the visualization

Running:
Due to loading in a csv file, many browsers will fail to load this unless run on an http server. 
Analysis:
• Click x/y labels to change the values of the chart.

• An Analysis is included on the webpage.
