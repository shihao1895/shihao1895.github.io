---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
a {
  text-decoration: none !important;
}
a:hover {
  text-decoration: underline;
}
</style>

<style>
.edu {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}
.edu img {
  width: 110px;
  margin-right: 16px;
}
.edu div {
  font-size: 15px;
  line-height: 1.5;
}
.edu strong {
  font-weight: 600;
}
.edu a {
  color: #1a4bb3;
  text-decoration: none;
}
.edu a:hover {
  text-decoration: underline;
}
</style>

<style>
.badge {
  font-size: 13px !important;
}
</style>


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is **Hao Shi (石昊)**, a Master's student in the Department of Automation at Tsinghua University, in a joint program with MEGVII Research, advised by Prof. [Gao Huang](https://scholar.google.com/citations?user=-P9LwcgAAAAJ) and [Xiangyu Zhang](https://scholar.google.com/citations?user=yuB-cfoAAAAJ), and I also work closely with [Tiancai Wang](https://scholar.google.com/citations?user=YI0sRroAAAAJ). 

My research focuses on **Embodied AI, Robot Learning, VLA, and World Model**, aiming to build foundation models for general robotic systems. 

I am expected to join [HKU MMLab](https://mmlab.hk) as a Ph.D. student advised by Prof. [Ping Luo](https://scholar.google.com/citations?user=aXdjxb4AAAAJ) in Fall 2026.


<!-- # 🔥 News

- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


# 📝 Research

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2026</div><img src='images/papers/memoryvla_pp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MemoryVLA++: Temporal Modeling via Memory and Imagination in Vision-Language-Action Models**

**Hao Shi**, Weiye Li, Bin Xie, Yulin Wang, Renping Zhou, Tiancai Wang, Xiangyu Zhang, Ping Luo, Gao Huang✉

Under Review 2026 |
[Paper](https://arxiv.org/abs/2606.09827) |
[Code](https://github.com/shihao1895/MemoryVLA) |
[Homepage](https://shihao1895.github.io/MemoryVLA-PP-Web) |
[Huggingface](https://huggingface.co/collections/shihao1895/memoryvla)

- MemoryVLA++ is the extended journal version of MemoryVLA, advancing it from past-only memory modeling to full temporal modeling with both past memory and future imagination.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2026</div><img src='images/papers/rmbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RMBench: Memory-Dependent Robotic Manipulation Benchmark with Insights into Policy Design**

Tianxing Chen\*, Yuran Wang\*, Mingleyang Li\*, Yan Qin\*, **Hao Shi**, Zixuan Li, Yifan Hu, Yingsheng Zhang, Kaixuan Wang, Yue Chen, Hongcheng Wang, Renjing Xu, Ruihai Wu, Yao Mu, Yaodong Yang, Hao Dong✉, Ping Luo✉

Under Review 2026 |
[Paper](https://arxiv.org/abs/2603.01229) |
[Code](https://github.com/RoboTwin-Platform/RMBench) |
[Homepage](https://rmbench.github.io) |
[Huggingface](https://huggingface.co/datasets/TianxingChen/RMBench)

- RMBench is a memory-oriented benchmark built on the RoboTwin, and it also provides a memory-enhanced hierarchical VLA model, Mem-0.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/papers/memoryvla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MemoryVLA: Perceptual-Cognitive Memory in Vision-Language-Action Models for Robotic Manipulation**

**Hao Shi**, Bin Xie, Yingfei Liu, Lin Sun, Fengrong Liu, Tiancai Wang, Erjin Zhou, Haoqiang Fan, Xiangyu Zhang, Gao Huang✉

**ICLR 2026** |
**CVPR 2026 Workshop <span style="color:red">Oral</span>** |
[Paper](https://arxiv.org/abs/2508.19236) |
[Code](https://github.com/shihao1895/MemoryVLA) |
[Homepage](https://shihao1895.github.io/MemoryVLA) |
[Huggingface](https://huggingface.co/collections/shihao1895/memoryvla)

- MemoryVLA is among the early works to explore memory in VLA models, introducing a hippocampus-inspired memory to capture temporal dependencies. It has since been <span style="color:red">cited over 100 times</span>, including by [Physical Intelligence](https://www.pi.website/).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 (Oral)</div><img src='images/papers/spatial_actor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SpatialActor: Exploring Disentangled Spatial Representations for Robust Robotic Manipulation**

**Hao Shi**, Bin Xie, Yingfei Liu, Yang Yue, Tiancai Wang, Haoqiang Fan, Xiangyu Zhang, Gao Huang✉

**AAAI 2026 <span style="color:red">Oral</span> (Accept rate≈4%)** |
[Paper](https://arxiv.org/abs/2511.09555) |
[Code](https://github.com/shihao1895/SpatialActor) |
[Homepage](https://shihao1895.github.io/SpatialActor) |
[Huggingface](https://huggingface.co/collections/shihao1895/spatialactor)

- SpatialActor is a disentangled spatial representations framework for robust robotic manipulation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2026</div><img src='images/papers/geovla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GeoVLA: Enpowering 3D Representations in Vision-Language-Action Models**

Lin Sun\*, Bin Xie\*, Yingfei Liu, **Hao Shi**, Tiancai Wang, Jiale Cao✉

**IROS 2026** |
[Paper](https://arxiv.org/abs/2508.09071) |
[Code](https://github.com/linsun449/GeoVLA) |
[Homepage](https://linsun449.github.io/GeoVLA)

- GeoVLA is a unified VLA framework that bridges 2D semantics and 3D geometry.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Findings</div><img src='images/papers/deground.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DEGround: An Effective Baseline for Ego-centric 3D Visual Grounding with a Homogeneous Framework**

Yani Zhang\*, Dongming Wu\*, **Hao Shi**, Yingfei Liu, Tiancai Wang, Haoqiang Fan, Xingping Dong✉

**CVPR 2026 Findings** |
[Paper](https://arxiv.org/abs/2506.05199) |
[Code](https://github.com/zyn213/DEGround)

- DEGround is an embodied perception framework for 3D grounding, achieving 1st place on EmbodiedScan. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Report 2025</div><img src='images/papers/dexbotic.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Dexbotic: Open-Source Vision-Language-Action Toolbox**

Dexbotic Team

Technical Report 2025 |
[Paper](https://arxiv.org/abs/2510.23511/v1) |
[Code](https://github.com/Dexmal/dexbotic) |
[Homepage](https://dexbotic.com) |
[Huggingface](https://huggingface.co/collections/Dexmal/dexbotic)

- Dexbotic is an open-source VLA codebase, similar to MMDetection, that unifies mainstream VLA frameworks and benchmarks, provides strong pretrained models, and has received <span style="color:red">1200+ GitHub stars</span>.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/papers/densegrounding.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DenseGrounding: Improving Dense Language-Vision Semantics for Ego-centric 3D Visual Grounding**

Henry Zheng\*, **Hao Shi\***, Qihang Peng, Yong Xien Chng, Rui Huang, Yepeng Weng, Zhongchao Shi, Gao Huang✉

*: equal contribution, ✉: corresponding author.

**ICLR 2025** |
**CVPR 2024 Workshop <span style="color:red">Oral</span>** |
[Paper](https://arxiv.org/abs/2505.04965) |
[Code]()

- DenseGrounding is an embodied perception framework for multi-view 3D visual grounding, which won the <span style="color:red">1st Place and Innovation Award</span> in CVPR 2024 Autonomous Grand Challenge ($9000).
</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPRW 2024 (Oral)</div><img src='images/papers/denseg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DenseG: Alleviating Vision-Language Feature Sparsity in Multi-View 3D Visual Grounding**

Henry Zheng\*, **Hao Shi\***, Yong Xien Chng, Rui Huang, Zanlin Ni, Tianyi Tan, Qihang Peng, Yepeng Weng, Zhongchao Shi, Gao Huang✉

*: equal contribution, ✉: corresponding author.

**CVPR 2024 Workshop <span style="color:red">Oral</span>** |
[Paper](https://opendrivelab.github.io/Challenge%202024/multiview_THU-LenovoAI.pdf) |
[Code]()
- **1st Place** and **Innovation Award** in CVPR 2024 Autonomous Grand Challenge, Embodied 3D Grounding Track (1/64 teams, 1/154 submissions).
</div>
</div> -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/papers/oldm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Open Compound Domain Adaptation with Object Style Compensation for Semantic Segmentation**

Tingliang Feng\*, **Hao Shi\***, Xueyang Liu, Wei Feng, Liang Wan, Yanlin Zhou, Di Lin✉

*: equal contribution, ✉: corresponding author.

**NeurIPS 2023** |
[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/c74a3a6f44a44b204e26b1a6d7fe4a66-Abstract-Conference.html) |
[Code]()

- We propose a memory-bank-based object-style compensation method for open compound domain adaptation.
</div>
</div>


# 🎖 Honors and Awards
- *2026.06,*  3rd Prize in CVPR 2026 ManiSkill-ViTac Challenge
- *2026.05,*  Beijing Outstanding Graduate Award. (<span style="color:red">Only 1 Master in Dept. Automation, THU</span>)
- *2026.05,*  ICML Gold Reviewer Award.
- *2026.01,*  Tsinghua Deng Feng Fund, Tsinghua University. (￥15000)
- *2025.11,*  Minghong Scholarship, Comprehensive Excellence 1st Prize, Tsinghua University. (Top 10% in THU, ￥10000) 
- *2024.11,*  Philobiblion Scholarship, Comprehensive Excellence 1st Prize, Tsinghua University. (Top 10% in THU, ￥10000) 
- *2024.06,*  **1st Place** and **Innovation Award** in CVPR 2024 Autonomous Grand Challenge, Embodied 3D Grounding Track. (<span style="color:red">1/154 submission, $9000</span>) 
- *2023.11,*  CXMT Scholarship, Comprehensive Excellence 1st Prize, Tsinghua University. (Top 10% in THU, ￥10000) 
- *2023.06,*  Outstanding Bachelor’s Thesis Award, Tianjin University. 
<!-- - *2023.06,*  Outstanding Graduate Award, Tianjin University.  -->
- *2021.12,*  Huawei Intelligent Base Scholarship, Ministry of Education-Huawei Intelligent Base Future Stars. 


# 📖 Education
<div class="edu">
  <img src="images/hku_logo.png" alt="The University of Hong Kong">
  <div>
    <strong>2026.09 – 2030.06 (expected)</strong><br>
    Incoming Ph.D. @ <a href="https://mmlab.hk">MMLAB</a>, HKU, Hong Kong.<br>
    Advisor: Prof. <a href="https://scholar.google.com/citations?user=aXdjxb4AAAAJ">Ping Luo</a><br>
  </div>
</div>

<div class="edu">
  <img src="images/thu_logo.png" alt="Tsinghua University">
  <div>
    <strong>2023.09 – 2026.06 (expected)</strong><br>
    M.Eng. @ <a href="https://www.leaplab.ai">LeapLab</a>, Tsinghua University, Beijing.<br>
    Advisors: Prof. <a href="https://scholar.google.com/citations?user=-P9LwcgAAAAJ">Gao Huang</a> and Dr. <a href="https://scholar.google.com/citations?user=yuB-cfoAAAAJ">Xiangyu Zhang</a><br>
  </div>
</div>

<div class="edu">
  <img src="images/tju_logo.png" alt="Tianjin University">
  <div>
    <strong>2020.06 – 2023.06</strong><br>
    B.Eng. in Computer Science, Tianjin University.<br>
    Academic advisor: Prof. <a href="https://scholar.google.com/citations?user=rW0r-hMAAAAJ">Di Lin</a><br>
  </div>
</div>

<div class="edu">
  <img src="images/tju_logo.png" alt="Tianjin University">
  <div>
    <strong>2019.09 – 2020.06</strong><br>
    B.Eng. student in Materials Science, Tianjin University.
  </div>
</div>


# 💻 Internship
<div class="edu">
  <div style="display: flex; align-items: center; margin-right: 16px;">
    <img src="images/dexmal_logo.png" alt="Dexmal" style="width: 90px;">
  </div>
  <div>
    <strong>2025.03 – present</strong><br>
    <strong>Dexmal</strong>, Embodied Foundation Algorithm Group, Beijing<br>
    Mentors:
    <a href="https://scholar.google.com/citations?user=YI0sRroAAAAJ">Tiancai Wang</a>,
    <a href="https://scholar.google.com/citations?user=pF9KA1sAAAAJ">Yingfei Liu</a> and
    <a href="https://scholar.google.com/citations?user=em-nmLIAAAAJ">Bin Xie</a>
  </div>
</div>

<div class="edu">
  <div style="display: flex; align-items: center; margin-right: 16px;">
    <img src="images/megvii_logo.png" alt="MEGVII" style="width: 90px;">
  </div>
  <div>
    <strong>2024.08 – 2025.02</strong><br>
    <strong>MEGVII</strong>, Foundation Model Group, Beijing<br>
    Mentors:
    <a href="https://scholar.google.com/citations?user=YI0sRroAAAAJ">Tiancai Wang</a> and
    <a href="https://scholar.google.com/citations?user=pF9KA1sAAAAJ">Yingfei Liu</a>
  </div>
</div>


# 💬 Invited Talks
- *2026.06,*  invited talk about MemoryVLA, [CVPR 2026 MARS Workshop](https://mars-eai.github.io/CVPR-SCI-MARS-Webpage), Denver
- *2026.01,*  invited talk about SpatialActor, [AAAI 2026 Main Conference](https://aaai.org/conference/aaai/aaai-26), Singapore
- *2025.09,*  invited talk about MemoryVLA, [3D视觉工坊](https://mp.weixin.qq.com/s/m6aFuOkS-GTIxwEHro56BQ), Online
- *2025.09,*  invited talk about MemoryVLA, [具身智能之心](https://mp.weixin.qq.com/s/MNapDpvpS2zQ7zGML08rrA), Online
- *2024.06,*  invited talk about DenseGrounding, [CVPR 2024 Workshop on Foundation Models for Autonomous Systems](https://opendrivelab.com/cvpr2024/workshop), Seattle
- *2024.06,*  invited talk about DenseGrounding, [Technical Seminar on End-to-End Embodied Agent](https://starleague.ai/event2024), Shanghai


# 🎓 Service
Reviewer / PC Member: 
- International Conference on Learning Representations (ICLR)
- International Conference on Machine Learning (ICML)
- Annual Conference on Neural Information Processing Systems (NeurIPS)
- IEEE / CVF Computer Vision and Pattern Recognition Conference (CVPR)
- IEEE / CVF International Conference on Computer Vision (ICCV)
- Annual AAAI Conference on Artificial Intelligence (AAAI)
- IEEE / RSJ International Conference on Intelligent Robots and Systems (IROS)
- Transactions on Machine Learning Research (TMLR)
