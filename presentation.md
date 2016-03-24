# Basic Literasee
## Markdown

---

## Headers

===

```
# H1 Heading
```

# H1 Heading

===

```
## H2 Heading
```

## H2 Heading

===

```
### H3 Heading
```

### H3 Heading

===

```
#### H4 Heading
```

#### H4 Heading

===

```
##### H5 Heading
```

##### H5 Heading


---

## Text

===

```
**Bold** or __Bold__
_Italic_ or *Italic*
_**Bold Italic**_ or **_Bold Italic_**
~~strike through~~
```

**Bold** or __Bold__

_Italic_ or *Italic*

_**Bold Italic**_ or **_Bold Italic_**

~~strike through~~

---

## Lists

===

1. First ordered list item
2. Another item
  * Unordered sub-list.
  - Second item of unordered sub-list using minus.
  + Third item of unordered sub-list using plus.
1. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
    2. Second item of sub-list
4. And another item.


---

## Tables

===

| Name | Description |
| ------------- | ----------- |
| Help | Display the help window.|
| Close | Closes a window     |
| Email | Initiate email window |
| ~~Twitter~~ | ~~Tweet~~ |


---

## Hypertext-Links

===

| Markdown | Result |
|----------|--------|
| ```[An inline-style link](http://literasee.io)``` | [An inline-style link](http://literasee.io)|
| ```[An inline-style link with title](http://literasee.io "Literasee Homepage")``` | [An inline-style link with title](http://literasee.io "Literasee Homepage") |

---

## Embedded images

===

### Embedded bitmap images

```
![alt text](https://avatars0.githubusercontent.com/u/16685371?v=3&s=200 "Literasee logo")
```

![alt text](https://avatars0.githubusercontent.com/u/16685371?v=3&s=200 "Literasee logo")


===

### Embedding vector graphics

```
<a href="https://literasee.github.io"><img src="https://literasee.github.io/public/Literasee_symbol_right_trimmed.svg" style="width: 100%;"></a>
```

<a href="https://literasee.github.io"><img src="https://literasee.github.io/public/Literasee_symbol_right_trimmed.svg" style="width: 100%;"></a>


===

### Embedding D3 visualizations

```
<iframe
    width="100%"
    height="510"
    scrolling="no" src="https://rawgit.com/bclinkinbeard/0192cf1c32d6fc50d247/raw/689619eeefdb0d79c1d0cbca935ca677c13cdfce/index.html">
</iframe>
```

<iframe
    width="100%"
    height="510"
    scrolling="no" src="https://rawgit.com/bclinkinbeard/0192cf1c32d6fc50d247/raw/689619eeefdb0d79c1d0cbca935ca677c13cdfce/index.html">
</iframe>


===

### Embedding Tableau visualizations

```
<iframe
    src="https://public.tableau.com/views/50YearsofCrime/USCrimeDashboard?:embed=y&:loadOrderID=0&:display_count=yes&:showTabs=y"
    width="800"
    height="800">
</iframe>
```

<iframe
    src="https://public.tableau.com/views/50YearsofCrime/USCrimeDashboard?:embed=y&:loadOrderID=0&:display_count=yes&:showTabs=y"
    width="800"
    height="800">
</iframe>


===

### Embedding Plotly visualizations

```
<iframe
    src="https://plot.ly/~matlab_user_guide/1963.embed?width=640&height=480."
    width="800"
    height="600">
</iframe>
```

<iframe
    src="https://plot.ly/~matlab_user_guide/1963.embed?width=640&height=480."
    width="800"
    height="600">
</iframe>


---

## Embedded videos

===

Markdown doesn't directly support the inclusion of videos. However, Markdown
supports HTML which can be used to embed videos

<iframe style=“border: 2px solid #111111;” src="https://player.vimeo.com/video/62604492?color=c9ff23&byline=0&portrait=0" width="800" height="450" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

---

## Blockquotes

===

```
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.
```

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

===

```
> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
```

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

---

## Code & syntax highlighting

===

```javascript
if (isAwesome){
  return true
}
```

===

```R
x <- rnorm(100, mean=50, sd=10)
y <- x + rnorm(100)
plot(x, y)
```
