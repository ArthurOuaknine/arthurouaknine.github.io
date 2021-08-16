---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

[Multi-View Radar Semantic Segmentation](https://arxiv.org/abs/2103.16214)  
[Arthur Ouaknine](https://arthurouaknine.github.io/), [Alasdair Newson](https://sites.google.com/site/alasdairnewson/), [Patrick Pérez](https://ptrckprz.github.io/), [Florence Tupin](https://perso.telecom-paristech.fr/tupin/), [Julien Rebut](https://scholar.google.com/citations?user=BJcQNcoAAAAJ&hl=fr)  
*ICCV 2021*  



[CARRADA Dataset: Camera and Automotive Radar with Range-Angle-Doppler Annotations](https://arxiv.org/abs/2005.01456)  
[Arthur Ouaknine](https://arthurouaknine.github.io/), [Alasdair Newson](https://sites.google.com/site/alasdairnewson/), [Julien Rebut](https://scholar.google.com/citations?user=BJcQNcoAAAAJ&hl=fr), [Florence Tupin](https://perso.telecom-paristech.fr/tupin/), [Patrick Pérez](https://ptrckprz.github.io/)  
*ICPR 2020*