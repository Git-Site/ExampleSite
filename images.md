---
title: Images
date: 2025-01-03
description: How to embed images in your GitSite pages
---

# Images

You can embed images using standard Markdown image syntax.

## Images from Your Repo

Place image files anywhere in your repository and reference them by relative path:

```markdown
![A description of the image](images/my-photo.jpg)
```

The path is relative to the current file. From a file in the root, `images/photo.jpg` refers to an `images` folder at the root of your repo.

## External Images

Link to any publicly accessible image URL:

```markdown
![GitHub logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

![GitHub logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

## Adding Alt Text

Always include descriptive alt text between the square brackets. This improves accessibility and is shown when an image fails to load.

## Images as Links

Wrap an image in a link to make it clickable:

```markdown
[![GitHub logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)](https://github.com)
```
