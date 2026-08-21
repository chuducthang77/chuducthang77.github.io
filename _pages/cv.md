---
permalink: /cv/
title: cv
nav: true
nav_order: 5
nav_link: /assets/pdf/CV.pdf
sitemap: false
---
<!doctype html>
<html lang="{{ site.lang | default: 'en' }}">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="refresh" content="0; url={{ page.nav_link | relative_url }}">
    <link rel="canonical" href="{{ page.nav_link | absolute_url }}">
    <title>CV - {{ site.first_name }} {{ site.last_name }}</title>
    <script>
      window.location.replace({{ page.nav_link | relative_url | jsonify }});
    </script>
  </head>
  <body>
    <p>Opening <a href="{{ page.nav_link | relative_url }}">Thang D. Chu's CV (PDF)</a>...</p>
  </body>
</html>
