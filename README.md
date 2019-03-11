<div align="center">
    <div clear="both">
    <a href="#"><img alt="Webpack logo" src="https://raw.githubusercontent.com/Serj190336/webpack-react-eslint-kit/master/src/images/webpack.png" float="left";></a>
    <a href="#"><img alt="React logo" src="https://raw.githubusercontent.com/Serj190336/webpack-react-eslint-kit/master/src/images/react.png" float="left";></a>
    <a href="#"><img alt="Babel logo" src="https://raw.githubusercontent.com/Serj190336/webpack-react-eslint-kit/master/src/images/babel.png" float="left";></a>
    </div>
    <div clear="both">
    <a href="#"><img alt="SASS logo" src="https://raw.githubusercontent.com/Serj190336/webpack-react-eslint-kit/master/src/images/sass.png" float="left";></a>
    <a href="#"><img alt="ESlint logo" src="https://raw.githubusercontent.com/Serj190336/webpack-react-eslint-kit/master/src/images/eslint.png" float="left";></a>
    </div>
</div>

# Webpack React ESLint starter kit

Lightweigth kit with basic features for frontend development, including ESLint with React and ES6+ support

### Installation

```
npm install
```

### Start Dev Server

```
npm run start
```

### Build Prod Version

```
npm run build
```

### Features:

- React
- ES6+ Support via Babel v7
- SASS Support
- ESLint for React and ES6+
- [Autoprefixer](https://www.npmjs.com/package/eslint-config-react-app "Autoprefixer") plugin to parse CSS and add vendor prefixes to CSS rules using values from [Can I Use](https://caniuse.com/ "Can I Use website")
- Different webpack settings that are needed for Development and Production

### Development Features:

- ESLint (React and ES6+) for IDE console by using [eslint-config-react-app](https://www.npmjs.com/package/eslint-config-react-app "eslint-config-react-app")
- ESLint (React and ES6+) for browser console by using [eslint-loader](https://github.com/webpack-contrib/eslint-loader "eslint-loader")
- Auto reload page on changes to any HTML/CSS/SCSS/SASS/JS files

### Production Features:

- On <b>build</b> script command, <b>dist</b> folder will be automaticly removed before buulding new Production version
- Final CSS file will be compiled and compressed
