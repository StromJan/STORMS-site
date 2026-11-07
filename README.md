# STORMS

Extratropical cyclones in the ECMWF IFS and AIFS control forecasts that reach
Finland (0–35°E, 50–70°N), updated after each 00 and 12 UTC run.

## Contents

- `index.html`: the page
- `img/`: the figures of the latest init
- `run.txt`: the init shown (YYYYMMDDHH)

## Method

Cyclones are tracked in the 0–168 h control forecasts with TempestExtremes
(MSLP minima) and kept when their track enters the region box. The page shows
the track maps of both models and, for each system, an IFS vs AIFS
comparison, wind, precipitation and wind persistence footprints, and the
change of the forecast track across recent inits.

Research prototype of the R2O STORMS project, Institute for Atmospheric and
Earth System Research (INAR), University of Helsinki. Not an official
forecast.

## Data

Contains modified ECMWF IFS and AIFS open forecast data, © European Centre
for Medium-Range Weather Forecasts (ECMWF), licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). ECMWF does not
accept any liability for errors or omissions in the data or for any use of
it. Coastlines: [Natural Earth](https://www.naturalearthdata.com/).
