# Sparkify: Data Modeling with Cassandra

## Background

A startup called Sparkify wants to analyze the data they've been collecting 
on songs and user activity on their new music streaming app. The analysis team 
is particularly interested in understanding what songs users are listening to. 
Currently, there is no easy way to query the data to generate the results, 
since the data reside in a directory of CSV files on user activity on the app.

I've been brought on as a data engineer to create an Apache Cassandra database 
which can create queries on song play data to answer the questions. 

## Project Description

In this project, I've applied what I've learned on data modeling with Apache
Cassandra and built an ETL pipeline using Python. I've modeled the data and 
created tables optimized for the queries that will be run.

## Data

The dataset is located in the ```event_data``` directory and consists of CSV files 
partitioned by date. Here are examples of filepaths to two files in the dataset:
```
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```

Running Part I of the notebook ```Project_1B_Project_Template.ipynb``` will result in
a new file called ```event_datafile_new.csv``` which will be denormalized data. Here is 
a screenshot of that file:
![](images/image_event_datafile_new.jpg)


## Files and Usage

- ```Project_1B_Project_Template.ipynb```: contains all code to process data, create tables,
and insert data.
