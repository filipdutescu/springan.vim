# springan.vim

<p align="center">
  <img width="762" height="544" src="https://github.com/filipdutescu/springan.vim/raw/master/img/springan.vim.png" alt="springan.vim colours"/>
</p>

A dark Vim/Neovim colour scheme for the GUI and 16/256/true-color terminals.

## Colour reference

<p align="center">
  <img src="https://github.com/filipdutescu/springan.vim/raw/master/img/colours.png" alt="springan.vim colours"/>
</p>

| Colour  | Normal           | Bright            |
|---------|:----------------:|:-----------------:|
| Black   | #26292B (color0) | #303436 (color8)  |
| Red     | #C16A6D (color1) | #CF8C8E (color9)  |
| Green   | #8AB97B (color2) | #A1C794 (color10) |
| Yellow  | #DBA057 (color3) | #E2B378 (color11) |
| Blue    | #7B82B9 (color4) | #949AC7 (color12) |
| Magenta | #B17ABA (color5) | #C193C8 (color13) |
| Cyan    | #7BB0B9 (color6) | #94BFC7 (color14) |
| White   | #D3D0CB (color7) | #E7E5DF (color15) |

## Installation

1. Install the theme using your Vim plug-in manager of choice (or manually, by
placing `colors/springan.vim` in your `~/.vim/colors/` directory (or `~/.config/nvim/colors/`,
for [Neovim](https://github.com/neovim/neovim)).

Or use a plugin manager to install it, such as [vim-plug](https://github.com/junegunn/vim-plug).
For example, for [vim-plug](https://github.com/junegunn/vim-plug), add this in your
`.vimrc` or `init.nvim`, then run `:PlugInstall`:

```bash

  Plug 'filipdutescu/springan.vim'

```

2. Add the following to your `~/.vimrc` (below any lines you may have added in step
1):

 ```vim
   syntax on
   colorscheme springan
 ```

3. Installing the [sheerun/vim-polyglot](https://github.com/sheerun/vim-polyglot)
plug-in is recommended for improved syntax highlighting for various languages, but
is not required.

## Acknowledgments

* **nuaNce** ([@co1ncidence](https://github.com/co1ncidence)) - used his setup
and functions for setting the colours

