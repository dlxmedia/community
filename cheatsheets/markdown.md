# 👨🏻‍🏫 MARKDOWN CHEATSHEET
Easy to understand guide to writing using `markdown` in Github issues, tasks, comments and discussions, with examples you can easily `copy/paste`

> 😀 For a list of Emoji codes you can use this [Emoji Code Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
&nbsp;
# HEADERS

### `📝 TO WRITE`
- ⚠️ Make sure you add a space after the # sign
- H1 and H2 add a line below automatically
- Add `#` or `---` to add a divider

```markdown
# H1 TITLE
## H2 TITLE
### H3 TITLE
#### H4 TITLE
```

### `👁️ WHAT YOU SEE`

# H1 TITLE
## H2 TITLE
### H3 TITLE
#### H4 TITLE

&nbsp;
### `🎨 STYLED HEADERS`

```markdown
H2 with Emoji + Highlight (code)
## `⚡️ Page Title`
```
 ## `⚡️ Page Title`

&nbsp;

```markdown
Quoted H3 with Line Below
> ### Section Title
```

> ### Section Title


&nbsp;
<br>

# TEXT

`📝 TO WRITE`  | `👁️ WHAT YOU SEE` | `⌨️ SHORTCUT`
------------- | ------------- | -------------
\*\*bold**  | **bold** | `cmd` + `b`
\*italic*  | *italic* | `cmd` + `i`
\~~strikethrough~~  | ~~strikethrough~~ | n/a
\`code`  | `code` | `cmd` + `e`

&nbsp;
<br>

# QUOTES

### `📝 TO WRITE`
```markdown
> quoted text
> `quoted code`
> > nested quote
```

### `👁️ WHAT YOU SEE`
> quoted text
&nbsp;

> `quoted code`
> > nested quote

&nbsp;
<br>

# LINKS

### `📝 TO WRITE`

```markdown
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][reference]

URLs and <URLs> will automatically get turned into links. 
http://www.example.com or <http://www.example.com> (but not example.com)

Reference link:
[reference]: https://reflink1.com

[![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)](https://imagelink.com)
 
```

### `👁️ WHAT YOU SEE`
> inline-style link:<br>
> [I'm an inline-style link](https://www.google.com)

> inline-style link with title<br>
> [I'm an inline-style link with title](https://www.google.com "Google's Homepage")

> reference link:<br>
> [I'm a reference-style link][reference]

[reference]: https://reflink1.com

> Image with link:<br>
> [![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)](https://imagelink.com)

&nbsp;
<br>

# LISTS

### `📝 TO WRITE`
```markdown
- bullet point 1
- bullet point 2
  - nested bullet point a
    - nested bullet point i

1. numbered item 1
2. numbered item 2
   1. nested numberd item i
   2. nested numberd item ii
   - nested bullet point a

- [ ] checkbox 1
- [x] checkbox 2
- - [ ] nested checkbox a
  > - [ ] nested checkbox b
```

### `👁️ WHAT YOU SEE`

- bullet point 1
- bullet point 2
  - nested bullet point a
    - nested bullet point i

1. numbered item 1
2. numbered item 2
   1. nested numberd item i
   2. nested numberd item ii
   - nested bullet point a

- [ ] checkbox 1
- [x] checkbox 2
- - [ ] nested checkbox a
  > - [ ] nested checkbox b
