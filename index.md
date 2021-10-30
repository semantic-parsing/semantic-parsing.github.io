---
layout: default
title: A Survey of Modeling and Data resources for Semantic Parsing
---
### Semantic Parsing

Semantic Parsing is the task of converting natural language texts into formal machine-understandable logical-form representations. This website surveys the work in this area.

#### 🏷 Browse Papers by Tag
{% assign rawtags = Array.new %}
{% for publication in site.publications %}
  {% assign ttags = publication.tags  %}  
  {% assign rawtags = rawtags | concat: ttags %}  
{% endfor %}
{% assign rawtags = rawtags | uniq | sort %}
{% for tag in rawtags %}<tag><a href="/tags.html#{{ tag }}">{{ tag }}</a></tag> {% endfor %}

### About This Site

This site is an experiment: a [living literature review](https://en.wikipedia.org/wiki/Living_review) that allows
you explore, [search and navigate]({% link papers.html %}) the literature in this area, by
following a [taxonomy]({% link base-taxonomy/index.md %})
based on the underlying design principles of each model.

### Contributing

This research area is evolving so fast that a static review cannot keep up.
But a website can! We hope to make this site a living document.
Anyone can add a paper to this web site, essentially by creating one Markdown file.
 To contribute, open a pull request in GitHub, by following [these instructions 
for contributing](contributing.html).

### Contributors

The core survey and the original taxonomy was created by

* [Rajaswa Patil](https://rajaswa.github.io/) TCS Research, India

#### Contributors to the website
This website accepts external [contributions](/contributing.html).
Please, feel free to add your name below, once you contribute to this
website. A comprehensive list can be found [here](https://github.com/semantic-parsing/semantic-parsing.github.io/graphs/contributors).

The structure of this survey has been borrowed from the [ml4code initiative](https://ml4code.github.io/).