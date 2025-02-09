# plane_crashes

## A data analysis, data visualization, and causal inference project

A portfolio project demonstrating ETL skills, EDA, data visualization, regression modeling, and causal inference methods in R. This project aims to explore factors linked to airplane crash fatalities between 1919 and 2022. The main data source under consideration in this project was acquired from [Kaggle](https://www.kaggle.com/datasets/abeperez/historical-plane-crash-data?resource=download), where Kaggle user Abe Caesar Perez had collected a tabular dataset of all historical plane crashes across the world from 1918 to 1922. The primary source of this dataset was the Bureau of Aircraft Accident Archives (B3A). 

### Version history
Original .Rmd draft upload 2025-02-09 <br />
Drafted and revised on RStudio between 2025-01-31 and 2025-01-31

### Key features
 * Data extraction, transformation, and cleaning
 * Data visualization in R using ggplot2 and ggplotly interactive visualizations
 * Summary statistics
 * Hypothesis testing
 * Time series analysis
 * Regression Discontinuity Analysis (RDA) for causal inference

### R libraries used
* ggplot2
* tidyverse
* lubridate
* plotly
* dplyr
* dbplyr
* coin
* rdrobust

### Data sets
* plane_crashes.csv, a 24.4 MB comma-separated value file acquired from [Kaggle](https://www.kaggle.com/datasets/abeperez/historical-plane-crash-data?resource=download) containing over 24000 observations of plane crash incidents worldwide from 1919 to 2022, each with 24 variables (columns) of numeric and string-formatted values.
