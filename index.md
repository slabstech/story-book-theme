---
layout: page
---


<center> <h3> {{ site.title }}</h3> </center>

<center> <h4> {{ site.description }} </h4> </center>


<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
