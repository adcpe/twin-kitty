# Twin for kitty

A pair of sibling themes for [kitty](https://sw.kovidgoyal.net/kitty/). Twin focuses on readability and comfort.

**Blue** is all about vibrant colors. **Grey** is cozier, with dimmed colors.

## Palette

## Twin Blue

![Twin Blue Palette](/img/tb_palette.png)

![Twin Blue Screenshot](/img/tb.png)

## Twin Grey

![Twin Grey](/img/tg_palette.png)

![Twin Grey Screenshot](/img/tg.png)

## Installation

<!-- ### Automatic

Run this command inside kitty to access all kitty themes.

```
kitty +kitten themes
```

Search for Twin Blue or Twin Grey to install. -->

### Manual

Download this file and place it alongside your kitty config file.

```
# Twin Blue
$ curl -o ~/.config/kitty/twin-blue.conf https://raw.githubusercontent.com/adcpe/twin-kitty/master/twin-blue.conf
```

```
# Twin Grey
$ curl -o ~/.config/kitty/twin-grey.conf https://raw.githubusercontent.com/adcpe/twin-kitty/master/twin-grey.conf
```

Place this line at the bottom of your config file:

```
# ~/.config/kitty/kitty.conf

include ./twin-blue.conf
# or
include ./twin-grey.conf
```

## License

[MIT](/LICENSE)
