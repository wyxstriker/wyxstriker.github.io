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
Hello😊, I am a 1st-year PhD student in Research Center for Social Computing and Interactive Robotics (SCIR), at Harbin Institute of Technology (HIT, China).
My advisor is Prof. [Wanxiang Che](https://chewanxiang.com).
Previously, my primary research interests were centered on deep learning for natural language generation (NLG), such as grammatical error correction. Recently, I have shifted my focus to studying efficient inference for large language models, particularly in the area of speculative decoding.

My main research interest is **efficient LLMs**, including inference acceleration and synthetic data.
If you are interested in my research or potential collaborations, please feel free to reach out to me at [yixuanwang@ir.hit.edu.cn](yixuanwang@ir.hit.edu.cn).

If you like the template of this homepage, welcome to star and fork Yi Ren's open-sourced template version [AcadHomepage ![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io?style=social)](https://github.com/RayeRen/acad-homepage.github.io).

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Our [ProxyAttn](https://arxiv.org/pdf/2509.24745) is accepted by ICLR 2026.
- *2025.11*: &nbsp;🎉🎉 Our [Judge Q](https://arxiv.org/pdf/2509.10798) and [CAMERA](https://arxiv.org/pdf/2508.02322) are accepted by AAAI 2026.
- *2025.08*: &nbsp;🎉🎉 Our [LookAhead Q-Cache](https://arxiv.org/pdf/2505.20334) (Main) is accepted by EMNLP 2025.
- *2025.05*: &nbsp;🎉🎉 Our [Token Recycling](https://arxiv.org/abs/2408.08696) (Main) and [TagEvol](https://arxiv.org/abs/2505.24165) (Findings) are accepted by ACL 2025.
- *2024.09*: &nbsp;🎉🎉 Our [Make-Some-Noise](https://arxiv.org/abs/2406.17404) is accepted by EMNLP 2024.
- *2024.09*: &nbsp;🎉🎉 Celebrate the birth of the homepage.

# 📝 Publications 
🚀**Speculative Decoding**
- ![](https://img.shields.io/badge/2025-Arxiv-orange) [Think Before You Accept: Semantic Reflective Verification for Faster Speculative Decoding](https://arxiv.org/pdf/2505.18629), **Yixuan Wang**, Yijun Liu, Shiyu Ji, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che.
- ![](https://img.shields.io/badge/2025-ACL_Main-green) [Turning Trash into Treasure: Accelerating Inference of Large Language Models with Token Recycling](https://arxiv.org/abs/2408.08696), Xianzhen Luo, **Yixuan Wang**, Qingfu Zhu, Zhiming Zhang, Xuanyu Zhang, Qing Yang, Dongliang Xu, Wanxiang Che.
[[code](https://github.com/Luowaterbi/TokenRecycling)]
- ![](https://img.shields.io/badge/2024-EMNLP_Main-green) [Make Some Noise: Unlocking Language Model Parallel Inference Capability through Noisy Training](https://arxiv.org/abs/2406.17404), **Yixuan Wang**\*, Xianzhen Luo\*, Fuxuan Wei, Yijun Liu, Qingfu Zhu, Xuanyu Zhang, Qing Yang, Dongliang Xu, Wanxiang Che.
[[code](https://github.com/wyxstriker/MakeSomeNoiseInference)]

⚡️**KV Cache Compression**
- ![](https://img.shields.io/badge/2025-Arxiv-orange) [CommonKV: Compressing KV Cache with Cross-layer Parameter Sharing](https://arxiv.org/pdf/2508.16134), **Yixuan Wang**\*, Haoyu Qiao\*, Lujun Li, Qingfu Zhu, Wanxiang Che.
[[code](https://github.com/rommel2021/CommonKV)]
- ![](https://img.shields.io/badge/2026-AAAI-green) [Judge Q: Trainable Queries for Optimized Information Retention in KV Cache Eviction](https://arxiv.org/pdf/2509.10798), Yijun Liu, **Yixuan Wang**, Yuzhuang Xu, Shiyu Ji, Yang Xu, Qingfu Zhu, Wanxiang Che.
- ![](https://img.shields.io/badge/2025-EMNLP_Main-green) [Lookahead Q-Cache: Achieving More Consistent KV Cache Eviction via Pseudo Query](https://arxiv.org/pdf/2505.20334), **Yixuan Wang**\*, Shiyu Ji\*, Yijun Liu, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che.
[[code](https://github.com/noforit/Lookahead_Q-Cache)]

👀**Efficient Attention**
- ![](https://img.shields.io/badge/2026-ICLR-green) [ProxyAttn: Guided Sparse Attention via Representative Heads](https://arxiv.org/pdf/2509.24745), **Yixuan Wang**, Huang He, Siqi Bao, Hua Wu, Haifeng Wang, Qingfu Zhu, Wanxiang Che.
[[code](https://github.com/wyxstriker/ProxyAttn)]


📊**Data Augmentation**
- ![](https://img.shields.io/badge/2025-ACL_Findings-green) [Tag-Evol: Achieving Efficient Instruction Evolving via Tag Injection](https://arxiv.org/abs/2505.24165), **Yixuan Wang**\*, Shiqi Zhou\*, Chuanzhe Guo, Qingfu Zhu.
[[code](https://github.com/fghccv/TagEvol)]
- ![](https://img.shields.io/badge/2024-ACL_Findings-green) [Improving Grammatical Error Correction via Contextual Data Augmentation](https://aclanthology.org/2024.findings-acl.647.pdf), **Yixuan Wang**, Baoxin Wang, Yijun Liu, Qingfu Zhu, Dayong Wu, Wanxiang Che.
[[code](https://github.com/wyxstriker/CDA4GEC)]

🖊**Grammatical Error Correction**
- ![](https://img.shields.io/badge/2024-LREC_COLING-green) [LM-Combiner: A Contextual Rewriting Model for Chinese Grammatical Error Correction](https://aclanthology.org/2024.lrec-main.934.pdf), **Yixuan Wang**, Baoxin Wang, Yijun Liu, Dayong Wu, Wanxiang Che.
[[code](https://github.com/wyxstriker/LM-Combiner)]
- ![](https://img.shields.io/badge/2022-COLING-green) [Adaptive Unsupervised Self training for Disfluency Detection](https://aclanthology.org/2022.coling-1.632.pdf), Zhongyuan Wang, **Yixuan Wang**, Shaolei Wang, Wanxiang Che.
[[code](https://github.com/wyxstriker/ReweightingDisfluency)]

# 🎖 Honors and Awards
- **The Prize of First Class for the Wu Wenjun Science and Technology Award** (吴文俊人工智能科技进步一等奖), 2024
- **National Scholarship**, 2023
- Academic Scholarship, First Class 2022
- People’s Scholarship (2018, 2019, 2020)
- **1st place** in Chinese Essay Fluency Evaluation, CCL2023

# 📖 Educations
- *2022.09 - Now*, Master-Phd Student, Harbin Institute of Technology, Harbin.
- *2018.09 - 2022.06*, Undergraduate, Harbin Institute of Technology, Harbin.

# 💻 Internships
- *2025.06 - Present*, Baidu, China.
- *2023.06 - 2023.09*, Joint Laboratory of HIT and iFLYTEK Research (HFL), China.

# 🌍 Visitors
<a href="https://info.flagcounter.com/Y8dl"><img src="https://s01.flagcounter.com/map/Y8dl/size_m/txt_000000/border_CCCCCC/pageviews_1/viewers_0/flags_0/" alt="Flag Counter" border="0"></a>
