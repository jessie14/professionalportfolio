---
title: Predicting Daily Rainfall in Australia 
summary: An ensemble machine learning model built using Big Data technologies and deployed on the AWS platform.
tags:
  - Machine Learning 
date: '2022-04-30T00:00:00Z'

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
    url: https://github.com/UBC-MDS/DSCI525-Group7
    
    
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

Data can come from many different sources, such as online networks, web pages, audio and video devices, social media platforms and many other sources. Some of the largest sources of data are social media platforms and networks. For example, Facebook generates more than 500 terabytes of data everyday in the form of pictures, videos, messages, and more. When dealing with such massive amounts of data, we can no longer use traditional tools to store, process, or analyze the data. Instead, we rely on big data technologies to help collect and store large datasets, as well as to analyze the data to uncover new and valuable insights.

In this project I used a variety of big data solutions including Hadoop and Spark to train a RandomForest Regressor model that predicts the rainfall in Sydney, Australia, which was deployed to the AWS platform. The model was trained on a large dataset around 6GB, where the features are outputs of different climate models and the target is the observed rainfall observation. The dataset used is can be found on [figshare](https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681). The first step of the process was to retrieve the data from the web using API, process the data, then convert it to an efficient file format. I then moved the data to cloud, setup the infrastructure in the cloud and built a machine learning model. This involved setting up an EC2 instance in AWS, moving data in an S3 bucket, and data wrangling. Next, I set up a distributed infrastructure to run the machine learning model by setting up an EMR cluster with Spark, Hadoop, and JupyterHub, which was used to train and optimize the model. Specifically, Spark's MLlib was used to optimize the hyperparameters for the model.  Lastly, the model was deployed in an EC2 instance on the cloud as a REST API using the FLASK web framework to allow other consumers to use it.
