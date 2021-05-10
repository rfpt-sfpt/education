---
title: "How to write a blog article"
description: "A tutorial on notebook, markdown, Word doc article writing"
image: images/diagram.png
layout: post
toc: true
comments: true
hide: false
search_exclude: true
categories: [education, article writing, markdown, jupyter, docx]
---


# Introduction
There are a number of ways to write an blog article. Here, we will present how to upload an article using the github web-interface. If you're more familiar with github, you may as well clone the repository locally, modify it as it fits, and push to the master branch via a pull request.

## File formats
An article can be submitted as a jupyter notebook, a markdown file or a Word file. Whatever the input file, a strict naming convention must be followed and it goes like this:
- `YYYY-MM-DD-*.ipynb` for notebooks
- `YYYY-MM-DD-*.md` for markdown files 
- `YYYY-MM-DD-*.docx`for Word docs

The `YYYY`, `MM` and `DD` correspond to the year, month and day of the publication (remeber to separate them by a hyphen). The `*` symbol should be replaced with an arbitrary title.

## Location in the `github` folder structure

Depnding on the file format of your article, you should place it in their corresponding folders. If you've written 
- a notebook article, place it inside the `_notebooks` folder, 
- a markdown article, place it inside the `_posts` folder, and
- a Word doc article, place it inside the `_word` folder.

In the following figure, the folders are marked with reg, green and blue rectangles, respectively:

![](images/github-folder-structure-marked.png) 

# Markdown article

1. Upload an existing file or create a new one
2. Include `front matter` to describe the metadata of the article 
   * Title, description, tags;
   * Please include an image, and do not forget to upload the file inside the `images` directory. The image will be displayed on the main page, next to your article
4. Write the content of your article using the [markdown language](https://guides.github.com/features/mastering-markdown/) 
5. Submit the article with the `Commit changes` button 

The above instructions are summarised in the figure below:

![](images/tutorial_write_blog.png)

# Other references

- [Writing Blogs With Jupyter](https://github.com/fastai/fastpages#writing-blog-posts-with-jupyter)

- [Writing Blogs With Markdown](https://github.com/fastai/fastpages#writing-blog-posts-with-markdown) 

- [Writing Blog Posts With Word](https://github.com/fastai/fastpages#writing-blog-posts-with-microsoft-word)

- [(Optional) Preview Your Blog Locally](_fastpages_docs/DEVELOPMENT.md)
