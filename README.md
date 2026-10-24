# Devario Linux Dotfiles

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
