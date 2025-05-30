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
Hello😊, I am a PhD student (expected to begin my studies in Spring 2025) in Research Center for Social Computing and Information Retrieval (SCIR), at Harbin Institute of Technology (HIT, China).
My advisor is Prof. [Wanxiang Che](http://ir.hit.edu.cn/~car/).
Previously, my primary research interests were centered on deep learning for natural language generation (NLG), such as grammatical error correction. Recently, I have shifted my focus to studying efficient inference for large language models, particularly in the area of speculative decoding.

My main research interest is **efficient LLMs**, including inference acceleration and synthetic data.
If you are interested in my research or potential collaborations, please feel free to reach out to me at [yixuanwang@ir.hit.edu.cn](yixuanwang@ir.hit.edu.cn).

If you like the template of this homepage, welcome to star and fork Yi Ren's open-sourced template version [AcadHomepage ![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io?style=social)](https://github.com/RayeRen/acad-homepage.github.io).

# 🔥 News
- *2025.05*: &nbsp;🎉🎉 Our [Token Recycling](https://arxiv.org/abs/2408.08696) (Main) and [TagEvol]() (Findings) are accepted by ACL 2025.
- *2024.09*: &nbsp;🎉🎉 Our [Make-Some-Noise](https://arxiv.org/abs/2406.17404) is accepted by EMNLP 2024.
- *2024.09*: &nbsp;🎉🎉 Celebrate the birth of the homepage.

# 📝 Publications 
🚀**Speculative Decoding**
- <span class="preprint-tag">Arxiv</span> [Think Before You Accept: Semantic Reflective Verification for Faster Speculative Decoding](https://arxiv.org/pdf/2505.18629), **Yixuan Wang**, Yijun Liu, Shiyu Ji, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che.
- <span class="conference-tag">ACL2025</span> [Turning Trash into Treasure: Accelerating Inference of Large Language Models with Token Recycling](https://arxiv.org/abs/2408.08696), Xianzhen Luo, **Yixuan Wang**, Qingfu Zhu, Zhiming Zhang, Xuanyu Zhang, Qing Yang, Dongliang Xu, Wanxiang Che.
- <span class="conference-tag">EMNLP2024</span> [Make Some Noise: Unlocking Language Model Parallel Inference Capability through Noisy Training](https://arxiv.org/abs/2406.17404), **Yixuan Wang**\*, Xianzhen Luo\*, Fuxuan Wei, Yijun Liu, Qingfu Zhu, Xuanyu Zhang, Qing Yang, Dongliang Xu, Wanxiang Che.

⚡️**KV Cache Compression**
- <span class="preprint-tag">Arxiv</span> [Lookahead Q-Cache: Achieving More Consistent KV Cache Eviction via Pseudo Query](https://arxiv.org/pdf/2505.20334), **Yixuan Wang**\*, Shiyu Ji\*, Yijun Liu, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che.

📊**Data Augmentation**
- <span class="conference-tag">ACL2025(Findings)</span> [Tag-Evol: Achieving Efficient Instruction Evolving via Tag Injection](), **Yixuan Wang**\*, Shiqi Zhou\*, Chuanzhe Guo, Qingfu Zhu.
- <span class="conference-tag">ACL2024(Findings)</span> [Improving Grammatical Error Correction via Contextual Data Augmentation](https://aclanthology.org/2024.findings-acl.647.pdf), **Yixuan Wang**, Baoxin Wang, Yijun Liu, Qingfu Zhu, Dayong Wu, Wanxiang Che.
[[code](https://github.com/wyxstriker/CDA4GEC)]

🖊**Grammatical Error Correction**
- <span class="conference-tag">ACL2024(Findings)</span> [Improving Grammatical Error Correction via Contextual Data Augmentation](https://aclanthology.org/2024.findings-acl.647.pdf), **Yixuan Wang**, Baoxin Wang, Yijun Liu, Qingfu Zhu, Dayong Wu, Wanxiang Che.
[[code](https://github.com/wyxstriker/CDA4GEC)]
- <span class="conference-tag">LREC-COLING2024(Findings)</span> [LM-Combiner: A Contextual Rewriting Model for Chinese Grammatical Error Correction](https://aclanthology.org/2024.lrec-main.934.pdf), **Yixuan Wang**, Baoxin Wang, Yijun Liu, Dayong Wu, Wanxiang Che.
[[code](https://github.com/wyxstriker/LM-Combiner)]
- <span class="conference-tag">COLING2022(Oral)</span> [Adaptive Unsupervised Self training for Disfluency Detection](https://aclanthology.org/2022.coling-1.632.pdf), Zhongyuan Wang, **Yixuan Wang**, Shaolei Wang, Wanxiang Che.
[[code](https://github.com/wyxstriker/ReweightingDisfluency)]

# 🎖 Honors and Awards
- **National Scholarship** (2023)
- Academic Scholarship (First Class 2022)
- People’s Scholarship (2018, 2019, 2020)
- **1st place** in Chinese Essay Fluency Evaluation, CCL2023

# 📖 Educations
- *2022.09 - Now*, Master, Harbin Institute of Technology, Harbin.
- *2018.09 - 2022.06*, Undergraduate, Harbin Institute of Technology, Harbin.

# 💻 Internships
- *2023.06 - 2023.09*, Joint Laboratory of HIT and iFLYTEK Research (HFL), China.
