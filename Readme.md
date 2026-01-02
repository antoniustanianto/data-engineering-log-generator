# Server Log Data Generator & Analysis

## Overview
This project simulates server log data to demonstrate core data engineering skills, including data schema design, synthetic data generation, and basic exploratory analysis.  
The goal is to show how raw, system-generated data can be structured and prepared for analysis.

This project reflects common real-world scenarios where log data is used to monitor system behavior and identify potential issues.

---

## Problem Statement
In many operational environments, server logs are generated continuously but are not always analysis-ready.  
Data engineers are responsible for transforming raw log data into structured datasets that can be queried and analyzed.

This project simulates that process using synthetic data.

---

## Dataset Description
The generated dataset contains the following fields:

- **timestamp**: Time when the request occurred  
- **ip_address**: Client IP address  
- **endpoint**: API or application endpoint accessed  
- **status_code**: HTTP response status code  
- **response_time_ms**: Server response time in milliseconds  

A total of 1,000 log records are generated to simulate system activity.

---

## Tools & Technologies
- Python
- Pandas
- Jupyter Notebook

---

## Data Engineering Concepts Demonstrated
- Designing a structured log schema
- Generating realistic synthetic operational data
- Handling time-series style data
- Performing basic validation and analysis on raw logs
- Preparing datasets for downstream analysis or pipeline integration

---

## Sample Analysis
Basic analysis performed in this project includes:
- Distribution of HTTP status codes
- Initial inspection of response time behavior

These steps represent early-stage data exploration commonly performed after data ingestion.

---

## Project Structure
data-engineering-log-generator/
|
├── generate_logs.ipynb
├── server_logs.csv
└── README.md


---

## Possible Improvements
This project can be extended by:
- Adding error rate monitoring
- Introducing log anomalies
- Loading the dataset into a database
- Scheduling automated log generation
- Visualizing trends over time

## Additional Analysis
Additional analysis includes calculating error rates and identifying endpoints with the highest number of failed requests to simulate basic system monitoring use cases.



---

## Author
Antonius Oktavian Tanianto
