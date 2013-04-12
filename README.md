# Gridism

A simple responsive CSS grid. [View the demo →](http://cobyism.com/gridism/)

## Why?

When I design web layouts, I don’t think in 12 or 16 column grids. Instead, my mental model usually works something like this:

- The page being divided up into multiple vertical sections, and…
- Each vertical section being divided up into simple combinations of fractions of the section width.

I think to my self:

> Alright, in this section, I want a bit that’s one third of the section’s width, and then next to that I want another bit that’s two thirds of the sections’s width. Now, in the next section…

When I use frameworks with fixed numbers of columns, I have to:

1. Remember how many columns are in the grid for the particular framework I’m using.
1. Decide how I want to divide up this particular section’s content.
1. Mentally do the conversion from what I want to see (one quarter + three quarters, for example) into the number of columns I need for the grid I’m using.
1. Remember the class naming structure for the framework I’m using. Is it `.span3`, `.grid_3`, `.col-3`, or something else altogether?

I feel like only the second step should be necessary. I couldn’t find a framework that matched this mental model of how I work, so I started hacking on Gridism.

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
