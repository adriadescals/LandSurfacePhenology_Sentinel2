# Land Surface Phenology with Sentinel-2


This repository contains the Google Earth Engine code that was developed for the estimation of Land Surface Phenology (LSP) metrics (start and end of season (SoS and EoS)) with Sentinel-2 at high latitudes. 

The LSP extraction method is the threshold method.

The repository contains the following files:

- Estimation of SoS and EoS with time series smoothing (20-day composition and cubic interpolation)
  https://code.earthengine.google.com/7b8201664a88b8a29ae08503a1f5bd23
  
- Estimation of SoS and EoS without time series smoothing (linear interpolation over the raw time series)
  https://code.earthengine.google.com/246ebbb8b98393445e5e12cd87ab524c
  
Adrià Descals - a.descals@creaf.uab.cat / CREAF - Centre de Recerca Ecològica i Aplicacions Forestals

REFERENCE PAPER
Descals, A., Verger, A., Yin, G., & Peñuelas, J. (2020). Improved estimates of arctic land surface phenology using Sentinel-2 time series. Remote Sensing, 12(22), 3738.
