# NYC-Airbnb-Data-Exploration

## About
This workbook provides an analysis of Airbnb listings in New York City with a focus on drilling down by borough. The 5 distinct boroughs of NYC (Manhatten, Brooklyn, Queens, the Bronx, and Staten Island) make for a fascinating case study in exploratory data analysis. Visualizations include:
<ul>
  <li>Top 10 Hosts with the Most Listings in NYC</li>
  <li>Distribution of Listings by Borough</li>
  <li>Mapped Listings by Borough</li>
  <li>Density Map of Listings</li>
  <li>Price Data Box Plots</li>
  <ul>
    <li>All data</li>
    <li>Outlier-adjusted box plot</li>
  </ul>
  <li>Price Heat Map</li>
  <li>Price Distribution by Borough</li>
  <li>Listing Types by Borough</li>
  <li>Popularity vs Price Scatterplot</li>
</ul>

## Tableau
The visuals produced in this workbook have been recreated in Tableau, where they have also been combined into a master dashboard. You can find the links for each visual's Tableau equivalent below the viz in the notebook, and you can find the dashboard link below.


<a href="https://public.tableau.com/views/NYCAirbnbAnalysisDashboard/NYCAirbnbDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank">NYC Airbnb Analysis Tableau Dashboard</a>

The full workbook is also available for download via the <a href="https://github.com/admacpherson/NYC-Airbnb-Data-Exploration/blob/main/NYC%20Aibnb%20Analysis.twbx" target="_blank">```NYC Airbnb Analysis.twbx```</a> file.

## Repository Structure
```Airbnb NYC.ipynb``` - The primary workbook for this repository. Contains analysis and visuals<br>
```Maps.ipynb``` - Maps of NYC's boroughs and neighborhoods created from geojson data<br>

```listings-summary.csv```,
```neighbourhoods.csv```,
```neighbourhoods.geojson``` - Data files used for analysis

```nyc_neighbourhoods_map_bw.png```, ```nyc_neighbourhoods_map_color.png``` - Python-generated maps of NYC used for visualizations based on provided geojson data 


## Libraries
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/>
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"/>
<img src="https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=folium&logoColor=white"/>
<img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white"/>
<img src="https://raw.githubusercontent.com/mwaskom/seaborn/master/doc/_static/logo-wide-lightbg.svg" height="25px"/>


## References
<b>Data: </b>NYC Airbnb Data; Source: <a href="https://insideairbnb.com/get-the-data/">Inside Airbnb</a>. From https://insideairbnb.com/get-the-data/. Licensed under a Creative Commons Attribution 4.0 International License.<br><br>
<b>Analysis: </b> Based on the work of Agratama Arfiano in <i>Towards Data Science</i>. <a href="https://towardsdatascience.com/data-exploration-on-airbnb-singapore-01-40698c54cac3">Data Exploration on Airbnb Singapore: 01</a><br>
