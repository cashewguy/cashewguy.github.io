---
layout: default
title: "Post Index"
---

<h2>Published Posts</h2>

<ul>
	{% for post in site.posts %}
	<li>
		<a href="{{ post.url }}">{{ post.title}} | {{ post.date }}</a> 
	</li>
	{% endfor %}
</ul>

<h2>Published Pages</h2>
<ul>
	{% for page in site.pages %}
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
	{% endfor %}
</ul>