#  Data Modeling for Sparkify 

### Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way to query their data, which resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

### Goal

Create a Postgres database and ETL pipeline

### Database & ETL pipeline

song and log datasets which were in json formate were use, created a star schema as shown below, which includes 
* one fact table: **songplays** 
* four dimension tables: **users**, **songs**, **artists** and **time**

<img src="star_schema.jpg" alt="drawing" width="400"/>

### Exmaples queries

1. What is the most played song over different years?
2. Who is the favorite artist for different locations?