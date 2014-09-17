---
title       : The Height Calculator
subtitle    : A Shiny Application
author      : Bridget Thrasher
job         : 
framework   : shower        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

# The Height Calculator  
  
## A Shiny Application  
  
### by Bridget Thrasher

---

# Objective  

# This Shiny application predicts a son's height based on the height of his father  

* Simple, dynamic interface  
* Based on widely-used data  
* Returns 95% confidence interval

---

# Data

# The data used in this application were collected by Karl Pearson in 1903  

* 1,078 pairs of father and son heights  
* Linear regression model yields statistically significant relationship between the variables:  
     + p-value = 1.1213 &times; 10<sup>-69</sup> 

---

## Prediction Model Plot

# Linear regression (blue line) not 1:1 relationship (black line):  

<img src="assets/fig/unnamed-chunk-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

---

# Application Usage and Outcome

* Enter father's height in inches into the text box  
* Lower and upper bounds of 95% confidence interval of son's height prediction displayed  
  
![App screenshot](images/shinyAppSS.jpg)
