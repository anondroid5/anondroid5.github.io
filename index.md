---
layout: top
---
{% include JB/setup %}
<img src="/images/index/technology.jpg" width="820px">

Here's `Posts List!`

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
