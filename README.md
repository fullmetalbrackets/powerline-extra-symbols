![Powerline Extra Symbols](https://raw.githubusercontent.com/ryanoasis/powerline-extra-symbols/master/img/logo.svg?sanitize=true)

> Extra glyphs for your Powerline separators

These glyphs are now available in the patched fonts from: [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts)

![preview](img/preview.png)

_NOTE: This repo is just a mirror of [the original](https://github.com/ryanoasis/powerline-extra-symbols) with only the glyphs and readme file._

Vim preview also showing column number glyph:

![preview](img/preview-3.png)

* `vimrc` settings to achieve the above:
  ```vim
  " testing extra-powerline-symbols

  " set font terminal font or set gui vim font
  " to a Nerd Font (https://github.com/ryanoasis/nerd-fonts):
  set guifont=DroidSansMono\ Nerd\ Font\ 12

  " testing rounded separators (extra-powerline-symbols):
  let g:airline_left_sep = "\uE0B4"
  let g:airline_right_sep = "\uE0B6"

  " set the CN (column number) symbol:
  let g:airline_section_z = airline#section#create(["\uE0A1" . '%{line(".")}' . "\uE0A3" . '%{col(".")}'])
  ```

# Glyphs

![font forge](img/fontforge.png)
