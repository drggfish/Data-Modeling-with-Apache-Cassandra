# Data-Modeling-with-Apache-Cassandra

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

# Datasets

For this project, you'll be working with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:

```
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv

```

## Project structure

Files used on the project:
1. **event_data** data folder with event data files in **csv** format that will be processed by the iPython notebook.
2. **Project_1B_Project.ipynb** project file that includes all of the necessary **Python** code to complete the tasks of the project.

## Database

The database can be installed locally or ran using Docker, which is the
preferred method. I have included a **docker-compose.yml** file that when ran using "docker-compose up -d"
will start a docker container running an **Apache Cassandra** database.

## Running the project

1. Run the **iPython** notebook one cell at a time. 