# Markdown Cheat Sheet

Reference website [Markdown Guide](https://www.markdownguide.org)

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1
## H2
### H3
suport hearding level1~6


### text

***
* * *
*****
- - -
----------

~~text~~

<u>text</u>

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Bold ,Italic And Wrap

*italicized text*
_italicized text_

**bold text**
__bold text__

***bold and italicized text***
___bold and italicized text___

The line break of a paragraph is the use of two or more spaces followed by a carriage return or a blank line directly after the paragraph to indicate restarting a paragraph   
text1  
text2

text1

text2

### List

Ordered List  
1. First item
2. Second item
3. Third item

Unordered List  
- First item
- Second item
- Third item

To nest a list, simply add two or four spaces before the options in the sublist:  
1. first
  a. first2
  b. secend  

- first
  - first2
  - secend

### Blockquote

> blockquote

> blockquote
> > nest blockquote

list in blockquote
> blockquote
> - list

blockquote in list
- block
  > list

### Code

`code`

    code

```java
code
```

### Link

[Markdown Guide](https://www.markdownguide.org)

<https://www.markdownguide.org>

This link uses 1 as the URL variable [Google][1]
This link uses runoob as the URL variable [Runoob][runoob]
Then assign a value (URL) to the variable at the end of the document

  [1]: http://www.google.com/
  [runoob]: http://www.runoob.com/

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

![alt text](https://www.markdownguide.org/assets/images/tux.png "subtitle")

Markdown cannot specify the height and width of the image yet. If you need it, you can use regular<img>tags.

<img decoding="async" src="https://www.markdownguide.org/assets/images/tux.png" width="10%">

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

| Align Left | Align Right | Align Center |
| :-----| ----: | :----: |
| Text | Text | Text |
| Text | Text | Text |

### Definition List

term
: definition
: text

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