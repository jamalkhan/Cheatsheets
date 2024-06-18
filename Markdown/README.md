# Markdown Cheat Sheet #

## Headers

# Header 1
Start a line with a single # to use Header 1. Subsequent, unhashed lines are treated as normal text
## Header 2
Start a line with a double ## to use Header 2. Subsequent, unhashed lines are treated as normal text
### Header 3
Start a line with a triple ### to use Header 3. Subsequent, unhashed lines are treated as normal text


## Formatting Text

**Surround text in two astericks (*) to embolden text** 

*Surround text in one astericks (*) to italicize text*

> Prefix a line with a Righgt Angle Bracket > to blockquote

## Lists

### Ordered List

1. Prefix a line with a number, followed by a period, <code>1. </code> then space to start a numbered list
2. This line is prefixed with <code>2. </code>, to define the second bullet is the second item on the line
2. This line is also prefixed with <code>2. </code>. Notice, when rendered, Markdown will format this as a properly numbered list.
3. This line is prefixed with <code>3. </code>.
   1. This line is prefixed with three spaces and then a number. e.g., <code>   1. </code>.
   2. This line is prefixedw ith three spaces and then a number. e.g., <code>   2. </code> .

### Unordered List

- First item is prefixed with <code>- </code>.
    - Sub bullet 1 is prefixed with three spaces, then an endash, space.
    - Like This, <code>&nbsp;&nbsp;&nbsp;- </code>, ensuring 
- Second item
    1. You can also embed numbered lists
    2. As such
- Third item

### Code

<code>code</code>

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![This is an 8-bit Mario, and you are reading the alt-text](https://www.kindpng.com/picc/m/50-506919_8-bit-mario-png-mario-bros-8-bits.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

I need to highlight these ==very important words==.

### Subscript

H~2~O

### Superscript

X^2^