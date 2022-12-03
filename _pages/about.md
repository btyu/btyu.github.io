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

Hi, nice to meet you!

I am Botao Yu (余博涛), a Master's student of [Websoft Research Group](http://ws.nju.edu.cn) at [Department of Computer Science and Technology](https://www.nju.edu.cn/EN/7f/6b/c7136a163691/page.htm), [Nanjing University](https://www.nju.edu.cn/EN/main.htm), advised by Assoc. Prof.  [Wei Hu (胡伟)](http://ws.nju.edu.cn/wiki/Wiki.jsp?page=Wei%20Hu).

I also work with [Xu Tan (谭旭)](https://www.microsoft.com/en-us/research/people/xuta), [Peiling Lu (卢佩玲)](https://www.microsoft.com/en-us/research/people/peil), and [Rui Wang (王蕊)](https://www.microsoft.com/en-us/research/people/ruiwa) from [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia), and Asst. Prof. [Muhao Chen](https://muhaochen.github.io/) from [University of Southern California](https://www.usc.edu/).

My **research interest** includes <u>NLP</u>, <u>AI music</u>, and <u>deep learning</u>. I have experience in information extraction (event extraction, relation extraction), symbolic music generation and understanding, deep learning models (pretrained language models, Transformers, generative models, GNNs, etc.).

😋 I am looking for a PhD position for fall 2023.

# 📝 Publication

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images/thumbnails/museformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[<b>NeurIPS 2022</b>] Museformer: Transformer with Fine- and Coarse-Grained Attention for Music Generation


**Botao Yu**, Peiling Lu, Rui Wang, Wei Hu, Xu Tan, Wei Ye, Shikun Zhang, Tao Qin, Tie-Yan Liu

[[Paper](https://arxiv.org/abs/2210.10349/)]     [[Code](https://github.com/microsoft/muzic/tree/main/museformer/)]     [[Demo](https://ai-muzic.github.io/museformer/)]

To solve the long sequence modeling and music structure modeling problem in symbolic music generation, we propose Museformer, a Transformer variant that combines a fine-grained attention for learning the structure-related correlations and a coarse-grained attention for preserving other contextual information at  a low cost.

</div>
</div>

- [**ISMIR 2022**] MeloForm: Generating Melody with Musical Form Based on Expert Systems and Neural Networks

  Peiling Lu, Xu Tan, **Botao Yu**, Tao Qin, Sheng Zhao, Tie-Yan Liu

  [[Paper](https://arxiv.org/abs/2208.14345/)]     [[Code](https://github.com/microsoft/muzic/tree/main/meloform)]     [[Demo](https://ai-muzic.github.io/meloform/)]

- [**EMNLP 2021**] Knowing False Negatives: An Adversarial Training Method for Distantly Supervised Relation Extraction

  Kailong Hao, **Botao Yu**, Wei Hu

  [[Paper](https://aclanthology.org/2021.emnlp-main.761/)]     [[Code](https://github.com/nju-websoft/fan/)]

- [**APWeb-WAIM 2020**] Joint Reasoning of Events, Participants and Locations for Plot Relation Recognition

  Shengguang Qiu, **Botao Yu**, Lei Qian, Qiang Guo, Wei Hu

  [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-60259-8_51)]


# 📖 Education
- 2019.09 - Now &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Nanjing China

  Master's student in Computer Science @ Nanjing University (南京大学)

- 2015.09 - 2019.06 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Dalian China

  Undergraduate student in Software Engineering @ Dalian University of Technology (大连理工大学)

- 2012.09 - 2015.06 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Changsha China

  High school student @ The High School Attached To Hunan Normal University (湖南师大附中)

# 💻 Internship
- 2021.04 - 2022.03 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Beijing China
  
  Research intern @ Microsoft Research Asia (微软亚洲研究院)





---

*Last modified: December 3, 2022*