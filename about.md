---
layout:default
Title: "about this website in the YAML HEADER"
author: "gfan23"
---

[Go Home](index.md)

## Project
This research project is all about teaching you how to create websites with GitHub pages.

## Funders
We gratefully acknowledge funding from the XYZ Founding Council, under grant number 'abc'.

## Cite us
You can cite the project as:

> *The Carpentries 2019 Annual Report. Zenodo. https://doi.org/10.5281/zenodo.3840372*

# about loops
{% for there in a list %}
[        ]

{% endfor %}

## Blog Posts
{% for post in site.blog %}
- {{post.date | date_to_string}}: [{{post.title}}]({{post.url | relative_url }})
