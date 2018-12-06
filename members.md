---
layout: page
title: Members
permalink: /members/
---
This list includes the current members of the Society for Arab Music Research. If you would like to add your name and contact information, please email [Christopher Witulski][email].

Click on the names to reveal further information on members' interests, contact information, and a selection of their publications.

{% for member in site.members %}
{% include member.html member=member %}
{% endfor %}

[email]: mailto:cwituls@bgsu.edu
