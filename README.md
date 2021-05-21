# TeamOne-MSc-Project
Msc-Group-Project
The repository is for MSc Group Project for MSc Student at the University of Bradford.

- Jesutofunmi Ibrahim
- Yahya Hussain
- Bilal Khan
- Gideon Gideon
- Amjad Ali


The Projects looks at identifying highly congested traffic zones within the city of Chicago and finding possible correlation with the air quality monitors in proximity. Machine learning algorithms are implemented on the data in two phases Phase one

The algorithms are implemented on data extract from 2018 with 4 idenfied zones in the air quality index
traffic congestion zones around the city modelled in tableau
Phase two

fine tuning selected algorithm to implement on live data accessed from APIs
Modelling the traffic data and air quality concetration through a live dashboard
The repositiory has the following folders

the Python codes with extensions .ipynb that can be executed from python ide
tableau workbook with extension .twb that is implemented in Tableau deskotp 2020.4.0
R studio with .RData that has been implemented in Rstudio
the data used in this analysis is found on the following websites Air qaulity data https://www.epa.gov/outdoor-air-quality-data/download-daily-data

traffic congestion data https://data.cityofchicago.org/Transportation/Chicago-Traffic-Tracker-Congestion-Estimates-by-Se/n4j6-wkkf

Executing the codes
Data Cleaning 
Traffic Data
Historical traffic data can be downloaded from the traffic congestion website, the air quality index data is located in the data folder of this repository 
- Load the python file in the feature extraction folder 
- perform feature extraction on the air quality data 
- perform data cleaning on the PM2.5 or AQI2014-2020 datset


Prophet 
- The Traffic data can be downloaded from the traffic Congestion site
- The air quality data used is PM2.5 found in the data folder of this repository
- execute the script in R studio and make sure all the libraries have been installed 
(Use Prophet model to identify the trends in traffic flow)
A step by step guide is also included in the Prophet Model Analysis document 

ARIMA Model and SVC
- load the Arima model python code loacted in the ARIMA folder with data from the data folder 
- load the SVC model in python IDE using the python code in SVC folder and data from the data folder
