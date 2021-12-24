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


Raw High-Definition Radar for Multi-Task Learning
[Julien Rebut](https://scholar.google.com/citations?user=BJcQNcoAAAAJ&hl=fr), [**Arthur Ouaknine**](https://arthurouaknine.github.io/), Waqas Malik, [Patrick Pérez](https://ptrckprz.github.io/)  
*Preprint, under review*
[[paper](https://arxiv.org/abs/2112.10646)][[code and data](https://github.com/valeoai/radial)]  


Multi-View Radar Semantic Segmentation  
[**Arthur Ouaknine**](https://arthurouaknine.github.io/), [Alasdair Newson](https://sites.google.com/site/alasdairnewson/), [Patrick Pérez](https://ptrckprz.github.io/), [Florence Tupin](https://perso.telecom-paristech.fr/tupin/), [Julien Rebut](https://scholar.google.com/citations?user=BJcQNcoAAAAJ&hl=fr)  
*ICCV 2021*  
[[page](https://arthurouaknine.github.io/codeanddata/mvrss)][[paper](https://arxiv.org/abs/2103.16214)][[code](https://github.com/valeoai/MVRSS)][[poster](https://arthurouaknine.github.io/files/ICCV2021_poster)]  



CARRADA Dataset: Camera and Automotive Radar with Range-Angle-Doppler Annotations  
[**Arthur Ouaknine**](https://arthurouaknine.github.io/), [Alasdair Newson](https://sites.google.com/site/alasdairnewson/), [Julien Rebut](https://scholar.google.com/citations?user=BJcQNcoAAAAJ&hl=fr), [Florence Tupin](https://perso.telecom-paristech.fr/tupin/), [Patrick Pérez](https://ptrckprz.github.io/)  
*ICPR 2020*  
[[page](https://arthurouaknine.github.io/codeanddata/carrada)][[paper](https://arxiv.org/abs/2005.01456)][[code](https://github.com/valeoai/carrada_dataset)][[dataset](https://arthurouaknine.github.io/codeanddata/carrada)][[poster](https://arthurouaknine.github.io/files/ICPR2021_poster)]  