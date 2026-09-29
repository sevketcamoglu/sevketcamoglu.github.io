---
layout: default
title: Home
permalink: /
---

<section class="intro">
  <div class="intro-photo">
    <img src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="Photo of {{ site.author.name }}">
  </div>
  <div class="intro-text">
    <h1 style="font-size: 1.5rem;">Hi! My name is {{ site.author.name }}.</h1>
    <p class="intro-tagline">{{ site.tagline }} &middot; {{ site.author.affiliation }}</p>
    <p>I study how firms access financing beyond traditional bank lending, with a focus on private credit, private equity, and venture capital. My research combines structural and empirical methods to study corporate finance, entrepreneurial finance, and banking.</p>
    <p>
  I am a Research Assistant in the Financial Markets team at
  <a href="{{ site.links.safe }}" target="_blank" rel="noopener">SAFE</a>,
  and I am part of the
  {% if site.links.wefi != "" %}
    <a href="{{ site.links.wefi }}" target="_blank" rel="noopener">WEFI Fellows</a>
  {% else %}
    WEFI Fellows
  {% endif %}
  program, and I co-organize the student-led WEFI workshop.
</p>
    <p><strong>Research Interests:</strong> Private Equity, Venture Capital, Entrepreneurial Finance, Corporate Finance.</p>
    <p><strong>Visiting periods:</strong> HEC Paris (Apr &ndash; May 2026; host: Matthias Efing) and SAFE (Oct 2025 &ndash; Mar 2026; host: Loriana Pelizzon).</p>
    <p class="intro-actions">{% if site.links.cv != "" %}<a class="btn" href="{{ site.links.cv }}" target="_blank" rel="noopener">Download CV</a>{% else %}<a class="btn" href="{{ '/assets/pdf/cv/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Download CV</a>{% endif %}</p>
  </div>
</section>

## Research {#research}

### Working Papers

{% include research.html %}
