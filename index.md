---
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.post_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>