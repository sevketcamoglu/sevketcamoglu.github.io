---
layout: default
title: Contact
permalink: /contact/
---

# Contact

**Email:** [{{ site.author.email }}](mailto:{{ site.author.email }})

**Affiliation:** {{ site.author.affiliation }}
**Research affiliation:** {{ site.author.research_affiliation }}

*[PLACEHOLDER — add your office address / room number here if you'd like it public.]*

<p class="footer-links">
{% if site.social.google_scholar != "" %}<a href="{{ site.social.google_scholar }}" target="_blank" rel="noopener">Google Scholar</a>{% endif %}
{% if site.social.orcid != "" %}<a href="{{ site.social.orcid }}" target="_blank" rel="noopener">ORCID</a>{% endif %}
{% if site.social.github != "" %}<a href="{{ site.social.github }}" target="_blank" rel="noopener">GitHub</a>{% endif %}
{% if site.social.linkedin != "" %}<a href="{{ site.social.linkedin }}" target="_blank" rel="noopener">LinkedIn</a>{% endif %}
</p>
