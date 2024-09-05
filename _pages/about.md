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

My **research interest** includes <u>AI for Science (Chemistry)</u>, <u>LLMs</u>, <u>NLP</u>, <u>AI music</u>, and <u>deep learning</u>.

# 🔥 News
- 2024.09: Please check out [MMMU-Pro](#pub-mmmupro), an enhanced version of [MMMU](#pub-mmmu) featuring full-vision evaluation.
- 2024.07: Our paper [LlaSMol](#pub-llasmol) is accepted by COLM 2024!
- 2024.04: Our paper [MMMU](#pub-mmmu) is selected as Oral at CVPR 2024 (0.8%)!
- 2024.02: Please check out [LlaSMol](#pub-llasmol), a series of LLMs that significantly outperform GPT-4 on chemistry tasks.
- 2023.11: Please check out [MMMU](#pub-mmmu), a Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI.
- 2023.08: Arrived at Columbus. My PhD journey officially starts 😋!
- 2023.05: Please check out [MuseCoco](#pub-musecoco), a text-to-music generation system.
- 2022.09: Our paper [Museformer](#pub-museformer) is accepted by NeurIPS 2022!

# 📝 Publication

<div class="keyword-buttons">
  <button class="keyword-btn" data-keyword="all">All</button>
  <button class="keyword-btn" data-keyword="ai-chemistry">AI for Chemistry</button>
  <button class="keyword-btn" data-keyword="nlp">NLP</button>
  <button class="keyword-btn" data-keyword="ai-music">AI Music</button>
  <button class="keyword-btn" data-keyword="cv">CV</button>
  <label class="first-author-label">
    <span class="switch">
      <input type="checkbox" id="firstAuthorToggle">
      <span class="slider"></span>
    </span>
    First Author Only
  </label>
</div>

<div id="no-publications-message">Please use the above keywords to filter the publications.</div>

<div id="publications">
  <ul>
    <li class="publication" data-keywords="nlp cv" data-first-author="true">
      <span class='anchor' id='pub-llasmol'></span>
      <h3>[Preprint 2024] MMMU-Pro: A More Robust Multi-discipline Multimodal Understanding Benchmark</h3>
      <div class="authors">Xiang Yue*, Tianyu Zheng*, Yuansheng Ni*, Yubo Wang, Kai Zhang, Shengbang Tong, Yuxuan Sun, Ming Yin, <strong>Botao Yu</strong>, Ge Zhang, Huan Sun, Yu Su, Wenhu Chen, Graham Neubig (* equal contribution)</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2402.09391">Paper</a>
        <a href="https://osu-nlp-group.github.io/LLM4Chem/">Page</a>
        <a href="https://huggingface.co/datasets/osunlp/SMolInstruct">Dataset</a>
        <a href="https://huggingface.co/osunlp/LlaSMol-Mistral-7B">Model</a>
        <a href="https://github.com/OSU-NLP-Group/LLM4Chem">Code</a>
      </div>
    </li>

    <li class="publication" data-keywords="ai-chemistry nlp" data-first-author="true">
      <span class='anchor' id='pub-llasmol'></span>
      <h3>[COLM 2024] LlaSMol: Advancing Large Language Models for Chemistry with a Large-Scale, Comprehensive, High-Quality Instruction Tuning Dataset</h3>
      <div class="authors"><strong>Botao Yu</strong>, Frazier N. Baker*, Ziqi Chen*, Xia Ning, Huan Sun (* equal contribution)</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2402.09391">Paper</a>
        <a href="https://osu-nlp-group.github.io/LLM4Chem/">Page</a>
        <a href="https://huggingface.co/datasets/osunlp/SMolInstruct">Dataset</a>
        <a href="https://huggingface.co/osunlp/LlaSMol-Mistral-7B">Model</a>
        <a href="https://github.com/OSU-NLP-Group/LLM4Chem">Code</a>
      </div>
    </li>

    <li class="publication" data-keywords="nlp cv">
      <span class='anchor' id='pub-mmmu'></span>
      <h3>[CVPR 2024 Oral] MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI</h3>
      <div class="authors">Xiang Yue, Yuansheng Ni, Kai Zhang, Tianyu Zheng, Ruoqi Liu, Ge Zhang, Samuel Stevens, Dongfu Jiang, Weiming Ren, Yuxuan Sun, Cong Wei, <strong>Botao Yu</strong>, Ruibin Yuan, Renliang Sun, Ming Yin, Boyuan Zheng, Zhenzhu Yang, Yibo Liu, Wenhao Huang, Huan Sun, Yu Su, Wenhu Chen</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2306.00110">Paper</a>
        <a href="https://github.com/MMMU-Benchmark/MMMU">Code</a>
        <a href="https://huggingface.co/datasets/MMMU/MMMU">Dataset</a>
        <a href="https://mmmu-benchmark.github.io">Page</a>
      </div>
    </li>

    <li class="publication" data-keywords="ai-music nlp" data-first-author="true">
      <span class='anchor' id='pub-musecoco'></span>
      <h3>[Preprint 2023] MuseCoco: Generating Symbolic Music from Text</h3>
      <div class="authors">Peiling Lu*, Xin Xu*, Chenfei Kang*, <strong>Botao Yu</strong>*, Chengyi Xing*, Xu Tan, Jiang Bian (* equal contribution)</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2306.00110">Paper</a>
        <a href="https://github.com/microsoft/muzic/tree/main/musecoco">Code</a>
        <a href="https://ai-muzic.github.io/musecoco">Demo</a>
      </div>
    </li>

    <li class="publication" data-keywords="ai-music">
      <h3>[Preprint 2023] EmoGen: Eliminating Subjective Bias in Emotional Music Generation</h3>
      <div class="authors">Chenfei Kang, Peiling Lu, <strong>Botao Yu</strong>, Xu Tan, Wei Ye, Shikun Zhang, Jiang Bian</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2307.01229">Paper</a>
        <a href="https://github.com/microsoft/muzic/tree/main/emogen">Code</a>
        <a href="https://ai-muzic.github.io/emogen">Demo</a>
      </div>
    </li>

    <li class="publication" data-keywords="ai-music" data-first-author="true">
      <span class='anchor' id='pub-museformer'></span>
      <h3>[NeurIPS 2022] Museformer: Transformer with Fine- and Coarse-Grained Attention for Music Generation</h3>
      <div class="authors"><strong>Botao Yu</strong>, Peiling Lu, Rui Wang, Wei Hu, Xu Tan, Wei Ye, Shikun Zhang, Tao Qin, Tie-Yan Liu</div>
      <div class="links">
        <a href="https://openreview.net/forum?id=GFiqdZOm-Ei">Paper</a>
        <a href="https://github.com/microsoft/muzic/tree/main/museformer">Code</a>
        <a href="https://ai-muzic.github.io/museformer">Demo</a>
      </div>
    </li>

    <li class="publication" data-keywords="ai-music">
      <h3>[ISMIR 2022] MeloForm: Generating Melody with Musical Form Based on Expert Systems and Neural Networks</h3>
      <div class="authors">Peiling Lu, Xu Tan, <strong>Botao Yu</strong>, Tao Qin, Sheng Zhao, Tie-Yan Liu</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2208.14345">Paper</a>
        <a href="https://github.com/microsoft/muzic/tree/main/meloform">Code</a>
        <a href="https://ai-muzic.github.io/meloform">Demo</a>
      </div>
    </li>

    <li class="publication" data-keywords="nlp">
      <h3>[EMNLP 2021] Knowing False Negatives: An Adversarial Training Method for Distantly Supervised Relation Extraction</h3>
      <div class="authors">Kailong Hao, <strong>Botao Yu</strong>, Wei Hu</div>
      <div class="links">
        <a href="https://aclanthology.org/2021.emnlp-main.761">Paper</a>
        <a href="https://github.com/nju-websoft/fan">Code</a>
      </div>
    </li>

    <li class="publication" data-keywords="nlp">
      <h3>[APWeb-WAIM 2020] Joint Reasoning of Events, Participants and Locations for Plot Relation Recognition</h3>
      <div class="authors">Shengguang Qiu, <strong>Botao Yu</strong>, Lei Qian, Qiang Guo, Wei Hu</div>
      <div class="links">
        <a href="https://link.springer.com/chapter/10.1007/978-3-030-60259-8_51">Paper</a>
      </div>
    </li>
  </ul>
</div>


# 📖 Education
- 2023.08 - Now &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Columbus, Ohio, USA

  PhD student in Computer Science and Engineering @ The Ohio State University

- 2019.09 - 2023.06 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Nanjing, Jiangsu, China

  Master's student in Computer Science @ Nanjing University (南京大学)

- 2015.09 - 2019.06 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Dalian, Liaoning, China

  Undergraduate student in Software Engineering @ Dalian University of Technology (大连理工大学)

- 2012.09 - 2015.06 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Changsha, Hunan, China

  High school student @ The High School Attached To Hunan Normal University (湖南师大附中)

# 💻 Internship
- 2021.04 - 2022.03 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Beijing, China
  
  Research intern @ Microsoft Research Asia (微软亚洲研究院)


<div style="height: 32vh;"></div>

---

*Last modified: Sep 5, 2024*

<style>
  #publications ul {
    list-style-type: none;
    padding: 0;
  }

  #publications li {
    background-color: #f8f9fa;
    border: 1px solid #e9ecef;
    border-radius: 8px;
    padding: 15px;
    margin-bottom: 15px;
    transition: box-shadow 0.3s ease;
  }

  #publications li:hover {
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }

  #publications h3 {
    margin-top: 0;
    margin-bottom: 10px;
    color: #333;
  }

  .authors {
    margin-bottom: 10px;
    font-style: italic;
    color: #555;
  }

  .links a {
    display: inline-block;
    margin-right: 10px;
    margin-bottom: 5px;
    padding: 5px 10px;
    background-color: #e0e0e0;
    color: #333;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s ease;
    border: none;
    cursor: pointer;
    font-size: 14px;
    line-height: 1.5;
  }

  .links a:hover {
    background-color: #c0c0c0;
  }

  #no-publications-message {
    display: none;
    margin-top: 20px;
    font-style: italic;
    color: #666;
  }

  /* Keyword buttons and first author toggle container */
  .keyword-buttons {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 20px;
  }

  /* Keyword buttons */
  .keyword-btn {
    display: inline-block;
    margin-right: 10px;
    margin-bottom: 5px;
    padding: 5px 10px;
    background-color: #e0e0e0;
    color: #333;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s ease;
    border: none;
    cursor: pointer;
    font-size: 14px;
    line-height: 1.5;
  }

  .keyword-btn:hover {
    background-color: #c0c0c0;
  }

  .keyword-btn.active {
    background-color: #0366d6;
    color: white;
  }

  /* First author toggle */
  .first-author-label {
    display: flex;
    align-items: center;
    margin-left: 15px;
    font-size: 14px;
    color: #333;
  }

  .switch {
    position: relative;
    display: inline-block;
    width: 50px;
    height: 24px;
    margin-right: 10px;
  }

  .switch input {
    opacity: 0;
    width: 0;
    height: 0;
  }

  .slider {
    position: absolute;
    cursor: pointer;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: #ccc;
    transition: .4s;
    border-radius: 24px;
  }

  .slider:before {
    position: absolute;
    content: "";
    height: 18px;
    width: 18px;
    left: 3px;
    bottom: 3px;
    background-color: white;
    transition: .4s;
    border-radius: 50%;
  }

  input:checked + .slider {
    background-color: #0366d6;
  }

  input:checked + .slider:before {
    transform: translateX(26px);
  }
</style>


<script>
document.addEventListener('DOMContentLoaded', function() {
  const keywordButtons = document.querySelectorAll('.keyword-btn');
  const publications = document.querySelectorAll('.publication');
  const allButton = document.querySelector('.keyword-btn[data-keyword="all"]');
  const noPublicationsMessage = document.getElementById('no-publications-message');
  const firstAuthorToggle = document.getElementById('firstAuthorToggle');

  keywordButtons.forEach(button => {
    button.addEventListener('click', function() {
      if (this.dataset.keyword === 'all') {
        keywordButtons.forEach(btn => btn.classList.remove('active'));
        this.classList.add('active');
      } else {
        allButton.classList.remove('active');
        this.classList.toggle('active');
        
        // Check if no keyword buttons are active
        const activeKeywords = document.querySelectorAll('.keyword-btn.active:not([data-keyword="all"])');
        if (activeKeywords.length === 0) {
          allButton.classList.add('active');
        }
      }
      updatePublications();
    });
  });

  firstAuthorToggle.addEventListener('change', updatePublications);

  function updatePublications() {
    const activeKeywords = Array.from(document.querySelectorAll('.keyword-btn.active'))
      .map(btn => btn.dataset.keyword);
    const firstAuthorOnly = firstAuthorToggle.checked;

    let visibleCount = 0;

    publications.forEach(pub => {
      const pubKeywords = pub.dataset.keywords.split(' ');
      const isFirstAuthor = pub.dataset.firstAuthor === 'true';
      if ((activeKeywords.includes('all') || activeKeywords.some(k => pubKeywords.includes(k))) &&
          (!firstAuthorOnly || isFirstAuthor)) {
        pub.style.display = 'list-item';
        visibleCount++;
      } else {
        pub.style.display = 'none';
      }
    });

    if (visibleCount === 0) {
      noPublicationsMessage.style.display = 'block';
    } else {
      noPublicationsMessage.style.display = 'none';
    }
  }

  // Set 'All' as active by default
  allButton.classList.add('active');
  updatePublications();
});
</script>

