# Impact of Wildfires on Air Quality in California
- `README.md`: The markdown file containing instructions and a project overview.
- `California_Fire_Incidents.csv`: air quality measurement dataset from https://www.kaggle.com/datasets/mexwell/us-air-pollution
- `uspollution_pollution_us_2000_2016`: detailed wildfires in California from 2013 to 2019 found at https://www.kaggle.com/code/docxian/wildfires-geospatial-visualization-and-eda; the dataset is too large to upload to GitHub, but you could get from the Kaggle link above
- `Cali Fire and AQI.ipynb`: the working jupyter notebook file with data loading, data preprocessing, merging, visualization, and analysis. Please see this file for the project details!!
## Project Overview
Wildfires cause devastating damage to California’s land and population every summer. Wildfires also contribute significantly to air pollution through the emissions of nitrogen dioxide (NO2), sulfur dioxide (SO2), ozone (O3), and carbon monoxide (CO). This report seeks to illustrate the relationship between air pollution and wildfires within California by observing how wildfires affect the Air Quality Index (AQI) for those four different chemicals. 
## Project Conclusion
The project analyzes the relationship between air pollution and wildfires in California by examining how wildfire events impact the Air Quality Index for key pollutants. We merged two datasets from Kaggle by date and county to align the air quality data with wildfire occurrences. Our Riverside County EDA analysis and data visualization reveals a prominent correlation between wildfires and the change of pollutant level, specifically O3, by observing huge spikes right after fires occurred. In addition, we do the time series graph to track AQI changes from day to day, which showcases a dramatic fluctuation in the O3 AQI daily change. It is worth noting that O3 AQI rose sharply during fire events but returned to normal shortly after, indicating a short-term but notable impact of wildfires on air quality.
