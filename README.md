# Stay Gold

A base webpack setup build to my needs as much as possible from [webpack.js.org](https://webpack.js.org/guides/getting-started/) and [Material Design](https://material.io/develop/web/docs/getting-started/)

## Terminal

```bash
GOLD="stay-gold-project"
cd sites
mkdir $GOLD
cd $GOLD
npm init -y
git init
mkdir src dist
touch .gitignore index.html README.md webpack.config.js src/app.scss src/app.js
npm install webpack webpack-cli webpack-dev-server css-loader sass-loader node-sass extract-loader file-loader autoprefixer postcss-loader @babel/core @babel/cli @babel/preset-env babel-loader --save-dev
npm install --save lodash

```

```bash

npm start
npm run build
```
