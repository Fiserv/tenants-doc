# Using Markdown in Documentation

### What is Markdown?
>Markdown is a text-to-HTML conversion tool for web writers.

>Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then gets converted to HTML.

For example, this entire page was created using Markdown!

Below is a quick reference of all the Markdown syntax that is supported by Stoplight.

### Table of Contents  
* [Headers](#headers)
* [Emphasis](#emphasis)
* [Lists](#lists)
* [Links](#lnks)
* [Images](#imgs)
* [Code and Syntax Highlighting](#code)
* [Tables](#tables)
* [Blockquotes](#blockquotes)
* [Horizontal Rule](#hr)

## <a name="headers"/> Headers

# H1<br/>
## H2<br/>
### H3<br/>
#### H4<br/>
##### H5<br/>
###### H6<br/>

## <a name="emphasis"/> Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.<br/>

Strong emphasis, aka bold, with **asterisks** or __underscores__.<br/>

Combined emphasis with **asterisks and _underscores_**.<br/>

Strikethrough uses two tildes. ~~Scratch this.~~<br/>

## <a name="lists"/> Lists

>In this example, leading and trailing spaces are shown with with dots: ⋅⋅⋅

1. First ordered list item<br/>
2. Another item<br/>
..- Unordered sub-list<br/>
3. Actual numbers don't matter, just that it's a number<br/>
..1. Ordered sub-list<br/>
4. And another item<br/>

...You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).<br/>

## <a name="lnks"/> Links

Different ways to create links:<br/><br/>
To link Inline-style<br/>
`[I'm an inline-style link](https://www.google.com)`<br/>

Note: Spaces are not allowed between the label and the link<br/>

[I'm an inline-style link](https://www.google.com)<br/>

To link to API explorer from documentation pages<br/>
`API page](../api?type=post&path=/v1/apis)`<br/>

[API page](../api?type=post&path=/v1/apis)<br/>

To link/reference to another document/markdown<br/>
`[Charge](?path=docs/Transactions/Charges.md)`<br/>
[Charge](?path=docs/Transactions/Charges.md)<br/>

To create anchor link within the page. You can place anchor by declaring<br/>
`[Dev Portal](#portal)`<br/><br/>
Now you can reference this link anywhere within the page by declaring link such as [Dev Portal](#portal)<br/>

## <a name="imgs"/> Images

## <a name="code"/> Code and Syntax Highlighting

Inline `code` has `back-ticks around` it.<br/>
<br/>
Here is the example for javascript code.<br/>
<br/>
```javascript
var s = "JavaScript syntax highlighting";<br/>
alert(s);<br/>
```
<br/>
Use language tags to change the syntax highlighting.<br/>
<br/>
```json
{
<nbsp><nbsp>"JSON": "Syntax Highlighting"
}
```

## <a name="tables"/> Tables

Tables aren't part of the core Markdown spec, but they are part of the *GFM* (GitHub Flavored Markdown). They are an easy way of adding structure to your documentation.<br/>

Colons can be used to align columns. The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily.<br/>
<br/>
| Tables        | Are           | Cool  |<br/>
| ------------- |:-------------:| -----:|<br/>
| col 3 is      | right-aligned | $1600 |<br/>
| col 2 is      | centered      |   $12 |<br/>
| zebra stripes | are neat      |    $1 |<br/>
<br/>
Note that the GFM standard requires there to be a blank line before the table in order for it to be considered a valid table. Also, there must be at least three hyphens in each column of the header row.<br/>
<br/>
For example, this is not a valid markdown table because it doesn't have a blank line proceeding it:<br/>
<br/>
*Some text directly proceeding a table*<br/>
*| Header1       | Header2       | Header 3 |*<br/>
*| ------------- |:-------------:| --------:|*<br/>
*| zebra stripes | are neat      |    $1    |*<br/>
<br/>

This is also not a valid markdown table because there aren't at least three hyphens in each column of the header row:<br/>
<br/>
*Some text not directly proceeding a table that doesn't have at lest three hyphens in each header colum*<br/>
<br/>
*|  1  |  2 |  3  |*<br/>
*| --- | -- | --- |*<br/>
*|  a  |  b |  c  |*<br/>
<br/>

## <a name="blockquotes"/> Blockquotes

> Blockquotes are very handy in email to emulate reply text.<br/>
> This line is part of the same quote.<br/>

Quote break<br/>

> This is a very long line of text that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote, just in case you didn't know.

## <a name="hr"/> Horizontal Rule

Three or more...<br/>
<br/>
---<br/>
Hyphens<br/>
***<br/>
Asterisks<br/>
___<br/>
Underscores<br/>
