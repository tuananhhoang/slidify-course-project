---
title       : Develop Data Product - Course Project P2
subtitle    : Presentation about Motor Trend Car Road Tests Dataset Analysis Product
author      : Tuan Hoang
job         : 
framework   : revealjs        # {io2012, html5slides, shower, dzslides, revealjs ...}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Motor Trend Car Road Tests Dataset - Analysis

[Motor Trend Car Road Tests Dataset](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/mtcars.html): The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973-74 models).

**Data Analysis**: There are many factors that can affect to mpg (Miles per gallon), and therefore it is required to analyze relationships of many different variables to recognize [confounding variables](https://en.wikipedia.org/wiki/Confounding) and to avoid [omitted-variable bias](https://en.wikipedia.org/wiki/Omitted-variable_bias) when estimating mpg.

---

## Analysis Options

1. Customize x-axis and/or y-axis
2. Customize plotting points by
  - Colour
  - Size

![Analysis Option](./assets/img/option.PNG)

---

## The resulting PLOT

The resulting plot looks like this

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

---

## Correlation

Correlation of x-axis variable and y-axis variable is calculated and displayed also.

![Analysis Option](./assets/img/correlation.PNG)

---

## Future Works

<p align="left"><b>In order for user to be able to perform data analysis on many different datasets, this data product could be expanded by</b></p>

<p align="left">1. Allowing user to input either:</p>
<p align="left">  - Name of a dataset that can be loaded directly using _data_ command in r</p>
<p align="left">  - Path to a local csv file that contain any data that user wish to analyze</p>
<p align="left">2. Then data variables shall be loaded automatically into the customized selection boxes of x-axis, y-axis, colour, size</p>
