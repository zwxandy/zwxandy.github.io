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

😎 Hi, I am currently a second-year master student at Institute for Artificial Intelligence, Peking University (PKU), supervised by [Prof. Meng Li](https://www.ai.pku.edu.cn/info/1158/2309.htm) and [Prof. Runsheng Wang](http://www.ai.pku.edu.cn/info/1170/1230.htm). Pior to that, I received the B.S. degree from University of Electronic Science and Technology of China (UESTC) in 2023, supervised by [Prof. Fan Zhou](https://sise.uestc.edu.cn/info/1035/9375.htm). My current research interests primarily focus on the **Efficient AI Algorithm & System, Agentic LLM, Multimodal LLM, and Reasoning.** From 2022, I have also explored a lot in the field of **Privacy-Preserving Machine Learning (PPML)**, focusing on accelerating the private inference systems via protocol-algorithm co-optimization.

📝 Welcome to my [blog](https://xuanland.blog.csdn.net), where I keep recording my study notes and knowledge summaries about computer science from 2019 (😄 300+ blogs and 80w+ visits now!).

**🌟 <font color="red">Currently, I am actively seeking Ph.D. opportunities for 2026 Fall. If you are interested in me, please contact me! My EN and CN resumes are available here:</font> [[EN](https://drive.google.com/file/d/1olqLW8GYoEe4OQcmY0q6JCK3jhF7YogQ/view?usp=sharing)] [[CN](https://drive.google.com/file/d/1xTVt7H-9TvQRSBAIHhugVtbEfy-AGBZS/view?usp=sharing)]** 😊 Kind tips: resumes may be outdated this time, but this homepage shows the latest information


# 📖 Educations
- [2023.09-2026.06] M.S. Peking University (PKU)
- [2019.09-2023.06] B.S. University of Electronic Science and Technology of China (UESTC)


# 🔥 News
- 🎉 [2025.7.30] I am happy to be invited as a Program Committee in AAAI 2026!
- 🔥 [2025.7.22] We have published our first survey on "Efficient Cross-Level Privacy-Preserving Machine Learning"! Welcome to cite and raise pull requests! Click [here](https://mp.weixin.qq.com/s/V0gn0BonQVuC4vz2oQ7knw) to see the report by SyncedTech.
- 🔥 [2025.6.26] Our team at Peking University won the **Global 1st Place🏅** in DAC System Design Contest!
- 🎉 [2025.5.21] Receive my first internship offer from Microsoft AI!
- 🎉 [2025.5.13] Welcome to my newly updated homepage! I finally change my homepage template today (lazy me 😮‍💨)
- 🎉 [2025.4.13] I am happy to be invited as a reviewer in NeurIPS 2025!
- 🥺 I hope there will be some good news in the near future 🙏 **Move on and be patient :)**


# 📝 Publications 
- Towards Efficient Privacy-Preserving Machine Learning: A Systematic Review from Protocol, Model, and System Perspectives \
  **Wenxuan Zeng\***, Tianshi Xu\*, Yi Chen\*, Yifan Zhou, Mingzhe Zhang, Jin Tan, Cheng Hong, Meng Li \
  Preprint 2025, [[Paper](https://arxiv.org/pdf/2507.14519)] [[Repo](https://github.com/PKU-SEC-Lab/Awesome-PPML-Papers)] [[Publicity](https://mp.weixin.qq.com/s/V0gn0BonQVuC4vz2oQ7knw)]
- H<sup>2</sup>EAL: Hybrid-Bonding Architecture with Hybrid Sparse Attention for Efficient Long-Context LLM Inference \
  Zizhuo Fu, Xiaotian Guo, **Wenxuan Zeng**, Shuzhang Zhong, Yadong Zhang, Peiyu Chen, Runsheng Wang, Le Ye, Meng Li \
  ICCAD 2025
- UniCAIM: A Unified CAM/CIM Architecture with Static-Dynamic KV Cache Pruning for Efficient Long-Context LLM Inference \
  Weikai Xu\*, **Wenxuan Zeng\***, Qianqian Huang, Meng Li, Ru Huang \
  DAC 2025, [[Paper](https://arxiv.org/pdf/2504.07479)]
- OptiPrime: Efficient Private Inference at ImageNet Scale \
  Jiangrui Yu, Ye Yu, Si Chen, **Wenxuan Zeng**, Junfeng Fan, Runsheng Wang, Ru Huang, Meng Li \
  Work in Progress
- MPCache: MPC-Friendly KV Cache Eviction for Efficient Private Large Language Model Inference \
  **Wenxuan Zeng**, Ye Dong, Jinjin Zhou, Junming Ma, Jin Tan, Runsheng Wang, Meng Li \
  Preprint 2025, [[Paper](arxiv.org/abs/2501.06807)]
- FlexHE: A Flexible Kernel Generation Framework for Homomorphic Encryption-Based Private Inference \
  Jiangrui Yu, **Wenxuan Zeng**, Tianshi Xu, Renze Chen, Yun (Eric) Liang, Runsheng Wang, Ru Huang, Meng Li \
  ICCAD 2024, [[Paper](https://dl.acm.org/doi/10.1145/3676536.3676739)]
- PrivQuant: Communication-Efficient Private Inference with Quantized Network/Protocol Co-Optimization \
  Tianshi Xu, Shuzhang Zhong, **Wenxuan Zeng**, Meng Li, Runsheng Wang, Ru Huang \
  ICCAD 2024, [[Paper](https://eprint.iacr.org/2024/2021.pdf)]
- BAT: Behavior-Aware Human-Like Trajectory Prediction for Autonomous Driving \
  Haicheng Liao, Zhenning Li, Huanming Shen, **Wenxuan Zeng**, Dongping Liao, Guofa Li, Shengbo Eben Li, Chengzhong Xu \
  AAAI 2024, [[Paper](https://arxiv.org/pdf/2312.06371)]
- EQO: Exploring Ultra-Efficient Private Inference with Winograd-Based Protocol and Quantization Co-Optimization \
  **Wenxuan Zeng**, Tianshi Xu, Cheng Hong, Meng Li, Runsheng Wang \
  Preprint 2024, [[Paper](https://arxiv.org/abs/2404.09404)]
- Kuaiji: the First Chinese Accounting Large Language Model \
  Jiayuan Luo, Songhua Yang, Xiaoling Qiu, Panyu Chen, Yufei Nai, **Wenxuan Zeng**, Wentao Zhang, Xinke Jiang \
  Preprint 2024, [[Paper](https://arxiv.org/abs/2402.13866)]
- CoPriv: Network/Protocol Co-Optimization for Communication-Efficient Private Inference \
  **Wenxuan Zeng**, Meng Li, Haichuan Yang, Wen-jie Lu, Runsheng Wang, Ru Huang \
  NeurIPS 2023, [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/f96839fc751b67492e17e70f5c9730e4-Paper-Conference.pdf)]
- MPCViT: Searching for Accurate and Efficient MPC-friendly Vision Transformer with Heterogeneous Attention \
  **Wenxuan Zeng**, Meng Li, Wenjie Xiong, Tong Tong, Wen-jie Lu, Jin Tan, Runsheng Wang, Ru Huang \
  ICCV 2023, [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Zeng_MPCViT_Searching_for_Accurate_and_Efficient_MPC-Friendly_Vision_Transformer_with_ICCV_2023_paper.pdf)]
- Factual Error Correction via Iterative Constrained Editing \
  Jiangjie Chen\*, Rui Xu\*, **Wenxuan Zeng**, Changzhi Sun, Lei Li, Yanghua Xiao \
  AAAI 2023, [[Paper](https://arxiv.org/pdf/2211.12130)]
- Connecting the Hosts: Street-Level IP Geolocation with Graph Neural Networks \
  Zhiyuan Wang\*, Fan Zhou\*, **Wenxuan Zeng\***, Goce Trajcevski, Chunjing Xiao, Yong Wang, Kai Chen \
  KDD 2022, [[Paper](https://cse.hkust.edu.hk/~kaichen/papers/ipgeo-kdd22.pdf)]


# 🎖 Honors and Awards
- [2024] Third Prize Scholarship at Peking University
- [2024] Merit Student Scholarship at Peking University
- [2023] Outstanding Graduate Student and Honors Research Certificate at UESTC
- [2020,2021,2022] Outstanding Student Scholarship and "Innovation and Entrepreneurship Training Plan" at UESTC
- [2022] Special Prize of “Tencent” Scholarship (3 Places at UESTC in Total)
- [2021] First Prize of “Shi Qiang” Scholarship (5 Places at UESTC in Total)


# 🏆 Contest Awards
- [2025] DAC system design on "On-Device Multi-modal Generative AI for Science", **Global 1st Place**
- [2024,2025] Badminton Competition of Institute for Artificial Intelligence at Peking University, **The 2nd, 3rd Prize**
- [2023] Annual Symposium and Tech Day of Institute for Artificial Intelligence at Peking University, **Most Popular Award**
- [2023] China Collegiate Computing Contest, **National Special Prize (the 1st Place)**
- [2022] "Pan-Pearl River Delta" Collegiate Computer Work Competition, **National Third Prize**
- [2021] China Collegiate Computing Contest, **National First Prize (the 1st Place)**
- [2021] "Zhong Gong Cup" Sichuan Collegiate Computer Work Competition, **Provincial Special Prize**


# 💬 Invited Activities
- [2025.1] Display our NeurIPS poster at West Lake Forum on Cyberspace Security 2024, Zhejing University, Hangzhou
- [2024.5] Record and launch the course about "Privacy-Preserving Machine Learning" with Ant Group [[Link](https://mp.weixin.qq.com/s/bRArxUSOPhXMzgrYvKH61w?poc_token=HGpRI2ijFv-TLpPwDOCH4lqhNrabIKX1RSonfT6O)]


# 💻 Internships
- [2025.5-present] Microsft Research Asia (supervised by [Dr. Mengyu Zhou](https://zmy.io/))
- [2022.6-present] Institute for Artificial Intelligence, Peking University (supervised by [Prof. Meng Li](https://www.ai.pku.edu.cn/info/1158/2309.htm) and [Prof. Runsheng Wang](http://www.ai.pku.edu.cn/info/1170/1230.htm))
- [2022.4-2022.7] Knowledge Works Research Laboratory, Fudan University (supervised by [Prof. Yanghua Xiao](http://kw.fudan.edu.cn/people/xiaoyanghua/))
- [2021.6-2022.6] Sichuan Key Laboratory of Network and Data Security, UESTC (supervised by [Prof. Fan Zhou](https://sise.uestc.edu.cn/info/1035/9375.htm))
- [2021.8-2022.5] Communication and Information Security Laboratory, Peking University (supervised by [Prof. Yuesheng Zhu](https://www.ece.pku.edu.cn/en/info/1057/1175.htm))

# 📚 Academic Services
- Serving as a reviewer of NeurIPS 2025, EMNLP 2025, AAAI 2026

# 💡 Lifestyle
- "Life is not about waiting for the storm to pass, but about learning to dance in the rain." - Helen Keller

- I am self-motivated at work, but I also seek balance and happiness in my life. "Reading thousands of books and traveling thousands of miles."

<!-- 很喜欢大冰老师的一句话："愿既可以朝九晚五，又可以浪迹天涯" -->

- My hobbies include but are not limited to 🎤singing, 🎸guitar, 🏂skiing, 🏸badminton, and various novel and interesting things like Rubik's Cube. Feel free to discuss these interests and hobbies with me!

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Guitar</div><img src='images/guitar.png' alt="sym" width="70%"></div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Skiing</div><img src='images/skiing.jpg' alt="sym" width="180%"></div></div>
