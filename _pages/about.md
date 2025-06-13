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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/why_does.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Why Does the Effective Context Length of LLMs Fall Short?]([https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf](https://arxiv.org/pdf/2410.18745?))

Chenxin An, Jun Zhang, Ming Zhong, Lei Li, Shansan Gong, Yao Luo, Jingjing Xu, Lingpeng Kong
- Analyze the effective context length of LLMs from a pretraining perspective.
- There is a left-skewed position frequency distribution in LLM pretraining and these infrequent positions cannot effectively model long-range dependencies.
- We propose STRING, a training-free method that does not require further training but brings significant improvements to popular RoPE-based LLMs.
</div>
</div>



# 📖 Experience
- *2021.10 - now*, researcher at ByteDance. 
- *2020.09 - 2021.07*: Master’s degree. National University of Singapore
- *2019.08 - 2019.11*: Research intern. National University of Singapore.
- *2016.09 - 2020.06*: Bachelor’s degree. Beijing University of Posts and Telecommunications.





<a href="https://clustrmaps.com/site/1c6lv"  title="ClustrMaps"><img src="//www.clustrmaps.com/map_v2.png?d=mVk5zoyIIJCGFhGqCzXpQJTlg9fHK5StXIVNMd6To7k&cl=ffffff" /></a>
