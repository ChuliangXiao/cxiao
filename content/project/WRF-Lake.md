+++
# Date this page was created.
date = "2015-10-01"

# Project title.
title = "WRF-Lake"

# Project summary to display on homepage.
summary = "Improving the 1-D lake model in WRF for the Great Lakes."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "2016-JAMES-Cover.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["WRF-Lake"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "2016-JAMES-Cover.jpg"
caption = "Great Lakes basin showing the seven waterbody polygons (lakes Nipigon, Superior, Huron, Michigan, St. Clair, Erie, and Ontario), the approximately 152,000 stream segments that connect to the lake waterbody polygons in over 3,000 locations.  Stream gages are shown in black for Environment and Climate Change Canada and red for U.S. Geological Survey."

+++
The lake module in WRF (original called LISSS, Subin et al. 2012) was obtained from the Community Land Model version 4.5 with some modifications by Gu et al. (2015), based on the origional concept of Hostetler and Bartlein (1990), which performs quite well in shallow lakes (depth < 50 m). (Incorporated in WRF since v3.6). Our work (Xiao et al. 2016) further updated the lake module in WRF with the surface albedo scheme and vertical diffusivity to improve the lake surface temperature and lake ice simulation in the Great Lakes.
