---
title: Basic Syntax
date: 2025-01-01
description: Headings, paragraphs, lists, links, inline formatting, and code blocks
---

# Basic Syntax

The building blocks of any GitSite page.

## Headings

Use `#` through `######` for six levels of headings.

## Paragraphs

Separate paragraphs with a blank line. A single line break
within a block is treated as a space, not a new paragraph.

## Inline Formatting

You can make text **bold**, *italic*, or ***bold and italic***.
`Inline code` uses backticks.
~~Strikethrough~~ uses double tildes.

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

## Links

Link to an external page: [GitHub](https://github.com)

Link to another page in this site: [Advanced Markdown](advanced-markdown.md)

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

## Blockquotes

> This is a blockquote. It can span multiple lines and is useful for
> calling out a passage or quotation.

## Horizontal Rule

---
