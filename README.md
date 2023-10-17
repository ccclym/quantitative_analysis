# MAST30034 Project 1 - Quantitative Analysis
- Student Name: Yimeng Liu
- Student ID: 1074206
- Due Date: Friday 13th of August 11:59:00 am (AEST).
- Report Link: 

# Dependencies
- Language: Python 3.8.3 
- Packages / Libraries: pandas, numpy, matplotlib, seaborn, geopandas, sklearn, folium, and warnings

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- External dataset 1 (Weather): https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00094728/detail

# Directory
- `raw_data`: "Download.ipynb" can be used to download the TLC trip data. The raw datasets of weather of 2019 and 2020 can be accessed in this folder.
- `preprocessed_data`: The preprocessed data of yellow taxi can be generated from "2019_preprocessing.ipynb" and "2019_extra_data_weather.ipynb". The preprocessed datasets of weather of 2019 and 2020 can be accessed in this folder. 
- `plots`: Figures are saved in here.
- `code`: 
    - "Download.ipynb" for "Downloading the datasets"
    - "2019_extra_data_weather.ipynb" for "Preprocessing of external weather dataset of 2019"
    - "2020_extra_data_weather.ipynb" for "Preprocessing of external weather dataset of 2020"
    - "2019_preprocessing.ipynb" for "Preprocessing of 2019 yellow taxis"
    - "2020_preprocessing.ipynb" for "Preprocessing of 2020 yellow taxis"
    - "2019_analysis.ipynb" for "Analysis and Visualisation for 2019 yellow taxis".
    - "2019_modelling_process.ipynb" for " Modelling of 2019 yellow taxis and Preidiction of 2020".
- `deprecated`: Nothing

# Other
The order to run the code:
1. Download.ipynb
2. 2019_extra_data_weather.ipynb + 2020_extra_data_weather.ipynb
3. 2019_preprocessing.ipynb + 2020_preprocessing.ipynb
4. 2019_analysis.ipynb
5. 2019_modelling_process.ipynb

