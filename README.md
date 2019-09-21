<!DOCTYPE html>
<html lang="en">
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>MD Conversion with Perl</title>
<style>body {
    margin: 1em auto;
    max-width: 40em;
    line-height: 1.61;
    font-size: 1.2em;
    font-family: sans-serif;
    color: #333;
    padding: 0 0.5em;
}
h1,
h2,
h3 {
    line-height: 1.2;
}
@media print {
    body {
        max-width: none;
    }
}

mark {
    background: #8ad;
}
del {
    background: #eaa;
}
ins {
    background: #9cb;
}

mark,
del,
ins {
    border-radius: 0.2em;
    padding: 0.1em 0.2em;
}
</style>
<article><h1>Markdown</h1>

This is a markdown implementation intended to be flexible and hackable to support multiple versions of markdown.

<h2>Contents     </h2>

<h3>Implemented</h3>

<ul>
<li>Headings
</li>
<li>Phrasing Elements
</li>
<li>HTML document wrapping and minimal styling
</li>
<li>Critic Markup
</li>
</ul>
<h3>Not Implemented</h3>

<ul>
<li>Lists
</li>
<li>Line Breaks
</li>
<li>Videos
</li>
<li>Code & Syntax Highlighting
</li>
<li>Links
</li>
<li>Most things Really
</li>
<li>Inline HTML
</li>
<li>Blockquotes
</li>
<li>Images
</li>
<li>Tables
</li>
<li>Horizontal rule
</li>
<li>TEX
</li>
</ul>
<h2>Phrasing Elements</h2>

To use <strong>strong</strong> tags put double ** or __ on each side of a word or phrase.
To use <strong>em</strong> tags put single * or _ on each side of a word or phrase.

<h2>Critic Markup</h2>

Comment with <mark><em>curly parenthesis and angle brackets</em></mark>

Use ins with <ins>plus</ins> del with <del>minus</del>, mark with <mark>mark</mark> 


Superscript with <sup>carrots</sup>. Subscript with <ins><sub>tilds</sub></ins><sup><ins>tilds</ins></sup>

<h2>Headings h1-h6</h2>

Use between 1 and 6 <strong>#</strong> at the start of a line to generate a heading.


<h2>Code</h2>

Inline code spans with <code>backticks</code>


