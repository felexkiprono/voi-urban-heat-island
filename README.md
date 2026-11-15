# Urban Heat Island Analysis – Voi Town, Kenya

## Project Overview

This project investigates spatial and temporal variations in Land Surface Temperature (LST) across Voi Town, Taita Taveta County, Kenya.

Using Landsat 8 and Landsat 9 satellite imagery, Google Earth Engine and Python, the analysis examines the relationship between surface temperature, vegetation cover and built-up surfaces.

The project uses remote sensing and geospatial analysis techniques to identify areas experiencing relatively higher surface temperatures.

## Objectives

- Analyse seasonal Land Surface Temperature patterns from 2016 to 2026.
- Calculate the Normalized Difference Vegetation Index (NDVI).
- Calculate the Normalized Difference Built-up Index (NDBI).
- Examine relationships between LST, NDVI and NDBI.
- Identify relatively hotter and cooler areas in 2025.
- Produce thematic maps and statistical visualizations.

## Study Area

Voi Town, Taita Taveta County, Kenya.

The current study area is defined using a 5 km buffer around an approximate town-centre coordinate.

## Data Sources

- Landsat 8 Collection 2 Level-2
- Landsat 9 Collection 2 Level-2

## Technologies and Tools

- Google Earth Engine
- Python
- Jupyter Notebook
- geemap
- pandas
- Matplotlib
- Earth Engine Python API

## Methodology

1. Study area definition.
2. Landsat image acquisition.
3. Cloud and shadow masking.
4. Surface reflectance and temperature preprocessing.
5. NDVI, LST and NDBI calculation.
6. Seasonal median composite generation.
7. Statistical and temporal trend analysis.
8. Correlation analysis.
9. Relative heat-class mapping.
10. Thematic map production and export.

## Key Outputs

- Land Surface Temperature map (2025).
- Vegetation Index map (2025).
- Built-up Index map (2025).
- Relative Heat Classification map (2025).
- Seasonal indicator statistics (2016–2026).
- Correlation analysis.

## Limitations

- The analysis uses June–September seasonal observations, not complete calendar-year data.
- Land Surface Temperature is not the same as near-surface air temperature.
- NDVI and NDBI are spectral indicators and do not independently establish land-cover classes.
- Heat classes represent relative temperature percentiles within the study area.
- Correlation does not establish causation.

## Project Purpose

This project demonstrates the application of GIS, remote sensing and data science techniques to urban environmental analysis and sustainable urban planning.

## Author

Geoinformatics and Data Science Portfolio Project