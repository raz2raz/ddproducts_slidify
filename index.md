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

<div style='text-align: center;'>
    <img height='400' src='assets/img/used-car.jpg' />
</div>

--- 

## mpg ~ wt + cyl
As the weight and cylinder count increase, MPG decreases

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

--- 

## The solution

Using the weight of the car and the number of cylinders of the car, we can predict its likely miles per gallon using historical auto data available in the R package.

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- 

## Try it @ raz2raz.shinyapps.io/part1

[MPG Predictor](http://raz2raz.shinyapps.io/part1/)

<a href="http://raz2raz.shinyapps.io/part1/" target="_blank">
<div style='text-align: center; border: 1px solid black'>
    <img height='400' src='assets/img/MPGPred.png' />
</div>
</a>

