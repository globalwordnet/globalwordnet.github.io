# Contributing

Thanks for your interest in improving the Global WordNet Association website!  
This repository contains the Jekyll source for <https://globalwordnet.github.io>.

* TOC
{:toc}


## How to update the **Wordnets in the World** page

The page at https://globalwordnet.github.io/resources/wordnets-in-the-world

is generated from a YAML data file loaded as `https://github.com/globalwordnet/globalwordnet.github.io/tree/main/_data/wordnets.yaml`. Each entry in that file corresponds to **one wordnet (or family of wordnets)** and is rendered into a row of the big table you see on the webpage. 

The template loops over each `wordnet` object and expects the following keys:

- `title` — list of `[name, url]` pairs for the resource name(s).
- `language` — list of human-readable language names (e.g. `["English", "Spanish"]`).
- `online` — list of `[label, url]` pairs describing online availability.
- `developer` — list of `[name, url]` pairs for institutions / developers.
- `contact` — list of `[name, url]` pairs for people.
- `license` — list of `[label, url]` pairs for licenses.
- `other` — list of `[label, url]` pairs for other relevant links/info (such as a download link).

All of the “link-like” fields (`title`, `online`, `developer`, `contact`, `license`, `other`) are lists of **two-element lists**:

```yaml
- - Visible label
  - URL or ''
```

If there is **no URL**, use the empty string `''`. The template checks `name[1] != ''` before turning the label into a link.

### Example entry: Multilingual Central Repository

Here is an example entry corresponding to the “Multilingual Central Repository” row on the site:

```yaml
- contact:
  - - Eneko Agirre Arantza Díaz-Ilarraza German Rigau
    - ''
  developer:
  - - University of the Basque Country
    - http://www.ehu.es/p200-shenhm/en
  - - Department of Software, Technical University of Catalonia (UPC)
    - http://www.lsi.upc.edu/?set_language=en
  language:
  - English
  - Spanish
  - Catalan
  - Basque
  - Italian
  license:
  - - CC By 3.0
    - http://creativecommons.org/licenses/by/3.0/
  - - CC-BY-NC-SA
    - http://creativecommons.org/licenses/by-nc-sa/3.0/
  online:
  - - 'YES'
    - http://ixa2.si.ehu.es/cgi-bin/mcr/public/wei.consult.perl
  other:
  - - Web EuroWordnet Interface 0.2 (by LSI-UPC)
    - http://ixa2.si.ehu.es/cgi-bin/mcr/public/wei.consult.perl
  title:
  - - Multilingual Central Repository
    - http://adimen.si.ehu.es/web/MCR
```

Notes:

* **Language names** are plain text; the template treats resources with more than 5 languages as “Multilingual”.
* If a given field does not apply (e.g. no `other` links), you can either:
  * omit the key entirely, or
  * give it an empty list (`other: []`).

---

## How to add a corpus entry

If you are maintaining one of the listed corpora and want to correct or update its information:

1. Find the existing row in `resources/wordnet-annotated-corpora.md`.
2. Update only the fields that need changing:

   * revised word counts or taggable/tagged counts;
   * updated developer or contact information;
   * changed license;
   * new URLs for download or browsing.
3. If you are adding or updating a **reference**, adjust the corresponding citation in the **Citations** section.

---

## How to add some news

The **News** page at [https://globalwordnet.github.io/news](https://globalwordnet.github.io/news) is generated from standard Jekyll blog posts in the `_posts` directory. ([globalwordnet.github.io][2])

To add a news item (call for papers, proceedings announcement, board update, etc.):

### 1. Create a new post file

All posts live in `_posts/` and follow the standard Jekyll naming convention:

```text
_posts/YYYY-MM-DD-short-title.md
```

For example:

```text
_posts/2025-11-14-proceedings-gwc2025-acl-anthology.md
```

### 2. Add the front matter

Each post must begin with YAML front matter as described in the repository README: ([GitHub][3])

```yaml
---
layout: post
author: Francis Bond
title: "Proceedings of GWC 2025 are now available in the ACL anthology"
---
```

Guidelines:

* `layout` should be `post`.
* `author` should be the name you want shown under the title.
* `title` is the full human-readable headline. Do **not** repeat it as a `#`-heading in the body; the layout already shows it.

The **date** is taken from the filename (`YYYY-MM-DD-...`), so there is normally **no need** to specify a `date:` field unless you have a special case.

### 3. Write the body of the post

After the front matter, add the post content in Markdown:

```markdown
We are pleased to announce that the Proceedings of GWC 2025 are now
available in the ACL anthology:

https://aclanthology.org/volumes/2025.gwc-1/

Additional details, acknowledgements, deadlines, or links can go here.
```

Tips:

* Use plain Markdown (paragraphs, lists, links).
* For external resources (e.g. EasyChair CFPs, ACL Anthology, conference websites), include clear URLs.
* Keep one post focused on one main announcement (e.g. "Call for Papers GWC2027", "Proceedings GWC2025 online").

---

## General guide to submitting a pull request

1. Make an issue

2. **Fork and clone** this repository.

3. **Make your change**

4. **Check it builds**

   Before opening a pull request, please ensure the site builds:

   ```bash
   bundle install          # first time only
   bundle exec jekyll build
   ```

   If the build completes without errors, then the page should render.

5. **Open a Pull Request**

   * Use a clear title, e.g.:

     * `Add UzWordnet entry to Wordnets in the World`
     * `Update Multilingual Central Repository URLs`
   * In the description, please include:

     * A short summary of the change.
     * For **new wordnets**:

       * Languages covered.
       * License(s).
       * Whether it’s linked to the Open Multilingual Wordnet or other resources.
       * Any special notes (e.g. “Browse only”, “Academic use only”).



## Code of Conduct

This project is part of the Global WordNet Association community.
We expect all contributors to follow standard norms of respectful, inclusive, and professional behaviour.

If you have questions about how to contribute, feel free to open an issue or start a discussion on the Global WordNet GitHub organisation.






