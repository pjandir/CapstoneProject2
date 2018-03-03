# SF 311 Data Predictions - Capstone Two Project Proposal

## Introduction

Like many other cities, San Francisco has a [311 program](https://sf311.org/). It allows residents, visitors, and businesses a way to obtain 
information, report problems, and submit service requests. Note this program is for non-emergencies only. This system is available 24 hours a day and is meant 
to be a fast and efficient way to interact with the local government. The interactions represent, to some degree, the needs and desires of San Francisco. The 
purpose then of this project is to investigate these interactions especially in the context of the socio-economic and demographic background (from the US Census
Bureau) of San Francisco. Do certain service requests come from certain areas of neighborhoods? Can we predict future interactions, specifically, service 
request volumes? The 311 program offers a glimpse into the local government and how it operates. This analysis will attempt to optimize the government, 
via 311, and allow it to be more proactive and responsive to the needs of people through predictive modeling.

## Approach

After obtaining the 311 program data, it will need to be cleaned. There are missing values in a few different columns. Because there are nearly 3
millions records in the data, rows with null values will be dropped. In fact, the size of the dataset is further reduced to keep only the years 2015-2017. 
The motivation for this is to have a more manageable dataset. In order to merge the 311 data with the Census data, the 311 data
needs to be assigned the proper Census tract numbers. The US Census Geocoding API provides a service to get these tract numbers, but the API constraints
mean making a few million calls is inefficient and slow. A predictive model using, for example, a Poisson regression can help explain the 311 service requests. 
This type of model is best used for integer-valued and time independent data, which is the case here. 

## Client

The potential target is the San Francisco local government. This project can shed some light on how city services are used and requested throughout
the different parts of San Francisco. A predictive model giving volume or count data on future service requests can also help the government in becoming more
effective and proactive in helping its citizens and visitors. This more efficient government can make a large positive impact on its community.

## Data

The main data source is the 311 request [data](https://data.sfgov.org/City-Infrastructure/311-Cases/vw6y-z8j6/data) available at San Francisco's 
open data portal. In addition, socio-economic, demographic and other types of data is available from the US Census Bureau 
[website](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml?refresh=t). 

## Deliverables

The major result from this project for the client will be the service request prediction model, in addition to any other interesting clustering 
insight from the data. As the purpose of this project is to provide a better understanding of San Francisco's citizens, any relevant will be provided. 
The full code will also be given, in the form of Jupyter Notebooks. The slide deck and report of this project is the last component of the full deliverable.


