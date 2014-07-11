---
title       : Survival on the Titanic
subtitle    : Easy to use survival analysis tool
author      : Shannon Rush
framework   : io2012
highlighter : highlight.js  
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- 

## Introduction
* The sinking of the RMS Titanic has been a subject of interest for over 100 years, in both academia and popular culture.

* The demographics of those who survived versus those who tragically perished provides insight into the way society of the early 1900s valued varying socio-economic classes, age groups, and genders.

* The [Titanic Survival Analysis Application](https://shanfu.shinyapps.io/DDP_shiny/) is an easy to use interface for analyzing the survival rates of Titanic passengers in demographics of your choosing.

--- 

## The Data
* The dataset used for this application was obtained from the Kaggle competition [Titanic: Machine Learning from Disaster](http://www.kaggle.com/c/titanic-gettingStarted)

* Reproducible markdown of all data processing is [available on Github](https://github.com/shannonrush/DDP_shiny/blob/master/data/data_processing.Rmd) 

* The resulting dataset consists of 714 passenger observations with 4 features


```r
    summary(data)
```

```
##    survived             class         gender         age      
##  Length:714         Min.   :1.00   female:261   Min.   : 0.0  
##  Class :character   1st Qu.:1.00   male  :453   1st Qu.:20.0  
##  Mode  :character   Median :2.00                Median :28.0  
##                     Mean   :2.24                Mean   :29.7  
##                     3rd Qu.:3.00                3rd Qu.:38.0  
##                     Max.   :3.00                Max.   :80.0
```

---

## Features
![](assets/img/screenshot.png)

---

## Thank You!
Thank you very much for viewing this presentation! 
* [Titanic Survival Analysis Application](https://shanfu.shinyapps.io/DDP_shiny/)
* [Titanic Survival Analysis Github Repo](https://github.com/shannonrush/DDP_shiny)
* [This Presentation's Github Repo](https://github.com/shannonrush/DDP_slidify)
* [The Kaggle competition 'Titanic: Machine Learning from Disaster'](http://www.kaggle.com/c/titanic-gettingStarted)



