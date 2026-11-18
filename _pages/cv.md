---
layout: academic-profile
title: Academic CV
permalink: /cv/
excerpt: Academic CV of M. G. Nirosha Darshani Weerarathna, including education, appointments, scholarship, teaching qualifications and technical skills.
---

<div class="cv-page" markdown="0">
  <header class="page-heading">
    <h1>Academic CV</h1>
    <p><strong>M. G. Nirosha Darshani Weerarathna</strong><br>PhD candidate, Wuhan University of Technology</p>
    <p>Research supervisor · <a href="https://junwzhou.github.io/">Prof. Junwei Zhou</a></p>
    <p class="print-only">Email · {{ site.author.email }}</p>
    <button class="print-button" type="button" onclick="window.print()">Print CV / save PDF</button>
  </header>
  <section class="section" aria-labelledby="education">
    <h2 id="education">Education</h2>
    <article class="entry">
      <p class="date">December 2022 – October 2026</p>
      <h3>Postgraduate Diploma in Electrical Engineering</h3>
      <p>University of Moratuwa, Sri Lanka</p>
    </article>
    <article class="entry">
      <p class="date">June 2017 – July 2021</p>
      <h3>Bachelor of Technology in Electrical and Electronics Engineering</h3>
      <p>National Institute of Technology Meghalaya, India · First Class Honours · GPA 8.47/10</p>
      <p>My undergraduate thesis explored the use of a cascaded H-bridge multilevel inverter for distribution static compensation (DSTATCOM) to improve power quality. I completed it under the supervision of Dr. Ramyani Chakrabarty.</p>
    </article>
  </section>
  <section class="section" aria-labelledby="appointments">
    <h2 id="appointments">Academic appointments</h2>
    <article class="entry">
      <p class="date">November 2023 – August 2026</p>
      <h3>Lecturer (Probationary)</h3>
      <p>Department of Electrical and Telecommunication Engineering, South Eastern University of Sri Lanka</p>
    </article>
    <article class="entry">
      <p class="date">October 2022 – October 2023</p>
      <h3>Temporary Lecturer</h3>
      <p>Department of Electrical and Computer Engineering, The Open University of Sri Lanka</p>
    </article>
    <a class="more screen-only" href="{{ site.baseurl }}/teaching/">Teaching and supervision <span aria-hidden="true">→</span></a>
  </section>
  <section class="section" aria-labelledby="training">
    <h2 id="training">Scholarship and professional development</h2>
    <ul class="summary-list">
      <li><strong>Certificate in Teaching and Related Initial Practices in Higher Education.</strong> Staff Development Centre, Eastern University, Sri Lanka, June 2025 – May 2026.</li>
      <li><strong>5G Mobile Communication Technology and Applications for Sri Lanka.</strong> Seminar organized by the Academy for International Business Officials, Ministry of Commerce, China, October–November 2025.</li>
      <li><strong>Nehru Memorial Scholarship Scheme.</strong> Full Government of India scholarship for undergraduate study, 2017–2021.</li>
    </ul>
  </section>
  <section class="section" aria-labelledby="tools">
    <h2 id="tools">Technical skills</h2>
    <p>Power system simulation and design with PSCAD, HOMER, OpenDSS, ETAP and AutoCAD. Programming in MATLAB, C and C++.</p>
  </section>
  <div class="section screen-only"><a class="more" href="{{ site.baseurl }}/publications/">Full publication list <span aria-hidden="true">→</span></a></div>
  <section class="section print-only" aria-labelledby="cv-publications">
    <h2 id="cv-publications">Publications</h2>
    {% for group in site.data.profile_papers %}{% for paper in group.papers %}
    <p class="record">{{ paper.authors | escape }} ({{ group.year }}). <strong>{{ paper.title | escape }}.</strong> <em>{{ paper.venue | escape }}.</em></p>
    {% endfor %}{% endfor %}
  </section>
</div>
