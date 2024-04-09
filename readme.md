# Leon's macOS configs

## Setup

```shell
cd ~
git init
git remote add origin https://github.com/leonsilicon/macos-configs
git pull origin main
```

## Keymappings

My Karabiner-Elements keymaps, which can be found at [`.config/goku/karabiner.edn`](./.config/goku/karabiner.edn), is defined using [GokuRakuJoudo](https://github.com/yqrashawn/GokuRakuJoudo) which uses it to generate a `karabiner.json` file.

## Shortcuts/Keybinds

### System-wide

Shortcuts for system-wide utilities such as controlling Yabai (the window manager) or opening certain applications use the following combination of modifier keys (referred to as "Super"): `⌘⌥^` (and optionally `⇧`)

> We don't use the `Fn` key because it's not detectable when setting shortcuts in certain applications.

#### Yabai

Karabiner is used for the keybinds which can be found at [`.config/goku/karabiner.edn`](./.config/goku/karabiner.edn)

> The general rule for using "Shift" is either if a command is a complementary one (e.g. increasing height instead of width) or if it modifies some sort of state (e.g. moving windows)

`<Super+J>` Focus window down\
`<Super+Shift+J>` Move window down\
`<Super+K>` Focus window up\
`<Super+Shift+K>` Move window up\
`<Super+L>` Narrow/expand window to left\
`<Super+Shift+L>` Increase window height\
`<Super+H>` Narrow/expand window to right\
`<Super+Shift+H>` Decrease window height\
`<Super+M>` Focus master window\
`<Super+K>` Focus master window\
`<Super+Shift+M>` Move window to master\
`<Super+Shift+I>` Increase number of master windows\
`<Super+Shift+D>` Decrease number of master windows\
`<Super+,>` Focus previous display\
`<Super+Shift+,>` Move window to previous display\
`<Super+.>` Focus next display\
`<Super+Shift+.>` Focus window to next display\
`<Super+Shift+Q>` Close focused window

#### Apps

`<Super+R>` Opens **R**aycast\
`<Super+C>` Opens **C**leanShot X (capture mode)\
`<Super+S>` Opens Clean**S**hot X (all-in-one mode)\
`<Super+T>` Opens Shor**t**cat\
`<Super+W>` Opens **W**arp\
`<Super+Q>` Opens **Q**utebrowser\
`<Super+P>` Opens 1**P**assword (quick access mode)\
`<Super+G>` Opens To**g**gl Track
`<Super+A>` Opens Todoist (`A` for "**a**dd todo)\
`<Super+N>` Show **N**otion Calendar

#### Input navigation

`<Option+Left>` Go to end of word\
`<Option+Shift+Left>` Select to end of word\
`<Option+Right>` Go to start of word\
`<Option+Shift+Right>` Select to start of word\
`<Command+Left>` Go to start of line\
`<Command+Shift+Left>` Select to start of line\
`<Command+Right>` Go to end of line\
`<Command+Shift+Right>` Select to end of line\
`<Command+Up>` Go to start of input\
`<Command+Shift+Up>` Select to start of input\
`<Command+Down>` Go to end of input\
`<Command+Shift+Down>` Select to end of input\

### VSCode

My VSCode shortcuts generally adhere to the following principles:

`⌥` - Used for "navigation" actions (e.g. changing views, go to definition, switching between editors, etc.)\
`⌘` - Used for "non-navigation" actions (usually modifies state, but also includes actions like search/find)\
`⌘⇧` - Used for complementary "non-navigation" actions, e.g. opposites (`⌘Z` = Undo, `⌘⇧Z` = Redo), or scope changes (`⌘F` = Find in current file, `⌘⇧F` = Find in all files)\
`^` - Not used for any VSCode shortcuts - reserved for the Vim extension\
`^⌥` - Used for shortcuts that set/toggle some sort of option

#### Common shortcuts

##### Option+KEY

`<Option+A>` Reveal Active File in Explorer View\
`<Option+C>` Go to declaration\
`<Option+D>` Go to definition\
`<Option+F>` Go to file\
`<Option+G>` A chord keybind to represent "global"-ness\
`<Option+HJKL>` Navigate between views\
`<Option+I>` Go to implementations\
`<Option+M>` Go to next merge conflict\
`<Option+Shift+M>` Go to previous merge conflict\
`<Option+P>` Go to next problem\
`<Option+Shift+P>` Go to previous problem\
`<Option+R>` Go to references

##### Command+Key

`<Command+A>` Select all\
`<Command+C>` Copy\
`<Command+E>` ESLint Fix auto-fixable problems\
`<Command+F>` Find in file\
`<Command+Shift+F>` Search in project\
`<Command+M B>` Merge conflict: Accept both\
`<Command+M C>` Merge conflict: Accept current\
`<Command+M I>` Merge conflict: Accept incoming

