# Getting Started with Create React App

```
 npx create-react-app landing_page_sp
 yarn
 yarn start
```

open [localhost](http://localhost:3000/)

Install gh-pages

```
npm install gh-pages --save-dev
```

Config:
package.json

```json
"homepage":"https://alexlevn.github.io/lp_et_harum_quidem",
```

add commands

```json
"scripts": {
  //...
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build",
  //...
}
```

Test

```
npm run deploy
```

the "public" folder will be created.
