# Land Surface Phenology with Sentinel-2


This repository contains the Google Earth Engine code that was developed for the estimation of Land Surface Phenology (LSP) metrics (start and end of season (SoS and EoS)) with Sentinel-2 at high latitudes. 

The LSP extraction method is the threshold method.

The repository contains the following files:

- Estimation of SoS and EoS with time series smoothing (20-day composition and cubic interpolation)
  https://code.earthengine.google.com/d9feace23f3337cff736c1122e1eeee3
  
- Estimation of SoS and EoS without time series smoothing (linear interpolation over the raw time series)
  https://code.earthengine.google.com/ec5822d3084767f27cd139cbc44cd998
  
Adrià Descals - a.descals@creaf.uab.cat / CREAF - Centre de Recerca Ecològica i Aplicacions Forestals
