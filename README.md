airline-hybrid-alt
==================

This is a theme for
[vim-airline](https://github.com/bling/vim-airline), a light-weight vim status bar
plugin.

Airline already comes bundled with a theme based on the
[hybrid](https://github.com/w0ng/vim-hybrid) colour scheme, but the way the
colours are applied is not to my liking - hence I created my own!

<p align="center">
    <img src="https://raw.github.com/daviesjamie/airline-hybrid-alt/master/preview.gif" alt="hybrid-alt" />
</p>

## Installation

The theme follows the standard runtime path structure, and so it is possible to
install it with any of the popular plugin managers:

- [Vundle](https://github.com/gmarik/vundle)
    - `Bundle 'daviesjamie/airline-hybrid-alt'`
- [NeoBundle](https://github.com/Shougo/neobundle.vim)
    - `NeoBundle 'daviesjamie/airline-hybrid-alt'`
- [Pathogen](https://github.com/tpope/vim-pathogen)
    -  `git clone https://github.com/daviesjamie/airline-hybrid-alt
       ~/.vim/bundle/airline-hybrid-alt`

You can also install the plugin manually, by copying the files into your
`~/.vim` directory.

After it is installed, you just need to tell Airline to use the theme:

```VimL
let g:airline_theme='hybridalt'
```
