# HTML Template Jekyll Site

This is the Jekyll version of the HTML Template website. It preserves the original Bootstrap-based design and adds a blog powered by Jekyll posts.

## Local setup

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Structure

- `_layouts/` contains the default page and blog post layouts.
- `_includes/` contains the shared head, navigation, footer, and scripts.
- `_posts/` contains blog posts.
- `blog/index.html` lists all posts.
- `assets/` contains the original CSS, JavaScript, and images.

## Adding a post

Create a Markdown file in `_posts/` using this format:

```markdown
---
layout: post
title: Your Post Title
description: A short description for search and social previews.
author: HTML Template
---

Your post content here.
```

Use the filename format `YYYY-MM-DD-post-title.md`.
