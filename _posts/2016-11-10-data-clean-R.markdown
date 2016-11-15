---
layout: post
title: Data Cleaning, Preparation and Analysis in R
category: posts r
---

## Time/Dates

* 9:00am - 12:00pm, Thursday, November 10, 2016

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

### Etherpad: <http://pad.software-carpentry.org/intro-r-ucsd>

## Instructors

* @u2ng - Reid Otsuji
* @jt14den - Tim Dennis  

## Audience

Graduate students and researchers

## Description

This workshop is geared to researchers wanting to use R for basic data manipulation and analysis. It will introduce participants to the basics of data tidying and manipulation (notably using tidyr & dplyr), how to set up data processing pipelines, and briefly cover working with a database. We will be using a genomics dataset for this course.  This workshop is designed for novices, but we would like you to have some experience with R or have attended the Intro to R course on 11/8.
