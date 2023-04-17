# Data-Visualization-U3
This repository is dedicated to the final project for Data Visualization class at CentraleSupelec. 

### Project Description
The CO2 emission has increased significantly in the past 300 years, primarily as the result of industrialization. However, with the implementation of United Nations Climate Change Conference (COP) and people's awareness of sustainable lifestyle, there has been new trends in the CO2 emission levels around the world. Therefore, our team decided to analyze the worldwide CO2 emission throughout time by creating a visualization tool in Python. 

### Data
The dataset of research can be referred to on this link: https://github.com/owid/co2-data/blob/master/owid-co2-codebook.csv
Here we focused mainly on 2 target variables: CO2 (annual total production-based emissions of carbon dioxide (CO₂), excluding land-use change, measured in million tonnes) and on CO2_per_capita (annual total production-based emissions of carbon dioxide (CO₂), excluding land-use change, measured in tonnes per person).The variables were explored on various scope levels (country, continent, etc.). 

### Output
We created 4 charts: a line plot for CO2 emission and CO2 emission per capita data for each year, a geographical heatmap showing each country's emission level for each year, a scatterplot of each continent's total emission during 2002 and 2021 and a bar chart of 2021's world population per continent. The first two charts have the feature of slider and dropdown widgets where you can interact with the graph by changing the year scope. The last two views are connected to each other by an interactive function where you can click on the continent's population data to visulize only the CO2 emission trends for that specific continent. 
The four charts can be viewed synthetically in a python panel. 

### Web Application
If you want to utilize the visualization tool independently, please visit the web application realized through hugging face: https://huggingface.co/spaces/asdf654/panel_dv
