---
layout: default
title: Carpe Hora Publications
---
# Welcome !
This is the homepage for [Carpe Hora Github repositories](https://github.com/Carpe-Hora).

{% for post in site.posts limit:5 %}
<div class="repo">  
  <h2 class="repotitle" ><a href="{{ post.link }}">{{ post.title }}</a></h2>
  {{ post.content }}
  <em>Ajouté le {{ post.date | date_to_long_string }}.</em>
</div>  
{% endfor %}


