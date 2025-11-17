---
permalink: /
title: "👏 Hello there, I'm Jundong Xu."
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

# Welcome!
Hi, nice to meet you! I’m Xu Jundong, a first-year PhD Student at the National University of Singapore (NUS) CTIC lab, working under the supervision of Prof. [Mong-Li Lee](https://www.comp.nus.edu.sg/~leeml/) and Prof. [Wynne Hsu](https://www.comp.nus.edu.sg/~whsu/). I am also mentored by Dr. [Hao Fei](https://haofei.vip/). Previously, I earned a Master of Computing from NUS and a BSc from University College London (UCL).

My work focuses on enhancing the symbolic reasoning capabilities of computational systems. I aim to develop methods that support systematic and reliable inference, helping to bridge the gap between data-driven approaches and structured logical reasoning.

I am especially interested in interdisciplinary collaborations and welcome discussions with researchers working on topics related to logic, reasoning, and neuro-symbolic frameworks. Check out our **[Neuro-Symbolic Model](https://llm-symbol.github.io/)** project website. Please feel free to reach out via email to talk about research!

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=kx4xFzMAAAAJ&hl=en'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=kx4xFzMAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News
- *2025.09*: &nbsp;🎉🎉 The paper [MuSLR](https://arxiv.org/abs/2509.25851) has been accepted to NeurIPS 2025. See you in San Diego!
- *2025.06*: &nbsp;🎉🎉 The paper [Aristotle](https://arxiv.org/abs/2412.16953) has been selected as an **<span style="color:red">oral</span>** presentation (8% of the accepted paper).
- *2025.05*: &nbsp;🎉🎉 The paper [Aristotle](https://arxiv.org/abs/2412.16953) has been accepted to ACL 2025 main conference.
- *2025.04*: &nbsp;🎉🎉 I got a PhD offer from NUS!
- *2025.01*: &nbsp;🎉🎉 I started working as a research assistant at NUS CTIC.
- *2025.01*: &nbsp;🎉🎉 I officially received my master's degree.
- *2024.12*: &nbsp;🎉🎉 Our new paper [Aristotle](https://arxiv.org/abs/2412.16953) is released on Arxiv.
- *2024.10*: &nbsp;🎉🎉 One paper was accepted at the ACM MM Workshop on Multi-modal Misinformation Governance in the Era of Foundation Models.
- *2024.05*: &nbsp;🎉🎉 The paper [SymbCoT](https://arxiv.org/abs/2405.18357) has been accepted to the ACL 2024 main conference.

# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2025</div>
      <img src="{{ '/images/muslr.png' | relative_url }}" alt="MuSLR" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <p><a href="https://arxiv.org/abs/2509.25851"><strong>MuSLR: Multimodal Symbolic Logical Reasoning</strong></a></p>
    <p><strong><span style="color:red">Jundong Xu</span></strong>, Hao Fei*, Yuhui Zhang, Liangming Pan, Qijun Huang, Qian Liu, Preslav Nakov, Min-Yen Kan, William Yang Wang, Mong-Li Lee, Wynne Hsu.</p>
    <p><a href="https://llm-symbol.github.io/MuSLR/"><strong>Project</strong></a> <strong><span class="show_paper_citations" data="DhtAFkwAAAAJ:ALROH1vI_8AC"></span></strong></p>
    <ul>
      <li>We present the first multimodal symbolic reasoning benchmark grounded in formal logical rules, and propose a modular framework, LogiCAM, to enhance VLMs’ MuSLR capabilities.</li>
    </ul>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACL 2025 Oral</div>
      <img src="{{ '/images/aristotle_framework.png' | relative_url }}" alt="Aristotle framework" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <p><a href="https://arxiv.org/abs/2412.16953"><strong>Aristotle: Mastering Logical Reasoning with A Logic-Complete Decompose–Search–Resolve Framework</strong> (<strong><span style="color:red">Oral</span></strong>)</a></p>
    <p><strong><span style="color:red">Jundong Xu</span></strong>, Hao Fei*, Meng Luo, Qian Liu, Liangming Pan, William Yang Wang, Preslav Nakov, Mong-Li Lee, Wynne Hsu.</p>
    <p><a href="https://llm-symbol.github.io/Aristotle/"><strong>Project</strong></a> <strong><span class="show_paper_citations" data="DhtAFkwAAAAJ:ALROH1vI_8AC"></span></strong></p>
    <ul>
      <li>This paper integrates a logic-complete decompose–search–resolve framework to strengthen LLM reasoning with symbolic logic.</li>
    </ul>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ACL 2024 Main</div>
      <img src="{{ '/images/symbcot_framework.png' | relative_url }}" alt="SymbCoT framework" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <p><a href="https://arxiv.org/abs/2405.18357"><strong>Faithful Logical Reasoning via Symbolic Chain-of-Thought</strong></a></p>
    <p><strong><span style="color:red">Jundong Xu</span></strong>, Hao Fei*, Liangming Pan, Qian Liu, Mong-Li Lee, Wynne Hsu.</p>
    <p><a href="https://github.com/Aiden0526/SymbCoT"><strong>Project</strong></a> <strong><span class="show_paper_citations" data="DhtAFkwAAAAJ:ALROH1vI_8AC"></span></strong></p>
    <ul>
      <li>This paper combines symbolic logical rules with the reasoning chain to improve logical reasoning in LLMs.</li>
    </ul>
  </div>
</div>

<!-- Clear floats so subsequent sections don't overlap the publication cards -->
<div style="clear: both;"></div>

# 📖 Educations
- *2025.08 - Present*, PhD in Computer Science, National University of Singapore
- *2023.01 - 2025.01*, Master of Computing, National University of Singapore
- *2019.09 - 2022.07*, BSc Information Management, University College London

# 💬 Invited Talks
- *2025.05*, Invited to [NICE](https://nice-intl.github.io) (NLP Academic Exchange) to introduce ACL 2025 paper Aristotle. \| [\[video\]](https://www.bilibili.com/video/BV1bAMAz4EPu/?spm_id_from=333.337.search-card.all.click&vd_source=cb6489f9e15bfd5fa43e30a8e01b0818)
- *2024.06*, Invited to [NICE](https://nice-intl.github.io) (NLP Academic Exchange) to introduce ACL 2024 paper SymbCoT. \| [\[video\]](https://www.bilibili.com/video/BV1dS411P7Y7/?spm_id_from=333.1387.upload.video_card.click&vd_source=cb6489f9e15bfd5fa43e30a8e01b0818)

# 💻 Academic Services
- **Reviewer:** ACL (2025), ICLR (2025, 2026), EMNLP (2025), ACM MM (2024, 2025), Neurocomputing (2024, 2025), NLPCC (2024)
- **Volunteer:** ACL 2024

# Miscellaneous
I love sports, especially basketball, tennis, and skiing. I'm a big fan of the Golden State Warriors and Stephen Curry, and I also admire Roger Federer.
I enjoy reading books, especially science fiction and psychology. Some of my favorites include *Narcissus and Goldmund* and *The Three-Body Problem*.
I also love watching movies. Some of my favorites are *Fight Club* by David Fincher and *A Confucian Confusion* by Edward Yang.
