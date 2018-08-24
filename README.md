# Webpack 4 Quick Start Project

This quick start sample project is prepared by following this tutorial : 
https://www.valentinog.com/blog/webpack-tutorial/

Move into directory and run : 
```bash 
$ npm i && npm run start
```

To change entry point use output flag in `package.json` under scripts :

```json
"scripts": {
  "dev": "webpack --mode development ./foo/src/js/index.js --output ./foo/main.js",
  "build": "webpack --mode production ./foo/src/js/index.js --output ./foo/main.js"
}
```

