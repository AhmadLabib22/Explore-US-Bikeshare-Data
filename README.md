# Explore-US-Bikeshare-Data
Udacity Data Analyst Degree - Project II

## Overview
In this project, Python is used to explore data related to bike share systems for three major cities in the United States — Chicago, New York City, and Washington.

The source code takes in raw input from the user to create an interactive experience.
According to the input the code will import the data and will provide information by computing descriptive statistics.

## What Software Do I Need?
To complete this project, i'll require the following softwares:
- Python 
- A text editor (Atom)
- A terminal application

## The Datasets
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

Start Time (e.g., 2017-01-01 00:07:57)
End Time (e.g., 2017-01-01 00:20:53)
Trip Duration (in seconds - e.g., 776)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)
The Chicago and New York City files also have the following two columns:

Gender
Birth Year

The original files are much larger and messier, and you don't need to download them, but they can be accessed here if you'd like to see them (Chicago, New York City, Washington). These files had more columns and they differed in format in many cases. Some data wrangling has been performed to condense these files to the above core six columns to make your analysis and the evaluation of your Python skills more straightforward. In the Data Wrangling course that comes later in the Data Analyst Nanodegree program, students learn how to wrangle the dirtiest, messiest datasets, so don't worry, you won't miss out on learning this important skill!

#Statistics Computed
You will learn about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, you'll write code to provide the following information:

##1 Popular times of travel (i.e., occurs most often in the start time)

most common month
most common day of week
most common hour of day
##2 Popular stations and trip

most common start station
most common end station
most common trip from start to end (i.e., most frequent combination of start station and end station)
##3 Trip duration

total travel time
average travel time
##4 User info

counts of each user type
counts of each gender (only available for NYC and Chicago)
earliest, most recent, most common year of birth (only available for NYC and Chicago)
##The Files
To answer these questions using Python, you will need to write a Python script. To help guide your work in this project, a template with helper code and comments is provided in a bikeshare.py file, and you will do your scripting in there also. You will need the three city dataset files too:

chicago.csv
new_york_city.csv
washington.csv
All four of these files are zipped up in the Bikeshare file in the resource tab in the sidebar on the left side of this page. You may download and open up that zip file to do your project work on your local machine.

Some versions of this project also include a Project Workspace page in the classroom where the bikeshare.py file and the city dataset files are all included, and you can do all your work with them there.

## Answering Questions
Through writing code, I'm able to answer the following questions about the bike share data:

- What month occurs most often in the start time?
- What day of the week (Monday, Tuesday, etc.) occurs most often in the start time? 
- What hour of the day occurs most often in the start time?
- What is the total trip duration and average trip duration?
- What is the most frequently used start station and most frequently used end station?
- What is the most common trip (i.e., the combination of start station and end station that occurs the most often)?
- What are the counts of each user type?
- What are the counts of gender?
- What is the earliest birth year (when the oldest person was born), most recent birth year, and most common birth year?
