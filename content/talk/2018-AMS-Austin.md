+++
date = 2018-01-01T00:00:00  # Schedule page publish date.

title = "Implementing the WRF-Hydro Modeling System in the Great Lakes Region"
time_start = 2018-01-09T14:00:00
time_end = 2018-01-09T17:00:00
abstract = ""
abstract_short = ""
event = "AMS 2018"
event_url = "https://ams.confex.com/ams/98Annual/webprogram/Paper336022.html"
location = "Austin, TX"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["WRF-Hydro"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "AMS-2018.png"
caption = ""

+++
As a physics-based, spatially-distributed hydrologic modeling system, the community Weather Research and Forecasting model (WRF) hydrological extension package (WRF-Hydro) has been used in several streamflow prediction applications in the U.S. and around the world, including the National Water Model (NWM) at the newly established NOAA National Water Center. However, because of lack of consistency of the geofabric data along the U.S. and Canada borders, the Great Lakes basin is not entirely included in NWM, leaving a substantial gap for applying the national model to the water-dominated region. Thus, a specific effort has been devoted to implementing the WRF-Hydro modeling system in the Great Lakes basin, including preparing high-resolution terrain datasets, parameterizing lakes and reservoirs, and calibrating the model. Two experiments have been carried out to support implementation of the NWM in the Great Lakes basin: an offline WRF-Hydro simulation forced by NLDAS2 and a coupled WRF/WRF-Hydro simulation. The model results are validated against observations in terms of precipitation, runoff, soil moisture, channel flow, and land surface heat fluxes. Our preliminary study presented here shows that the WRF-Hydro model is capable of reproducing the land–hydro-air feedbacks in the Great Lakes region.