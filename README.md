# belly-button-challenge

During this project, I used concepts that I have learned to build an interactive dashboard to explore the Belly Button Diversity Dataset (http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels. This folder contains index.html, my default homepage file. This folder also contains samples.json for reference. First, I used the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json. Next, I created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual. I used sample_values as the values for the bar chart, otu_ids as the labels for the bar chart and otu_labels as the hovertext for the chart. Next, I created a bubble chart that displays each sample. I used otu_ids for the x values, sample_values for the y values, sample_values for the marker size, otu_ids for the marker colors, otu_labels for the text values. Next, I displayed the sample metadata, i.e., an individual's demographic information. Then, I displayed each key-value pair from the metadata JSON object somewhere on the page. Next, I updated all the plots when a new sample is selected. Then, I adapted the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

# static/js

This folder contains app.js, my main JavaScript file.

# Deploying index.html to GitHub Pages
Next, I deployed my index.html file to GitHub Pages.

# Final website
https://antara2022.github.io/belly-button-challenge
