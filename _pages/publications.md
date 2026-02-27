---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p style="margin-bottom: 2em;">My research focuses on computer vision and machine learning applied to remote sensing. More specifically, I am interested in multi-modal and multi-task deep learning for biodiversity applications. {% if author.googlescholar %}You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>{% endif %}</p>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<div class="section-header" style="margin-top: 3em;">
  <h2>Conferences and Journals</h2>
</div>

**SelvaMask: Segmenting Trees in Tropical Forests and Beyond**  
Simon-Olivier Duguay, Hugo Baudchon, Etienne Laliberté, Helene Muller-Landau, Gonzalo Rivas-Torres, **Arthur Ouaknine**.  
*ArXiv 2026*  
<a href="https://arxiv.org/abs/2602.02426" class="pub-link pub-link--paper">Paper</a>
<a href="https://github.com/hugobaudchon/CanopyRS" class="pub-link pub-link--code">Code CanopyRS</a>
<a href="https://github.com/hugobaudchon/geodataset" class="pub-link pub-link--code">Code geodataset</a>
<a href="https://huggingface.co/datasets/CanopyRS/SelvaMask" class="pub-link pub-link--dataset">Dataset</a>  

**SelvaBox: A high-resolution dataset for tropical tree crown detection**  
Hugo Baudchon, **Arthur Ouaknine**, Martin Weiss, Mélisande Teng, Thomas R. Walla, Antoine Caron-Guay, Christopher Pal, Etienne Laliberté.  
*ICLR 2026*  
<a href="https://arxiv.org/abs/2507.00170" class="pub-link pub-link--paper">Paper</a>
<a href="https://github.com/hugobaudchon/CanopyRS" class="pub-link pub-link--code">Code CanopyRS</a>
<a href="https://github.com/hugobaudchon/geodataset" class="pub-link pub-link--code">Code geodataset</a>
<a href="https://huggingface.co/datasets/CanopyRS/SelvaBox" class="pub-link pub-link--dataset">Dataset</a>  

**Bringing SAM to new heights: Leveraging elevation data for tree crown segmentation from drone imagery**  
Mélisande Teng, **Arthur Ouaknine**, Etienne Laliberté, Yoshua Bengio, David Rolnick, Hugo Larochelle.  
*NeurIPS 2025*  
<a href="https://arxiv.org/abs/2506.04970" class="pub-link pub-link--paper">Paper</a>  

**GreenHyperSpectra: A multi-source hyperspectral dataset for global vegetation trait prediction**  
Eya Cherif, **Arthur Ouaknine**, Luke A. Brown, Phuong D. Dao, Kyle R. Kovach, Bing Lu, Daniel Mederer, Hannes Feilhauer, Teja Kattenborn, David Rolnick.  
*NeurIPS 2025 (Dataset & Benchmark Track)*  
<a href="https://arxiv.org/abs/2507.06806" class="pub-link pub-link--paper">Paper</a>
<a href="https://github.com/echerif18/HyspectraSSL" class="pub-link pub-link--code">Code</a>
<a href="https://huggingface.co/datasets/Avatarr05/GreenHyperSpectra" class="pub-link pub-link--dataset">Dataset</a>  

**FoMo: Multi-Modal, Multi-Scale and Multi-Task Remote Sensing Foundation Models for Forest Monitoring**  
Nikolaos Ioannis Bountos, **Arthur Ouaknine**, Ioannis Papoutsis, David Rolnick.  
*AAAI 2025*  
<a href="https://arxiv.org/abs/2312.10114" class="pub-link pub-link--paper">Paper</a>
<a href="https://github.com/RolnickLab/FoMo-Bench" class="pub-link pub-link--code">Code and Data</a>  

**Tree semantic segmentation from aerial image time series**  
Venkatesh Ramesh, **Arthur Ouaknine**, David Rolnick.  
*Environmental Data Science 2025*  
<a href="https://arxiv.org/abs/2407.13102" class="pub-link pub-link--paper">Paper</a>  

**OpenForest: A data catalogue for machine learning in forest monitoring**  
**Arthur Ouaknine**, Teja Kattenborn, Etienne Laliberté, David Rolnick.  
*Environmental Data Science 2024*  
<a href="https://arxiv.org/abs/2311.00277" class="pub-link pub-link--paper">Paper</a>
<a href="https://github.com/RolnickLab/OpenForest" class="pub-link pub-link--code">Code and Data</a>  


**Raw High-Definition Radar for Multi-Task Learning**  
Julien Rebut, **Arthur Ouaknine**, Waqas Malik, Patrick Pérez.  
*CVPR 2022*  
<a href="https://arxiv.org/abs/2112.10646" class="pub-link pub-link--paper">Paper</a>
<a href="https://github.com/valeoai/radial" class="pub-link pub-link--code">Code and Data</a>  



**Multi-View Radar Semantic Segmentation**  
**Arthur Ouaknine**, Alasdair Newson, Patrick Pérez, Florence Tupin, Julien Rebut.  
*ICCV 2021*  
<a href="https://arthurouaknine.github.io/codeanddata/mvrss" class="pub-link pub-link--page">Page</a>
<a href="https://arxiv.org/abs/2103.16214" class="pub-link pub-link--paper">Paper</a>
<a href="https://github.com/valeoai/MVRSS" class="pub-link pub-link--code">Code</a>
<a href="https://arthurouaknine.github.io/files/posters/ICCV2021_poster.pdf" class="pub-link pub-link--poster">Poster</a>  


**CARRADA Dataset: Camera and Automotive Radar with Range-Angle-Doppler Annotations**  
**Arthur Ouaknine**, Alasdair Newson, Julien Rebut, Florence Tupin, Patrick Pérez.  
*ICPR 2020*  
<a href="https://arthurouaknine.github.io/codeanddata/carrada" class="pub-link pub-link--page">Page</a>
<a href="https://arxiv.org/abs/2005.01456" class="pub-link pub-link--paper">Paper</a>
<a href="https://github.com/valeoai/carrada_dataset" class="pub-link pub-link--code">Code</a>
<a href="https://arthurouaknine.github.io/codeanddata/carrada" class="pub-link pub-link--dataset">Dataset</a>
<a href="https://arthurouaknine.github.io/files/posters/ICPR2020_poster.pdf" class="pub-link pub-link--poster">Poster</a>


---

<div class="section-header" style="margin-top: 3em;">
  <h2>PhD Thesis</h2>
</div>

**Deep learning for radar data exploitation of autonomous vehicle**  
**Arthur Ouaknine**  
*Institut Polytechnique de Paris, Télécom Paris, 2022*  
<a href="https://arxiv.org/abs/2203.08038" class="pub-link pub-link--paper">Thesis</a>  