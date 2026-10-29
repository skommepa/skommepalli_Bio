---
permalink: /sites/
title: "My Sites"
---

Other websites I run.

<div class="cards">
{% for s in site.data.sites %}
  <a class="card" href="{{ s.url }}"><h3>{{ s.name }} ↗</h3><p>{{ s.description }}</p></a>
{% endfor %}
</div>
