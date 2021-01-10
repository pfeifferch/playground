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
<h1>{{ page.title }}</h1>
<div class="tags">
 {% assign sortedCategories = page.categories | sort %}
 {% for category in sortedCategories %} 
<span class="tag">
 <a href="/category/{{ category }}">#{{ category }}</a>
</span> 
{% endfor %}
</div>


---

Test3:
 -
