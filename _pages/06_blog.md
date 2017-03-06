---
layout: page
icon: rss
title: Blog
permalink: /blog/
---

{% for post in site.posts %}
<div class="row">
<div class="two columns">
<p class="post-meta"><span><time>{{ post.date | date: "%-d %b" }}</time></span></p>
</div>
<div class="ten columns">
<h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
{{ post.excerpt }}
</div>
</div>
---
{% endfor %}

<p>subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
