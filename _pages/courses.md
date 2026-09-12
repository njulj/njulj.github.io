---
layout: page
title: Courses
permalink: /courses/
description: Course information, competitions, and practical assignments.
nav: true
nav_order: 4
---

<style>
  .courses-page {
    --course-accent: #3f7185;
    --course-accent-strong: #28586c;
    --course-surface: rgb(63 113 133 / 7%);
    --course-border: rgb(63 113 133 / 22%);
  }

  .course-intro {
    margin: 0.75rem 0 0;
    color: var(--global-text-color-light);
    line-height: 1.75;
  }

  .course-card {
    overflow: hidden;
    border: 1px solid var(--course-border);
    border-radius: 0.8rem;
    background: var(--global-bg-color);
    box-shadow: 0 0.45rem 1.4rem rgb(30 55 68 / 8%);
  }

  .course-card__header {
    padding: 1.55rem 1.65rem 1.35rem;
    background: linear-gradient(135deg, var(--course-surface), transparent);
  }

  .course-card__eyebrow {
    margin-bottom: 0.4rem;
    color: var(--course-accent);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .course-card h2 {
    margin: 0;
    font-size: 1.55rem;
    line-height: 1.35;
  }

  .course-section {
    padding: 1.4rem 1.65rem 1.5rem;
    border-top: 1px solid var(--course-border);
  }

  .course-section h3 {
    margin: 0 0 1rem;
    color: var(--course-accent-strong);
    font-size: 1.12rem;
  }

  .course-notice {
    --notice-accent: #b509ac;
    padding: 1.1rem 1.2rem;
    border: 1px solid color-mix(in srgb, var(--notice-accent) 35%, transparent);
    border-left: 4px solid var(--notice-accent);
    border-radius: 0.5rem;
    background: color-mix(in srgb, var(--notice-accent) 10%, var(--global-bg-color));
    box-shadow: 0 0.35rem 1rem color-mix(in srgb, var(--notice-accent) 12%, transparent);
  }

  .course-notice__item + .course-notice__item {
    margin-top: 1rem;
    padding-top: 1rem;
    border-top: 1px solid color-mix(in srgb, var(--notice-accent) 22%, transparent);
  }

  .course-notice__title {
    margin: 0 0 0.65rem;
    font-size: 1rem;
    font-weight: 700;
    line-height: 1.5;
  }

  .course-notice__title,
  .course-notice__title i,
  .course-notice__title a {
    color: var(--notice-accent);
  }

  .course-notice__title a {
    text-decoration: underline;
    text-underline-offset: 0.15em;
  }

  .course-notice__deadlines {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem 1.25rem;
    margin: 0;
    color: var(--global-text-color-light);
    font-size: 0.9rem;
  }

  .course-notice__deadlines strong {
    color: var(--notice-accent);
  }

  #notice-title {
    color: #b509ac;
  }

  .challenge {
    padding: 1.15rem 1.2rem;
    border-left: 3px solid var(--course-accent);
    border-radius: 0.35rem;
    background: var(--course-surface);
  }

  .challenge__title {
    margin: 0 0 0.35rem;
    font-size: 1.05rem;
    font-weight: 700;
    line-height: 1.45;
  }

  .challenge__meta {
    margin: 0 0 0.35rem;
    color: var(--global-text-color-light);
    font-size: 0.9rem;
  }

  .challenge__deadline {
    margin: 0 0 0.9rem;
    color: var(--course-accent-strong);
    font-size: 0.9rem;
    font-weight: 700;
  }

  .course-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.55rem;
  }

  .course-link {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.45rem 0.75rem;
    border: 1px solid var(--course-border);
    border-radius: 0.35rem;
    background: var(--global-bg-color);
    color: var(--course-accent-strong) !important;
    font-size: 0.88rem;
    font-weight: 600;
    text-decoration: none !important;
  }

  .course-link:hover {
    border-color: var(--course-accent);
    background: var(--course-accent);
    color: #fff !important;
  }

  .practice-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.75rem;
  }

  .chapter-list {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.65rem 1rem;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .chapter-item {
    display: flex;
    align-items: baseline;
    gap: 0.65rem;
    padding: 0.7rem 0.8rem;
    border-bottom: 1px solid var(--course-border);
  }

  .chapter-number {
    flex: 0 0 auto;
    color: var(--course-accent);
    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 0.03em;
  }

  .chapter-name {
    line-height: 1.5;
  }

  .practice-item {
    padding: 0.9rem 1rem;
    border: 1px solid var(--course-border);
    border-radius: 0.5rem;
    background: var(--global-bg-color);
  }

  .practice-item strong {
    display: block;
    color: var(--course-accent-strong);
  }

  .practice-item span {
    color: var(--global-text-color-light);
    font-size: 0.86rem;
  }

  @media (max-width: 600px) {
    .course-card__header,
    .course-section {
      padding-right: 1.1rem;
      padding-left: 1.1rem;
    }

    .practice-grid {
      grid-template-columns: 1fr;
    }

    .chapter-list {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="courses-page">
  <article class="course-card">
    <header class="course-card__header">
      <div class="course-card__eyebrow">Introduction to Artificial Intelligence</div>
      <h2>人工智能导论（匡亚明学院）</h2>
      <p class="course-intro">课程围绕人工智能的基础知识、真实任务挑战与项目实践展开，帮助学生在学习核心概念的同时积累完整的问题分析和工程实践经验。</p>
    </header>

    <section class="course-section" aria-labelledby="notice-title">
      <h3 id="notice-title">最新通知</h3>
      <div class="course-notice">
        <div class="course-notice__item">
          <p class="course-notice__title">
            <i class="fas fa-bullhorn" aria-hidden="true"></i>
            Assignment 1.1 已经上线，<a href="https://xiepengyu2004.github.io/ai-introduction-course/#/assignments/assignment1.1" target="_blank" rel="noopener noreferrer">点击查看作业详情</a>
          </p>
          <p class="course-notice__deadlines">
            <span><strong>Soft DDL：</strong>2026 年 9 月 15 日 23:59</span>
            <span><strong>Hard DDL：</strong>2026 年 9 月 25 日 23:59</span>
          </p>
        </div>
        <div class="course-notice__item">
          <p class="course-notice__title">
            <i class="fas fa-trophy" aria-hidden="true"></i>
            2026 RSNA 膝关节 MRI 异常检测 AI 挑战赛已开放，<a href="https://www.kaggle.com/competitions/rsna-knee-abnormality-detection/overview" target="_blank" rel="noopener noreferrer">点击查看比赛详情</a>
          </p>
          <p class="course-notice__deadlines">
            <span><strong>竞赛任务：</strong>膝关节 MRI 异常检测</span>
            <span><strong>截止时间：</strong>2026 年 10 月 22 日</span>
            <span><strong>竞赛报告截止时间：</strong>待定</span>
          </p>
        </div>
      </div>
    </section>

    <section class="course-section" aria-labelledby="chapters-title">
      <h3 id="chapters-title">章节安排</h3>
      <ol class="chapter-list">
        <li class="chapter-item"><span class="chapter-number">第 0 章</span><span class="chapter-name">人工智能简介</span></li>
        <li class="chapter-item"><span class="chapter-number">第 1 章</span><span class="chapter-name">机器学习基础</span></li>
        <li class="chapter-item"><span class="chapter-number">第 2 章</span><span class="chapter-name">深度学习基础</span></li>
        <li class="chapter-item"><span class="chapter-number">第 3 章</span><span class="chapter-name">卷积神经网络</span></li>
        <li class="chapter-item"><span class="chapter-number">第 4 章</span><span class="chapter-name">循环神经网络</span></li>
        <li class="chapter-item"><span class="chapter-number">第 5 章</span><span class="chapter-name">注意力与 Transformer</span></li>
        <li class="chapter-item"><span class="chapter-number">第 6 章</span><span class="chapter-name">自然语言处理中的自监督学习</span></li>
        <li class="chapter-item"><span class="chapter-number">第 7 章</span><span class="chapter-name">计算机视觉中的自监督学习</span></li>
        <li class="chapter-item"><span class="chapter-number">第 8 章</span><span class="chapter-name">生成式模型基础</span></li>
        <li class="chapter-item"><span class="chapter-number">第 9 章</span><span class="chapter-name">生成式模型进阶</span></li>
        <li class="chapter-item"><span class="chapter-number">第 10 章</span><span class="chapter-name">分词与大语言模型</span></li>
        <li class="chapter-item"><span class="chapter-number">第 11 章</span><span class="chapter-name">多模态大模型</span></li>
        <li class="chapter-item"><span class="chapter-number">第 12 章</span><span class="chapter-name">大模型微调技术</span></li>
        <li class="chapter-item"><span class="chapter-number">第 13 章</span><span class="chapter-name">具身智能与多智能体简介</span></li>
      </ol>
    </section>

    <section class="course-section" aria-labelledby="competition-title">
      <h3 id="competition-title">课程竞赛</h3>
      <div class="challenge">
        <p class="challenge__title">RSNA Knee Abnormality Detection AI Challenge</p>
        <p class="challenge__meta">2026 · 膝关节 MRI 异常检测</p>
        <p class="challenge__deadline"><i class="far fa-calendar-alt" aria-hidden="true"></i> 截止时间：2026 年 10 月 22 日</p>
        <div class="course-links">
          <a class="course-link" href="https://www.rsna.org/artificial-intelligence/ai-image-challenge/knee-mri-ai-challenge" target="_blank" rel="noopener noreferrer">
            <i class="fas fa-external-link-alt" aria-hidden="true"></i>
            RSNA 官网
          </a>
          <a class="course-link" href="https://www.kaggle.com/competitions/rsna-knee-abnormality-detection/overview" target="_blank" rel="noopener noreferrer">
            <i class="fas fa-trophy" aria-hidden="true"></i>
            Kaggle 比赛页面
          </a>
        </div>
      </div>
    </section>

    <section class="course-section" aria-labelledby="practice-title">
      <h3 id="practice-title">课程实践</h3>
      <div class="practice-grid">
        <div class="practice-item"><strong>Assignment 1</strong><span>课程作业</span></div>
        <div class="practice-item"><strong>Assignment 2</strong><span>课程作业</span></div>
        <div class="practice-item"><strong>Assignment 3</strong><span>课程作业</span></div>
        <div class="practice-item"><strong>Final Project</strong><span>课程综合项目</span></div>
      </div>
    </section>
  </article>
</div>
