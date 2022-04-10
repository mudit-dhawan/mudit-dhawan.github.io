---
layout: archive
entries_layout: tag
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if sites.author.googlescholar %}
  You can also find my articles on <u><a href="{{sites.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Conference Publications

{% include base_path %} {% for post in site.publications %} {% if post.tag == 'conference' %} {% include archive-single.html %} * * * {% endif %} {% endfor %}


## Pre-Prints/ Under-Review

{% include base_path %} {% for post in site.publications %} {% if post.tag == 'preprint' %} {% include archive-single.html %} * * * {% endif %} {% endfor %}

## Thesis

{% include base_path %} {% for post in site.publications %} {% if post.tag == 'thesis' %} {% include archive-single.html %} * * * {% endif %} {% endfor %}