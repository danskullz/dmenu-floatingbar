# Description
This patch allows you to transform the dmenu into a floating bar, with customizable height, as well as vertical and horizontal padding. This is an extension / port of [floatingstatus](https://dwm.suckless.org/patches/floatingstatus/) for dwm.

NOTE: Added an extra flag, '-bo', which allows you to specify the colour of the border explicitly.
By default, the background just inherits the '-sb' flag, to cooperate with default dwm behaviour.

This is my first time patching suckless software. Please feel free to email me if you encounter any issues.

See also: https://dwm.suckless.org/patches/floatingstatus/


## Config

Everything is in ``config.def.h``

    barpadh - [int] Vertical padding: how far the bar is from the top.
    barpadv - [int] Horizontal padding: how far the bar is from each side.
    barheight - [int] Bar height: How long the bar is vertically.
    barborder - [int] Bar border: How thick the border is.

## Download

[dmenu-floatingbar-1.0.diff](https://github.com/danskullz/dmenu-floatingbar/raw/refs/heads/main/dmenu-floatingbar-1.0.diff)

## Authors

    Daniel Guihot - daniel@guihot.net
