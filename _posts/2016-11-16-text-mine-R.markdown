---
layout: post
title: Introduction to text mining in R
category: posts r
---

## Materials & Resources
* We followed the workshop materials created by Rochelle Terman (@rochelleterman): [Computational Text Analysis Workshop Materials
](https://github.com/rochelleterman/text-analysis-dhbsi)
* Text analysis with R for students of literature  <http://roger.ucsd.edu/record=b8216276~S9>
* Guide to Text Corpora <http://ucsd.libguides.com/data-statistics/textmining>
* We subscribe to [Crimson Hexagon](http://ucsd.libguides.com/data-statistics/crimsonhexagon)

## Topics

* Preprocessing text  
* Creating a DTM (document term matrix)
* Working with DTMs
* Word frequencies
* Wordclouds - of course!
* Discriminating / Distinctive Words
* Time permitting: Dictionary Methods (i.e. Sentiment Analysis)

**Things not covered**

* Document Similarity
* Topic modeling
* Clustering

## Time/Dates

* 9:00am - 12:00pm, Wednesday, November 16, 2016

## Location

* [Biomedical Library Classroom 4](http://maps.google.com/maps?q=32.875270,%20-117.236917)

## Instructors

* @u2ng - Reid Otsuji
* @jt14den - Tim Dennis  

## Setup

This lesson assumes you have the R, RStudio software installed on your computer.

R can be downloaded [here](https://cran.r-project.org/mirrors.html).

We will use the following packages in R, if you can, install prior to class:

RStudio is an environment for developing using R. It can be downloaded [here](https://www.rstudio.com/products/rstudio/download/). You will need the Desktop version for your computer.

###  Required R Packages

1. `tm` # text mining in R
2. `RTextTools` # a machine learning package for text classification
3. `qdap` # quantiative discourse analysis
4. `qdapDictionaries` # for sentiment analysis, etc
4. `entropy` # tools applying Information Theory
5. `dplyr` # data preparation and pipes $>$
6. `ggplot2` # for plotting
7. `SnowballC` # for stemming
8. `matrixStats` # for stats
9. `data.table` # for easier data manipulation
10. `scales` # to help us plot
11. `lsa` # latent semantic analysis
12. `cluster` # for clustering analysis
13. `fpc` # flexible procedures for clustering
14. `mallet` # a wrapper around the Java machine learning tool MALLET
15. `wordcloud` # to visualize wordclouds
16. `rJava` # dependency for mallet
17. Any dependencies to the packages above.

## Data

<https://drive.google.com/open?id=0ByRar-ghNtRlNGpENWJmNGNlS2s>

## Etherpad
http://pad.software-carpentry.org/r-txt-analysis

## Audience

Graduate students and researchers

## Description

This workshop will introduce you to text analysis techniques in R, an open source programming language. Some familiarity with R is expected as a requirement to attend this course.  You can attend the Intro to R course we provide or take this online tutorial <https://www.datacamp.com/courses/free-introduction-to-r> from DataCamp.

## Credits

* Rochelle Terman <https://github.com/rochelleterman/text-analysis-dhbsi>
* DataCamp.com for some examples
