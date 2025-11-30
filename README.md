# Exploring Impacts of Large Scale Fires in Los Angeles, CA
### Author: Kylie Newcomer
#### Date: 11/22/25

## About
In January 2025, the Los Angeles area experience two large scale wildfires that resulted in extreme damage. This project visualizes the aftermath and burn scars of the Palisades and Eaton fires with wavelength reflectance from satellite imagery and geospatial perimeter data. The `xarray` and `geopandas` packages were used to handle the raster and geographic data. 


## Repository structure
```
├── hwk4-task2-false-color-NEWCOMER.ipynb
├── README.md
└── .gitignore
│   ├──data
```

## Data
This notebook contains datasets with the perimeters of the Palisades and Eaton fires and reflectance satellite imagery of the Los Angeles area following the fires. The perimeter data comes from the ArcGIS hub and can be downloaded [here](https://hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about). The other dataset is a `NetDCF` comes from the Microsof Planetary Computer data catalogue and was collected by the Earth Resources Observation and Science (EROS) Center and can be downloaded from this [shared Google Drive](https://drive.google.com/drive/folders/1USqhiMLyN8GE05B8WJmHabviJGnmAsLP?usp=share_link).

## References

Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8–9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 [Dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6 [Accessed Nov. 22 2025]

Los Angeles County Enterprise GIS. (2025). Palisades and Eaton Dissolved Fire Perimeters [Dataset]. Los Angeles County. https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about [Accessed Nov. 22 2025]

### Course Information

- **Course Title:** [EDS 220 - Working with Environmental Datasets](https://bren.ucsb.edu/courses/eds-220)
- **Instructor:** [Carmen Galaz García](https://github.com/carmengg)
- **Co-Instructor:** [Annie Adams](https://github.com/annieradams) 

Complete materials for the homework and additional resources can be found on the [course website](https://meds-eds-220.github.io/MEDS-eds-220-course/).
