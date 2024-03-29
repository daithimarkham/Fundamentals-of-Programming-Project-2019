# David Markham
# Fundamentals of Data Analytics Project - September 2019
# G.M.I.T. 
# Lecturer: Ian McLoughlin 


## Project containing a Jupyter Notebook, describing the statistics, plots, and relationships between the variables within the well known Tips Data-set.

## Topic: The Tips Data-Set

![download](https://user-images.githubusercontent.com/47174160/67091657-22f6ac80-f1a5-11e9-9474-680c86e77c6f.jpg) (Monster.com, 2019) 

## In this project we will be researching the well known Waiter Tips data-set, provide analysis of it and describe what kind of relationships were there between the variables, and try and predict the tip size for a given day.

We will be using a Jupyter Notebook to illustrate our findings, along with libraries such as Pandas and SeaBorn. Jupyter Notebook's are very powerful tools in terms of versatility, shareable and visualization.

The findings will be demonstrated by plots, histograms, boxplots, scatter-plots, and other statistical tools. 

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

Data can be an excellent resource when trying to predict, forecast, improve decision-making or gain a competitive advantage. When investigating a data set you ask yourself what you want to get from it? What is the sole purpose of it, and will pulling data, answer the problem you want to solve correctly?

An excellent way of aiding your investigations is displaying results via plots, multi-plots, scatter plots, boxplots etc, which can be done by using the Pandas and SeaBorn libraries. Machine learning is about making predictions. This will display data and explore for eg, weekly, monthly, quarterly or yearly trends based on what ever you are looking for.

## 2. Software needed for this project.

Below is the software you will need to install in order to to get this project started.


- You will need to download Anaconda, which comes with Python, Jupyter, SeaBorn. You will also need a command line. For this project, we will be using Commander.
- Create a Git Repository on Github, and clone it down to your machine, via terminal. 
- CD in the folder you just created on Github. 
- Jupyter Notebook will be displayed in your browser, when you type Jupyter Notebook on your command line. From there you create a new Notebook, which we will be using to display our code and findings.
- Enter some code, save and close down notebook, go back to your terminal and go through the standard commands to push to Github, and you're all set to go. 

## 3. Project Plan

To start with we will be going through what is involved when setting out to investigate a data set, and how you can back up arguments using scripts of code through Jupyter Notebook, certain libraries which will illustrate and back up your findings.

The purpose of this project is to gain skills using Jupyter Notebook, how to use libraries to display data visualization, statistics, and to improve your skills in machine learning. We will be using the Tips data-set to demonstrate our findings.

Using Jupyter Notebook I will display my findings, stats , attached will be plots, scatter-plots and other data visualization, which will be displayed through Pandas and SeaBorn libraries. Finally I will provide a summary and draw my conclusion of the data set.

- Firstly we will be using the data-set to see what the tips were like, smokers/non-smokers, lunch/dinner, male/female, day, min tip, max tip etc. This can be done through Pandas.

- Secondly we will be displaying relationships between the values, total bill and tip amount, day of week and tip size, smoker versus non/smoker, lunch and dinner tips etc. If someone spends an x amount on their dinner, what would the tip be? Can we see a relationship in the evening time, esp at weekends when alcohol maybe is involved, and the tip size and smoking is increased due to this maybe? 

- And finally analyzing all pairs of variables, or selecting certain subsets of the data. The aim here is to pick out interesting data, not your standard data. Should tips be raised or reduced for example. When was the data set recorded? Maybe the gap between men and women bill-payers has reduced greatly since then. Maybe smoking has also reduced since then, due to a more health conscious population.

## 4. What's involved when investigating a data set and how Jupyter Notebook can be used as a tool to show relationships between variables.

**What data you are analyzing, and is it available to download via CSV file?**

To start your research on the Tips data set, go through various websites, read and watch material based on the data set, what do you want to extract from the data, tip-size in the afternoon versus evening for example, tips too small, too big etc. 

Basically we will be trying to predict the tip size, based on the data, for the waiter on a given time and day.

Next download the Tips data-set via csv file, which will help you find the relationship or patterns between the values in the file, which are as follows, dining times, tips size, smokers or non-smokers etc. You can find good CSV files on Github, or Haggle. We will be using various scripts of code to calculate the stats, maximum, minimum and mean of the column rows in the csv. Pandas library will demonstrate these for us. Along with the above, we can use visualization methods to demonstrate my findings, such as SeaBorn and Jupyter, and some more libraries as necessary.  

We will be using Jupyter Notebook to display all our work. This is an excellent tool and interactive document to show programmers work, combine comments and markdown with code, and visualizations, all in the same environment. It lets you keep a detailed record of your work. Also, the ease of use of the Jupyter Notebook means that you can do all of your interactive work in notebooks, put them under version control, and commit regularly.

SeaBorn is a Python package for creating and illuminating plots from data-sets. The tutorial provided with SeaBorn covers much more than just the use of SeaBorn - it teaches how to use plots effectively. SeaBorn contains many example data-sets that are installed with SeaBorn itself. We will be adapting some code from there, along with Pandas, which will help us display stats.

Sometimes on Github, it won't open Jupyter Notebook files. If Github won't open your file, copy and paste the URL address from the Jupyter file on Github and paste in the following link. This will display it every time you wish to view it.

https://nbviewer.jupyter.org/


### Load the Tips data-set from a url. You will need to write the following code. This will display your data-set in Jupyter Notebook.

import pandas as pd

df = pd.read_csv('https://raw.githubusercontent.com/mwaskom/seaborn-data/master/tips.csv')  

df (displays the data-frame you just imported.)

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

I began my research by googling the waiter tips data-set, where I found information on the data-set quite easily. I found data-sets which I could import and used it to display stats through Pandas, and visualization, in terms of plots and trying to identify relationships between the variables, through SeaBorn. 


A waiters tips can be determined by many factors, such as location, quality of food and service, size of the party, smoking or non-smoking etc. Our main focus, was to try and determine, **what factors determined tip-size**? Are there patterns as to how customers tip, such as total bill, time etc. I quickly found out using various code I found online, and on the Pandas Tutorial page, that I could get all kinds of stats on the data-set. This proved very quickly to be helpful, as I could spot stats and trends straight away. The code which was used gave us tip-size for the bills, percentage tip-size, smoker vs non-smoker tip-size, busy days of the week, time of day which was busier and so on. 

After exploring the statistics using <a href="https://pandas.pydata.org/" target="_blank">Pandas</a>, we next moved on, using <a href="https://seaborn.pydata.org/" target="_blank">Seaborn</a>, a very effective tool for data visualization. It provides a high-level interface for drawing attractive and informative statistical graphics. Using the library displayed all kinds of relationships, which helped us determine many relationships between the variables. For example, we could easily identify a relationship among non-smokers, smokers seemed more spread out on the plots, and less unpredictable, in terms of tipping. Many types of plots were used to display trends, and identify relationships, using this library.


## 7. **Findings**

After our research and investigation into the dat-set, using Pandas and Seaborn, we could determine, what factors determined tip-size, and helped us predict what the tip-size was going to be on a given day, and time. This could be done through smokers or non, size of the party, dinner vs lunch, day of the week and sex.

- Summary of the statistics we got from the variables:
1. Total bill average was 20 Dollars.
2. Tip average was 3 Dollars.
3. Average size of the party was 2.5 people.
-   156 total bills paid by size of party, 2 people. 
-   38 bills was party size 3, and 37 was party size four.
4. Saturday and Sunday were the busiest days , 87 and 76 total bills. Friday had 19, and Thursday 62.
5. Smokers - 93, Non- Smokers 151. 
6. Male bill payers - 157, Female bill payers totalled 87. 
7. Male tip size was 485.07, Female tip size was 246.51.
8. Dinner total bills was 176, lunch total bills was 76. 


I think the stat which stands out the most is the size of the dinner party. The greater the size of the party, the more the tip reduces. It is clear from the stats above that the most tips and totals bills received, was by parties of two, which had an average tip size the greatest, over the four days. This size table, requires less work than large tables, and generates more in tip size. 

We saw that females seem to have more of a relationship in tipping, 15%. Males have less of a relationship, tips can vary up and down a little from the average. 

        T.Bill  Tip     Size   Percent Tip       
**Female**

Dinner	999.08	  156.11	   128      15.625375

Lunch	571.87	   90.40	    86      15.807788

**Male**

Dinner	2661.22	  389.96	   335      14.653430
 
Lunch	595.60	   95.11	    78	    15.968771

We can also see that the tips are extremely low on Fridays, due to how quiet it is from total bills paid. If you are a waiter here, management need to roster employees accordingly with the busy days, so all waiters can get an equal chance to earn the same amount of tips as each other, based on service of course. 

Other interesting stats included, times. Dinner had 176 bills, while lunch only had 68. If you are a waiter, you want to be working on evening shift, as more tips are clearly generated. Males seemed to pay more bills at the weekend, when the dinner size was two. 

Another set of variables I found interesting was smokers. Male smokers tipped less @ 13.5 percent tip size vs total bill. While male non-smokers tipped 15.7%. Female non-smokers tipped 15.7% of total bill, while female smokers tipped the highest @ 16.3%. So clearly from the above, female smokers generate the highest tip vs total bill.

We also found out using a plot from Seaborn, that smokers vs non-smokers seemed to be very similar on a Saturday dinner time, could be down to alcohol, as Saturday tends to be the night out which quite a few people tend to have drinks, which could be related. Female tippers who smoke on a Saturday night out, will tip the highest, for waiting staff in this particular restaurant on a Saturday, dinner time. 

Also this data was recorded in the 90's, as demographics have changed over the previous few decades I'm sure the stats would be quite different now in terms of male vs female bill payers. The same could also be said for smoking which is banned in a considerable amount of countries.

The tip size is 15% of the total bill in America. If you receive above average service and you deem it to be exceptional, the tips size is said to be a customary 20%/25%. In most places a good tip is deemed to be 20%. As we can see from the stats above, this was not met, only on few occasions, usually by table sizes of one. The bigger table size, left below the average on most occasions, of between 10 and 12%. Using stats like these can help management to improve service and enhance business.  

Overall, it was an excellent data-set for learning how to extract data and pull all kinds of stats, how to chop and change data, and to visualize and plot data.



## 8. **Bibliography**

https://seaborn.pydata.org/tutorial 

https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html

https://numpy.org/devdocs/user/quickstart.html 

https://www.tutorialspoint.com/seaborn/seaborn_pair_grid.htm

https://www150.statcan.gc.ca/n1/edu/power-pouvoir/ch12/5214889-eng.htm 







