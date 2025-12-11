---
layout: archive
title: "projects"
permalink: /projects/
author_prfile: true

---
# this is the landing page of projects
 
See below the list of work in progress
===
 <ul> {% include base_path %}
  {% for post in site.projects %} 
   {% include archive-single.html}
    {% endfor %} </ul>