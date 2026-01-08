---
permalink: /
layout: single
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% comment %}
This block constructs the URL for the Google Scholar stats badge.
The 'if' statement handles different base URLs for local development vs. deployed site.
{% endcomment %}
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me

I am Junlin Fang (方俊麟), an incoming Ph.D. student at the [College of Computing and Data Science (CCDS)](https://www.ntu.edu.sg/computing) at Nanyang Technological University (NTU), starting in Spring 2026. I will be fortunate to be supervised by Prof. [Sean Du](https://d12306.github.io/index.html).

Previously, I obtained both my Master's and Bachelor's degrees from Southwest Jiaotong University. During my studies, I was advised by Prof. [Fengmao Lv](https://fengmaolv.github.io/online-cv/) and had a close and fruitful collaboration with Prof. [Wenya Wang](https://personal.ntu.edu.sg/wangwy/).

My research interests include the **Reliability**, **Security**, **Alignment**, and **Reasoning** of Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs).

---

# News

- **[1/7/2026]** Start my journey at NTU!
- **[9/25/2025]** Honored to receive a Ph.D. offer from Prof. [Sean Du](https://d12306.github.io/index.html) to join his group at NTU!
- **[7/6/2025]** One paper was accepted as an oral presentation at **ACM Multimedia 2025**.
- **[1/21/2025]** One paper was accepted as an oral presentation at **The Web Conference 2025**.
- **[7/25/2024]** One paper was accepted to **ACM Multimedia 2024**.
- **[7/25/2024]** One paper was accepted as an oral presentation at **CIKM 2024**.

---

#  Publications

* Rethinking the Effect of Unimodal Labels in Multimodal Sentiment Analysis. <br>
    Lingli Zhang, Tianrui Li, Baiyu Lu, **Junlin Fang**, Desheng Zheng, Wei Zhou, Weide Liu, Fengmao Lv. <br>
    *ACM Transactions on Multimedia Computing, Communications, and Applications (**TOMM**).* [Accepted]
  
* Why is a Bird’s Caption a Good Demonstration? Towards Effective Multimodal In-Context Learning without Dedicated Data. <br>
    **Junlin Fang**, Wenya Wang, Lingli Zhang, Fengmao Lv. <br>
    *Proceedings of the ACM International Conference on Multimedia, 2025.* (Oral)

* MSTI-Plus: Introducing Non-Sarcasm Reference Materials to Enhance Multimodal Sarcasm Target Identification. <br>
    Fengmao Lv, Mengting Xiong, **Junlin Fang**, Lingli Zhang, Tianze Luo, Weichao Liange, Tianrui Li. <br>
    *Proceedings of the ACM Web Conference (**WWW**), 2025.* (Oral) <br>
    [\[PDF\]](https://dl.acm.org/doi/10.1145/3696410.3714570) [\[Code\]](https://github.com/tiggers23/MSTI-Plus)

* Sentiment-oriented Sarcasm Integration for Video Sentiment Analysis Enhancement with Sarcasm Assistance. <br>
    **Junlin Fang**, Wenya Wang, Guosheng Lin, Fengmao Lv. <br>
    *Proceedings of the ACM International Conference on Multimedia, 2024.* <br>
    [\[PDF\]](https://dl.acm.org/doi/10.1145/3664647.3680703) [\[Code\]](https://github.com/tiggers23/PS2RI)

* Progressive Multimodal Pivot Learning: Towards Semantic Discordance Understanding as Humans. <br>
    **Junlin Fang**, Wenya Wang, Tianze Luo, Yanyong Huang, Fengmao Lv. <br>
    *Proceedings of the ACM International Conference on Information and Knowledge Management (**CIKM**), 2024.* (Oral) <br>
    [\[PDF\]](https://dl.acm.org/doi/10.1145/3627673.3679524) [\[Code\]](https://github.com/tiggers23/PMPL)

%
* Modeling Deep Fusion of Intra- and Inter-Modal Incongruity for Multimodal Sarcasm Detection. <br>
    Fengmao Lv, **Junlin Fang**, Guosheng Lin, Wenya Wang. <br>
    *IEEE Transactions on Knowledge and Data Engineering (**TKDE**).* [Under Major Revision]
%
---

# Education

-   **Ph.D. in Computer Science** <br>
    Nanyang Technological University, Singapore <br>
    *Jan. 2026*

-   **M.S. in Computer Science and Technology** <br>
    Southwest Jiaotong University, China <br>
    *Sep. 2023 - Dec. 2025 (Expected)*

-   **B.Eng. in Computer Science and Technology** <br>
    Southwest Jiaotong University, China <br>
    *Sep. 2019 - Jun. 2023*
