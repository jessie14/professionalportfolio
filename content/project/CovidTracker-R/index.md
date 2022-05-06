---
title: CovidTrackerR 
summary: An R package designed for the easy retrieval and analysis of data pertaining to Covid trends in Canada, including information about cases, vaccinations and testing. 
tags:
  -  Software Packages 
date: '2022-02-05T00:00:00Z'

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
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Github Repo
    url: https://github.com/UBC-MDS/Group28-CovidTracker-R
  - icon: book
    icon_pack: fas
    name: Documentation
    url: https://ubc-mds.github.io/Group28-CovidTracker-R/
    
    
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

The CovidTrackerR package is a software package in R that provides basic data cleaning, wrangling and plotting of real time Covid tracking data in Canada. The package serves as a wrapper for the opencovid.ca API, and provides additional helper functions for visualising the data, as a time series or in the form of a map, as well as provides summary statistics of the data. The package consists of four functions, each listed below with their respective purpposes:
* `get_covid_data()` : Retrieves cleaned and formatted data of specified type and within (optionally) provided time ranges and locations
* `plot_time_series()` : Plots time series trends in selected Covid data, including options for trendlines and smoothing
* `plot_geographical()` : Plots choropleth map of selected Covid data across Canada
* `calculate_stat_summary()`: Returns key statistical information about Covid data, such as long run trends and comparisons between provinces

Through this project I demonstrated appropriate use of collaborative software development processes and tools, including packaging code for use by others, using advanced distributed version control workflows and features to effectively manage a multi-person project, writing comprehensive test suites, and carrying out continuous integration via GitHub Actions. The documentation for this package was built using Roxygen and pkgdown, and can be found [here](https://ubc-mds.github.io/Group28-CovidTracker-R/).

