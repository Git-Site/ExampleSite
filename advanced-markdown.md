---
title: Advanced Markdown
date: 2025-01-02
description: Tables, footnotes, task lists, definition lists, and GitHub-style alerts
---

# Advanced Markdown

GitSite uses [Markdig](https://github.com/xoofx/markdig) with advanced extensions enabled, giving you a rich set of formatting options beyond standard Markdown.

## Tables

| Feature       | Supported | Notes                        |
|---------------|-----------|------------------------------|
| Tables        | Yes       | With alignment               |
| Footnotes     | Yes       |                              |
| Task lists    | Yes       |                              |
| Alerts        | Yes       | GitHub-style                 |
| Strikethrough | Yes       | `~~text~~`                   |

Column alignment with `:`:

| Left | Center | Right |
|:-----|:------:|------:|
| A    |   B    |     C |
| 1    |   2    |     3 |

## Footnotes

GitSite supports footnotes[^1]. You can have multiple[^2].

[^1]: This is the first footnote, rendered at the bottom of the page.
[^2]: And here is the second.

## Task Lists

- [x] Create `site.yaml`
- [x] Write the index page
- [ ] Add more example pages
- [ ] Push to GitHub

## Definition Lists

GitSite
: A static site generator driven by a GitHub repository.

Front matter
: A YAML block at the top of a Markdown file used to set metadata like title and date.

Markdig
: The Markdown parser used by GitSite, with support for many extensions.

## Alerts

> [!NOTE]
> This is a note. Use it for supplementary information.

> [!TIP]
> This is a tip. Use it to suggest a better approach.

> [!WARNING]
> This is a warning. Use it to flag something the reader should be careful about.

> [!IMPORTANT]
> This is an important callout.

> [!CAUTION]
> This is a caution, for things that could cause harm or data loss.
