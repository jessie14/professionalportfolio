---
title: Olympic Athletes Dashboard (R)
summary: An interactive dashboard to visualize and explore demographic information of Olympic athletes from 1896 to 2016
tags:
  - Dashboards 
date: '2022-03-16T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

share: false
show_date: false

show_related:
  docs: false
  page: false
  post: false
  project: false
  publication: false
  talk: false

image:
  caption: 
  placement: 1
  focal_point: Center

links:
  - icon: github
    icon_pack: fab
    name: Github Repo
    url: https://github.com/UBC-MDS/Olympic_athletes_dashboard-R
  - icon: chart-column
    icon_pack: fas
    name: Dashboard
    url: https://olympic-athletes-dash-r.herokuapp.com/
    
    
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The Olympic Games involve a large number of athletes from a variety of backgrounds, as well as personal attributes (height, weight, age). Olympic committees have an interest in identifying talented individuals for various sports at an early point in order to bolster their olympic teams. To address this, we built a data dashboard which allows olympic committees to explore historical trends in various athletes across all years and sports. The dashboard displays the distributions of athlete attributes, which can be filtered by medals won, country, olympic years, and sport, such that users can make quick comparisons and understand long-term trends in the data. The data used in the dashboard is sourced from Tidy Tuesday [here](https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-07-27/readme.md)

The dashboard framework was built using Plotly Dash in R, and HTML and CSS components were used to create stylistic customizations. The dashboard consists of 4 plots: 3 histograms for athletes' Age, Weight, and Height distribution with two colors to distinguish genders that can interactively zoom in or out, and a map which shows the number of athletes per country. There are 5 filters on the left side bar: a slider for year range selection, two drop-down menus for sports and countries, and two radio buttons to select medal and season. The dashboard is hosted publicly using Heroku.

A quick demonstration of the dashboard functionalities is shown below, and the full dashboard can be found [here](olympic-athletes-dash-r.herokuapp.com/).

![screen reader text](Olympic_athletes_dashboard_R.gif "Olympic Athletes Dashboard")
