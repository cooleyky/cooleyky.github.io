---
title: Past Blog Posts
layout: default
---
<!-- Instructions from creating an index of all posts from https://jekyllrb.com/docs/posts/#displaying-an-index-of-posts -->
<ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
</ul>