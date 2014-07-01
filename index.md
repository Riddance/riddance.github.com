---
layout: page
---
{% include JB/setup %}
<div class="posts">
  {% for post in site.posts %}
    <div class="post">
      <div class="header">
        <div class="date">{{ post.date | date_to_string}}</div>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      </div>
      <div class="meta-header"></div>
      <div class="body">
        {{ post.content }}
      </div>
      <div class="meta-footer">
      </div>
    </div>
  {% endfor %}
</div>



