---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

###  [Journal Articles](#journal-articles) &nbsp;&nbsp;&nbsp; [Conference Papers](#conference-papers)

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
