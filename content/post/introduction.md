---
title: "The Enabler: Introduction"
date: 2019-08-28T22:44:36+10:00
# lastmod: 2018-03-07T16:01:23+08:00
draft: false
tags: ["random"]
categories: ["stargazing"]
author: "George"

weight: 1

# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
# comment: false
# toc: false

# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
# contentCopyright: '<a href="https://github.com/gohugoio/hugoBasicExample" rel="noopener" target="_blank">See origin</a>'
# reward: true
# mathjax: true

---

Hi there, and welcome to my new adventure. You may remember me by the appearances on https://crmtipoftheday.com and https://crm.audio. 

<!--more-->

## History

On one sunny (potentially) afternoon (maybe) I was searching 



## Paragraph and line breaks

A paragraph is simply one or more consecutive lines of text. In markdown source code, paragraphs are separated by more than one blank lines. In Typora, you only need to press `Return` to create a new paragraph.

Press <kbd>Shift + Return</kbd> to create a single line break. However, most markdown parser will ignore single line break, to make other markdown parsers recognize your line break, you can leave two whitespace at the end of the line, or insert `<br/>`.

## Blockquotes

Markdown uses email-style > characters for block quoting. They are presented as:


> This is a blockquote with two paragraphs. This is first paragraph.
>
> This is second pragraph.Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> This is another blockquote with one paragraph. There is three empty line to seperate two blockquote.
>
> 这是一段中文测试。
>


In typora, just input ‘>’ followed by quote contents a block quote is  generated. Typora will insert proper ‘>’ or line break for you. Block quote inside anther block quote is allowed by adding additional levels of ‘>’.

## Lists

Input `* list item 1` will create an un-ordered list, the `*` symbol can be replace with `+` or `-`.

Input `1. list item 1` will create an ordered list, their markdown source code is like:

* Red
* Green
* Blue

1. Red
2. Green
3. Blue


## Task List

Task lists are lists with items marked as either `[ ]` or `[x]` (incomplete or complete). For example:

- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**, @mentions, #1234 refs
- [ ] incomplete
- [x] completed

You can change the complete/incomplete state by click the checkbox before the item.

## Syntax Highlighting

```js
function helloWorld () {
  alert("Hello, World!")
}
```

```java
public class HelloWorld {
  public static void main(String[] args) {
    System.out.println("Hello, World!");
  }
}
```


