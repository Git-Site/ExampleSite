---
title: Features
date: 2025-01-02
description: What you can do with GitSite — site config, front matter, post lists, and more
---

# Features

This page describes the various ways you can use markdown to control how GitSite shows your pages.

---

## File Structure

Any `.md` or `.markdown` file in your repo becomes a page. The URL maps directly from the file path:

| File | URL |
|------|-----|
| `readme.md` | `/` (index) |
| `about.md` | `/about` |
| `posts/hello.md` | `/posts/hello` |
| `posts/readme.md` | `/posts` (index) |

If there is no `readme.md` at the root, a default page is generated that shows a post list.

---

## site.yaml

Place a `site.yaml` or `site.yml` in the root of your repo to set site-wide metadata:

```yaml
title: My Site
description: A short description for SEO
```

This file is not turned into a page.

---

## Front Matter

Any page can have a YAML front matter block at the top:

```yaml
---
title: My Custom Title
description: Overrides the SEO description for this page
date: 2024-03-15
---
```

- `title` — overrides the page title (defaults to the first H1, or the site title)
- `description` — overrides the meta description (defaults to the first paragraph, truncated to 160 chars)
- `date` — sets the post date, shown below the H1 as `March 15, 2024` and used to sort post lists

---

## :::PostList

Place this anywhere in a page to generate a chronological list of all non-index pages, newest first:

```
:::PostList
:::
```

---

## Internal Links

Link to other pages using the `.md` filename as you would on GitHub — the extension is stripped automatically on the live site:

```markdown
[About](about.md)
[My post](posts/hello.md)
```
