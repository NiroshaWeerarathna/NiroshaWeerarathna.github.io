---
layout: academic-profile
title: Nirosha Weerarathna
permalink: /
excerpt: "Research by Nirosha Weerarathna on power quality, renewable energy integration and fault diagnosis in electrical distribution networks."
redirect_from:
  - /about/
  - /about.html
---

<div class="home-page" markdown="0">
  <header class="hero">
    <p class="hero-affiliation"><a href="https://www.whut.edu.cn/">Wuhan University of Technology</a></p>
    <h1>Nirosha Weerarathna</h1>
    <p class="hero-role">PhD candidate</p>
    <p class="supervisor">Research supervisor · <a href="https://junwzhou.github.io/">Prof. Junwei Zhou</a></p>
    <div class="actions">
      <a class="action primary" href="{{ site.baseurl }}/publications/">Selected publications</a>
      <a class="action" href="{{ site.baseurl }}/projects/">Research projects</a>
    </div>
  </header>

  <section class="section" aria-labelledby="about">
    <h2 id="about">About</h2>
    <p>I am an electrical and electronic engineering researcher and a PhD candidate at Wuhan University of Technology. I study how power networks behave when they carry more renewable energy. My work looks at how batteries can help keep a network stable, how solar generation and nonlinear loads affect voltage quality, and how machine learning can help locate electrical faults.</p>
    <p>Before coming to Wuhan, I taught electrical engineering at South Eastern University of Sri Lanka and The Open University of Sri Lanka. At both universities, I supervised undergraduate research. My own early work on power quality began at the National Institute of Technology Meghalaya, where I studied how a multilevel inverter could compensate for disturbances in a distribution system.</p>
  </section>

  <section class="section" aria-labelledby="research-areas">
    <h2 id="research-areas">Research areas</h2>
    <div class="area-grid">
      <div class="area">
        <h3>Power quality and fault diagnosis</h3>
        <p>Detecting disturbances in voltage signals and identifying the type and location of faults in low- and medium-voltage networks.</p>
      </div>
      <div class="area">
        <h3>Renewable energy integration</h3>
        <p>Studying battery storage and solar generation on the grid, alongside ways to harvest energy from waves, small hydro sites and road surfaces.</p>
      </div>
    </div>
  </section>

  <section class="section" aria-labelledby="selected-publications">
    <h2 id="selected-publications">Selected publications</h2>
    <ul class="summary-list">
      {% for group in site.data.profile_papers %}{% for paper in group.papers %}{% if paper.selected %}
      <li><a href="{{ paper.link | escape }}">{{ paper.title | escape }}</a>. <em>{{ paper.short_venue }}</em>, {{ group.year }}.</li>
      {% endif %}{% endfor %}{% endfor %}
    </ul>
    <a class="more" href="{{ site.baseurl }}/publications/">All publications <span aria-hidden="true">→</span></a>
  </section>

  <section class="section" aria-labelledby="current-projects">
    <h2 id="current-projects">Current research projects</h2>
    <ul class="summary-list">
      {% for project in site.data.profile_projects.ongoing %}{% if project.featured %}
      <li>{{ project.title | escape }}</li>
      {% endif %}{% endfor %}
    </ul>
    <a class="more" href="{{ site.baseurl }}/projects/">All research projects <span aria-hidden="true">→</span></a>
  </section>
</div>
