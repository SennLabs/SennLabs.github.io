---
date: 2025-01-13
title: Building The Blog
slug: BuildingTheBlog
comments: true
categories:
  - blog
tags:
  - Automation
  - mkdocs
  - blog
hide: [toc, tags]
publish: true
---


## Why Make a Blog
After debating setting up a blog for months. I finally decided to set it up.
As I have been watching the loss of info with the fall of forums, and many online communities claiming discord/facebook works as a replacement (it doesn't), I decided to have a place to log my projects and learning.

<!-- more -->


## What did I use for this blog?
I had some simple requirements for my blog:
- Simple UI and presentation
- Static Site with a simple generator
- Basic Hosting
- Automated Publishing following commits
- Comments for each post
- Markdown for Posts

GitHub's Pages and Actions make hosting and automation easy.
I looked at Jekyll and Hugo, but decided on MkDocs, this is to also give me a single platform for future code documentation.
Along with mkdocs-material and using Giscus to handle comments, all my requirements are met. The docs provided by mkdocs-material made the initial set up simple and fast.
