# NOAA_Climate_Analysis_Ann_Arbor_2005_2015

## Overview

This repository contains code and documentation for analyzing climate data. The analysis covers temperature records from 2005-2015, including record highs and lows, visualization of weather stations, and a summary of 2015 temperatures. The dataset includes temperature records and station locations.

## Repository Structure

- `datasets/` - Contains the CSV files:
  - `temperature.csv` - Temperature records with date and temperature values.
  - `binsize.csv` - Weather station locations with IDs, latitude, and longitude.
  
- `NOAA_Climate_Analysis_2005_2015.ipynb` - Jupyter Notebook with detailed analysis and visualizations.

- `ann_arbor_stations_map.html` - Interactive map showing weather stations near Ann Arbor.

## Analysis and Logical Implementation

1. **Temperature Analysis (2005-2014)**:
   - **Objective**: Plot record high and low temperatures by day of the year, with shaded areas representing temperature ranges.
   - **Implementation**: Filtered data for the years 2005-2014, separated high and low temperatures, and used pivot tables to get daily records. Visualized the data with a line graph and shaded the area between record highs and lows.
   
2. **Record Breakers (2015)**:
   - **Objective**: Highlight temperatures from 2015 that exceeded or fell below the 2005-2014 records.
   - **Implementation**: Overlaid scatter plots on the 2005-2014 temperature graph to indicate broken records in 2015. This helps visualize how 2015 temperatures compared to historical records.
   
3. **Leap Days**:
   - **Objective**: Exclude February 29th (leap days) from the analysis to avoid skewing the results.
   - **Implementation**: Filtered out leap days from the dataset to ensure accurate daily comparisons.
   
4. **Plot Enhancements**:
   - **Objective**: Improve readability by adding clear legends, labels, and minimizing chart junk.
   - **Implementation**: Adjusted plot elements to enhance clarity and focus on data. Added legends, axis labels, and a grid with a clean design.
   
5. **Weather Stations Map**:
   - **Objective**: Visualize the locations of weather stations near Ann Arbor.
   - **Implementation**: Used the `folium` library to create an interactive map with markers for each station. This visualization helps in understanding the spatial distribution of weather data collection points.

## Why Additional Modules?

- **Folium**: Chosen for its ability to create interactive maps easily. This module helps in visualizing station locations effectively.

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   
2.Navigate to the Project Directory:
        
        cd repository-name




**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Acknowledgments**
Thanks to the creators of the folium library for interactive mapping.
Data sources and contributors who provided the datasets.


This format will help users follow the necessary steps to set up and run the project, and it includes license and acknowledgment sections for proper attribution.


## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/repository-name.git
