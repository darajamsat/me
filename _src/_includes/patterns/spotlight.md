<style>
  .spotlight {
    background-color: #CDB3AE;
  }
  .card-group {
    @media (min-width: 800px){
      padding: 20px 20px;
    }
  }
</style>
<div class="spotlight grid">

## Project story spotlight 

<div class="card-group">
{%- for post in collections.projects reversed limit:2 -%}
<div class="card-flag">
<img src="/assets/projects/{{ post.data.feature }}" />
<div class="body">
  <h3><a href="{{ post.url }}">{{ post.data.title }}</a></h3>
  <p> {{ post.data.short }} </p>
</div>
</div>
{% endfor %}
</div>

[view all project stories](/stories) <i class="fa-duotone fa-solid fa-arrow-right-to-arc"></i>
</div>