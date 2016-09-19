---
layout: main
title: Partenaires
published: true
---

{% for partners in site.data.partners %}
  {{ partners.name }}
  {{ partners.logo }}
  {{ partners.motivation }}
{% endfor %}
