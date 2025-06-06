---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: RICHARD C POWELL III
description: Cyber | Data | AI | Linguistics | Research
description2: San Antonio, TX
---

# Nice to meet you, I'm Richard


<ul class="responsive-container">
  <li class="item">
    <img src="/assets/headshot.jpg" alt="My Headshot. June 2024." title="My Headshot. June 2024." class="card-image">
  </li>
  <li class="item">
    <div class="contact-grid">
      <div class="square"><div class="social-button"><a class="type1" href="https://linkedin.com/in/richard-c-powell-iii/"><i class="fa-brands fa-linkedin-in"></i></a></div></div>
      <div class="square"><div class="social-button"><a class="type2" href="https://github.com/richardcpowelliii/"><i class="fa-brands fa-github"></i></a></div></div>
      <div class="square"><div class="social-button"><a class="type2" href="mailto:richardcpowelliii@gmail.com"><i class="fa-solid fa-envelope"></i></a></div></div>
      <div class="square"><div class="social-button"><a class="type3" href="tel:2109008313"><i class="fa-solid fa-phone"></i></a></div></div>
    </div>
  </li>
</ul>

I graduated from the University of Texas at San Antonio in May of 2025. I have a BS in Computer Science with a concentration in Cyber Security and a minor in Linguistics. I also happen to be looking for a job.

___
<br>

# Selected Projects

These are some of my favorite projects from the last couple years. Check them out!


___
## Undergrate Researcher, CONNNECT URE, University of Texas at San Antonio

Currently, I am working with Dr. Amanda Fernandez and UTSA's Vision AI Lab (VAIL) through an Undergraduate Reserach Experience funded by the Department of Energy's National Nuclear Security Administration. We are working on computer vision applications for nuclear materials science.

<a href="https://sites.google.com/view/amandafernandez/research/vision-ai-lab" class="btn">Vision AI Lab</a>

<br>

___
## Research Assistant, JUN Project, UT Health San Antonio

In the Spring of 2025, I worked as a research assistant with Dr. Allison Crawford on JUN, an online application with an integrated chatbot to help pregnant people on community supervision with self-efficacy. I helped run a pilot study of 60 participants, and we are in the process of publishing some papers about the study and the chatbot.

I will update this page when the work we are doing is published or otherwise released, but for now you can learn more about the JUN project from their landing page:

<a href="https://uthscsa.edu/nursing/outreach/jun-research" class="btn">JUN Research</a>

<br>

___
## Civic Tech Scholars Internship: Pothole Project

In June of 2024, I landed a 10-week internship with the Better Futures Institute, a small non-profit focused on civic tech and policy research.

We completed a data science project for the City of San Antonio. They gave us data on ~68,000 potholes over 8 years, to which we added weather, soil, watershed, floodplain, and lots of other data using QGIS.

After doing a lot of initial analysis, I decided to push myself a bit and try to predict pothole occurence at the street level. This involved: making ~18,000 street segments of about equal length; joining the potholes and other data to those segments for each year; training a classification model to predict whether a segment would have *any* potholes; training dozens of regression models to predict *how many* potholes these segments would have; tuning the regression model to more accurately predict outliers (i.e., those with the most potholes); and checking for accuracy up to May 2024.

It was quite a challenge and a whole lot of fun, but unfortunately I am not allowed to share the data because it belongs to the city. Here's a redacted screenshot instead showing what the results looked like:

<img src="/assets/pothole_results_redacted.png" alt="A redacted screenshot of an excel spreadsheet containing the results of my pothole predictions. August 2024" title="A redacted screenshot of an excel spreadsheet containing the results of my pothole predictions. August 2024" class="project-image"/>

<br>

___
## Linguistics Website

Throughout my Introduction to Linguistics course, I made a website using GitHub Pages to hold and present about a dozen articles about different topics.

I also learned D3.js and made some pretty nice dynamic visualizations!

The first is a responsive tree of the Sino-Tibetan language group, containing 458 languages in 100 subgroups. Hovering over a language will show its location, and clicking on it will send you to its listing on Ethnologue with some more information.

The second is a visualization of hyponym/hypernym relationships in words from the Open English wordnet. It has ~85,000 words and ~159,000 relationships. Hovering over a word will show its definition, and clicking it will make it the new center of the graph.

<ul class="responsive-container">
  <li class="item">
    <a href="https://jespytall.github.io/cel3/panel1/sino-tibetan_tree">
      <img src="/assets/linguistics_visualization_2.png" alt="A screenshot of my Sino-Tibetan language group visualization. October 2024." title="A screenshot of my Sino-Tibetan language group visualization. October 2024." class="project-image"/>
	</a>
  </li>
  <li class="item">
    <a href="https://jespytall.github.io/project/tree">
	  <img src="/assets/linguistics_visualization_1.png" alt="A screenshot of my hyponym visualization. November 2024." title="A screenshot of my hyponym visualization. November 2024." class="project-image"/>
	</a>
  </li>
</ul>

You can click one of the above photos to check out the visualizations. Both of them also support panning, and zooming.

You can also visit the main site here:  

<a href="https://jespytall.github.io/" class="btn">Learning Celebrations</a>

<br>

___
## Rowdyhacks IX Second Place Project

For Rowdyhacks IX in February 2024, My team and I created a web dashboard to determine which days would be cheapest to travel to San Antonio, given a month and duration of stay.

We trained ARIMA models on 4 years of historical airline prices, and we added average hotel stay prices, holidays and local events, and a busyness index for Six Flags.

It ended up winning us second place, and we were pretty proud of both the idea and the execution.

<img src="/assets/RHIX_Pic_2.png" alt="My team and me winning second place at Rowdyhacks IX. February 2024." title="My team and me winning second place at Rowdyhacks IX. February 2024." class="project-image"/>

Check it out here*:  

<a href="https://deadpooldatesa.streamlit.app/" class="btn">PerfectDateSA</a>

**Note: Streamlit seems to have updated since we made this and looks like it broke some of the formatting. It looked nice when we presented it, I promise!*

<br>

___
## Developing AI Tools for Children

During the spring 2024 semester, I was lucky enough to get into an independent study class with the department chair, Dr. Fred Martin. Myself and 11 other researchers worked in pairs to create tools that would teach AI concepts to middle-school children.

My partner and I created a web-based game with a where children were given a character and told to serve them videos based on what they might like best. At the end, results were shown and compared to the average, and we were able to lead a discussion about how out assumptions and implicit biases affect the technologies we make and use.

The game was quite simple, but it was engaging and led to productive discussion questions afterward. We are now in the process of editing and submitting our paper to conferences.

You can try the game here:  

<a href="https://vidmatch.pythonanywhere.com/" class="btn">VidMatch</a>

<br>

