---
layout: articles
title: News
articles:
  data_source: paginator.posts
  article_type: BlogPosting
  show_cover: false
  show_excerpt: true
  show_readmore: true
  show_info: true
key: page-news
---
<div class="layout--home">
  {%- include paginator.html -%}
</div>
<script>
  {%- include scripts/home.js -%}
</script>

{{ content }}
<!-- <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul> -->