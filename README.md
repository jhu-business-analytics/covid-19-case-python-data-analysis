# Data Analytics for Crisis Management using Covid-19 Data

## Data Analysis with Covid-19 Data

Even though we're using a new tool to conduct data analysis, we'll still want to use our same business analytics process to solve problems:

1. __Business Question__: what's our need or pain point? what do we want to figure out (big-picture) that might not be associated with metrics at this point?
2. __Data Question__: what data sources do we have that might hlep us answer this question? what metrics can help us figure out if we're on the right track to a feasible recommendation or proposal? what methods or metrics do other similar organizations/institutions/industries use to answer related questions?
3. __Data Answer__: calculate metrics, trends, models and evaluate the numerical results. what do these calculations and models tell us from a statistical perspective? how "good" are our models?
4. __Business Answer__: what do these numbers and data visualizations mean for someone not familar with statistics or the data in general? how do we relate these numbers back to answering (at least a part of) the original business question? what additional information do we need or what are the next steps to solving this?

Businesses in all industries have had to make quick decisions on hiring and firing employees, setting up remote work availability, ramping up or taming down production, and providing additional services (such as distributing free meals) in a matter of days without much information. What can we learn from what people have done so far and how this relates to their busines or city characteristics (demographics, socioeconomics status, business/people population, number of people per capita who've been tested positive for Covid-19, etc.) to better prepare for additional restrictions and recommendations or to prepare for future crisis scenarios?

## 1. Business Question
__*What kinds of resources and support do municipalities need to better manage citizens, services, and other organizational requirements during the covid-19 pandemic?*__

This question is probably too broad and multi-faceted for us to answer in a way that's useful for whoever needs to be informed, but this might be an example of an initial question that someone might ask, especially with so much uncertainty surrounding the pandemic. 

Let's explore some general data sets related to Covid-19, cases, recovery, mortality, restaurant use, and work from home policies to help us better understand the situation and perhaps develop a clearer business question for a more focused business solution. 

## 2. Data Question
__*What data sets have accurate and reliable data that we can use to help us answer any business questions, and what metrics do we need to keep track of and calculate to help answer this?*__

We'll first work with the open data set from the [Johns Hopkins Center for Systems Science and Engineering](https://systems.jhu.edu/), who made and maintains the [coronavirus covid-19 global cases dashboard](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6).

We'll use Python in the IDE (Integrated Development Environment--essentially where we can write and execute code) [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) for our initial work with Python. This is free to use (up to a certain RAM and Disk space), but you will need to download this in your Google Drive account. The markdown text cells are very similar to the markdown language used in GitHub repository markdown files, but there are some minor changes, outlined [here](https://colab.research.google.com/notebooks/markdown_guide.ipynb#scrollTo=tPqPXAKKkzaM).

We'll work through this Colab notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZA7-VpFHMFwej0JArcBwh8OkxjQ9-U_0)

or, you can look through this Colab notebook to find the executed code: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zClEc4YwwmQcxYKtTVT5YgqHVKn2GSqJ)

## 3. Data Answer
Here, we're mainly exploring some big-picture data findings to gain a baseline understanding of how the novel coronavirus spreads, and to see if we can find any interesting trends to note in global spread of the virus. 

We create a bar chart that shows the total number of global Covid-19 cases to date:
![alt text](https://github.com/jhu-business-analytics/covid-19-case-python-data-analysis/blob/master/covid19-global-cases-march26.png)

and then we break down the chart to show the increase in cases by country in line graphs:
![alt text](https://github.com/jhu-business-analytics/covid-19-case-python-data-analysis/blob/master/covid19-country-cases-march26.png)

This also allows us to manipulate our chart to look at specific countries individually or with other selected countries, and to zoom into specific time ranges. The HTML file for the line chart is in this repository saved as [covid19_global_cases_line.html](https://github.com/jhu-business-analytics/covid-19-case-python-data-analysis/blob/master/covid19_global_cases_line.html).

We can use this html file (or graph within our notebook) to further explore our data and share with others:
![alt text]()

## 4. Business Answer
