# EPA Air Quality Datasets


## Summary
This dataset was prepared for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2019

The dataset contains data from air quality monitoring of PM2.5 and ozone in North Carolina in 2017 and 2018.

## Database Information

Data were collected using the Doanload Daily Data tool (https://www.epa.gov/outdoor-air-quality-data/download-daily-data).
The following selections were made: 
* PM2.5 and Ozone (Pollurant)
* 2018 and 2019 (Year)
* North Carolina (Geographic Area)
* Download CSV (spreadsheet)


csv files were saved as `EPAair_O3_NC2018_raw.csv`, `EPAair_O3_NC2019_raw.csv`, `EPAair_PM25_NC2018_raw.csv`, and `EPAair_PM25_NC2019_raw.csv`. 

Data were accessed 2020-01-03.

## Data Content Information
Information gathered from: https://www.epa.gov/outdoor-air-quality-data/air-data-basic-information and https://aqs.epa.gov/aqsweb/documents/AQS_Format.html

Column names without descriptors are self-explanatory.

Date: month/day/year
Source: AQS (Air Quality System) or AirNow
Site ID: A unique number within the county identifying the site.
POC: “Parameter Occurrence Code” used to distinguish different instruments that measure the same parameter at the same site.
Daily Mean PM2.5 Concentration: numeric value
Daily Max 8-hour Ozone Concentration: numeric value
Units: units for concentration

Daily_AQI_VALUE: Air quality index (range 0-500). Levels: 
0-50: Good (green)
51-100: Moderate (yellow)
101-150: Unhealthy for sensitive groups (orange)
151-200: Unhealthy (red)
201-300: Very unhealthy (purple)
301-500: Hazardous (maroon)

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

## Naming conventions and file formats
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)

## Additional Information and Support
For more information, please contact the data assembler, **Kateri Salk** (kateri.salk@duke.edu)