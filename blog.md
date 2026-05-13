---
layout: fullwidth
title: Blog
permalink: /blog/
---

<style>
  .fullwidth-container {
    max-width: 1400px !important;
    width: 100% !important;
  }
  .page-content {
    max-width: 100% !important;
  }
</style>

{% for post in site.posts %}
  <div style="margin-bottom: 2rem;">
    <h2><a href="{{ post.url }}" style="text-decoration: none;">{{ post.title }}</a></h2>
    <p style="opacity: 0.7;">{{ post.date | date: "%B %d, %Y" }}</p>
    <p>{{ post.excerpt }}</p>
    <a href="{{ post.url }}">Read more →</a>
  </div>
{% endfor %}