---
layout: page
title: Credits
heading: Site Credits
subheading: Awesome stuff used on this site!
permalink: /credits/
---

{% if jekyll.environment != "production" %}
> **Non Production Environment**  
> Environment: {{ jekyll.environment }}
{% endif %}

## Engine

- [Jekyll](http://jekyllrb.com/) - "A simple, blog-aware, static site generator"
- Hosted on GitHub [wnowicki/hospoda](https://github.com/wnowicki/hospoda)

## Assets

- **Template:** [Clean Blog](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) - "is a stylish, responsive blog theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/)."
- [CSS Flag Sprites generator](https://www.flag-sprites.com/ "Country flags in single CSS sprite")
- [ISO 3166-1](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)

```plain
Build: {% project_version commit long %}
Site generated: {{ site.time | date: "%H:%M %d.%m.%Y %Z"}}
```

Version [{% project_version commit short %}](https://github.com/wnowicki/hospoda/commit/{% project_version commit long %})
