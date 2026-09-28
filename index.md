---
layout: default
title: Home
permalink: /
---

<section class="hero">
  <img src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="Photo of {{ site.author.name }}" class="profile-photo" onerror="this.style.display='none'">
  <h1>{{ site.author.name }}</h1>
  <p class="hero-tagline">{{ site.tagline }}</p>
  <p class="hero-affiliation">{{ site.author.affiliation }} &middot; {{ site.author.research_affiliation }}</p>
  <p class="hero-links">
    <a class="btn" href="{{ '/assets/pdf/cv/cv.pdf' | relative_url }}" target="_blank">Download CV (PDF)</a>
    <a class="btn btn-secondary" href="{{ '/contact/' | relative_url }}">Contact</a>
  </p>
</section>

## About

I am a PhD student in Economics/Finance at **{{ site.author.affiliation }}**, and a research affiliate at **{{ site.author.research_affiliation }}**. My advisors are **{{ site.author.advisors[0] }}** and **{{ site.author.advisors[1] }}**.

*[PLACEHOLDER — replace this paragraph with 3–5 sentences introducing yourself, your PhD program, and what motivates your research.]*

## Research Interests

- Venture Capital
- Private Equity
- Private Credit
- Government Venture Capital
- Entrepreneurial Finance
- Financial Economics

## Current Research

My main ongoing project studies **Government Venture Capital (GovVC) in Europe** — how public co-investment and government-backed VC funds shape financing, selection, and outcomes for young innovative firms.

*[PLACEHOLDER — expand with 2–3 sentences on your specific research question and approach.]*

[See my Research page &rarr;]({{ '/research/' | relative_url }})
