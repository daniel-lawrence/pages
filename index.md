<html>
<head><title>Test Github Pages -- Main Landing Page</title></head>
<body>
<h1> Hello World.</h1>
  <ul>
  {% for page in site.pages %}
  <li>{{ page.title }}</li>
{% endfor %}
    </ul>
</body>
</html>
