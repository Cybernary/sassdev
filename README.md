# SASSdev

This is My SASS development environment setup, a simple way to show in real time your changes into any SASS file.

## How to set up

1. Clone repo and get inside the directory
1. Run `npm install`
1. Modify `src/scss/styles.scss` with your SASS code and `src/index.html` with the HTML you want to show
1. Run `gulp style`, this will create the CSS file
1. Run `gulp watch`, this will open http://localhost:3000/ with the HTML and all your SCSS changes

## Packages

1. [Browsersync](https://www.npmjs.com/package/browser-sync)
1. [Gulp](https://www.npmjs.com/package/gulp)
1. [gulp-sass](https://www.npmjs.com/package/gulp-sass)