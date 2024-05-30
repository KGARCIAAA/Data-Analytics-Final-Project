The Data Analytics Final Project was part of the Data Analytics course in my graduate program. The point of the course was to provide in depth practice of analytical thinking by using coding languages to solve a problem. The main goal was to use public API's and retrieve data, in order to clean and analyze a relationship. 

For this project, I used TicketMasters' Discovery API to access venue information for the city of New York. I wanted to research the effect venue location has on parking zones in the year 2022. I had to use econometric regression analysis. The model used in this project was a logit model.  

The following steps are provided below to replicate my analysis.

Please run the codebooks in the following order:

1. K_Garcia_Part1-3_JupyterNotebook.ipynb
  This Jupyter notebook contains the code for requesting json from an API, data cleaning and graphs.
  final_dataset.csv is my data file that I used to import into R. 

2. K_Garcia_Part4_RNotebook.Rmd
This R notebook contains the code for the regressions, as well as discussions of the results.

Technical Note: The files taxi_zone_lookup.csv and 2022_Yellow_Taxi_Trip_Data_20240330.csv (too large for github) are the csv files I used in python to build my final dataset.
  I share the 2022 yellow taxi data via google drive.

Thank you!
