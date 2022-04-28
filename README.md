# Getting Started with Create React App

## 1. Start with Github Page

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

"lp_et_harum_quidem" : the name of the repo on github

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

```bash
git add .
git commit -m'lorem comments'
git push
```

open the [home page](https://alexlevn.github.io/lp_et_harum_quidem/)

## 2. Top Menu

## 3. Common Block

### 3.1

### 3.2

### 3.3

## 4. Scroll

Ref: [link](https://viblo.asia/p/deploy-ung-dung-reactjs-len-github-pages-1VgZvw3MlAw)