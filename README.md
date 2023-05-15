# Esmond Theme

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-green.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![MELPA](https://melpa.org/packages/esmond-theme-badge.svg)](https://melpa.org/#/esmond-theme)

## About
Esmond is a dark color scheme for emacs

![esmond-theme](https://user-images.githubusercontent.com/53369750/238314322-4bc47320-4f9b-459a-a598-1a8e8db9be3d.png)

## Installation

### Manual

Download `esmond-theme.el` to the directory `~/.emacs.d/themes/` and add this
to your `.emacs` or `init.el`

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
```
If you want to load it by default you can add this line to your init file
```lisp
(load-theme 'esmond)
```

### Package.el

Esmond is avaliable on MELPA, you can install it with
`M-x package-install esmond-theme`

If you cannot find the package try `M-x package-refresh-contents`