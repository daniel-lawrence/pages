---
title: Test Github Pages -- Main Landing Page
---
{% assign thispage = page.url %}

<h1> Hello World.</h1>
  <ul>
{% for page in site.html_pages %}
    {% if page.url != thispage %}
  <li><a href="http://daniel-lawrence.github.io/pages{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
{% else %}
    
{% endfor %}
    </ul>
