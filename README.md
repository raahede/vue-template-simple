# vue-template-simple
Get started working with Vue.js without a build setup. 

This boilerplate is based on Vue's own [simple boilerplate](https://github.com/vuejs-templates/simple), and is meant for simple proof-of-concept work, or getting familiar with Vue.js. For proper app development, I recommend a build setup. Have a look at [Vue's official templates](https://github.com/vuejs-templates).

### 1. Clone or download this repository
All you really need is the `index.html` file.

```zsh
git clone https://github.com/raahede/vue-template-simple.git
cd vue-template-simple
```

### 2. Run local server
You can open the `index.html` file in the browser, but then you can't use ajax requests in local development.

I recommend a module like [live-server](https://www.npmjs.com/package/live-server):

```zsh
# install globally
npm install -g live-server
# run server
live-server
```
> You may need to run installation as admin `sudo npm install -g live-server`
