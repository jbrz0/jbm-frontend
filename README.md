# JBM Frontend Setup

## Dependencies:
```
Local Development:
'gulp'
'gulp-utils'
'gulp-webserver'
`gulp-sass`

Production:
'bootstrap'
'jQuery'
'jQuery UI'
'jQuery dataTables'
```

## Installation
1. install gulp globally: `npm install --global gulp`
2. clone repo
3. cd into repo
4. run `npm install`
5. run `gulp`

## Sass stylesheets
- @import all `.scss` files in `style.scss`
- All changes saved to `style.scss` and other `.scss` files get compiled to `style.css` in `css` folder

## jQuery Imports
- Load all global js files from `/app/js/main/` into `/app/js/index.js`
