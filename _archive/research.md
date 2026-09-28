---
layout: default
title: Research
permalink: /research/
---

# Research

*[PLACEHOLDER — optional 1–2 sentence overview of your overall research agenda.]*

## Working Papers

{% assign papers = site.working_papers | sort: 'date' | reverse %}
{% if papers.size > 0 %}
<ul class="paper-list">
  {% for p in papers %}
  <li>
    <a href="{{ p.url | relative_url }}">{{ p.title }}</a>
    {% if p.authors %}<br><span class="paper-list-authors">{{ p.authors }}</span>{% endif %}
    {% if p.date %}<br><span class="paper-list-date">{{ p.date | date: "%B %Y" }}</span>{% endif %}
  </li>
  {% endfor %}
</ul>
{% else %}
<p><em>No working papers listed yet.</em></p>
{% endif %}

## Publications

{% assign pubs = site.publications | sort: 'date' | reverse %}
{% if pubs.size > 0 %}
<ul class="paper-list">
  {% for p in pubs %}
  <li>
    <a href="{{ p.url | relative_url }}">{{ p.title }}</a>
    {% if p.journal %}<br><span class="paper-list-authors"><em>{{ p.journal }}</em></span>{% endif %}
  </li>
  {% endfor %}
</ul>
{% else %}
<p><em>No publications yet — as a current PhD student, this section will be updated as papers are published.</em></p>
{% endif %}

## Work in Progress

{% assign wips = site.wip %}
{% if wips.size > 0 %}
<ul class="paper-list">
  {% for p in wips %}
  <li>
    <a href="{{ p.url | relative_url }}">{{ p.title }}</a>
    {% if p.authors %}<br><span class="paper-list-authors">{{ p.authors }}</span>{% endif %}
  </li>
  {% endfor %}
</ul>
{% else %}
<p><em>No work in progress listed yet.</em></p>
{% endif %}

## Conference & Seminar Presentations

{% assign talks = site.presentations | sort: 'date' | reverse %}
{% if talks.size > 0 %}
<ul class="paper-list">
  {% for t in talks %}
  <li>
    <strong>{{ t.title }}</strong><br>
    <span class="paper-list-authors">{{ t.venue }}{% if t.date %}, {{ t.date | date: "%B %Y" }}{% endif %}</span>
  </li>
  {% endfor %}
</ul>
{% else %}
<p><em>No presentations listed yet.</em></p>
{% endif %}
