# Kanji (漢字)

A modern theme for Sublime Text!

### Installation

###### Recommended

You can install Kanji via [Package Control](https://packagecontrol.io/).

1. Press <kbd>cmd/ctrl</kbd> + <kbd>shift</kbd> + <kbd>p</kbd> to open the command palette.
2. Type `install package` and press enter. Then search for `kanji`

###### Manual

1. Download the [latest release](https://github.com/tassyguy/kanji-theme/releases/latest), extract and rename the directory to `ayu`.
2. Move the directory inside your sublime `/Packages` directory. *(Preferences > Browse packages...)*

---

### Font

While you can use any font you wish, Kanji by default uses [__Roboto Mono__](https://www.google.com/fonts/specimen/Roboto+Mono) as main font and it's highly recommended to install it to get monospaced font in filetree. But if you don't have it then the UI theme will downgrade to standard UI font used in Sublime Text.

### File Icons

Kanji supports customization via [A File Icon](https://github.com/ihodev/a-file-icon) package. Please install it and restart Sublime for better expereince.

<!---
### Screenshots

<h6 align='center'>Light with <code>ui_separator</code> option off</h6>

![Light](https://i.imgur.com/DbWFq76.png)

---

<h6 align='center'>Dark with <code>ui_separator</code> option off</h6>

![Dark](https://i.imgur.com/pmkHtQJ.png)
-->
<!--
### Settings

```js
"ui_native_titlebar":       true, // use native titlebars on macOs
"ui_separator":             true, // separators between panels
"ui_font_size_small":       true, // smaller UI font size(sidebar, statusbar etc)
"ui_big_tabs":              true, // increased tab height
"ui_fix_tab_labels":        true, // to fix tab labels if they look not right
"ui_font_source_code_pro":  true, // use Source Code Pro (https://fonts.google.com/specimen/Source+Code+Pro) as UI font
"ui_font_default":          true, // use Sublime's default UI font
"ui_wide_scrollbars":       true, // wider scrollbars
```
-->
---

### Installation

###### Recommended

You can install Kanji via [Package Control](https://packagecontrol.io/).

1. Press <kbd>cmd/ctrl</kbd> + <kbd>shift</kbd> + <kbd>p</kbd> to open the command palette.
2. Type `install package` and press enter. Then search for `kanji`

###### Manual

1. Download the [latest release](https://github.com/tassyguy/kanji-theme/releases/latest), extract and rename the directory to `ayu`.
2. Move the directory inside your sublime `/Packages` directory. *(Preferences > Browse packages...)*

---

### Activation

###### Recommended

Open command palette via `Tools > Command Palette` (or <kbd>cmd/ctrl</kbd> + <kbd>shift</kbd> + <kbd>p</kbd>) and type `Kanji: Activate theme`.


###### With Skins package

[Skins](https://packagecontrol.io/packages/Skins) provides a simple and efficient way to change themes, save your own presets and quickly try out new looks. Activation is as simple as opening up the command palette, running `Select Skin` and choosing `Kanji - Dark` or `Kanji - Light` from the list.


###### Via Preferences

Add these lines to your user settings *Preferences > Setting - User*:

For light theme:

```js
"theme": "kanji.light.sublime-theme",
"color_scheme": "Packages/kanji/kanji.light.tmTheme",
```

For dark theme:

```js
"theme": "kanji.dark.sublime-theme",
"color_scheme": "Packages/kanji/kanji.dark.tmTheme",
```

### Related projects and ports

- `Kanji` for Atom: https://github.com/tassyguy/kanji-ui
- `Kanji` for VSCode: https://github.com/teabyii/kanji-vscode

<div align="right"><sup>
  made with ❤️ by <a href="https://github.com/tassyguy">@tassyguy</a>
</sup></div>
