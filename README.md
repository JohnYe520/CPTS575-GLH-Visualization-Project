# CPTS575-GLH-Visualization-Project

This repository is for Minzhang Li and Tianhao Ye's CPTS 475/575 Project. 

Our project topic is Google Location History. We are Team 46.

## Usage and Our Idea

After the datasets are downloaded from Google Drive, please place the dataset for each person in folder **FD0X** (X can be 1, 2, 3, ...).

We handle each dataset as 3 parts: 

- **Records.json**
- Activity Segment Data from **Year_Month.json** (e.g., 2019_DECEMBER.json)
- Places Visit Data from **Year_Month.json**

We wrote codes in 4 .rmd files to handle the 3 parts, 1 for Records.json, 1 for Activity Segment Data, and 2 for Places Visit Data.

- Records.json: Minzhang Li handled it in **HandleRecords.Rmd**, which should be placed in the same location as folders **FD0X**. Please follow the instructions in the file to use it. We convert Records.json to .csv file, clean the data, do the visualization and try exploratory analysis.
- Activity Segment Data: Minzhang Li handled the Year_Month.json files in **ActivitySegmentData_MonthData_All_In_One.Rmd**, which should also be placed in the same location as folders **FD0X**.. Please follow the instructions in the file to use it. We convert Year_Month.json files to .csv file, clean the data, do the visualization and try exploratory analysis.
- Places Visit Data:
  - Tianhao Ye completed this part.
  - The below 2 .rmd files should be placed in the same directory with place_visit_month folder.
  - **merge.rmd**: Contains code for merging csv files from each month of the year into one csv file for each corresponding year. It also contains code for combining each user's csv files seperately.
  - **place_visit_visualization.Rmd**: Contaions code for building Shiny app to create visualizations for the place visited datasets.

All the converted CSV files are stored in Google Drive, and we post the link in the appendix part of our final report.
