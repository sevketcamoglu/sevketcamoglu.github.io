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
    <h1>Hi! My name is {{ site.author.name }}.</h1>
    <p class="intro-tagline">{{ site.tagline }} &middot; {{ site.author.affiliation }}</p>
    <p>I study how firms raise financing beyond traditional bank lending, including private credit, private equity, and venture capital. My work uses structural and empirical estimation in corporate finance, entrepreneurial finance, and banking.</p>
    <p>I am a Research Assistant in the Financial Markets team at SAFE. I am part of the {% if site.links.wefi != "" %}<a href="{{ site.links.wefi }}" target="_blank" rel="noopener">WEFI Fellows</a>{% else %}WEFI Fellows{% endif %} program of the Workshop on Entrepreneurial Finance and Innovation (WEFI), and I co-organize the student-led WEFI workshop.</p>
    <p><strong>Research Interests:</strong> Private Equity, Venture Capital, Entrepreneurial Finance, Corporate Finance.</p>
    <p><strong>Visiting periods:</strong> HEC Paris (Apr &ndash; May 2026; host: Matthias Efing) and SAFE, Goethe University Frankfurt (Oct 2025 &ndash; Mar 2026; host: Loriana Pelizzon).</p>
    <p class="intro-actions">{% if site.links.cv != "" %}<a class="btn" href="{{ site.links.cv }}" target="_blank" rel="noopener">Download CV (PDF)</a>{% else %}<a class="btn" href="{{ '/assets/pdf/cv/cv.pdf' | relative_url }}" target="_blank" rel="noopener">Download CV (PDF)</a>{% endif %}</p>
  </div>
</section>

## Research {#research}

### Working Papers

{% include research.html %}
