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

Start watching files for compilation.

``` bash
npm start
```

Use `index.html` as a starting point and edit the files in `src/` to customize the CSS.

---

MIT License

