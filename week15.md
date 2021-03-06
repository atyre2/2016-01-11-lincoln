---
title: NRES 898 Week 15
layout: page
root: .
venue: "University of Nebraska-Lincoln"      # brief name of host site without address (e.g., "Euphoric State University")
---

## Week 15: SQL

See [the bottom of this page](#assignment) for this weeks Challenge. The start page for the DataCarpentry lesson is [here](http://www.datacarpentry.org/sql-ecology-lesson/index.html).

### Preparation

This week's videos and exercises are based on educational materials from [DataCarpentry](http://www.datacarpentry.org/). Create a directory to hold all your work for this week. We will also use this directory next week. It doesn't matter what it is called; I called mine learn_sql so that's what you'll see in the videos. The data files needed for the challenges can be [downloaded here](http://figshare.com/articles/Portal_Project_Teaching_Database/1314459). You want the CSV files surveys.csv, plots.csv and species.csv. I put these files in a subdirectory called data. 

### Introduction to SQL

* [Install SQLite Manager for Firefox](https://youtu.be/y96LxVSzUg4)
* [Reading for introduction](http://www.datacarpentry.org/sql-ecology-lesson/00-sql-introduction.html). This has a bit of motivational text and instructions for creating the database by importing the CSV files. 
* [Short video demonstrating data import](https://youtu.be/To8eVcbHFqk)

### Basic Queries

* [What is a Query?](https://youtu.be/uK_LHHbTNkU)
* [More complex queries](https://youtu.be/o1ema8tWv8M)
* [Reading and challenges](http://www.datacarpentry.org/sql-ecology-lesson/01-sql-basic-queries.html)
* [Video with challenge solutions](https://youtu.be/dIS-A-nhOxQ) in case you get stuck! The final challenge is not here; it is part of this week's assignment.

### Aggregating data

* [Counting and grouping rows](https://youtu.be/WttCJEATBqE)
* [Ordering and filtering aggregated results, and saving queries](https://youtu.be/J9Un-lHbfTY)
* [Reading and challenges](http://www.datacarpentry.org/sql-ecology-lesson/02-sql-aggregation.html)
* [Video with challenge solutions](https://youtu.be/gV8aJI_aLsA) in case you get stuck! The final challenge is not here; it is part of this week's assignment.

### Joining tables

Warning! The second challenge on this page is *hard*. Don't wrestle with it too long before looking at the solution video. Here's a hint: a query saved as a view can be used in the FROM clause of another query.

* [Joining tables](https://youtu.be/yxQCsH-lWzA)
* [Reading and challenges](http://www.datacarpentry.org/sql-ecology-lesson/03-sql-joins-aliases.html)
* [Joining tables challenge solutions](https://youtu.be/INmeMgBWmXo)

### Extra practice (optional!)

* [Downloading and using a database from the command line](https://youtu.be/adre7d2t0Pg)
* [Extra readings and challenges](http://swcarpentry.github.io/sql-novice-survey/index.html)

### Assignment

There are 3 challenges to turn in this week. Although I am not requiring you to turn in most of the challenges in the readings, I recommend that you attempt them to practice. 

1.  Challenge at the bottom of the [Basic Queries page](http://www.datacarpentry.org/sql-ecology-lesson/01-sql-basic-queries.html).
2.  Challenge at the bottom of the [SQL Aggregation page](http://www.datacarpentry.org/sql-ecology-lesson/02-sql-aggregation.html).
3.  Write a query that finds the average weight of each rodent species (i.e., only include species with Rodent in the taxa field). You will need to join the surveys and species tables. This challenge is in the middle of the [joins and aliases page](http://www.datacarpentry.org/sql-ecology-lesson/03-sql-joins-aliases.html)
 
Copy and paste the SQL statement for each challenge into a text file saved as week15_yourlastname.txt and attach that file to your submission. This Assignment is due on Friday of Week 15 \(April 22\) at 5 pm. Late assignments will receive a score of zero unless prior approval is granted.  
