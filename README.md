# Predicting San Francisco's 311 Service Requests

## Introduction

The San Francisco [311 program](https://sf311.org/) allows residents, visitors, and businesses a way to obtain information, report problems, 
and submit service requests. This system is available 24 hours a day and is meant to be a fast and efficient way to interact with the local 
government. The goal of this project is to investigate these interactions especially in the context of the socio-economic and demographic 
background (from the US Census Bureau) of San Francisco. The 311 program offers a glimpse into the local government and how it operates. 
This analysis will attempt to optimize the government, via 311, and allow it to be more proactive and responsive to the needs of people 
through predictive modeling.

This repo contains the code, data, documentation and reports for this project. 

## Results

Using a SARIMA model, we are able to model various service request types in the multitude of census tracts of San Francisco. We can 
predict weekly service request counts for the most popular request types in a given census tract. We further show that using demographic 
data from the US Census, we can often improve the model fit. The scoring metric is mean absolute error.  

## Overview

| Step | Description | File(s) |
| --- | --- | --- |
| Proposal | Full project proposal and idea | [report](https://github.com/pjandir/CapstoneProject2/blob/master/Proposal.md) |
| Data wrangling | Data cleaning, wrangling, and munging | [code](https://nbviewer.jupyter.org/github/pjandir/CapstoneProject2/blob/master/data-wrangling.ipynb) |
| Data exploration | Closer statistical look at the data | [code](https://nbviewer.jupyter.org/github/pjandir/CapstoneProject2/blob/master/data-exploration.ipynb) |
| Milestone report | Summary of all steps completed so far | [report](https://github.com/pjandir/CapstoneProject2/blob/master/milestone-report.pdf) |
| Model building | In-depth analysis and machine learning | [code](https://nbviewer.jupyter.org/github/pjandir/CapstoneProject2/blob/master/model-building.ipynb) |
| Final report | Discussion and overview of completed project | [report](https://github.com/pjandir/CapstoneProject2/blob/master/full-report.pdf), [slide deck](https://github.com/pjandir/CapstoneProject2/blob/master/slide-deck.pdf) | 


