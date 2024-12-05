## Setup

Download zip and copy paste the contents in ~/.config/mpv.

Alternatively:
```
cd ~/.config/mpv && git clone https://github.com/talpinum/mpv-config.git
```

Obviously, if you don't want the keyboard shortcuts and other things to be changed, don't copy the mpv.conf and input.conf files


## Gradience support
The script colors the playback bar pulling the accent color from 
> ~/.config/gtk-4.0/gtk.css

If not possible, the bar is white

*Note: accent color must be defined as "@define-color accent_bg_color #INSERT_HEX_HERE;", like gradience does to color gtk3 and gtk4 apps

