---
layout: default
title: 活動記録一覧
---

<p class="end-of-content"><a href="/">←Home</a></p>

# HUIT これまでの活動記録

<ul>
{% for post in site.posts reversed %}

  {% if post.previous %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% capture pyear %}{{ post.previous.date | date: '%Y' }}{% endcapture %}
  {% endif %}

  {% if post.previous %}
    {% if year != pyear %}
      <!-- 新しい年だったとき -->
      </ul>
      <li><h3>{{ post.date | date: '%Y' }} 年</h3></li>
      <ul>
        <li>{{ post.date | date: "%m月" }} <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% else %}
      <!-- 前の記事と同じ年だったとき -->
      <li>{{ post.date | date: "%m月" }} <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% else %}
    <!-- pyearが無いとき、つまり始めの年のとき -->
    <li><h3>{{ post.date | date: '%Y' }} 年</h3></li>
    <ul>
      <li>{{ post.date | date: "%m月" }} <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endif %}

  {% if forloop.last %}</ul>{% endif %}

{% endfor %}
</ul>

<style>
  li { margin: 10px 0; }
</style>