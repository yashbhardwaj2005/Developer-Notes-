# Markdown Syntax Notes 📝

> Quick revision notes for writing README files and documentation on GitHub.

---

# 1. Headings Formats 

```md
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

Output:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

---

# 2. Bold & Italic

```md
**Bold Text**

*Italic Text*

***Bold + Italic***
```

Output:

**Bold Text**

*Italic Text*

***Bold + Italic***

---

# 3. Lists

### Unordered List

```md
- Apple
- Mango
- Orange
```

or

```md
* Apple
* Mango
* Orange
```

---

### Ordered List

```md
1. First
2. Second
3. Third
```

---

# 4. Task List

```md
- [x] Learn Markdown
- [x] Create README
- [ ] Master GitHub
```

Output:

* [x] Learn Markdown
* [x] Create README
* [ ] Master GitHub

---

# 5. Links

```md
[GitHub](https://github.com)
```

---

# 6. Images

```md
![Logo](image.png)
```

or

```md
<img src="image.png" width="300">
```

---

# 7. Inline Code

```md
Use `git status` to check repository status.
```

Output:

Use `git status` to check repository status.

---

# 8. Code Blocks

### JavaScript

````md
```javascript
console.log("Hello World");
```
````

### Java

````md
```java
public class Main{
    public static void main(String[] args){
        System.out.println("Hello");
    }
}
```
````

---

# 9. Horizontal Line

```md
---
```

Output:

---

# 10. Block Quote

```md
> Practice makes progress.
```

Output:

> Practice makes progress.

---

# 11. Tables

```md
| Language | Level |
|----------|-------|
| Java | Intermediate |
| JavaScript | Intermediate |
| React | Learning |
```

---

# 12. Checkboxes

```md
- [ ] Learn React
- [ ] Learn Node
- [x] Learn HTML
```

---

# 13. Emojis

```md
🚀 💻 📚 ⭐ 🔥 ✅ ❌
```

You can also use:

```md
:rocket:
:smile:
:fire:
```

---

# 14. Escaping Characters

To display Markdown symbols literally:

```md
\*
\#
\`
```

---

# 15. HTML Inside Markdown

Markdown supports HTML:

```html
<h1 align="center">
Hello World
</h1>

<p align="center">
My GitHub Profile
</p>
```

Useful for beautiful README files.

---

# 16. README Best Practices

✅ Use one `#` heading for the title.

✅ Organize sections using `##`.

✅ Use bullet points for readability.

✅ Add code blocks for examples.

✅ Keep notes concise.

✅ Prefer clean formatting over excessive emojis.

---

# ⚡ Markdown Quick Cheat Sheet

| Purpose          | Syntax                         |      |      |   |
| ---------------- | ------------------------------ | ---- | ---- | - |
| Heading 1        | `# Heading`                    |      |      |   |
| Heading 2        | `## Heading`                   |      |      |   |
| Heading 3        | `### Heading`                  |      |      |   |
| Bold             | `**text**` or `__text__`       |      |      |   |
| Italic           | `*text*` or `_text_`           |      |      |   |
| Bold + Italic    | `***text***`                   |      |      |   |
| Unordered List   | `- Item` or `* Item`           |      |      |   |
| Ordered List     | `1. Item`                      |      |      |   |
| Task List        | `- [ ] Task`                   |      |      |   |
| Completed Task   | `- [x] Task`                   |      |      |   |
| Link             | `[Google](https://google.com)` |      |      |   |
| Image            | `![Alt Text](image.png)`       |      |      |   |
| Inline Code      | `` `code` ``                   |      |      |   |
| Code Block       | ` ```language ... ``` `        |      |      |   |
| Block Quote      | `> Quote`                      |      |      |   |
| Horizontal Line  | `---`                          |      |      |   |
| Table            | `                              | Col1 | Col2 | ` |
| Escape Character | `\*` `\#` ```                  |      |      |   |
| Emoji (GitHub)   | `:rocket:` → 🚀                |      |      |   |
| HTML in Markdown | `<img>`, `<h1>`, `<div>`       |      |      |   |

---

⭐ **Revision Tip:** Markdown is mainly used for `README.md` files, project documentation, notes, and GitHub profiles. Learn the basics once, then practice by writing your own README files.
