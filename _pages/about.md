---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🧑‍ About Me 

Dr. Pengcheng Fang received his Bachelor's degree from Shanxi University in China, followed by a Master's degree from Lancaster University. He completed his PhD at the University of Southampton.

After completing his master's degree, Dr. Fang worked in China as an algorithm engineer, focusing primarily on computer vision applications. He served as a research team lead at two publicly listed companies, where he led the development and deployment of several successful consumer-facing (C-end) and enterprise-level (B-end) AI projects. These real-world experiences provided him with deep insights into the practical challenges of applying machine learning at scale. Motivated by a strong interest in scientific research and innovation, he later resigned from industry and pursued a Ph.D. in the United Kingdom to further explore cutting-edge research in artificial intelligence.

Dr. Fang is currently engaged in several interdisciplinary research projects at the intersection of artificial intelligence and real-world applications. His work focuses on:

* Human motion generation, where he explores generative models and transformer-based architectures for producing realistic and controllable movements from textual or sensory inputs.

* Multimodal foundation models, aiming to unify visual, textual, and structural data for improved perception, understanding, and reasoning across domains.

* Multi-object tracking (MOT), particularly in complex and unconstrained environments, using deep tracking-by-detection methods and video transformers.

* Wildlife biometrics, focusing on animal identification and behavior analysis using computer vision, with an emphasis on non-invasive recognition of species such as donkeys in natural settings.

* Medical image reconstruction and segmentation, where he applies lightweight Mamba-based models and diffusion techniques to enhance MRI imaging and improve diagnostic accuracy.

* His research integrates model efficiency, representation learning, and real-world deployment concerns, with applications ranging from intelligent surveillance to conservation and healthcare.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Journal</div><img src='images/hiresnet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hi-ResNet: Edge Detail Enhancement for High-Resolution Remote Sensing Segmentation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10638169)

**Yuxia Chen**, **Pengcheng Fang**, Xiaoling Zhong, Jianhui Yu, Xiaoming Zhang, Tianrui Li

- The paper "Hi‑ResNet: Edge Detail Enhancement for High‑Resolution Remote Sensing Segmentation" proposes a novel segmentation network tailored for high-resolution remote sensing images. It introduces a funnel module for high-res semantic extraction and a multi-branch Information Aggregation (IA) module to capture multi-scale object variations. Additionally, a Class-agnostic Edge Aware (CEA) loss is designed to enhance boundary accuracy. The method achieves strong performance on benchmarks like LoveDA, Potsdam, and Vaihingen.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/mogo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MOGO: Residual Quantized Hierarchical Causal Transformer for High-Quality and Real-Time 3D Human Motion Generation](https://arxiv.org/pdf/2506.05952)

**Dongjie Fu**, **Tengjiao Sun**, **Pengcheng Fang**, Xiaohao Cai, Hansung Kim

- The paper “MOGO: Residual Quantized Hierarchical Causal Transformer for High‑Quality and Real‑Time 3D Human Motion Generation” presents MOGO, an autoregressive transformer designed for efficient, on‑the‑fly 3D motion synthesis. It features residual quantization and a hierarchical causal structure to balance fidelity and real-time responsiveness. The framework achieves state-of-the-art motion quality while enabling streaming generation. It’s validated on benchmark datasets, demonstrating both high quality and low latency performance.
</div>
</div>


# 📖 Educations
- *2024.07 - 2028.07 (now)*, PhD, University of Southampton, Southampton, UK.
- *2019.01 - 2020.11*, Master, Lancaster University, Lancaster, UK.
- *2014.09 - 2018.07*, Undergraduate, Shanxi University, Shanxi, China.

# 💬 Events
- *2024.07 - now*, Cooperated with The Isle of Wight Donkey Sanctuary on wildlife protection.
- *2023.06*, Invited talk at Greater Bay Area Industrial Expo.


# 💻 Working Experiences
- *2023.10 - 2024.03*, Thunder Software Technology Co., Ltd.
- *2022.07 - 2023.10*, Chengdu Guoxing Aerospace Technology Co., Ltd.
- *2021.03 - 2022.07*, NetThink Technology Group Co., Ltd.
