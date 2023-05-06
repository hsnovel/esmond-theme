# Esmond Theme #

# About
Esmond is a dark color scheme for emacs

# Screenshot #

![esmond-theme](https://user-images.githubusercontent.com/53369750/236633567-ad3bdfb5-6aef-4e54-9d49-d648c8575f49.png)

# Installation #

Esmond is currently not on MELPA so you have to install it by hand,
to do that create a custom theme folder wherever you want, after that
copy esmond-theme.el file inside theme folder and load to emacs with:

```
(add-to-list 'custom-theme-load-path "<path_to_themes_folder>")
(load-theme 'esmond)
```