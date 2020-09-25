# **US Political Climate & COVID-19**

---

This is a topic chosen for Project 5 for the Metis Data Science Bootcamp - Summer 2020 Cohort.

## Context

With the presidential race happening at the tail-end of 2020, the COVID-19 pandemic came at an interesting time. The Trump administration has made a number of decisions in response to it, some of those decisions being considered favorable or unfavorable by the American Public. With Trump hoping for re-election, it's a fair question to ask how his administration's handling of the pandemic will affect his voting.

## Objective

- Examine how Trump's approval ratings have changed in response to his handling of COVID-19

- See if different political views correspond to higher or lower rates, using SHAP feature importance to view classification impact from COVID-19 cases per capita.

- Forecast the 2020 election

## Findings
- President Trump’s national approval ratings have only slightly gone down with COVID-19’s development
- Counties’ COVID-19 case rates are not a strong indicator of political views
- Joe Biden is currently(9/15/2020) the likely winner of the 2020 US election

# Methodology

## Gathering data:


COVID-19 Data and US population data by county from [usafacts.org](https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/)

Trump Approval polling data from [FiveThirtyEight](https://projects.fivethirtyeight.com/polls/)

2016 Election data from [Opendatasoft](https://public.opendatasoft.com/explore/dataset/usa-2016-presidential-election-by-county/export/?disjunctive.state)

Biden-Trump polling data from [The Economist](https://projects.economist.com/us-2020-forecast/president)


* [Full data and analysis](data_and_analysis)
  * [Classification and SHAP](data_and_analysis/Project_5_-_Classification_and_SHAP.ipynb)
  * [COVID-19 Forecasting](data_and_analysis/Project_5_-_COVID-19_Forecasting.ipynb)
  * [Trump Approval Forecasting](data_and_analysis/Project_5_-_Trump_Approval_Forecasting.ipynb)
  * [State Poll Forecasting](data_and_analysis/Project_5_-_State_Poll_Forecasting.ipynb)
* Presentation Deck
  * [PDF version](presentation/JJoseph_Grovers_-_Project_5_-_Metis_-_COVID-19's_Impact_on_the_2020_Election.pdf.zip)
  * [Google Slides version](https://docs.google.com/presentation/d/1grTQekUg5QMcgZkKwHjAaX3ndhNPCObpMhiw25rp0gQ/edit?usp=sharing)
  * [PPT version](presentation/Joseph_Grovers_-_Project_5_-_Metis_-_COVID-19's_Impact_on_the_2020_Election.pptx.zip)

### [Joseph Grovers GitHub](https://github.com/josephgrovers)

## Technologies Used

* Jupyter Notebook

* Python

* Pickle

* Matplotlib

* Seaborn

* SKLearn

* Numpy

* datetime

* fbprophet

* Google Slides