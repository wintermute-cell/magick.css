# magick.css
> magically playful, yet simple styling. all in one file.

<br>
<img alt="a wizard" src="wizard.webp" width="240" height="240">

### Translations

- [中文 (Simplified Chinese)](./translations/zh-CN.md)

> Feel free to contribute a translation to your language!

## What is magick.css?
magick.css is a minimalistic, (mostly) classless CSS framework that is designed
to be easy to use and easy to understand. It is contained in a single file, and
every choice is commented. The goal is to achieve an elegant, but magically
playful look, while maximizing readability and the ability to convey
information; *somewhat akin to the notes of a wizard*.

The framework retains its beauty and functionality across all devices and
screen sizes, and works entirely without JavaScript. It is inspired by
[LaTeX](https://www.latex-project.org/), old school TTRPG rulebooks, CSS
frameworks like [concrete.css](https://concrete.style/) and [Tufte
CSS](https://edwardtufte.github.io/tufte-css/) and the "usability as design"
ethic of brutalism.

## What does it look like?
You can find a live example of magick.css being used [on my
website](https://css.winterveil.net)!

## How do I use magick.css?
> magick.css is built with
> [normalize.css](https://necolas.github.io/normalize.css/). While it will look
> 90% correct without, it is recommended to use normalize.css.

### CDN
The easiest way to check out magick.css for your own project is to add it from
a CDN. Just add these two lines to your html `<head>`:

```html
<link rel="stylesheet" href="https://unpkg.com/normalize.css">
<link rel="stylesheet" href="https://unpkg.com/magick.css">
```

### Local File
You could also just download the `magick.css` file from this repo, and include
it into your html `<head>` as you normally would:

```html
<link rel="stylesheet" href="path/to/magick.css">
```

### JS/NPM
You could also add `magick.css` to your JS project like this:

```bash
npm install normalize.css magick.css
```

And import them in your code:
```js
import 'normalize.css'
import 'magick.css'
```

## Ports
magick.css currently also available as...

### Obsidian.md Theme
> I don't like the hoops theme developers have to jump through to publish their
> work on the official theme gallery of a proprietary, monetized product. There
> is no compensation for their hard work beyond the donations of generous
> users; all the while Obsidian.md benefits greatly from them. That's why the
> Obsidian.md theme version of magick.css is not available in the official
> gallery.

Still, Obsidian.md is a useful tool for a lot of people. That's why I've made
the effort to port this CSS framework to Obsidian.md. You can install it by...

1. Downloading `ports/obsidian.md/magick.css.zip` from this repo.
2. Unpacking it into the Obsidian.md theme directory. You can find this
   directory by pressing the folder icon next to the `Appearance > Themes`
   setting inside of Obsidian.md
3. If the theme is not immediately selectable, try restarting Obsidian.md to
   refresh.
