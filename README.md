# Bayes-Rule-with-Forecasting
Using R to implement Bayes Rule with Forecasting.

## Overview
The following document will use R to implement the Bayes Rule with Forecasting on a given Situation

## Situation
Let's assume that Madison, Wisconsin gets about 115 days of precipitation per year. Suppose that when there is precipitation, the forecast on Channel 3000 is correct 93% of the time and when there is no precipitation in the city, they are correct 87% of the time.

## Question: How many days will Channel 3000 correctly forecast in a non-leap year (365 days)

### Answer:
Correct Precipitation Prediction: $`(Odds Correct for Precipitation) * (Days there is Precipitation)`$ = 107 (106.95)

Correct No Precipitation Prediction: $`(Odds Correct for Non-Precipitation) * (Days there is No Precipitation)`$ = 218 (217.5)

$`Correct Prediction = (Correct Precipitation Prediction) + (Correct No Precipitation Prediction)`$

Correct Prediction = 107 + 218 = 325 Days

## Question: 

## Question: Let's assume that the Channel 3000 forecast was correct yesterday. This increases the likelihood of Channel 3000's forecast for today. Specifically, if the forecast was correct yesterday, then the probability of Channel 3000 accurately predicts if there is precipitation 93% of the time, and 87% of the time when there is no precipitation. If the forecast was correct on January 29th, what is the probability it was correct on January 28th? Assume that the forecast was incorrect on the 27th.

### Last Updated
02/15/2024
