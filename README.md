# agda-evil-emacs

`agda-evil-emacs` is a small, extensible configuration for Emacs, designed for
vim users who want to try out Agda, without having to go through the fuss of
learning larger Emacs distributions like Doom or Spacemacs. Furthermore,
every piece of the configuration is thoroughly documented, so
this can also serve as a good jumping off point if you decide you want
to use emacs for non Agda purposes.

Specifically, it comes with `agda-mode` preconfigured, all you need is
to have a working install of `agda` and you are good to go!

## Installation
First, install Emacs. If you are on OSX, I personally recommend using the following homebrew formula,
with the options `--with-cocoa` and `--with-native-comp`.
- https://github.com/daviderestivo/homebrew-emacs-head

First, install Agda, either from your package manager, or by following the instructions
found (here)[https://agda.readthedocs.io/en/latest/getting-started/installation.html].

Next, create a directory called `.emacs.d` in your home directory, and copy the
`init.el` in this repository into it. After that, simply launch up Emacs!

## Keybinding Cheat Sheet
Most useful keybindings start with a `SPC` prefix.
- `SPC f f` can be used to open files.
- `SPC b b` can be used to select buffers.
- `SPC w` opens up the window management menu, which lets us split/switch windows.

If you type part of a key sequence and wait, Emacs will display a list of possible
keybindings available.
