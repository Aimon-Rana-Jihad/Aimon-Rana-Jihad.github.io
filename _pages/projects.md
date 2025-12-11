---
layout: archive
title: "projects"
permalink: /projects/
author_prfile: true

---
# this is the landing page of projects
 

 {% include base_path %}
  {% for iteam in site.projects %} 
   {% include archive-single.html type="grid" %}
    {% endfor %}