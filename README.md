# Pug + Sass Template

## Environment

- Node v12.18.2
- NPM 6.14.5
- Webpack 4.43

## Getting Started

- Install all packages

```
npm install
```

- Start to Development

```
npm start
```

- Build Static Files

```
npm run build
```

## Folder Structure

```
.
├── README.md
├── package-lock.json
├── package.json
├── src
│   ├── assets
│   ├── css
│   ├── images
│   ├── js
│   ├── pug
│   └── sass
└── webpack.config.js
```

All files are in the src folder, it includes `assest`, `css`, `images`, `js`, `sass` and `pug` folders.

- **assets** : some static files, e.g. fonts, svg ...etc.
- **images** : you can put your jpg, png or gif files here
- **css** : some external css files
- **js** : entry point `index.js` is here, and you also can put other customize js files
- **pug** : pug template files, you can use a different layout for extends

And `webpack.config.js` is webpack 4.x config setting, to handle Pug + Sass into HTML files.
