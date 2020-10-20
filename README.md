# Frontend boilerplate

This is a starter workflow for building vanilla JavaScript applications using Parcel along with Babel and Sass.

## Included tools and libraries

* [Parcel](https://parceljs.org/): The zero configuration web application bundler
* [Babel](https://babeljs.io/): The Javascript compiler. It's used implicitly by Parcel. 
* [Sass](https://sass-lang.com/): The CSS pre-compiler.
* [Eslint](https://eslint.org/) with the [airbnb](https://github.com/airbnb/javascript) configuration: Because everyone should use a linter nowadays.
* [pug](https://pugjs.org/api/getting-started.html): The Javascript template engine available. 

## Feature
* optimizing images
* compiling Sass .scss files
* handling and inlining assets
* automatically appending vendor prefixes
* removing unused CSS selectors
* minifying CSS
* outputing sourcemaps for use in browser devtools
live-reloading CSS in a browser when source files change.

## Building and running on localhost

### Install dependency

```sh
npm install
```
or

```sh
yarn install
```
### Dev mode: http://localhost:1234

```sh
npm start
```
or

```sh
yarn start
```

### Production mode

```sh
npm run build-prod
```
or

```sh
yarn run build-prod
```
