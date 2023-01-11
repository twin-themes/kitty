# Twin for kitty

A pair of sibling themes for [kitty](https://sw.kovidgoyal.net/kitty/). Twin focuses on readability and comfort.

**Black** is cozy, with dimmed colors. **Blue** is all about vibrant colors.

## Palette

## Twin Black

![Twin Black](/img/black_palette.png)

![Twin Black Screenshot](/img/black.png)

## Twin Blue

![Twin Blue Palette](/img/blue_palette.png)

![Twin Blue Screenshot](/img/blue.png)

## Installation

<!-- ### Automatic

Run this command inside kitty to access all kitty themes.

```
kitty +kitten themes
```

Search for Twin Black or Twin Blue to install. -->

### Manual

Download this file and place it alongside your kitty config file.

```
# Twin Black
$ curl -o ~/.config/kitty/twin-black.conf https://raw.githubusercontent.com/adcpe/twin-kitty/master/twin-black.conf
```

```
# Twin Blue
$ curl -o ~/.config/kitty/twin-blue.conf https://raw.githubusercontent.com/adcpe/twin-kitty/master/twin-blue.conf
```

Place this line at the bottom of your config file:

```
# ~/.config/kitty/kitty.conf

include ./twin-black.conf
# or
include ./twin-blue.conf
```

## License

[MIT](/LICENSE)
