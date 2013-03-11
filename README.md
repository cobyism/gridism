# Gridism

A simple responsive CSS grid. [View the demo →](http://cobyism.com/gridism/)

## Overview

- **Simple**—Each `.grid` element is a horizontal row which can contain `.unit` elements of various widths. Width combinations are detailed below.
- **Responsive**—Units get stacked on screens 568px or smaller. Grids in a `.wrap` have maximum widths of 978px, or 1140px when there’s lots of room.
- **Easy**—All units have even inner and outer gutters. You can turn gutters off with `.no-gutters`. There are also a few other commonly needed classes for things like alignment, floating, and hiding things.

## Installation

### 1. Get the files

The easiest way to use Gridism in your project is via the [Bower](http://twitter.github.com/bower) package manager.

```sh
bower install gridism
```

Elsewise, [download a zip folder](https://github.com/cobyism/gridism/archive/gh-pages.zip), extract it, and copy `gridism.css` into your project’s folder.

### 2. Link the stylesheet

Add the following stylesheet to your HTML’s `<head>` section:

```html
<link rel="stylesheet" href="components/gridism/gridism.css">
```

**Note:** If you didn’t install using Bower, you need to adjust the path of CSS file to match your file structure.

### 3. Viewport scale

Add the following meta tag to your HTML’s `<head>` section:

```html
<meta name="viewport" content="width=device-width,initial-scale=1">
```

Without this meta tag, mobiles and tablets might load your page as a scaled-down version of the desktop size, instead of resizing the content to match the device’s actual viewport width.

## Contributing

I’d :heart: to recieve contributions to this project. It doesn’t matter if it’s just a typo, or if you’re proposing an overhaul of the entire project—I’ll gladly take a look at your changes. Fork at will! :grinning:.

## License

Go nuts. See [LICENSE](https://github.com/cobyism/gridism/blob/gh-pages/LICENSE) (MIT).
