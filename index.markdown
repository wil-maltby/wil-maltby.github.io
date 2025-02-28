---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Welcome to Wil Maltby's Site

Hey all, this is where I share things I'm building and some excerpts from books I'm reading.

## Projects

[Your projects will go here]

## Recent Posts

{% for post in site.posts limit:5 %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}

## Contact

Find me on [GitHub](https://github.com/wil-maltby)
