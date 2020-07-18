---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Journal Articles
----------------

{% capture written_year %}'None'{% endcapture %}
{% for post in site.publications reversed %}
  {% if post.type %}
   {% if post.type == 'journal' %}
    {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
    {% if year != written_year %}
      {% include year-heading.html %}
      {% capture written_year %}{{ year }}{% endcapture %}    
    {% endif %}
    {% include archive-single.html %}
   {% endif %}
  {% endif %}
{% endfor %}

Conference Papers
-----------------

{% capture written_year %}'None'{% endcapture %}
{% for post in site.publications reversed %}
  {% if post.type != 'journal' %}
    {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
    {% if year != written_year %}
      {% include year-heading.html %}
      {% capture written_year %}{{ year }}{% endcapture %}    
    {% endif %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
