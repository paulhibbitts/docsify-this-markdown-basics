# Markdown

## What is Markdown? 
Markdown is a syntax to format the display of content stored as plain text - similar but simpler than HTML formatting

## Why Markdown? 

* System-independent
* Text only format (perfect for version control)
* Separation of content vs. presentation
* Human-readable (i.e. more than HTML)
* Can also contain HTML snippets

## Markdown Examples

## Headers

<h1> # Your h1 Text Here </h1>
<h2> # Your h2 Text Here </h2>

```
# Your h1 Text Here  
## Your h2 Text Here  
```

## Emphasis

_your italic text here_  

```
_your italic text here_  
```

**your bold text here**  

> **Fusion Drive** combines a hard drive with a flash storage (solid-state drive) and presents it as a single logical volume with the space of both drives combined.

* your unordered list item here  

  1. your numbered (and indented) list item here   

[link title](www.google.com)  

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

![image alt text](https://octodex.github.com/images/minion.png)

Footnote 1 link[^first].

[^first]: Footnote **can have markup**

```
Tip: To ensure a new paragraph after text in markdown, put two spaces after the end of the line

## Headings

Headings from `h1` through `h6` are constructed with a `#` for each level:

<h1> # h1 Heading </h1>
<h2> # h2 Heading </h2>
<h3> # h3 Heading </h3>
<h4> # h4 Heading </h4>
<h5> # h5 Heading </h5>
<h6> # h6 Heading </h6> 


## Horizontal Rule

---


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> This is an example Blockquote.


## Lists

Unordered

- Create a list by starting a line with `-`, or `*`
- Sub-lists are made by indenting 2 spaces:
  - So this is a sub-list item!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica


## Images

![Minion](https://octodex.github.com/images/minion.png)


## Footnotes

Footnote 1 link[^first].

Footnote 2 link[^second].


[^first]: Footnote **can have markup**

[^second]: Footnote text.
