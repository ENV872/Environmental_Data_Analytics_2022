# ECOTOX Neonicotinoid Dataset


## Summary
This dataset was prepared for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2020

The dataset contains data from studies on several neonicotinoids and their effects insects.

## Database Information
Data were collected from the U.S. Environmental Protection Agency's ECOTOX Knowledgebase. More information can be found here: https://cfpub.epa.gov/ecotox/help.cfm

Data were collected using the Explore tool on the ECOTOX website (https://cfpub.epa.gov/ecotox/explore.cfm).
From the Explore homepage, the following selections were made: 
* Chemicals (left button)
* Neonicotinoids (check box)
* Explore Data (top right button)
* Uncheck Aquatic (top left button)
* Species Group = Insects/Spiders (left dropdown menu)
* Send Query Filters to Search (top right button)
* Export (top right button)

csv file was saved as `ECOTOX_Neonicotinoids_Insects_raw.csv`. 

Data were accessed 2019-12-13.

## Data Content Information

See the `ECOTOX_CodeAppendix.pdf` metadata file for more information about column headers and codes. 

## Naming conventions and file formats
Files are named according to the following naming convention: `databasename_datatype_details_stage.format`, where: 

**databasename** refers to the database from where the data originated

**datatype** is a description of data 

**details** are additional descriptive details, particularly important for processed data 

**stage**refers to the stage in data management pipelines (e.g., raw, cleaned, or processed)

**format** is a non-proprietary file format (e.g., .csv, .txt)

## Additional Information and Support
For more information, please contact the data assembler, **Kateri Salk** (kateri.salk@duke.edu)