# Google-Fiber-Project

Hello there! I undertook this project as part of the Google Business Intelligence Professional Certificate. 

## Background

Google Fiber provides people and businesses with fiber optic internet. Currently, the customer service team working in their call centers answers calls from customers in their established service areas. In this project, my role as the BI Analyst involves exploring trends in repeat calls to reduce the number of times customers have to call in order for an issue to be resolved.

## Project Planning

To identify key metrics and dashboard requirements, I created 3 key project planning documents: 
* Stakeholder requirements document.
* Project requirements document.
* Strategy document. 

The documents have been attached to this repo for your viewing. 

## Data Extraction

This BI course introduces the concepts of Extract, Transform and Load (ETL) and the use of Google DataFlow to achieve this. 

For this step, I have been provided datasets for 3 different markets in csv format and I decided to join them using Google BigQuery. 

```
SELECT *
FROM `bi-project-bigquery.fibre.market_1`
UNION ALL
SELECT *
FROM`bi-project-bigquery.fibre.market_2`
UNION ALL
SELECT *
FROM `bi-project-bigquery.fibre.market_3`
```

As the data had been previously cleaned, the target table is created and ready. This step also represents the Extract phase of the ETL pipeline. 

### Data Visualization

