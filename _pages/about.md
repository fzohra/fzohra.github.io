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

## Events 2026
* August 31 - September 11: Will be attending [MLSS-2026](https://mlss2026.is.tuebingen.mpg.de/), Tübingen, Germany
* August 1 - November 30: Visiting Researcher at [HITSZ](http://global.hitsz.edu.cn/index_en.htm), Shenzen, China.
* February 9-11 : Poster at [RSAI](https://www.kaust.edu.sa/events/rsais26/) Symposium, KAUST

## Recent Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

