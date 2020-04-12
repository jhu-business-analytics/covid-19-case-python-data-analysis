# Python Data Analysis for COVID-19 Pandemic Crisis Management

The novel coronavirus disease (Covid-19) pandemic is an enormous and unprecedented challenge for all individuals, businesses, organizations, and governments. Available information about the virus characteristics, infection rate, mortality rate, and subsequent effects for businesses, schools, healthcare organizations, and governments, changes daily, which make quick and accurate crisis and data management processes even more valuable and necessary. We can take action to protect and help minimize the effects of the disease if we have systematic ways to quickly and objectively analyze data or other research and communicate these outcomes to the necessary decision-makers or to the public, which is challenging in a novel situation.

The [Stanford Human-Centered Artificial Intelligence](https://hai.stanford.edu/) center recently held a virtual conference to talk about the intersection of AI and Covid-19, where one speaker talked about the county-level needs summarized here:

![alt text](https://github.com/jhu-business-analytics/covid-19-case-python-data-analysis/blob/master/images_for_readme/county_needs_during_covid19.png)

There a lot of [uncertainty about predicting](https://fivethirtyeight.com/features/why-its-so-freaking-hard-to-make-a-good-covid-19-model/) how many cases and how many deaths might occur in the US, but what we can do it look at how prepared certain counties might be to handle an influx of infected patients, which might inform the kinds of resources that businesses might donate or send to different counties, or what kind of policies might be most effective in mitigating the spread of Covid-19.

## Business Question: Which US counties are the most vulnerable to the pandemic based on population characteristics and hospital bed availability?

We want to better understand which counties might be most vulnerable to a fast-growing infection rate so that those counties might be able to simultaneously implement social distancing policies that allow people to stay at home and still have access to essential items such as food and healthcare _and_ prepare healthcare workers and medical supplies for an influx of patients. 

## Data Question: What data and metrics can we use to show and monitor the COVID-19 pandemic in US Counties?

We’ll use data from the following sources to assess our business question: 
* [Johns Hopkins University Center for Systems Science and Engineering](https://github.com/CSSEGISandData/COVID-19) (COVID-19 case, death, recovered data)
* [New York Times](https://github.com/nytimes/covid-19-data) (COVID-19 US county-specific data)
* American Community Survey](https://data.census.gov/cedsci/table?q=United%20States&g=0100000US&tid=ACSDP1Y2018.DP05) (US county population data)
* [US Census](https://www.census.gov/geographies/reference-files/2018/demo/popest/2018-fips.html) (state and county geographic data)
* [Homeland Infrastructure Foundation-Level](https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals)(US hospital data)

This data is also available in this repository. 

In our Python Notebooks we’ll use the following packages to conduct our analysis:
```
pandas 1.0.3
numpy 1.81.1
plotly 4.60
```
We'll also work through this Colab notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ZA7-VpFHMFwej0JArcBwh8OkxjQ9-U_0)

or, you can look through this Colab notebook to find the executed code: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zClEc4YwwmQcxYKtTVT5YgqHVKn2GSqJ)

## 3. Data Answer
The steps for our data analysis are available in the following GitBook tutorials:

1. [Getting Started with Python and General Python Analysis with Google Colaboratory Notebooks](https://app.gitbook.com/@melanieshimano/s/python-data-analysis/)
1. [Merging Data and Creating Data Visualizations with Ploty in JupyterLab Notebooks](https://app.gitbook.com/@melanieshimano/s/merging-data-and-plotly-visualizations/)

The final notebooks from these tutorials are also available in this notebook:

## Business Answer: Which Counties Should be Most Cautious as the COVID-19 Pandemic spread across the US?

