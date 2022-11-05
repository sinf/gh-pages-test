---
layout: default
---

# Index

text text text  

[Link to Page](./Page)
[Link to one post]({% link _posts/2022-11-05-new-post.md %})
[Link to one post](/_posts/2022-11-05-new-post.md)

# Index of posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

