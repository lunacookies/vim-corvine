<table><tbody align="center"><tr><td>
<h1>vim-corvine</h1>
<table><tbody align="center"><tr><td><img src="https://raw.githubusercontent.com/arzg/resources/master/corvine-screenshot.png"/></td>
<td><img src="https://raw.githubusercontent.com/arzg/resources/master/corvine-light-screenshot.png"/></td></tr></tbody></table>
<h3>the <a href="https://github.com/baskerville/etc/blob/master/neovim/.config/nvim/colors/raven-dark.vim">Raven</a> colourscheme for Vim, modified and rebuilt</h3>
<em>made in <a href="https://github.com/lifepillar/vim-colortemplate">Colortemplate</a>, the Toolkit for Vim Colourscheme Designers</em>
</td></tr></tbody></table>

## Installation

Use your favourite runtimepath/plugin manager, or place `corvine.vim` into
`~/.vim/colors/` for \*nix and `%userprofile%\vimfiles\colors\` for Windows.

## Usage

If you’re using a GUI, then Corvine should work out of the box. However, if you’re planning to use Corvine in a terminal, the terminal must support the 256 colour palette, which most modern ones do. For Corvine Light, on the other hand, your terminal must support 24-bit colour, also known as True Colour, if you want the correct background colour (apart from this, Corvine Light does not require 24-bit colour). You can enable Vim to use this palette (if it is available) with `set termguicolors`. If you want other terminal output to match with Corvine, then set its colours to match the ones below:

Dark:

| Colour     | Normal    | Bright    |
| ---        | ---       | ---       |
| Black      | `#3a3a3a` | `#626262` |
| Red        | `#d78787` | `#ffafaf` |
| Green      | `#87af5f` | `#afd787` |
| Yellow     | `#d7d7af` | `#d7d787` |
| Blue       | `#87afd7` | `#87d7ff` |
| Magenta    | `#afafd7` | `#d7afd7` |
| Cyan       | `#87d7d7` | `#5fd7d7` |
| White      | `#c6c6c6` | `#eeeeee` |
| Foreground | `#c6c6c6` |           |
| Background | `#262626` |           |

Light:

| Colour     | Normal    | Bright    |
| ---        | ---       | ---       |
| Black      | `#eee8dc` | `#9e9e9e` |
| Red        | `#d75f5f` | `#d7005f` |
| Green      | `#005f00` | `#008700` |
| Yellow     | `#af8700` | `#af5f00` |
| Blue       | `#0087d7` | `#00afd7` |
| Magenta    | `#5f5faf` | `#af5faf` |
| Cyan       | `#008787` | `#00afaf` |
| White      | `#585858` | `#000000` |
| Foreground | `#585858` |           |
| Background | `#fff9ed` |           |

A preset for both of these colourschemes is included for iTerm. Only the dark variant has a preset for Terminal.app. This is because Terminal.app doesn’t support 24-bit colour, therefore leading to a situation in which a colourscheme that is impossible to match in Vim is included as a terminal preset. In the end, I simply decided against including the preset to avoid the issue.

## Options

- `g:corvine_italics`: set to `0` to force italics off, and `1` to force italics on
