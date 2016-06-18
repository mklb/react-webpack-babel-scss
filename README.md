# react webpack babel scss

## Dependencies:

```
npm install
npm i webpack-dev-server webpack -g
```

## Structure
```
/components - all components (.jsx) files
/public - generated site
/scss - the css file
  _base.scss - some css resets, basic font styling, box-sizing: border-box, 3 classes: .clearfix, .wrapper, .wrapper-large (fullscreen)
  _styles.scss - default required empty file for your styles
  main.scss - variables and imports, mobile first media querie
```

## Development
Run development server: `npm run dev` -> `http://localhost:8080/`

## Production
`npm run build` -> /public contains the generated site