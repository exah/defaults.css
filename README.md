# defaults.css

> normalize.css extended with opinionated resets & defaults

notable resets:

- paddings, margins
- borders in `fieldset`, `iframe`
- spacing after `audio`, `canvas`, `iframe`, `img`, `svg`, `video` elements

defaults:

- set `box-sizing` globally to `inherit` parent value
- use `box-sizing: border-box` in `html`
- set default font-family to `system-ui`
- make inputs, buttons, links to `inherit` text styles
- enable `font-smoothing` by default
- `svg` to use `currentColor` for filling

...and many other, see [source code](./src/defaults.css)


## Install

```sh
npm install --save defaults.css
```


## Related

- [normalize.css](https://github.com/necolas/normalize.css/) — A collection of HTML element and attribute style-normalization
- [sanitize.css](https://github.com/jonathantneal/sanitize.css) — The best-practices CSS foundation
- [MiniReset.css](https://github.com/jgthms/minireset.css) — A tiny modern CSS reset
- [reset.css](http://meyerweb.com/eric/tools/css/reset/) — Eric Meyer's CSS reset

---

MIT © [John Grishin](http://johngrish.in)
