# floatingbar

## Description

This patch transforms dmenu into a floating bar with configurable height, along with customizable vertical and horizontal padding. It extends the [floatingstatus](https://dwm.suckless.org/patches/floatingstatus/) patch for dwm.

An additional `-bo` option has been added to explicitly set the border colour. By default, the border colour inherits the `-sb` value, matching the default behaviour of dwm.

#### Example configuration

* `barpadh` (`int`) – Horizontal padding: distance between the bar and the sides of the screen.
* `barpadv` (`int`) – Vertical padding: distance between the bar and the top of the screen.
* `barheight` (`int`) – Bar height.
* `barborder` (`int`) – Border width.

#### Screenshots

![bar](bar.png)

![dmenu](dmenu.png)

## Download

* [dmenu-floatingbar-5.4.diff](dmenu-floatingbar-5.4.diff)

## Author

* Daniel Guihot - [daniel@guihot.net](mailto:daniel@guihot.net)
