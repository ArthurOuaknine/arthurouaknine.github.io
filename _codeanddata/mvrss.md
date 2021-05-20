---
title: "Multi-View Radar Semantic Segmentation"
excerpt: "<br/><img src='/images/mvrss_teaser.png'>"
collection: codeanddata
permalink: /codeanddata/mvrss
---

[Arthur Ouaknine](https://arthurouaknine.github.io/), [Alasdair Newson](https://sites.google.com/site/alasdairnewson/), [Julien Rebut](https://scholar.google.com/citations?user=BJcQNcoAAAAJ&hl=fr), [Florence Tupin](https://perso.telecom-paristech.fr/tupin/), [Patrick Pérez](https://ptrckprz.github.io/)

Preprint under review, ArXiv 2021.

---

<center><b>Abstract</b></center>

<div style="text-align: justify">Understanding the scene around the ego-vehicle is key to assisted and autonomous driving. Nowadays, this is mostly conducted using cameras and laser scanners, despite their reduced performances in adverse weather conditions. Automotive radars are low-cost active sensors that measure properties of surrounding objects, including their relative speed, and have the key advantage of not being impacted by rain, snow or fog. However, they are seldom used for scene understanding due to the size and complexity of radar raw data and the lack of annotated datasets. Fortunately, recent open-sourced datasets have opened up research on classification, object detection and semantic segmentation with raw radar signals using end-to-end trainable models. In this work, we propose several novel architectures, and their associated losses, which analyse multiple “views” of the range-angle-Doppler radar tensor to segment it semantically. Experiments conducted on the recent CARRADA dataset demonstrate that our best model outperforms alternative models, derived either from the semantic segmentation of natural images or from radar scene understanding, while requiring significantly fewer parameters.</div>

---

The **code** and **pretrained models** are available on Github: [https://github.com/valeoai/MVRSS](https://github.com/valeoai/MVRSS)


If you find this code or the dataset useful for your research, please cite our [paper](https://arxiv.org/pdf/2103.16214.pdf):
```
@misc{ouaknine2021multiview,
      title={Multi-View Radar Semantic Segmentation},
      author={Arthur Ouaknine and Alasdair Newson and Patrick Pérez and Florence Tupin and Julien Rebut},
      year={2021},
      eprint={2103.16214},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```