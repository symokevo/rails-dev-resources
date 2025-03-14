Here’s a complete **Markdown Syntax Guide** with examples for all commonly used Markdown features. Markdown is a lightweight markup language used for formatting plain text. It’s widely used for documentation, README files, and more.

---

# Markdown Syntax Guide

## 1. Headings
Use `#` to create headings. The number of `#` indicates the heading level.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

---

## 2. Paragraphs and Line Breaks
- Paragraphs are separated by a blank line.
- Use two spaces at the end of a line to create a line break.

```markdown
This is a paragraph.

This is another paragraph.  
This is a new line in the same paragraph.
```

---

## 3. Emphasis (Bold and Italic)
- Use `*` or `_` for italic.
- Use `**` or `__` for bold.
- Use `***` or `___` for bold and italic.

```markdown
*Italic text*  
_Italic text_  

**Bold text**  
__Bold text__  

***Bold and italic text***  
___Bold and italic text___
```

---

## 4. Lists

### Unordered Lists
Use `-`, `*`, or `+` for unordered lists.

```markdown
- Item 1
- Item 2
  - Sub-item 2.1
  - Sub-item 2.2
* Item 3
+ Item 4
```

### Ordered Lists
Use numbers followed by a period.

```markdown
1. First item
2. Second item
   1. Sub-item 2.1
   2. Sub-item 2.2
3. Third item
```

---

## 5. Links
Use `[text](URL)` for links.

```markdown
[Google](https://www.google.com)
```

For reference-style links:
```markdown
[Google][1]

[1]: https://www.google.com
```

---

## 6. Images
Use `![alt text](image URL)` for images.

```markdown
![Markdown Logo](https://markdown-here.com/img/icon256.png)
```

For reference-style images:
```markdown
![Markdown Logo][logo]

[logo]: https://markdown-here.com/img/icon256.png
```

---

## 7. Code

### Inline Code
Use backticks (`` ` ``) for inline code.

```markdown
This is `inline code`.
```

### Code Blocks
Use triple backticks (```` ``` ````) for code blocks.

```markdown
```
function hello() {
  console.log("Hello, world!");
}
```
```

For syntax highlighting, specify the language after the opening triple backticks:

```markdown
```javascript
function hello() {
  console.log("Hello, world!");
}
```
```

---

## 8. Blockquotes
Use `>` for blockquotes.

```markdown
> This is a blockquote.
> 
> - Author
```

---

## 9. Horizontal Rules
Use `---`, `***`, or `___` to create a horizontal rule.

```markdown
---
```

---

## 10. Tables
Use pipes (`|`) and dashes (`-`) to create tables.

```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Data 1   | Data 2   |
| Row 2    | Data 3   | Data 4   |
```

---

## 11. Inline HTML
You can use HTML tags for advanced formatting.

```markdown
<p style="color:red;">This is a red paragraph.</p>
```

---

## 12. Escaping Characters
Use a backslash (`\`) to escape special characters.

```markdown
\*This is not italic\*
```

---

## 13. Task Lists
Use `- [ ]` for unchecked tasks and `- [x]` for checked tasks.

```markdown
- [x] Complete the guide
- [ ] Publish the guide
```

---

## 14. Footnotes
Use `[^1]` for footnotes.

```markdown
Here is a footnote reference[^1].

[^1]: This is the footnote.
```

---

## 15. Strikethrough
Use `~~` for strikethrough.

```markdown
~~This text is strikethrough.~~
```

---

## 16. Emojis
Use `:emoji_name:` to add emojis.

```markdown
I love Markdown! :heart:
```

---

## 17. Comments (HTML)
Markdown doesn’t support comments natively, but you can use HTML comments.

```markdown
<!-- This is a comment -->
```

---

This guide covers most of the Markdown syntax. You can use it to format your submissions effectively!