[Documentation](https://emilo9.github.io/GSCL/) | [NPM]() | [Testing](https://stackblitz.com/edit/vue-psxzbw?file=src%2FApp.vue)

main.js
```
const { createApp } = require('vue');
import App from "./App.vue";

import GSCL from "gscl";
import 'gscl/dist/style.css'


createApp(App).use(GSCL).mount("#app");
```
App.vue
```
<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <GSCLButton/>
  </div>
</template>
```
