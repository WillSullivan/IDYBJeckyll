---
layout: downvote
iDownvotedYouBecause: ...one of these many reasons
title: I downvoted you on StackOverflow because
---
{% for post in site.categories.so %}
[{{ post.title }}]({{ post.url }}) {{ post.description }}
{% endfor %}
