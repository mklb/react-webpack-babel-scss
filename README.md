# React Webpack Babel Scss Boilerplate / Starter App
A react app with an development environment (Webpack), using Babel and SCSS.

## Dependencies:

```
npm install
npm i webpack-dev-server webpack -g
```

## Structure
```
/components - all components (.jsx) files
/public - generated site
/scss - all scss files
  _base.scss - some css resets, basic font styling, box-sizing: border-box, 3 classes: .clearfix, .wrapper, .wrapper-large (fullscreen)
  _styles.scss - default required empty file for your styles
  main.scss - variables and imports, mobile first media queries
```

## Development
Run development server: `npm run dev` -> `http://localhost:8080/`

## Build ReactJS App for production
`npm run build` -> /public contains the generated site