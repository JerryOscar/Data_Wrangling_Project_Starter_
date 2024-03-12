# Project: Real World Data Wrangling

## Table of Contents
1. [Introduction](#introduction)
2. [Data Gathering](#Data_Gathering)
3. [Data Assessment](#Data_Assessment)
Data Cleaning
Analysis
Data Storing
Project Reflection
<a name="introduction"></a>

<a name="introduction"></a>
## Introduction
This project investigates whether certain car makes and models are more likely to be involved in traffic violations and crashes. We analyze data from two datasets: one focusing on traffic violations and the other on crash reports. By comparing vehicle characteristics across these datasets, we aim to identify any trends that could help improve road safety measures.

<a name="data-gathering"></a>

##Data Gathering
We extract data using two different methods:

Programmatically downloading the 'Crash_Reporting_-_Drivers_Data' file.
Manually downloading the 'Traffic_Violations' file.
Datasets
Crash_Reporting_-_Drivers_Data
The data is programmatically downloaded from the official source using a custom function designed to fetch the dataset from a given URL. This ensures the latest and most accurate information is obtained for analysis.

Variables:

Vehicle Make: Represents the manufacturer or brand of the vehicle involved in the crash.
Vehicle Model: Refers to the specific model of the vehicle.
Vehicle Year: Indicates the manufacturing year of the vehicle.
Collision Type: Specifies the type of collision that occurred in the crash.
Driver At Fault: Indicates whether the driver was at fault in the crash.
Traffic_Violations
The data is downloaded manually from the official source website: data.gov

Variables:

Violation Type: Specifies the type of traffic violation committed.
Make: Represents the manufacturer or brand of the vehicle involved.
Model: Refers to the specific model of the vehicle.
Year: Indicates the manufacturing year of the vehicle.
<a name="data-assessment"></a>

Data Assessment
We assess the data according to data quality and tidiness metrics. We list two data quality issues and two tidiness issues. We assess each data issue visually and programmatically, then briefly describe the issue we find. We include justifications for the methods we use for the assessment.

<a name="data-cleaning"></a>

Data Cleaning
We clean the data to solve the 4 issues corresponding to data quality and tidiness found in the assessing step. After the cleaning for each issue, we use either the visually or programmatical method to validate the cleaning was successful. At this stage, we also remove variables that are unnecessary for our analysis and combine our datasets.

<a name="analysis"></a>

Analysis
We use the cleaned data to answer our research question. We produce at least two visualizations using the cleaned data and explain how they help us answer the question.

<a name="data-storing"></a>

Data Storing
We update our local database/data store with the cleaned data, following best practices for storing our cleaned data:

We maintain different instances/versions of data (raw and cleaned data).
We name the dataset files informatively.
We ensure both the raw and cleaned data is saved to our database/data store.
<a name="project-reflection"></a>

Project Reflection
We reflect on the project and discuss any further actions we would take if given more time to complete the project. We also explain how we would share our findings with different stakeholders.
