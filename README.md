# springan.vim

A dark Vim/Neovim colour scheme for the GUI and 16/256/true-color terminals.

## Colour reference

<p align="center">
  <img src="https://github.com/filipdutescu/springan.vim/raw/master/img/colours.png" alt="springan.vim colours"/>
</p>

| Colour  | Normal                                                                 | Bright                                                                                     |
|---------|:----------------------------------------------------------------------:|:------------------------------------------------------------------------------------------:|
| Black   | #26292B (<span style="background-color: #26292B; color: #D3D0CB;">color0</span>) | #303436 (<span style="background-color: #303436; color: #E7E5DF;">color0</span>) |
| Red     | #C16A6D (<span style="background-color: #26292B; color: #D3D0CB;">color1</span>) | #CF8C8E (<span style="background-color: #CF8C8E; color: #E7E5DF;">color1</span>) |
| Green   | #8AB97B (<span style="background-color: #26292B; color: #D3D0CB;">color2</span>) | #A1C794 (<span style="background-color: #A1C794; color: #303436;">color2</span>) |
| Yellow  | #DBA057 (<span style="background-color: #26292B; color: #D3D0CB;">color3</span>) | #E2B378 (<span style="background-color: #E2B378; color: #303436;">color3</span>) |
| Blue    | #7B82B9 (<span style="background-color: #26292B; color: #D3D0CB;">color4</span>) | #949AC7 (<span style="background-color: #949AC7; color: #E7E5DF;">color4</span>) |
| Magenta | #B17ABA (<span style="background-color: #26292B; color: #D3D0CB;">color5</span>) | #C193C8 (<span style="background-color: #C193C8; color: #E7E5DF;">color5</span>) |
| Cyan    | #7BB0B9 (<span style="background-color: #26292B; color: #D3D0CB;">color6</span>) | #94BFC7 (<span style="background-color: #94BFC7; color: #303436;">color6</span>) |
| White   | #D3D0CB (<span style="background-color: #26292B; color: #D3D0CB;">color7</span>) | #E7E5DF (<span style="background-color: #E7E5DF; color: #303436;">color7</span>) |

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

