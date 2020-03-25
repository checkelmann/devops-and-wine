# DevOps and Wine Website

## Installation

``` bash
git clone git@github.com:checkelmann/devops-and-wine.git
cd devops-and-wine/devops-and-wine/
hugo server --themesDir ../..
```

## Adding new blog post

Just copy the existing one under `devops-and-wine/content/meeting-1.md` to `devops-and-wine/content/meeting-X.md` where X should be an incremental number, and add your content.

Keep the category (Meetings), adjust the title, author, date and description. If you want to add an image to your post, add it to the `devops-and-wine/static/images` folder like the post-1.jpg file.

``` markdown
+++
title = "Meeting #1 - 19. March 2020"
image = "/images/post/post-1.jpg"
author = "Christian Heckelmann"
date = 2019-11-07T05:00:00Z
description = "Past meetings"
categories = ["Meetings"]
type = "post"

+++
Some text about the meeting and what was discussed.
```
