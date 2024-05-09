---
layout: default
title: Home Page
---

# Welcome to My Jekyll Site

Welcome to my personal blog. Here you will find my thoughts, projects, and more.

## Recent Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | absolute_url }})
  {% endfor %}

## About Me

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur vel neque non libero suscipit suscipit eu eu urna.

## Contact

Feel free to [contact me](mailto:email@example.com) or follow me on [GitHub](https://github.com/).
