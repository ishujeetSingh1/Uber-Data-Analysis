# Uber-Data-Analysis

## Introduction

The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## Architecture 
The architecture diagram depicts data storage in Google Cloud Storage, serving as the object storage. Transformation logic will be scripted in Python and deployed using the open-source data pipeline tool, MAGE. Subsequently, data will load into BigQuery, GCP's data warehouse. The final dashboard will be constructed in Looker, leveraging various components.

![architecture (1)](https://github.com/ishujeetSingh1/Uber-Data-Analysis/assets/142827400/a4761842-eb24-42ec-9fae-eba2c38ca171)


## Technology Used
- Programming Language - Python

Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/

Contibute to this open source project - https://github.com/mage-ai/mage-ai


## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="data_model.jpeg">


