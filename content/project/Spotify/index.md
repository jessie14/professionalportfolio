---
title: Prediction of Song Popularity
summary: An data pipeline to train a regression-based model to predict the popularity of a song, given various features such as genre, duration, and tempo.
tags:
  - Machine Learning 
date: '2022-04-01T00:00:00Z'

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
  placement: 2
  focal_point: Center

links:
  - icon: github
    icon_pack: fab
    name: Github Repo
    url: https://github.com/UBC-MDS/DSCI_522_Spotify_Track_Popularity_Predictor
  - icon: book
    icon_pack: fas
    name: Report
    url: uploads/Report.pdf 
    
    
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
Millions of new songs are released every year, but only a small fraction of them become popular. With new artists and new songs constantly emerging in the booming music industry, it has become increasing competitive for artists to release the most popular songs. Having an algorithm that predicts how popular a new song will be can be an effective tool for artists writing new music to determine if they will become major hits. 

In this project, I built a data pipeline that cleans the data, then builds and trains a Ridge regression model to predict the popularity of a Spotify song, given various features such as genre, duration, and tempo. Cross validation was carried out, and hyperparameter optimization was performed using RandomizedSearchCV. Through this project I gained experience managing project software and environment dependencies using Docker, and automating data science workflows using Make. I learned to write R, Python and shell scripts for non-interactive data analysis and run literate coding documents non-interactively.

The data used in the project was sourced from Tidy Tuesday and can be found [here](https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-09-14/readme.md). A report of the full analysis can be found [here](https://jessiewong.netlify.app/uploads/Report.pdf).
