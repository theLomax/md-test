# md-test

.md | output
:---:|:---:
`# h1`|h1
`## h2`<br><br>*or*<br><br>`text`<br>`---`|h2
`### h3`|h3
`#### h4`|h4
`##### h5`|h5
`###### h6`|h6
`<br>`|line<br>Break
<br>`---`|line
`**bold**`|**bold**
`_italic_`<br><br>*or*<br><br>`*italic*` |*italic*
`~~strike~~`|~~strikethrough~~
\``code snippet`\`|`code snippet`
` ```` `code block` `` ````` <br>*or*<br>` ` ` ` ` ` ` ` `(four spaces) code`<br>`block`|```code```<br>```block```
`\*`|escape: *
`>quote`| quote
`>quote`<br><br>`>>nested quote`|»quote<br>»»nested quote
`- one `<br><br>`- two`<br><br>`- three`| _bulleted list_<br>- one<br>- two<br>- three
`1.`<br><br>`1.`<br><br>`1.`|_numbered (auto) list_<br>1.<br>2.<br>3.
`1.`<br><br>`2.`<br><br>`5\.`<br><br>`9\.`|_escaped numbers_<br>1.<br>2.<br>5.<br>9.
`-`<br><br>`_`<br><br>`#`<br><br>`*`<br><br>`>`<br><br>``` ` ```| _Characters that **must** be escaped:_<br><br>\- n dash<br><br>\_ underscore<br>#adjacent-hashtage<br><br>\* asterisk<br><br>\> angle bracket _(quote)_<br><br>\` backticks
`![Alt Text](URL)`<br><br> *or* <br><br>`![](URL)`| _image_<br> ![image](https://placeimg.com/300/150/any)
`http://URL`<br><br> *or* <br><br>`[Link Text](http://URL)`|[_URL link_]()

Right<br>Aligned | Middle<br>Aligned | Left<br>Aligned
---:|:---:|:---
Test|TEST|test
