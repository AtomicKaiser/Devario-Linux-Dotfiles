# Devario Linux Dotfiles
# THIS IS A VERY PERSONALIZED THEME + WAY OF SETTING UP A WM 

Configuration backups for the Devario Linux desktop.

| Directory  | Installs to       | Contents                                  |
| ---------- | ----------------- | ----------------------------------------- |
| `aqueous/` | `~/.config/aqueous` | Compositor/WM config (layout, outputs, keybinds) |
| `pearl/`   | `~/.config/pearl`   | Theme engine state, matugen templates and generated outputs |

## Restore

```sh
cp -a aqueous ~/.config/aqueous
cp -a pearl ~/.config/pearl
```

Note: `pearl/matugen/writer.lock` and `pearl/qt/writer.lock` are empty runtime
lock files and can be ignored or deleted after restoring.

This does not come with my wallpaper set by default ;  Please add your own one or set it manually. I do not like forcing colour scheme and wallpaper~
( also github fuck you its colour not color)

