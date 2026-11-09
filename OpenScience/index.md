---
title: Open-Science-Portal
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# <i class="fas fa-tools"></i> Open Science Portal

We are fully committed to open science: open-source software, public datasets and benchmarks built for AI research, and open-access publications. Open science makes impactful science. Below you find the tools and data released with our papers and earlier open-science work by our group members.

{% assign n_sw = site.data.tools | data_filter: "group == 'software'" | size %}
{% assign n_data = site.data.tools | data_filter: "group == 'data'" | size %}
{% assign n_prev = site.data.tools | data_filter: "group == 'previous'" | size %}

<div class="os-jump">
  <a href="#software"><i class="fa-solid fa-code"></i> Software <b>{{ n_sw }}</b></a>
  <a href="#data"><i class="fa-solid fa-database"></i> Datasets <b>{{ n_data }}</b></a>
  <a href="#earlier-work"><i class="fa-solid fa-clock-rotate-left"></i> Earlier work <b>{{ n_prev }}</b></a>
</div>

{% include section.html %}

{% include search-box.html %}

{% include search-info.html %}

<h2 id="software">Open-source software</h2>

{% include os-grid.html group="software" %}

{% include section.html %}

<h2 id="data">Open datasets</h2>

{% include os-grid.html group="data" %}

{% include section.html %}

<h2 id="earlier-work">Earlier work by our group members</h2>

{% include os-grid.html group="previous" %}
