---
layout: default
---

{% for cats in site.my_categories %}


<a href="{{ cats.url | prepend: site.baseurl }}">
{{ cats.name }}
</a>
<h4>{{cats.slug}}</h4>
<h4>{{cats.color}}</h4>
<hr>
<br />
{% endfor %}     
