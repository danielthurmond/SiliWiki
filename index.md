---
title: SiliWiki - IC Design Process
layout: default
---

# Integrated Circuit (IC) Design Process
The journey from **specifications** to a **manufactured chip** involves multiple steps:

<div class="process-grid">
  {% for step in site.data.ic_design_steps %}
    <div class="process-card">
      <a href="{{ step.link }}">
        <h3>{{ step.name }}</h3>
        <p>{{ step.description }}</p>
      </a>
    </div>
  {% endfor %}
</div>

[🔙 Back to Main Page](https://danielthurmond.github.io/)
