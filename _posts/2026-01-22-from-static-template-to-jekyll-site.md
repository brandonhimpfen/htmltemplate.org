---
layout: post
title: From Static Template to Jekyll Site
description: Turning a static template into a Jekyll site keeps the simplicity of HTML while adding reusable layouts, includes, posts, and publishing structure.
author: Brandon Himpfen
---

A static HTML template is useful because everything is explicit. A Jekyll site is useful because repeated structure can be managed once.

The conversion from one to the other should preserve the design and layout while introducing maintainability. Navigation, metadata, footers, scripts, and page shells can move into includes and layouts. Content pages can stay simple.

## What changes

The main change is organization. Instead of repeating the same HTML across every page, Jekyll lets the site define shared structure in one place. Blog posts live in `_posts`, layouts live in `_layouts`, and reusable fragments live in `_includes`.

The result is still a static site. It can be hosted on GitHub Pages, Cloudflare Pages, Netlify, or any static hosting provider.

## What should stay the same

The visual identity should not change just because the build system changes. The same CSS, spacing, color treatment, cards, navbar, hero section, and footer can remain intact.

A good conversion adds publishing capability without making the original site feel like a different product.

