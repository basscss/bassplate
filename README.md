# Bassplate
Boilerplate for [Basscss](http://basscss.com) with cssnext

## Features

- Basic `index.html` template with asset links and responsive viewport meta tag
- Starter folder structure
- npm run scripts for processing with [cssnext](https://cssnext.github.io/)
- npm run script for local web server
- cssnext features
  - [Autoprefixer](https://github.com/postcss/autoprefixer)
  - [Custom properties](http://www.w3.org/TR/css-variables/) (variables)
  - [Custom Media Queries](http://dev.w3.org/csswg/mediaqueries/#custom-mq)
  - [Inline imports](https://github.com/postcss/postcss-import) for npm modules and local files
  - [Reduce `calc()`](https://github.com/postcss/postcss-calc)
  - [`color()`](http://dev.w3.org/csswg/css-color/#modifying-colors)

## Getting Started

To start fresh, clone Bassplate into a new project and remove its git directory.

``` bash
git clone https://github.com/basscss/bassplate.git new-project
cd new-project
rm -rf .git
```

Install dev dependencies. (Requires Node and npm -- [Install Node](http://nodejs.org/download/))

``` bash
npm install
```

Start watching files for compilation and start development server.

``` bash
npm start
```

Open <http://localhost:8080>

Use `index.html` as a starting point and edit the files in `src/` to customize the CSS.

---

MIT License

