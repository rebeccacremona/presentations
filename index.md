---
---

{% for slides in site.slides %}
 - [{{ slides.slug }} (html)]({{ slides.url | relative_url }})
 - [{{ slides.slug }} (slideshow)]({{ "/slides/" | append: slides.slug  | relative_url }})
{% endfor %}
