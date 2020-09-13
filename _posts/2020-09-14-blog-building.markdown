---
layout: post
title:  "How to Build a Blog"
date:   2020-09-14 21:23:18 +0800
categories:
  - Blog
  - GitHub Pages
  - Jekyll
---

# Tools:
Blog -> GitHub Pages -> Jekyll (GitHub Pages' default) -> Minima (Jekyll's Default)

# Steps:
1. Create a repository on GitHub with name `<username>.github.io`
2. Clone the repository to your local, `git clone git@github.com:<username>/<username>.github.io.git`
3. Install `Ruby` and `Jekyll`
4. Create a Jekyll project, `jekyll new .`
5. Update config and `bundle exec jekyll serve`
6. `git push`

# Config
Gemfile
I use github-pages which import the jekyll
```
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
```
_config.yml
Delete `about.md`
