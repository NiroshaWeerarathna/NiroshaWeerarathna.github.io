---
layout: academic-profile
title: Nirosha Weerarathna
permalink: /
excerpt: "Research by Nirosha Weerarathna on artificial intelligence, computer vision, machine vision, fault detection and data-driven engineering systems."
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
    <p>I am an electrical and electronic engineering researcher and a PhD candidate at Wuhan University of Technology, China, with an interdisciplinary research focus spanning Electrical Engineering, Computer Science, and Artificial Intelligence. My current research explores the application of AI, machine learning, and deep learning techniques to solve complex engineering problems. My research interests include computer vision, AI-based image compression, machine vision, intelligent fault detection, and data-driven engineering systems. I am particularly interested in developing efficient and intelligent computational approaches for real-world applications.</p>
    <p>Before coming to Wuhan, I taught electrical engineering at South Eastern University of Sri Lanka and The Open University of Sri Lanka, where I also supervised undergraduate research projects. My academic foundation was established at the National Institute of Technology Meghalaya, India, where I completed my Bachelor's degree in Electrical and Electronics Engineering. My early research work focused on power quality, particularly investigating how multilevel inverters could compensate for disturbances in electrical distribution systems.</p>
    <p>My broader research interests bring together electrical engineering principles and emerging computational technologies, particularly exploring how artificial intelligence can contribute to smarter, more efficient, and reliable engineering systems.</p>
  </section>

  <section class="section" aria-labelledby="research-areas">
    <h2 id="research-areas">Research areas</h2>
    <div class="area-grid">
      <div class="area">
        <h3>Artificial intelligence and machine learning</h3>
        <p>Developing machine learning and deep learning approaches for intelligent, efficient and data-driven engineering systems.</p>
      </div>
      <div class="area">
        <h3>Computer vision and intelligent fault detection</h3>
        <p>Applying computer vision, machine vision and AI-based image analysis to image compression and fault detection in real-world systems.</p>
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
