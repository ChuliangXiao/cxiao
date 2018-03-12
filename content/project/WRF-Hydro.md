+++
# Date this page was created.
date = "2016-10-01"

# Project title.
title = "WRF-Hydro"

# Project summary to display on homepage.
summary = "The implementation of National Water Model in the Great Lakes Basin"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "NWM_GLB.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["WRF-Hydro"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "NWM_GLB.png"
caption = "Great Lakes basin showing the seven waterbody polygons (lakes Nipigon, Superior, Huron, Michigan, St. Clair, Erie, and Ontario), the approximately 152,000 stream segments that connect to the lake waterbody polygons in over 3,000 locations.  Stream gages are shown in black for Environment and Climate Change Canada and red for U.S. Geological Survey."

+++
- The implementation of the community Weather Research and Forecasting model hydrological extension package (WRF-Hydro) ([Gochis et al. 2013](https://ral.ucar.edu/projects/wrf_hydro/overview)) in the Great Lakes region with collaborators from the National Center for Atmospheric Research (NCAR) supported by a newly granted NOAA Joint Technology Transfer Initiative (JTTI) project.  
- Beginning in the summer of 2016, the NOAA [National Water Center (NWC)](http://water.noaa.gov) in partnership with the National Centers for Environmental Prediction (NCEP), the National Center for Atmospheric Research (NCAR) and other academic partners will produce operational hydrologic predictions for the nation using a new National Water Model (NWM) that is based on WRF-Hydro. The WRF-Hydro modeling system is a physics-based, distributed hydrologic modeling system and has been used in several streamflow prediction applications in the U.S. and around the world.  The modeling system provides users with a multi-physics and multi-scale modeling framework for representing a large range of terrestrial hydrologic processes such as infiltration, runoff, lateral flow, channel flow, soil moisture, snowpack, and evapotranspiration as well as various water management components.  
- Because of lack of consistency of high-resolution terrain (also known as “geofabric”) data along the U.S. and Canada borders, the Great Lakes basin is not entirely included in the current version of NWM, leaving a substantial gap for applying the national model to the water-dominated region with the largest lake system on earth. Thus, a specific effort has been devoted to implementing the WRF-Hydro modeling system in the Great Lakes basin, including preparing high-resolution terrain datasets, parameterizing lakes and reservoirs, and calibrating the model.
