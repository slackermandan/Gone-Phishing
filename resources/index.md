---
layout: single
title: "Educational Materials"
permalink: /resources/
author_profile: false
---

Guides, checklists, and reference material you can read on your own or share with someone else. Unlike the blog, this section is meant to be a lasting reference library rather than a chronological feed.

<ul>
{% assign sorted_resources = site.resources | sort: "title" %}
{% for resource in sorted_resources %}
  <li>
    <a href="{{ resource.url | relative_url }}">{{ resource.title }}</a>
    {% if resource.excerpt %} — {{ resource.excerpt | strip_html }}{% endif %}
  </li>
{% endfor %}
</ul>

*More guides — including downloadable PDFs and interactive quizzes — are on the way.*
