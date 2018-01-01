<div class="page-header">
    <h1>博客</h1>
</div>

<ul class="posts">
    {% for post in site.categories.blog %}
    <li><span>{{ post.date | date: "%Y-%m-%d" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

<div class="tiles">
{% for post in site.categories.sample %}
  {% include post-grid.html %}
{% endfor %}