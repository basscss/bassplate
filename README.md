# Bassplate
Boilerplate for [Basscss](http://basscss.com) with postcss

## Features

- Basic `index.html` template with asset links and responsive viewport meta tag
- Starter folder structure
- npm run scripts for processing with postcss
- postcss plugins
  - import
  - custom-media
  - custom-properties
  - calc
  - color-function
  - discard-comments
  - autoprefixer

## Getting Started

You will need

- [git](https://git-scm.com/)
- [Node.js](http://nodejs.org/download/)
- **[npm v3](https://docs.npmjs.com/getting-started/installing-node#updating-npm)** - just a `sudo npm install -g npm` away

To start fresh, clone Bassplate into a new project and remove its git directory.

``` bash
git clone https://github.com/basscss/bassplate.git new-project
cd new-project
rm -rf .git
```

Install the dependencies.

``` bash
npm install
```

Start watching files for compilation.

``` bash
npm start
```

Use `index.html` as a starting point, and edit `src/base.css` to customize the CSS.

## Adding optional modules

To add [other helpful basscss modules](https://www.npmjs.com/search?q=basscss), add the relevant `@import` to `src/base.css` and add the dependency to your `package.json`

So to add the basscss [background image utils](https://github.com/basscss/background-images)
you'd:

Edit `src/base.css`

```css
@import 'basscss-background-images';
```

Add the dependency

```sh
npm install basscss-background-images
```

and then recompile with

```sh
npm run css
```

---

MIT License

