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

**SelvaBox: A high-resolution dataset for tropical tree crown detection**  
Hugo Baudchon, **Arthur Ouaknine**, Martin Weiss, Mélisande Teng, Thomas R. Walla, Antoine Caron-Guay, Christopher Pal, Etienne Laliberté.  
*ArXiv 2025*  
[[paper](https://arxiv.org/abs/2507.00170)][[code CanopyRS](https://github.com/hugobaudchon/CanopyRS)][[code geodataset](https://github.com/hugobaudchon/geodataset)][[dataset](https://huggingface.co/datasets/CanopyRS/SelvaBox)]  

**Bringing SAM to new heights: Leveraging elevation data for tree crown segmentation from drone imagery**  
Mélisande Teng, **Arthur Ouaknine**, Etienne Laliberté, Yoshua Bengio, David Rolnick, Hugo Larochelle.  
*ArXiv 2025*  
[[paper](https://arxiv.org/abs/2506.04970)][code TBA]  

**GreenHyperSpectra: A multi-source hyperspectral dataset for global vegetation trait prediction**  
Eya Cherif, **Arthur Ouaknine**, Luke A. Brown, Phuong D. Dao, Kyle R. Kovach, Bing Lu, Daniel Mederer, Hannes Feilhauer, Teja Kattenborn, David Rolnick.  
*ArXiv 2025*  
[paper TBA][[code](https://github.com/echerif18/HyspectraSSL)][[dataset](https://huggingface.co/datasets/Avatarr05/GreenHyperSpectra)]  

**FoMo: Multi-Modal, Multi-Scale and Multi-Task Remote Sensing Foundation Models for Forest Monitoring**  
Nikolaos Ioannis Bountos, **Arthur Ouaknine**, Ioannis Papoutsis, David Rolnick.  
*AAAI 2025*  
[[paper](https://arxiv.org/abs/2312.10114)][[code and data](https://github.com/RolnickLab/FoMo-Bench)]  

**Tree semantic segmentation from aerial image time series**  
Venkatesh Ramesh, **Arthur Ouaknine**, David Rolnick.  
*Environmental Data Science 2025*  
[[paper](https://arxiv.org/abs/2407.13102)]  

**OpenForest: A data catalogue for machine learning in forest monitoring**  
**Arthur Ouaknine**, Teja Kattenborn, Etienne Laliberté, David Rolnick.  
*Environmental Data Science 2024*  
[[paper](https://arxiv.org/abs/2311.00277)][[code and data](https://github.com/RolnickLab/OpenForest)]  


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

## PhD thesis

**Deep learning for radar data exploitation of autonomous vehicle**  
**Arthur Ouaknine**  
*Institut Polytechnique de Paris, Télécom Paris, 2022*  
[[Thesis](https://arxiv.org/abs/2203.08038)]  