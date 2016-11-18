---
layout: main
title: Partenaires
published: false
---

{% for partners in site.data.partners %}
  {{ partners.name }}
  {{ partners.logo }}
  {{ partners.motivation }}
{% endfor %}
