# Windows Terminal Themes

Here are my config and themes for [Windows Terminal](https://github.com/microsoft/terminal).

I added some new themes including:

1. MaterialUI
2. FlatUI
3. Dracula
4. IndianPalette

## To use these config & themes

### 1. Copy `.terminalIcons` folder and paste it int `C:\Users\<user>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState`

### 2. Open Terminal settings, which will open `Profiles.json`, Remove all from there and paste all of these from [here](https://github.com/DNI9/Windows-Terminal-Themes/raw/master/profiles.json)

Now save and restart Terminal.

To change theme, use the theme name from above and set `"colorScheme": "<ThemeName>"` in any profile.

MaterialUI enabled by default.

## Note:

`Azure Cloud Shell` is disabled in this config. To enable, set the value of `"hidden": true` to `false`.

\* Git bash also included. To hide it add `"hidden": true` in Git bash profile.

# Extras

## Enabling context menu

Go [here](https://github.com/kerol2r20/Windows-terminal-context-menu#install) & follow the installation guide.

## Customizing More

coming soon xD
