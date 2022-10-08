# DatafestAfrica Final Datathon
 ## Abstract
Performing basic analysis and creating an interactive dashboard on the Zentel Network service center data.

## Wrangling
This was done using Microsoft Excel, Python and Power Query.

### Microsoft Excel
Used to convert the Service Data page from .xlxs to .csv for importation into jupyter notebooks using pandas
used to add the "Unknown" Fault key to the fault type table.

### Python
Used for assessing the dataset and checking for errors
Used to replace the spaces in the column headers with underscores to make cleaning and analysis easier
used to convert the ticket_open_time, ticket_resp_time and issue_res_time from object(string) to datetime
used to replace the null values in the Fault type column to "Unknown"

### Power Query
Removed unwanted Row IDs
Added a calender table
Created a new table for DAX measures
Created a new table "resolution duration" which consists of the time difference between ticket response time and issue resolution time
Created a table "response duration" which consists of the difference between the ticket open time and ticket response time

## Data Modelling
This was entirely done using PowerBI

## Exploratory Data Analysis
This was primarily done with PowerBI

## Visualization
PowerBI was utilized to create an interactive dashboard.
