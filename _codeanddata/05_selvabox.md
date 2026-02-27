---
title: "SelvaBox: A high-resolution dataset for tropical tree crown detection"
excerpt: "<br/><img src='/images/selvabox_teaser.png' width=600px height=auto><br><br><br>"
collection: codeanddata
permalink: /codeanddata/selvabox
venue: "ICLR 2026"
---

[Hugo Baudchon](https://github.com/hugobaudchon), [Arthur Ouaknine](https://arthurouaknine.github.io/), Martin Weiss, Mélisande Teng, Thomas R. Walla, Antoine Caron-Guay, Christopher Pal, Etienne Laliberté

ICLR 2026  

---

<center><b>Abstract</b></center>

<div style="text-align: justify">
Detecting individual tree crowns in tropical forests is essential to study these complex and crucial ecosystems impacted by human interventions and climate change. However, tropical crowns vary widely in size, structure, and pattern and are largely overlapping and intertwined, requiring advanced remote sensing methods applied to high-resolution imagery. Despite growing interest in tropical tree crown detection, annotated datasets remain scarce, hindering robust model development. We introduce SelvaBox, the largest open-access dataset for tropical tree crown detection in high-resolution drone imagery. It spans three countries and contains more than 83,000 manually labeled crowns - an order of magnitude larger than all previous tropical forest datasets combined. Extensive benchmarks on SelvaBox reveal two key findings: (1) higher-resolution inputs consistently boost detection accuracy; and (2) models trained exclusively on SelvaBox achieve competitive zero-shot detection performance on unseen tropical tree crown datasets, matching or exceeding competing methods. Furthermore, jointly training on SelvaBox and three other datasets at resolutions from 3 to 10 cm per pixel within a unified multi-resolution pipeline yields a detector ranking first or second across all evaluated datasets. Our dataset, code, and pre-trained weights are made public. </div>

---

<img src='/images/selvabox_teaser.png' class="center">


The **FoMo-Bench** code and data, the **TalloS** dataset and the **FoMo-Net** code and pre-trained models are available on Github: [https://github.com/RolnickLab/FoMo-Bench](https://github.com/RolnickLab/FoMo-Bench)  

**SelvaBox dataset** is available on HuggingFace: [https://huggingface.co/datasets/CanopyRS/SelvaBox](https://huggingface.co/datasets/CanopyRS/SelvaBox)

**CanopyRS** repository (benchmark, inference, and training) is available on Github: [https://github.com/CanopyRS/CanopyRS](https://github.com/CanopyRS/CanopyRS)

**Geodataset** repository (geospatial data processing) is available on Github: [Benchmark, inference, and training](Benchmark, inference, and training)


If you find our paper, our code or our data useful for your research, please cite our [paper](https://openreview.net/forum?id=GH7z1RURL6):
```
@inproceedings{
baudchon2026selvabox,
title={SelvaBox: A high\nobreakdash-resolution dataset for tropical tree crown detection},
author={Hugo Baudchon and Arthur Ouaknine and Martin Weiss and M{\'e}lisande Teng and Thomas R. Walla and Antoine Caron-Guay and Christopher Pal and Etienne Lalibert{\'e}},
booktitle={The Fourteenth International Conference on Learning Representations},
year={2026},
url={https://openreview.net/forum?id=GH7z1RURL6}
}
```