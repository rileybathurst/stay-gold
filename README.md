# Stay Gold
A base webpack setup build to my needs as much as possible from [webpack.js.org](https://webpack.js.org/guides/getting-started/)

## Setup
```bash
mkdir stay-gold
cd stay-gold
npm init -y
git init
npm install webpack webpack-cli --save-dev
```

I'm using [github desktop](https://desktop.github.com) as it get's around the 2FA easier than $ git push.
Drag the folder down to the dock icon.

```bash
touch index.html
mkdir src
touch src/index.html
```

[index.html](index.html)
`<!doctype html>
<html>
  <head>
    <title>Getting Started</title>
    <script src="https://unpkg.com/lodash@4.16.6"></script>
  </head>
  <body>
    <script src="./src/index.js"></script>
  </body>
</html>
`
