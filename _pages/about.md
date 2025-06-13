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

**Yao Luo (罗尧)** is a LLM researcher at the ByteDance Seed Team. She received her Master’s degree from the National University of Singapore and her Bachelor’s degree from the Beijing University of Posts and Telecommunications.

She is dedicated to developing **<font color=red>efficient and powerful architectures of foundation model</font>**, including large language models and large multimodal models. To this end, her research interests include *<font color=blue>sparse architectures, linear attention, long-context modeling, and model merging</font>*, among others.

> We are recruiting LLM interns. If you're interested in LLM efficiency or sparse/linear attention, feel free to contact me via Email `luoyao0323@163.com` or WeChat `15600307011`.

# 🔥 News
- *2025.05*: &nbsp;🎉	We offer some pre-training guidelines for effective <font color=red>model merging</font>!
- *2025.04*: &nbsp;🎉	We release <font color=red>Seed1.5-Thinking</font>, a powerful reasoning model!
- *2025.01*: &nbsp;🎉	<font color=red>2 papers</font> about long-context modeling are accepted by ICLR 2025!

  
# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Bytedance Seed</div><img src='images/modelmerge.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Model Merging in Pre-training of Large Language Models](https://arxiv.org/pdf/2505.12082)

ByteDance Seed

[![arXiv](https://img.shields.io/badge/Paper-Bytedance%20Seed-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2505.12082)
- We present a comprehensive investigation of model merging techniques during the pre-training process.
- Merging checkpoints trained with constant learning rates not only achieves significant performance improvements but
also enables accurate prediction of annealing behavior.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Bytedance Seed</div><img src='images/seed_1.5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Seed1.5-Thinking: Advancing Superb Reasoning Models with Reinforcement Learning](https://arxiv.org/pdf/2504.13914)

ByteDance Seed

[![arXiv](https://img.shields.io/badge/Paper-Bytedance%20Seed-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2504.13914) [![project](https://img.shields.io/badge/Try%20Seed1.5--Thinking-orange.svg)](https://www.volcengine.com/experience/ark)
- Seed1.5-Thinking has achieved strong performance in both reasoning and non-reasoning tasks.
- Seed1.5-Thinking is a Mixture-of-Experts (MoE) model with a relatively small size, featuring 20B activated
and 200B total parameters.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/flexprefill.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FlexPrefill: A Context-Aware Sparse Attention Mechanism for Efficient Long-Sequence Inference](https://arxiv.org/pdf/2502.20766?)

Xunhao Lai, Jianqiao Lu, Yao Luo, Yiyuan Ma, Xun Zhou

[![arXiv](https://img.shields.io/badge/Paper-ICLR_2025-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2502.20766?) [![](https://img.shields.io/github/stars/ByteDance-Seed/FlexPrefill?style=social&label=Code+Stars)](https://github.com/ByteDance-Seed/FlexPrefill)
- FlexPrefill is a dynamic and context-aware sparse attention mechanism that optimizes computational efficiency during long-sequence inference for LLMs.
- FlexPrefill can dynamically adjust sparse attention patterns and computational budgets in real-time based on input demands and attention head requirements.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/why_does.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Why Does the Effective Context Length of LLMs Fall Short?](https://arxiv.org/pdf/2410.18745?)

Chenxin An, Jun Zhang, Ming Zhong, Lei Li, Shansan Gong, Yao Luo, Jingjing Xu, Lingpeng Kong

[![arXiv](https://img.shields.io/badge/Paper-ICLR_2025-b31b1b.svg?style=plastic&logo=arXiv)](https://arxiv.org/pdf/2410.18745?) [![](https://img.shields.io/github/stars/HKUNLP/STRING?style=social&label=Code+Stars)](https://github.com/ByteDance-HKUNLP/STRING)
- We find there is a left-skewed position frequency distribution in LLM pretraining and these infrequent positions cannot effectively model long-range dependencies.
- We propose STRING, a training-free method that does not require further training but brings significant improvements to popular RoPE-based LLMs.
</div>
</div>



# 📖 Experience
- *2021.10 - now*, researcher at ByteDance. 
- *2020.09 - 2021.07*: Master’s degree. National University of Singapore.
- *2019.08 - 2019.11*: Research intern. National University of Singapore.
- *2016.09 - 2020.06*: Bachelor’s degree. Beijing University of Posts and Telecommunications.


<a href="https://clustrmaps.com/site/1c6lv"  title="ClustrMaps"><img src="//www.clustrmaps.com/map_v2.png?d=mVk5zoyIIJCGFhGqCzXpQJTlg9fHK5StXIVNMd6To7k&cl=ffffff" /></a>
