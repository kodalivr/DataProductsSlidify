---
title       : Devloping Data Products Project
subtitle    : The relationship between variables and MPG
author      : Venkat Kodali
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

This is a simple Shiny app to show the relationship between variable and miles per gallon (MPG).

The app uses mtcars dataset.

In this application  the user can choose the variable and plot will show the relationship of the selected variable to MPG. The app also has a radio button to choose the color of Boxplot.

Shiny server link: https://kodalivr.shinyapps.io/Project

--- .class #id 

## Application Help

# How to use the application

The following options are avialable in the application to show relationship with MPG. 

# 1. variable
     
     1.  Number of cylinders          2.  Displacement (cu.in.)
     3.  Gross horsepower             4.  Rear axle ratio
     5.  Weight (lb/1000)             6.  1/4 mile time
     7.  V/S                          8.  Transmission
     9.  Number of forward gears      10. Number of carburetors
     

# 2. Show BoxPlot's outlines

# 3. Boxtop Color
 
 There is a tab for displaying BoxPlot or Regression Model.


--- .class #id 

## Sample Code snippet


```r
#     selectInput("variable", "Variable:",
#                  c("Number of cylinders" = "cyl",
#                 "Displacement (cu.in.)" = "disp",
#                 "Gross horsepower" = "hp",
#                 "Rear axle ratio" = "drat",
#                 "Weight (lb/1000)" = "wt",
#                 "1/4 mile time" = "qsec",
#                 "V/S" = "vs",
#                 "Transmission" = "am",
#                 "Number of forward gears" = "gear",
#                 "Number of carburetors" = "carb"
#                 )),
#     checkboxInput("outliers", "Show BoxPlot's outliers", FALSE),
#     radioButtons("colors","Boxplot Color:",c("Red" = "red", "Blue" = "blue"))
```




--- .class #id 

## Conclusion

This project deals with creating a simple Shiny application with little documentation that easily make anyone to use the application. Then created 5 slides (inclusive of the title slide)  to pitch the app. Create a web page using Slidify.



