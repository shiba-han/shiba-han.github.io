---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
---

Data sources commonly used in environmental economics research (to be updated)



# I. Air Pollution
## Ground Monitoring Data
- **Source**: China Ministry of Ecology and Environment  
- **Resolution**: monitor x hourly  
- **Coverage**: national (~1,600 monitors across all 330+ prefecture-level cities), 2013 – today  
- **Pollutants**: PM<sub>2.5</sub>, PM<sub>10</sub>, O<sub>3</sub>, NO<sub>2</sub>, SO<sub>2</sub>, CO  
- Real-time monitoring data are posted [here](http://106.37.208.233:20035/). Historical data going back to 2013 are available for purchase from [a private nonenterprise](http://data.epmap.org/). Another version of the historical data (May 2014 onward) is provided by Xiaolei Wang free of charge [here](https://quotsoft.net/air/).

## U.S. Embassy & Consulates Monitoring Data
- **Source**: U.S. Department of State Air Quality Monitoring Program  
- **Resolution**: monitor x hourly  
- **Coverage**: Beijing (2008 - 2017), Chengdu (2012 - 2017), Guangdong (2011 - 2017), Shanghai (2011 - 2017), Shenyang (2013 - 2017)  
- **Pollutants**: PM<sub>2.5</sub>
- These data can be downloaded from [stateair.net](http://stateair.net/). Click the city of interest -> View Data -> Agree to the data use agreement.

## Estimated PM<sub>2.5</sub> from Combining Satellite Data and Chemical Transport Modeling
- **Source**: Atmospheric Composition Analysis Group V5.GL.03  
- **Resolution**: 0.01° x 0.01° x yearly or 0.01° x 0.01° x monthly  
- **Coverage**: global, 2000–2022  
- **Pollutants**: PM<sub>2.5</sub> 
- PM<sub>2.5</sub> are estimated using information from satellite-, simulation- and monitor-based sources. Aerosol optical depth from multiple satellites (MODIS, VIIRS, MISR, and SeaWiFS) and their respective retrievals (Dark Target, Deep Blue, MAIAC) are combined with simulation (GEOS-Chem) based upon their relative uncertainties as determined using ground-based sun photometer (AERONET) observations to produce geophysical estimates that explain most of the variance in ground-based PM<sub>2.5</sub> measurements. 
- These data can be downloaded from [here](https://sites.wustl.edu/acag/datasets/surface-pm2-5/#V4.CH.03).

## SO<sub>2</sub> Satellite Data
- **Source**: OMI/Aura Sulphur Dioxide (SO<sub>2</sub>) Global Gridded V3  
- **Resolution**: 0.125 ° x 0.125 ° x daily  
- **Coverage**: global, 2004.10–present  
- **Pollutants**: SO<sub>2</sub> (molecule per square centimeter)  

OMSO<sub>2</sub>e is collected by OMI, a spectrometer aboard NASA’s Aura satellite. OMSO<sub>2</sub>e measures Total Column Density of SO<sub>2</sub> in the Planetary Boundary Layer. The data can be downloaded from [NASA Earth Data](https://disc.gsfc.nasa.gov/datasets/OMSO2G_003/summary).  
*Note*: OMSO<sub>2</sub>e contains many negative values with a mean value close to zero. Negative values are a result of OMSO<sub>2</sub>e’s retrieval algorithm, which is based on principal component analysis. The algorithm may give slightly negative values in regions where SO<sub>2</sub> emissions are low. However, when SO<sub>2</sub> emissions are high, we will see a stronger signal and higher SO2 value.

## Global High Air Pollutants (GHAP)
- Long-term, full-coverage, high-resolution, and high-quality datasets of ground-level air pollutants. It is generated from big data (e.g., ground-based measurements, satellite remote sensing products, atmospheric reanalysis, and model simulations) using artificial intelligence by considering the spatiotemporal heterogeneity of air pollution. 
- **Pollutants**: 7 major air pollutants (i.e., PM<sub>1</sub>, PM<sub>2.5</sub>, PM<sub>10</sub>, O<sub>3</sub>, NO<sub>2</sub>, SO<sub>2</sub>, and CO), PM<sub>2.5</sub> chemical composition (i.e., SO<sub>4</sub><sup>2-</sup>, NO<sub>3</sub><sup>-</sup>, NH<sub>4</sub><sup>+</sup>, Cl<sup>-</sup>, BC, and OM), and ambient polycyclic aromatic hydrocarbons (PAHs), including 7 carcinogenic PAHs (i.e., BaA, Chr, BbF, BkF, BaP, DahA, IcdP).
- Released by: Wei, Jing, Zhanqing Li, Alexei Lyapustin, Jun Wang, Oleg Dubovik, Joel Schwartz, Lin Sun, Chi Li, Song Liu, and Tong Zhu. 2023. “First Close Insight into Global Daily Gapless 1 Km PM2.5 Pollution, Variability, and Health Impact.” _Nature Communications_ 14 (1): 8349.  
The data can be downloaded from [Zenodo](https://zenodo.org/communities/ghap/records?q=&l=list&p=1&s=10&sort=newest).

# II. Instrumental Variable for Air Pollution
## Thermal Inversion
- **Source**: MERRA-2  
- **Resolution**: 0.5 ° x 0.625 ° x 3 hours x 42 pressure levels  
- **Coverage**: global, 1980–present  
- These data can be downloaded from [NASA Earth Data](https://disc.gsfc.nasa.gov/datasets/M2I3NPASM_5.12.4/summary?keywords=MERRA2).


# III. Water Pollution
## Monitoring Data
- **Source**: [National Environmental Quality Monitoring Network–Surface Water Monitoring System](https://szzdjc.cnemc.cn:8070/GJZ/Business/Publish/Main.html)  
- **Resolution**: monitoring section x 4-hour (note: 2014-04-2020-11: ~100 monitoring sections, after 2020.11: 1600+ monitoring sections)  
- **Coverage**: 2014.04-present  
- **Pollutants**
    - **Before 2020.05**: pH, 溶解氧（DO）, 高锰酸盐指数（CODMn）, 总有机碳（TOC）, 氨氮（NH3-N）
    - **After 2020-05**: 水温 (C摄氏度), pH, 溶解氧（mg/L）, 电导率 (us/cm), 浊度 (NTU), 高猛酸盐指数 (mg/L), 氨氮 (mg/L), 总磷 (mg/L), 总氮 (mg/L), 叶绿素α (mg/L), 藻密度 (cells/L)


# IV. Firm-level Emission Data
## Environmental Survey and Reporting, [(ESR)](http://hbk.cei.cn/aspx/default.aspx)  
- **Source**: administrated by MEP, first self-reported by each polluter, and then randomly verified by government auditors  
- **Resolution**: firm x yearly  
- **Coverage**: since 2001, top firms/plants contributing 85% of total emissions of the major pollutants in a county are entered in the ERS (Wang et al. 2018)  
- **Pollutants**: COD, ammonia nitrogen, sulfur dioxide, industrial smoke and dust, and solid waste  
- The most comprehensive environmental data in China and monitors polluting activities of all major polluting sources, including heavily polluting industrial firms, hospitals, residential pollution discharging units, hazardous waste treatment plants, and urban sewage treatment plants.
- Papers that use this data
    - Chen, S., et al. (2023). Bank deregulation and corporate environmental performance. _World Development_, 161, 106106.
    - He, G., Wang, S., & Zhang, B. (2020). Watering Down Environmental Regulation in China*. _The Quarterly Journal of Economics_.
    - Liu, Z., Shen, H., Welker, M., Zhang, N., & Zhao, Y. (2021). Gone with the wind: An externality of earnings pressure. _Journal of Accounting and Economics_, 72(1), 101403.
    - Wang, C., Wu, J., & Zhang, B. (2018). Environmental regulation, emissions and productivity: Evidence from Chinese COD-emitting manufacturers. _Journal of Environmental Economics and Management_.
    - Wu, H., Guo, H., Zhang, B., & Bu, M. (2017). Westward movement of new polluting firms in China: Pollution reduction mandates and location choice. _Journal of Comparative Economics_, 45(1), 119–138.
    - Zhang, B., Chen, X., & Guo, H. (2018). Does central supervision enhance local environmental enforcement? Quasi-experimental evidence from China. _Journal of Public Economics_, 164, 70–90.

## Continuous Emissions Monitoring Systems (CEMS) Data
- **Source**: each province’s publicly accessible data platform  
- **Resolution**: firm x unit x hourly  
- **Coverage**: e.g., Guangdong, Hubei, Shandong, Hebei, Zhejiang, and Shanghai  
- **Pollutants**: SO<sub>2</sub>, NO<sub>x</sub>, smoke and dust, CO<sub>2</sub>, etc.


# V. Weather / Climate
## Ground Monitoring Data
- **Source**: [National Meteorological Information Center of China](https://data.cma.cn/)
- **Resolution**: monitor x daily  
- **Coverage**: national (700+ monitors across all 330+ prefecture-level cities), 2008–2021 
- Include temperature, air pressure, water pressure, precipitation, relative humidity, sunshine duration, wind speed, wind direction
- Downloading the data needs access as an education user.


## NOAA Monitoring Data
- **Source**: [NOAA](https://www.ncei.noaa.gov/data/global-hourly/access/)
- **Resolution**: monitor x hourly
- **Coverage**: global; for China: national (400+ monitors across all 200+ prefecture-level cities), 1901-present
- Include elevation, temperature, dew temperature, cloud height, air pressure, visual distance, rain, snow depth, wind speed, wind direction

## ERA5 Reanalysis Data
- **Source**: [ECMWF](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels?tab=overview)
- **Resolution**: 0.25° x 0.25° x hourly (atmosphere), 0.5° x 0.5° x hourly (ocean waves)
- **Coverage**: global, 1940-present
- Include all the common-used variables, in addition, some other useful variables such as boundary layer height are also included.

## Weather Forecast Data #1
- **Source**: [ECMWF Integrated Forecasting System (IFS)](https://confluence.ecmwf.int/display/FUG/Section+2+The+ECMWF+Integrated+Forecasting+System+-+IFS) for detailed descriptions for different models.
- Different models and products have different resolutions: e.g., for the Atmospheric model Ensemble 15-day forecast (Set III - ENS): 0.1° x 0.1°, 4 forecast runs per day (00/06/12/18); different forecast time stamp for different runs (00/06/12/18): hourly, 3-hourly, 6-hourly.
The data can be accessed at [ECMWF Archive](https://www.ecmwf.int/en/forecasts/dataset/operational-archive), need a subscription (€3000 (EUR) per annum). Real-time forecast data are available to the public free of charge.

## Weather Forecast Data #2
- **Source**: [NOAA Global Forecast System (GFS)](https://www.ncei.noaa.gov/products/weather-climate-models/global-forecast)
- **Resolution**: From 0.25°, 0.5° to 1°, depending on the product; 4 runs per day: 00, 06, 12, 18UTC; time stamp varies from hourly, 3-hourly, 12-hourly, etc. 
- **Coverage**: 2004–present, depending on the product

## Weather Forecast Data #3
- **Source**: National Meteorological Information Center of China
- Including hourly forecast, next day half-day forecast, 15-day forecast, 40-day forecast.
- **Resolution**: district x daily
- **Coverage**: 2017–present
- CMDSC only has real-time data available to the public; historical data going back to 2017 are available for purchase from a [private nonenterprise](http://data.epmap.org/).


## Climate Projections
- **Source**: CMIP5
- **Resolution**: From 0.125° x 0.125° x daily to 5° x 5° x daily depending on the model
- **Coverage**: global, 1850–2300
- Historical experiments which cover the period where modern climate observations exist. These experiments show how the GCMs performs for the past climate and can be used as a reference period for comparison with scenario runs for the future. The period covered is typically 1850-2005.
- Ensemble of experiments from the Atmospheric Model Intercomparison Project (AMIP), which prescribes the oceanic variables for all models and during all period of the experiment. This configuration removes the added complexity of ocean-atmosphere feedbacks in the climate system. The period covered is typically 1950-2005.
- Ensemble of climate projection experiments following the Representative Concentration Pathways (RCP) 2.6, 4.5, 6.0 and 8.5. The RCP scenarios provide different pathways of the future climate forcing. The period covered is typically, 2006-2100 some extended RCP experimental data is available from 2100-2300.


# VI. Flood
## Flood Events Data #1
- **Source**: Global Active Archive of Large Flood Events or [Global Flood Database (GFD)](https://floodobservatory.colorado.edu/Archives) generated by the Dartmouth Flood Observatory (DFO). 
- **Coverage**: Global, 1985-2021
- Including location (shp file), start and end date, severity (quantified by damage, displaced/deaths), and main causes of large flood events across the globe. 
- *Note*: A map of the flood event with greater geographical accuracy (a pixel resolution of 250 meters) is available at [this website](https://global-flood-database.cloudtostreet.ai/#interactive-map).

## Flood Events Data #2
- **Source**: [FloodList](https://floodlist.com/data-api). (Access to the data has been closed but one can request the data on the waiting list.)
- **Coverage**: Global, early 2016–present
- For each flood event, the database includes (where possible) dates, locations (with geo-location), magnitude (rainfall, rivers, etc, also with geo-location) and damages (including fatalities, injuries, affected population, evacuations, and other material damages, also with geo-location).

## MODIS/Aqua+Terra Global Flood Product
- **Source**: [LANCE MODIS NRT global flood product (MCDWD)](https://nrt3.modaps.eosdis.nasa.gov/archive/allData/61/MCDWD_L3_NRT. ) by NASA
- **Resolution**: ~250m x daily
- **Coverage**: global, 2012-present
- The Flood Product shows flood and surface water detected from the twice-daily overpass of the MODIS optical sensors (onboard Terra and Aqua satellites). Several flood composites are generated: 1-Day, 2-Day, and 3-Day. These require 1, 2, and 3 water detections, respectively, to mark a pixel as water. Detailed description can be found at the [description page](https://www.earthdata.nasa.gov/learn/find-data/near-real-time/modis-nrt-global-flood-product).

