[Startseite](https://gh.pfeiffer.space/) - [News](https://gh.pfeiffer.space/news.html) 

## Newsfeed 

### Derzeit keine Neuigkeiten 

---

Alle:
<ul>
 {% for post in site.posts %}
 <li>
  <a href="{{ post.url }}">{{ post.title }}</a>
 </li>
{% endfor %}
</ul>

---

Test:
<h1>{{ page.title }}</h1> <ul class="posts"> {% for post in site.categories.de %} <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li> {% endfor %} </ul>
