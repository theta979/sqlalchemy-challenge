# sqlalchemy-challenge
Module 10 Challenge
Part 1:
After importing dependencies and sqlalchemy we connect to the sqlite engine.

I used automap to load the database schema into Python classes automatically then accessed the tables in the database to find the names of the columns.

Then I was able to use sqlalchemy functions to find the most ecent date. That allowwed me to use a query to look back a year and isolate temperature data for that time period.

This was plotted in a graph. After finding the most active station in the database, I was able to find the highest, lowest and average temperature observation data and plot it in a histogram.

After working on this project, I definitley would like to spend more time learning a working with not only the functions available with sqlalchemy but the other tools and features for Object relational mapping.