---
layout: post
title:  State Law V. Gun Death
image:  '/images/Project6.png'
tags:   [UI Design, Programming]
description: Visualizing the amount of gun-related state laws versus their subsequent gun death rate
---
### Project Summary
Firearm legislation has been an important topic of discussion in politics. However, as more media coverage is devoted to the topic, there is a higher chance of the information to be biased due to one’s emotion, political affiliation, etc.

This data visualization aims to showcase the correlation between the amount of gun-related state laws and their subsequent gun death rate in an understandable and easily digestible way.

**Project Type** <br>
Academic coding project with a classmate

**Project Duration** <br>
4 weeks (Feburary - March 2018)

**My Role** <br>
For this project, I pair-programmed with a classmate in creating a data visualization using the programming language R and interactive R Shiny program.

### Data Visualization
In order to create this visualization, data from two different sources were used: Centers for Disease Control and Prevention (CDC) and a State Firearm Law Database by Dr. Michael Siegel. Using the programming language R, different sets of data were simplified, joined, and filtered to draw correlational data between the number of state firearm legislation and the gun related death tolls/rates of each state. The R Shiny program allowed us to present the data in an easily understandable and interactive way.

![Home Page]({{site.baseurl}}/images/vis-home.png)

![All States Page]({{site.baseurl}}/images/vis-1.png)

![By States Page]({{site.baseurl}}/images/vis-2.png)

![Our Interpretation Page]({{site.baseurl}}/images/vis-3.png)

The interactive dashboard can be accessed by clicking [**here**](https://deroun.shinyapps.io/StateLawsVGunDeath/). Visit the [**Github page**](https://github.com/DeRoun/StateLawsVGunDeath) for more details as well.

### Results
Based on data collected from both the CDC and the States Firearms Law Database, as well as the data presented in this application, we concluded that the number of state firearm laws does have an impact on that state’s firearm related death rate with a correlation coefficient of - 0.64. According to our data interpretation, states with a greater number of firearm laws are more likely to have a lower firearm related death rate.