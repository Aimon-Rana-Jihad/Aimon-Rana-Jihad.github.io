---
layout: archive
title: "projects"
permalink: /projects/
author_prfile: true

---
# this is the landing page of projects
 
See below the list of work in progress
===
  <ul>{% for post in site.projects reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## list
<h2>Remote Sensing Classification (Fatikchhari)</h2>

<div class="project-item">
    <h3>Supervised Classification Map</h3>
    <img src="supervised.png" alt="Supervised Map" style="width:100%; max-width:700px; margin-bottom:20px;">
</div>

<div class="project-item">
    <h3>Unsupervised Classification Map</h3>
    <img src="unsupervised.png" alt="Unsupervised Map" style="width:100%; max-width:700px;">
</div>
