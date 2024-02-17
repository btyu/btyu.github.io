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

I am Botao Yu (余博涛), a first-year PhD student at [The Ohio State University](https://www.osu.edu/), advised by Prof. [Huan Sun](http://web.cse.ohio-state.edu/~sun.397/). Previously, I earned my Master's degree at [Nanjing University](https://www.nju.edu.cn/en/), advised by Prof. [Wei Hu (胡伟)](http://ws.nju.edu.cn/wiki/Wiki.jsp?page=Wei%20Hu).

My **research interest** includes <u>AI for Science (Chemistry)</u>, <u>NLP</u>, <u>AI music</u>, and <u>deep learning</u>.

# 🔥 News
- 2024.02: Check out [LlaSMol](#pub-llasmol), a series of LLMs that significantly outperform GPT-4 on chemistry tasks.
- 2023.11: Please check out [MMMU](#pub-mmmu), a Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI.
- 2023.08: Arrived at Columbus. My PhD journey officially starts 😋!
- 2023.05: Please check out [MuseCoco](#pub-musecoco), a text-to-music generation system.
- 2022.09: Our paper [Museformer](#pub-museformer) is accepted by NeurIPS 2022!

# 📝 Publication

## AI for Science

<span class='anchor' id='pub-llasmol'></span>
- [**Preprint 2024**] LlaSMol: Advancing Large Language Models for Chemistry with a Large-Scale, Comprehensive, High-Quality Instruction Tuning Dataset

  **Botao Yu**, Frazier N. Baker\*, Ziqi Chen\*, Xia Ning, Huan Sun &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (* equal contribution)

  [[Paper](https://arxiv.org/abs/2402.09391)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Page](https://osu-nlp-group.github.io/LLM4Chem/)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Dataset](https://huggingface.co/osunlp/LlaSMol-Mistral-7B)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Model](https://huggingface.co/osunlp/LlaSMol-Mistral-7B)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Code](https://github.com/OSU-NLP-Group/LLM4Chem)]


## NLP

<span class='anchor' id='pub-mmmu'></span>

- [**Preprint 2023**] MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI

  Xiang Yue, Yuansheng Ni, Kai Zhang, Tianyu Zheng, Ruoqi Liu, Ge Zhang, Samuel Stevens, Dongfu Jiang, Weiming Ren, Yuxuan Sun, Cong Wei, **Botao Yu**, Ruibin Yuan, Renliang Sun, Ming Yin, Boyuan Zheng, Zhenzhu Yang, Yibo Liu, Wenhao Huang, Huan Sun, Yu Su, Wenhu Chen

  [[Paper](https://arxiv.org/abs/2306.00110)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Code](https://github.com/MMMU-Benchmark/MMMU)]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[[Dataset](https://huggingface.co/datasets/MMMU/MMMU)]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Page](https://mmmu-benchmark.github.io)]

- [**EMNLP 2021**] Knowing False Negatives: An Adversarial Training Method for Distantly Supervised Relation Extraction

  Kailong Hao, **Botao Yu**, Wei Hu

  [[Paper](https://aclanthology.org/2021.emnlp-main.761)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Code](https://github.com/nju-websoft/fan)]

- [**APWeb-WAIM 2020**] Joint Reasoning of Events, Participants and Locations for Plot Relation Recognition

  Shengguang Qiu, **Botao Yu**, Lei Qian, Qiang Guo, Wei Hu

  [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-60259-8_51)]

## AI Music

<span class='anchor' id='pub-musecoco'></span>

- [**Preprint 2023**] MuseCoco: Generating Symbolic Music from Text

  Peiling Lu\*, Xin Xu\*, Chenfei Kang\*, **Botao Yu**\*, Chengyi Xing\*, Xu Tan, Jiang Bian &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (* equal contribution)

  [[Paper](https://arxiv.org/abs/2306.00110)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Code](https://github.com/microsoft/muzic/tree/main/musecoco)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Demo](https://ai-muzic.github.io/musecoco)]   

- [**Preprint 2023**] EmoGen: Eliminating Subjective Bias in Emotional Music Generation

  Chenfei Kang, Peiling Lu, **Botao Yu**, Xu Tan, Wei Ye, Shikun Zhang, Jiang Bian

  [[Paper](https://arxiv.org/abs/2307.01229)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Code](https://github.com/microsoft/muzic/tree/main/emogen)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Demo](https://ai-muzic.github.io/emogen)]

<span class='anchor' id='pub-museformer'></span>

- [**NeurIPS 2022**] Museformer: Transformer with Fine- and Coarse-Grained Attention for Music Generation

  **Botao Yu**, Peiling Lu, Rui Wang, Wei Hu, Xu Tan, Wei Ye, Shikun Zhang, Tao Qin, Tie-Yan Liu

  [[Paper](https://openreview.net/forum?id=GFiqdZOm-Ei)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Code](https://github.com/microsoft/muzic/tree/main/museformer)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Demo](https://ai-muzic.github.io/museformer)]

- [**ISMIR 2022**] MeloForm: Generating Melody with Musical Form Based on Expert Systems and Neural Networks

  Peiling Lu, Xu Tan, **Botao Yu**, Tao Qin, Sheng Zhao, Tie-Yan Liu

  [[Paper](https://arxiv.org/abs/2208.14345)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Code](https://github.com/microsoft/muzic/tree/main/meloform)] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [[Demo](https://ai-muzic.github.io/meloform)]


# 📖 Education
- 2023.08 - Now &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Columbus, USA

  PhD student in Computer Science and Engineering @ The Ohio State University

- 2019.09 - 2023.06 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Nanjing, China

  Master's student in Computer Science @ Nanjing University (南京大学)

- 2015.09 - 2019.06 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Dalian, China

  Undergraduate student in Software Engineering @ Dalian University of Technology (大连理工大学)

- 2012.09 - 2015.06 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Changsha, China

  High school student @ The High School Attached To Hunan Normal University (湖南师大附中)

# 💻 Internship
- 2021.04 - 2022.03 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Beijing, China
  
  Research intern @ Microsoft Research Asia (微软亚洲研究院)





---

*Last modified: Feb 16, 2024*