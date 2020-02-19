# GeoResource Collection
 A collection of useful data or tools in learning of earth science ;) [![HitCount](http://hits.dwyl.io/fsn1995/GeoResource-Collection.svg)](http://hits.dwyl.io/fsn1995/GeoResource-Collection)
# Open Access Data
## 1. Climate Data 
### 1.1 weather station records
- [Climate Data Online NOAA](https://www.ncdc.noaa.gov/cdo-web/datasets) - An online portal that contains the collection of meteorological data from global weather stations.
- [SMHI](https://www.smhi.se/klimatdata/meteorologi/) - Swedish Meteorological and Hydrological Institute provides detailed long-term monitoring data.
- [Tarfala Research Station](https://su.figshare.com/TRS)
    * Meteorological record of weather station at Tarfala Research Station, Stockholm University. Mass balance record of Storglaciären can be found at [Bolin Center for Climate Research](https://bolin.su.se/data/tarfala/tarfalaglaciaren.php).

### 1.2 Assimulated Global Climatic data
- [GLDAS NOAH](https://disc.gsfc.nasa.gov/datasets?page=1&project=GLDAS)
    * Global Land Data Assimilation System ingests satellite and ground-based observational data products (0.25 arc degree). 
    * The data can be downloaded mannually or automatically by a [tool](https://github.com/fsn1995/Fun-with-Python-for-Geodata/blob/master/EarthdataDownload.py). 
    * Google Earth Engine also has access to the data. I have done a [practice](https://github.com/fsn1995/Fun-with-Google-Earth-Engine/blob/master/Noah.js) to convert the units and display the global monthly/annual precipitation and temperature. 
- [Sea Surface Temperature](https://podaac.jpl.nasa.gov/dataset/REYNOLDS_NCDC_L4_SST_HIST_RECON_MONTHLY_V3B_NETCDF)
    * Smith and Reynolds NCDC Level 4 Historical Reconstructed Sae Surface Temperature Monthly Data. 
- [WorldClim](https://www.worldclim.org/)
    * Provides climatic variables at a global scale with a high spatial resolution (1km^2).
    * Also includes data of future spectrums by different earth system models and historical climatic features by different models and records.
    * This data is available in Google Earth Engine.

## 2. Other
- Hurrican path
    * [International Best Track Archive for Climate Stewardship (IBTrACS)](https://www.ncdc.noaa.gov/ibtracs/index.php?name=ib-v4-access) gives us hurrican tracks in csv/netcdf/shapefile formats. 
    * [National Hurricane Center](https://www.nhc.noaa.gov/gis/)
- Humanitarian Data
    * [ACLED](https://www.acleddata.com/)The Armed Conflict Location & Event Data Project 
    * [HDX](https://data.humdata.org/) Humanitarian Data Exchange

# Useful tools/software
### 3.1 Google Earth Engine
- [earthengine-py-notebooks](https://github.com/giswqs/earthengine-py-notebooks)
- [gee-community](https://github.com/gee-community)
- [fun with gee](https://github.com/fsn1995/Fun-with-Google-Earth-Engine) - Personal practice templates :)

### 3.2 Python
- [rasterio](https://rasterio.readthedocs.io/en/latest/) - library for processing raster data
- [geopandas](http://geopandas.org/) - library for vector data
- [Introduction to Python GIS](https://automating-gis-processes.github.io/CSC18/index.html) - quick start course
- [Fun with Python for Geodata](https://github.com/fsn1995/Fun-with-Python-for-Geodata) - personal practice, under development :)
    
### 3.3 R library
- SPEI
    * Standard Precipitation and Evaportranspiration Index: [point scale](https://github.com/sbegueria/SPEI), [spatial scale](https://github.com/sbegueria/SPEIbase). https://spei.csic.es/ A useful and reliable drought index.

### 3.4 Matlab
- [Efficient subpixel image registration by cross-correlation](https://www.mathworks.com/matlabcentral/mlc-downloads/downloads/submissions/18401/versions/4/previews/html/efficient_subpixel_registration.html)
    * A powerful  tool to achieve high precision sub-pixel image registration. :+1:
- [ImGRAFT](https://github.com/grinsted/ImGRAFT)
    * An Image Georectification and Feature Tracking toolbox. This is where I started the glacier surge project. Personally I learned a lot from it. :mountain_snow:

### 3.5 ENVI/IDL
- [COSI-CORR](http://www.tectonics.caltech.edu/slip_history/spot_coseis/download_software.html) - Tools for displacement tracking.

### 3.6 Other
- [Awesome GIS](https://github.com/sshuair/awesome-gis) - The most comprehensive GIS list.
- [Geofolio](https://geofolio.org/#select-area) - Quick tool to check the climate, landcover and other land surface conditions at your study area. 
- [Google Dataset Search](https://datasetsearch.research.google.com/) - A platform to search for dataset.
- [WUR Geoscripting](https://geoscripting-wur.github.io/) - Geoscripting course from Wageningen University
- [OpenDroneMap](https://github.com/OpenDroneMap/WebODM/) - An open source tool for processing drone images.

#### Hope this will make our life easier. Feel free to share your collection of data and comment.
苟日新，日日新，又日新。