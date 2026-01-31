---
title: "About me"
nav_order: 1
permalink: /
---

{% if site.author.photo %}
<div style="margin: 12px 0;">
  <img
    src="{{ site.author.photo | relative_url }}"
    alt="{{ site.author.name | default: 'Photo' }}"
    width="160"
    style="border-radius: 14px;"
  />
</div>
{% endif %}

{% include social-links.html %}