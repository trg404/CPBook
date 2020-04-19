---
title: Books/Index
layout: page.html
___

# Books

- [agile](/agile)
  - Agile practices and what each ceremony artifact and role means
- [communication](/communication)
  - how to talk to people or convey information
- [art](/art)
  - art history and things I wanna try
- [books to read](/toRead)
  - books that have been recomended or I've come accross to read later




# Index

{% for post in collections.all -%}
* [{{ post.data.title }}]({{post.url}})
{% endfor -%}
