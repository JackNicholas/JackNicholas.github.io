---

layout: default
title: "Testing jrn-ebo home page"

---



        # Testing markdown etc
        
  this is a test
  
  {{ page.title }}
  
  
  <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

