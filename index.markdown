---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Social Data Analysis and Visualization - Assignment 2
layout: default
---



## Introduction

Our investigation began by examining the prevalence of various crimes across different districts. We observed a significant concentration of drug/narcotic crimes in Tenderloin. Intrigued by this discovery, we delved deeper into the data in order to explore the potential underlying causes.

## Plot 1: Calendar Plot
Upon closer inspection of drug/narcotic crimes citywide, we uncovered a consistent downward trend. This trend is visually represented in the calendar plot.
The decreasing trend in drug/narcotic crimes in San Francisco between 2013 and 2017 can be attributed to the implementation of Proposition 47 in 2014, a measure that reclassified drug possession offenses from felonies to misdemeanors. This legislative change aimed to address overcrowding in prisons and shift the focus towards rehabilitation rather than incarceration. In San Francisco, law enforcement responded to Proposition 47 by scaling back efforts against drugs. This approach effectively tolerated public drug use, contributing to the overall decrease in drug-related crimes during the specified period (Lopez et al., 2024).

<div style="width: 100%; height: 400px; overflow-y: auto;">
  <img src="/assets/calendar_plot.png" alt="Large Image" style="width: 100%;">
</div>

## Plot 2: Map
Having first noticed the concentration of drug/narcotic crimes in Tenderloin, we wanted to explore the socio-economic status of the different police districts in San Francisco. We did some research, and ended up with placing the ten districts in five different buckets.

- **Low socio-economic status**
  - City central location with high amounts of poverty and homelessness.
    - Tenderloin

- **Lower-middle socio-economic status**
  - Economic challenges, but has been targeted for development and is changing.
    - Bayview
    - Ingleside

- **Middle socio-economic status**
  - Generally a strong community presence, with a culturally diverse area further gentrified than Bayview and Ingleside. These areas are more mixed when it comes to income.
    - Taraval
    - Mission

- **Upper-middle socio-economic status**
  - The more residential areas where mostly families live, with a mix of middle and high income. These areas have a more stable economic base than the lower buckets, but not necessarily the extreme wealth of the highest bucket.
    - Park
    - Richmond

- **High socio-economic status**
  - Mostly high-income areas in newly developed housing, home to some of the richest people in the city. These regions include areas like Pacific Heights, SoMa and parts of the Financial district, which are at least perceived as having the highest incomes in the city.

These buckets gave us a better way of understanding our data, not only from an income level but from other angles as well. When we mapped out the amount of drug/narcotics crime in each neighborhood on our map, we were astounded that Tenderloin had the lowest amount. We then considered the fact that Tenderloin is also the smallest area on the map, and did some research considering the population in each of our regions. We noticed that there was a big difference in the population between the police districts, where Tenderloin was by far the smallest. After normalizing our data to instead be drug/narcotic crime per resident in that district, the map looked completely different. The population we normalized to was data from 2020, and we normalized it in total, not per year. (Prison Policy Initiative, 2020)



<div style="display: flex; justify-content: center;">
  <iframe src="/assets/Map_Bokeh.html" frameborder="0" width="600" height="600"></iframe>
</div>

## Plot 3: Line Plot

In analyzing the crime statistics over time for different police districts, as reflected in the chart, we observe that the districts characterized by lower drug crime rates show stability over the years. The frequency of drug-related offenses within these areas remains consistently close to their mean values, suggesting a persistent level of drug activity without fluctuations.

However, in districts that have a higher rate of drug-related crimes, the variability in crime rates is notably more pronounced. This is particularly evident in the Tenderloin district, notorious for its issues with drug-related offenses and overall high crime rates. The chart reveals a peak in drug crime rates for Tenderloin around 2008, where the levels over twenty times higher when compared to Richmond, which represents the lower threshold. Tenderloin's high incidence of crime, coupled with the pronounced problems of drug abuse and overdoses, is illustrated in the line plot.

However, the apparent halving of crime rates in Tenderloin from 2008 to 2016 does not necesarrily suggest a reduction in drug usage. It is important to consider the context of San Francisco's evolving policy stance during this period, particularly regarding drug-related offenses. The city's pivot from a strategy of incarceration to one of rehabilitation signifies a broader policy shift. This tcould be the reason for the observations in the Tenderloin district, where there has been an increased tolerance for public drug consumption. Such policy changes can influence both the actual and reported rates of drug-related crimes, as law enforcement priorities shift and community policing strategies adapt to new directives.

This shift towards rehabilitation and harm reduction may contribute to a decline in reported drug-related crimes, despite the persistence of drug use in the community. As policing strategies change  the lower crime rates may reflect this reclassification of drug use within the legal framework, rather than an actual decrease in drug activity. Therefore, while the descending trend line for the Tenderloin district might suggest an improvement in the drug crime situation at a glance, a deeper analysis is required to understand the underlying dynamics of the situation.


<iframe src="/assets/Line_Bokeh.html" frameborder="0" width="800" height="400"></iframe>




## References:
Lopez, G., Katz, J. and Parlapiano, A. (2024) Can San Francisco solve its drug crisis? Five things to consider., The New York Times. Available at: https://www.nytimes.com/2024/01/31/upshot/san-francisco-drug-crisis.html (Accessed: 21 March 2024)

Prison Policy Initiative. (2020). San Francisco Police District Appendix - Where people in prison come from - California (2020). Prisonpolicy.org. https://www.prisonpolicy.org/origin/ca/2020/sanfrancisco_police.html

‌


## Contributions
We have structured the assginment so that everyone had one main part to focus on. As we had all done the exercises everyone had a good understanding of all the tasks.

|StudieNr |Contributions|
|-----|--------|
|s232047|Mainly plot 3        |
|s232058|Mainly plot 1        |
|s232046|Mainly plot 2        |