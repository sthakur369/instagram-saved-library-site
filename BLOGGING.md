# Adding a blog post

The website uses Jekyll, so you do **not** need to create an HTML page for every article.

## Add a new article

Create one Markdown file inside `_posts/`:

```text
_posts/YYYY-MM-DD-your-article-title.md
```

Example:

```text
_posts/2026-09-01-how-to-save-instagram-posts.md
```

At the top of the file, add:

```yaml
---
layout: post
title: "How to Save Instagram Posts Before Deleting Instagram"
description: "A simple guide to exporting and keeping your Instagram saved posts before deleting your account."
categories: [Instagram]
tags: [instagram, saved-posts, data-export]
author: Shubham Thakur
---
```

Then write normal Markdown below it:

```markdown
## Your first heading

Write your article here.

You can use **bold**, links, images, lists, code and normal Markdown.
```

Commit/push the file to GitHub.

That's it.

Jekyll will automatically:

- publish the article
- create its article URL
- add it to the homepage's **From the blog** section
- add it to `/blog/`
- make it searchable on the blog page
- make category and tag filters available
- include it in the generated sitemap
- expose it through the RSS feed

You do **not** need to edit `index.html`, `blog/index.html`, the sitemap, or the blog navigation when adding a new article.

## Important

The filename must start with the publication date:

```text
YYYY-MM-DD-your-slug.md
```

Use a clear, search-friendly title and write for the person who has the problem you are solving. Don't stuff keywords into the article.
