# estimate-glacier-surface-melt
Lindsay Summers
Boise State University - Department of Geosciences

## Correspondence
lindsaysummers@u.boisestate.edu

## Description
Code to estimate glacier surface melt using temperature downscaling and a PDD model. 

## Requirements
- a Digital Elevation Model (DEM) of each year
- Daily Automated Weather Station (AWS) temperature data located near the glacier AND/OR ERA5 temperature data from one location near the glacier
- csv containing lon/lat locations to estimate melt (preferably equally spaced points along a centerline from terminus to headwall)
- outputs from glacier-snow-cover-mapping (.nc files)
- (optional) a lapse rate for the glacier (can also use the USGS Benchmark Glacier lapse rate of 0.0065 °C/m)

## Basic Workflow
1. (optional) Yearly_DEM.ipynb
2. downscale_temperatures.ipynb
3. extract_snow_cover_results.ipynb
4. estimate_melt_PDD.ipynb

## Acknowledgements
Thank you to the USGS Benchmark Glacier Project staff for their support and available data. 
