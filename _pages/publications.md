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


**Raw High-Definition Radar for Multi-Task Learning**  
Julien Rebut, **Arthur Ouaknine**, Waqas Malik, Patrick Pérez.  
*CVPR 2022*  
[[paper](https://arxiv.org/abs/2112.10646)][[code and data](https://github.com/valeoai/radial)]  



**Multi-View Radar Semantic Segmentation**  
**Arthur Ouaknine**, Alasdair Newson, Patrick Pérez, Florence Tupin, Julien Rebut.  
*ICCV 2021*  
[[page](https://arthurouaknine.github.io/codeanddata/mvrss)][[paper](https://arxiv.org/abs/2103.16214)][[code](https://github.com/valeoai/MVRSS)][[poster](https://arthurouaknine.github.io/files/posters/ICCV2021_poster.pdf)]  


**CARRADA Dataset: Camera and Automotive Radar with Range-Angle-Doppler Annotations**  
**Arthur Ouaknine**, Alasdair Newson, Julien Rebut, Florence Tupin, Patrick Pérez.  
*ICPR 2020*  
[[page](https://arthurouaknine.github.io/codeanddata/carrada)][[paper](https://arxiv.org/abs/2005.01456)][[code](https://github.com/valeoai/carrada_dataset)][[dataset](https://arthurouaknine.github.io/codeanddata/carrada)][[poster](https://arthurouaknine.github.io/files/posters/ICPR2020_poster.pdf)]


---

## Thesis

**Deep learning for radar data exploitation of autonomous vehicle**  
**Arthur Ouaknine**  
[[Thesis](https://arxiv.org/abs/2203.08038)]  