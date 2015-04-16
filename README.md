HexColor
==========
This is a fork of [vim-coloresque](https://github.com/gorodinskiy/vim-coloresque), but _for hex and rgb values only_ (e.g. it won't automatically find and highlight colors like ``red`` or ``blue``).
***


![pic](https://raw.github.com/gorodinskiy/vim-coloresque/master/screen.png)

color preview for vim.

###Overview

This is merge of [ap vim-css-color](https://github.com/ap/vim-css-color) and [colorizer](https://github.com/lilydjwg/colorizer).
The main goal was to fix cursorline [bug](https://github.com/skammer/vim-css-color/issues/12) and keep named colors(i.e. white, black, aqua). I ended up mixing both plugins plus wrote some stuff, so I decided to leave it as a separate plugin.

###Installation

Via [vundle](https://github.com/gmarik/vundle):

```
Bundle 'https://github.com/gorodinskiy/vim-coloresque.git'
```

###Features

You can still use hsl(a)

![Picture](https://coderwall-assets-0.s3.amazonaws.com/uploads/picture/file/1965/hsla.png)

or multiple colours on same line

![Picture](https://coderwall-assets-0.s3.amazonaws.com/uploads/picture/file/1963/cursorline.png)

and you can use named colors(case insensitive)

![Picture](https://coderwall-assets-0.s3.amazonaws.com/uploads/picture/file/1964/letters.png)
