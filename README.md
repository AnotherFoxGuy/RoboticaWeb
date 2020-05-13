## Welkom bij RoboticaWeb!

### Alle blogposts
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
