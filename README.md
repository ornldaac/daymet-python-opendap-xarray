# Toward Analysis Ready Data—Programmatically Discover, Access, and Subset Daymet V4 Data with Python and ArcGIS

**Author:** ORNL DAAC       
**Date:** August 31, 2021       
**Contact for the ORNL DAAC:** support-ornl.gov@earthdata.nasa.gov       

**Keywords:** Daymet, netCDF, Python, OPeNDAP, Web Service, Pydap, Xarray, Geospatial       

## Overview       
These Notebooks were presented in a NASA Earthdata Webinar presented by the ORNL DAAC August 31, 2021.

The [Daymet](https://daymet.ornl.gov/) dataset available at NASA's Oak Ridge National Laboratory Distributed Active Archive Center (ORNL DAAC) provides long-term, continuous, gridded estimates of daily weather and climatology variables across North America. In the webinar, we introduced participants to the recently released Daymet Version 4 Data Collection and provided information on how to access NASA data holdings to programmatically discover and subset Daymet data to a region and time period of interest.

Researchers often require data such as Daymet that are formatted in multidimensional scientific formats but are not familiar with access methods that can allow them to programmatically search and discover as well as subset and download those data based on their own search parameters such as a regional and temporal area-of-interest. Demonstrated using NASA metadata API’s and Python Geospatial programming techniques, we provide examples using Jupyter Notebooks that search, subset, and download Daymet V4 data. We also demonstrate the use of Python Geospatial libraries such as Xarray to create climatological data. Thanks to a collaboration between the NASA DAACs and Esri, we also demonstrate an example ArcGIS Notebook workflow that perform spatial analysis using multidimensional tools with Daymet data in the ArcGIS environment.

<img src="images\JuneAnomaly_saveas.png" width="750" style="display:block;margin-left: auto; margin-right:auto;">

## Webinar
The content in this repository was presented during a NASA Earthdata webinar in August 2021. A link to the webinar recording will be provided when it's available.

## Procedure

Links to Notebooks presented in this webinar:

Jupyter Notebook: [1_daymetv4_discovery_access_subsetting.ipynb](1_daymetv4_discovery_access_subsetting.ipynb)     
Juptyer Notebook: [2_daymetv4_normal_anomaly_conus.ipynb](2_daymetv4_normal_anomaly_conus.ipynb)

ArcGIS Notebook:  [WineSuitability.ipynb](WineSuitability.ipynb)

## Related Tutorials
More tutorials related to ORNL DAAC data and web services can be found at the [ORNL DAAC Learning](https://daac.ornl.gov/resources/learning/) page.
