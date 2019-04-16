# ENVIRON872L-EDA_Final-Project
Environmental Data Analytics course final project data on renewable electricity generation trends in the USA at the national and state level.

## Summary
This dataset was prepared for Environmental Data Analytics (ENV 872L) final year project

The dataset contains data from the Energy Information Administration (EIA) on monthly total electric power generation data by State and energy source from 2001 - 2018, 

## Database Information
Data were collected from the Energy Information Administration (EIA) database. The database and more information on it can be found here:https://www.eia.gov/electricity/data.php

To obtain the main dataset for analysis, state-level data was selected from the main page of the dataset. At the state level page, the excel sheet titled Net Generation by State by Type of Producer by Energy Source was selected.
The dataset can be directly downloaded from the site https://www.eia.gov/electricity/data/state/generation_monthly.xlsx 

Each sheet of the excel sheet workbook coresponding to a year of data was saved as a separate CSV labeled `Year_data.csv`. Data sheets for generation on and before 2011 contained more than one year of data therefore the scv was labeled `StartYear_EndYear_data`

The dataset contains the following collums of data;
Year - coresponding to year of electricity generation year
Month - coresponding to month of electricty generation
State - corresponding to 51 state and national electricty generation
Type of producer - corresponding to various types of energy producers
Energy Source - corresponding to various energy sources for electricty genration
Electricty generation - coresponding to electricty generation in MWh by energy source, type of producer, state an and month and year.


## Additional Information and Support
For more information, please contact the data assembler, **Njeri Kara** (rnk10@duke.edu)