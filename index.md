---
layout: default
title: Home
permalink: /
---

<section class="hero">
  <img src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="Photo of {{ site.author.name }}" class="profile-photo" onerror="this.style.display='none'">
  <h1>{{ site.author.name }}</h1>
  <p class="hero-tagline">{{ site.tagline }}</p>
  <p class="hero-affiliation">{{ site.author.affiliation }}</p>
</section>

## About

My research interests include structural and empirical estimation in corporate finance, entrepreneurial finance, and banking, with a particular emphasis on alternative sources of firm financing, including private credit, private equity, and venture capital.

I am a PhD student in Economics at {{ site.author.affiliation }} and a Research Assistant in the Financial Markets team at SAFE. I am part of the {% if site.links.wefi != "" %}[WEFI Fellows]({{ site.links.wefi }}){% else %}WEFI Fellows{% endif %} program of the Workshop on Entrepreneurial Finance and Innovation (WEFI), and I co-organize the student-led WEFI workshop.

**Visiting periods:** HEC Paris (Apr – May 2026; host: Matthias Efing) and SAFE, Goethe University Frankfurt (Oct 2025 – Mar 2026; host: Loriana Pelizzon).

## Research {#research}

{% include research.html %}
