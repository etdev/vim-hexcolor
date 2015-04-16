HexColor
==========
This is a vim plugin that highlights hex and rgb color codes in css files etc. with that respectice color. It's a fork of [vim-coloresque](https://github.com/gorodinskiy/vim-coloresque), but _for hex and rgb values only_ (e.g. it won't automatically find and highlight colors like ``red`` or ``blue``).
***

Preview:   
![original](https://cloud.githubusercontent.com/assets/6726985/7173406/14a58e92-e432-11e4-84cc-0e6316960ddd.png)

My changes:
![my-changes](https://cloud.githubusercontent.com/assets/6726985/7173407/17b57250-e432-11e4-9376-9ba4f75a8e98.png)

###Overview

This is a merge of [ap vim-css-color](https://github.com/ap/vim-css-color) and [colorizer](https://github.com/lilydjwg/colorizer).

###Installation

Via [vundle](https://github.com/gmarik/vundle):

```
Bundle 'https://github.com/etdev/vim-hexcolor.git'
```

###Features

* You can still use hsl(a)

![Picture](https://coderwall-assets-0.s3.amazonaws.com/uploads/picture/file/1965/hsla.png)

* Use multiple colors on the same line
