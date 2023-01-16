---
title: "Portfolio"
layout: archive
permalink: /categories/portfolio/
author_profile: true
sidebar_main: true
sidebar:
    nav: true
---

{% assign posts = site.categories.portfolio %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}