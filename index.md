---
title: SiliWiki - IC Design Process
layout: default
---

# Integrated Circuit (IC) Design Process
The journey from **specifications** to a **manufactured chip** involves multiple steps:

---

<div class="process-grid">
{% for process in site.data.ic_design_steps %}
    <div class="process-card">
      <a href="{{ process.link }}">
        <img src="{{ process.image }}" alt="{{ process.name }}">
        <h3>{{ process.name }}</h3>
        <p>{{ process.description }}</p>
      </a>
    </div>
  {% endfor %}
</div>

[🔙 Back to Main Page](https://danielthurmond.github.io/)
