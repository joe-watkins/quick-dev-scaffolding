# Quick Front-end Dev Scaffolding
This project is for creating a quick dev environment. It's not a framework but gives you Sass, JS linting & Uglify for quick and dirty dev.

## Setup
1. `npm install` - installs goodies
2. `npm run setup` - will build the environment + launch server
3. `npm run dev` - will watch Sass, JS, and run a live-server
4. `npm run uglify-js` - will build a minified version of JS to `javascripts/dist/`

## Folder Structure
```
.jscsrc
|-- javascripts
    |-- main.js
|-- scss
    |-- main.scss
|-- styles
    |-- main.css
index.html
```

## Configuration
Visit the `package.json` file to tweak setup. Look for the `scripts` property.
