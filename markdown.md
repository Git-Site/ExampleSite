---
title: Markdown Examples
date: 2025-01-01
description: Headings, paragraphs, lists, links, code blocks, tables, footnotes, task lists, alerts, and more
---

[View this page on GitHub](https://github.com/Git-Site/ExampleSite/blob/main/markdown.md)

<br>

# Use H1 for post titles
This is text below a heading 1.
## Heading 2
This is text below a heading 2.
### Heading 3
This is text below a heading 3.
#### Heading 4
This is text below a heading 4.
##### Heading 5
This is text below a heading 5.
###### Heading 6
This is text below a heading 6.

---

## Paragraphs

Separate paragraphs with a blank line. A single line break
within a block is treated as a space, not a new paragraph.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---

## Inline Formatting

You can make text **bold**, *italic*, or ***bold and italic***.
`Inline code` uses backticks.
~~Strikethrough~~ uses double tildes.

---

## Lists

Unordered list:

- Apples
- Oranges
- Bananas
  - A nested item

Ordered list:

1. First step
2. Second step
3. Third step

---

## Links

Link to an external page: [GitHub](https://github.com)

Link to another page in this site: [Images](images.md)

---

## Code Blocks

Fenced code blocks support syntax highlighting:

```csharp
public string Greet(string name)
{
    return $"Hello, {name}!";
}
```

```javascript
function greet(name) {
    return `Hello, ${name}!`;
}
```

```bash
echo "Hello, world!"
```

---

## Blockquotes

> This is a blockquote. It can span multiple lines and is useful for
> calling out a passage or quotation.

---

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

---

## Footnotes

GitSite supports footnotes[^1]. You can have multiple[^2].

[^1]: This is the first footnote, rendered at the bottom of the page.
[^2]: And here is the second.

---

## Task Lists

- [x] Create `site.yaml`
- [x] Write the index page
- [ ] Add more example pages
- [ ] Push to GitHub

---

## Images

Embed images using standard Markdown syntax:

```markdown
![A description of the image](images/my-photo.jpg)
```

Or link to any public URL:

![A small placeholder image](https://placehold.co/120x80)

Wrap an image in a link to make it clickable:

```markdown
[![Alt text](image.jpg)](https://example.com)
```

---

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
