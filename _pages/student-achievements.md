---
layout: page
title: Student Honors
permalink: /student-achievements/
description: 学生竞赛荣誉与科研成长
nav: true
nav_order: 5
---

<style>
  .achievements {
    --achievement-accent: #3f7185;
    --achievement-border: rgb(63 113 133 / 20%);
  }
  .achievements .achievement-year {
    display: grid;
    grid-template-columns: 4.5rem minmax(0, 1fr);
    gap: 1.5rem;
    margin-bottom: 2.5rem;
  }
  .achievements .achievement-year > h2 {
    margin: 0;
    padding-top: 1.15rem;
    color: var(--achievement-accent);
    font-size: 1.35rem;
    font-weight: 600;
    font-variant-numeric: tabular-nums;
  }
  .achievements .achievement-list {
    margin: 0;
    padding: 0;
    list-style: none;
    border-top: 1px solid var(--achievement-border);
  }
  .achievements .achievement-entry {
    padding: 1.15rem 0;
    border-bottom: 1px solid var(--achievement-border);
  }
  .achievements .achievement-meta {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin-bottom: 0.6rem;
    font-size: 0.8rem;
  }
  .achievements time {
    color: var(--global-text-color-light);
    font-variant-numeric: tabular-nums;
  }
  .achievements .achievement-award {
    padding: 0.15rem 0.6rem;
    border-radius: 0.25rem;
    background: rgb(63 113 133 / 10%);
    color: var(--achievement-accent);
    font-weight: 600;
  }
  .achievements .achievement-entry h3 {
    margin: 0 0 0.35rem;
    font-size: 1.02rem;
    font-weight: 600;
    line-height: 1.6;
    overflow-wrap: anywhere;
  }
  .achievements .achievement-detail {
    margin: 0 0 0.55rem;
    color: var(--global-text-color-light);
    font-size: 0.88rem;
    line-height: 1.65;
  }
  .achievements .achievement-students {
    margin: 0;
    font-size: 0.92rem;
    line-height: 1.7;
  }
  .achievements .achievement-links {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin-top: 0.55rem;
    font-size: 0.8rem;
  }
  .achievements .achievement-links a { color: var(--achievement-accent); }
  .achievements .achievement-links a:hover { text-decoration: underline; }
  .achievements .achievement-links a:focus-visible {
    outline: 2px solid var(--achievement-accent);
    outline-offset: 3px;
  }
  .achievements .achievement-section-heading {
    margin: 0 0 1.25rem;
    font-size: 1.35rem;
  }
  html[data-theme="dark"] .achievements { --achievement-accent: #8fbccc; }
  @media (max-width: 576px) {
    .achievements .achievement-year { grid-template-columns: 1fr; gap: 0.75rem; }
    .achievements .achievement-year > h2 { padding-top: 0; }
  }
</style>

<div class="achievements">
  <h2 class="achievement-section-heading">Competition Awards <span lang="zh">· 竞赛获奖</span></h2>
  {% assign years = site.data.student_achievements.awards | group_by_exp: "item", "item.date | slice: 0, 4" %}
  {% for year in years %}
  <section class="achievement-year" aria-labelledby="awards-{{ year.name }}">
    <h2 id="awards-{{ year.name }}">{{ year.name }}</h2>
    <ul class="achievement-list">
      {% for achievement in year.items %}
        {% include student-achievement.liquid achievement=achievement %}
      {% endfor %}
    </ul>
  </section>
  {% endfor %}

  <h2 class="achievement-section-heading">Research Recognition <span lang="zh">· 科研资助</span></h2>
  {% assign research_years = site.data.student_achievements.research | group_by_exp: "item", "item.date | slice: 0, 4" %}
  {% for year in research_years %}
  <section class="achievement-year" aria-labelledby="research-{{ year.name }}">
    <h2 id="research-{{ year.name }}">{{ year.name }}</h2>
    <ul class="achievement-list">
      {% for achievement in year.items %}
        {% include student-achievement.liquid achievement=achievement %}
      {% endfor %}
    </ul>
  </section>
  {% endfor %}
</div>
