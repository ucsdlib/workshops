---
layout: post
title: Carpentries Fall Workshops (2016)
category:
- posts
- R
- Carpentries
---

## Introduction

* Introduction to R: This 3 hour course includes a basic introduction to the R syntax, data structures, and language constructs.  We will also cover using RStudio, a tool to help manage R projects and write R scripts.  Following the basics, we will cover how to import data into R and how to work with R's most used data structure,  a dataframe.  This course is geared to participants who are new to R.
* Data Visualization in R: This workshop is geared to researchers wanting to use R for basic data visualization. It will cover ggplot2 and touch on ggvis for data visualization.  Some experience with R or attendance of the Intro to R course on 11/8 is required.

## Date
* Intro to R: November 8, 2016 (9:00 AM - 12:00 PM)
* Data Visualization in R: November 9, 2016 (9:00 AM - 12:00 PM)
* Data Cleaning, Preparation and Analysis in R: November 10, 2016 (9:00 AM - 12:00 PM)

## Instructors
* @u2ng - Reid Otsuji
* @jt14den - Tim Dennis  

## Audience

All graduate students and researchers.

### Data (We will use a few csvs)

1. Gapminder, you can get that by running this code in R:

~~~
gapminder <- read.csv("https://goo.gl/BtBnPg", header = T)
~~~

~~~
download.file('https://raw.githubusercontent.com/swcarpentry/r-novice-gapminder/gh-pages/_episodes_rmd/data/gapminder_wide.csv', 'data/gapminder_wide.csv')
~~~

2. A zip file of several csv's:

<https://github.com/ucsdlib/workshops/raw/gh-pages/notebooks/data.zip>

Unzip those into your 'data' folder inside your workshop project folder.

## Resources
* [Collaborative Notes: Etherpad](http://pad.software-carpentry.org/intro-r-ucsd)
* [Lessons for Class](http://swcarpentry.github.io/r-novice-gapminder/)
* [R for Reproducible Scientific Analysis](http://swcarpentry.github.io/r-novice-gapminder/)
   * Introduction to R and RStudio through Control Flow  
   * [Dataframe manipulation with dplyr](http://swcarpentry.github.io/r-novice-gapminder/13-dplyr/)
   * [Dataframe manipulation with tidyr](http://swcarpentry.github.io/r-novice-gapminder/14-tidyr/)
* [RStudio Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf)
* [Introduction to R (datacamp free course)](https://campus.datacamp.com/courses/free-introduction-to-r)
* [Data wrangling cheat sheet from RStudio](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)
* [Introduction to dplyr](http://stat545.com/block009_dplyr-intro.html)
* [R E-Books](https://goo.gl/zBiQ7U)
* [Data/GIS Lab](http://ucsd.libguides.com/data-gis-lab)
* Contact me <timdennis@ucsd.edu>, or set up an appointment <https://calendly.com/timdennis>
