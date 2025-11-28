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
# About Me
I'm a fourth year Ph.D student from the College of information science and electronic engineering, Zhejiang University. My research interests include model compression (typically vector quantization) and edge accelerators. 

I'm advised by Prof. Kejie Huang. I used to be a research intern at VIVO Mobile Communication. Currently, I am seeking internship and academic collaboration opportunities.



# 🔥 News
- *2025.06*: 🎉 ViM-VQ and SSVQ are accepted by ICCV 2025.
- *2024.12*: 🎉 VQ4ViT is accepted by AAAI 2025.
- *2024.11*: 🎉 MVQ is accepted by ASPLOS 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/VIMVQ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ViM-VQ: Efficient Post-Training Vector Quantization for Visual Mamba](https://arxiv.org/pdf/2503.09509)

**Juncan Deng**, Shuaiting Li, Zeyu Wang, Kedong Xu, Hong Gu, Kejie Huang
 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A vector quantization method that combines convex combination updates and incremental quantization.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/SSVQ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SSVQ: Unleashing the Potential of Vector Quantization with Sign-Splitting](https://arxiv.org/abs/2503.08668)
[Code](https://github.com/list0830/SSVQ)

Shuaiting Li, **Juncan Deng**, Chenxuan Wang, Kedong Xu, Rongtao Deng, Hong Gu, Haibin Shen, Kejie Huang
 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A new Vector Quantization paradigm, simple but effective.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/VQ4DIT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion Transformers](https://ojs.aaai.org/index.php/AAAI/article/view/33782)
[Code](https://github.com/dengjuncan/VQ4DiT)

**Juncan Deng**,Shuaiting Li, Zeyu Wang, Hong Gu, Kedong Xu, Kejie Huang
 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A vector quantization method based on assignment learning. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASPLOS 2025</div><img src='images/ASPLOS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MVQ: Towards Efficient DNN Compression and Acceleration with Masked Vector Quantization](https://dl.acm.org/doi/abs/10.1145/3669940.3707268)

Shuaiting Li, Chengxuan Wang, **Juncan Deng**, Zeyu Wang, Zewen Ye, Zongsheng Wang, Haibin Shen, Kejie Huang
 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- A highly efficient HW-SW co-designed system for Vector Quantization. 
</div>
</div>


# 📖 Educations
- *2022.09 - now*, PhD student, College of information science and electronic engineering, Zhejiang University

# 💻 Internships
- *2024.09 - 2025.06*, Research intern at VIVO Mobile Communication, China.
