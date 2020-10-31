---
layout: archive
title: "Publications And Research"
permalink: /publications/
author_profile: true 
classes: wide
---
<font size=2>*Clicking on any of the links below will redirect you to the abstract and details of my contributions.<br/><br/></font>

# Research Interests 
<font size=4><strong>Multi-agent Reinforcement Learning , Human-in-the-Loop AI, Machine Perception, Deep Learning </strong><br/><br/></font>


<!-- Here are some of the research projects I was fortunate to work on!  -->
{% include base_path %}

# Publications 
{% for post in site.publications reversed %}
  {% if post.id contains 'publication_' %}
  
    {% include archive-single.html %} 
  {% endif %}
{% endfor %}



# Research 
{% for post in site.publications reversed %} 
    {% if post.id contains 'research_' %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
