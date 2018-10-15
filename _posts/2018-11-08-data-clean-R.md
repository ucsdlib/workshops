---
layout: post
title: Data Cleaning, Preparation and Analysis in R
category: posts r
---

## Resources and materials

* [R for Reproducible Scientific Analysis](http://swcarpentry.github.io/r-novice-gapminder/)
  * [Dataframe manipulation with dplyr](http://swcarpentry.github.io/r-novice-gapminder/13-dplyr/)
  * [Dataframe manipulation with tidyr](http://swcarpentry.github.io/r-novice-gapminder/14-tidyr/)
* [Data wrangling cheat sheet from RStduio](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf)
* [Introduction to dplyr](http://stat545.com/block009_dplyr-intro.html)

## Time/Dates

* 9:00am - 12:00pm, Thursday, November 8, 2018

## Course materials

### Data - We will use a few csvs:

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

### HackMD: 

## Instructors

* @u2ng - Reid Otsuji
* @stephlabou - Stephanie Labou 

## Audience

Graduate students and researchers

## Description

This workshop is geared to researchers wanting to use R for basic data manipulation and analysis. It will introduce participants to the basics of data tidying and manipulation (notably using tidyr & dplyr), how to set up data processing pipelines, and briefly cover working with a database. We will be using a genomics dataset for this course.  This workshop is designed for novices, but we would like you to have some experience with R or have attended the Intro to R course on 11/8.

Some familiarity with R is expected as a requirement to attend this course.  You can attend the [Intro to R](http://ucsd.libcal.com/event/2846343?hs=a) course we provide or take this online tutorial <https://www.datacamp.com/courses/free-introduction-to-r> from DataCamp. 

<slabou@ucsd.edu>
<rotsuji@ucsd.edu> 
