---
layout: page
title : About
permalink: /about/
---

<div class="footer-col footer-col-2 footer-content">
  <ul class="social-media-list">
    {% if site.github_username %}
    <li>
      {% include icon-github.html username=site.github_username %}
    </li>
    {% endif %}

    {% if site.email %}
    <li>
    <a href="mailto:{{ site.email }}"><span class="username">{{ site.email }}</span></a>
    </li>
    {% endif %}

  </ul>
</div>
