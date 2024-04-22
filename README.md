# suhiR
An R package that allows you to estimate SUHI using Landsat 8 imagery
In order to calculate Land Surface Temperature, we need emissivity, which can be calculated via formula: 0.004 * FV + 0.986
But to estimate FV using the formula: ((NDVI - NDVI_min) / (NDVI_max - NDVI_min))^2, we need NDVI values
Therefore, the package has following functions to acheive that
  1. scale the optical bands (L8_Scale)
  2. scale the thermal bands(L8_Scale_Thermal)
  3. calculate NDVI (L8_NDVI)
  4. calculate FV (L8_FV)
  5. calculate emissivity (L8_em)
  6. calculate Land Surface Temperature (L8LST)
  7. calculate Surface Urban Heat Island (SUHI)
