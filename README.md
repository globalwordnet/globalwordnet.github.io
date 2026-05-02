# Global WordNet Association Website

This site hosts the website for the Global WordNet Association. The site is built using Jekyll and hosted on GitHub Pages.

## Creating a new page

To create a new page, create a new markdown file in the root directory. The file should have the following front matter:

```
---
layout: default
---

# Page Title
```

## Editing the navigation

The navigation is defined in `_data/toc.yaml`. To add a new item to the navigation, add a new item to the list. The `title` is the text that will be displayed in the navigation, and the `url` is the path to the page.

## Creating a new post

To create a new post, create a new markdown file in the `_posts` directory. The file should have the following name format:

```
YYYY-MM-DD-title.md
```

The file should have the following front matter:

```
---
layout: post
author: Author
title: "Title"
---

```

Do not include a level 1 heading in the post, as the title will be displayed automatically.

## Running locally

To run the site locally, you will need to have Ruby installed. You can install the dependencies by running:

```
bundle install
```

You can then run the site locally by running:

```
bundle exec jekyll serve
```

## Checking for broken links and HTML errors

After building the site, run [HTMLProofer](https://github.com/gjtorikian/html-proofer) to validate internal links, images, and HTML:

```
bundle exec jekyll build && bundle exec htmlproofer ./_site --disable-external --no-enforce-https
```

Add `--swap-urls "^/globalwordnet.github.io/:/"` if the site is built with a non-root `baseurl`.

