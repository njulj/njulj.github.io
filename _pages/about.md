---
layout: about
permalink: /
title: about
nav: false
subtitle: <a href="https://is.nju.edu.cn/">School of Intelligence Science and Technology</a><br>Nanjing University, Suzhou · Jiangsu, China
profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
selected_papers: false
social: true
announcements:
  enabled: false
latest_posts:
  enabled: false
redirect_from:
  - /about/
  - /about.html
---

<style>
  /* Keep the homepage navigation aligned even when GitHub Pages serves a
     cached copy of the theme stylesheet. */
  #navbar {
    top: 0 !important;
    right: 0 !important;
    left: 0 !important;
    width: 100% !important;
    min-height: 57px;
    padding-top: 0 !important;
    padding-bottom: 0 !important;
  }

  #navbar > .container {
    min-height: 57px;
  }

  @media (min-width: 576px) {
    #navbar > .container {
      display: flex !important;
      flex-wrap: nowrap;
      align-items: center;
      justify-content: flex-end;
      width: 100% !important;
      max-width: 930px;
      margin-right: auto !important;
      margin-left: auto !important;
    }

    #navbar .navbar-collapse-main {
      display: flex !important;
      visibility: visible !important;
      flex: 1 1 auto;
      width: auto;
      justify-content: flex-end;
      margin-left: auto;
    }

    #navbar .navbar-menu-list {
      margin-right: 0;
      margin-left: auto;
    }
  }

  .post {
    --about-accent: #3f7185;
    --about-accent-hover: #2c596a;
    --about-news-text: #4d5c63;
  }

  .post article .clearfix a {
    color: var(--about-accent);
  }

  .post article .clearfix a:hover {
    color: var(--about-accent-hover);
  }

  .post-header .desc a {
    color: var(--about-accent);
  }

  .post-header .desc a:hover {
    color: var(--about-accent-hover);
  }

  .post-header {
    padding-right: 30%;
  }

  .news-scroll {
    max-height: 28rem;
    overflow-y: auto;
    overscroll-behavior: contain;
    margin-bottom: 1.25rem;
    padding: 0.15rem 1rem 0.15rem 0;
    scrollbar-width: thin;
  }

  .news-scroll > ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .news-scroll > ul > li {
    position: relative;
    margin: 0 0 0.5rem;
    padding-left: 4.8rem;
    color: var(--about-news-text);
    line-height: 1.5;
  }

  .news-date {
    position: absolute;
    top: 0.06em;
    left: 0;
    width: 4.2rem;
    padding: 0.08em 0.35em;
    border: 1px solid rgb(63 113 133 / 24%);
    border-radius: 999px;
    background: rgb(63 113 133 / 10%);
    color: var(--about-accent);
    font-size: 0.82em;
    font-variant-numeric: tabular-nums;
    font-weight: 550;
    letter-spacing: 0.01em;
    line-height: 1.35;
    text-align: center;
    white-space: nowrap;
  }

  .news-scroll > ul > li > span:not(.news-date) {
    color: inherit !important;
  }

  .news-scroll > ul > li > ul,
  .news-scroll > ul > li > p {
    text-indent: 0;
  }

  .news-scroll:focus-visible {
    outline: 2px solid var(--global-theme-color);
    outline-offset: 4px;
  }

  .profile img {
    aspect-ratio: 1 / 1;
    object-fit: cover;
    object-position: center 5%;
  }

  .profile {
    position: relative;
    z-index: 1;
    margin-top: -5.1rem;
    width: 27%;
  }

  .profile .profile-social {
    margin-top: 0.7rem;
    text-align: center;
  }

  .profile .profile-social .contact-icons {
    font-size: 1.45rem;
    line-height: 1;
  }

  .profile .profile-social .contact-icons a {
    margin: 0 0.28rem;
  }

  .featured-publications {
    margin-top: 0.75rem;
  }

  .featured-publication {
    display: grid;
    grid-template-columns: minmax(150px, 24%) 1fr;
    gap: 1.1rem;
    align-items: center;
    margin-bottom: 1.5rem;
  }

  .featured-publication .preview {
    overflow: hidden;
    border-radius: 0.3rem;
    box-shadow: 0 2px 6px rgb(0 0 0 / 18%);
    background: #fff;
  }

  .featured-publication .preview img {
    display: block;
    width: 100%;
    height: auto;
    background: #fff;
  }

  .featured-publication .paper-title {
    margin-bottom: 0.2rem;
    font-weight: 600;
    line-height: 1.3;
  }

  .featured-publication .paper-authors,
  .featured-publication .paper-venue {
    margin-bottom: 0.2rem;
    line-height: 1.4;
  }

  .corresponding-mark {
    display: inline-block;
    margin-left: 0.16em;
    color: var(--global-theme-color);
    font-family: Arial, sans-serif;
    font-size: 0.72em;
    font-style: normal;
    font-weight: 400;
    line-height: 1;
    vertical-align: 0.38em;
  }

  .featured-publication .paper-links a {
    display: inline-block;
    margin: 0.25rem 0.25rem 0 0;
    padding: 0.15rem 0.65rem;
    border: 1px solid var(--global-text-color);
    border-radius: 0.2rem;
    color: var(--global-text-color);
    font-size: 0.78rem;
    text-decoration: none;
  }

  .featured-publication .paper-links a:hover {
    border-color: var(--global-theme-color);
    color: var(--global-theme-color);
  }

  .featured-publication .citation-count {
    border-color: rgb(66 133 244 / 38%);
    background: transparent;
    color: #1967d2;
  }

  .featured-publication .citation-count:hover {
    border-color: #4285f4;
    background: transparent;
    color: #1558b0;
  }

  .featured-publication .citation-count i {
    margin-right: 0.22em;
    color: #1967d2 !important;
  }

  .featured-publication .citation-count .ai-google-scholar::before {
    color: #1967d2 !important;
  }

  .featured-publication .github-stars i {
    margin-right: 0.22em;
    color: #c58a24;
  }

  @media (max-width: 576px) {
    .post-header {
      padding-right: 0;
    }

    .news-scroll {
      max-height: 22rem;
    }

    .profile {
      margin-top: 0;
      width: 100%;
    }

    .featured-publication {
      grid-template-columns: 1fr;
      gap: 0.75rem;
    }

    .featured-publication .preview {
      max-width: 18rem;
    }
  }
</style>

> 🐳 I am recruiting **1–2 Ph.D. students and 1–2 master's students for 2027**. Interested students are welcome to contact me at [liujie@nju.edu.cn](mailto:liujie@nju.edu.cn).

## Biography
I am working as an Assistant Professor at the School of Intelligence Science and Technology, Nanjing University. I am also a member of the [Multimedia Computing Group (MCG)](http://mcg.nju.edu.cn/), working with [Prof.Jie Tang](http://mcg.nju.edu.cn/) and [Prof.Limin Wang](https://wanglimin.github.io/). Previously, I obtained my Ph.D. at the Department of Computer Science and Technology, Nanjing University, China, in Sep. 2022. Before that, I received my master's degree in the Department of Computer Science and Technology at Nanjing University, China, in Jue. 2018 and B.E degree from the Department of Computer Science and Technology, Nanjing University, China, in Jue. 2015.

My research interest broadly includes deep learning, computer vision and speech processing. Specifically, I focus on image/video restoration and generation, multimodal perception and understanding, efficient MLLM/LLM, agentic system, etc.

## News

<div class="news-scroll" markdown="1" role="region" aria-label="Recent news" tabindex="0">

* <span class="news-date">2026.07</span> <span style="color:purple">Our paper "Enabling Proactive Spoken Turns via a Generalized Style-Aware Full-Duplex Framework" was accepted by MM 2026 (CCF-A). Congratulations Tianrui Pan!</span>
* <span class="news-date">2026.06</span> <span style="color:purple">We secured third place in the REAL-I 2026 — The 1st Real-World Embodied AI Learning Challenge, held at ICRA 2026. 恭喜陈宇宁、孙飞宇和张明轩同学！</span>
* <span class="news-date">2026.03</span> <span style="color:purple">We secured third place in the NTIRE Efficient Super-Resolution Challenge, held at CVPR 2026. 恭喜雷业成（大二）和闵文楷（大二）！</span>
* <span class="news-date">2026.02</span> <span style="color:purple">Our paper [Disentangled Textual Priors for Diffusion-based Image Super-Resolution](https://arxiv.org/abs/2603.07430) was accepted by CVPR 2026 (CCF-A). Congratulations Lei Jiang!</span>
* <span class="news-date">2026.01</span> <span style="color:purple">Our paper [GLAD: Generative Language-Assisted Visual Tracking for Low-Semantic Templates](https://link.springer.com/article/10.1007/s11263-026-02774-7) was accepted by IJCV (CCF-A). Congratulations Xingyu Luo!</span>
* <span class="news-date">2025.12</span> <span style="color:orange">“挑战杯”获奖作品被《扬子晚报》追踪报导！</span>[链接](https://wap.yzwb.net/wap/news/4891087.html)
* <span class="news-date">2025.11</span> <span style="color:gray">恭喜研一的张明轩、陈宇宁、张朱昊、孙飞宇、李嘉伟同学获得第十九届“挑战杯”全国大学生课外学术科技作品竞赛 “人工智能+”挑战赛 全国特等奖！</span>[链接](https://mp.weixin.qq.com/s/Rzbuh9of7G2_tolubgal-Q)
* <span class="news-date">2025.11</span> <span style="color:gray">恭喜大三的周擎、黄伟轩、程启航、陈巧、刘鑫鑫同学获得第十九届“挑战杯”全国大学生课外学术科技作品竞赛 2025年度“揭榜挂帅”专项赛 全国三等奖！</span>[链接](https://mp.weixin.qq.com/s/si2J3FAXIx3eScu7UDhzHg)
* <span class="news-date">2025.10</span> <span style="color:gray">Win the 2nd place in the MAC 2025: the 2nd Micro-Action Analysis Grand Challenge @ MM2025! 恭喜罗星宇同学（研一）！</span>
   * 🥈🥈🥈
   <p align="left">
   <img src="MAC25.png" width="400">
	</p>
* <span class="news-date">2025.09</span> <span style="color:gray">恭喜许煜恒同学《面向LUT超分辨率模型的纹理增强与存储压缩技术研究 》获批国家自然科学基金青年学生基础研究项目（本科生）!</span>
* <span class="news-date">2025.06</span> <span style="color:gray">Our ACL paper was selected as Oral Presentation!</span>
* <span class="news-date">2025.05</span> <span style="color:gray">One paper was accepted by ACL 2025 Main (CCF-A). Congratulations Tianrui Pan!</span>
* <span class="news-date">2025.03</span> <span style="color:gray">One paper was accepted by Neural Networks (CCF-B). Congratulations Shijie Yang!（研二）</span>
* <span class="news-date">2025.03</span> <span style="color:gray">One paper was accepted by ICME 2025 (CCF-B). 恭喜吴隽雨（大三）同学!</span>:
* <span class="news-date">2025.02</span> <span style="color:gray">Two papers were accepted to CVPR 2025 (CCF-A). 恭喜刘鑫（研二）和许煜恒（大三）同学!</span>:
* <span class="news-date">2024.11</span> <span style="color:gray">恭喜梁锦文（大四）、罗星宇（大四）、陈依言（大三）获得第十九届“挑战杯”全国大学生课外学术科技作品竞赛 2024年度“揭榜挂帅”专项赛 全国三等奖！</span>
* <span class="news-date">2024.10</span> <span style="color:gray">Win the 1st place in the Multi-Modal Visual Pattern Recognition Challenge # Track 2 @ ICPR2024! 恭喜吴隽雨（大三）& 晁宇豪（大三）！</span>
   * 🥇🥇🥇
   <p align="left">
	<img src="ICPR24.jpg" width="400">
	</p>
* <span class="news-date">2024.10</span> <span style="color:gray">恭喜林彦铠同学（大三）获得昇腾AI原生创新算子挑战赛（S2赛季）优秀奖！</span>
* <span class="news-date">2024.08</span> <span style="color:gray">Invited to serve as a reviewer for AAAI & ICLR 2025.</span>
* <span class="news-date">2024.07</span> <span style="color:gray">One paper was accepted to ACM MM 2024. Congratulations Tianrui Pan!</span>
* <span class="news-date">2024.07</span> <span style="color:gray">One paper was accepted to ECCV 2024. Congratulations Haonan Wang!</span>
* <span class="news-date">2024.05</span> <span style="color:gray">Invited to serve as a reviewer for NeurIPS 2024.</span>
* <span class="news-date">2024.04</span> <span style="color:gray">梁锦文、罗星宇、石璐、孙源泽同学赴阿联酋·阿布扎比参加AICAS Grand Challenge 2024</span>
* <span class="news-date">2024.04</span> <span style="color:gray">🎊 指导的21级本科生获得天池[“AICAS 2024：通用算力大模型推理性能软硬协同优化挑战赛”](https://tianchi.aliyun.com/competition/entrance/532170?spm=a2c22.12281957.0.0.4c886d94Fr3gDe&lang=zh-cn)第二名的优异成绩（USD 3000）。恭喜梁锦文、罗星宇、石璐、孙源泽同学！</span>
   * 🥈🥈🥈
	<p align="left">
	<img src="AICAS.png" width="400">
	</p>
* <span class="news-date">2023.12</span> <span style="color:gray">One paper was accepted to AAAI 2024 (CCF-A). Congratulations Chao Chen!</span>:
* <span class="news-date">2023.11</span> <span style="color:gray">Invited to serve as a reviewer for CVPR 2024.</span>
* <span class="news-date">2023.08</span> <span style="color:gray">🎊 恭喜指导的21级本科生石璐和梁锦文同学在天池算法竞赛平台上举办的[“AFAC2023-金融数据验真-金融文档防篡改挑战赛”](https://tianchi.aliyun.com/competition/entrance/532096/introduction)中获得季军的优异成绩（¥10000）</span>
   * 🥉🥉🥉
	<p align="left">
	<img src="AFAC.png" width="400">
	</p>
* <span class="news-date">2023.08</span> <span style="color:gray">荣获AFAC2023金融智能挑战赛“优秀指导教师”!</span>
* <span class="news-date">2023.07</span> <span style="color:gray">One paper was accepted to ACM MM 2023 (CCF-A). Congratulations Haonan Wang!</span>:
  * ["Lightweight Super-Resolution Head for Human Pose Estimation"](https://arxiv.org/abs/2307.16765). Haonan Wang, Jie Liu\*, Jie Tang, and Gangshan Wu. (\* indicates corresponding author)
* <span class="news-date">2023.07</span> <span style="color:gray">One paper was accepted to ICCV 2023 (CCF-A). Congratulations Yidong Cai!</span>:
  * ["Robust Object Modeling for Visual Tracking"](https://arxiv.org/abs/2308.05140). Yidong Cai, Jie Liu\*, Jie Tang, and Gangshan Wu. (\* indicates corresponding author)
* <span class="news-date">2023.04</span> <span style="color:gray">One paper was accepted to IJCAI 2023 (CCF-A). Congratulations Chang Zhou!</span>:
  * [Video Frame Interpolation with Densely Queried Bilateral Correlation](https://arxiv.org/abs/2304.13596). Chang Zhou, Jie Liu\*, Jie Tang, and Gangshan Wu. (\* indicates corresponding author)
* <span class="news-date">2022.11</span> One paper was accepted to AAAI 2023 (CCF-A):
  * [From Coarse to Fine: Hierarchical Pixel Integration for Lightweight Image Super-Resolution](https://arxiv.org/abs/2211.16776). Jie Liu, Chao Chen, Jie Tang, and Gangshan Wu.
* <span class="news-date">2021.07</span> 🎊 Honorable Mention Award
	* We won the Honorable Mention Award of the [CVPR MAI 2021 Quantized Image Super-Resolution Challenge](https://ai-benchmark.com/workshops/mai/2021/).
* <span class="news-date">2020.07</span> 🎊 Winner Award 🏆
   * We won the first prize of the [ECCV AIM 2020 Efficient Super-Resolution Challenge](https://data.vision.ee.ethz.ch/cvl/aim20/).
   <p align="left">
	<img src="AIM.png" width="400">
	</p>
* <span class="news-date">2020.07</span> One paper was accepted to ACM MM 2020 (CCF-A).
  * [Memory Recursive Network for Single Image Super-Resolution](https://dl.acm.org/doi/abs/10.1145/3394171.3413696). Jie Liu, Minqiang Zou, Jie Tang, Gangshan Wu.
* <span class="news-date">2020.02</span> One paper was accepted to CVPR 2020 (CCF-A).
  * [Residual Feature Aggregation Network for Image Super-Resolution](https://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Residual_Feature_Aggregation_Network_for_Image_Super-Resolution_CVPR_2020_paper.html). Jie Liu, Wenjie Zhang, Yuting Tang, Jie Tang, Gangshan Wu.

</div>

## Selected Publications [[Full List](/publications/)]

<div class="featured-publications">
  <div class="featured-publication">
    <div class="preview"><img src="/assets/img/publication_preview/dtpsr.png" alt="DTPSR paper PDF preview"></div>
    <div>
      <div class="paper-title">Disentangled Textual Priors for Diffusion-based Image Super-Resolution</div>
      <div class="paper-authors">Lei Jiang, Xin Liu, Xinze Tong, Zhiliang Li, <strong>Jie Liu</strong><span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu</div>
      <div class="paper-venue"><em>CVPR 2026</em></div>
      <div class="paper-links"><a href="https://arxiv.org/abs/2603.07430">PDF</a><a href="https://github.com/JL6666JL/DTPSR">Code</a><a class="github-stars" href="https://github.com/JL6666JL/DTPSR/stargazers" title="GitHub stars"><i class="fa-solid fa-star" aria-hidden="true"></i>15</a><a class="citation-count" href="https://scholar.google.com/scholar?oi=bibs&amp;hl=en&amp;cites=1602891317005625924" title="Google Scholar citations"><i class="ai ai-google-scholar" aria-hidden="true"></i>1</a></div>
    </div>
  </div>
  <div class="featured-publication">
    <div class="preview"><img src="/assets/img/publication_preview/glad.png" alt="GLAD paper PDF preview"></div>
    <div>
      <div class="paper-title">GLAD: Generative Language-Assisted Visual Tracking for Low-Semantic Templates</div>
      <div class="paper-authors">Xingyu Luo, Yidong Cai, <strong>Jie Liu</strong><span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, Gangshan Wu, and Limin Wang</div>
      <div class="paper-venue"><em>IJCV 2026</em></div>
      <div class="paper-links"><a href="https://link.springer.com/article/10.1007/s11263-026-02774-7">Paper</a><a href="https://github.com/Confetti-lxy/GLAD">Code</a><a class="github-stars" href="https://github.com/Confetti-lxy/GLAD/stargazers" title="GitHub stars"><i class="fa-solid fa-star" aria-hidden="true"></i>6</a><a class="citation-count" href="https://scholar.google.com/scholar?oi=bibs&amp;hl=en&amp;cites=8484577720452671235" title="Google Scholar citations"><i class="ai ai-google-scholar" aria-hidden="true"></i>1</a></div>
    </div>
  </div>
  <div class="featured-publication">
    <div class="preview"><img src="/assets/img/publication_preview/tasu.png" alt="TASU paper PDF preview"></div>
    <div>
      <div class="paper-title">In-the-wild Audio Spatialization with Flexible Text-guided Localization</div>
      <div class="paper-authors">Tianrui Pan, <strong>Jie Liu</strong><span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Zewen Huang, Jie Tang, and Gangshan Wu</div>
      <div class="paper-venue"><em>ACL 2025 Main (Oral)</em></div>
      <div class="paper-links"><a href="https://arxiv.org/pdf/2506.00927">PDF</a><a href="https://github.com/Alice01010101/TASU">Code</a><a class="github-stars" href="https://github.com/Alice01010101/TASU/stargazers" title="GitHub stars"><i class="fa-solid fa-star" aria-hidden="true"></i>10</a><a class="citation-count" href="https://scholar.google.com/scholar?oi=bibs&amp;hl=en&amp;cites=13634392053545912425" title="Google Scholar citations"><i class="ai ai-google-scholar" aria-hidden="true"></i>3</a></div>
    </div>
  </div>
  <div class="featured-publication">
    <div class="preview"><img src="/assets/img/publication_preview/catanet.png" alt="CATANet visual comparison"></div>
    <div>
      <div class="paper-title">CATANet: Efficient Content-Aware Token Aggregation for Lightweight Image Super-Resolution</div>
      <div class="paper-authors">Xin Liu, <strong>Jie Liu</strong><span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu</div>
      <div class="paper-venue"><em>CVPR 2025</em></div>
      <div class="paper-links"><a href="https://arxiv.org/abs/2503.06896">PDF</a><a href="https://github.com/EquationWalker/CATANet">Code</a><a class="github-stars" href="https://github.com/EquationWalker/CATANet/stargazers" title="GitHub stars"><i class="fa-solid fa-star" aria-hidden="true"></i>235</a><a class="citation-count" href="https://scholar.google.com/scholar?oi=bibs&amp;hl=en&amp;cites=6564347727405235652" title="Google Scholar citations"><i class="ai ai-google-scholar" aria-hidden="true"></i>96</a></div>
    </div>
  </div>
  <div class="featured-publication">
    <div class="preview"><img src="/assets/img/publication_preview/romtrack.png" alt="ROMTrack architecture"></div>
    <div>
      <div class="paper-title">Robust Object Modeling for Visual Tracking</div>
      <div class="paper-authors">Yidong Cai, <strong>Jie Liu</strong><span class="corresponding-mark" title="Corresponding author" aria-label="Corresponding author">&#9993;&#65038;</span>, Jie Tang, and Gangshan Wu</div>
      <div class="paper-venue"><em>ICCV 2023</em></div>
      <div class="paper-links"><a href="https://arxiv.org/abs/2308.05140">PDF</a><a href="https://github.com/dawnyc/ROMTrack">Code</a><a class="github-stars" href="https://github.com/dawnyc/ROMTrack/stargazers" title="GitHub stars"><i class="fa-solid fa-star" aria-hidden="true"></i>48</a><a class="citation-count" href="https://scholar.google.com/scholar?oi=bibs&amp;hl=en&amp;cites=16959695817106881254" title="Google Scholar citations"><i class="ai ai-google-scholar" aria-hidden="true"></i>260</a></div>
    </div>
  </div>
  <div class="featured-publication">
    <div class="preview"><img src="/assets/img/publication_preview/rfanet.png" alt="RFANet paper PDF preview"></div>
    <div>
      <div class="paper-title">Residual Feature Aggregation Network for Image Super-Resolution</div>
      <div class="paper-authors"><strong>Jie Liu</strong>, Wenjie Zhang, Yuting Tang, Jie Tang, and Gangshan Wu</div>
      <div class="paper-venue"><em>CVPR 2020</em></div>
      <div class="paper-links"><a href="https://openaccess.thecvf.com/content_CVPR_2020/html/Liu_Residual_Feature_Aggregation_Network_for_Image_Super-Resolution_CVPR_2020_paper.html">Paper</a><a href="https://github.com/njulj/RFANet">Code</a><a class="github-stars" href="https://github.com/njulj/RFANet/stargazers" title="GitHub stars"><i class="fa-solid fa-star" aria-hidden="true"></i>106</a><a class="citation-count" href="https://scholar.google.com/scholar?oi=bibs&amp;hl=en&amp;cites=17474753560595458218" title="Google Scholar citations"><i class="ai ai-google-scholar" aria-hidden="true"></i>783</a></div>
    </div>
  </div>
  <div class="featured-publication">
    <div class="preview"><img src="/assets/img/publication_preview/rfdn.png" alt="RFDN architecture"></div>
    <div>
      <div class="paper-title">Residual Feature Distillation Network for Lightweight Image Super-Resolution</div>
      <div class="paper-authors"><strong>Jie Liu</strong>, Jie Tang, and Gangshan Wu</div>
      <div class="paper-venue"><em>ECCVW 2020</em></div>
      <div class="paper-links"><a href="https://link.springer.com/chapter/10.1007/978-3-030-67070-2_2">Paper</a><a href="https://github.com/njulj/RFDN">Code</a><a class="github-stars" href="https://github.com/njulj/RFDN/stargazers" title="GitHub stars"><i class="fa-solid fa-star" aria-hidden="true"></i>400</a><a class="citation-count" href="https://scholar.google.com/scholar?oi=bibs&amp;hl=en&amp;cites=5480173376995974751" title="Google Scholar citations"><i class="ai ai-google-scholar" aria-hidden="true"></i>806</a></div>
    </div>
  </div>
</div>

## Research Topics (Series A)
* Image/video restoration and generation
	* Real-world super-resolution
	* Efficient image/video generation
	* Scientific image enhancement
* Multimodal perception and understanding
	* Multimodal tracking
	* Audio-visual tasks
* MLLM & LLM
	* MLLM/LLM for mobile devices
	* MLLM for image quality assessment

## Research Topics (Series B)
* Low-level foundation model
	* Foundation model for image restoration
* World model
	* World model in embodied ai
	* World model in video generation
* AI agents
	* Image restoration agent
	* GUI agent

## Funds and Projects
* 国家青年科学基金项目(C类)，2025-01-01 至 2027-12-31，主持
*  江苏省青年基金项目，2024-09 至 2027-08，主持
*  科技创新2030-“新一代人工智能”重大项目，通用视频理解的基础模型与方法体系，2023-01 至 2025-12，参与
*  国家重点研发计划-课题，参与

## Honors and Awards
* National Scholarships for Doctoral Students （博士研究生国家奖学金）
* Supported by the program B for
Outstanding PhD candidate of Nanjing University （南京大学提升B计划）
* AFAC2023金融智能挑战赛“优秀指导教师”

## Teaching
* 计算机系统基础（ICS）
	* 2025年秋季学期（计算机+AI+匡院 PA实验）
	* 2024年秋季学期（计算机+AI+匡院 PA实验）
	*  2023年秋季学期（PA实验）
	*  2023年春季学期（理论部分）
* 教学论文
	* 袁春风，苏 丰，吴海军，余子濠，汪 亮，刘 杰，朱光辉，"计算机系统导论课程实践项目及实践体系建设"，《计算机教育》
* 教材出版
	* 《计算机系统实践教程：基于x86+Linux平台》，苏 丰，汪 亮，刘 杰，王慧妍，朱光辉，余子濠，鲍培明，袁春风

## Academic Services
* Reviewer
  * ICLR 2025, CVPR 2025, ICML 2025, ICCV 2025, MM 2025, NeurIPS 2025
  * CVPR 2024, ECCV 2024, MM 2024, ACCV 2024, NeurIPS 2024
  * CVPR 2023, ICCV 2023
  * ECCV 2022, CVPR 2022
  * ICCV 2021, CVPR 2021, AAAI 2021
  * IEEE TMM, IEEE TCSVT, IJCV, TIP
  * ...

## Alumni
* 2024
	* 陈超（百度），蔡益东（字节），王浩男（腾讯），周畅（无锡天一中学）
