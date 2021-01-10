[Startseite](https://gh.pfeiffer.space/) - [News](https://gh.pfeiffer.space/news.html) 

## Newsfeed 

### Derzeit keine Neuigkeiten 

---

Test1:
<ul>
 {% for post in site.posts %}
 <li>
  <a href="{{ post.url }}">{{ post.title }}</a>
 </li>
{% endfor %}
</ul>

---

Test2:
<h1>{{ page.tag }}</h1> <ul> {% for post in site.tags[page.tag] %} <li> {{ post.date | date: "%B %d, %Y" }}: <a href="{{ post.url }}">{{ post.title }}</a> </li> {% endfor %} </ul>
