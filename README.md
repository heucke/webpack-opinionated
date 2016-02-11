# vue-webpack-opinionated-boilerplate

> An opinionated Webpack setup for `vue-loader` for quick prototyping.

**Wondering why I made this and how it went? Check out my [blog](http://heucke.io/web-dev/).**

### Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli). Includes support for Jade and Sass. This boilerplate also contains handy examples of child components, data binding, data passing, list rendering, and form binding for easy pickup of the Vue ecosystem.

``` bash
$ npm install -g vue-cli
$ vue init theucke/webpack-opinionated my-project
$ cd my-project
$ npm install
$ npm run dev
```

### What's Included

- `npm run dev`: Webpack + `vue-loader` with proper config for source maps & hot-reload.

- `npm run build`: Production build with HTML/CSS/JS minification.

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

### Adding Bootstrap

This template does not include any CSS frameworks. If you want to install your favorite version follow along with this example for Bootstrap4.

```base
$ npm install bootstrap@4.0.0-alpha.2
```

In a new `src/style/custom.scss`, you can customize the default Bootstrap colors.

```sass
$color-primary: #42A4F5;
$color-secondary: #F7F7F9;

$brand-primary: $color-primary;
$body-bg: $color-secondary;

@import '~bootstrap/scss/bootstrap-flex';
```

Then in your `main.js`, require the file with `require('./style/custom.scss')`.

### Fork It And Make Your Own

You can fork this repo to create your own boilerplate, and use it with `vue-cli`:

``` bash
vue init username/repo my-project
```
