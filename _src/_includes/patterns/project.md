
<div class="card-group">
{% for p in project %}
<div class="card-flag">
<img src="/assets/{{ p.img }}" />
<div class="body">
  <h3><a href="{{ p.link }}">{{ p.title }}</a></h3>
  <p> {{ p.content}} </p>
</div>
</div>
{% endfor %}
</div>
