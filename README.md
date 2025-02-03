<!-- omit from toc --> 
# Google Data Analytics Capstone
This is the final project for the Google Data Analytics Professional Certificate.

* **Date:** February 2, 2025 
* **Last Updated:** February 2, 2025

<!-- omit from toc -->   
## Contents
- [Description](#description)
- [Getting Started](#getting-started)
  - [Gathering Data](#gathering-data)
  - [File Prep](#file-prep)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Findings](#findings)
- [Visualisation](#visualisation)
- [Further Exploration](#further-exploration)
- [Final Thoughts](#final-thoughts)


---------------------------

## Description
For the Capstone, I was required to complete a Case Study. I opted to do Case Study 1: How does a bike-share navigate speedy success?

For this task, I was asked to examine the habits of casual users of a bike-sharing company so that the marketing team can entice them into yearly memberships.

## Getting Started
### Gathering Data
* I downloaded the last 12 months of datasets (2024) from here: https://divvy-tripdata.s3.amazonaws.com/index.html
* I opened one file to examine the type of data present in the file, determining what files I may consider keeping
  
### File Prep
* in **Excel**, I loaded all 12 files to transform them
* I removed the following columns:
  * Ride_Id
  * Start & End Station Names
  * Start & End Station longitude & latitude
* Created a column, Ride Time, to calculate the total number of times in minutes that the bike was used
* The amount of data in Ride Time column was a bit much. Created buckets to make it easier to group in visual


## Exploratory Data Analysis (EDA)
* After transforming the data, I created some Pivot Tables to get a better sense of the data

### Findings
* Casual users use the bike-sharing service **on the weekends**
* Casual user usage was heaviest from **May - Sept (the summer)**
* Casual users do not user the **bikes longer than 30 minutes**


## Visualisation
After initial EDA, I created a Dashboard in Excel with these initial findings. I then went on to open the dataset into Power Bi to create a visualisation.


## Further Exploration
I would like to go back and see what I could do with the geo information (perhaps make a map?)

## Final Thoughts
Sincce it's my first Case Study, I wasn't sure what to expect. It was certainly interesting to see how all the things learned over the course of the Certification would come together. 
