---
title: For Example of very Long Title Would Be Typography Elements in One
updated: 2016-10-18 23:37

---
**NOTE:** This markdown cheatsheet is a typography demo for this theme. Check out this post to learn more about this markdown usage when you want to get started with this theme. Enjoy!

## Typography Elements in One

Let's start with a informative paragraph. **This text is bolded.** But not this one! _How about italic text?_ Cool right? Ok, let's **_combine_** them together. Yeah, that's right! I have code to highlight, so `ThisIsMyCode()`. What a nice! Good people will hyperlink away, so [here we go](#) or [http://www.example.com](http://www.example.com).

<div class="divider"></div>

## Headings H1 to H6

# H1 Heading

## H2 Heading

### H3 Heading

#### H4 Heading

##### H5 Heading

###### H6 Heading

<div class="divider"></div>

## Footnote

Let's say you have text that you want to refer with a footnote, you can do that too! This is an example for the footnote number one \[^1\]. You can even add more footnotes, with link! \[^2\]

<div class="divider"></div>

## Blockquote

> Start by doing what's necessary; then do what's possible; and suddenly you are doing the impossible. --Francis of Assisi

**NOTE:** This theme does NOT support nested blockquotes.

<div class="divider"></div>

## List Items

1. First order list item
2. Second item

* Unordered list can use asterisks


* Or minuses


* Or pluses

<div class="divider"></div>

## Code Blocks

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

    No language indicated, so no syntax highlighting.
    But let's throw in a <b>tag</b>.

<div class="divider"></div>

## Table

### Table 1: With Alignment

| Tables | Are | Cool |
| --- | :---: | ---: |
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

### Table 2: With Typography Elements

| Markdown | Less | Pretty |
| --- | --- | --- |
| Still | renders | nicely |
| 1 | 2 | 3 |

<div class="divider"></div>

## Horizontal Line

The HTML `<hr>` element is for creating a "thematic break" between paragraph-level elements. In markdown, you can create a `<hr>` with any of the following:

* `___`: three consecutive underscores
* `---`: three consecutive dashes
* `***`: three consecutive asterisks

renders to:

***

***

***

<div class="divider"></div>

## Media

### YouTube Embedded Iframe

<iframe width="560" height="315" src="https://www.youtube.com/embed/n1a7o44WxNo" frameborder="0" allowfullscreen></iframe>

### Image

![Minion](http://octodex.github.com/images/minion.png)

{% include caption.html sideBySide=false url="https://images.unsplash.com/photo-1593642632559-0c6d3fc62b89?ixid=MXwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2250&q=80" description="We decided to explore the usage of the ribbon from our wireframes, building assets to match the style and sharpness of the angles." %}

{% include caption.html sideBySide=true url="https://images.unsplash.com/photo-1613092869277-6e02af5564aa?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2250&q=80" description="It's just a wave." %}

{% include caption.html sideBySide=true url="https://images.unsplash.com/photo-1508108712903-49b7ef9b1df8?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2250&q=80" description="Pain delle Betulle, Italy" %}

\[^1\]: Footnote number one yeah baby! Long sentence test of footnote to see how the words are wrapping between each other. Might overflowww!
\[^2\]: A footnote you can link to - [click here!](#)