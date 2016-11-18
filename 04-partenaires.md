---
title: Partenaires
published: false
layout: main
---

{% for partners in site.data.partners %}
  {{ partners.name }}
  {{ partners.logo }}
  {{ partners.motivation }}
{% endfor %}
