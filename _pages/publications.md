---
layout: page
title: publications
permalink: /publications/
description: Publications in reverse chronological order.
nav: true
nav_order: 2
---

<style>
  .post {
    --publication-accent: #4f7183;
    --publication-accent-hover: #2f6177;
    --publication-title: #667d89;
    --publication-venue: #315f75;
  }

  .corresponding-mark {
    display: inline-block;
    margin-left: 0.16em;
    color: var(--publication-accent);
    font-family: Arial, sans-serif;
    font-size: 0.72em;
    font-style: normal;
    font-weight: 400;
    line-height: 1;
    vertical-align: 0.38em;
  }

  .corresponding-note {
    color: var(--global-text-color-light);
    font-size: 0.9rem;
  }

  .publication-code i {
    margin-right: 0.18em;
    font-size: 0.92em;
    vertical-align: -0.02em;
  }

  .publication-code {
    color: var(--publication-accent);
  }

  .publication-code:hover {
    color: var(--publication-accent-hover);
  }

  .post article li a:not(.publication-code) {
    color: var(--publication-title);
  }

  .post article li a:not(.publication-code):hover {
    color: var(--publication-accent-hover);
  }

  .post article li > p {
    margin-bottom: 0;
    line-height: 1.5;
  }

  .post article ul {
    padding-left: 0;
    list-style: none;
  }

  .post article li {
    position: relative;
    margin-bottom: 0.85rem;
    padding-left: 1rem;
    line-height: 1.5;
  }

  .post article li::before {
    position: absolute;
    top: 0.72rem;
    left: 0.05rem;
    width: 0.38rem;
    height: 0.38rem;
    border: 1.5px solid var(--publication-accent);
    border-radius: 50%;
    content: "";
  }

  /* Put the paper title on its own line; metadata flows below it. */
  .post article li > p > a:not(.publication-code):first-of-type,
  .post article li > a:not(.publication-code):first-of-type,
  .publication-title {
    display: block;
    min-height: 1.65em;
    margin-bottom: 0.12rem;
    color: var(--publication-title);
    font-weight: 500;
    line-height: 1.4;
  }

  /* The venue is the final emphasized phrase in each publication entry. */
  .post article li strong:last-of-type {
    color: var(--publication-venue);
    font-weight: 400;
  }

  .post article li strong:not(:last-of-type) {
    color: var(--publication-accent);
  }

  .post article li strong:last-of-type::before {
    content: "\A";
    white-space: pre;
  }

  .pub-rank {
    float: right;
    display: inline-flex;
    align-items: center;
    margin: 0.18em 0 0 0.6em;
    padding: 0.1em 0.55em;
    border: 1px solid transparent;
    border-radius: 999px;
    font-size: 0.78em;
    font-weight: 650;
    line-height: 1.35;
    letter-spacing: 0.015em;
    vertical-align: 0.12em;
    white-space: nowrap;
  }

  .pub-rank.rank-a {
    border-color: rgb(192 57 43 / 22%);
    background: rgb(192 57 43 / 10%);
    color: #c0392b;
  }

  .pub-rank.rank-b {
    border-color: rgb(41 98 163 / 22%);
    background: rgb(41 98 163 / 10%);
    color: #2962a3;
  }

  .pub-rank.rank-cn {
    border-color: rgb(35 126 105 / 22%);
    background: rgb(35 126 105 / 10%);
    color: #237e69;
  }
</style>


You can also find my articles on [Google Scholar](https://scholar.google.com/citations?user=oab9IRYAAAAJ&hl=en).

<span class="corresponding-note"><span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span> indicates the corresponding author</span>

### 2026
* <span class="pub-rank rank-a">CCF-A</span> [Enabling Proactive Spoken Turns via a Generalized Style-Aware Full-Duplex Framework]() Tianrui Pan, Qinglin Zhang, Chong Deng, Luyao Cheng, Qian Chen, Wen Wang, Jie Tang, Gangshan Wu, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>. **ACM MM**, 2026.

* <span class="pub-rank rank-b">CCF-B</span> [RASR: Retrieval-Augmented Super Resolution for Practical Reference-Based Image Restoration](https://arxiv.org/pdf/2508.09449?) Jiaqi Yan, Shuning Xu, Xiangyu Chen<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Dell Zhang, Jiantao Zhou, Jie Tang, GangshanWu, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>. **ISCAS**, 2026.

* <span class="pub-rank rank-a">CCF-A</span> [Disentangled Textual Priors for Diffusion-based Image Super-Resolution](https://arxiv.org/abs/2603.07430) Lei Jiang, Xin Liu, Xinze Tong, Zhiliang Li, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu. **CVPR**, 2026. <a class="publication-code" href="https://github.com/JL6666JL/DTPSR" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

* <span class="pub-rank rank-a">CCF-A</span> [GLAD: Generative Language-Assisted Visual Tracking for Low-Semantic Templates](https://link.springer.com/article/10.1007/s11263-026-02774-7) Xingyu Luo, Yidong Cai, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, Gangshan Wu, and Limin Wang. **IJCV**, 2026. <a class="publication-code" href="https://github.com/Confetti-lxy/GLAD" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

### 2025
* <span class="pub-rank rank-cn">中文 CCF-A</span> [基于多尺度特征自适应调制的单图像超分辨率网络](https://www.ejournal.org.cn/thesisDetails#10.12263/DZXB.20250032&lang=zh) 沈伟露, **刘杰**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, 唐杰, 武港山. **《电子学报》**, 2025.

* <span class="pub-rank rank-a">CCF-A</span> [In-the-wild Audio Spatialization with Flexible Text-guided Localization.](https://arxiv.org/pdf/2506.00927) Tianrui Pan, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Zewen Huang, Jie Tang, and Gangshan Wu. **ACL Main (Oral)**, 2025. <a class="publication-code" href="https://github.com/Alice01010101/TASU" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>


* <span class="pub-rank rank-b">CCF-B</span> [FSDM: An Efficient Video Super-Resolution Method Based On Frames-Shift Diffusion Model.](https://www.sciencedirect.com/science/article/abs/pii/S0893608025003144) Shijie Yang, Chao Chen, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu. **Neural Networks**, 2025.

* <span class="pub-rank rank-b">CCF-B</span> <span class="publication-title">Towards Practical Real-Time Low-Latency Music Source Separation.</span> Junyu Wu, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Tianrui Pan, Jie Tang, and Gangshan Wu. **ICME**, 2025.

* <span class="pub-rank rank-a">CCF-A</span> [CATANet: Efficient Content-Aware Token Aggregation for Lightweight Image Super-Resolution.](https://arxiv.org/abs/2503.06896) Xin Liu, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu. **CVPR**, 2025. <a class="publication-code" href="https://github.com/EquationWalker/CATANet" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

* <span class="pub-rank rank-a">CCF-A</span> [AutoLUT: LUT-Based Image Super-Resolution with Automatic Sampling and Adaptive Residual Learning.](https://www.arxiv.org/abs/2503.01565) Yuheng Xu, Shijie Yang, Xin Liu, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu. **CVPR**, 2025. <a class="publication-code" href="https://github.com/SuperKenVery/AutoLUT" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

### 2024
* <span class="pub-rank rank-a">CCF-A</span> [RAVSS: Robust Audio-Visual Speech Separation in Multi-Speaker Scenarios with Missing Visual Cues](https://arxiv.org/abs/2407.19224) Tianrui Pan, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Bohan Wang, Jie Tang, and Gangshan Wu. **ACM MM**, 2024. <a class="publication-code" href="https://github.com/pantianrui/RAVSS" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

* <span class="pub-rank rank-b">CCF-B</span> [GTPT: Group-based Token Pruning Transformer for Efficient Human Pose Estimation](https://arxiv.org/abs/2407.10756) Haonan Wang, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, Gangshan Wu, Bo Xu, Yanbing Chou, and Yong Wang. **ECCV**, 2024. <a class="publication-code" href="https://github.com/haonanwang0522/GTPT?tab=readme-ov-file" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

* <span class="pub-rank rank-a">CCF-A</span> [Sketch and Refine: Towards Fast and Accurate Lane Detection](https://ojs.aaai.org/index.php/AAAI/article/view/27860) Chao Chen, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Chang Zhou, Jie Tang, and Gangshan Wu. **AAAI**, 2024. <a class="publication-code" href="https://github.com/passerer/SRLane" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

### 2023
* <span class="pub-rank rank-a">CCF-A</span> [Robust Object Modeling for Visual Tracking](https://arxiv.org/abs/2308.05140) Yidong Cai, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu. **ICCV**, 2023. <a class="publication-code" href="https://github.com/dawnyc/ROMTrack" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

* <span class="pub-rank rank-a">CCF-A</span> [Lightweight Super-Resolution Head for Human Pose Estimation](https://arxiv.org/abs/2307.16765) Haonan Wang, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu. **ACM MM**, 2023. <a class="publication-code" href="https://github.com/haonanwang0522/SRPose" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

* <span class="pub-rank rank-a">CCF-A</span> [Video Frame Interpolation with Densely Queried Bilateral Correlation](https://arxiv.org/abs/2304.13596) Chang Zhou, **Jie Liu**<span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu. **IJCAI**, 2023. <a class="publication-code" href="https://github.com/kinoud/DQBC" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

* <span class="pub-rank rank-a">CCF-A</span> [From Coarse to Fine: Hierarchical Pixel Integration for Lightweight Image Super-Resolution](https://arxiv.org/abs/2211.16776) **Jie Liu**, Chao Chen, Jie Tang, and Gangshan Wu. **AAAI**, 2023. <a class="publication-code" href="https://github.com/passerer/HPINet" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

### 2022
* <span class="pub-rank rank-b">CCF-B</span> [Two Strategies Toward Lightweight Image Super-Resolution](https://ieeexplore.ieee.org/abstract/document/9746192/) Zongcai Du, **Jie Liu**, Jie Tang, Gangshan Wu. **ICASSP**, 2022.
* [IAA-VSR: An iterative alignment algorithm for video super-resolution](https://link.springer.com/article/10.1007/s10489-022-03364-z)  **Jie Liu**, Jie Tang, and Gangshan Wu. **Applied Intelligence**, 2022.
* [Fast and Memory-Efficient Network Towards Efficient Image Super-Resolution](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Du_Fast_and_Memory-Efficient_Network_Towards_Efficient_Image_Super-Resolution_CVPRW_2022_paper.html) Zongcai Du, Ding Liu, **Jie Liu**, Jie Tang, Gangshan Wu, Lean Fu. **CVPRW**, 2022. <a class="publication-code" href="https://github.com/NJU-Jet/FMEN" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

### 2021
* [Anchor-based Plain Net for Mobile Image Super-Resolution](https://openaccess.thecvf.com/content/CVPR2021W/MAI/html/Du_Anchor-Based_Plain_Net_for_Mobile_Image_Super-Resolution_CVPRW_2021_paper.html) Zongcai Du, **Jie Liu**, Jie Tang, Gangshan Wu. **CVPRW**, 2021. <a class="publication-code" href="https://github.com/NJU-Jet/SR_Mobile_Quantization" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>

### 2020
* <span class="pub-rank rank-a">CCF-A</span> [Memory Recursive Network for Single Image Super-Resolution](https://dl.acm.org/doi/abs/10.1145/3394171.3413696) **Jie Liu**, Minqiang Zou, Jie Tang, Gangshan Wu. **ACM MM**, 2020.
* <span class="pub-rank rank-a">CCF-A</span> [Residual Feature Aggregation Network for Image Super-Resolution](https://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Residual_Feature_Aggregation_Network_for_Image_Super-Resolution_CVPR_2020_paper.html) **Jie Liu**, Wenjie Zhang, Yuting Tang, Jie Tang, Gangshan Wu. **CVPR**, 2020. <a class="publication-code" href="https://github.com/njulj/RFANet" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>
* <span class="pub-rank rank-b">CCF-B</span> [Belief Map Enhancement Network for Accurate Human Pose Estimation](https://ebooks.iospress.nl/volumearticle/55208) **Jie Liu**, Yishun Dou, Wenjie Zhang, Jie Tang, Gangshan Wu. **ECAI**, 2020.
* [Residual feature distillation network for lightweight image super-resolution](https://link.springer.com/chapter/10.1007/978-3-030-67070-2_2) **Jie Liu**, Jie Tang, Gangshan Wu. **ECCVW**, 2020. <a class="publication-code" href="https://github.com/njulj/RFDN" target="_blank" rel="external nofollow noopener"><i class="fa-brands fa-github" aria-hidden="true"></i>Code</a>
