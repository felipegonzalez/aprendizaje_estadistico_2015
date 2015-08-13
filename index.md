---
layout: default
---

{% include about.md %}

- - -

## Clases, material y avisos

Todo el código está en el [repositorio del curso](https://github.com/felipegonzalez/aprendizaje_estadistico_2015).


<ul class="post-list">
    {% for post in site.posts limit:3 %}
      <li>  <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }} ~</span> 
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}"> {{ post.title }}</a>
	{{ post.excerpt }}
      </li>
    {% endfor %}
</ul>


