---
layout: layouts/base
title: Project stories

project:
  - title: Client Name
    content: |
      I belief it is my mission to help people live better lives through Art & Technology
    img: placeholder.png
    link: #
  - title: Client Name
    content: |
      I belief it is my mission to help people live better lives through Art & Technology
    img: placeholder.png
    link: #
  - title: Client Name
    content: |
      I belief it is my mission to help people live better lives through Art & Technology
    img: placeholder.png
    link: #
  - title: Client Name
    content: |
      I belief it is my mission to help people live better lives through Art & Technology
    img: placeholder.png
    link: #
---
<style>
 
</style>
<div class="grid grid-color">

# {{ title }}

<div class="card-group">
{%- for post in collections.projects reversed -%}
<div class="card-flag">
<img src="/assets/projects/{{ post.data.feature }}" />
<div class="body">
  <h3><a href="{{ post.url }}">{{ post.data.title }}</a></h3>
  <p> {{ post.data.short }} </p>
</div>
</div>
{% endfor %}
</div>

</div>