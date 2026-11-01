---
layout: page
permalink: /research/
title: research
description: My research focuses on causal inference in political economy, AI evaluation, and LLM-based measurement. Below are my current projects. Please reach me at ml4967@columbia.edu if you have any questions or are interested in collaborating.
nav: true
nav_order: 1
---

<!-- _pages/publications.md: the projects themselves are listed in _data/research.yml -->

<style>
  .publications .project-meta { color: var(--global-text-color-light); }
  .publications .project-description { margin-top: 0.4rem; }
  .publications .project-description p { margin-bottom: 0; }
  .publications ol.bibliography li { margin-bottom: 1.5rem; }
</style>

<div class="publications">
{% for group in site.data.research %}
  <h2 class="bibliography">{{ group.section }}</h2>
  <ol class="bibliography">
  {% for project in group.projects %}
    <li>
      <div class="row">
        <div class="col-sm-10">
          <div class="title">{{ project.title }}</div>
          {% capture meta %}{% if project.coauthors %}with {{ project.coauthors | array_to_sentence_string }}{% endif %}{% if project.coauthors and project.status %} · {% endif %}{% if project.status %}{{ project.status | markdownify | remove: '<p>' | remove: '</p>' | strip }}{% endif %}{% endcapture %}
          {% assign meta = meta | strip %}
          {% if meta != "" %}<div class="periodical project-meta">{{ meta }}</div>{% endif %}
          <div class="project-description">{{ project.description | markdownify }}</div>
        </div>
      </div>
    </li>
  {% endfor %}
  </ol>
{% endfor %}
</div>
