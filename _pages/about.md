---
permalink: /
title: "Welcome to YuChuang's homepage!"
excerpt: "Homepage"
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

<h1 style="border-bottom: none;">Welcome to my website! 😆😆😆</h1>

I am now working on Multi-image/video understanding and reasoning, Infrared small target detection, and Multimodal image registration. If you are seeking any form of <span style="color:#8B0000; font-weight:600;">academic cooperation (学术合作)</span>, please feel free to email me at [**yuchuang@sia.cn**](yuchuang@sia.cn) / [**yuchuang1205@163.com**](yuchuang1205@163.com). 


I am a PHD student in the University of the Chinese Academy of Sciences's Master-Doctor combined program, supervised by Prof. Yunpeng Liu.


Since October 2024, I have been honored to be a visiting Ph.D at [**CUHK-MMLab**](https://mmlab.ie.cuhk.edu.hk/people.html), under the supervision of Prof. [**Xiangyu Yue**](https://xyue.io/).


I won the CAS President Award - Special Prize (<span style="color:#8B0000; font-weight:600;">中国科学院院长特别奖</span>, Top 0.1%) in 2025 and was twice awarded the **National Scholarship for PHD Students** in 2022 and 2024.

I won **the 1st place** of _Water Body Extraction from High-resolution and Multi-modal Optical Images in the 2024 ISPRS TC I Contest on Intelligent Interpretation for Multi-modal Remote Sensing Application_ (Team leader) and **the 1st prize** in the _PRCV2024 Wide-area Infrared Small Target Detection Challenge_ (Team leader).

<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->


# 🔥 News 🔥 
-*2022.02*: &nbsp;🎉🎉 

<!--
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
--> 

# 📝 Publications 

-----
<style>
  .pub-item {
    display: flex;
    align-items: flex-start; /* 改为顶部对齐，防止图片被拉伸变形 */
    margin-bottom: 30px;
    background-color: transparent;
  }
  
  .pub-item img {
    margin-right: 20px;   /* 图片与文字的间距 */
    width: 220px;         /* 缩小图片宽度，使其高度更容易与简短的文字对齐 */
    height: auto;         /* 确保图片按比例缩放，不被裁剪或拉伸 */
    flex-shrink: 0;       /* 防止图片被 flex 容器挤压 */
    border-radius: 4px;
    object-fit: contain;  /* 确保内容完整 */
  }

  /* 右侧内容容器 */
  .pub-content {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }

  /* 论文标题：调小字体 */
  .pub-item h3 {
    margin-top: 0;
    margin-bottom: 5px;
    font-size: 1.0rem;    /* 与正文 H3 接近，或设为 1.05rem */
    line-height: 1.3;
  }
  
  /* 作者、期刊信息：调小字体，与上面 News 字体大小一致 */
  .pub-item p {
    line-height: 1.4;     /* 增加行高，让文字占据的空间稍微变大，匹配图片高度 */
    font-size: 0.85rem;   /* 这里的 0.85-0.9rem 通常是标准正文的大小 */
    margin: 0;
    color: #333;
  }

  /* 描述文字 */
  .pub-desc {
    margin-top: 5px !important;
    margin-bottom: 8px !important;
    color: #555;
    font-style: italic;
    font-size: 0.85rem !important; /* 保持一致的小号字体 */
    line-height: 1.4 !important;
  }

  /* 链接颜色 */
  .pub-content a {
    font-size: 0.85rem;
  }

  .pub-divider {
    border: none;
    border-top: 1px solid #eee;
    margin: 20px 0;
  }
</style>


<div class="pub-item">
  <img src="../images/MIND_main.png">
  <div class="pub-content">
    <h3>MIND: Multi-rationale INtegrated Discriminative Reasoning Framework for Multi-modal Large Models</h3>
    <p>
      <strong><u>Chuang Yu</u></strong>, Jinmiao Zhao, Mingxuan Zhao, Yunpeng Liu*, Xiujun Shu, Yuanhao Feng, Bo Wang, Xiangyu Yue*<br>

      <strong style="display:inline-block; margin:6px 0;">arXiv Preprint, 2025</strong>
    </p>
    <p class="pub-desc">
      We propose MIND, a multi-rationale integrated discriminative reasoning framework that enhances multi-modal large models through structured rationale integration and hard negative discrimination.
    </p>
    <p>
      <a href="https://arxiv.org/abs/2512.05530">Paper</a> |
      <!-- | <a href="https://mind-project.github.io/">Project</a> -->
      <a href="https://github.com/YuChuang1205/MIND">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/FDEP_main.png">
  <div class="pub-content">
    <h3>Rethinking Infrared Small Target Detection: A Foundation-Driven Efficient Paradigm</h3>
    <p>
      <strong><u>Chuang Yu</u></strong>, Jinmiao Zhao, Yunpeng Liu*, Yaokun Li, Xiujun Shu, Yuanhao Feng, Bo Wang, Yimian Dai, Xiangyu Yue*<br>

      <strong style="display:inline-block; margin:6px 0;">arXiv Preprint, 2025</strong>
    </p>
    <p class="pub-desc">
      We rethink infrared small target detection from a foundation-model perspective and propose an efficient, foundation-driven paradigm that improves generalization and deployment efficiency across diverse infrared scenarios.
    </p>
    <p>
      <a href="https://arxiv.org/abs/2512.05511">Paper</a> |
      <!-- | <a href="https://your-project-page.github.io/">Project</a> -->
      <a href="https://github.com/YuChuang1205/FDEP-Framework">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/PAL_main.png">
  <div class="pub-content">
    <h3>From Easy to Hard: Progressive Active Learning Framework for Infrared Small Target Detection with Single Point Supervision</h3>
    <p>
      <strong><u>Chuang Yu</u></strong>, Jinmiao Zhao, Yunpeng Liu*, Sicheng Zhao, Yimian Dai, Xiangyu Yue*<br>

      <strong style="display:inline-block; margin:6px 0;">ICCV 2025 (Accepted)</strong>
    </p>
    <p class="pub-desc">
      We propose a progressive active learning framework that transitions from easy to hard samples for infrared small target detection under single-point supervision, significantly reducing annotation cost while improving detection robustness.
    </p>
    <p>
      <a href="https://openaccess.thecvf.com/content/ICCV2025/html/Yu_From_Easy_to_Hard_Progressive_Active_Learning_Framework_for_Infrared_ICCV_2025_paper.html">Paper</a> |
      <a href="https://github.com/YuChuang1205/PAL">Code</a>
      <span style="margin-left:8px; font-weight:600;">🔥 Github 200+⭐</span>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/KGL-Net_main.png">
  <div class="pub-content">
    <h3>Why and How: Knowledge-Guided Learning for Cross-Spectral Image Patch Matching</h3>
    <p>
      <strong><u>Chuang Yu</u></strong>, Yunpeng Liu*, Jinmiao Zhao, Xiangyu Yue*<br>

      <strong style="display:inline-block; margin:6px 0;">arXiv Preprint, 2025</strong>
    </p>
    <p class="pub-desc">
      We present a knowledge-guided learning framework that explicitly models the “why” and “how” of cross-spectral discrepancies, enabling robust and discriminative patch matching across heterogeneous spectral domains.
    </p>
    <p>
      <a href="https://arxiv.org/abs/2412.11161">Paper</a> |
      <a href="https://github.com/YuChuang1205/KGL-Net">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/MSDA-Net_main.png">
  <div class="pub-content">
    <h3>Multi-Scale Direction-Aware Network for Infrared Small Target Detection</h3>
    <p>
      Jinmiao Zhao, Zelin Shi*, <strong><u>Chuang Yu</u></strong>, Yunpeng Liu, Xinyi Ying, Yimian Dai<br>

      <strong style="display:inline-block; margin:6px 0;">IEEE Transactions on Geoscience and Remote Sensing, 2025 (Accepted)</strong>
    </p>
    <p class="pub-desc">
      We propose a multi-scale direction-aware network that explicitly models directional and scale-sensitive cues, significantly enhancing infrared small target detection performance under complex backgrounds.
    </p>
    <p>
      <a href="https://arxiv.org/abs/2406.02037">Paper</a> |
      <a href="https://github.com/YuChuang1205/MSDA-Net">Code</a>
      <span style="margin-left:8px; font-weight:600;">🔥 Github 100+⭐</span>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/FEST_main.png">
  <div class="pub-content">
    <h3>Towards Robust Infrared Small Target Detection: A Feature-Enhanced and Sensitivity-Tunable Framework</h3>
    <p>
      Jinmiao Zhao, Zelin Shi*, <strong><u>Chuang Yu</u></strong>, Yunpeng Liu, Yimain Dai<br>

      <strong style="display:inline-block; margin:6px 0;">Knowledge-Based Systems, 2025 (Accepted)</strong>
    </p>
    <p class="pub-desc">
      We propose a feature-enhanced and sensitivity-tunable framework that improves robustness for infrared small target detection by adaptively balancing feature representation and detection sensitivity under complex backgrounds.
    </p>
    <p>
      <a href="https://arxiv.org/abs/2407.20090">Paper</a> |
      <a href="https://github.com/YuChuang1205/FEST-Framework">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">


<div class="pub-item">
  <img src="../images/RRL-Net_main.png">
  <div class="pub-content">
    <h3>Relational Representation Learning Network for Cross-Spectral Image Patch Matching</h3>
    <p>
      <strong><u>Chuang Yu</u></strong>, Yunpeng Liu*, Jinmiao Zhao, Dou Quan, Xiangyu Yue*<br>

      <strong style="display:inline-block; margin:6px 0;">Information Fusion, 2024 (Accepted)</strong>
    </p>
    <p class="pub-desc">
      We propose a relational representation learning network that explicitly models cross-spectral relationships, enabling robust and discriminative image patch matching across heterogeneous spectral modalities.
    </p>
    <p>
      <a href="https://arxiv.org/abs/2403.11751">Paper</a> |
      <a href="https://github.com/YuChuang1205/RRL-Net">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/FIL-Net_main.png">
  <div class="pub-content">
    <h3>Feature Interaction Learning Network for Cross-Spectral Image Patch Matching</h3>
    <p>
      <strong><u>Chuang Yu</u></strong>, Yunpeng Liu*, Jinmiao Zhao, Shuhang Wu, Zhuhua Hu<br>

      <strong style="display:inline-block; margin:6px 0;">IEEE Transactions on Image Processing, 2023 (Accepted)</strong>
    </p>
    <p class="pub-desc">
      We propose a feature interaction learning network that explicitly models inter-feature relationships across heterogeneous spectra, significantly improving robustness and discriminability for cross-spectral image patch matching.
    </p>
    <p>
      <a href="https://ieeexplore.ieee.org/document/10251126">Paper</a> |
      <a href="https://github.com/YuChuang1205/VIS-LWIR-patch-dataset">Data1</a> |
      <a href="https://github.com/YuChuang1205/SEN1-2-patch-dataset">Data2</a> |
      <a href="https://github.com/YuChuang1205/RRL-Net">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/EFR-Net_main.png">
  <div class="pub-content">
    <h3>Efficient Feature Relation Learning Network for Cross-Spectral Image Patch Matching</h3>
    <p>
      <strong><u>Chuang Yu</u></strong>, Jinmiao Zhao, Yunpeng Liu*, Shuhang Wu, Chenxi Li<br>

      <strong style="display:inline-block; margin:6px 0;">IEEE Transactions on Geoscience and Remote Sensing, 2023 (Accepted)</strong>
    </p>
    <p class="pub-desc">
      We propose an efficient feature relation learning network that models cross-spectral feature interactions with low computational overhead, achieving accurate and scalable image patch matching across heterogeneous spectral modalities.
    </p>
    <p>
      <a href="https://ieeexplore.ieee.org/document/10164118">Paper</a> |
      <a href="https://github.com/YuChuang1205/OS-patch-dataset">Data</a> |
      <a href="https://github.com/YuChuang1205/RRL-Net">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/MFD-Net_main.png">
  <div class="pub-content">
    <h3>Multi-branch Feature Difference Learning Network for Cross-Spectral Image Patch Matching</h3>
    <p>
      <strong><u>Chuang Yu</u></strong>, Yunpeng Liu*, Chenxi Li et al.<br>

      <strong style="display:inline-block; margin:6px 0;">IEEE Transactions on Geoscience and Remote Sensing, 2022 (Accepted)</strong>
    </p>
    <p class="pub-desc">
      We propose a multi-branch feature difference learning network that explicitly captures cross-spectral discrepancies via complementary branches, enabling robust and discriminative image patch matching across heterogeneous spectral domains.
    </p>
    <p>
      <a href="https://ieeexplore.ieee.org/document/9777946">Paper</a> |
      <a href="https://github.com/YuChuang1205/MFD-Net">Code1</a> |
      <a href="https://github.com/YuChuang1205/RRL-Net">Code2</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

# 🏆 Honors and Awards
- *2025* <strong>CAS President Award – Special Prize (中国科学院院长特别奖) (Top 0.1%)</strong>  ([news report](http://www.sia.cas.cn/xwzx/zhxw/202506/t20250624_7874445.html))
- *2024* <strong>The 1st place of Water Body Extraction from High-resolution and Multi-modal Optical Images in the 2024 ISPRS TC I Contest on Intelligent Interpretation for Multi-modal Remote Sensing Application (Team leader)</strong> ([news report](http://www.sia.cas.cn/xwzx/kydt/202405/t20240527_7173244.html))
- *2024* <strong>The 1st prize in the PRCV2024 Wide-area Infrared Small Target Detection Challenge (Team leader)</strong> ([news report](http://www.sia.cas.cn/xwzx/kydt/202411/t20241113_7438837.html))
- *2024* The 2nd prize in the ICPR 2024 Resource-Limited Infrared Small Target Detection Challenge Track 1. (Team leader)
- *2024* The 2nd prize in the ICPR 2024 Resource-Limited Infrared Small Target Detection Challenge Track 2. (Team leader)
- *2024* The 3rd prize of the First "Shensi Cup" - Urban Lifeline·AI Problem Solving Challenge. (Team leader)
- *2024* The 3rd place of Marine Farms Segmentation in High-Resolution SAR Images in the 5TH Gaofen Challenge on Automated High Resolution Earth Observation Image Interpretation (Team leader)
- *2024 and 2022* <strong>National Scholarship (Top 1%)</strong>
- *2024* <strong>Outstanding Communist Youth League Member of CAS (Top 0.1%) </strong>  ([news report](http://www.sia.cas.cn/dj/gzdt/202405/t20240509_7156313.html))
- *2023* Outstanding Graduate Student Award of Shenyang Institute of Automation, CAS (Top 1%)
- *2023 and 2024* <strong>Pacemaker to Merit Student of the University of Chinese Academy of Sciences (Top 1%)</strong>
- *2021, 2023 and 2024* First Class Academic Scholarship of Shenyang Institute of Automation, CAS (Top 10%)
- *2020* Outstanding Graduates (Top 1%)
- *2019* The 2nd prize of China Collegiate Computing Contest Artificial Intelligence Innovation Contest. (Team leader)

<!--
# 🚀 Some personal news reports:
- **CAS President Award – Special Prize**（中国科学院院长特别奖） 
- **1st Place**, Water Body Extraction, *ISPRS TC I Contest 2024* 
- **1st Prize**, PRCV 2024 Wide-area Infrared Small Target Detection Challenge 
- **Outstanding Communist Youth League Member of CAS** 
-->

<!--
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->

# ⚡ Academic Service:
- Conference Reviewer: CVPR, ICCV, ICPR, etc.
- Journal Reviewer: TGRS, Inf. Fusion, KBS, ESWA, EAAI, JSTARS, IPT,  Neurocomputing, etc.  


# 🎯 Hobbies
- 🍳 Cooking and exploring different cuisines
- 🏃 Running and physical conditioning
- 🎧 Music appreciation
- 🎬 Watching films
