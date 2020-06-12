# Research Journal
## Table of Contents

|Date|Title|Page|
|:--|:--|--|
|5/23/20|[Selecting and Refining Research Topic: Exploring Past Projects](#selecting-and-refining-research-topic-exploring-past-projects)|3|
|5/31/20|[Choosing a Topic](#choosing-a-topic)|4|
|6/1/20|[Background Research](#background-research)|5|
|6/10/20|[Refining Research Question](#refining-research-question)|6|
|6/10/20|[Refining Research Question: Air Quality](#refining-research-question-air-quality)|7|
|6/10/20|[Refining Research Question: Fatality Rate and Air Pollution](#refining-research-question-fatality-rate-and-air-pollution)|8|

## Selecting and Refining Research Topic: Exploring Past Projects
### 5/23/20

Developing an Artificial Intelligence-Based Assistive Robot: A Novel Approach to Prevent Falling in Elderly People - 50826

Modeling Intersections as an Asymmetric Non-Zero Sum Game for Maximin Decision Theory and Traffic Flow Optimization - 50823

A Novel Program for the Detection and Translation of the ASL Alphabet through the Use of Deep Learning - 50814

## Choosing a Topic
### 5/31/20

Area of research interest: COVID-19 pandemic
Research Topic: the impact of widespread disease on pollution

3 questions about COVID-19:
 - How well-prepared is the average American household for the economic impact of COVID-19?
 - How closely does COVID-19's impact on pollution follow Kuznets Curve?
 - How has COVID-19 affected air quality?

What is the correlation between COVID-19 and the amount of air pollutants such as nitrogen dioxide or benzene?

I chose this question because I was wondering if human activity is the cause of pollution and whether decreasing human activity would have a significant or notable effect on the air quality. For example, in several cities in China, the amount of smog in the air forces people to wear masks. An upside of COVID-19 is that it has helped us conduct an experiment and its results can show a lot about how humans affect air quality. 

## Background Research
### 6/1/20

**Research Question:** What is the correlation between COVID-19 and air pollution?

<ins>**Keywords**</ins>:
 - COVID-19: *a mild to severe respiratory illness caused by a coronavirus*
 - Air Pollution - *the presence of harmful substances in the air*
 - Vehicular Emissions - *exhaust gases that come out of vehicle engines*

<ins>**Things I need to learn:**</ins>
 - different types of pollution
 - meaning of different measurements
	 - sample duration
	 - pollutant standard
	 - observation count
	 - observation percent
 - how air pollution data is measured
 - Python
	 - pandas
	 - maplotlib
	 - manim (maybe)

<ins>**Why my research is important**</ins>

The results of my research will reveal whether taking action will have an impact on the quality of the air. 

## Refine Research Question
### 6/10/20

Research Question: How have various social policies affected the quality of the air? What effect does air pollution have on the fatality rate of COVID-19?

Part 1:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Independent Variable:   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;different policies enacted by the government  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dependent Variable:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;air quality  
Part 2:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Independent Variable:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;air quality  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dependent Variable:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;COVID-19 fatality rate

<ins>**Social Policies**</ins>

These could be: 
 - state of emergency declared
 - stay-at-home order
 - banned gatherings

The dependent variable could easily be measured. I just have to decide what to observe. 

<ins>**How does air pollution affect the fatality rate of COVID-19?**</ins>

This is going to be a hard question to answer. The fatality rate cannot be accurate because the total confirmed cases depends on the testing capacity. 

## Refine Research Question: Measuring Air Quality
### 6/10/20

I will look at common air pollutants and see if COVID-19 has affected them at all. 

<ins>**Common Air Pollutants**</ins>

|Pollutant|Source|
|--|--|
|lead|leaded fuels, ore processing|
|sulfur dioxide|fossil fuels|
|PM<sub>2.5</sub>|energy production, natural sources|
|ozone|vehicular emissions|
|nitrogen dioxide|car emissions|
|carbon monoxide|burning fuels|
|benzene|crude oil, cigarette smoke, natural sources|

## Refining Research Question: Fatality Rate and Air Quality
### 6/10/20

<ins>**Inaccuracies of the Fatality Rate**</ins>

COVID-19 has infected many more people than have been confirmed. Asymptomatic cases make counting the total cases impossible. 

Compared to other diseases, COVID-19 is a lot harder to count. For example, with Ebola, a very small fraction of cases are asymptomatic, which makes getting accurate numbers a much less tedious task. 

<ins>**My Plan**</ins>

I will look at the more general trend of the fatality rate. I can use a logistic regression to obtain the best-fit line. With that line, I can see if there is a trend in the fatality rate. I will see if long-term exposure to air pollution has an effect on the fatality rate.

I will see if places with infamously-bad air pollution have higher fatality rates <ins>compared to neighboring regions with similar responses to the outbreak</ins>. 
