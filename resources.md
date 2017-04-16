---
layout: page
title: Resources
permalink: /resources/
---

One of our goals is to provide collaborative bibliographies for important topics related to the study of Arab music. These are not exhaustive, but may provide starting points for research or reading. If you would like to add any resources or suggest a bibliography, please email [Christopher Witulski][email].

{% for bib in site.resources %}
{% include resource.html bib=bib %}
{% endfor %}

[email]: mailto:cwituls@bgsu.edu
