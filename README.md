<div align="center">

# NOAA Climate Analysis 2005-2015

[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Domain](https://img.shields.io/badge/Domain-Climate_Science-22c55e?style=for-the-badge)](.)

> A decade of NOAA temperature data - record highs, record lows, 2015 anomalies, and geospatial station maps.

</div>

---

## What This Project Analyses

Using real NOAA weather station data from Ann Arbor, Michigan (2005-2015):

- What were the **record high and low temperatures** for each day of the year?
- Did any day in **2015 break a 10-year record**?
- How are weather stations **geographically distributed**?

---

## Visualisations

| Plot | What It Shows |
|---|---|
| Temperature Range Chart | Daily record highs and lows (2005-2014 baseline) with 2015 overlay |
| Station Map | Interactive HTML map of NOAA monitoring locations |
| Anomaly Scatter | Days where 2015 broke the 10-year record highlighted in colour |

---

## Dataset

```
datasets/
├── temperature.csv   - Daily min/max temps per station, 2005-2015
└── BinSize.csv       - Station metadata and geographic coordinates
```

Source: **NOAA Global Historical Climatology Network (GHCN)**

---

## Tech Stack

```
pandas      - data loading, groupby, pivot operations
numpy       - numerical processing
matplotlib  - multi-layer temperature range plots
folium      - interactive geospatial station map
```

---

## Run Locally

```bash
git clone https://github.com/arunima-anil/NOAA_Climate_Analysis_2005_2015
cd NOAA_Climate_Analysis_2005_2015
pip install pandas numpy matplotlib folium jupyter
jupyter notebook NOAA_Climate_Analysis_2005_2015.ipynb
```

---

<div align="center">Built as part of AI & Data Science portfolio | <a href="https://github.com/arunima-anil">@arunima-anil</a></div>
