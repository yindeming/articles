---
Time-stamp: <02-12-2015 21:18>
layout: article
title: "How to use Jekyll not as a blog"
permalink: /how-to-use-jekyll-not-as-a-blog-on-windows/
---

### This is NOT a blog

So I don't have much to post, but I want to keep updating my (few) articles. I have found people with the same though in mind:
- https://github.com/jekyll/jekyll/issues/1650
- http://stackoverflow.com/questions/30837079/using-jekyll-for-website-without-blog

As for generate a list of pages(not posts):
- http://stackoverflow.com/questions/17118551/generating-a-list-of-pages-not-posts-in-a-given-category

### How to set it up on windows

Since I use windows, I need a way of manage articles easily. And I don't like the tedious commands everytime I change something.

I use:
- https://desktop.github.com/
- [Portable Jekyll](https://github.com/madhur/PortableJekyll)
  Run `setpath.cmd`
  Run `jekyll new myblog` and `jekyll serve` and check at http://localhost:4000

To write articles, I can use any editor of my choice, I can also do it on GitHub website.

The rules are simple:
https://help.github.com/articles/markdown-basics/

### Use the subdomain

As I prefer a shorter link for my articles:
http://articles.deming.im/how-to-use-jekyll-not-as-a-blog-on-windows/
other than
http://yin.deming.im/how-to-use-jekyll-not-as-a-blog-on-windows/

This is archived through:
http://stackoverflow.com/questions/10685961/multiple-github-pages-and-custom-domains-via-dns#

### Use a preferred style

I like the plain and simple BootStrap theme, so I changed in _layout/default.html and it looks good so far.

### TODO: Make a list of articles:

- http://stackoverflow.com/questions/17118551/generating-a-list-of-pages-not-posts-in-a-given-category
