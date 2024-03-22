# magick.css
> magically playful, yet simple styling. all in one file.

<br>
<img alt="a wizard" src="wizard.webp" width="240" height="240">

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

