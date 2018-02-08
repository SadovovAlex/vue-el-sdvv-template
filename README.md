# Vue-Element-Template
#### Demo: 


## Includes:

- [Element](http://element.eleme.io/#/en-US) and normalize.css
- [Vue -v 2.1](https://vuejs.org/) & Vue-router
- [Vuex](https://github.com/vuejs/vuex) & Vuex-router-sync
- [Fetch polyfill](https://www.npmjs.com/package/whatwg-fetch)
- [Webpack](https://webpack.github.io/)
- [TestCafe](https://testcafe.devexpress.com/) for testing
- Eslint, Babel (stage-0)

## Out-of-box:
### (theme color is purple, but you can use your own color, more info below)

## Folder structure:

```
app
├── build // webpack config files
├── client - Your App
│   └── components - your components
│   ├── router - routing
│   ├── store - Vuex store
│   ├── styles - styles folder with scss vars, mixins, etc.
│   ├── views - your pages
│   ├── app.js - import dependencies and App component
│   ├── index.js - main file
│   ├── pwa.js - for PWA apps
├── dist - build.
├── static - static assets, etc.
├── tests - Your tests
├── theme - Element UI generated theme
```

Template built based on [vue-element-starter](https://github.com/Metnew/vue-element-starter)

## To start:

```bash
 git clone https://github.com/SadovovAlex/vue-element-template.git my-vue-project  
 cd my-vue-project 
 in Linux rm -rf .git
 in Windows del .git

 npm install
 npm run generate_default_styles # run this command to generate default_styles for Element-theme
```

[Element-theme](https://www.npmjs.com/package/element-theme) generates default styles. Just **change primary-color** in `./client/element-variables.css` and run:

```bash
 npm run generate_theme
```

Now app is ready and you can run it with:

```bash
 npm run dev
```

Make production build:

```bash
 npm run build
```

### Also
PRs, issues, questions, \<something-another> are always welcome.     
Feel free to contact me (or add new issue).

### Author
Sadovov Alex <aasdvv@gmail.com>

### LICENSE
MIT
