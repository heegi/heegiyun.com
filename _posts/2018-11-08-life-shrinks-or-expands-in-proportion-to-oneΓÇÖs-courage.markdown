---
layout: post
title:  State Law V. Gun Death
image:  '/images/Project6.png'
tags:   [UI Design, Programming]
description: Visualizing the amount of gun-related state laws versus their subsequent gun death rate
---
## Overview
This *4-week long* academic project aimed to showcase the correlation between the amount of gun-related state laws and their subsequent gun death rate in an understandable and easily digestible way.

**My Role** <br>
I pair-programmed with a classmate in creating a data visualization using the programming language R and interactive R Shiny program.

### Data Visualization
Data from Centers for Disease Control and Prevention (CDC) and a State Firearm Law Database by Dr. Michael Siegel were used to create the interactive dashboard. The two different sets of data were simplified, joined, and filtered to draw correlations between the number of state firearm legislation and the gun related death tolls/rates of each state. The R Shiny program allowed us to present information in a more user-friendly way.

![Home Page]({{site.baseurl}}/images/vis-home.png)

![All States Page]({{site.baseurl}}/images/vis-1.png)

![By States Page]({{site.baseurl}}/images/vis-2.png)

![Our Interpretation Page]({{site.baseurl}}/images/vis-3.png)

The entire interactive dashboard can be accessed by clicking [**here**](https://deroun.shinyapps.io/StateLawsVGunDeath/). <br>
Visit the [**Github**](https://github.com/DeRoun/StateLawsVGunDeath) page for more details as well.

### Results
Based on data collected from both the CDC and the States Firearms Law Database, as well as the data presented in this application, we concluded that the number of state firearm laws DOES have an impact on the state’s firearm related death rate with a moderate correlation (*r= -0.64*). According to our data interpretation, states with a greater number of firearm laws are more likely to have a lower firearm related death rate.