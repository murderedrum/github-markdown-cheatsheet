# **Github Flavored Markdown Beginners Cheatsheet**
### **Markdown Editor Built into Atom**

Show rendered HTML markdown using `CTRL-SHIFT-m`.  ATOM enables HTML markdown for *.markdown, .md, .mdown, .mkd, .mkdown, .ron*, and *.txt* files.  HTML can also be added to the text.  Install [ :dizzy: Atom](https://atom.io/) for Windows, Mac or Linux.

# **Comment**
(If anything besides this line is seen in this Comment area **then that specific comment command is not working!**)
[//]: # (Comment Type/Test #1)
[//]: <> (Comment Type/Test #2)
[comment]: <> (Comment Type/Test #3)

# **Headers**
(Start line with the number of hashtags (#) as stated after the **H** to make the following headers.)
# H1 tag
alternative H1 tag
==================
## H2 tag
alternative H2 tag
------------------
### H3 tag
#### H4 tag
##### H5 tag
###### H6 tag
(In Atom, only two -- or == is needed under the word to use the alternative header tag.  For readability of the text file, however, it's recommended to add the line across the entire title.)

# **Text Styling**
(italic - surround text with \* or \_ ): *italic text 1* or _italic text 2_

(bold - surround text with \*\* or \_\_ ): **bold text 1** or __bold text 2__

**You can encapsulate *italics* in bold**

or _ __bold__ in italics..._

Strikethough by surrounding text with \~\~ can ~~redact~~.

# **Links**
(simple: enter the URL, it becomes a link) https://github.com/

(relative - \[link name\]\(url\) - example: [github](https://www.github.com/))

# **Quote**
(The first two can used to format code w/o code highlighting.)

this is an `inline` quote

```
A box of formated text```

> This is a blockquote

> enjoy!

# **Code**
(Four ```` followed by code language. Supports code highlighting whenever possible.)
````javascript
alert('Hello World!')
````

````python
print("Hello World!")
````

````html
<html>
  <head>
    <title>Hello World!</title>
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html>
````

```
 three ``` also works (no code formatting)```

This is inline code ( surround text with \` ): `#!/bin/bash`

# **Tables**
(Use | for every column and - between header; Place | where  - meets.)

Header 1 | Header2 | Header 3
:-------:|:--------|---------:
Center 1 | Left 2  | Right 3
Center 4 | Left 5  | Right 6

# **Unordered Lists**
(Use tabs for sub-items: + - or * can be used.)
* item
  * sub-item
    + sub-sub-item
      - sub-sub-sub-item
* item
* item

# **Ordered Lists**
(Add two tabs add unordered items - behavior can be strange and might change in future...)
1. item
  1. sub-item
    1. sub-sub-item
    * sub-sub-sub-item
2. item
3. item
* item

# **Task Lists**
(Add lists of marked and unmarked items with "- [ ]" unmarked or "- [x]" marked.)
- [x] one
- [ ] two
- [x] three


# **Images**
(Bracket holds alternative text of image, parens hold the URL of the image)
![8-bit octo](https://github.com/octo.png)

# **Emoji**
(display emojis on the screen by surrounding the word with ::)

:smile: :shit: :eggplant:

**Full list:** http://www.webpagefx.com/tools/emoji-cheat-sheet/

# **Ignore Markdown**
(add \ in front of markdown character to escape and display character, not always necessary)

\# I love hashtags \#


# **Inline HTML**
(most HTML works with GitHub Flavored Markdown)

# **Notice**
CC0 - Ron Cotton
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="http://roncotton.com/">
    <span property="dct:title">Ron Cotton</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">github-markdown-cheatsheet</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="http://roncotton.com/">
  United States</span>.
</p>
