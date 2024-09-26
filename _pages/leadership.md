---
layout: archive
title: "Leadership"
permalink: /leadership/
author_profile: true
---
<hr/>
{% include base_path %}

<!-- New style rendering if leadership categories are defined -->
{% if site.leadership_category %}
  {% for category in site.leadership_category  %}
    {% assign title_shown = false %}
    {% for post in site.leadership reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <p/><h2>{{ category[1].title }}</h2>
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.leadership reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}



