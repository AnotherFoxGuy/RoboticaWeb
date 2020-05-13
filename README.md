## Welkom bij RoboticaWeb!

### Alle blogposts

  {% for post in site.posts %}
  <article>
    <h4>
      <a href="{{ post.url | prepend: site.baseurl }}">
        {{ post.title }}
      </a>
    </h4>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    {{ post.content }}
  </article>
{% endfor %}
