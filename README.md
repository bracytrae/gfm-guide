# GitHub Flavored Markdown Guide

A beginner-friendly guide to **GitHub Flavored Markdown**, also known as **GFM**.

This repository explains the Markdown syntax commonly used in GitHub README files, issues, pull requests, discussions, and documentation.

## What Is GitHub Flavored Markdown?

GitHub Flavored Markdown is GitHub’s version of Markdown. It includes standard Markdown formatting along with additional features such as:

* Task lists
* Tables
* Strikethrough text
* Syntax-highlighted code blocks
* Automatic links
* Mentions
* Issue and pull request references

## Headings

Use the `#` symbol to create headings.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

## Text Formatting

```markdown
**Bold text**

*Italic text*

***Bold and italic text***

~~Strikethrough text~~

`Inline code`
```

Example:

**Bold text**

*Italic text*

***Bold and italic text***

~~Strikethrough text~~

`Inline code`

## Lists

### Unordered Lists

```markdown
- Item one
- Item two
- Item three
```

### Ordered Lists

```markdown
1. First item
2. Second item
3. Third item
```

### Nested Lists

```markdown
- Programming
  - Python
  - JavaScript
  - Java
```

## Task Lists

Task lists are useful for tracking progress.

```markdown
- [x] Create the repository
- [x] Add a README
- [ ] Add more examples
- [ ] Complete the guide
```

Example:

* [x] Create the repository
* [x] Add a README
* [ ] Add more examples
* [ ] Complete the guide

## Links

```markdown
[GitHub](https://github.com)
```

Example:

[GitHub](https://github.com)

## Images

```markdown
![Alternative text](image-url)
```

Example:

```markdown
![GitHub logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

## Blockquotes

Use the `>` symbol to create a blockquote.

```markdown
> Markdown makes documentation easier to read and write.
```

Example:

> Markdown makes documentation easier to read and write.

## Inline Code

Use single backticks for short pieces of code.

```markdown
Use the `git status` command to check your repository.
```

## Code Blocks

Use three backticks to create a code block.

````markdown
```python
print("Hello, GitHub!")
```
````

You can include the programming language after the opening backticks to enable syntax highlighting.

```python
print("Hello, GitHub!")
```

## Tables

```markdown
| Syntax | Description |
|--------|-------------|
| `#` | Heading |
| `**text**` | Bold text |
| `*text*` | Italic text |
| `- [ ]` | Task list item |
```

Example:

| Syntax     | Description    |
| ---------- | -------------- |
| `#`        | Heading        |
| `**text**` | Bold text      |
| `*text*`   | Italic text    |
| `- [ ]`    | Task list item |

## Horizontal Lines

Use three hyphens, asterisks, or underscores.

```markdown
---
```

---

## Escaping Markdown Characters

Use a backslash when you want Markdown symbols to appear as regular text.

```markdown
\# This is not a heading
\* This is not italic text
```

## GitHub Mentions

Mention a GitHub user by placing `@` before their username.

```markdown
@username
```

## Referencing Issues and Pull Requests

Reference an issue or pull request by using the `#` symbol followed by its number.

```markdown
#12
```

You can reference an item from another repository using:

```markdown
username/repository#12
```

## Collapsible Sections

GitHub supports collapsible sections using HTML.

```html
<details>
  <summary>Click to view more</summary>

  Hidden content goes here.

</details>
```

Example:

<details>
  <summary>Click to view more</summary>

Hidden content goes here.

</details>

## Keyboard Keys

Use the `<kbd>` HTML element to display keyboard keys.

```html
Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy.
```

Example:

Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy.

## Directory Structure

```text
gfm-guide/
├── README.md
├── examples/
│   ├── headings.md
│   ├── lists.md
│   ├── tables.md
│   └── task-lists.md
└── LICENSE
```

## Purpose of This Repository

The purpose of this project is to:

* Practice writing Markdown
* Learn GitHub documentation formatting
* Create a quick GFM reference
* Improve README-writing skills
* Help beginners understand GitHub formatting

## Contributing

Contributions are welcome!

I felt this repository was more than just a personal repo or referenceable repo and felt it would be a good idea to add a contributions section for a tool that's universal. I'm very active on git-hub so I'd be incredibly happy to accept PR's. 

To contribute:

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/new-example
```

3. Make your changes.
4. Commit your changes.

```bash
git commit -m "Add new Markdown example"
```

5. Push the branch.

```bash
git push origin feature/new-example
```

6. Open a pull request.

## Resources

* [GitHub Markdown Documentation](https://docs.github.com/en/get-started/writing-on-github)
* [Basic Writing and Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [GitHub Flavored Markdown Specification](https://github.github.com/gfm/)

## License

This project is available for educational and personal use.

## Author

Created by [Trae Bracy](https://github.com/traebracy).
