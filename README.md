# ENV 872 Final Project Dataset

## Summary
This dataset was prepared for the final project for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2019.

The dataset contains data from air quality monitoring of PM2.5 in California from 1999 to 2018.

The dataset also contains county boundary in California.

## Database Information
Data were collected using the Doanload Daily Data tool (https://www.epa.gov/outdoor-air-quality-data/download-daily-data).
The following selections were made: 
* PM2.5 (Pollutant)
* 1999 to 2018 (Year)
* California (Geographic Area)
* Download CSV (spreadsheet)

csv files were saved in the following format `pm_year_ca.csv` and kept in the 'Raw' folder. 

County boundary data were collected using the California government open data portal (https://data.ca.gov/dataset/ca-geographic-boundaries/resource/091ff50d-bb24-4537-a974-2ce89c6e8663). 

The data were saved as shapefile and kept in the 'SpatialData' folder.

Data were accessed 2019-04-08.

## Data Content Information
Information gathered from: https://www.epa.gov/outdoor-air-quality-data/air-data-basic-information and https://aqs.epa.gov/aqsweb/documents/AQS_Format.html

Date: month/day/year
Source: AQS (Air Quality System) or AirNow
Site ID: A unique number within the county identifying the site.
Daily Mean PM2.5 Concentration: numeric value
Units: units for concentration

Column names without descriptors are self-explanatory.
Site Name
DAILY_OBS_COUNT: number of observations per day
PERCENT_COMPLETE
AQS_PARAMETER_CODE
AQS_PARAMETER_DESC
CBSA_CODE
CBSA_NAME
STATE_CODE
STATE
COUNTY_CODE
COUNTY
SITE_LATITUDE
SITE_LONGITUDE

## Additional Information and Support
For more information, please contact the data assembler, **Connie Xiong** (wanchen.xiong@duke.edu)