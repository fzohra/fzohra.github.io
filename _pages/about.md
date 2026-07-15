---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. Student in Computer Science at the King Abdullah University of Science and Technology (KAUST), where I am advised by [Prof. Bernard Ghanem](https://www.bernardghanem.com/) and [Prof. Chen Zhao](https://zhao-chen.com/) in the Image and Video Understanding Lab [IVUL](https://ivul.kaust.edu.sa/).

I research Deep Learning in Computer Vision, primarily on Video Understanding, Large Vision-Language Models, Vision-Text Alignment, and Temporal Action Detection.

Prior to my doctoral studies, I completed my undergrad in Computer Science at The University of Texas at Austin and worked as a Computer Scientist at Adobe in Seattle.

## Recent Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

