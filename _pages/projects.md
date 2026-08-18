---
layout: page
title: Projects
permalink: /projects/
description: Open-source research projects and community resources.
nav: true
nav_order: 3
---

<style>
  .projects-page {
    --project-accent: #4f7183;
    --project-accent-strong: #2f6177;
    --project-surface: rgb(79 113 131 / 7%);
    --project-border: rgb(79 113 131 / 22%);
  }

  .project-card {
    overflow: hidden;
    margin: 1.25rem 0 2rem;
    border: 1px solid var(--project-border);
    border-radius: 0.8rem;
    background: var(--global-bg-color);
    box-shadow: 0 0.45rem 1.4rem rgb(30 55 68 / 8%);
  }

  .project-card__main {
    padding: 1.5rem 1.6rem 1.35rem;
  }

  .project-card__eyebrow {
    margin-bottom: 0.5rem;
    color: var(--project-accent);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .project-card h2 {
    margin: 0 0 0.75rem;
    font-size: 1.35rem;
    line-height: 1.3;
  }

  .project-card h2 a {
    color: var(--global-text-color);
  }

  .project-card h2 a:hover {
    color: var(--project-accent-strong);
  }

  .project-card__description {
    margin-bottom: 1.1rem;
    color: var(--global-text-color-light);
    line-height: 1.7;
  }

  .project-card__tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    margin-bottom: 1.2rem;
  }

  .project-card__tag {
    padding: 0.18rem 0.6rem;
    border: 1px solid var(--project-border);
    border-radius: 999px;
    background: var(--project-surface);
    color: var(--project-accent-strong);
    font-size: 0.78rem;
  }

  .project-card__link {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.5rem 0.85rem;
    border-radius: 0.35rem;
    background: var(--project-accent);
    color: #fff !important;
    font-size: 0.9rem;
    font-weight: 600;
    text-decoration: none !important;
  }

  .project-card__link:hover {
    background: var(--project-accent-strong);
  }

  .community-panel {
    padding: 1.35rem 1.6rem 1.45rem;
    border-top: 1px solid var(--project-border);
    background: var(--project-surface);
  }

  .community-panel h3 {
    margin: 0 0 0.6rem;
    color: var(--project-accent-strong);
    font-size: 1.08rem;
  }

  .community-panel p {
    margin-bottom: 0.75rem;
    line-height: 1.65;
  }

  .community-panel__content {
    display: grid;
    grid-template-columns: minmax(0, 1fr) 180px;
    gap: 1.4rem;
    align-items: center;
  }

  .community-panel ul {
    margin: 0.4rem 0 1rem;
    padding-left: 1.25rem;
  }

  .community-panel li {
    margin-bottom: 0.3rem;
  }

  .qq-group {
    display: inline-flex;
    align-items: center;
    gap: 0.55rem;
    padding: 0.45rem 0.75rem;
    border: 1px solid var(--project-border);
    border-radius: 0.4rem;
    background: var(--global-bg-color);
  }

  .qq-group strong {
    color: var(--project-accent-strong);
    font-size: 1.02rem;
    letter-spacing: 0.04em;
  }

  .community-qr {
    margin: 0;
    text-align: center;
  }

  .community-qr img {
    display: block;
    width: 100%;
    max-width: 180px;
    margin: 0 auto;
    border: 1px solid var(--project-border);
    border-radius: 0.55rem;
    background: #fff;
  }

  .community-qr figcaption {
    margin-top: 0.4rem;
    color: var(--global-text-color-light);
    font-size: 0.76rem;
  }

  @media (max-width: 600px) {
    .project-card__main,
    .community-panel {
      padding-right: 1.1rem;
      padding-left: 1.1rem;
    }

    .community-panel__content {
      grid-template-columns: 1fr;
    }

    .community-qr {
      order: -1;
    }
  }
</style>

<div class="projects-page">
  <article class="project-card">
    <div class="project-card__main">
      <div class="project-card__eyebrow">Interactive Research Tool</div>
      <h2><a href="https://github.com/njulj/Understand-Anypaper">Understand Anypaper</a></h2>
      <p class="project-card__description">
        An open-source tool that turns research papers into interactive Paper Argument Graphs. It reorganizes a paper around its core contributions, connecting each claim to its motivation, methodology, formulas, figures, experiments, and supporting evidence so readers can understand the paper's logic and trace every insight back to the original source.
      </p>
      <div class="project-card__tags" aria-label="Project topics">
        <span class="project-card__tag">Research Assistant</span>
        <span class="project-card__tag">Argument Graph</span>
        <span class="project-card__tag">Paper Reading</span>
        <span class="project-card__tag">LLM</span>
        <span class="project-card__tag">Open Source</span>
      </div>
      <a class="project-card__link" href="https://github.com/njulj/Understand-Anypaper">
        <i class="fa-brands fa-github" aria-hidden="true"></i>
        View on GitHub
      </a>
    </div>
  </article>

  <article class="project-card">
    <div class="project-card__main">
      <div class="project-card__eyebrow">Curated Research Resource</div>
      <h2><a href="https://github.com/njulj/Awesome-Agent-Based-Low-Level-Vision">Awesome Agent for Low-level Vision</a></h2>
      <p class="project-card__description">
        A curated and continuously updated collection of papers, code, and resources at the intersection of autonomous agents, multimodal large language model agents, and low-level vision. The project tracks research across image restoration, editing, super-resolution, video restoration, computational photography, retouching, and image quality assessment.
      </p>
      <div class="project-card__tags" aria-label="Project topics">
        <span class="project-card__tag">AI Agents</span>
        <span class="project-card__tag">Low-level Vision</span>
        <span class="project-card__tag">Image Restoration</span>
        <span class="project-card__tag">Open Source</span>
      </div>
      <a class="project-card__link" href="https://github.com/njulj/Awesome-Agent-Based-Low-Level-Vision">
        <i class="fa-brands fa-github" aria-hidden="true"></i>
        View on GitHub
      </a>
    </div>

    <section class="community-panel" aria-labelledby="community-title">
      <h3 id="community-title">💬 Community &amp; Discussion</h3>
      <div class="community-panel__content">
        <div>
          <p>欢迎对图像恢复 Agent、低层视觉与多模态智能感兴趣的研究者、开发者和同学加入社区，一起交流讨论！</p>
          <ul>
            <li>讨论最新论文与研究想法</li>
            <li>分享开源项目和实用资源</li>
            <li>交流技术问题与实现经验</li>
            <li>寻找潜在的科研合作伙伴</li>
          </ul>
          <div class="qq-group">
            <span>QQ群</span>
            <strong>1056914561</strong>
          </div>
          <p><small>可在 QQ 中搜索群号申请加入，或扫描右侧二维码，欢迎大家进群交流。</small></p>
        </div>
        <figure class="community-qr">
          <img src="{{ '/images/awesome-agent-qq-group.png' | relative_url }}" alt="Awesome Agent for Low-level Vision QQ group QR code, group number 1056914561">
          <figcaption>扫码加入 QQ 群</figcaption>
        </figure>
      </div>
    </section>
  </article>
</div>
