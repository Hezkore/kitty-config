## Kitty Configuration
Just my personal [Kitty](https://github.com/kovidgoyal/kitty) configuration.

Copy/symlink/clone `hezkore.conf` into `~/.config/kitty`.\
It also depends on the Kitty [Dracula Theme](https://draculatheme.com/kitty), which should be placed in `~/.config/kitty/dracula`.

Then add this to your `~/.config/kitty/kitty.conf` file:
```
include ./dracula/dracula.conf
include ./hezkore.conf
```

When combined with the GTK [Dracula Theme](https://draculatheme.com/gtk), this configuration unifies the color scheme of the Kitty terminal and the window title bar, creating the appearance of a single, seamless window.