---
title       : Calculate Body mass index
subtitle    : measure of relative size based on the mass and height of an individual
author      : leiqin
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Body mass index

The body mass index (BMI), or Quetelet index, is a measure of relative size 
based on the mass and height of an individual.

The index was devised by Adolphe Quetelet during the course of developing 
what he called "social physics", between 1830 and 1850.

$$BMI = \frac{mass(kg)} {(height(m))^{2}}$$

--- .class #id 

## BMI value range

BMI provides a simple numeric measure of a person's thickness or thinness, 
allowing health professionals to discuss weight problems more objectively 
with their patients.

the current value recommendations are as follow: a BMI from 18.5 up to 25 
may indicate optimal weight, a BMI lower than 18.5 suggests the person 
is underweight, a number from 25 up to 30 may indicate the person is 
overweight, and a number from 30 upwards suggests the person is obese.

---

## Calculate

If a person has body mass 65 kilograms, and height 1.75 metres.


```r
mass <- 65
height <- 1.75
BMI <- mass / height^2
BMI
```

```
## [1] 21.22449
```

he's BMI is 21.2.

he is optimal weight.

---

## Reference

You can find more information at [Wikipedia](http://en.wikipedia.org/wiki/Body_mass_index)

You can find a [shiny app](https://leiqin.shinyapps.io/devdataprodShinyApp) here.
