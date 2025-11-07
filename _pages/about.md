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

My name is **Hao Shi (石昊)**, a third-year Master's student in the Department of Automation at Tsinghua University, in a joint program with MEGVII Research, advised by Prof. [Gao Huang](https://scholar.google.com/citations?user=-P9LwcgAAAAJ) and [Xiangyu Zhang](https://scholar.google.com/citations?user=yuB-cfoAAAAJ), and I also work closely with [Tiancai Wang](https://scholar.google.com/citations?user=YI0sRroAAAAJ). 

Previously, I received my Bachelor's degree from the College of Intelligence and Computing at Tianjin University in 2023, advised by Prof. [Di Lin](https://dilincv.github.io). 

My research interests lie primarily in **Embodied AI, Robot Learning, VLA, and 3D Perception**. I am dedicated to exploring foundation models for general robotic systems. 

I am expected to join [HKU MMLab](https://mmlab.hk) as a Ph.D. student advised by Prof. [Ping Luo](https://scholar.google.com/citations?user=aXdjxb4AAAAJ) in Fall 2026.

<!-- # 🔥 News

- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Education
- *2023.09 - 2026.06 (expected)*, M.Eng. in AI, Department of Automation, Tsinghua University, Beijing.
  - Advisors: Prof. [Gao Huang](https://scholar.google.com/citations?user=-P9LwcgAAAAJ) and [Xiangyu Zhang](https://scholar.google.com/citations?user=yuB-cfoAAAAJ)
  - GPA: 3.8 / 4.0
- *2020.06 - 2023.06*, B.Eng. in Computer Science, College of Intelligence and Computing, Tianjin University. 
  - Academic advisor: Prof. [Di Lin](https://dilincv.github.io)
  - GPA: 3.81 / 4.0, 91.2 / 100
- *2019.09 - 2020.06*, B.Eng. student in Materials Science, School of Materials Science and Engineering, Tianjin University. 

# 📝 Research
## Selected Works

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2025</div><img src='images/papers/memoryvla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[MemoryVLA: Perceptual-Cognitive Memory in Vision-Language-Action Models for Robotic Manipulation](https://shihao1895.github.io/MemoryVLA)**

**Hao Shi**, Bin Xie, Yingfei Liu, Lin Sun, Fengrong Liu, Tiancai Wang, Erjin Zhou, Haoqiang Fan, Xiangyu Zhang, Gao Huang✉

- MemoryVLA is a Cognition-Memory-Action framework for robotic manipulation inspired by human memory systems. It builds a hippocampal-like perceptual-cognitive memory to capture the temporal dependencies essential for current decision-making, enabling long-horizon, temporally aware action generation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Technical Teport 2025</div><img src='images/papers/dexbotic.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Dexbotic: Open-Source Vision-Language-Action Toolbox](https://dexbotic.com)**

Dexbotic Team

- Dexbotic is an open-source VLA toolbox for embodied AI research (similar to MMDetection). It provides a unified and experiment-centric codebase that supports multiple mainstream VLA frameworks and benchmarks within a single environment, and offers stronger pretrained models.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/papers/densegrounding.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[DenseGrounding: Improving Dense Language-Vision Semantics for Ego-centric 3D Visual Grounding](https://arxiv.org/pdf/2505.04965)**

Henry Zheng\*, **Hao Shi\***, Qihang Peng, Yong Xien Chng, Rui Huang, Yepeng Weng, Zhongchao Shi, Gao Huang✉

*: equal contribution, ✉: corresponding author.

- DenseGrounding is a framework for embodied 3D visual grounding. It tackles the loss of fine-grained visual semantics from sparse fusion of point clouds with multi-view images, as well as the limited textual semantic context from arbitrary instructions, enabling more accurate and context-aware grounding.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2025</div><img src='images/papers/spatial_actor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[SpatialActor: Exploring Disentangled Spatial Representations for Robust Robotic Manipulation]()**

**Hao Shi**, Bin Xie, Yingfei Liu, Yang Yue, Tiancai Wang, Haoqiang Fan, Xiangyu Zhang, Gao Huang✉
- SpatialActor is a disentangled framework for robust robotic manipulation. It decouples perception into complementary high-level geometry from fine-grained but noisy raw depth and coarse but robust depth expert priors, along with low-level spatial cues and appearance semantics.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPRW 2024</div><img src='images/papers/denseg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[DenseG: Alleviating Vision-Language Feature Sparsity in Multi-View 3D Visual Grounding](https://opendrivelab.github.io/Challenge%202024/multiview_THU-LenovoAI.pdf)**

Henry Zheng\*, **Hao Shi\***, Yong Xien Chng, Rui Huang, Zanlin Ni, Tianyi Tan, Qihang Peng, Yepeng Weng, Zhongchao Shi, Gao Huang✉

*: equal contribution, ✉: corresponding author.

- **1st Place** and **Innovation Award** in CVPR 2024 Autonomous Grand Challenge, Embodied 3D Grounding Track (1/64 teams, 1/154 submissions). 
- **Oral Presentation** at CVPR 2024 Workshop on Foundation Models for Autonomous Systems.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/papers/oldm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Open Compound Domain Adaptation with Object Style Compensation for Semantic Segmentation](https://proceedings.neurips.cc/paper_files/paper/2023/file/c74a3a6f44a44b204e26b1a6d7fe4a66-Paper-Conference.pdf)**

Tingliang Feng\*, **Hao Shi\***, Xueyang Liu, Wei Feng, Liang Wan, Yanlin Zhou, Di Lin✉

*: equal contribution, ✉: corresponding author.

- We propose object style compensation for open compound domain adaptation. It builds an object-level discrepancy memory bank to capture fine-grained source–target domain gaps and compensates target features to align with source distribution, enabling cross-domain segmentation. 
</div>
</div>


## Other Works

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2025</div><img src='images/papers/geovla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[GeoVLA: Enpowering 3D Representations in Vision-Language-Action Models](https://arxiv.org/pdf/2508.09071)**

Lin Sun\*, Bin Xie\*, Yingfei Liu, **Hao Shi**, Tiancai Wang, Jiale Cao✉
- GeoVLA is a framework that bridges 2D semantics and 3D geometry for VLA. By encoding geometric embeddings with a dual-stream design and leveraging a Mixture-of-Experts 3D-Aware Action Expert, it achieves robustness across diverse camera views, object heights, and sizes.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2025</div><img src='images/papers/deground.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Grounding Beyond Detection: Enhancing Contextual Understanding in Embodied 3D Grounding](https://arxiv.org/pdf/2506.05199)**

Yani Zhang\*, Dongming Wu\*, **Hao Shi**, Yingfei Liu, Tiancai Wang, Haoqiang Fan, Xingping Dong✉
- DEGround transfers general proposals from detection into grounding with shared queries, and mitigates vision–language misalignment through region activation and query-wise modulation, achieving 1st place on EmbodiedScan. 
</div>
</div>


# 🎖 Honors and Awards
- *2025.11,*  Minghong Scholarship, Comprehensive Excellence 1st Prize, Tsinghua University. (**Top 10% in THU, ￥10000**) 
- *2024.11,*  Philobiblion Scholarship, Comprehensive Excellence 1st Prize, Tsinghua University. (**Top 10% in THU, ￥10000**) 
- *2024.06,*  **1st Place** and **Innovation Award** in CVPR 2024 Autonomous Grand Challenge, Embodied 3D Grounding Track. (<span style="color:red">1/154 submission, $9000</span>) 
- *2023.11,*  CXMT Scholarship, Comprehensive Excellence 1st Prize, Tsinghua University. (**Top 10% in THU, ￥10000**) 
- *2023.06,*  Outstanding Bachelor’s Thesis Award, Tianjin University. 
- *2023.06,*  Excellent Graduate Award, Tianjin University. 
- *2021.12,*  Ministry of Education-Huawei Intelligent Base Future Stars. 
- *2021.12,*  Huawei Intelligent Base Scholarship. 


# 💻 Internship
- *2024.08 - now*, MEGVII and Dexmal, Beijing.
  - Department: Embodied Fundation Research Group.
  - Mentors: [Tiancai Wang](https://scholar.google.com/citations?user=YI0sRroAAAAJ), [Yingfei Liu](https://scholar.google.com/citations?user=pF9KA1sAAAAJ) and [Bin Xie](https://xb534.github.io).


# 💬 Invited Talks
- *2025.09,*  invited talk about MemoryVLA, [3D视觉工坊](https://mp.weixin.qq.com/s/m6aFuOkS-GTIxwEHro56BQ), Online
- *2025.09,*  invited talk about MemoryVLA, [具身智能之心](https://mp.weixin.qq.com/s/MNapDpvpS2zQ7zGML08rrA), Online
- *2024.06,*  invited talk about DenseGrounding, [CVPR 2024 Workshop on Foundation Models for Autonomous Systems](https://opendrivelab.com/cvpr2024/workshop), Seattle
- *2024.06,*  invited talk about DenseGrounding, [Technical Seminar on End-to-End Embodied Agent](https://starleague.ai/event2024), Shanghai


# 🎓 Service
Reviewer / PC Member: 
- ICLR 2026, ICLR 2025
- AAAI 2026
- ICCV 2025

