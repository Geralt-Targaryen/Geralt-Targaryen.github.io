---
layout: project
type: project
image: images/MCM_cover.png
title: "Mining the Past and Envisioning the Future"
date: 2022.02
published: true
projectpaper: ../resources/MCM.pdf
labels:
  - Data Science
  - Time Series Analysis
summary: "This is a time series analysis project for Mathematical Contest of Modeling (MCM) 2022. The paper won Honorable Mention prize."
---

Bitcoin and gold are two major investment methods in modern society. Gold price tends to be stable, while the Bitcoin price tends to vibrate. Investors are often seeking for opportunities to transfer their funds between different goods to maximize their gain. In this project, we are provided with two historical data for gold and Bitcoin respectively. The question is to find a detailed investment plan (i.e. hold how much money in gold, bitcoin, or in hand in each day) to maximize the initial fund of 1000 dollars.

This is a classic time series analysis question, and we adopt different models to solve the problem:

1. Traditional investment methods by analyzing the trend lines.
2. Auto Regressive Integrated Moving Average (ARIMA)
3. Long Short-Term Memory (LSTM)
4. Gradient Boosting Regression
5. Reinforcement Learning

Our final result combines several models above by having them vote for the final strategy.

The report can be found [here](../resources/MCM.pdf).
