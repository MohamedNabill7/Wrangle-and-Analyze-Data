# Wrangle-and-Analyze-Data
Udacity Data Wrangling Project "WeRateDogs Twitter Data"
## Introduction
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as ~WeRateDogs~. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

## What Software Do I Need?
You need to be able to work in a Jupyter Notebook on your computer. Please revisit our Jupyter Notebook and Anaconda tutorials earlier in the Nanodegree program for installation instructions.

The following packages (libraries) need to be installed. You can install these packages via conda or pip. Please revisit our Anaconda tutorial earlier in the Nanodegree program for package installation instructions.

* pandas
* NumPy
* requests
* tweepy
* json

You need to be able to create written documents that contain images and you need to be able to export these documents as PDF files. This task can be done in a Jupyter Notebook, but you might prefer to use a word processor like Google Docs, which is free, or Microsoft Word. A text editor, like Sublime, which is free, will be useful but is not required.

## Steps
### Gathering Data

Data is successfully gathered:

* From at least the three (3) different sources on the Project Details page.

* In at least the three (3) different file formats on the Project Details page.

### Assessing Data

Two types of assessment are used:

* Visual assessment: each piece of gathered data is displayed in the Jupyter Notebook for visual assessment purposes. Once displayed, data can additionally be assessed in an 
external application (e.g. Excel, text editor).

* Programmatic assessment: pandas' functions and/or methods are used to assess the data.

At least eight (8) data quality issues and two (2) tidiness issues are detected, and include the issues to clean to satisfy the Project Motivation. Each issue is documented in 
one to a few sentences each.

### Cleaning Data

* The define, code, and test steps of the cleaning process are clearly documented.

* Copies of the original pieces of data are made prior to cleaning.

* All issues identified in the assess phase are successfully cleaned using Python and pandas.

* A tidy master dataset with all pieces of gathered data is created.

### Storing and Acting on Wrangled Data

* Save master dataset to a CSV file.

* The master dataset is analyzed using pandas in the Jupyter Notebook and at least three (3) separate insights are produced.

* At least one (1) labeled visualization is produced in the Jupyter Notebook using Python’s plotting libraries.

