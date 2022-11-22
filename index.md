---
layout: default
---

# Blogs
{% for post in site.posts %}
 
<ul>
 
<li><h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3></li>
 
</ul>
{% endfor %}

Not exactly sure what I'm doing, but I've gotten this far. 
Welcome to my website.

You can find my blogs [here](./blog/)




