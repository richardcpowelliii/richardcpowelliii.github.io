---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: RICHARD C POWELL III
description: Cyber | Data | AI | Linguistics | Research
description2: San Antonio, TX
---

# **Nice to meet you, I'm Richard**


<div style="text-align: center;">
	<img src="/assets/headshot.jpg" style="width: 75%;" alt="My headshot. June 2024">
</div>

I am a Senior at the University of Texas at San Antonio studying Computer Science with a concentration in Cyber Security and a minor in Linguistics. I also happen to be looking for a job.

Below are some of my favorite projects from the last couple years. Check them out!

___
<br>

# **Projects**

___
## **Civic Tech Scholars Internship: Pothole Project**

In June of 2024, I landed a 10-week internship with the Better Futures Institute, a small non-profit focused on civic tech and policy research.

We completed a data science project for the City of San Antonio. They gave us data on ~68,000 potholes over 8 years, to which we added weather, soil, watershed, floodplain, and lots of other data using QGIS.

After doing a lot of initial analysis, I decided to push myself a bit and try to predict pothole occurence at the street level. This involved: making ~18,000 street segments of about equal length; joining the potholes and other data to those segments for each year; training a classification model to predict whether a segment would have *any* potholes; training dozens of regression models to predict *how many* potholes these segments would have; tuning the regression model to more accurately predict outliers (i.e., those with the most potholes); and checking for accuracy up to May 2024.

It was quite a challenge and a whole lot of fun, but unfortunately I am not allowed to share the data because it belongs to the city. Here's a redacted screenshot instead showing what the results looked like:
![A redacted screenshot of an excel spreadsheet containing the results of my pothole predictions. August 2024](/assets/pothole_results_redacted.png "A redacted screenshot of an excel spreadsheet containing the results of my pothole predictions. August 2024")

<br>

___
## **Linguistics Website**

Throughout my Introduction to Linguistics course, I made a website using GitHub Pages to hold and present about a dozen articles about different topics.

I also learned D3.js and made some pretty nice dynamic visualizations!

You can visit the site here:  

<a href="https://jespytall.github.io/" class="btn">jespytall.github.io</a>

<br>

___
## **Rowdyhacks IX Second Place Project**

For Rowdyhacks IX in February 2024, My team and I created a web dashboard to determine which days would be cheapest to travel to San Antonio, given a month and duration of stay.

We trained ARIMA models on 4 years of historical airline prices, and we added average hotel stay prices, holidays and local events, and a busyness index for Six Flags.

It ended up winning us second place, and we were pretty proud of both the ideas and the execution.

Check it out here*:  

<a href="https://deadpooldatesa.streamlit.app/" class="btn">deadpooldatesa.streamlit.app</a>

**Note: Streamlit seems to have updated since we made this and looks like it broke some of the formatting. It looked nice when we presented it, I promise!*

<br>

___
## **Developing AI Tools for Children**

During the spring 2024 semester, I was lucky enough to get into an independent study class with the department chair, Dr. Fred Martin. Myself and 11 other researchers worked in pairs to create tools that would teach AI concepts to middle-school children.

My partner and I created a web-based game with a where children were given a character and told to serve them videos based on what they might like best. At the end, results were shown and compared to the average, and we were able to lead a discussion about how out assumptions and implicit biases affect the technologies we make and use.

The game was quite simple, but it was engaging and led to productive discussion questions afterward. We are now in the process of editing and submitting our paper to conferences.

You can try the game here:  

<a href="https://vidmatch.pythonanywhere.com/" class="btn">vidmatch.pythonanywhere.com</a>

<br>

