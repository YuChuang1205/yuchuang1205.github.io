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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

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
      <a href="https://arxiv.org/abs/2512.05530">Paper</a>
      <!-- | <a href="https://mind-project.github.io/">Project</a> -->
      <!-- | <a href="https://github.com/xxx/MIND">Code</a> -->
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
      <a href="https://arxiv.org/abs/2512.05511">Paper</a>
      <!-- | <a href="https://your-project-page.github.io/">Project</a> -->
      <!-- | <a href="https://github.com/your-repo">Code</a> -->
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
      <a href="https://arxiv.org/abs/xxxx.xxxxx">Paper</a> |
      <a href="https://github.com/your-repo/PAL">Code</a>
      <span style="margin-left:8px; font-weight:600;">🔥 200+⭐</span>
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

      <strong style="display:inline-block; margin:6px 0;">arXiv Preprint, 2024</strong>
    </p>
    <p class="pub-desc">
      We present a knowledge-guided learning framework that explicitly models the “why” and “how” of cross-spectral discrepancies, enabling robust and discriminative patch matching across heterogeneous spectral domains.
    </p>
    <p>
      <a href="https://arxiv.org/abs/2412.11161">Paper</a> |
      <a href="https://github.com/your-repo/knowledge-guided-cross-spectral-matching">Code</a>
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
      <a href="https://doi.org/xxxx.xxxx/xxxxx">Paper</a> |
      <a href="https://github.com/your-repo/RRLN-CrossSpectral">Code</a>
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
      <a href="https://doi.org/xxxx.xxxx/TIP.2023.xxxxx">Paper</a> |
      <a href="https://your-dataset-link/data1">Data1</a> |
      <a href="https://your-dataset-link/data2">Data2</a> |
      <a href="https://github.com/your-repo/FILN-CrossSpectral">Code</a>
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
      <a href="https://doi.org/xxxx.xxxx/TGRS.2023.xxxxx">Paper</a> |
      <a href="https://your-dataset-link/data">Data</a> |
      <a href="https://github.com/your-repo/EFRLN-CrossSpectral">Code</a>
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
      <a href="https://doi.org/xxxx.xxxx/TGRS.2025.xxxxx">Paper</a> |
      <a href="https://github.com/your-repo/MSDAN-IRSTD">Code</a>
      <span style="margin-left:8px; font-weight:600;">🔥 100+⭐</span>
    </p>
  </div>
</div>
<hr class="pub-divider">

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
