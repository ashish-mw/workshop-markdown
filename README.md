![markdown logo](assets/md-logo.png)

# A gentle intro to Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a light-weight
markup language used for creating formatted text using a simple text-editor.

This is similar in spirit to HTML, but its a lot less small.

We can convert text written in markdown to a variety of other document formats. This
includes html, pdf and a whole lot of others. It should be noted that the technique of
writing content in one format (markup) and exporting it to another format pre-dates
markdown or html. The most widely used of these approaches is
[LATEX](https://en.wikipedia.org/wiki/LaTeX). Tools like
[pandoc](https://pandoc.org/MANUAL.html) will help with this.

One common use-case for markdown is writing
[READMEs](https://en.wikipedia.org/wiki/README) in projects. Source code hosting
platforms like Github will render mardown to html so that it can be viewed in
all its glory in our browsers.

## Previewing markdown

- In [vscode](https://code.visualstudio.com/download), on the md file and press `Ctrl + Shift + v` to open the preview window.
Drag the tab to the side and preview as your compose.
- Download any one markdown composer that you'd like from <https://www.fossmint.com/best-markdown-editors-for-macos> or <https://www.oberlo.in/blog/markdown-editors>.
- Try online at <https://dillinger.io/>

## The markdown cheatsheet

This is not a definitive list, but this would be enough to write good documentation
for our projects.

### 1. Headings

```
# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6
```

will give

# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6

### 2. Paragraphs

Normal lines are paragraphs by default.

### 3. Bold

```
**I am bold**
```

will give

**I am bold**

### 3. Italic

```
*I am italicized*
```

will give

*I am italicized*

### 4. blockquote

```
> This is a blockquote that someone has said in their lifetime.
```

will give

> This is a blockquote that someone has said in their lifetime.

### 5. Ordered list

```
1. First item
2. Second item
3. Third item
```

will give

1. First item
2. Second item
3. Third item

### 6. Un-ordered list

```
- First item
- Second item
- Third item
```

will give

- First item
- Second item
- Third item

### 7. Code

```
`code`
```

will give

`code`

### 8. Horizontal rule

```
---
```

will give

---

### 9. Links

```
[example.com](https://www.example.com)
```

will give

[example.com](https://www.example.com)

### 10. Image

```
![markdown's logo](assets/md-logo.png)
```

will give

![markdown's logo](assets/md-logo.png)

### 11. Code block

```
``` const msg = 'Hello World!' ```
```

will give

```
const msg = 'Hello World!'
```

## More reading

- [https://www.markdownguide.org/cheat-sheet/](https://www.markdownguide.org/cheat-sheet/)
- [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [GH markdown style](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

## Bonus

```
$ npm i -g markdown-html-cli
$ md2html README.md
$ open README.html
```