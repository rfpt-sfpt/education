---
title: "How to write a blog article"
description: "A tutorial on notebook OR markdown OR Word doc article writing"
layout: post
toc: false
comments: true
hide: false
search_exclude: true
categories: [fastpages, markdown]
---

There are a number of ways to write an blog article. Here, we will present how to upload an article using the github web-interface. If you're more familiar with github, you may as well clone the repository locally, modify it as it fits, and push to the master branch via a pull request.

# File formats
An article can be submitted as a jupyter notebook (`*.ipynb`), a markdown file (`*.md`) or a Word file (`*.docx`). Whatever the input file, a strict naming convention must be followed and it goes like this:
- `YYYY-MM-DD-*.ipynb` for notebooks
- `YYYY-MM-DD-*.md` for markdown files 
- `YYYY-MM-DD-*.docx`for Word docs

The `YYYY`, `MM` and `DD` correspond to the year, month and day of the publication (remeber to separate them by a hyphen). The `*` symbol should be replaced with an arbitrary title.

# Location in the `github` folder structure

Depnding on the file format of your article, you should place it in their corresponding folders. If you've written 
- a notebook article, place it inside the `_notebooks` folder, 
- a markdown article, place it inside the `_posts` folder, and
- a Word doc article, place it inside the `_word` folder.

In the following figure, the folders are marked with reg, green and blue rectangles, respectively:

![](images/github-folder-structure-marked.png) 

to be continued

- [Writing Blogs With Jupyter](https://github.com/fastai/fastpages#writing-blog-posts-with-jupyter)

- [Writing Blogs With Markdown](https://github.com/fastai/fastpages#writing-blog-posts-with-markdown)

- [Writing Blog Posts With Word](https://github.com/fastai/fastpages#writing-blog-posts-with-microsoft-word)

- [(Optional) Preview Your Blog Locally](_fastpages_docs/DEVELOPMENT.md)
