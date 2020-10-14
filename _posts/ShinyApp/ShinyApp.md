---
title: "COVID-19 in Colombia & South Africa - R Shiny App"
description: |
  A data story of COVID-19 in Colombia & South Africa in an R Shiny Application.
author:
  - name: Rahul Bharadwaj
    url: https://rahul-bharadwaj.github.io/My-Portfolio/
    affiliation: Monash University
date: 10-16-2020
output:
  distill::distill_article:
    self_contained: false
---

![](Images/Covid.PNG)

# **Introduction -**

* This is a blog post describing an R Shiny Application that combines the work from the previous blogs [Covid-19 in Colombia (12 Sep 2020)](https://rahul-bharadwaj.netlify.app/posts/covid-19-col/) and [Covid-19 in South Africa (4 Sep 2020)](https://rahul-bharadwaj.netlify.app/posts/covid-19-sa/).

* This [Shiny Application](https://rahul-bharadwaj-mysore-venkatesh.shinyapps.io/shiny-assessment-rahul-bharadwaj/) is a dashboard of Covid-19 stats for the countries Colombia and South Africa. The purpose of this Shiny App is to make the explanation easy, interactive and concise in the form of a Web-App that can be shared and easily used. Interactive and UI-based data stories are more effective in conveying the explanations and involving the user completely.

There are three main tabs in the Shiny App that covers the data story/message to be conveyed to the reader.

* **Total Count Comparison:** Compares Total tests, cases, recoveries, and deaths till date in Colombia and South Africa.

* **Attribute Count Comparison:** Compares tests, cases, recoveries, and deaths as single attributes for both the countries.

* **Daily Counts:** Has a sub-menu for each country that explores the Daily Counts of tests, cases, recoveries, and deaths due to Covid-19.

* **Citation:** Contains references to R packages and Data Resource used for the analysis.

It has an easy to use interface and conclusions can be drawn by the reader based on their observations. Self-reflection is an important part of learning and gaining perspective about ourselves in terms of where we stand and what we can do to get better. As a part of this process, the following section describes my journey of self-reflection.

# **Self Review -**

### **What did I do well?**

It's always good to start with something that went well when going through a self-reflection process. So the first thing I would like to self-reflect upon is the things that I'm good at and did well.

* I consider myself creative and I'm happy with the fact that I have made a dashboard that is visually appealing. The unique part about the picture in the 'About' section is that I designed it myself to best reflect the content the reader can expect with a glance.
  
* As part of analyzing the Covid-19 situation in Colombia and South Africa, I have done a fairly decent job in conveying the stats clearly to the reader. The choice of graphs for a variable over time is precise and a time-line best describes this kind of data. There are bar plots used to directly compare the absolute counts of Tests, Cases, Recoveries, and Deaths in both the regions and gives a clear picture to the reader. Interactive plots help in assessing a variable at a particular point in time and this is made available which immerses the user and captures their complete attention.
  
* There is enough instructions embedded in the App to make sure the user has a clear idea on how to use it and learn from it.
  
### **What are some things I can improve on?**

Self-reflection on past mistakes and points that we can improve upon are as important as identifying what went well or what we did right. This process helps us learn better and be better than we already are.

* Implementation of a 'plotly' event would make the App more interactive and immersive for the user. Learning better use of handling 'plotly' data will be a point to improve upon. 

* Use of external styling files could further enhance the visual appeal of the App and overall user experience.

### **Some plausible things that can be added -**

Some of the plausible things that can be added to enhance the analysis and the data story conveyed through the App are as follows:

* The dataset can be extended with external data to reflect data of each state in the country to make a comparison of the regions in the country that were affected.

* Location data about the states can be used to make leaflet plots to visually display the parts of the country that were affected by the pandemic. Spatial Data is required to implement the same.

### **Data or Technology Limitations -**

Some things cannot be donw yet with the current data/technology and these limitations are as follows:

* Data Limitation - There is no spatial data consisting of longitude and latitude for states and this limits the analysis. The entire country will not be affected uniformly throughout and some visual representation of the worst-hit parts of the country can further enhance the scope of analysis. This can be done by combining the data with another external source of data with information on the statistics in each state.

* Technology Limitation - The data source, and thus the dashboard, are static and are not dynamic. Once the App is created, it will not reflect real-time data but limits to the day the code was created for the App. With a real-time data source, it makes the App more relevant for a longer duration of time after the publication. The files need to be knit often to make the App refelect the most recent data.