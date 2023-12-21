# vim-espresso

This is a Vim color scheme based on the [Espresso][] theme for iTerm2. It has
support for both GUI and terminal colors, and includes its own colorscheme for
[Lightline][].

[Espresso]: https://github.com/mbadolato/iTerm2-Color-Schemes#espresso
[Lightline]: https://github.com/itchyny/lightline.vim

## Screenshots

Here is a terminal instance of Vim with some Scala code:

![vim-espresso Scala Example](https://raw.githubusercontent.com/gmoe/vim-espresso/gh-pages/images/scala.png)

And here is another Vim instance with Python code:

![vim-espresso Python Example](https://raw.githubusercontent.com/gmoe/vim-espresso/gh-pages/images/python.png)

## Installation

If you're unfamiliar with vim, consider using something like [vim-plug][] to
maintain your plugins:

1. Add the following to your `.vimrc`:
```vim
Plug 'coryab/vim-espresso'
```
2. Restart vim and execute `:PlugInstall` to automatically download and install
   this plugin.

Or consider using Vim 8's [native plugin manager][vim8] and clone this repo
into your bundle.


Make sure to edit your `.vimrc` as well:

```vim
set t_Co=256
set background=dark
colorscheme espresso
```

[vim-plug]: https://vimhelp.org/repeat.txt.html#packages
[vim8]: https://vimhelp.org/repeat.txt.html#packages
