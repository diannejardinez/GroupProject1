### The Effect of Climate Change on The Great Barrier Reef Analysis

Team: Aastha Arora, Alan Franzen, Dianne Jardinez

[Presentation](https://docs.google.com/presentation/d/12Ht8ZEcmuWUNDNb-ccjsUEraP6oKfDfq5JlL08IDAG4/edit?usp=sharing) (Google slides)(Updated)


#### Project description
We are uncovering the effects of global climate change on the Australian Great Barrier Reef.

Looked at historical trends in Sea Surface Temperature(SST)°C and the economic effects on tourism consumption near the Great Barrier Reef.  

The project imports satellite remote sensing measurement data for Northern GBR and Central GBR and analyzes the effect on increased Sea Surface Temperature (SST) on Coral Bleaching.

Corals experience thermal stress when the SST is 1°C warmer than the highest monthly mean temperature and the bleaching Threshold is 1° C more than max average month temperature.

We needed some way to measure not only how far the temperature is above the threshold, but how long it has stayed above that point, also known as the Degree Heating Weeks(DHW). The DHW shows how much heat stress has accumulated in an area over the past 12 weeks (3 months).

Wanted to see if these changes in SST connected with a decrease in tourism consumption in North Tropical Queensland, Australia due to coral bleaching in the Great Barrier Reef.

### Questions for Research
How has changing sea surface temperature(SST) affected the frequency and intensity of coral bleaching at the Great Barrier Reef since 2000? For the last five years?

Has Australian Tourism Consumption near the Great Barrier Reef affected by coral bleaching during bleaching events?


### Datasets used
Google Maps(API), National Oceanic and Atmospheric Administration(NOAA), Australian Government: Tourism Research Australia

### Summarize findings
For Northern GBR:

We looked at historic trends in Sea Surface Temperature (SST) and Degree Heating Weeks from 2000-2019 in the Northern Great Barrier Reef station. There were high points in the average SST in 2010, 2013, and 2016 -There were low points in the average SST in 2006, 2011, 2014, and 2019.


For the low points, we looked at 2006 and 2014 and saw that no degree heating week values were more than 4 or 8 indicating that sea surface temperatures did not increase more than the Average Maximum Monthly Mean of 28.7 °C for very long.


For high points, we looked at 2010 and 2016 and saw that in 2016 only, the degree heating week values reached over 8 indicating the sea surface temperatures did increase more than the Average Maximum Monthly Mean of 28.7 °C for a long period of time. This would also mean that a widespread coral bleaching and marine mortality most likely occurred.



For Central GBR:

We calculated Daily SST data for the last 20 years but displayed that there was a noticeable increase during the years of 2000 to 2020.

Then we looked into the monthly max and average SST data and max degree heating week values for the past five years and saw a noticeable increase in SST in 2016, 2017, and 2020. 

We compared the last five years for Central GBR by doing one-way analysis of variance (ANOVA)test (assumed a 5% significance level) to determine whether there was a significant difference in average SST during the summer years of 2015-2016, 2016-2017, 2017-2018, 2018-2019, 2019-20 and found that that there was a variation of the average SST observed over these time periods.


For Northern and Central GBR:

We compared the SST data for the 2015-2020 during the summer months of December-March where our Null Hypothesis was that there was no statistical difference between the SST for Northern and Central GBR for the summer months. We did an Independent t-test (assumed a 5% significant level) and got a p-value of 6.52e-43 so we rejected the Null and accepted the Alternate Hypothesis that the SST at Northern GBR is different from the Central GBR.

For Australian State Tourism Consumption:

We obtained the annual aggregate statistics of the effect of consumption data in AUD in millions from three Australian states that border the Great Barrier Reef(New South Wales, Victoria, and Queensland) during 2007-2018. We found that New South Wales and Victoria have a positive slope in tourism consumption but that Queensland had fluctuations that coincide with high SST data.

When we looked further in Tropical North Queensland, an entry way for the Great Barrier Reef tourism, and where SSTs were high from 2015-2017 in the Northern and Central GBR there was a significant drop in dollar values for tourism consumption during the same time period.

We checked into a specific Great Barrier Reef station for good measure that was directly south of Tropical North Queensland, Davies Reef Station from 2015-2019 that collected maximum monthly SST data from 4 meters deep, and we saw that there were also high SSTs during the times of decreased tourism dollars in Tropical North Queensland.

---

### Guidelines for Project 1

This document contains guidelines, requirements, and suggestions for Project 1.

## Project Proposal

Before you start writing any code, your group should outline the scope and purpose of your project. This helps provide direction and prevent [scope creep](https://en.wikipedia.org/wiki/Scope_creep).

Write this as a brief summary of your interests and intent, including:

* The kind of data you'd like to work with/field you're interested in (e.g., geodata, weather data, etc.)

* The kinds of questions you'll be asking of that data

* Possible source for such data

In other words, write down what kind of data you plan to work with, and what kinds of questions you'd like to ask of it. This constitutes your Project Proposal/Outline, and should look something like this:

> Our project is to uncover patterns in criminal activity around Los Angeles. We'll examine relationships between types of crime and location; crime rates and times of day; trends in crime rates over the course of the year; and related questions, as the data admits.

## Finding Data

Once your group has written an outline, it's time to start hunting for data. You are free to use data from any source, but we recommend the following curated sources of high-quality data:

* [data.world](https://data.world/)

* [Kaggle](https://www.kaggle.com/)

* [Data.gov](https://www.data.gov)

* [Public APIs](https://github.com/abhishekbanthia/Public-APIs)

* [Awesome-APIs List](https://github.com/Kikobeats/awesome-api)

* [Medium APIs List](https://medium.com/@benjamin_libor/a-curated-collection-of-over-150-apis-to-build-great-products-fdcfa0f361bc)


## Data Cleanup & Analysis

With data in hand, it's time to tackle development and analysis. This is where the fun starts!

Inevitably, the analysis process can be broken into two broad phases: **Exploration & Cleanup** and **Analysis** proper.

As you've learned, you'll need to explore, clean, and reformat your data before you can begin to answer your research questions. We recommend keeping track of these exploration and cleanup steps in a dedicated Jupyter Notebook, both for organization's sake and to make it easier to  present your work later.

Similarly, after you've massaged your data and are ready to start crunching numbers, you should keep track of your work in a Jupyter Notebook dedicated specifically to analysis.

During both phases, **don't forget to include plots**! Don't make the mistake of waiting to build figures until you're preparing your presentation. Creating them along the way can reveal insights and interesting trends in the data that you might not notice otherwise.

We recommend focusing your analysis on techniques such as aggregation, correlation, comparison, summary statistics, sentiment analysis, and time series analysis.


## Presentation

After you've analyzed your data to your satisfaction, you'll put together a presentation to show off your work, explain your process, and discuss your conclusions.

This presentation will be delivered as a slideshow, and should give your classmates and instructional staff an overview of your work. PowerPoint, Keynote, and Google Slides are all acceptable for building slides.


- - -

### Copyright

Coding Boot Camp © 2017. All Rights Reserved.

