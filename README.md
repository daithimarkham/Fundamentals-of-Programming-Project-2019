# David Markham
# Fundamentals of Data Analytics Project - September 2019
# G.M.I.T. 
# Lecturer: Ian McLoughlin 


## Project containing a Jupyter Notebook, describing the statistics, plots, and relationships between the variables within the well known Tips Data-set.

## Topic: The Tips Data-Set

![download](https://user-images.githubusercontent.com/47174160/67091657-22f6ac80-f1a5-11e9-9474-680c86e77c6f.jpg) (Monster.com, 2019) 

## This project required me to research the well known Tips data-set, provide my own analysis of it and describe what kind of relationships were there between the variables.

I will be using a Jupyter Notebook to illustrate my findings, along with libraries such as Pandas and SeaBorn. Jupyter Notebook's are very powerful tools in terms of versatility, shareable and visualization.

My findings will be demonstrated by plots, histograms, boxplots, scatter-plots, and other statistical tools. 

# Contents 
1. **Getting Started** 
2. **Software need for this project.** 
3. **Project Plan and purpose.** 
4. **What's involved when investigating a data set and how Jupyter Notebook and SeaBorn can be used as an investigative tool.**
5. **What is the TIPS Data Set**
6. **My Research, Investigation**
7. **Findings**
8. **Bibliography**

## 1. Getting Started

When investigating data four steps to follow can be as follows;

**1. Question**: What are you trying to resolve or achieve?

**2. Analyze**: What tools are you going to use to present your findings?

**3. Investigate**: Research and investigate the problem/sector you are trying to extract data from.

**4. Repeat**: Keep repeating the process until you resolve the problem and present your findings.

Data can be an excellent resource when trying to predict, forecast, improve decision-making or gain a competitive advantage. When investigating a data set you ask yourself what you want to get from it? What is the sole purpose of it, and will pulling data answer the problem you want to solve correctly?

An excellent way of aiding your investigations is displaying results via plots, multi-plots, scatter plots, boxplots etc, which can be done by using the Pandas and SeaBorn libraries. Machine learning is about making predictions. This will display data and explore for eg, weekly, monthly, quarterly or yearly trends based on what you are looking for.

## 2. Software needed for this project.

Below is the software you will need to install in order to to get this project started.


- You will need to download Anaconda, which comes with Python, Jupyter, SeaBorn. You will also need a command line. I will be using Commander.
- Create a Git Repository on Github, and clone it down to your terminal. 
- CD in the folder you just created on Github. 
- Jupyter Notebook will be displayed in your browser, when you type Jupyter Notebook on your command line. From there you create a new Notebook, which we will be using to display our code and findings, and you're all set to go. 

## 3. Project Plan

To start with we will be going through what is involved when setting out to investigate a data set, and how you can back up arguments using scripts of code through Jupyter Notebook, certain libraries which will illustrate and back up your findings.

The purpose of this project is to gain skills using Jupyter Notebook, how to use libraries to display data visualization, statistics, and to improve your skills in machine learning. We will be using the Tips data-set to demonstrate our findings.

Using Jupyter Notebook I will explain my arguments and findings, attached will be plots, scatter-plots and other data visualization, which will be outputted from Pandas and SeaBorn libraries in my Jupyter Notebook. Along with the above data, included will be screenshots of my work in the ReadMe, and various other techniques explained, which I used to demonstrate my findings. Finally I will provide a summary and draw my conclusion of the data set.

- Firstly we will be using the data-set to see what the tips were like, smokers/non-smokers, lunch/dinner, male/female, day, min tip, max tip etc. 

- Secondly we will be discussing relationships between the values, total bill and tip amount, day of week and tip size, smoker versus non/smoker, lunch and dinner tips etc. If someone spends an x amount on their dinner, what would the tip be? Can we see a relationship in the evening time, esp at weekends when alcohol maybe involved and the tip size is increased due to this maybe? 

- And finally analyzing all pairs of variables, or selecting certain subsets of the data. The aim here is to pick out interesting data, not your standard data. Should tips be raised or reduced for example.  

## 4. What's involved when investigating a data set and how Jupyter Notebook can be used as a tool to show relationships between variables, if any.

**What data you are analyzing, and is it available to download via CSV file?**

To start your research on the Tips data set, go through various websites, read and watch material based on the data set, what do you want to extract from the data, tip-size in the afternoon versus evening for example, tips too small, too big etc. 

Basically we will be trying to predict the tip size based on the data for the waiter on a given time and day.

Next download the Tips data-set via csv file, which will help you find the relationship or patterns between the values in the file, which are as follows, dining times, tips size, smokers or non-smokers etc. You can find good CSV files on Github. I will be using various scripts of code to calculate the stats, maximum, minimum and mean of the column rows in the csv, along with other visualization methods to demonstrate my findings, such as SeaBorn and Jupyter, and some more libraries as necessary.  

We will be using Jupyter Notebook to display all our work. This is an excellent tool and interactive document to show programmers work, combine comments and markdown with code, and visualizations, all in the same environment. It lets you keep a detailed record of your work. Also, the ease of use of the Jupyter Notebook means that you can do all of your interactive work in notebooks, put them under version control, and commit regularly.

SeaBorn is a Python package for creating illuminating plots from data-sets. The tutorial provided with SeaBorn covers much more than just the use of SeaBorn - it teaches how to use plots effectively. SeaBorn contains many example data-sets that are installed with SeaBorn itself.

Sometimes on Github, it won't open Jupyter Notebook files. If Github won't open this file, copy and paste the URL address from the Jupyter file on Github and paste in the following link. This will display it every time you wish to viw it.

https://nbviewer.jupyter.org/


### Load the Tips data-set from a url. You will need to write the following code. This will display your data-set in Jupyter Notebook.

import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/mwaskom/seaborn-data/master/tips.csv')  

df

**Below are some of the libraries we will be using to analyze and plot our data.** 

- 1. Numpy: Designed for mathematical and scientific computation.

- 2. Pandas: Manipulates and analyzes data, for eg CSV files or SQL databases.

- 3. Matplotlib: A Python plotting library which plots and displays data on graphs, histograms, bar-charts, scatter-plots etc.

- 4. SeaBorn: A Python data visualization library based on Matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. (SeaBorn) 


## 5. **What is the TIPS Data Set**


- The Tips Data-Set is a well known set of data recorded by a waiter over a period of months, 244 days, containing seven variables. 
- The purpose of investigating this data set will be to try and predict the tip size for the waiter.
- The data recorded was as follows: 

1. Total bill in dollars.
2. Tip in dollars.
3. Male/Female bill payer.
4. Smoker/Non-Smoker at the dining party.
5. Day of the week. 
6. Time of the day: Lunch/Dinner.
7. Size of the party.

Our CSV file will consist of seven columns of data, it was recorded over 244 days, which will be our Index column. (https://www.kaggle.com/jsphyg/tipping) 


## 6. **My Research, Investigation**



## 7. **Findings**
## 8. **Bibliography**

https://seaborn.pydata.org/tutorial 

https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html

https://numpy.org/devdocs/user/quickstart.html








