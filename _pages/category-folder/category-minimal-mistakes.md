---
title: "minimal-mistakes"
layout: archive
permalink: /categories/minimal-mistakes/
author_profile: true
sidebar_main: true
sidebar:
    nav: true
---

{% assign posts = site.categoreis.minimal-mistakes %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}