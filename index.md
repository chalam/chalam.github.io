---
layout: page
title: Hello World!
tagline: Welcome to the Age of Data
---
{% include JB/setup %}

## About Me

I'm a software engineer with years of experience in solving interesting problems in trading, risk and regulatory areas of financial services, arguably the original big data space. I'm passionate about planning, design, implementation and delivery of large-scale, mission critical systems by applying data-centric computing architecture with distributed system.

## Musings

Here's a sample posts list.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


