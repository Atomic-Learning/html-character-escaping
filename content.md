When writing HTML, some characters should be escaped so they are treated as content instead of markup.

Character references start with an ampersand `&` and usually end with a semicolon `;`.

In normal HTML text content, there are two characters that must always be escaped:

* `&amp;` for &amp;
* `&lt;` for &lt;

# Greater Than Sign

The character `>` is usually safe to use unescaped in text content. Some authors still escape it with `&gt;` for consistency or to avoid edge-case parser ambiguity.

# Other Escapes

Many other characters can be escaped using their numeric or named character references. This can improve source readability and portability in some workflows, but is not generally required. Here are a few examples:

* `&copy;` for &copy;
* `&reg;` for &reg;
* `&trade;` for &trade;
* `&mdash;` for &mdash;
