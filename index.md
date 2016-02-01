---
title       : Learning from Titanic Disaster? (Kaggle)
subtitle    : Developing Data Products - Coursera
author      : Vimal Kumar M
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

1. Project is inspired by: 
  - Kaggale training [Titanic: Machine Learning from Disaster?](https://www.kaggle.com/c/titanic-gettingStarted)
  - Tutorial by Trevor Stephens available [here](http://trevorstephens.com/post/72916401642/titanic-getting-started-with-r)
2. In this project we must predict the fate of the passengers aboard the RMS Titanic, which famously sank in the Atlantic ocean during its maiden voyage from the UK to New York City after colliding with an iceberg.

--- .class #id 

## How many passengers were there in RMS Titanic?

Class   | Number of Passengers
--------|---------------------
First   | 325
Second  | 285 
Third   | 706
Crew    | 885   

    
-Servivers vs Not Servivers

Servived?     | Number of Passengers
--------------|---------------------
Servived      | 711
Not Servived  | 1490

--- .class #id 

## Does your chances of Serivival increased if you were 1st class?

Servived?     | 1st Class | 2nd Class | 3rd Class | Crew
--------------|-----------|-----------|-----------|-----
Servived      | 203       | 118       | 178       |212
Not Servived  | 122       | 167       | 528       |673
total         | 325       | 285       | 706       |885   

    
- So Rate of Servival of 1st class Vs 3rd Class is
  - First Class 62.4615385%
  - Third Class 25.2124646%

From the above result it is clearly evident that first class passenger had more chances winning than third calss passenger.

--- .class #id 

## Hope you would like to travel in first class :)

![](http://projectaccesseasttn.org/thank-you/) 



