---
title       : Body Mass Index
subtitle    : An APP to help you control weight
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, quiz, bootstrap] # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## The Problem

According to the Center for Disease Control

* More than one-third (34.9% or 78.6 million) of U.S. adults are obese. 
* Obesity leads to increased heart disease, stroke, and type 2 diabetes.
* The medical costs for people who are obese were $1,429 higher than those of normal weight. 

We can take individual responsibility for this by monitoring our own body fat.

---

## Assessing Your Risk

There are many ways to access your risk, but three that are accessible to most people are:

* The body mass index which is calculated from your height and weight.
* Your waist circumference; if your waist is larger that 35 inches you may carry your fat there and be at a higher risk of medical issues.
* You have a known risk factor such as
  * High blood pressure
  * Family history
  * High cholesterol
  * Smoker  
  
Even though the body mass index does not distinquish between fat and muscle, we will use it for measure of body fat because it does take into account height.  We suggest that you use this metric in combination with advice from your physician.

---  


## Body Mass Index

The body mass index is calculated from your height, inches, and weight, pounds.  The formula is:
$$ BMI = {weight \over height^2}*703$$
where the 703 is to adjust for units.  The following plot gives the normal weight range for a given height in inches.  A 5 foot 9 in person should be between 125 and 169 pounds as indicated by the lines.  
![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

    


---

## BMI App

To help you determine your body fat status, we have developed an easy to use internet application.  Go to the [BMI Calculator App](https://anand336.shinyapps.io/BMI_Calc) and enter your height and weight and the application will determine your body mass index as well as giving you a classification, such as normal, underweight, etc.  

This app will be particularly useful for


* Monitoring the impact of a exercise program. 
* Answering what if questions about your weight and the impact of body fat.
* Setting goals. 


