# HTML Whitespace Handling

This document explains how whitespace is handled in HTML, covering how browsers interpret spaces, tabs, and new lines in HTML documents.

### Whitespace in HTML

In HTML, whitespace refers to any sequence of spaces, tabs, or new lines in the code. Whitespace is important for improving code readability, but it is not displayed in the same way on the web page.

### 1. Collapsing Whitespace

By default, HTML collapses multiple spaces, tabs, or new lines into a single space when rendering content in the browser. This means that even if you add multiple spaces or line breaks in your HTML code, only one space will be shown.

### 2. Non-Breaking Space `(&nbsp;)`
To prevent the collapsing of whitespace and ensure extra spaces appear on the web page, you can use a non-breaking space, represented by the HTML entity `&nbsp;`.

### 3. Preserving Whitespace with `<pre>` Tag
The `<pre>` tag is used to preserve both whitespace and line breaks in HTML. Content inside a `<pre>` element is displayed exactly as written in the HTML code, including multiple spaces, tabs, and new lines.