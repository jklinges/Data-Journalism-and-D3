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
•	assets/dataset in data.csv
•	assets/js holds .eslintrc.json and app.js, the latter of which runs the javascript code that contains the visua lization

• Running:
As it relates to developing the interactive graph visualization, many browsers will fail to load a  csv file unless run on an http server.  I checked the data was being pulled via the console function and pulled data using the "source activate pythondata" command to connect with the local HTTP (host.8000)server.

• An Analysis is included on the webpage and was derived by clicking the x/y labels to change the values of the chart.


