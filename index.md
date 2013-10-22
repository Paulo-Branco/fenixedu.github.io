---
layout: default
title: FenixEdu™ for Developers
base_url: "./"
---

### Recent Posts in FenixEdu Developer Blog
{% for post in site.posts %}
<div style="width: 100%; float: left; display: block; margin-bottom: 10px">
	<div style="float: left; margin-right: 10px; display: inline; text-align: center; color: #AAA; padding: 2px 5px; border-radius: 4px; background-color: #EEE; font-size: 13px">{{post.date | date: "%b"}}<br/><span style="color: black">{{post.date | date: "%d"}}</span></div>
	<a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}