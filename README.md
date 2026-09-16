# cachemix.com

Personal site and blog, served by GitHub Pages at
[cachemix.com](https://cachemix.com).

Built on [Millennial](https://github.com/LeNPaul/Millennial) (MIT).

## Adding a post

Create `_posts/YYYY-MM-DD-slug.md` with front matter:

```yaml
---
layout: post
title: "Title"
author: "Jim Liming"
categories: notes
tags: [tag]
---
```

Push to `main` and GitHub Pages rebuilds automatically.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```
