# vue-webpack-opinionated-boilerplate

> An opinionated Webpack setup for `vue-loader` for quick prototyping.

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

In your `App.vue`, add these lines to the top of your style section. You can customize the default Bootstrap colors by changing the variables before importing Bootstrap.

```sass
$blue: #42a5f5;
$white: #f7f7f9;

$brand-primary: $blue;
$body-bg: $white;
$component-active-color: $white;
$btn-primary-color: $white;
$btn-secondary-bg: $white;
$btn-info-color: $white;
$btn-success-color: $white;
$btn-warning-color: $white;
$btn-danger-color: $white;
$input-bg: $white;

@import '~bootstrap/scss/bootstrap-flex';
```

### Fork It And Make Your Own

You can fork this repo to create your own boilerplate, and use it with `vue-cli`:

``` bash
vue init username/repo my-project
```
