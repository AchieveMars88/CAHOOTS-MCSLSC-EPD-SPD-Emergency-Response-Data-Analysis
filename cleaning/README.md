# Data Cleaning/Preparation Overlook

The following folder utilizes the "data.ipynb" notebook to merge, clean, and reformat the raw data across all agencies and associated weather data. This portion of the project is essential for ensuring the data is properly harmonized and prepared for the visualization/statistical analysis. 

## Parent Folder Contents:

* Eugene_CAD_Data: Contains all the raw (and cleaned) data on CAHOOTS and EPD call services.
  1. Input Data:
  - 2015_CAD.csv (2015 Raw Data)
  - 2016_CAD.csv (2016 Raw Data)
  - 2017_CAD.csv (2017 Raw Data)
  - 2018_CAD.csv (2018 Raw Data)
  - 2019_CAD.csv (2019 Raw Data)
  - 2020_CAD.csv (2020 Raw Data)
  - 2021_CAD.csv (2021 Raw Data)
  - 2022_CAD.csv (2022 Raw Data)
  - 2023_CAD.csv (2023 Raw Data)
  - 2024_CAD.csv (2024 Raw Data)
  - 2025_CAD.csv (2025 Raw Data)
  2. Output Data:
  - CAD_CLEAN.csv
* MCSLC_Data: Contains all the raw (and cleaned) data on MCSLC call services.
  1. Input Data
  - MCSLC.csv
  2. Output Data:
  - MCSLC_CLEAN.csv
* Springfield_SPD_Data: Contains all the raw (and cleaned) data on CAHOOTS and SPD call services.
  1. Input Data:
  - 2015_SPD.csv (2015 Raw Data)
  - 2016_SPD.csv (2016 Raw Data)
  - 2017_SPD.csv (2017 Raw Data)
  - 2018_SPD.csv (2018 Raw Data)
  - 2019_SPD.csv (2019 Raw Data)
  - 2020_SPD.csv (2020 Raw Data)
  - 2021_SPD.csv (2021 Raw Data)
  - 2022_SPD.csv (2022 Raw Data)
  - 2023_SPD.csv (2023 Raw Data)
  - 2024_SPD.csv (2024 Raw Data)
  - 2025_SPD.csv (2025 Raw Data)
  2. Output Data:
  - SPD_CLEAN.csv

  ##### Close_Codes Folder: Adds additional column to SPD dataframe.
  1. Input Data:
  - 2015_key.csv (2015 Raw Data)
  - 2016_key.csv (2016 Raw Data)
  - 2017_key.csv (2017 Raw Data)
  - 2018_key.csv (2018 Raw Data)
  - 2019_key.csv (2019 Raw Data)
  - 2020_key.csv (2020 Raw Data)
  - 2021_key.csv (2021 Raw Data)
  - 2022_key.csv (2022 Raw Data)
  - 2023_key.csv (2023 Raw Data)
  - 2024_key.csv (2024 Raw Data)
  - 2025_key.csv (2025 Raw Data)
  2. Output Data:
  - Key.csv

* Weather_Data Folder: Contains all the raw (and cleaned) data on Eugene/Springfield weather.
  1. Input Data
  - weather_data.csv
  2. Output Data:
  - weather_CLEAN.csv
* data.ipynb: The main notebook used to process/combine all of the raw data.

## Running the Notebook:

1. Save the data as formatted in the repository to a local directory (exclude the cleaned data files).
2. In "data.ipynb", change every line (11 lines) with a file path to your associated file path.
3. Run the notebook. The cleaned data will appear where they're placed in the repository.

## Dependencies:
Using Python base 3.13.5, the following packages are used:

- pandas (dataframe manipulation)
- datetime (date parsing) and regex (value formatting) standard library usages
