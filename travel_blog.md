---
layout: page
title: Travel Blog
description: Lots more to explore! Hang in there for more ...
order: 4
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More...</a>
    </article>
    <br/>
  {% endfor %}
</div>