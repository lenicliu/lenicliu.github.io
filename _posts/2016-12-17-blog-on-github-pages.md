# Blog on GitHub Pages

## Setup

* Create `USERNAME.github.io` repository

* Create `README.md` or `index.md`

```
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}
```

* Create `_config.yml`

```
title: YOUR BLOG NAME
theme: jekyll-theme-hacker
highlighter: rouge
```

* The first post `/_post/YYYY-MM-DD-FILENAME.md`

```
# Hey, Github Pages
* I'm here.
```
