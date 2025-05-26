---
title: El Dream Team
permalink: /about/
layout: default
---

<section class="cards-grid about-column">
  {% for person in site.data.team %}
    {% include card-person.html person=person %}
  {% endfor %}
</section>
