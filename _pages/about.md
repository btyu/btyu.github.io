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

My **research interest** includes <u>AI for Science (esp. Chemistry)</u>, <u>LLMs</u>, <u>NLP</u>, <u>AI music</u>, and <u>deep learning</u>.

# 🔥 News
- 2024.11: Please check out our new preprint [ChemAgent](#pub-chemagent), an enhanced chemistry agent and its performance on various chemistry problems.
- 2024.10: Please check out our new preprint [ScienceAgentBench](#pub-scienceagentbench), a benchmark to assess language models in scientific tasks.
- 2024.09: Check out our new preprint [MMMU-Pro](#pub-mmmupro), an enhanced version of [MMMU](#pub-mmmu) featuring full-vision evaluation.
- 2024.07: Our paper [LlaSMol](#pub-llasmol) is accepted to COLM 2024 🎉!
- 2024.05: Our paper [MMMU](#pub-mmmu) is selected as Oral (0.8%) and nominated for best paper (24 in total) at CVPR 2024 🎊!
- 2023.08: Arrived at Columbus. My PhD journey officially starts 😋!
- 2023.05: Please check out our preprint [MuseCoco](#pub-musecoco), a text-to-music generation system.
- 2022.09: Our paper [Museformer](#pub-museformer) is accepted to NeurIPS 2022 🎉!

# 📝 Publication

<div class="keyword-buttons">
  <button class="keyword-btn" data-keyword="all">All</button>
  <button class="keyword-btn" data-keyword="ai-science">AI for Science</button>
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

<div id="no-publications-message">Sadly, there are no such publications.</div>

<div id="publications">
  <ul>
    <span class='anchor' id='pub-chemagent'></span>
    <li class="publication" data-keywords="ai-science nlp" data-first-author="true">
      <h3>[Preprint 2024] Tooling or Not Tooling? The Impact of Tools on Language Agents for Chemistry Problem Solving</h3>
      <div class="authors"><strong>Botao Yu</strong>, Frazier N. Baker*, Ziru Chen*, Garrett Herb, Boyu Gou, Daniel Adu-Ampratwum, Xia Ning, Huan Sun (* equal contribution)</div>
      <div class="description">We propose a tool-augmented language agent for chemistry named ChemAgent, and evaluate it on both specialized chemistry tasks and general chemistry questions. The results show that tools cannot always help and may cause more reasoning errors.</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2411.07228">Paper</a>
        <a href="https://osu-nlp-group.github.io/ChemAgent/">Page</a>
        <a href="https://github.com/OSU-NLP-Group/ChemAgent">Code</a>
      </div>
    </li>

    <span class='anchor' id='pub-scienceagentbench'></span>
    <li class="publication" data-keywords="ai-science nlp">
      <h3>[Preprint 2024] ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery</h3>
      <div class="authors">Ziru Chen, Shijie Chen, Yuting Ning, Qianheng Zhang, Boshi Wang, <strong>Botao Yu</strong>, Yifei Li, Zeyi Liao, Chen Wei, Zitong Lu, Vishal Dey, Mingyi Xue, Frazier N. Baker, Benjamin Burns, Daniel Adu-Ampratwum, Xuhui Huang, Xia Ning, Song Gao, Yu Su, Huan Sun</div>
      <div class="description">The study introduces a benchmark for evaluating language models in scientific discovery, using 102 tasks from peer-reviewed publications and expert validation. It reveals current limitations in code generation, highlighting the need for rigorous task assessments.</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2410.05080">Paper</a>
        <a href="https://osu-nlp-group.github.io/ScienceAgentBench/">Page</a>
        <a href="https://huggingface.co/datasets/osunlp/ScienceAgentBench">Benchmark</a>
        <a href="https://github.com/OSU-NLP-Group/ScienceAgentBench">Code</a>
      </div>
    </li>

    <span class='anchor' id='pub-mmmupro'></span>
    <li class="publication" data-keywords="nlp cv">
      <h3>[Preprint 2024] MMMU-Pro: A More Robust Multi-discipline Multimodal Understanding Benchmark</h3>
      <div class="authors">Xiang Yue*, Tianyu Zheng*, Yuansheng Ni*, Yubo Wang, Kai Zhang, Shengbang Tong, Yuxuan Sun, Ming Yin, <strong>Botao Yu</strong>, Ge Zhang, Huan Sun, Yu Su, Wenhu Chen, Graham Neubig (* equal contribution)</div>
      <div class="description">An enhanced version of MMMU featuring full-vision evaluation for multi-discipline multimodal understanding.</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2409.02813">Paper</a>
        <a href="https://mmmu-benchmark.github.io/#leaderboard">Page</a>
        <a href="https://huggingface.co/datasets/MMMU/MMMU_Pro">Dataset</a>
      </div>
    </li>

    <span class='anchor' id='pub-llasmol'></span>
    <li class="publication" data-keywords="ai-science nlp" data-first-author="true">
      <h3>[COLM 2024] LlaSMol: Advancing Large Language Models for Chemistry with a Large-Scale, Comprehensive, High-Quality Instruction Tuning Dataset</h3>
      <div class="authors"><strong>Botao Yu</strong>, Frazier N. Baker*, Ziqi Chen*, Xia Ning, Huan Sun (* equal contribution)</div>
      <div class="description">We propose a carefully curated chemistry task dataset for instruction tuning and a series of LLMs that significantly outperform GPT-4 and Claude-3-Opus on various chemistry tasks.</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2402.09391">Paper</a>
        <a href="https://osu-nlp-group.github.io/LLM4Chem/">Page</a>
        <a href="https://huggingface.co/datasets/osunlp/SMolInstruct">Dataset</a>
        <a href="https://huggingface.co/osunlp/LlaSMol-Mistral-7B">Model</a>
        <a href="https://github.com/OSU-NLP-Group/LLM4Chem">Code</a>
        <a href="https://github.com/btyu/btyu.github.io/blob/main/static/poster/llasmol_poster.pdf">Poster</a>
      </div>
    </li>

    <span class='anchor' id='pub-mmmu'></span>
    <li class="publication" data-keywords="nlp cv">
      <h3>[CVPR 2024 Oral] MMMU: A Massive Multi-discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI</h3>
      <div class="authors">Xiang Yue*, Yuansheng Ni*, Kai Zhang*, Tianyu Zheng*, Ruoqi Liu, Ge Zhang, Samuel Stevens, Dongfu Jiang, Weiming Ren, Yuxuan Sun, Cong Wei, <strong>Botao Yu</strong>, Ruibin Yuan, Renliang Sun, Ming Yin, Boyuan Zheng, Zhenzhu Yang, Yibo Liu, Wenhao Huang, Huan Sun*, Yu Su*, Wenhu Chen* (* core contributors)</div>
      <div class="description">This paper proposes a massive multi-discipline multimodal understanding and reasoning benchmark for expert AGI.</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2311.16502">Paper</a>
        <a href="https://mmmu-benchmark.github.io">Page</a>
        <a href="https://huggingface.co/datasets/MMMU/MMMU">Dataset</a>
        <a href="https://github.com/MMMU-Benchmark/MMMU">Code</a>
      </div>
    </li>

    <span class='anchor' id='pub-musecoco'></span>
    <li class="publication" data-keywords="ai-music nlp" data-first-author="true">
      <h3>[Preprint 2023] MuseCoco: Generating Symbolic Music from Text</h3>
      <div class="authors">Peiling Lu*, Xin Xu*, Chenfei Kang*, <strong>Botao Yu</strong>*, Chengyi Xing*, Xu Tan, Jiang Bian (* equal contribution)</div>
      <div class="description">A two-stage text-to-music generation system for creating symbolic music from textual descriptions.</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2306.00110">Paper</a>
        <a href="https://ai-muzic.github.io/musecoco">Page</a>
        <a href="https://github.com/microsoft/muzic/tree/main/musecoco">Code</a>
      </div>
    </li>

    <li class="publication" data-keywords="ai-music">
      <h3>[Preprint 2023] EmoGen: Eliminating Subjective Bias in Emotional Music Generation</h3>
      <div class="authors">Chenfei Kang, Peiling Lu, <strong>Botao Yu</strong>, Xu Tan, Wei Ye, Shikun Zhang, Jiang Bian</div>
      <div class="description">A method for generating emotional music while reducing subjective bias in the process.</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2307.01229">Paper</a>
        <a href="https://ai-muzic.github.io/emogen">Page</a>
        <a href="https://github.com/microsoft/muzic/tree/main/emogen">Code</a>
      </div>
    </li>

    <span class='anchor' id='pub-museformer'></span>
    <li class="publication" data-keywords="ai-music" data-first-author="true">
      <h3>[NeurIPS 2022] Museformer: Transformer with Fine- and Coarse-Grained Attention for Music Generation</h3>
      <div class="authors"><strong>Botao Yu</strong>, Peiling Lu, Rui Wang, Wei Hu, Xu Tan, Wei Ye, Shikun Zhang, Tao Qin, Tie-Yan Liu</div>
      <div class="description">We propose a fine- and coarse-grained attention mechanism for modeling the structures of music.</div>
      <div class="links">
        <a href="https://openreview.net/forum?id=GFiqdZOm-Ei">Paper</a>
        <a href="https://ai-muzic.github.io/museformer">Page</a>
        <a href="https://github.com/microsoft/muzic/tree/main/museformer">Code</a>
        <a href="https://github.com/btyu/btyu.github.io/blob/main/static/poster/museformer_poster.pdf">Poster</a>
      </div>
    </li>

    <li class="publication" data-keywords="ai-music">
      <h3>[ISMIR 2022] MeloForm: Generating Melody with Musical Form Based on Expert Systems and Neural Networks</h3>
      <div class="authors">Peiling Lu, Xu Tan, <strong>Botao Yu</strong>, Tao Qin, Sheng Zhao, Tie-Yan Liu</div>
      <div class="description">A system for generating melodies with musical form using a combination of expert systems and neural networks.</div>
      <div class="links">
        <a href="https://arxiv.org/abs/2208.14345">Paper</a>
        <a href="https://ai-muzic.github.io/meloform">Page</a>
        <a href="https://github.com/microsoft/muzic/tree/main/meloform">Code</a>
      </div>
    </li>

    <li class="publication" data-keywords="nlp">
      <h3>[EMNLP 2021] Knowing False Negatives: An Adversarial Training Method for Distantly Supervised Relation Extraction</h3>
      <div class="authors">Kailong Hao, <strong>Botao Yu</strong>, Wei Hu</div>
      <div class="description">An adversarial training method to improve distantly supervised relation extraction by addressing false negatives.</div>
      <div class="links">
        <a href="https://aclanthology.org/2021.emnlp-main.761">Paper</a>
        <a href="https://github.com/nju-websoft/fan">Code</a>
      </div>
    </li>

    <li class="publication" data-keywords="nlp">
      <h3>[APWeb-WAIM 2020] Joint Reasoning of Events, Participants and Locations for Plot Relation Recognition</h3>
      <div class="authors">Shengguang Qiu, <strong>Botao Yu</strong>, Lei Qian, Qiang Guo, Wei Hu</div>
      <div class="description">A method for recognizing plot relations by jointly reasoning about events, participants, and locations in narratives.</div>
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

<div class="micro-text">Psst! 🔍 Kudos on your keen eye! Didn't expect anyone to notice this microscopic text. Since you've ventured this far, fancy embarking on a friendship adventure?</div>

*Last modified: Nov. 13, 2024*

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
    margin-bottom: 5px;
    color: #333;
  }

  .authors {
    margin-bottom: 5px;
    font-style: italic;
    color: #555;
  }

  .description {
    margin-bottom: 15px;
  }

  .links {
    margin-top: 10px;
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

  .keyword-buttons {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 20px;
  }

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

  .micro-text {
    font-size: 2px;
    color: #999;
    margin-bottom: 5px;
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

