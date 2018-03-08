---

layout: default
title: "Jack Nicholas: home"

---



# Jack Nicholas: writing, notes, links, about, etc. 
  
  {{ page.title }}
  
  
  <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%B %e, %Y" }})
    </li>
  {% endfor %}
</ul>
