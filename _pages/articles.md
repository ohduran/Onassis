---
layout: section
title: articles
permalink: /articles
---
{% include sections/last_post.html last_post=site.articles.last%}
{% include sections/items_except_last.html items=site.articles%}
