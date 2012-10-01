---
layout: default
title: Best Practices
contributors: Harlan T Wood
---

{% for content_page in site.html_pages %}
{% if content_page.url != page.url %}
<section>
  <header>
    <h1>{{ content_page.title }}</h1>
  </header>
  <div>
    {{ content_page.content }}
  </div>
</section>
{% endif %}
{% endfor %}
