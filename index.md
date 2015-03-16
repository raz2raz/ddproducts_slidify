---
title       : MPG Predictor
subtitle    : Developing Data Products - Course Project Part 2
author      : Peter Randazzo
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The problem

When purchasing a used car, it can be very difficult to predict its miles per gallon based on the limited information available.

--- 

## The solution

Using the weight of the car and the number of cylinders of the car, we can predict its likely miles per gallon using historical auto data available in the R package.

--- 

## mpg ~ wt + cyl
As the weight and cylinder count increase, MPG decreases

```r
data(mtcars);library(ggplot2);qplot(wt,mpg,colour=factor(cyl),data=mtcars)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

--- 

## Try it @ raz2raz.shinyapps.io/part1

[MPG Predictor](http:/raz2raz.shinyapps.io/part1/)
