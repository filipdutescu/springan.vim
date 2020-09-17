# springan.vim

A dark Vim/Neovim colour scheme for the GUI and 16/256/true-color terminals.

## Colour reference

![springan.vim](https://raw.githubusercontent.com/filipdutescu/spingan.vim/master/img/colours.png)

| Colour  | Normal  | Bright  |
|-----------------------------|
| Black   | #26292B | #303436 |
| Red     | #C16A6D | #CF8C8E |
| Green   | #8AB97B | #A1C794 |
| Yellow  | #DBA057 | #E2b378 |
| Blue    | #7B82B9 | #949AC7 |
| Magenta | #B17ABA | #C193C8 |
| Cyan    | #7BB0B9 | #94BFC7 |
| White   | #D3D0CB | #E7E5DF |

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

